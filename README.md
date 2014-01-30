# Twitter module for Kohanaphp

## Create Twitter app

     See https://dev.twitter.com to create you app 
    
     See https://twitter.com/settings/applications (to revoke access key and renegociate)

## Configure

    copy config file to config directory
    
    modules/koahana-twitter/config/twitter.php  >> application/config/twitter.php


## Use
    
    $twitter = new Twitter();
    
    $status = $twitter->send('my message');
    
    echo $status ? 'OK': 'ERROR';



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/madeinnordeste/kohana-twitter/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

