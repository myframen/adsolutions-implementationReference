# Using the Beta environment for display Ads

In order to use our Beta environment you should only redirect the AdLib request **from** the global Appnexus CDN **to** the Ad Solutions development server.

From `https://www.asadcdn.com/adlib/*`

--> to `https://www.asadcdn.com/adlib/beta/$1`

## How to redirect the requests?

We recommend to use the Chrome browser Plugin [Redirector](https://chrome.google.com/webstore/detail/redirector/ocgpenflpmgnfapjedencafcfakcekcd)

### Settings for Redirector:

![Settings for Redirector](https://github.com/spring-media/adsolutions-implementationReference/blob/master/assets/redirectorBeta.png?raw=true?raw=true)

**You can also use Charles Proxy, Wireshark or whatever you like most as alternative.**

If you have some question don't hesitate to contact us:


__Carlos Bracho__
 
  Head of Ad Technology
  SPRING
  
  Tel: +49 30 2591 76784
  Mobile: +49 151 44619807 
  carlos.bracho@axelspringer.de

__Ad Technology Team__
  adtechnology@axelspringer.de
  
