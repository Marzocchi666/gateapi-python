# Order

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Order ID | [optional] 
**text** | **str** | User defined information. If not empty, must follow the rules below:  1. prefixed with &#x60;t-&#x60; 2. no longer than 16 bytes without &#x60;t-&#x60; prefix 3. can only include 0-9, A-Z, a-z, underscore(_), hyphen(-) or dot(.)  | [optional] 
**create_time** | **str** | Order creation time | [optional] 
**update_time** | **str** | Order last modification time | [optional] 
**status** | **str** | Order status  - &#x60;open&#x60;: to be filled - &#x60;closed&#x60;: filled - &#x60;cancelled&#x60;: cancelled | [optional] 
**currency_pair** | **str** | Currency pair | 
**type** | **str** | Order type. limit - limit order | [optional] [default to 'limit']
**account** | **str** | Account type. spot - use spot account; margin - use margin account | [optional] [default to 'spot']
**side** | **str** | Order side | 
**amount** | **str** | Trade amount | 
**price** | **str** | Order price | 
**time_in_force** | **str** | Time in force | [optional] [default to 'gtc']
**left** | **str** | Amount left to fill | [optional] 
**fill_price** | **str** | Total filled in quote currency | [optional] 
**fee** | **str** | Fee deducted | [optional] 
**fee_currency** | **str** | Fee currency unit | [optional] 
**point_fee** | **str** | Point used to deduct fee | [optional] 
**gt_fee** | **str** | GT used to deduct fee | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


