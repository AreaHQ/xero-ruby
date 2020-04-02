# XeroRuby::ExpenseClaim

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**expense_claim_id** | **String** | Xero generated unique identifier for an expense claim | [optional] 
**status** | **String** | Current status of an expense claim – see status types | [optional] 
**payments** | [**Array&lt;Payment&gt;**](Payment.md) | See Payments | [optional] 
**user** | [**User**](User.md) |  | [optional] 
**receipts** | [**Array&lt;Receipt&gt;**](Receipt.md) |  | [optional] 
**updated_date_utc** | **DateTime** | Last modified date UTC format | [optional] [readonly] 
**total** | **Float** | The total of an expense claim being paid | [optional] [readonly] 
**amount_due** | **Float** | The amount due to be paid for an expense claim | [optional] [readonly] 
**amount_paid** | **Float** | The amount still to pay for an expense claim | [optional] [readonly] 
**payment_due_date** | **Date** | The date when the expense claim is due to be paid YYYY-MM-DD | [optional] [readonly] 
**reporting_date** | **Date** | The date the expense claim will be reported in Xero YYYY-MM-DD | [optional] [readonly] 
**receipt_id** | **String** | The Xero identifier for the Receipt e.g.  e59a2c7f-1306-4078-a0f3-73537afcbba9 | [optional] 

## Code Sample

```ruby
require 'XeroRuby'

instance = XeroRuby::ExpenseClaim.new(expense_claim_id: null,
                                 status: null,
                                 payments: null,
                                 user: null,
                                 receipts: null,
                                 updated_date_utc: null,
                                 total: null,
                                 amount_due: null,
                                 amount_paid: null,
                                 payment_due_date: null,
                                 reporting_date: null,
                                 receipt_id: null)
```


