# Electrotronix
Chain-/Viewer &amp; Wallet

```
REST-FUCKUP-OPEN/
│
├─ index.html
│
├─ portable.js
├─ portable.css
├─ portable.html
├─ portable.config.js
│
├─ python/
│   ├─ logic.py
│   ├─ helper.js
│   ├─ schema.sql
│   ├─ config.yaml
│   ├─ config.yml
│   ├─ wallet_engine.py
│   ├─ tx_engine.py
│   ├─ hash_engine.py
│   ├─ viewer_engine.py
│   ├─ rapp_engine.py
│   ├─ session_engine.py
│   ├─ swap_engine.py
│   ├─ stake_engine.py
│   ├─ unstake_engine.py
│   ├─ mining_engine.py
│   ├─ txi_engine.py
│   ├─ txf_engine.py
│   ├─ tx_validator.py
│   ├─ tx_fee_engine.py
│   ├─ hash_linker.py
│   ├─ hash_encryptor.py
│   ├─ block_engine.py
│   ├─ interaction_engine.py
│   ├─ block_navigation_engine.py
│   ├─ rapp_vm.py
│   ├─ rapp_api.py
│   ├─ rapp_permissions_engine.py
│   ├─ rapp_store_engine.py
│   ├─ session_device_engine.py
│   ├─ session_expiry_engine.py
│   ├─ session_token_engine.py
│   ├─ security_engine.py
│   ├─ encryption_engine.py
│   ├─ phrase_engine.py
│   ├─ popup_engine.py
│   ├─ button_engine.py
│   ├─ navigation_engine.py
│   └─ json_engine.py
│
├─ javascript/
│   ├─ server.js
│   ├─ util.py
│   ├─ migrate.sql
│   ├─ settings.yaml
│   ├─ settings.yml
│   ├─ wallet.js
│   ├─ tx.js
│   ├─ hash.js
│   ├─ viewer.js
│   ├─ rapp.js
│   ├─ session.js
│   ├─ swap.js
│   ├─ stake.js
│   ├─ unstake.js
│   ├─ mining.js
│   ├─ txi.js
│   ├─ txf.js
│   ├─ tx_validator.js
│   ├─ tx_fee.js
│   ├─ hash_linker.js
│   ├─ hash_encryptor.js
│   ├─ block.js
│   ├─ interaction.js
│   ├─ block_navigation.js
│   ├─ rapp_vm.js
│   ├─ rapp_api.js
│   ├─ rapp_permissions.js
│   ├─ rapp_store.js
│   ├─ session_device.js
│   ├─ session_expiry.js
│   ├─ session_token.js
│   ├─ security.js
│   ├─ encryption.js
│   ├─ phrase.js
│   ├─ popup.js
│   ├─ button.js
│   ├─ navigation.js
│   └─ json_engine.js
│
├─ core/
│   ├── state-machine.js
│   ├── event-store.js
│   ├── vigilant-fetch.js
│   ├── coldnet-warmnet.js
│   ├── identity.js
│   ├── parity.js
│   ├── crypto.js
│   ├── auth-ui.js
│   ├── settings-ui.js
│   │
│   ├── state-machine.test.js
│   ├── event-store.test.js
│   ├── vigilant-fetch.test.js
│   ├── identity.test.js
│   ├── crypto.test.js
│   ├── auth-ui.test.js
│   ├── settings-ui.test.js
│   │
│   ├── index.js
│   └── utils.js
│
├─ backend/
│   ├── backend-api.js
│   ├── backend-events.js
│   ├── backend-errors.js
│   ├── backend-router.js
│   ├── backend-storage.js
│   │
│   ├── index.js
│   └── config.js
│
├─ database/
│   ├─ schema.sql
│   ├─ seed.py
│   ├─ migrate.js
│   ├─ db.yaml
│   ├─ db.yml
│   ├─ wallet_tables.sql
│   ├─ tx_tables.sql
│   ├─ viewer_tables.sql
│   ├─ rapp_tables.sql
│   ├─ session_tables.sql
│   ├─ user_tables.sql
│   ├─ settings_tables.sql
│   ├─ security_tables.sql
│   ├─ rapp_vm_tables.sql
│   ├─ rapp_api_tables.sql
│   ├─ interaction_tables.sql
│   ├─ hash_tables.sql
│   ├─ session_devices.sql
│   ├─ session_tokens.sql
│   └─ session_expiry.sql
│
├─ config/
│   ├─ app.yaml
│   ├─ app.yml
│   ├─ loader.py
│   ├─ loader.js
│   ├─ init.sql
│   ├─ wallet_config.yaml
│   ├─ tx_config.yaml
│   ├─ viewer_config.yaml
│   ├─ rapp_config.yaml
│   ├─ session_config.yaml
│   ├─ security_config.yaml
│   ├─ ui_config.yaml
│   ├─ device_config.yaml
│   ├─ hash_config.yaml
│   ├─ mining_config.yaml
│   ├─ stake_config.yaml
│   ├─ unstake_config.yaml
│   ├─ swap_config.yaml
│   ├─ rapp_vm_config.yaml
│   └─ rapp_api_config.yaml
│
├─ json/
│   ├─ session/
│   │   ├─ active_session.json
│   │   ├─ session_history.json
│   │   ├─ session_lock.json
│   │   ├─ session_tokens.json
│   │   ├─ session_devices.json
│   │   └─ session_expiry.json
│   │
│   ├─ user/
│   │   ├─ users.json
│   │   ├─ usernames.json
│   │   ├─ userpassword.json
│   │   ├─ phrases.json
│   │   ├─ user_roles.json
│   │   ├─ user_settings.json
│   │   ├─ user_security.json
│   │   └─ user_activity.json
│   │
│   ├─ wallet/
│   │   ├─ balances.json
│   │   ├─ addresses.json
│   │   ├─ transactions.json
│   │   ├─ mining.json
│   │   ├─ staking.json
│   │   ├─ unstaking.json
│   │   ├─ swaps.json
│   │   ├─ deposits.json
│   │   ├─ withdrawals.json
│   │   └─ wallet_activity.json
│   │
│   ├─ viewer/
│   │   ├─ blocks.json
│   │   ├─ txi.json
│   │   ├─ txf.json
│   │   ├─ interactions.json
│   │   ├─ hashes.json
│   │   ├─ block_links.json
│   │   ├─ viewer_settings.json
│   │   └─ viewer_activity.json
│   │
│   ├─ settings/
│   │   ├─ profile_settings.json
│   │   ├─ wallet_settings.json
│   │   ├─ rapp_settings.json
│   │   ├─ security_settings.json
│   │   ├─ ui_settings.json
│   │   └─ device_settings.json
│   │
│   └─ store/
│       ├─ rapps.json
│       ├─ store_state.json
│       ├─ search_history.json
│       ├─ rapp_downloads.json
│       ├─ rapp_updates.json
│       └─ rapp_permissions.json
│
├─ html/
│   ├─ wallet.html
│   ├─ profile.html
│   ├─ settings.html
│   ├─ viewer.html
│   ├─ store.html
│   ├─ tx_viewer.html
│   ├─ hash_viewer.html
│   ├─ rapp_vm.html
│   ├─ rapp_api.html
│   ├─ mining.html
│   ├─ staking.html
│   ├─ unstaking.html
│   ├─ swap.html
│   ├─ deposit.html
│   ├─ withdraw.html
│   ├─ send.html
│   ├─ receive.html
│   ├─ popups.html
│   ├─ buttons.html
│   └─ navigation.html
│
├─ css/
│   ├─ style.css
│   ├─ wallet.css
│   ├─ profile.css
│   ├─ settings.css
│   ├─ viewer.css
│   ├─ store.css
│   ├─ tx_viewer.css
│   ├─ hash_viewer.css
│   ├─ rapp_vm.css
│   ├─ rapp_api.css
│   ├─ mining.css
│   ├─ staking.css
│   ├─ unstaking.css
│   ├─ swap.css
│   ├─ deposit.css
│   ├─ withdraw.css
│   ├─ send.css
│   ├─ receive.css
│   ├─ popups.css
│   ├─ buttons.css
│   └─ navigation.css
│
├─ yaml/
│   ├─ app.yaml
│   ├─ wallet.yaml
│   ├─ tx.yaml
│   ├─ viewer.yaml
│   ├─ rapp.yaml
│   ├─ session.yaml
│   ├─ security.yaml
│   ├─ hash.yaml
│   ├─ mining.yaml
│   ├─ stake.yaml
│   ├─ unstake.yaml
│   ├─ swap.yaml
│   ├─ rapp_vm.yaml
│   ├─ rapp_api.yaml
│   ├─ session_device.yaml
│   ├─ session_expiry.yaml
│   └─ session_token.yaml
│
├─ yml/
│   ├─ app.yml
│   ├─ wallet.yml
│   ├─ tx.yml
│   ├─ viewer.yml
│   ├─ rapp.yml
│   ├─ session.yml
│   ├─ security.yml
│   ├─ hash.yml
│   ├─ mining.yml
│   ├─ stake.yml
│   ├─ unstake.yml
│   ├─ swap.yml
│   ├─ rapp_vm.yml
│   ├─ rapp_api.yml
│   ├─ session_device.yml
│   ├─ session_expiry.yml
│   └─ session_token.yml
│
├─ sql/
│   ├─ schema.sql
│   ├─ wallet.sql
│   ├─ tx.sql
│   ├─ viewer.sql
│   ├─ rapp.sql
│   ├─ session.sql
│   ├─ user.sql
│   ├─ settings.sql
│   ├─ security.sql
│   ├─ rapp_vm.sql
│   ├─ rapp_api.sql
│   ├─ interaction.sql
│   ├─ hash.sql
│   ├─ session_devices.sql
│   ├─ session_tokens.sql
│   └─ session_expiry.sql
│
├─ docs/
│   ├── architecture.md
│   ├── state-machine.md
│   ├── event-model.md
│   ├── parity.md
│   ├── coldnet-warmnet.md
│   ├── vigilance.md
│   ├── settings.md
│   ├── auth.md
│   ├── sync.md
│   ├── status.md
│   ├── multi-domain-demo.md
│   ├── event-store.md
│   ├── vigilant-fetch.md
│   ├── identity.md
│   ├── crypto.md
│   ├── auth-ui.md
│   ├── settings-ui.md
│   ├── backend-router.md
│   ├── backend-storage.md
│   ├── backend-api.md
│   ├── backend-events.md
│   ├── backend-errors.md
│   ├── minimal-client.md
│   ├── offline-demo.md
│   └── portable.md
│
└─ examples/
    ├── minimal-client.html
    ├── offline-demo.html
    ├── minimal-client.js
    ├── minimal-client.css
    ├── offline-demo.js
    ├── offline-demo.css
    ├── multi-domain-demo.js
    └── multi-domain-demo.css
```

Rollen in Modis:
```
User = Benutzer & Admin = Entwickler
```

Pop Ups bedeutung:
```
protokollierung & auftauchende eingabe fenster oder der switch der eben durch den tab auf einen hash link in ein andere seite wechselt etc
```

# Master.NET(ist wie GitHub als X-Hub CMD = CMD-X):
```
MASTER == ADMIN(Admins sind immer Master von eigenen eXtended öko extentioned daten)

dropdown menü (ist für die weiterentwicklung einer jeder seite im MASTER Modus muss jede neben seite die als Button der Home/Wallet/Haupt seite gilt also damit ist nur Profil Settings X-Hub CMD-X und Explore Viewer gemeint)
```
```
TX = TXi & TXf
```
Home Profil Buttons & Pop ups:
```
Register/Login = Button
```
```
Home & Profil -> wenn ausgeloggt dann read only
Register = Account Erstellen
```
```
Login = Account Anmelden -> wenn eingeloggt dann write only
```
```
Home, Profil & Settings Buttons & Pop ups:
```

## Home, Profil & Settings Buttons & Pop ups:
```
Home = Register & Login 
       Wallet Blockchain as read only mode Landing Page & Wallet as Blockchain write & read only Application Page
       Benutzer/User & Entwickler/Dev Documentations, Unangemeldete und Angemeldete sicht oder auch ohne und mit Account.
       Home = Wallet, Balance & Wert, Deposit Withdraw Send Receive Swap Stake Unstake Start Mining & Stop Mining
        Pop Ups       0,00 = €$¢¥£,  ISO (13616), IBAN, BIC Wallet Adresse/n, Vorhandene Wallet Saldo/Balance.
       Profil = Settings, Benutzername & Passwort management, Phrasen einsicht, Wallet, Ton & rApp Connect.
        Pop Ups           Benutzernamen Ändern & Passwort Ändern, Phrasen Kopieren, alle Wallets aus Wallet & Ton                                  Connect = alle zusammen rApp Connect & rApp Connect = 12-/24 Chiffre.
       Explore Viewer = X-Hub, Blocks/Blöcke hashes, Transaktionen hashes, Interaktions Hashes für/als register, Login,                                 Logout, für beide(3) Rollen User & Admin-/Master des jeweiligen Accounts(Profil/Wallet),                                 Profil Name, Profil Passwort, Wallet Adressen, Send Receive Deposit Withdraw Swap, Stake                                 Unstake Start Mining Stop Mining, write massage by a transaction (Energie Kosten für                                     bustaben länge muss bezaht werden zur Transaktios gebühr hinzu), such eingaben, settings                                 bearbeitungs & display berührungs, Hash/es in/als DB Website, sind also nur Hash arten                                   wallet Adressen und Profil/Nutzer Namen Einsehbarkeit.
                               also ein Verlauf jedes Bereiches in Blöcken als Hashes Sha-/AES via pzqqet 256/512/1024 
        Pop Ups                info button so wie konsole Button & ganz speziell die Hashes sind Links so das jeder Hash                                ein eigener Block ist und darstellen wird als gesamte website ansicht wechselt man                                       von dem Block wo man war in den Bloock auf dessen Hash man geklickt hat um den Block der                                 Hash ein zu sehen die man durch anklicken der hash block links eisehen will. 
       rApp Store = X-Hub, ist eine Card im Home(unangemeldete Wallet) im Wallet(angemeldet im Home) und im Explore             Viewer so wie auch im Profil NUR NICHT IN SETTINGS, also in den genannten ist rApp Store ein Fenster/Rendering in        dem die rApp X-Hub als erste rApp existiert wie auch im gogle play store oder apple store app mit/als icon.
        Pop Ups
        die Card istd as fenster als rApp store der apps in die man in dem amn eindach auf sie tippt rein gehen kann die         card und dessen rApps drinnen sind von oben nach unten scrollable so wie von rechts nach links scrollable und            einer sucheingabe leiste wie auch im Explore Viewer der auch der X-Hub ist.
 ```     

kurzzusammenfassung der Home, Profil & Settings Buttons & Pop ups:
```
nur Register/Login Button Pop up fenster ist durch antippen des Buttons wen man unangeneldet ist aufrufbar und die rApps des stores also die die darinen sind = Electrotronix(ist die Wallet) X-Hub und Explore Viewer, müssen die einzigen 4 Pop Ups sein wenn man unangemeldet die website betritt.
```

Wallet Profil Links Buttons & Setting Pop ups:
```
Phrasen Benutzername Passwort Wallet adresse Wallet Hash manuell-transaktions hash interactions-transactions hash
```



# Test.NET(ist wie Preview in einer code Datei):
```
TXf & TXi = TX
```
Home Profil Buttons & Pop ups:
```
Register/Login = Button
```
```
Home & Profil -> wenn ausgeloggt dann read only
Register = Account Erstellen
```
```
Login = Account Anmelden -> wenn eingeloggt dann write read only (vigilanz)
```

## Home, Profil & Settings Buttons & Pop ups:
```
Home = Register & Login 
       Wallet Blockchain as read only mode Landing Page & Wallet as Blockchain write & read only Application Page
       Benutzer/User & Entwickler/Dev Documentations, Unangemeldete und Angemeldete sicht oder auch ohne und mit Account.
       Home = Wallet, Balance & Wert, Deposit Withdraw Send Receive Swap Stake Unstake Start Mining & Stop Mining
        Pop Ups       0,00 = €$¢¥£,  ISO (13616), IBAN, BIC Wallet Adresse/n, Vorhandene Wallet Saldo/Balance.
       Profil = Settings, Benutzername & Passwort management, Phrasen einsicht, Wallet, Ton & rApp Connect.
        Pop Ups           Benutzernamen Ändern & Passwort Ändern, Phrasen Kopieren, alle Wallets aus Wallet & Ton                                  Connect = alle zusammen rApp Connect & rApp Connect = 12-/24 Chiffre.
       Explore Viewer = X-Hub, Blocks/Blöcke hashes, Transaktionen hashes, Interaktions Hashes für/als register, Login,                                 Logout, für beide(3) Rollen User & Admin-/Master des jeweiligen Accounts(Profil/Wallet),                                 Profil Name, Profil Passwort, Wallet Adressen, Send Receive Deposit Withdraw Swap, Stake                                 Unstake Start Mining Stop Mining, write massage by a transaction (Energie Kosten für                                     bustaben länge muss bezaht werden zur Transaktios gebühr hinzu), such eingaben, settings                                 bearbeitungs & display berührungs, Hash/es in/als DB Website, sind also nur Hash arten                                   wallet Adressen und Profil/Nutzer Namen Einsehbarkeit.
                               also ein Verlauf jedes Bereiches in Blöcken als Hashes Sha-/AES via pzqqet 256/512/1024 
        Pop Ups                info button so wie konsole Button & ganz speziell die Hashes sind Links so das jeder Hash                                ein eigener Block ist und darstellen wird als gesamte website ansicht wechselt man                                       von dem Block wo man war in den Bloock auf dessen Hash man geklickt hat um den Block der                                 Hash ein zu sehen die man durch anklicken der hash block links eisehen will. 
       rApp Store = X-Hub, ist eine Card im Home(unangemeldete Wallet) im Wallet(angemeldet im Home) und im Explore             Viewer so wie auch im Profil NUR NICHT IN SETTINGS, also in den genannten ist rApp Store ein Fenster/Rendering in        dem die rApp X-Hub als erste rApp existiert wie auch im gogle play store oder apple store app mit/als icon.
        Pop Ups
        die Card istd as fenster als rApp store der apps in die man in dem amn eindach auf sie tippt rein gehen kann die         card und dessen rApps drinnen sind von oben nach unten scrollable so wie von rechts nach links scrollable und            einer sucheingabe leiste wie auch im Explore Viewer der auch der X-Hub ist.
 ```     

kurzzusammenfassung der Home, Profil & Settings Buttons & Pop ups:
```
nur Register/Login Button Pop up fenster ist durch antippen des Buttons wen man unangeneldet ist aufrufbar und die rApps des stores also die die darinen sind = Electrotronix(ist die Wallet) X-Hub und Explore Viewer, müssen die einzigen 4 Pop Ups sein wenn man unangemeldet die website betritt.
```


Wallet:
```
senden = send
```
```
empfangen = receive 
```
```
Mine = Mining-start-&-stop
```
```
Stake = Staking 
Unstake = Unstaking 
```
```
transaction = hash
```

# rApp Store(VM) & (API)Explor-Viewer: 
***(action event & post)***
```
search = suchen 
```
```
Home = X-Hub, Profil & Settings Buttons & Pop ups:
```

```
Home = Explore Viewer, Profil & Settings Buttons & Pop ups: 
```

```
X-Hub hat eigenes Profil & Settings Buttons & Pop ups trotzdem immer selber rApp Account des rApp store (X-Hub Wallet und Explore Viewer).
```
```
Explore Viewe hat eigenes Profil & Settings Buttons & Pop ups trotzdem immer selber rApp Account des rApp store (X-Hub Wallet und Explore Viewer).
```


# Main.NET:
```
TXf & TXi = TX
```
## Home Profil Buttons & Pop ups:
```
Register/Login = Button
```

```
Home & Profil -> wenn ausgeloggt dann read only
Register = Account Erstellen
```

```
Login = Account Anmelden -> wenn eingeloggt dann write only
```
## Home, Profil & Settings Buttons & Pop ups:
```
Home = Register & Login 
       Wallet Blockchain as read only mode Landing Page & Wallet as Blockchain write & read only Application Page
       Benutzer/User & Entwickler/Dev Documentations, Unangemeldete und Angemeldete sicht oder auch ohne und mit Account.
       Home = Wallet, Balance & Wert, Deposit Withdraw Send Receive Swap Stake Unstake Start Mining & Stop Mining
        Pop Ups       0,00 = €$¢¥£,  ISO (13616), IBAN, BIC Wallet Adresse/n, Vorhandene Wallet Saldo/Balance.
       Profil = Settings, Benutzername & Passwort management, Phrasen einsicht, Wallet, Ton & rApp Connect.
        Pop Ups           Benutzernamen Ändern & Passwort Ändern, Phrasen Kopieren, alle Wallets aus Wallet & Ton                                  Connect = alle zusammen rApp Connect & rApp Connect = 12-/24 Chiffre.
       Explore Viewer = X-Hub, Blocks/Blöcke hashes, Transaktionen hashes, Interaktions Hashes für/als register, Login,                                 Logout, für beide(3) Rollen User & Admin-/Master des jeweiligen Accounts(Profil/Wallet),                                 Profil Name, Profil Passwort, Wallet Adressen, Send Receive Deposit Withdraw Swap, Stake                                 Unstake Start Mining Stop Mining, write massage by a transaction (Energie Kosten für                                     bustaben länge muss bezaht werden zur Transaktios gebühr hinzu), such eingaben, settings                                 bearbeitungs & display berührungs, Hash/es in/als DB Website, sind also nur Hash arten                                   wallet Adressen und Profil/Nutzer Namen Einsehbarkeit.
                               also ein Verlauf jedes Bereiches in Blöcken als Hashes Sha-/AES via pzqqet 256/512/1024 
        Pop Ups                info button so wie konsole Button & ganz speziell die Hashes sind Links so das jeder Hash                                ein eigener Block ist und darstellen wird als gesamte website ansicht wechselt man                                       von dem Block wo man war in den Bloock auf dessen Hash man geklickt hat um den Block der                                 Hash ein zu sehen die man durch anklicken der hash block links eisehen will. 
       rApp Store = X-Hub, ist eine Card im Home(unangemeldete Wallet) im Wallet(angemeldet im Home) und im Explore             Viewer so wie auch im Profil NUR NICHT IN SETTINGS, also in den genannten ist rApp Store ein Fenster/Rendering in        dem die rApp X-Hub als erste rApp existiert wie auch im gogle play store oder apple store app mit/als icon.
        Pop Ups
        die Card istd as fenster als rApp store der apps in die man in dem amn eindach auf sie tippt rein gehen kann die         card und dessen rApps drinnen sind von oben nach unten scrollable so wie von rechts nach links scrollable und            einer sucheingabe leiste wie auch im Explore Viewer der auch der X-Hub ist.
 ```     

kurzzusammenfassung der Home, Profil & Settings Buttons & Pop ups:
```
nur Register/Login Button Pop up fenster ist durch antippen des Buttons wen man unangeneldet ist aufrufbar und die rApps des stores also die die darinen sind = Electrotronix(ist die Wallet) X-Hub und Explore Viewer, müssen die einzigen 4 Pop Ups sein wenn man unangemeldet die website betritt.
```

## Wallet:
```
senden = send 
```

```
empfangen = receive 
```

```
Mine = Mining-start-&-stop
```

```
Stake = Staking 
Unstake = Unstaking 
```

```
transaction = hash
```


# rApp Store(VM) & (API)Explor-Viewer: 
***(action event & post)***
```
search = suchen 
```
```
Home = X-Hub, Profil & Settings Buttons & Pop ups:
```

```
Home = Explore Viewer, Profil & Settings Buttons & Pop ups: 
```

```
X-Hub hat eigenes Profil & Settings Buttons & Pop ups trotzdem immer selber rApp Account des rApp store (X-Hub Wallet und Explore Viewer).
```
```
Explore Viewe hat eigenes Profil & Settings Buttons & Pop ups trotzdem immer selber rApp Account des rApp store (X-Hub Wallet und Explore Viewer).
``` 





