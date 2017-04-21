# HANGAM WSEI

## Cel aplikacji:

Gra powstała z myślą o fanach serialu telewizyjnego "Gra o Tron" oraz wszystkich osób lubiących tego typu gry. Gra pełni także funkcję edukacyjną ponieważ ciekawe i oryginalne hasła, które gracz musi odgadnąć, pozwalają poszerzyć zasób słownictwa.

## Opis:

Gra jest odmianą popularnej gry Wisielec. W tym wydaniu oferujemy graczowi możliwość uratowania bohatera serialu „Gra o tron”. Zadaniem gracza jest odgadnięcie hasła dzięki czemu bohater serialu nie staci życia. 


## Twórcy:

Bartosz Pieczara (team menager)

    Email: 
    
    Facebook: https://facebook.com/bartek.pieczara.7

Mateusz Dudłak

    Email: mateusz.dudlak@gmail.com
    
    Facebook: https://facebook.com/dudlakmateusz

## info
zapraszamy na stronę [wiki][Wiki] 

###
copyright: WSEI 2017




## Usage

#### PhoneGap CLI

The hello-world template is the default when you create a new application using the [phonegap-cli][phonegap-cli-url].

    phonegap create my-app

Create an app using this template specifically:

    phonegap create my-app --template hello-world

To see a list of other available PhoneGap templates:

    phonegap template list

## [config.xml][config-xml]

#### android-minSdkVersion (Android only)

Minimum SDK version supported on the target device. Maximum version is blank by default.

This template sets the minimum to `14`.

    <preference name="android-minSdkVersion" value="14" />

#### &lt;access ...&gt; (All)

This template defaults to wide open access.

    <access origin="*" />

It is strongly encouraged that you restrict access to external resources in your application before releasing to production.

For more information on whitelist configuration, see the [Cordova Whitelist Guide][cordova-whitelist-guide] and the [Cordova Whitelist Plugin documentation][cordova-plugin-whitelist]

## [www/index.html][index-html]

#### Content Security Policy (CSP)

The default CSP is similarly open:

    <meta http-equiv="Content-Security-Policy" content="default-src * 'unsafe-inline'; style-src 'self' 'unsafe-inline'; media-src *" />

Much like the access tag above, you are strongly encouraged to use a more restrictive CSP in production.

A good starting point declaration might be:

    <meta http-equiv="Content-Security-Policy" content="default-src 'self' data: gap: 'unsafe-inline' https://ssl.gstatic.com; style-src 'self' 'unsafe-inline'; media-src *" />

For more information on the Content Security Policy, see the [section on CSP in the Cordova Whitelist Plugin documentation][cordova-plugin-whitelist-csp].

Another good resource for generating a good CSP declaration is [CSP is Awesome][csp-is-awesome]

[wiki]: https://github.com/dudlakmateusz/hangman-wsei/wiki
[phonegap-cli-url]: http://github.com/phonegap/phonegap-cli
[cordova-app]: http://github.com/apache/cordova-app-hello-world
[bithound-img]: https://www.bithound.io/github/phonegap/phonegap-app-hello-world/badges/score.svg
[bithound-url]: https://www.bithound.io/github/phonegap/phonegap-app-hello-world
[config-xml]: https://github.com/phonegap/phonegap-template-hello-world/blob/master/config.xml
[index-html]: https://github.com/phonegap/phonegap-template-hello-world/blob/master/www/index.html
[cordova-whitelist-guide]: https://cordova.apache.org/docs/en/dev/guide/appdev/whitelist/index.html
[cordova-plugin-whitelist]: http://cordova.apache.org/docs/en/latest/reference/cordova-plugin-whitelist
[cordova-plugin-whitelist-csp]: http://cordova.apache.org/docs/en/latest/reference/cordova-plugin-whitelist#content-security-policy
[csp-is-awesome]: http://cspisawesome.com
