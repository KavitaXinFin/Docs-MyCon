
**API's**

**REST-full API implantation of mycontract platform**

# **Introduction**

Welcome to the MyContract API! We are the leading platform for Smart Contract Creation, Deployment, Interaction, and Token Offering.

# **Authentication**

A JSON Web Token is used to send information that can be verified and trusted by means of a digital signature. It comprises a compact and URL-safe JSON object, which is cryptographically signed to verify its authenticity, and which can also be encrypted if the payload contains sensitive information.
 

Application may request to access routes, services, or resources on behalf of that user. To do so, it uses an access token, which is in the form of a JWT token. User has to provide JWT token in header as a authorization in every subsequent request after login.

```axios.get('https://api.mycontract.co:3001/demo', {headers: {
Authorization:"yRQYnWzskCZUxPwaQupWkiUzKELZ49eM" //JWT Token}
})
```

```axios.post('https://api.mycontract.co:3001/demo', {headers: {Authorization:"yRQYnWzskCZUxPwaQupWkiUzKELZ49eM" //JWT Token},data: //JSON})```

# **Account Related APIs**

!!! POST 

**Sign Up**

		https://api.mycontract.co:3001/v1/admin/signup


This endpoint allows you to signup for admin.


![overview](/assets/Request1.jpg)

![overview](/assets/Response1.jpg)


!!! POST 

**Login**

                https://api.mycontract.co:3001/v1/admin/login

This endpoint allows you to login as admin.


![overview](/assets/Request2.jpg)

![overview](/assets/Response2.jpg)


!!! GET

**Profile Details**

                https://api.mycontract.co:3001/v1/admin/details

This endpoint is used to get admin profile details

![overview](/assets/Request3.jpg)

![overview](/assets/Response3.jpg)



!!! GET

**Upload KYC Data**

                https://api.mycontract.co:3001/v1/admin/uploadKYC

This endpoint is used to upload KYC data.


![overview](/assets/Request4.jpg)

![overview](/assets/Response4.jpg)



!!! GET

**Client List**

                https://api.mycontract.co:3001/v1/admin/client/list

This endpoint is used to retrieve client list. 


![overview](/assets/Request5.jpg)

![overview](/assets/Response5.jpg)


!!! GET

**Individual client detail**

                https://api.mycontract.co:3001/v1/admin/client/:clientId

This endpoint is used to retrieve client list. 


![overview](/assets/Request6.jpg)

![overview](/assets/Response6.jpg)



!!! GET

**Individual client detail**

                https://api.mycontract.co:3001/v1/admin/client/:clientId

This endpoint is used to retrieve client list. 


![overview](/assets/Request6.jpg)

![overview](/assets/Response6.jpg)




!!! POST

**Update Client KYC Status**

                https://api.mycontract.co:3001/v1/admin/client/updateKYC/:clientId

This endpoint is used to update KYC status.


![overview](/assets/Request7.jpg)

![overview](/assets/Response7.jpg)


!!! GET

**Logout**

                https://api.mycontract.co:3001/v1/admin/logout

This endpoint is used to end user session.


![overview](/assets/Request8.jpg)

![overview](/assets/Response8.jpg)


!!! Warning

!!! Tip

!!! Info
