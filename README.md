# Microsoft 3D Builder installer

These files are (inexplicably) no longer available in the Microsoft Store.  At least currently, within the US, and using Windows 11, the original link (https://apps.microsoft.com/detail/9wzdncrfj3t6?hl=en-us&gl=PH) reports an error: _This product is unavailable in your market._

Thankfully, these files were helpfully archived by 
[`ccatlett1984`](https://github.com/ccatlett1984/3dbuilder), dated 8/29/2023, but I do not know if that was the latest version.

---

### Authenticity

I ran [Microsoft's Sysinternals sigcheck](https://learn.microsoft.com/en-us/sysinternals/downloads/sigcheck) utility to confirm the authenticity of these files.  Click below to see the file hashes and sigcheck output:

<details>
<summary> sigcheck output and file hashes for the files within this repository</summary>

```cmd
C:\Users\sure-fire\Downloads\3D-builder>..\sysinternalsSuite\sigcheck.exe -h *.App*

Sigcheck v2.90 - File version and signature viewer
Copyright (C) 2004-2022 Mark Russinovich
Sysinternals - www.sysinternals.com

C:\Users\sure-fire\Downloads\3D-builder\Microsoft.3DBuilder_20.0.4.0_neutral_~_8wekyb3d8bbwe.AppxBundle:
        Verified:       Signed
        Signing date:   7:39 PM 8/29/2023
        Publisher:      Microsoft Corporation
        Company:        n/a
        Description:    n/a
        Product:        n/a
        Prod version:   n/a
        File version:   n/a
        MachineType:    n/a
        MD5:    CC6B44B7A843EA58F1D95F04B939BA39
        SHA1:   A774D39833CC9671F4CFBB1150E13442EBA064BE
        PESHA1: A774D39833CC9671F4CFBB1150E13442EBA064BE
        PE256:  B01AD9F297208E4C4491A15CF34B669756DDFAB4EC4C54EEC8BF043D50A3E805
        SHA256: B01AD9F297208E4C4491A15CF34B669756DDFAB4EC4C54EEC8BF043D50A3E805
        IMP:    n/a
C:\Users\sure-fire\Downloads\3D-builder\Microsoft.UI.Xaml.2.0_2.1810.18004.0_x64__8wekyb3d8bbwe.Appx:
        Verified:       Signed
        Signing date:   11:20 AM 2/8/2019
        Publisher:      Microsoft Corporation
        Company:        n/a
        Description:    n/a
        Product:        n/a
        Prod version:   n/a
        File version:   n/a
        MachineType:    n/a
        MD5:    107E44C2737FD3C6DFD280E2DD1D52B9
        SHA1:   784246407DD5EBE49A6986B6CC2B9E83EFFAB74E
        PESHA1: 784246407DD5EBE49A6986B6CC2B9E83EFFAB74E
        PE256:  120D736C81563C833CFC8A3E082DB4A5A92918FBEC1C5621E5D0A36FEA42BCB4
        SHA256: 120D736C81563C833CFC8A3E082DB4A5A92918FBEC1C5621E5D0A36FEA42BCB4
        IMP:    n/a
C:\Users\sure-fire\Downloads\3D-builder\Microsoft.VCLibs.120.00_12.0.21005.1_x64__8wekyb3d8bbwe.Appx:
        Verified:       Signed
        Signing date:   2:47 PM 10/9/2013
        Publisher:      Microsoft Corporation
        Company:        n/a
        Description:    n/a
        Product:        n/a
        Prod version:   n/a
        File version:   n/a
        MachineType:    n/a
        MD5:    28014B7B1FCBF83FAF30462946746DF0
        SHA1:   9671E25D9EADCBF900E3371D7F405261496F4D77
        PESHA1: 9671E25D9EADCBF900E3371D7F405261496F4D77
        PE256:  64DD765B88D1983C09EBB33DC631BDFEFB415F45F29177AB423BBC12C506E64F
        SHA256: 64DD765B88D1983C09EBB33DC631BDFEFB415F45F29177AB423BBC12C506E64F
        IMP:    n/a
C:\Users\sure-fire\Downloads\3D-builder\Microsoft.VCLibs.140.00_14.0.33519.0_x64__8wekyb3d8bbwe.Appx:
        Verified:       Signed
        Signing date:   1:30 PM 1/29/2024
        Publisher:      Microsoft Corporation
        Company:        n/a
        Description:    n/a
        Product:        n/a
        Prod version:   n/a
        File version:   n/a
        MachineType:    n/a
        MD5:    38C974B0D873031E25B196982D4F1B08
        SHA1:   00C5A18B3243C99296724D4C02975BA8FC3FF353
        PESHA1: 00C5A18B3243C99296724D4C02975BA8FC3FF353
        PE256:  9C17B521F9D690A1F504DA5108ED6EEC5669EB3A8FD1331EEF43E40D84E74283
        SHA256: 9C17B521F9D690A1F504DA5108ED6EEC5669EB3A8FD1331EEF43E40D84E74283
        IMP:    n/a
C:\Users\sure-fire\Downloads\3D-builder\Microsoft.WindowsPreview.Kinect.8.1_2.0.1410.19000_x64__8wekyb3d8bbwe.Appx:
        Verified:       Signed
        Signing date:   10:50 AM 10/20/2014
        Publisher:      Microsoft Corporation
        Company:        n/a
        Description:    n/a
        Product:        n/a
        Prod version:   n/a
        File version:   n/a
        MachineType:    n/a
        MD5:    FBFCF7034FDC25BD7AF23E32CDED0DDB
        SHA1:   52D7ACDB671B5A8BC8F1D4288A137B60F6F075E5
        PESHA1: 52D7ACDB671B5A8BC8F1D4288A137B60F6F075E5
        PE256:  005BC2D247F853BC2E2F313DF69F4946319FEAF433E50362D9AB82E705B7D819
        SHA256: 005BC2D247F853BC2E2F313DF69F4946319FEAF433E50362D9AB82E705B7D819
        IMP:    n/a```
```
</details>

----

### Installation steps

1. Create a '3d-builder' folder within your Downloads folder.
2. Download the contents of this repo into that folder.
3. From a Powershell command line, paste in the following two commands:
```powershell
cd $HOME\Downloads\3d-builder

Get-Childitem $filePath -filter *.appx| %{Add-AppxPackage -Path $_.FullName}

Get-Childitem $filePath -filter *.appxbundle | %{Add-AppxPackage -Path $_.FullName}
```

If you don't see "3d Builder" in your start menu, then double-click on the `Microsoft.3DBuilder_20.0.4.0_neutral_~_8wekyb3d8bbwe` file to interactively install it.
