Obtain Line Notify personal token.
Copy notify_linefolder from custom_components to your custom_components in Home Assistant directory.
Add configuration to configuration.yaml
notify:
  - name: serverchan_notification
    platform: serverchan_notify
    access_token: 'PASTE_YOUR_PERSONAL_TOKEN_HERE'
Reboot your Home Assistant instance.
Call notify.serverchan_notification(with service data described below) from script or automation as you desire.