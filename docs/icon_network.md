# ICON Network
When you switch between networks, make sure you use the correct network ID.
If the network ID does not match, the transaction will fail.  

## Private Devnet on AWS
- TBA


## Testnet for DApps

Please note that the current testnet can be reset anytime and you may experience unexpected downtime.
We are working on preparing a more stable final test environment
along with less-managed multiple playground networks.  

|              |                |
|--------------|----------------|
| Name         | Yeouido (여의도) |
| Node         | https://bicon.net.solidwallet.io |
| API endpoint | https://bicon.net.solidwallet.io/api/v3 |
| Network ID (nid)| 3 |
| Tracker         | https://bicon.tracker.solidwallet.io |
| Transaction fee | on  |
| SCORE audit     | off |

To receive test ICX, please send an email to `testicx@icon.foundation` with the following information.
- Testnet node url
- Address to receive the testnet ICX. Address should start with `hx` followed by 20 byte string.


## Testnet for Exchanges
The Euljiro Network is open exclusively to exchange developers. 

|              |                |
|--------------|----------------|
| Name         | Euljiro (을지로) |
| Node         | https://test-ctz.solidwallet.io |
| API endpoint | https://test-ctz.solidwallet.io/api/v3 |
| Network ID (nid)| 2 |
| Tracker         | https://trackerdev.icon.foundation |
| Transaction fee | on  |
| SCORE audit     | on  |

To receive test ICX, please contact your account manager.


## Mainnet

|              |                |
|--------------|----------------|
| Name         | ICON Mainnet   |
| Node         | https://ctz.solidwallet.io |
| API endpoint | https://ctz.solidwallet.io/api/v3 |
| Network ID (nid)| 1 |
| Tracker         | https://tracker.icon.foundation |
| Transaction fee | on  |
| SCORE audit     | on  |

Before you submit your SCORE to the ICON mainnet, you should thoroughly test it on T-Bears and the testnet.
Note that the SCORE audit is not enabled in testnet. Please make sure you understand the ICON audit policy and follow the guidelines.
- [SCORE Audit](score_audit.md)
- [Audit Checklist](audit_checklist.md)
- [Deploy Guideline](score_deploy_guide.md)
  
If you have any questions about the audit process, please send an email to `audit@icon.foundation`.

## How to change network in the ICONex Chrome extension
- Open the Chrome DevTools by pressing F12, then go to the **Application** tab. In the **Storage** section, expand **Local Storage**. 
- Add a new key/value pair, **isDev/true**, by clicking on the empty row at the bottom of the table.

![](images/iconex-isdev.png)

- Reload your wallet, then you will see the menu in the bottom. Click the **ICX (SERVER)** button to open the dropup list of the available networks. You can choose a predefined one, or manually set a custom node. 

![](images/iconex-network.png)

 
