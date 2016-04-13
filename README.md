#  Polar Cape Cordova Plugin WiFi Connect

## Install

    npm install -g polarcape-cordova-plugin-wifi-connect

## Example

Test on Cordova 3.4.0

```javascript
    
    var args = [{"SSID":"Goran's iPhone"}];
    window.wifiConnect(function(data){
        console.log(data);
    },args);


License - The MIT License
