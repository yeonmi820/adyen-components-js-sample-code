Request:
  "merchantAccount": "AdyenRecruitmentCOM",
  "reference": "YanmeiCui_adyenrecruitment",
  "countryCode": "NL",
  "channel": "Web",
  "returnUrl": "https://docs.adyen.com/",
  "amount": {
    "value": 1000,
    "currency": "EUR"
  },
  "lineItems": [
    {
      "id": "1",
      "description": "Test Item 1",
      "amountExcludingTax": 10000,
      "amountIncludingTax": 11800,
      "taxAmount": 1800,
      "taxPercentage": 1800,
      "quantity": 1,
      "taxCategory": "High"
    }
  ],

Response:
  "pspReference": "BSGH7B7C96QLJJV5",
  "resultCode": "Authorised",
  "amount": {
    "currency": "EUR",
    "value": 1000
  },
  "merchantReference": "YanmeiCui_adyenrecruitment",
  "paymentMethod": {
    "brand": "jcb",
    "type": "scheme"
  }

 
