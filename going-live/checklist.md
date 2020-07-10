# Go live checklist
*Use this guide to prepare yourself for going live with your FP integration*

We recommend you review the sections below in detail to make sure you give yourself enough time to prepare your integration to go live in production.  
Email us at [fpsupport@cybrilla.com](mailto:fpsupport@cybrilla.com) when you are ready with the details.

### Identity

To activate KYC Check APIs in your production account, we need the following details

**CVL KRA** (*Time: 2-3 weeks*)

- [ ] Username
- [ ] POS Code
- [ ] Password


### Orders

To activate order processing in your production account, we need the following details about your distribution license:

**About your business** (*Time: min. 2 weeks*)
- [ ] Amfi Registration Number (ARN issued by AMFI) or RIA code (Registered investment advisor code issed by SEBI)
- [ ] Employee unique identification number (EUIN)
- [ ] Your business registered location

**To route orders through RTA gateway** (*Time: min. 4 weeks*)

*CAMS*
- [ ] User code
- [ ] Online broker code
- [ ] STP credentials
  - [ ] STP username
  - [ ] STP password

*Karvy*
- [ ] User code
- [ ] Broker code
- [ ] STP credentials
  - [ ] STP username
  - [ ] STP password
  - [ ] STP app identifier
  - [ ] STP arn number
  - [ ] STP branch code

*Franklin*
- [ ] User code
- [ ] Broker code
- [ ] STP credentials
  - [ ] STP username
  - [ ] STP password

**To route orders through BSE gateway** (*Time: min. 4 weeks*)
- [ ] BSE user id
- [ ] BSE member id
- [ ] BSE password

### Payments

To activate payments in your production account, we need the following details:

**Payment gateway (Razorpay)** (*Time: 4-6 weeks*)

*Razorpay account 1 (with third party verification enabled)*
- [ ] Merchant ID
- [ ] Live account api key id
- [ ] Live account api key secret

*Razorpay account 2 (with third party verification disabled)*
- [ ] Merchant ID
- [ ] Live account api key id
- [ ] Live account api key secret

Ensure the following in both of your Razorpay accounts:
- [ ] Payments and Route are enabled
- [ ] Send out an email to Razorpay Support to add `fintechprimitives.com` domain to the whitelisted domains/urls for your accounts

**AMCs**

*Collection bank account details for each AMC that needs to be enabled*
- [ ] Bank name
- [ ] Account holder name
- [ ] Account number
- [ ] IFSC code