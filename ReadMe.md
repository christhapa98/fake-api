# Fake API Example

This repository contains a fake API for demonstration purposes only.

To use the API, make a GET request to the following endpoint:

# get purchases list

url : https://riddhasoftchris.github.io/fake-api/purchases.json

response example: 

[
  {
    "poNo": "67-548-3215",
    "poDate": "12/25/2022",
    "arrivalDate": "3/10/2023",
    "supplierAgentName": "Bobette Soldan",
    "itemName": "Vilevine",
    "uom": 8,
    "quantity": 22,
    "netAmount": 96
  }
  ]

 # get items list

  url :  https://riddhasoftchris.github.io/fake-api/items.json

  response example : 
  
  [
  {
    "itemName": "Amaretto",
    "group": "Leader Arthritis Pain",
    "openingStock": 1,
    "uom": "5790",
    "salesPrice": 1,
    "itemStatus": true,
    "taxCategory": "13 % Vat"
  }]

 # get gatepass list

  url :  https://riddhasoftchris.github.io/fake-api/gatepass.json

  response example : 
  
  [
  {
            "gpNo": "36-471-8423",
            "gpDate": "2/4/2023",
            "supplierAgentName": "Garden",
            "itemName": "Grenville",
            "uom": 19,
            "quantity": 5,
            "netAmount": 41
        }]