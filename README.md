<!--
  KeyShotXR
  (c) Copyright 2012-2017 Luxion ApS - All Rights Reserved.
-->

<!DOCTYPE html>
<html xmlns='http://www.w3.org/1999/xhtml'>
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=Edge"/>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <title>KeyShotXR</title>
    <style type="text/css">
      body { -ms-touch-action: none; }
    </style>
    <script type="text/javascript" src="XS S M L_XR.313535915/files/KeyShotXR.js"></script>
    <script type="text/javascript">
      var keyshotXR;

      function initKeyShotXR() {
        var nameOfDiv = "KeyShotXR";
        var folderName = "XS S M L_XR.313535915";
        var viewPortWidth = 1555;
        var viewPortHeight = 875;
        var backgroundColor = "#FFFFFF";
        var uCount = 18;
        var vCount = 1;
        var uWrap = true;
        var vWrap = false;
        var uMouseSensitivity = -0.05;
        var vMouseSensitivity = 1;
        var uStartIndex = 9;
        var vStartIndex = 0;
        var minZoom = 1;
        var maxZoom = 1;
        var rotationDamping = 0.96;
        var downScaleToBrowser = true;
        var addDownScaleGUIButton = false;
        var downloadOnInteraction = false;
        var imageExtension = "jpg";
        var showLoading = true;
        var loadingIcon = "ks_logo.png"; // Set to empty string for default icon.
        var allowFullscreen = true; // Double-click in desktop browsers for fullscreen.
        var uReverse = false;
        var vReverse = false;
        var hotspots = {};
        
        keyshotXR = new keyshotXR(nameOfDiv,folderName,viewPortWidth,viewPortHeight,backgroundColor,uCount,vCount,uWrap,vWrap,uMouseSensitivity,vMouseSensitivity,uStartIndex,vStartIndex,minZoom,maxZoom,rotationDamping,downScaleToBrowser,addDownScaleGUIButton,downloadOnInteraction,imageExtension,showLoading,loadingIcon,allowFullscreen,uReverse,vReverse,hotspots);
      }

      window.onload = initKeyShotXR;
    </script>
  </head>
  <body oncontextmenu="return false;">
    <div id="KeyShotXR"></div>
  </body>
</html>
