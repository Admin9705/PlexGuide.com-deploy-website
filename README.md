<p align="center">
  <img src="https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/blob/Version-5/scripts/plexguide-logo5.PNG?raw=true" alt="PlexGuide.com Logo"/>
</p>

----------------------------------------------------------------------
**Tip**: Did you know if you click the star in the upper right, it promotes our project further on GITHUB?

### Personal Site Deployment - Coded By:
- [Admin9705](https://github.com/Admin9705)

### Important
- **UBUNTU 16.04 & 17.04 ** Only !!! PlexGuide is not MADE FOR SERVER EDITONS 16.10 - 17.10**
- This requires the [PlexGuide Install First](https://plexguide.com)

### Social
- [PlexGuide Discord Channel](https://discord.gg/mg7bVnw)

### Want to Donate? Everybit Helps!

**Support US**: Purchase multiple crypto-curriencies via http://binance.plexguide.com - Purchase Stellar & Ripple! Value increased 4 times from late Dec 17 thru Jan 18!

- Bitcoin : 1H3SD3ef6qaN8ND8S8ZQCaEyD4pMW4kFsA
- LiteCoin: LbCDaq26N39TuUarBkrxTXNFjsNWds9Ktj

----------------------------------------------------------------------

1. Ensure that you installed PlexGuide as Noted Above - This relies on certain programs

```
sudo git clone https://github.com/Admin9705/PlexGuide.com-deploy-website.git /opt/deploysite
```

2. Place this in the terminal to place your variables for you own wordpress website

```
sudo ansible-playbook /opt/deploysite/config.yml
```

3. Then to execute your wordpress, put the following in:

```
sudo ansible-playbook /opt/deploysite/wordpress.yml
```
