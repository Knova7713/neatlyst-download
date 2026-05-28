<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Download Neatlyst</title>

<script>
window.onload = function() {

    var userAgent = navigator.userAgent || navigator.vendor || window.opera;

    // iOS detection
    if (/iPad|iPhone|iPod/.test(userAgent) && !window.MSStream) {

        window.location.href =
        "https://apps.apple.com/us/app/neatlyst/id1091657112";

    }

    // Android detection
    else if (/android/i.test(userAgent)) {

        window.location.href =
        "https://play.google.com/store/apps/details?id=com.neatlyst.neatlystapp";

    }

    // Desktop fallback
    else {

        window.location.href =
        "https://www.neatlyst.com/";

    }
};
</script>

</head>

<body>

<p>Redirecting...</p>

</body>
</html># neatlyst-download
