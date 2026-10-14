# HTTP+ Standard

## HTTP Standard -Compliant Version

All requests are to be given an `X-HttpP-Code` header, as well as an optional `S-HttpP-Reason-Phrase`.

Requests making use fo the HTTP+ Standard are to use status code 198, designated by HTTP+ as "Switching Interpretation".

Possible Http+ status codes:

| `X-HttpP-Code` | `S-HttpP-Reason-Phrase`                  |
| :------------: | :---------------------:                  |
| -1             | Internal Classified Error                |
| 0              | Unknown Error                            |
| 1              | No Access                                |
| 1.1            | No Access (R)                            |
| 1.2            | No Access (W)                            |
| 1.3            | No Access (X)                            |
| 1.4            | Classified                               |
| 2              | Illegal Content                          |
| 3              | Unavailable due to legal takedown        |
| 4              | Resource temporarily unavailable         |
| 5              | Malformed Input                          |
| 6              | Unexpected Header                        |
| 7              | Resources Exhausted                      |
| 8              | Ratelimited                              |
| 8.1            | Ratelimited based on hardware details    |
| 9              | Resource format changed                  |
