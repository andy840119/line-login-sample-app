# line-login-sample-app
LINE Login sample for ASP.NET Core web app

# How to make it work
- 1.Clone this project

- 2.Create a `Provider` and `Line login channel` in `https://developers.line.biz`

- 3.Add `https://localhost:44303/signin-oidc` into `Line login channel`'s callback url

- 3.Fill `LoginClientId`, `LoginClientSecret` and `MessagingAccessToken(optional)` in `appsettings.Base.json`

- 4.Rename `appsettings.Base.json` to `appsettings.json`

- 5.Start the server and make sure it run in `Https`(Importent)

- 6.Click `Login in` button

- 7.If everything works well you can see `Line`'s login screen

- 8.Enter your `Email` and `Password` and click `Login` button, it will redirect to homepage.

- 9.If login success, you will see your account's email and avator.
