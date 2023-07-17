<h1 align="center">FAQ | Azion Technologies</h1>
<p align="center">
    <img src="static/images/cover.png" width="600px" />
</p>
<p align="center">
    <a target="_blank" href="https://www.azion.com/en/documentation/products/getting-started/" title="Azion Documentation | Getting Started">Azion Documentation | Getting Started</a>
    <br />
    Frequently Azion Asked Questions to help the process to simplify the knowldge os Azion Edge Platform.
</p>

<br />

## QUESTIONS AND ANSWERS
### 1. Why is my Azion's Edge Function returning 403 HTTP Status?

To be able to send POST HTTP Requests you need to have Application Acceleration enabled.

### 2. Why can't I modify the Rules Engine criteria?

To be able to modify the rules engine criteria you need to have Application Acceleration enabled.
With that you will be able to select:

- ${arg_}
- ${args}
- ${cookie_}
- ${device_group}
- ${domain}
- ${geoip_city_continent_code}
- ${geoip_city_country_code}
- ${geoip_city_country_name}
- ${geoip_city}
- ${geoip_continent_code}
- ${geoip_country_code}
- ${geoip_country_name}
- ${geoip_region_name}
- ${geoip_region}
- ${host}
- ${http_}
- ${remote_addr}
- ${remote_port}
- ${remote_user}
- ${remote_port}
- ${remote_user}
- ${request_body}
- ${request_uri}
- ${request}
- ${scheme}
- ${uri}

### 3. Can you give me example of Azion Edge Functions?
To easly support you to create a new Azion Edge functions, just pick the best sample for you code in the following Github repository.
https://github.com/aziontech/azion-samples
