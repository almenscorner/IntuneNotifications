# IntuneNotifications

The goal with this application is to notify you and your team and give you a visual indication if any tokens/certificates is about to expire or if a sync fails to connected services. For me this is a really handy tool when on the go, there's been multiple times when a sync has failed to ABM/VPP and I only knew once I signed in to the MEM console to check.

## Setup
To setup and use this application, please see [this blog post](https://almenscorner.io/introducing-intune-notifications-app/).

## App overview
### Home screen
The home screen is where you see all notifications, at this time it monitors APNs certificate expiry, ABM token expiry, VPP token expiry, ABM sync failures and VPP sync failures. If a token/certificate is about to expire in 30 days, the notification will be shown here as a warning, inidcated by the orange circle. If a sync fails to any of the services, a notification with a red circle is shown to indicate an error. At the bottom of the screen is an overview of the services sync status. If any token fails a sync the green check mark will be switched to the orange warning sign.

![HomeScreen](https://user-images.githubusercontent.com/78877636/131859982-b35664b9-103c-4e03-bc67-d2ba90d17067.png)

### ABM details screen
Shows details about all connected ABM tokens, here you can also see which one has failed the sync.

![ABMDetailScreen](https://user-images.githubusercontent.com/78877636/131860549-7f6ac9e0-65aa-4489-8dd7-0c1f9cf1382f.png)

### VPP details screen
Shows details about all connected VPP tokens, here you can also see which one has failed the sync.

![VPPdetailsScreen](https://user-images.githubusercontent.com/78877636/131860391-9d05f060-cc49-4741-80a0-ef9fa5cdfbb7.png)

### Managed Google Play details screen
Shows details about Managed Google Play, here you can also see if it has failed to sync.

![GPlaydetailScreen](https://user-images.githubusercontent.com/78877636/131860729-fd182fea-ef0a-4ecd-8004-7abbfdc70348.png)
