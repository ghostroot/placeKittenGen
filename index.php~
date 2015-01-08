<html>
<head>
<title>Placekitten Generator</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="style.css">
<script src="https://code.jquery.com/jquery-1.11.2.min.js"></script>

</head>
<body>
<script>
$(document).ready(function() {
            $(document).scroll(function() {
                if ((window.pageYOffset + window.innerHeight) >= $(this).height() - 80) {
                    var str=$('.row').html();
                    $('.more').append(str);
                }
            }).scroll();
        });
               
</script>

<div class="container">
<div class="row">

	<?php for($i=0;$i<40;++$i){?>

<img class="kittens" src="http://placekitten.com/g/<?php echo rand(200,600); ?>/<?php echo rand(200,500);?>/">
  <?php }?>
<div class="more">
</div>
</div>

</div>



<script>
$(document).ready(function() {
  $( ".kittens" ).fadeIn(4500);
});
</script>
</body>
</html>
