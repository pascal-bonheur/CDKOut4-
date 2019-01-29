# concertologic /subscriptions/275ddf79-b240-44e7-9916-f24175b451b1/resourceGroups/ConcertoDev/providers/Microsoft.Logic/workflows/concertologic


| / |
| --- |


## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAISSURBVDhPY6Aq+P//P2P9/pc8UC5RoPvCc24oEwLKz9zlj91+63bsjtvLoUJEgfiddxbGbL91K3//fQGwQOqe247R22/9rF91hQ0sAAUC1UflmQqPvWYqOvaRpfj4JagwHNTv/88Ste3mt5Sdd5zAAsk7brnG7rj1FcxBBkVHDZlLjh8FaWApPoYpDwQRW2+9SQDqB3NwGcRdc1KbsfDYB6ai4weALnoPFUYBRBkEAiaTLnq6L7/6RKz+khJUCAWgGJS4605kzPbbT8AcNJC775599LZbL4r23xCBCqEAYNg+BBoUBeZEbb35JXHHrV4wBwqAkuWgmATGyr6EHbebgBZdA/IvxW+/lQFVAgaJO+90g/SDOSATY7bffAzmAEH+3nvqQANOF6Olk9xDt0SBhl0o2n1XDSrEAHTtw8Sdt2LAHOQw6jwiK1W3W/xA2U6j5817uJLBCqCgeR9feMlOu0e1e2Q3dx9VEgOJ4Qzsxn0c9rW7GP6DcM1OhjVgBVBQt4txDUyucReLPUgMp0FtBwQtYYrrdjGjpPS63cwrYXLNuzlsQGIoBoFSJjBMftbv388CynNNO7mMa3cymPfsl0SJqZ6DUrLVOxg86nezu6xaFcqcduYMa9S2W1+TgDkDrACUV6K33bwdt+PWIrAAkSB+5+1lMdtu3SjffZcfKgTJ/Vkk5n5QaQHSB+UOOsDAAABIGCmsj6Sc2gAAAABJRU5ErkJggg==) Settings


| Name | concertologic  |
| --- | --- |
| State | Disabled  |
| Version | 08586691634935977337  |
| Integration Account |   |
| Location | eastus  |
| Changed Time | 7/24/2018 2:43:11 PM  |
| Created Time | 11/15/2016 5:43:45 PM  |


## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAH7SURBVDhPrVTLTsJQEK2gyK2LbjSxhZZCgqAxvk2M8fELPuLOxG8wxseuia8dbQHfIVFAN/6BG1EX/oNGv0NwozOXuYKkEBee5Ib0nJlpZ+ZcpEYofZmFDt25Z9F0niiOLngO6G5JiWcXiWoNKPIq9aa+fGrqU5/OaZb15UvOFlWfaleQ7wg77xTaGnIss4UJePxaquwP2VDU/hCcbKa3KbQ5VlZu/Z0RNy+SvE6n4eYxjlJqwJm0h52XoJnZFEWgrTIz3UN1/Dy5unHXpQ6eJ+F5H3leLOIWZIjHPCV+vMQLBQy3VP/GNgjuTh7Pc7EB3f1nc6D/tIkH8h+4yEynCOKnEJiZPuBCE8A290QsLoSZmWuSJEkfzWl+rTrQCLRDtCeikxd9GAfx5fDwaYjoGmCtfL04E6I8sb7+zKhQhagajLEzVXyRNpFLEO0JbUh8UapsjBVVonnPeWE2PLgdkjzxe0Z2hUXdAhcChvMghKoIW+s/meViA3oGjmbqzYkH8p+4iD5A28sxdyegOwUq9oFvDo2cxtfWLoP4y6LZXeRRB3ffBMHhkPemJE6WeaFfAMeCL1o6G+xxY1mldspoDnSsSMLNtKl2dUPEybE/3DVE/e2PT12FJMvy4b8APiOP7VBoayiJ7DK09wgtFIniYHC/cLDeM/k3SNI33Fv3PjU/IO4AAAAASUVORK5CYII=) Workflow Definition
The definition of the workflow is:{
  &quot;$schema&quot;: &quot;https://schema.management.azure.com/providers/Microsoft.Logic/schemas/2016-06-01/workflowdefinition.json#&quot;,
  &quot;ContentVersion&quot;: &quot;1.0.0.0&quot;,
  &quot;Parameters&quot;: {
    &quot;$connections&quot;: {
      &quot;DefaultValue&quot;: {},
      &quot;Type&quot;: &quot;Object&quot;
    }
  },
  &quot;Triggers&quot;: {
    &quot;When_a_resource_event_occurs&quot;: {
      &quot;SplitOn&quot;: &quot;@triggerBody()&quot;,
      &quot;Type&quot;: &quot;ApiConnectionWebhook&quot;,
      &quot;Inputs&quot;: {
        &quot;Body&quot;: {
          &quot;Properties&quot;: {
            &quot;Destination&quot;: {
              &quot;EndpointType&quot;: &quot;webhook&quot;,
              &quot;Properties&quot;: {
                &quot;EndpointUrl&quot;: &quot;@{listCallbackUrl()}&quot;
              }
            },
            &quot;Topic&quot;: &quot;/subscriptions/275ddf79-b240-44e7-9916-f24175b451b1&quot;
          }
        },
        &quot;Host&quot;: {
          &quot;Connection&quot;: {
            &quot;Name&quot;: &quot;@parameters('$connections')['azureeventgrid_1']['connectionId']&quot;
          }
        },
        &quot;Path&quot;: &quot;/subscriptions/@{encodeURIComponent('275ddf79-b240-44e7-9916-f24175b451b1')}/providers/@{encodeURIComponent('Microsoft.Resources.subscriptions')}/resource/eventSubscriptions&quot;,
        &quot;Queries&quot;: {
          &quot;X-ms-api-version&quot;: &quot;2017-06-15-preview&quot;
        }
      }
    }
  },
  &quot;Actions&quot;: {
    &quot;Send_an_email&quot;: {
      &quot;RunAfter&quot;: {},
      &quot;Type&quot;: &quot;ApiConnection&quot;,
      &quot;Inputs&quot;: {
        &quot;Body&quot;: {
          &quot;Body&quot;: &quot;@triggerBody()?['subject']&quot;,
          &quot;Subject&quot;: &quot;something changed !&quot;,
          &quot;To&quot;: &quot;pascal@umaknow.com&quot;
        },
        &quot;Host&quot;: {
          &quot;Connection&quot;: {
            &quot;Name&quot;: &quot;@parameters('$connections')['office365']['connectionId']&quot;
          }
        },
        &quot;Method&quot;: &quot;post&quot;,
        &quot;Path&quot;: &quot;/Mail&quot;
      }
    }
  },
  &quot;Outputs&quot;: {}
} 
## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAEkSURBVDhPnZOxSsRAEIb3EfQdfARLwS47gw8hHKgIVwhWNtkNKNeL7Gwq8T1sr7BSBBUVq0OwU7T2dC7OGe+cu1394Idk9///bIbE5FICHXiIJ97SqQe6cUCvbvV4Qbbz4OCzx/gxLYc07K2ERbHNxyMNtJJ9jMt8wjPWe28tUcamO62ktGEw2q+wxmYN4nkT0BjNYbpgQkD342ueX19ik/Dm1XcgQzyrQ4m28JNuNfM8lRDWJf5FBfFBM6bkiqMlqWgG+6iZUqqQulLRvM6bZkrK1ltSYQx/oS+qKSFXxE2paOGyJ808Sw7qjkR/U2LeoF0RZpeM4ZNda+FWtCHWNFx2qZZA3BZLPg7ixc8Svt+Rrb/jrfwmlvZk6f94DLtymcCYTxhUn7TOvHz8AAAAAElFTkSuQmCC) Tags


| Tag Key | Tag Value |
| --- | --- |
| Application  | ADKApp2  |





## ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAJ8SURBVDhPfZTNaxNBGMan1gZJNsQkO7PJya9oauLiVf8ET/ZSREQPgop48SqCQdFsZqOC4qEepNBWbWMhtgqVmP1IPWir2XRFpVbQk4gfINJWY9J0nU0myaSpeeBhdmff97fvvjOzYD31p0B3XPfulzQ4ihX0ZTwfWb430zs7/CK0LxYDG2hYZ2GVv5BUA4tXc0Gr5oD16PXehtOmuJQq9J6l4e1KPPV6EopgJPWg1epWUN2kysygtmUTTW8qqQvzzSpYrw+ynXoZMWl6TQkVxdgqZC1oSQp8l1D9p64rQnRkdvuBB/ndF9MF8fta2Oir0JEqxG4sVoVlFoJVNBjTwMZqAKO7z0TvQzO6wIIm5vb8TKX6u4GkbxZbq0HvWQjHcZAMjftbbyLcZEGssLD7z8NbgazCCRYkTcPTNMeWm4AKLpdrkt5XlTYiYyxoLB+WAOnFEgvCij9M44HD4djldrvfEpBAp6oamdlxggWljegdICv8DxYkZZBI4211EcghUtUCue6pTQFQNv0HV0xk1f3X9N4EchYNscsdz6LzNB54PJ5tBPKReIpOVVUy/OMtoDnfcXAp497JViTrwueYBjmaA5xOZ4AMjWpWDQ6WTL5ch5RNVLHmgzwAFuiSVeFbC0wTDLJybbv28hQfXMzzn9hqyGd+oI8B6RM8xoJsYxUWsc4PYA31xRV0WFLQY/KClWsaLP3O+4p1UNHwRSimJqzD4bWw/3kgh379Mfhi2fBhmt7UydugR1KFlj3VyUM5eM4ip4KmtwtnUR/WAl/JUVltA2jBSkLlzfgTGKLhnWX/vOzGkl1/BmvwBukTJuPRK9PkuJDFoWGMAPgHNgHtxQBV7kUAAAAASUVORK5CYII=) Billing
![]() Total cost : 
