# testVippsKeysOrUptime

#### Short Description:
Script to test subsciption-keys and uptime in Vipps test environment.

#### Long Description:
Script will load credentials from input.json file, and then fetch accesstoken from Vipps. With the received access token it will initiate a payment and receive Deeplink. When deeplink is received script will open firefox geckodriver with deeplink to vipps payment and simulate user to click button and confirm payment. In order for this to work you need to have a testuser profile received from integration with Vipps.

### Technical Requirements
You need to have firefox installed and you need to have a geckodriver located at "c:/geckodriver/geckodriver.exe" (get geckodriver here:https://github.com/mozilla/geckodriver/releases)

### How to run:

- Rename the file inputExample.json to input.json
- Fill in the missing keys and data in the new input.json file
- run the getAccessTokenAndInitiatePayment.jar file

Regards,
Håkon
