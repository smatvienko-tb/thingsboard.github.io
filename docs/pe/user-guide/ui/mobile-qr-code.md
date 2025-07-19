---
layout: docwithnav-pe
assignees:
- stitenko
title: Mobile application QR code
description: Mobile app QR code guide

download-app-with-qr-code:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-thingsboard-home-page-1-pe.png
        title: 'Log into your ThingsBoard account and navigate to the "Home" page. You will find the QR code for connecting the mobile app in the bottom right corner;'
    1:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-scan-and-install-app-pe.png
        title: 'Open the camera app on your phone or tablet and point it at the QR code. The phone will automatically scan the code and show the link button. Click this button to open the link to download the <b>ThingsBoard mobile app</b>;'
    2:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-mobile-install-app-pe.png
        title: 'Install ThingsBoard mobile application;'
    3:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-mobile-open-app-1-pe.png
        title: 'Launch the ThingsBoard mobile app to start using it.'

clicking-button:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-thingsboard-home-page-2-pe.png
        title: 'Clicking the "App Store" or "Google Play" button in the "Connect mobile app" widget, you will be redirected to the ThingsBoard app page in the respective app store for further downloading to your device.'
    1:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-button-2-pe.png
        title: 'App Store.'
    2:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-button-1-pe.png
        title: 'Google Play.'

authorize-with-qr-code:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-mobile-login-with-qr-1-pe.png
        title: 'Launch the ThingsBoard mobile app on your device and use the QR code scanning feature. Make sure you have the latest version of the app installed;'
    2:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-scan-and-open-app-pe.png
        title: 'Scan the QR code on the "Home" page of your ThingsBoard instance using the mobile app. You will find the QR code for connecting the mobile app in the bottom right corner;'
    3:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/qr-code-mobile-dashboard-1-pe.png
        title: 'You have successfully logged into the ThingsBoard mobile app with your account.'

mobile-app-qr-code-widget-settings:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/mobile-app-qr-code-widget-settings-1-pe.png
        title: 'Navigate to the "QR code widget" tab on the "Mobile center" page and disable "Use system settings" toggle;'

application-settings-default:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/mobile-app-qr-code-widget-settings-2-pe.png
        title: 'Leave "Default" applications settings to use the <b>ThingsBoard Cloud</b> mobile application.'

application-settings-custom:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/mobile-app-qr-code-widget-settings-3-pe.png
        title: 'If you prefer to use your custom application, switch to the custom settings, and specify the bundle preconfigured on the "Bundle" tab. Then, save changes.'

disable-platforms:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/mobile-app-qr-code-widget-settings-4-pe.png
        title: 'If necessary, you can disable unused platforms.'

appearance-on-home-page:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/mobile-app-qr-code-widget-settings-5-pe.png
        title: 'You can disable the QR code widget on the "Home" page, adjust the positioning of the badges, and update the QR code label.'

add-qr-code-widget:
    0:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/add-qr-code-widget-1-pe.png
        title: 'Open your dashboard and switch to edit mode. Click the "+ Add widget" icon at the top of the screen;'
    1:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/add-qr-code-widget-2-pe.png
        title: 'Navigate to the "Cards" widget bundle;'
    2:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/add-qr-code-widget-3-pe.png
        title: 'Select the "Mobile app QR code" widget;'
    3:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/add-qr-code-widget-4-pe.png
        title: 'You can use either the system settings or customize your own. If desired, you can configure badges (or turn them off altogether), and update the QR code label. Click "Add".'
    4:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/add-qr-code-widget-5-pe.png
        title: 'Adjust widget size to fit your needs. After you&#39;re done tweaking, click "Save" to save the dashboard;'
    5:
        image: https://img.thingsboard.io/user-guide/ui/qr-code/add-qr-code-widget-6-pe.png
        title: 'Mobile app QR code widget has been added. Scan QR code with your mobile and check you are redirected to the specified application.'
  

---

{% assign docsPrefix = "pe/" %}
{% include get-hosts-name.html docsPrefix=docsPrefix %}
{% include docs/user-guide/ui/mobile-qr-code.md %}