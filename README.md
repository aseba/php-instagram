#PHPIRT
## PHP Instagram Real Time api implementation

###Disclaimer
This an in ultra-alpha library, but it works. It's just a piece of code I've created to play along with the Instagram Real Time API

In order to use this library you will need to set it somewhere where the `callback.php` file can be accessible by instagram servers

`test.php` file has an example on usage for the basic subscriptions calls

To configure the callback usage you must create a new class extending `SubscriptionProcessor` in `phpirt.php` file and redefine the `public static function process($data){}` function.