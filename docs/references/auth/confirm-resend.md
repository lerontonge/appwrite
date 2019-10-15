This endpoint allows the user to request your app to resend him his email confirmation message. The redirect arguments act the same way as in /auth/register endpoint.

Please notice that in order to avoid a [Redirect Attack](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Unvalidated_Redirects_and_Forwards_Cheat_Sheet.md) the only valid redirect URLs are the ones from domains you have set when adding your platforms in the console interface.