# Reviews

Use this application to get a random user from a github team.

## Getting Started

Run `make setup` to setup the necessary tools.

Duplicate the `.env.template` file and save the new as `.env`.
Fill the new `.env` file with your information.

Run `make run` to run the script.

## Example

ORG: PicPay

TEAM: iOS

TOKEN: ghp_OLps7JTx9WLYIr004SETTD0EmpVJvQ184uRB

(token is a Personal access token)

Obs.: Mais sobre o token na seção ["Autenticar com o SSO do SAML"](https://docs.github.com/pt/rest/overview/other-authentication-methods)
 
## To test if the env parameters are correct
curl -v -H "Authorization: token ghp_OLps7JTx9WLYIr004SETTD0EmpVJvQ184uRB" https://api.github.com/orgs/PicPay/teams/iOS/members
