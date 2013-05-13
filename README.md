
  <head>
    <title>JQVMap - Brazil Map</title>
    
    <link href="../jqvmap/jqvmap.css" media="screen" rel="stylesheet" type="text/css" />
    
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js" type="text/javascript"></script>
    <script src="../jqvmap/jquery.vmap.js" type="text/javascript"></script>
    <script src="../jqvmap/maps/jquery.vmap.brazil.js" type="text/javascript"></script>
    
	<script type="text/javascript">
	jQuery(document).ready(function() {
		jQuery('#vmap').vectorMap({
		    map: 'brazil_br',
		    enableZoom: true,
		    showTooltip: true
		});
	});
	</script>
  </head>


