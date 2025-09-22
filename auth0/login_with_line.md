# Auth0 Integration with LINE

## Create LINE Login Channel
1. Open [LINE Developers](https://developers.line.biz/en/) and go to the Console.
2. Create your channel.
![Create channel](/__images__/auth0/login_with_line/create_channel_1.png)
![Create channel](/__images__/auth0/login_with_line/create_channel_2.png)
![Create channel](/__images__/auth0/login_with_line/create_channel_3.png)
3. Save your `Channel ID` and `Channel Secret` to use in Auth0.

## Setting Up LINE Connections in Auth0
1.  Open your Auth0 dashboard, then choose `Authentication` → `Social` → `Create Connection`.
![Create channel](/__images__/auth0/login_with_line/setting_line_connection_1.png)
![Create channel](/__images__/auth0/login_with_line/setting_line_connection_2.png)
2. Enter your `Channel ID` and `Channel Secret`.
![Create channel](/__images__/auth0/login_with_line/setting_line_connection_3.png)

## Setting the Callback URL in Your LINE Channel
1. Open the **LINE Login** settings in your channel and enter your `Auth0 Callback URL`.
![Create channel](/__images__/auth0/login_with_line/setting_callback_1.png)
*The Auth0 Callback URL is `https://YOUR_DOMAIN.auth0.com/login/callback`.*