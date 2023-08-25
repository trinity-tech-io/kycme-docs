---
description: 'Documentation version: v1.0.3'
---

# KYC me & Alicloud Authentication Guide

**Update date**: 2023.08.22

The Trinity-Tech team has completed the integrated development with Alicloud eKYC, and now the real-name authentication can be completed through the **passport**. The user experience will continue to be optimized in the future.

## **1. Device**

mobile phone

## **2. Essentials version**

The versions after Essentials v3.0.9 are available.

### **Download the latest version of Essentials**

#### **Android version：**

[https://download.trinity-tech.io/app/elastos-essentials/Essentials.apk](https://download.trinity-tech.io/app/elastos-essentials/Essentials.apk)

#### **IOS version：**

[https://elink.elastos.net/download](https://elink.elastos.net/download)

## **3. Steps**

_**Note:**_

_`The Android version is built-in to support third-party applications. The iOS version does not support built-in due to the review policy.`_

_`At the same time, the iOS version supports opening third-party applications on external browsers by default.`_

So if iOS users want to experience a similar effect on Android, iOS users need to do the following:

1. Open the Essentials app.
2. On the Essentials homepage, click the settings icon in the upper right corner to enter the settings page, then click the privacy menu to enter the privacy settings page, and open the button in the column behind the built-in browser.
3. Open the "Discover dApps" menu.
4. Enter "kyc-me.io" in the address bar to open the KYC dapp.  &#x20;

<figure><img src=".gitbook/assets/截屏2023-08-22 18.15.18.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/截屏2023-08-22 18.15.33.png" alt="" width="563"><figcaption></figcaption></figure>

_**`The following uses the Android device to operate`**_

## Login with Elastos DID within KYC-me

1. Enter the Essentials wallet homepage, find the menu "Discover dApps", and click to enter.
2. Find the dApp -- "Kyc-me", and click to enter the "Kyc-me" application.  &#x20;

<figure><img src=".gitbook/assets/截屏2023-08-22 18.18.34.png" alt="" width="563"><figcaption></figcaption></figure>

3. Click the "Sign in" button in the upper right corner.
4. After the page jumps, click the "Sign in with Elastos DID" button.
5. Jump to Essentials, the pop-up request DID authorization login page, and click the "Accept" button.  &#x20;

<figure><img src=".gitbook/assets/截屏2023-08-22 18.20.09.png" alt="" width="563"><figcaption></figcaption></figure>

6. Jump to the KYC-me again, and click the "My Dashboard >" button.
7. After the page jumps, click the "Verify now >" button.
8. After the page jumps, click the "Verify" button.  &#x20;

<figure><img src=".gitbook/assets/截屏2023-08-22 18.24.34.png" alt="" width="563"><figcaption></figcaption></figure>

_**Note：**_

_Chinese users can also use the second-generation ID card for authentication._

<figure><img src=".gitbook/assets/截屏2023-08-22 18.25.33.png" alt="" width="563"><figcaption></figcaption></figure>

### Do KYC certification in Alicloud -- t**ake the passport as an example**

1. The page jumps to the alicloud in-app authentication, and after viewing the prompt information, click the "Start certification" button.&#x20;

<figure><img src=".gitbook/assets/截屏2023-08-22 18.26.45.png" alt="" width="189"><figcaption></figcaption></figure>

2. Follow the tips to do KYC authentication.

* The first step is to use the passport for authentication.
* The second step is to do face recognition.  &#x20;

<figure><img src=".gitbook/assets/截屏2023-08-22 18.28.21.png" alt="" width="563"><figcaption></figcaption></figure>

3. After the authentication is successful, jump to the KYC-me application;&#x20;

<figure><img src=".gitbook/assets/截屏2023-08-22 18.29.28.png" alt="" width="188"><figcaption></figcaption></figure>

### Import KYC credentials into identity

1. Click the "Back to dashboard" button to enter the certificate list page.&#x20;

{% code overflow="wrap" %}
```
There are currently 6 credentials: Full name, Gender, Nationality, Date of birth, Passport number, and Passport number hash.
```
{% endcode %}

2. If you want to import a certain credential separately, please click the button "Import to Identity wallet" under this credential.&#x20;

{% code overflow="wrap" %}
```
If you want to import all credentials at once, please click the button "Import all credentials to Identity wallet".
```
{% endcode %}

3. On the pop-up page of requesting to import credentials on Essentials, click "Accept" to complete the import of credentials. &#x20;

<figure><img src=".gitbook/assets/截屏2023-08-22 18.30.28.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/截屏2023-08-22 18.31.25.png" alt="" width="563"><figcaption></figcaption></figure>

### Check the imported credentials in Essentials

<figure><img src=".gitbook/assets/截屏2023-08-22 18.32.33.png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/截屏2023-08-22 18.32.56.png" alt="" width="375"><figcaption></figcaption></figure>

## 4. FAQ

### 1. Why is the DID login unsuccessful, prompting me to publish my identity?&#x20;

DID can be successfully signed in on KYC-me after it is published on the chain.

Under normal circumstances, DID will be automatically published on the chain after it is created.

If DID is not published successfully due to network or service, please manually publish it on the chain.

If the DID has been published successfully, but when you try to sign in, it still prompts that you need to publish it on the chain. It may be due to the network, just wait for a few minutes and try again.

_**Note:**_

The steps to manually publish DID are as follows:

<figure><img src=".gitbook/assets/截屏2023-08-22 18.36.05.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/截屏2023-08-22 18.36.18.png" alt="" width="375"><figcaption></figcaption></figure>

### 2. Why the "Verify" button is grayed out and cannot be clicked on the page opened by kyc-me.io?&#x20;

Desktop browser is not supported, please switch to the mobile phone to experience.

### 3. Why does the ID photo taken in the local gallery always prompt that the authentication failed?

Please ensure that the ID photo is taken on a horizontal screen.

Currently, compatibility with vertical screens is low.

The recognition rate is higher when the ID photo is directly taken during authentication.

Please follow the rules for taking ID photos before starting the authentication.

### 4. Some Android devices open the KYC-me app in the Essentials internal browser, the camera is stuck?&#x20;

The built-in browser compatibility of some Android models is not very good, please switch to the external browser to use.

Mainstream browsers such as Chrome/safari are recommended.

Switch to open the dapp method:

<figure><img src=".gitbook/assets/截屏2023-08-22 18.38.28.png" alt="" width="563"><figcaption></figcaption></figure>

### 5. Samsung mobile phone, the camera cannot be turned on when doing kyc authentication on the Samsung browser?&#x20;

There may be a problem with the permissions that allow the browser to use the camera.

Please do the related operations:

{% code overflow="wrap" %}
```
Settings->Apps->Samsung Internet->Permissions->Camera, select "Allow only while using the app" (if there is no problem with the settings, please continue to the next step)
```
{% endcode %}

```
Clear history on the Samsung browser.
```

```
Kill the Samsung browser process and try it again.
```

### 6.  Can't find Essentials in the Apple store for iOS devices?

&#x20;    An overseas ID is required to download Essentials.
