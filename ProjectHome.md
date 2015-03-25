# Overview #
During user input field, this plugin controls the format of IPv4 or IPv6 addresses.

# Examples #
```
$(function(){
    $('.ipv4').ipAddress();
    $('.ipv6').ipAddress({v:6});
});

//mask input type text (ipv4) : ___.___.___.___
//mask input type text (ipv6) : ____:____:____:____:____:____:____:____

```

Helpers in Javascript :
```
...
var myip = '192.168.1.1';
if(myip.isIpv4()) { // or myip.isIpv6()
    return true;
} else {
    return false;
}
...
```