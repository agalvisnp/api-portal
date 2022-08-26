---
description: lorem ipsum lorem ipsum lorem ipsum
---

# 🎯 Notification

* lorem ipsum 1
* lorem ipsum 2

{% embed url="https://www.loom.com/share/95cd3f765304425583fb66f40d521d3c" %}

{% embed url="https://gist.github.com/LuisMDeveloper/a900acbf7140c18217dc7a1679c52114" %}



{% swagger src="../.gitbook/assets/Notification.yaml" path="/itsp/{clientID}/vtis/v1/notification" method="post" %}
[Notification.yaml](../.gitbook/assets/Notification.yaml)
{% endswagger %}

{% content-ref url="../reference/api-reference/pets.md" %}
[pets.md](../reference/api-reference/pets.md)
{% endcontent-ref %}

{% tabs %}
{% tab title="Sandbox" %}
[https://sandbox-api.novopayment.com/customers/v1](https://sandbox-api.novopayment.com/customers/v1)
{% endtab %}

{% tab title="Second Tab" %}
[https://cert-api.novopayment.com/customers/v1/individuals](https://cert-api.novopayment.com/customers/v1/individuals)
{% endtab %}

{% tab title="Untitled" %}
[https://prod-api.novopayment.com/customers/v1/individuals](https://prod-api.novopayment.com/customers/v1/individuals)
{% endtab %}
{% endtabs %}

#### Data Object

| Name        | Description                                                               | Data Type                   | Required / Optional / Conditional       |
| ----------- | ------------------------------------------------------------------------- | --------------------------- | --------------------------------------- |
| customerId  | <p>Unique customer identifier.</p><p>Sample: Sample: 56BA34F664FB9B90</p> | String(40)                  | Required                                |
| legalName   | <p>customer's full name</p><p>Sample: John Doe</p>                        | String (100)                | Required                                |
| createdDate | <p>Customer creation date</p><p>Sample: 2020/02/09 16:13:53</p>           | Date (yyyy/mm/dd H24:Mi:ss) | Required$$f(x) = x * e^{2 pi i \xi x}$$ |

{% code overflow="wrap" lineNumbers="true" %}
```json
// Some code
{

	"userCredentials": {
		"username": "JDOE"
	},
	"generalInformation": {
		"firstNames": "John",
		"lastNames": "Doe",
		"gender": {
			"id": "1"
		},
		"civilStatus": {
			"id": "1"
		},
		"birthCountry": {
			"iso2": "US"
		},
		"birthState": {
			"name": "New York"
		},
		"birthCity": {
			"name": "New York"
		},
		"birthDate": "1985/01/07",
		"educationLevel": {
			"id": "1"
		}
	},
	"identityDocuments": [{
			"documentType": {
				"id": "3"

			},
			"documentNumber": "C96485632",
			"isPrimary": true,
			"issueDate": "2020/01/01",
			"expirationDate": "2030/01/01",
			"country": {
				"iso2": "US"
			},
			"firstNames": "John",
			"lastNames": "Doe",
			"gender": {
				"id": "1"
			},
			"birthDate": "1985/01/07"
		}

	],
	"personalAddress": {
		"country": {
			"iso2": "US"
		},
		"state": {
			"name": "New York"
		},
		"city": {
			"name": "New York"
		},
		"streetAddress": "01 W. 31th St, New York",
		"address2": "John Doe Building",
		"zipCode": "10011",
		"buildingNumber": "10",
		"homeNumber": "101"
	},
	"contactInformation": {
		"phoneCodeIso2": "US",
		"phoneNumber": "6450000000",
		"email": "JohnDoe@example.com"
	}
}
```
{% endcode %}
