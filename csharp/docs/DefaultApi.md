# IO.Swagger.Api.DefaultApi

All URIs are relative to *https://virtserver.swaggerhub.com/Zeavz9/PlayGame/0.0.1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetscreenGet**](DefaultApi.md#getscreenget) | **GET** /getscreen | ok


<a name="getscreenget"></a>
# **GetscreenGet**
> void GetscreenGet ()

ok

ok

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class GetscreenGetExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();

            try
            {
                // ok
                apiInstance.GetscreenGet();
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.GetscreenGet: " + e.Message );
            }
        }
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

