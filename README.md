# API Guide

## Base URL(s)

> Multiple domain does not mean they are backwards compatible, it is available on all of them, nor does it have a full functionality. Generally speaking, /v2 has more advanced features but requires a more stricter usages. Copy the entire url endpoint that you want to use.

- Base Domain - https://api.dani-dev.co.za/
- v1 Services - https://api.dani-dev.co.za/v1/
- v2 Services - https://api.dani-dev.co.za/v2/

## Services

| Base | v1  | v2 |
|:-------------:|:-------------: |:-------------:|
| /lyrics | ✔ | ✘ |
| /music | ✘ | ✔ |
| /stream | ✔ | ✔ |
| /transport | ✘ | ✔ |
| /utilities/weather | ✔ | ✘ |

## Notes

###### 1. This API is free to use and will not be rate-limited (unless forced to) due to nature of live/real-time fetching.
###### 2. All data returned by the API are fetched directly from the providers server.
###### 3. Some JSON data will be automatically cached to the Cloudflare Workers KV to reduce latency.
###### 4. Visiting some endpoints might return helpful text to guide on properly interact with the API.
###### 5. There will be endpoints that does not exist in the text files but are shown in the API response, because they are in development or experimental so expect fail/error when doing so.
###### 6. All endpoints that requires authentication are strictly optional as the API handles the internal secrets and passing your own authentication data is currently in experimental mode.
###### 7. This API may be geo-blocked and requires a Malaysian IP to have a 100% guaranteed response.
