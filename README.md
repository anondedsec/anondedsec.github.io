<html>
<style>
	.class1 { shape-outside: url(data:image/gif;base64,R0lGODlhEAAQAMQAAORHHOVSKudfOulrSOp3WOyDZu6QdvCchPGolfO0o/XBs/fNwfjZ0frl3/zy7////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAkAABAALAAAAAAQABAAAAVVICSOZGlCQAosJ6mu7fiyZeKqNKToQGDsM8hBADgUXoGAiqhSvp5QAnQKGIgUhwFUYLCVDFCrKUE1lBavAViFIDlTImbKC5Gm2hB0SlBCBMQiB0UjIQA7); }
	msub::first-line { background-image: cross-fade(url(abc), url(data:image/gif;base64,R0lGODlhEAAQAMQAAORHHOVSKudfOulrSOp3WOyDZu6QdvCchPGolfO0o/XBs/fNwfjZ0frl3/zy7////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAkAABAALAAAAAAQABAAAAVVICSOZGlCQAosJ6mu7fiyZeKqNKToQGDsM8hBADgUXoGAiqhSvp5QAnQKGIgUhwFUYLCVDFCrKUE1lBavAViFIDlTImbKC5Gm2hB0SlBCBMQiB0UjIQA7), 50%);  }
</style>
<script>
	function trigger() {
		document.getElementsByTagName("style")[0].appendChild(document.createElement("a")); 
		setTimeout( () => {
			msubEle.prepend("1");
			mathEle.focus() // This can be a few different calls. setSelectionRange also worked
			mathEle.remove();
		}, 0);
	}
</script>
<body onload=trigger()>
	<math id="mathEle" class="class1">
		<msub id="msubEle">
			<mi></mi>
		</msub>
	</math>
</body>
</html>
