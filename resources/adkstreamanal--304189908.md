# adkstreamanal/subscriptions/275ddf79-b240-44e7-9916-f24175b451b1/resourceGroups/adklaketest/providers/Microsoft.StreamAnalytics/streamingjobs/adkstreamanal
![Cloudockit](../assets/8a249bdc2f99409db5edf76392daa29e.jpg) 
## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAEbSURBVDhPY6AaiNl5gdti9jEVXNhxwRHl0FWrmKHKcQOb2ceuW8w89h8ftpt9bD5UOW5gOfNoCRBX4MM2s0+UlW64zlu//z8LOv7//z8j2KDIrTe/R2279Z9cHLv99nmwQRFAgyKBAuRikH6iDIradvND3M7be7DJgTDRBqXsvh0Xs/3WA2xyIEyUQXE7bq/N339fARiOV4D8J+jyIEzQoOhtt17kHrolClYEBLE7bq/Gpo6gQQk77yxM2307vPTIa96U3ffisKkBYYIGgXD09lvvCo89UonafvMjNnkQJsqguO23VsTuuHUImxwME2UQMLYeYhNHxnCDYrbduoFNAbEYaNlNsEFZ+1/yFO9/pEMuBukHGzTIAAMDAIs9h2ek8wvrAAAAAElFTkSuQmCC) Settings


| Name | adkstreamanal  |
| --- | --- |
| Location | East US 2  |
| Job State | Stopped  |
| Sku Name | Standard  |
| Events Late Arrival Max Delay (sec) | 5  |
| Events Out Of Order Max Delay (sec) | 0  |
| Events Out Of Order Policy | Adjust  |
| Output Error Policy | Stop  |
| Output Start Mode | JobStartTime  |
| Output Start Time | 5/25/2017 7:37:25 PM  |
| Last Output Event Time | 5/25/2017 7:43:33 PM  |


## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAADOSURBVDhPYxj8YMGChSdIwYsXL5aBakUFCxYu+k8KXrRokQpUKyoASc5fsGgHlIsTLFi0qHFgDKp371do8JjeWhjSywkVAgOCBmED9R4zNjR4zvjfG7ISbhhWgypspgnWe0yNwYcbPGZ8AxkWb1/PAdKD1aAmzxm6DZ7Tf+HHM/6DcKvrHB2QHrK8VuHcJgwypN57GtgQECAc2AsWXp6/cNEMKJeh2W2eLMiQWo+pplAhMCBsEFBy8KUjUjBOgxYCw4cUDDRIDKp1UAEGBgBuPTnhRAXLDAAAAABJRU5ErkJggg==) Inputs
The following inputs are defined :
- adkhubinput (adkeventhub - Microsoft.ServiceBus/EventHub - Json)

- therefdata (adkdev - Microsoft.Storage/Blob - Json)


## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAACySURBVDhPYxh8YMGChSdIwgsX74JqRQULFi76TyJ+C9WKCmAKZs6cyQoVwgkGn0ELFy5aPH/hohkhm29KR265+T9qy800qBRpBiGD8K131UCGRWy5EQMWwGUQSBGxOHzTDWeyXQQCEVtuvgHi12AOuQYBvXQjYvONDwz//zOCBUgxCKr2bcjKK0Jhm6/phK5axQyVIs8gKBcVUN0gEjB2g4CJbAYpeP7ChX1QrYMaMDAAAEDnPhHkDN8MAAAAAElFTkSuQmCC) Outputs
The following outputs are defined :
- datalakeout ( -  - Json)

- outputeventhub (adkeventhub - Microsoft.ServiceBus/EventHub - Json)

- servicebusqueue (SelectWinesMsg-ns - Microsoft.ServiceBus/Queue - Json)

- servicebustopic (SelectWinesMsg-ns - Microsoft.ServiceBus/Topic - Json)

- theblobstorage (adkdev - Microsoft.Storage/Blob - Json)








## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAKDSURBVDhPfZTPTxNBHMUHkaJ02wDdmWkTDwYtYqHxwIk/wejFRLyZqBdjvOjZaKMJ7I8KamKCnEyARoqRIhzb3VniBWu7LYSkIXrgohe4aCEUiqyz22mZQuUlL9udfe/T73ZnCxppcAY0DxsdAxKB06qOfn3K9m5/+NaTjn29MBCJgFMsdrJkIj6N6v7iy8WAVbHfWli5UnNiObwVz/U8ZvHjerPU6ZUJzkSNgFXvelDVs9lQciR+7iyrHypq4MLhFLwbg2zH06EVVq9I0tEzfgqVBCxZgwVJ8z2IEtw3ZXZd/Zi9/DyRC28chU2lu287EPuHVXS8zUNUHU9ECDjtBDjFvoQ75nK9azxoPhf+M2MNNgPJaA/XTaOj7zxEEASRHmrnb1dDAi3/5WGxdLALKATO1YEW4UPWsUU5gul2uxfYuaPZTGiaB8Uzl0aApMEtHjREfD0sD1wuV9Dj8ay2tbUF2JKjyaWL93hQwuydAqombvKgFwYKs7ytJq/Xe4tOtUY/t1SWACjn2q/tLyOr6lK+fRwoGpzkH7esoycsD1pbW89TyDqdKsmWHO1lfXEetJfz3QeK4QnyE9H99DNCoMA6gN6Wv7+/vzaNlRHEvWWxXIWU8+igmMeIXgFNioY3eJhKcDbyHpxh3ZqGUggXTfEHP005L65blOEEpBS8w4NsKzosybo4phB8XSbwpqTjz/QL9kcNuLtjdpaqoN18R58DqYq+6bGjsP95zIC/d0yxVDZ9r1j9UOMZ0KLoaL5RsZEnDBSht9TM6sclGeiGauDNKAkcHC3T1+dA1lBhOCl2s/jJsv+8RhfFgJxCj+j2eKcS+DpK4N2hlBvbD4fFOAHwD6eN8YGiac9WAAAAAElFTkSuQmCC) Billing
![]() Total cost : 
