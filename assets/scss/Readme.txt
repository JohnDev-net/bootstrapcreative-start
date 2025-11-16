The .scss (Sass) files are only available in the pro version.
You can buy it from: https://bootstrapmade.com/enno-free-simple-bootstrap-template/

<?php
$file = 'counter.txt';
$count = (int) file_get_contents($file);
$count++;
file_put_contents($file, $count);
?>
Anda pengunjung ke: <?= $count ?>
