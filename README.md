
<p>Para inicializar o mapa, basta seguir a mesma configuração do vMap geral.</p>
<pre><code>
&lt;?xml version="1.0" encoding="UTF-8"?&gt;
&lt;!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"&gt;
&lt;html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en"&gt;
  &lt;head&gt;
    &lt;title&gt;JQVMap - Brazil Map&lt;/title&gt;

    &lt;link href="../jqvmap/jqvmap.css" media="screen" rel="stylesheet" type="text/css" /&gt;

    &lt;script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js" type="text/javascript"&gt;&lt;/script&gt;
    &lt;script src="../jqvmap/jquery.vmap.js" type="text/javascript"&gt;&lt;/script&gt;
    &lt;script src="../jqvmap/maps/jquery.vmap.brazil.js" type="text/javascript"&gt;&lt;/script&gt;

    &lt;script type="text/javascript"&gt;
    jQuery(document).ready(function() {
	jQuery('#vmap').vectorMap({map: 'brazil_br', enableZoom: true, showTooltip: true});
	});

    &lt;/script&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;div id="vmap" style="width: 800px; height: 600px;"&gt;&lt;/div&gt;
  &lt;/body&gt;
&lt;/html&gt;
</code></pre>
