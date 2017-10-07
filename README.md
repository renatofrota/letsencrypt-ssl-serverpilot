# letsencrypt-ssl-serverpilot
Let's Encrypt SSL issuance and renewals automation for [ServerPilot free plan](http://bit.ly/serverpilot)

# English

## How to use

### Installing the script

```
cd $HOME && \
git clone https://github.com/renatofrota/letsencrypt-ssl-serverpilot.git && \
sudo cp letsencrypt-ssl-serverpilot/spssl /usr/local/bin/ && \
sudo chmod +x /usr/local/bin/spssl
```

### Issuing (and installing) a certificate

Run `spssl` and follow on screen instructions.

Certificates are renewed automatically.

### Uninstalling the script

```
rm -f /usr/local/bin/spssl /etc/cron.daily/letsencrypt-renew-cron
```

## Donate

Think on how much $ you're saving and buy me some coffee! :)

> USD

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=R58RLRMM8YM6U)

> BRL

[![Doar](https://www.paypalobjects.com/pt_BR/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9JMBDY5QA8X5A)

# Português

# letsencrypt-ssl-serverpilot
Automação de emissão e renovação de certificados Let's Encrypt SSL para o [plano gratuito da ServerPilot](http://bit.ly/serverpilot)

## Como utilizar

### Instalando o script

```
cd $HOME && \
git clone https://github.com/renatofrota/letsencrypt-ssl-serverpilot.git && \
sudo cp letsencrypt-ssl-serverpilot/spssl /usr/local/bin/ && \
sudo chmod +x /usr/local/bin/spssl
```

### Emitindo (e instalando) um certificado

Execute `spssl` e siga as instruções na tela.

Os certificados são renovados automaticamente.

### Desinstalando o script

```
rm -f /usr/local/bin/spssl /etc/cron.daily/letsencrypt-renew-cron
```

## Donate

Pense em quanta grana você está economizando e me pague um café! :)

> BRL

[![Doar](https://www.paypalobjects.com/pt_BR/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9JMBDY5QA8X5A)

> USD

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=R58RLRMM8YM6U)
