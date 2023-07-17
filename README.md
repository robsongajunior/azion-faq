# Azion FAQ - Frequently Asked Questions

## Why my Azion Edge Functions returning 403?
To be able to send POST HTTP Requests you need to have Application Acceleration enabled.

## Why I can't modify the Rules Engine *criteria*?
To be able to modify the rules engine criteria you need to have Application Acceleration enabled. With that you will be able to
select ${arg_}, ${args}, ${cookie_}, ${device_group}, ${domain}, ${geoip_city_continent_code},${geoip_city_country_code}, ${geoip_city_country_name}, ${geoip_city}, ${geoip_continent_code}, ${geoip_country_code}, ${geoip_country_name}, ${geoip_region_name}, ${geoip_region}, ${host}, ${http_}, ${remote_addr}, ${remote_port}, ${remote_user}, ${remote_port}, ${remote_user}, ${request_body}, ${request_uri}, ${request}, ${scheme}, ${uri}
