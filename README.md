# single-sign-on

1. start both apps: SsoClientApplication and SsoServerApplication.
2. visit sso-client at http://localhost:8082/sso-client/ , you'll be redirected to sso-server.
3. login once (user,password) at sso-server (localhost:8080).
4. been redirected to sso-client, now you're authorized with SSO token, saved by sso-server in cookies (valid for a session).
5. next time you visit http://localhost:8082/sso-client/ , you'll be authorized with SSO token, previously saved in cookies.
