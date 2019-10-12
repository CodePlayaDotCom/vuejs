# vuejs
vuejs related issues and helpful snipts


Index:

-- [IIS WebServer Config For Vuejs](iis-config-reverse-proxy) by [@github/fahamidev](https://github.com/fahamidev)

Works Together With NodeJs webserver

Description:

with this config all the traffic of your website pass through your primary port and domian: example.com/
and IIS seperate the traffic with their sub directory requested to determine which request is for vuejs and which one is for
another handler for example Laravel,Php,Yii or ... what ever which is not handled nodejs
in result you getting work interactive app using both vuejs and non nodejs backend
 

-- Non-SSR Vuejs Application Seo
Description:

According to [New Google Evergreen Bot Presentation](https://webmasters.googleblog.com/2019/05/the-new-evergreen-googlebot.html), google bots capable of rendering the page with v8 engine and you can use Vuejs non-ssr with no concerning about seo issues and page indexing
which explain that google bots can see the page like others do.
Also need to mention that although it can render your page ,You MUST use links in your page to lead bot's to correct direction, and
also SiteMap is required and better to exists
