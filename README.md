<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Neatlyst</title>

<!-- Redirección rápida -->
<script>

const android =
"https://play.google.com/store/apps/details?id=com.neatlyst.neatlystapp";

const ios =
"https://apps.apple.com/us/app/neatlyst/id1091657112";

const userAgent = navigator.userAgent || navigator.vendor || window.opera;

// iPhone / iPad
if (/iPad|iPhone|iPod/.test(userAgent) && !window.MSStream) {

    window.location.replace(ios);

}

// Android
else if (/android/i.test(userAgent)) {

    window.location.replace(android);

}

// Desktop
else {

    window.location.replace(android);

}

</script>

<style>

html,body{
    margin:0;
    background:#ffffff;
}

</style>

</head>

<body>
</body>
</html>
