jQTagCould
================

Simple, configurable Tag Cloud in jQuery

Usage:
=======

	<div id="panel">				
		<a count="38" href="#">Horizontal</a>
		<a count="76" href="#">FullLength</a>
		<a count="14" href="#">Japan</a>
		<a count="38" href="#">Toyota Stadium</a>
		<a count="59" href="#">Toyota</a>
	</div>
	
	<script>
		$("#panel").jqTagCloud({ maxSize:30, minSize:12 });
	</script>
	
<b>maxSize</b>: Maximum font size to use
<br>
<b>minSize</b>: Minimum font size to use
<br><br>
Multiple tag clouds can be used on same page. Checkout the example file for demo:

	<script>
		$("#panel").jqTagCloud({ maxSize:30, minSize:12 });
		$("#panel2").jqTagCloud({ maxSize:35, minSize:10 });
	</script>
