# NRF5340-DK BLE notification and indication for the same characteristic 
 
This is a test project, which shows a problem with notificaton for the BLE characteristic with flags
```
BT_GATT_CHRC_READ |  BT_GATT_CHRC_NOTIFY | BT_GATT_CHRC_INDICATE 
```
The problem is: when I subscribe from nRF Connect Android app to the nodifications of Button state service, the app receives indications instead of notifications. In the app I also see, that it switches to "Indications"


