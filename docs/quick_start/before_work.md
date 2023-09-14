# Before you start#

Before you start working with Flow API you are required to follow the below steps:

1. [Create Account in Your profile](#1-create-account-in-your-profile)
2. [Create User account](#2-create-user-account)
3. [Install mobile app WhatsApp Business](#3-install-mobile-app-whatsapp-business)
4. [Authorize User account](#4-authorize-user-account)
5. [Get access parameters to User account](#5-get-access-parameters-to-user-account)
6. [Set receiving incoming data](#6-set-receiving-incoming-data)


## 1. Create account in Your profile
To create Account go to [Your profile](https://cabinet.flowsell.me/account/profile). 
After authorization in your profile, you will be able to create a user account. 
In your profile you may create several user accounts for one account.


## 2. Create User account
You need to go to [WhatsApp accounts](https://cabinet.flowsell.me/accounts/whats-app) in [your Flowsell cabinet](https://cabinet.flowsell.me/). Using add button create a new user account.

## 3. Install mobile app WhatsApp Business
Sending and receiving WhatsApp messages is done from your mobile phone. 
The phone must have the official [WhatsApp Business](https://business.whatsapp.com/) mobile app installed. 
It is also allowed to use the mobile application [WhatsApp](https://www.whatsapp.com/), if the use of [WhatsApp Business](https://business.whatsapp.com/) is impossible for any reason.

## 4. Authorize User account
If you use a personal mobile phone for work with Flow API, you have to authorize User account. 
Account authorization is carried out in [Your profile](https://cabinet.flowsell.me/account/profile) by scanning QR code from [WhatsApp Business](https://business.whatsapp.com/) mobile app. 
To do this, open [WhatsApp Business]('https://business.whatsapp.com/') application on your mobile phone, go to the application settings and scan the QR code displayed in your profile.


## 5. Get access parameters to User account
To execute HTTP API WhatsApp requests, you need to use the access parameters to User account. 
Access parameters:

- `idInstance` - account unique number. You can get it in [WhatsApp accounts](https://cabinet.flowsell.me/accounts/whats-app)
- `apiTokenInstance` - account access key. You can get it in [Integration via API](https://cabinet.flowsell.me/templates/apicrm)

Account access key can be changed if necessary, for example, if it is compromised.


## 6. Information about webhooks
- Information how you can set webhook is [here](../api/account/set-settings.md)
- Information how you can get webhook is [here](../api/account/get-settings.md)
- Information about types of webhooks is [here](../api/receiving/index.md)

## Done!#
Everything is ready to start sending and receiving WhatsApp messages!

