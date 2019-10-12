# vuejs
vuejs related issues and helpful snipts


Index:

-- [IIS WebServer Config For Vuejs](iis-config-reverse-proxy), Works Together With NodeJs webserver
Description:
with this config all the traffic of your website pass through your primary port and domian: example.com/
and IIS seperate the traffic with their sub directory requested to determine which request is for vuejs and which one is for
another handler for example Laravel,Php,Yii or ... what ever which is not handled nodejs
in result you getting work interactive app using both vuejs and non nodejs backend
