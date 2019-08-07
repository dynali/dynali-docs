all status codes
================

| code | state   | message                                                     |
|------|---------|-------------------------------------------------------------|
| -1   | error   | 'Invalid input data: could not parse json input.'           |
| -2   | error   | 'Invalid input data: missing action.'                       |
| -3   | error   | 'Invalid input data: unknown action.'                       |
| -980 | error   | 'Critical error on Dynali side.'                            |
| -981 | error   | 'Critical error on Dynali side.'                            |
| -982 | error   | 'Critical error on Dynali side.'                            |
| 101  | error   | 'Missing authorization data.'                               |
| 102  | error   | 'Missing hostname.'                                         |
| 103  | error   | 'Missing IP.'                                               |
| 104  | error   | 'Invalid IP.'                                               |
| 105  | error   | 'Missing new password.'                                     |
| 109  | error   | 'New password must be a Md5-hashed string.'                 |
| 899  | error   | 'DynAli Internal problems: database failure. We are on it!' |
| 900  | error   | 'DynAli Internal problems: database failure. We are on it!' |
| 105  | error   | 'Hostname not registered.'                                  |
| 106  | error   | 'Domain has been blocked due to abuse.'                     |
| 107  | error   | 'Domain is expired. Please renew.'                          |
| 108  | error   | 'Invalid authorization data.'                               |
| 200  | success | 'Okay.'                                                     |
| 201  | success | 'Update not required: same IP.'                             |