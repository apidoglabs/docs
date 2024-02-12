# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including


| Common Error Messages | Description | Suggested Solutions |
| --- | --- | --- |
| Preview Error | fdsfsadfasdfalsjflasdjfklasdjfksnkvcansudkfjwidsfjaosifjdiosfmnadskifjaoisdfjaosdfjiasdjfoadsjfmoasdjfaosdmfcadlsfjaosdfmcodsaijfoaisjfasodfjasodjfasdjfosdfjoads| Select the preview browser when prompting the Salla CLI [`preview`](doc-422776?nav=01HNA8QHCPJTCY5VSEZ616JCAK) command. |
| Non-existent Theme ID | The theme ID doesn't exist in your developer account. | Re-login through the CLI using the command [salla login](doc-422762?nav=01HNA8QHCPJTCY5VSEZ616JCAK). |
| CLI Request Failure | The CLI failed to request a preview for the theme. | Reconnect your [Github](https://github.com/) account to Salla and give all authorizations. |
| Web Socket Issue | There's an issue with the web socket. | Contact support via [Telegram](https://t.me/SallaSupportBot). |
| Token Authorization | There's a problem with token authorization. | Personal Accesss Token is used as an alternative to passwords for authentication to Github with Salla CLI. This step is required for creating themes using Salla CLI. Read more [here](doc-422769?nav=01HNA8QHCPJTCY5VSEZ616JCAK).  |
| Bad CPU Type in executable | Users with Apple devices running on the Apple Silicon chip processors will face a problem, which is caused by the package used, [cloudflare](https://www.npmjs.com/package/cloudflare). The package is not compatible *yet* with Apple devices using the new Apple Silicon chip. | Installing Rosetta by following this [guide](doc-422761?nav=01HNA8QHCPJTCY5VSEZ616JCAK).

| Common Error Messages | Description | Suggested Solutions |
| --- | --- | --- |
| Preview Error | While previewing the Twilight theme during development using your browser, it seems to not be replacing assets url with `localhost:8000/assets/...`. | Select the preview browser when prompting the Salla CLI [`preview`](doc-422776?nav=01HNA8QHCPJTCY5VSEZ616JCAK) command. |
| Non-existent Theme ID | The theme ID doesn't exist in your developer account. | Re-login through the CLI using the command [salla login](doc-422762?nav=01HNA8QHCPJTCY5VSEZ616JCAK). |
| CLI Request Failure | The CLI failed to request a preview for the theme. | Reconnect your [Github](https://github.com/) account to Salla and give all authorizations. |
| Web Socket Issue | There's an issue with the web socket. | Contact support via [Telegram](https://t.me/SallaSupportBot). |
| Token Authorization | There's a problem with token authorization. | Personal Accesss Token is used as an alternative to passwords for authentication to Github with Salla CLI. This step is required for creating themes using Salla CLI. Read more [here](doc-422769?nav=01HNA8QHCPJTCY5VSEZ616JCAK).  |
| Bad CPU Type in executable | Users with Apple devices running on the Apple Silicon chip processors will face a problem, which is caused by the package used, [cloudflare](https://www.npmjs.com/package/cloudflare). The package is not compatible *yet* with Apple devices using the new Apple Silicon chip. | Installing Rosetta by following this [guide](doc-422761?nav=01HNA8QHCPJTCY5VSEZ616JCAK). 


- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to autopropagate changes from youre repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
