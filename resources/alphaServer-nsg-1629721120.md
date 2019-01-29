# alphaServer-nsg/subscriptions/275ddf79-b240-44e7-9916-f24175b451b1/resourceGroups/ConcertoDev/providers/Microsoft.Network/networkSecurityGroups/alphaServer-nsg

## ![C:\Users\haido\Documents\UMAknow\CDK\Azure\Microsoft_CloudnEnterprise_Symbols_v2.7\Symbols\CnE_Cloud\PNG\Network Security Group_COLOR.png](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAKqSURBVDhPvdNZTxNRGAZgbuRGb/TCv6A/QQQiNWUVTZQlSkgkKhARZBG6QKGRJhREjQsV6IKAdI0tQoEGcWEJM620M3VoFURAlhgNxkSvldeZcTQ0bEWNb/IlM3PO9+ScnDMR2yXdGtiXaqHbs/qYvcKnP0u23b//uMVflGCilsVGColGapGF8y+GCyeZ6YR4k68r0Uy72Hoj7vKtclCanYFqbB4pFj+4d7a+JZqoyViDuydaSzxI7vCkCkRoxCa6JJ5tyHRM4mxvEGVPZqDxLWNk6Qs6mQ+ofDqL/L4pnGbHk7t8EBncONRKQNzmrhSI0HAgu0oQ77+uKw6sfjbHV+XQDCoGXvF1WEv+HahgV/kL+yegxPV656CuZxDW0Qkean7YB4ebwaXaG8i9bUZZN4Uz8gZkltei2EaEByoab6FQWoXRhU+oqFVDoqpHfS+Biv4g0i5Xocg4zD+XO5ntwXgThQs116CwPUeh+i5yJFdRNxREjlQFaVMHzpVIYaYXkCepQYO5HzE699Ygd8+yZGrIXSyi0iCjuAq5d6yQt7DbVarQ2GZEzc0mSOsa0eJwIVYfBijrZ/jTVLD3sNQ+gVKHF9ed4xieX8Ho4mc46Wl0vwjyz1uCKRaqgAOvPJ7hT1Q2OP37NPXeRR5YW4+mPvIX+4iOKBSI0KRbXx5gwe8Z9knIWXTt9dgIzO8NIKp1fDXV6D0oEOtzzExrRJ1enDL5NgVH2JINTfGrizO4m4XWjaMMIDJWTzq5ySkdEyh2BkPAgbcrON/N/NyqgRzMsAUihdbNk+f17mJ/fA3XFKMjkWWlcc/zDuqxWRxt8/CYyOBpUYaDrY24nTwRrSOWOCBKS/BQtJZcTmr3nBSm7DzZnf7dovue6hg9ORendysLbIE9wtD/SkTED0RWmclNo48mAAAAAElFTkSuQmCC) Settings


| Name | alphaServer-nsg  |
| --- | --- |
| Location | eastus  |


## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAFPSURBVDhPYyAGTLkiygNlUg4mHxaIn3JE+OeUIyL/Jh0WTIcKEwcmHRbVn3xE2GTKUcHiyYeFLk89KvIfGwbKnZ90RKiwZjeDYf0eBi2odkyATTMu3LyH5X/9LgYwhmrHBNg0YsOdBzjghpFl4LSjYv+nHRMDsyceFkAxjGQDr71Y/B8Gbr/ZgGEYSQYuPKMHNmjWcQWwC//8/fm/96A0+QauuugMNhDEbt7D/P/px9P/N1xNId/AA3dLwAauvugDdK3z/9dfb/w/+qAHaAgjeQbiAu37+IeLgcA8+wFmWPs+Nqh2TNC2j484A4GJNhtkWN8hXhQN+HDDLoZ8qHbsYMJB/hPYNGLFOxleQLXhB0CFB7AagITrdjEcgSonDtTtZKjEatBOhn9AuguqjDTQcYaBH2jAE7iBIPZ+BgGoNPkAWIjqNe5kMIdy8QAGBgAFhDcsl+dbCAAAAABJRU5ErkJggg==) Security rules


| Name | Access | Protocol | Direction | Source Address Prefix | Source Port Range | Destination Address Prefix | Destination Port Range |
| --- | --- | --- | --- | --- | --- | --- | --- |
| default-allow-rdp  | Allow  | TCP  | Inbound  | *  | *  | *  | 3389  |

## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAEkSURBVDhPnZOxSsRAEIb3EfQdfARLwS47gw8hHKgIVwhWNtkNKNeL7Gwq8T1sr7BSBBUVq0OwU7T2dC7OGe+cu1394Idk9///bIbE5FICHXiIJ97SqQe6cUCvbvV4Qbbz4OCzx/gxLYc07K2ERbHNxyMNtJJ9jMt8wjPWe28tUcamO62ktGEw2q+wxmYN4nkT0BjNYbpgQkD342ueX19ik/Dm1XcgQzyrQ4m28JNuNfM8lRDWJf5FBfFBM6bkiqMlqWgG+6iZUqqQulLRvM6bZkrK1ltSYQx/oS+qKSFXxE2paOGyJ808Sw7qjkR/U2LeoF0RZpeM4ZNda+FWtCHWNFx2qZZA3BZLPg7ixc8Svt+Rrb/jrfwmlvZk6f94DLtymcCYTxhUn7TOvHz8AAAAAElFTkSuQmCC) Tags


| Tag Key | Tag Value |
| --- | --- |
| Application  | ADKApp2  |





## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAJOSURBVDhPjZPLa9RQFIdva63iPEBn8hIs6BS1NFZE/AdEEEFwJQji1qULEVcDcaG0k3Rh3dUi0i601OcoSEXhJmOtKCNJxsE/QYtPREs1mSaeJGfa5E5a+sEPknvP+bg5Sch6DBuFo6rOT6tUWHhoykt36vusW/N9x3B7Y4w969+i6eKjUUPy43naOJjIfVOexJa1Uee4kqZLflpYYZAn9tDy1Os9PLYn0Z4LMjR67MnaSRMGqdpD3pQlZFAToTRJb5okCDz+J8iLB6b8sWofcNOl8k/FJ92og9NR8TH7iCD5myhCbr4qDYLEY6V33++9iCUgZGQqyMbHyWbc7mDy7c4CzK9DGm4O68VDrPB8PSnLZDKDeLnCPUu+wAon5kv9pEKFWUb4GXtCstlsMZ/P/4J8xaWQYByscMYcuAzzExbjQpWKs9gTksvlToCsCZc90coqrLBqyVcJzOs781ZfYn2bLhAeh/yD7MC1kJbN+/E4ZrFMVMpPx4WqLv3B+hA44UkQNSBf4LY3WiXEp6SHFbYa3GkyamzfFRcG0QxhN/aFgOwIXq7gmHyZFXrtDzw+w2iOkqfUpW3hZgp+U+pzLd5jhbgN/zAVR1gpzLKl1YQzWBKi3CZb4SVegR9h2bG5xbjMaRQPY1kECBz20dfLjZr4uy1zbe4DalapzBVyIF3qPOnamaiJ31yL++HPkE2oSRL8IVC4kHai9AjvfJ90YXs6ikK6NcqdY08TD3y77jVa2I8tG+f6G16oGPzZChXL8OIuqQZ/KhgNbqdAyH991EwL2yt2pgAAAABJRU5ErkJggg==) Billing
![]() Total cost : 
