***GET***
<br/> **/employee/{id}

**Description**
------------------
GET the employee by Id

**Headers**
------------------
| Parameters | Description | Required | Format | Example |
| ------:| -----------:| --------:|------:|-----:|
| uuid | The random unique identifier used for logging and debugging | Yes | String | abc123 |
| client_secret| this is a secret known only to the application and the authorization server | Yes | String | abc123 |
| client_id | The public identifier for the application | Yes | String | abc123 |

**URI parameters**
------------------
| Parameters | Description | Required | Format | Example |
| ------:| -----------:| --------:|------:|-----:|
| id | id of the employee  | Yes | String | 123 |


**Response Body**
------------------
```
HTTP 200 - OK
```

```
{ "id" : 341, "name" : "Judy", "designation" : "Sr. developer" }
```
