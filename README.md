## Follow these instructions

First run the Office deployment tool and extract the files onto a folder.

Rename the first file to

```bash
configuration.xml
```

Delete all the text in the first file and paste the following text

```bash
<Configuration>
  <Add OfficeClientEdition="64"  Channel="PerpetualVL2024">
     <Product ID="ProPlus2024Volume" PIDKEY="#####-#####-#####-#####-#####" >
         <Language ID="en-us" />
    </Product>
  </Add>
  <RemoveMSI />
  <Property Name="AUTOACTIVATE" Value="1" />
</Configuration>
```

And delete the remaining files except the setup.exe file

Now open this folder in CMD

```bash
setup /configure configuration.xml
```

Wait for a few minutes as the files are being downloaded, then run this command again

```bash
setup /download configuration.xml
```

Installation will begin

Open MS Word and go to Account and Activate the license using the below code

```bash
Y63J7-9RNDJ-GD3BV-BDKBP-HH966
```

