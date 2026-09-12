# API Guide

## Base URL(s)

> Multiple domain does not mean they are backwards compatible nor it is available on all of them. Copy the entire url endpoint that you want to use.

- Base Domain - https://api.dani-dev.co.za/
- v1 Services - https://api.dani-dev.co.za/v1/
- v2 Services - https://api.dani-dev.co.za/v2/

## Services

| Base | v1  | v2 |
|:-------------:|:-------------: |:-------------:|
| /lyrics | ✔ | ✘ |
| /stream | ✔ | ✘ |
| /transport | ✘ | ✔ |

## Notes

###### 1. This API is free to use and will not be rate-limited (unless forced to) due to nature of live/real-time fetching.
###### 2. All data returned by the API are fetched directly from the providers server.
###### 3. Some JSON data will be automatically cached to the Cloudflare Workers KV to reduce latency.
###### 4. Visiting some endpoints might return helpful text to guide on properly interact with the API.
###### 5. There will be endpoints that does not exist in the text files but are shown in the API response, because they are in development or experimental so expect fail/error when doing so.