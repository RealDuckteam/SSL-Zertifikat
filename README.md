# SSL-Zertifikat

```apt update && apt upgrade -y```

```apt install certbot python3-certbot-apache -y```

```certbot --authenticator webroot --installer apache -w /var/www/html/ -d MeineDomain.de```


Danach werden Sie nach Ihre E-Mail Adresse gefragt, bitte geben Sie hier Ihre korrekte E-Mail Adresse ein. Um die Certbot-Nutzungsbedingungen zuzustimmen, müssen Sie danach "A" eingeben. Danach werden Sie gefragt, ob Sie gerne den Newsletter der Electronic Frontier Foundation abonnieren möchten. Sie können dies selbst entscheiden ("Y" = Ja / "N" = Nein). Am Ende werden Sie gefragt, ob die Verbindung Secure (HTTPS) sein sollte, bitte da dementsprechend die Zahl eingeben.

Sobald Sie alles erledigt haben, müssen Sie nur noch auf Ihrer Webseite gehen und kontrollieren, ob HTTPS einwandfrei funktioniert.
