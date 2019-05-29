# Login Endpoint Documentation

* Endpoint address: https://www.fedex.com/fcl/logon.do

* HTTP method: POST
* Encoding: HTTP form

## Required fields

* `username` 

  > FedEx account username

* `password` 

  >  FedEx account password

* `appName`

  > The application to login to, only one value is permissible

  * Example value: `fclfsm`

* `locale`

  > Website locale

  * Example value: `us_en`

* `afterwardsURL`

  > Redirect URL after successful login, this will allow any URL and is probably a security vulnerability

  * Example value: `https://www.fedex.com/shipping/shipEntryAction.do?method=doEntry&link=1&locale=en_US&urlparams=us&sType=F`

## Optional fields

* `cc_lang`

  > Website language

  * Example value: `us`

* `registrationType`

  > Action type, does not appear to be used in any way

  * Example value: `logon`

* `ssoguest`

  > Integration with single sign-on

  * Example value: `n`

* `login`

  > Action type, does not appear to be used in any way

  * Example value: `Login`

