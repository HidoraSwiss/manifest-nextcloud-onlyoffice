![Nextcloud / Onlyoffice](/images/nextcloud-onlyoffice.png)

## Nextcloud 
Nextcloud puts your data at your fingertips, under your control.
Store your documents, calendar, contacts and photos on your Jelastic plateform.
More info on [https://nextcloud.com/](https://nextcloud.com/)

## Onlyoffice
Onlyoffice is an online office that enables you to manage documents, projects, team and customer relations in one place.
More info on [https://www.onlyoffice.com/](https://www.onlyoffice.com/)

## Nextcloud and Onlyoffice together
 These two tools will allow you to work in real time with your collaborators. You can access to your document and modify it directly on your tablet or even smartphone.

## Deploy Nextcloud/Onlyoffice in 3 minutes
This is a quick tutorial to explain how to quickly deploy a [Nextcloud](https://nextcloud.com/) and Onlyoffice servers on Hidora (or any other [Jelastic provider](https://jelastic.cloud/)).
1. On the Jelastic console, click on `Import` and select the URL tab.
2. Paste this URL in the input field : https://raw.githubusercontent.com/HidoraSwiss/manifest-nextcloud-onlyoffice/master/manifest.jps and click on `Import`.
3. Provide an environnment name and a display name for your new environnement and then click on `Install`.

Few minutes later, your new Nextcloud and Onlyoffice server  is fully installed and you can now link your Nextcloud to your Onlyoffice.

4. Open your environment Nextcloud and enable `Onlyoffice` in **Apps/Office & text/ Enable Onlyoffice**
5. After that, go to **Settings/Onlyoffice**, and specify the URL of your environment Onlyoffice which is available on your  Dashboard (ex : http://docker22252-env-0895495.hidora.com)
> If you need a secure connection over SSL/TLS, you can easily add it by the *topology panel* corresponding to your envrionnement and click on `SSL` to enable it. Then, when you click on `Apply`, your environnement is reconfigured to use HTTPS.
