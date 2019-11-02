# Password-checker

Script allows you to check if your password have ever been hacked. To do so, it is using pwnedpasswords API. You don't put your password into the browser and send the request somewhere, but instead you are only sending first 5 characters of your password's hash to get matched results. After that, comparison is done locally on your machine.