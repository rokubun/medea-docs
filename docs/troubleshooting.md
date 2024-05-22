## Access Medea Dashboard
### Using USB and a PC with Linux

 1. Connect your PC directly to the Medea's USB-C port using a USB cable.
 2. Go to the dashboard as described in step 5 of the [quick start guide](quick_start_guide.md) using the address http://medea-medea_ID.local. If it works, skip the other steps; you already have access to the dashboard.
 3. Go to the **network settings** in the Ubuntu settings.
 4. Find the USB *wired* interface listed as *USB Ethernet* or *Linux Ethernet*.
 5. Configure the interface in the **IPv4 tab**, and select the IPv4 Method as *Manual*.
 6. In Addresses, enter `10.0.0.2` as the **Address**, `255.255.255.0` as the **Netmask**, and `10.0.0.1` as the **Gateway**.
  <img src="/images/network_settings.png" style="width: auto;" />
 7. Apply the changes.
 8. Turn off the interface toggle and then turn it back on.
 9. You can access the device dashboard by opening http://10.0.0.2 in your browser.
## Convert from rbf to Rinex v3

### Using Medea's Dashboard

 1. Connect to the MEDEA dashboard using a web browser as explained above.
 2. Go to the logger's page.
 3. On the RBF file element, press the button shown on the picture.
 <img src="/images/rbf2rnx.png" style="width: auto; border: 1px solid black;" />
 This option is only available if no remote service is selected in the Push datasets selector on the logger's page.

### Using JASON GNSS Converter
[JASON GNSS Converter](https://jason.rokubun.cat/converter) is free to use, but it requries having an account.

 1. Choose or drop the rbf file.
 2. Press *CONVERT FILE* button.
 3. Press *DOWNLOAD RESULTS (.ZIP)* button.

<img src="/images/jason_converter.png" style="width: auto; border: 1px solid black;" />

### Using RTKLIB
Use the following command from [RTKLIB]( https://rtklib.com/):

`convbin -r ubx -f 10 -scan -v 3 -od -os <file_to_convert.rbf>`


## Change country

Steps to change the country assigned to the device, which is used in the filename of the generated RINEX files.

<img src="/images/change_country_1.png" style="width: auto; border: 1px solid black;" />

- Open the dashboard Menu.
<div style="margin: 2rem"></div>

<div width="100%" align="center">
    <img src="/images/change_country_2.png" style="width: auto; border: 1px solid black;" />   
</div>

- Go to the Settings page.
<div style="margin: 2rem"></div>

<img src="/images/change_country_3.png" style="width: auto; border: 1px solid black;" />

- Open the Station settings dropdown.
<div style="margin: 2rem"></div>

<img src="/images/change_country_4.png" style="width: auto; border: 1px solid black;" />

1. Select the station’s country on the country dropdown.
2. Save the changes by clicking the CHANGE button.

<div style="margin: 2rem"></div>