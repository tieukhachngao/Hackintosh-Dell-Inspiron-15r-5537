# Hackintosh-Dell-Inspiron-15r-5537
Full kext Hackintosh Dell Inspiron 15r 5537 Macos sierra 10.12.6 (16G1114)
#I.Graphic Card:
  #Using: FakePCIID.kext, FakePCIID_Intel_HD_Graphics.kext and config.plist right values.
        #1. Using Clover Configurator, mount EFI Partition.
        #2. Load the config.plist from mounted EFI/Clover/ using "Import Configuration".
        #3. Set Devices/FakeID/IntelGFX to 0x04128086.
        #4. Set Graphics/ig-plataform-id to 0xa260006.
        #5. Export Configuration > Save.
        #6. Copy FakePCIID.kext and FakePCIIDIntelHD_Graphics.kext to EFI/Clover/kexts/Other.
        #7. Install both FakePCIID.kext and FakePCIIDIntelHD_Graphics.kext with Kext Utility.
        #8. Reboot.
#II.Audio: 
  #Install tool VoodooHDA-2.8.8.pkg will auto fix audio (ALC283)
