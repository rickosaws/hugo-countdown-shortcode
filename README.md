# hugo-countdown-shotcode
Javascript Countdown timer shortcode for HUGO generated sites.


### Installation
Simply copy the shortcode and JS into the respective HUGO folders and your done. Im using the Learn theme so the files are relative to that theme. 

### Usage
The Shortcode uses the {{ countdown `int`}} short code followed by an  INTEGER value representing the mins to countdown from.

```e.g {{ countdown 15 }} for a 15min Countdown.```

To use simply add the shortcode {{ countdown 15 }} in your page. 

The default start message displayed can also be updated by modifying the `countdown.html` and updating the following line;

```<h3 id="headline">Great Work Everyone!. Lets take a Break!</h1>```

The default end message displayed can also be updated by modifying the `countdown.js` and updating the following line;

```headline.innerText = "Lets get back to it!";```


#### TODO
+ Handle exceptions e.g (non integer values)
+ Extend the shortcode parameters to allow passing start and end greeting to overrides to the defaults.
+ 

