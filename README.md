# Name-Enquiry
Guide for Name Enquiry API

This method retrieves the Name of any UserID. You can get the User Full Name using UserID with respective parameters.

HTTP Method: GET

# Resource Url

https://cofredpay.com/api/v1/nameenquiry

# Headers

See our Guide for how to setup Header https://github.com/cofred/Header-Authentication

# Authentication Headers

merchant_id: VFdCMTY3WURPZUpJdkNnVWJWRXE=   // Base64 Encoded

secret_code: I8AtLUljNqcdS4F76OVy2Zf1bJvGwsP95rE

terminal_id: YINCU

access_token: dUp4dEtybVg0UmpmMEFT  // Base64 Encoded

timestamp: 1505628722

"user_id: 1262846"

# Request Parameters

Field	M/O	Length	Format	Description

UserID	M	7	Numeric	UserID to get Name

# GetName Response

A HTTP response code 200 is sent back for a success

# Response Parameters

Field	Description

responseCode	Response Code

responseMessage	Response Message which will return Full Name

# Sample Response

200

{
   "responseCode":"200",
   "responseMessage":"Om Bharti"
}

# Communication

Requests will be sent over the REST protocol
