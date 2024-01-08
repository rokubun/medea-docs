## Convert from rbf to Rinex v3

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