# MobileAppApi

All URIs are relative to *https://ha.mine/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**webhookWebhookIdPost**](MobileAppApi.md#webhookWebhookIdPost) | **POST** /webhook/{webhookId} | Send info to HA


<a name="webhookWebhookIdPost"></a>
# **webhookWebhookIdPost**
> webhookWebhookIdPost(webhookId, body)

Send info to HA



### Example
```java
// Import classes:
//import io.swagger.client.api.MobileAppApi;

MobileAppApi apiInstance = new MobileAppApi();
String webhookId = "webhookId_example"; // String | Webhook ID
Webhook body = new Webhook(); // Webhook | json body
try {
    apiInstance.webhookWebhookIdPost(webhookId, body);
} catch (ApiException e) {
    System.err.println("Exception when calling MobileAppApi#webhookWebhookIdPost");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **webhookId** | **String**| Webhook ID |
 **body** | [**Webhook**](Webhook.md)| json body |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

