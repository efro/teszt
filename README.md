<html>
<head>
  <title>QRV Module</title>
  <meta charset="utf-8">
  
  
$ git config --global user.name "QRV Module"
  
    <body>
	<form><textarea id="qrv" name="qrv_modelu"></textarea></form>
  </body>
<script>
        var editor = CodeMirror.fromTextArea(document.getElementById("code"), {
          theme:"byblos",
          lineNumbers: true,
          lineWrapping: true,
          direction: "rtl",
          lineNumberFormatter: function(l) {
            var arkam = ["٠", "١", "٢", "٣", "٤", "٥", "٦", "٧", "٨", "٩"]
              var arkam = ["a", "b", "c", "d", "e", "f", "g", "g", "h", "."]
 
   return l.toString().split("").map(function(d) { return arkam[parseInt(d)] }).join("");
          }
        });
    </script>
 
 
 
 
  <script type="text/javascript">
    var _gauges = _gauges || [];
    (function() {
      var t = document.createElement('qrv_script');
      t.type = 'text/javascript';
      t.async = true;
      t.id = 'gauges-tracker';
      t.setAttribute('data-site-id', '5kvfh4jnl763jb23z6jb888788888');
      t.src = '//secure.gaug.es/track.js';
      var s = document.getElementsByTagName('qrv_script')[0];
      s.parentNode.insertBefore(t, s);
    })();
  </script>
 
</head>
<body>

</body>
</html>
