Users

* username: String
    * Must contain only word characters
* password: String
    * Must be at least 8 characters
* email: String
    * Must contain an @ symbol
* profile: {
  	birthday: {"value": date, "visible": boolean},
  	gender: {"value": String 1 char, "visible": boolean},
  	phone_number: {"value": String, "visible": boolean},
  	location: {"city": String, "state": String, "country": String, "visible": boolean}
  	info: String
}
