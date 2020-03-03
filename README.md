# cordova-plugin-nlbarcodescanner

# BarcodeScannerPlugin
Cordova plugin to interface with NLSCAN barcode scanners (on Android)
This is a cordova plugin for U9000 - Newland 2DEM3090.

# How to install


`   
    console.log( "register didShow received!" );

    var listener = function( e ) {
      //log: didShow received! userInfo: {"data":"test"}
      console.log( "didShow received! userInfo: " + JSON.stringify(e)  );
    }

    window.broadcaster.addEventListener( "didShow", listener);    console.log( "register didShow received!" );

    var listener = function( e ) {
      //log: didShow received! userInfo: {"data":"test"}
      console.log( "didShow received! userInfo: " + JSON.stringify(e)  );
    }

    window.broadcaster.addEventListener( "didShow", listener);
`


# JS API
Aftere install BarcodeScanner plugin,you can use the following JS API to get scanning result or change scanner setting.
                                                        
# Dependency
cordova-plugin-broadcaster
https://github.com/bsorrentino/cordova-broadcaster                                                        
