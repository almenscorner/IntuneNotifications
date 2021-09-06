# Intune Notifications

The goal with this application is to notify you and your team and give you a visual indication if any tokens/certificates is about to expire or if a sync fails to connected services. For me this is a really handy tool when on the go, there's been multiple times when a sync has failed to ABM/VPP and I only knew once I signed in to the MEM console to check.

## Setup
To setup and use this application, please see [this blog post](https://almenscorner.io/introducing-intune-notifications-app/).

## Update
If you already have the app imported when downloading the latest release, make sure "Update" is selected. If new flows have been added they should be imported as "Create new"

## App overview
### Home screen
The home screen is where you see all notifications, at this time it monitors APNs certificate expiry, ABM token expiry, VPP token expiry, ABM sync failures and VPP sync failures. If a token/certificate is about to expire in 30 days, the notification will be shown here as a warning, inidcated by the orange circle. If a sync fails to any of the services, a notification with a red circle is shown to indicate an error. At the bottom of the screen is an overview of the services sync status. If any token fails a sync the green check mark will be switched to the orange warning sign. If a service is turned off in settings, a grey circle will be shown on the turned off service under Sync status.

![HomeScreen](![Home12](https://user-images.githubusercontent.com/78877636/132257861-3d501cbd-6799-4c4a-a922-38fe0d7e213b.jpg)

### Menu
![Menu](https://user-images.githubusercontent.com/78877636/132257899-613c1193-9227-43d7-abb5-d71b06e5a70c.jpg)

### Apple Business Manager screen
Shows details about all connected ABM tokens, here you can also see which one has failed the sync

### Volume Purchase Program screen
Shows details about all connected VPP tokens, here you can also see which one has failed the sync.

### Managed Google Play screen
Shows details about Managed Google Play, here you can also see if it has failed to sync

### Settings screen
Here you can turn services on and off that you want to monitor. If a service is turned on, the flow will run and if it's off it will not.

![Settings](https://user-images.githubusercontent.com/78877636/132257956-01a4e017-9169-4cab-a38f-c7b8958e3a83.jpg)

### About
Quick info about the app and where to reach out if you have feedback or questions.
