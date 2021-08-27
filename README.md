# Prodinfo Restore TegraScript
A script to restore a prodinfo backup on your Switch

Can restore a full PRODINFO backup, or an automatic backup from [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere), on sysMMC and emuMMC.

Before restoration, a backup of your current PRODINFO is made *-/tegraexplorer/prodinfo/PRODINFO_BACKUP.bin-*

# Warning

DO NOT USE THIS SCRIPT IF YOU DON'T KNOW WHAT IT DOES!

This will OVERWRITE your PRODINFO.

This should only be used as a recover attempt if you messed up with your PRODINFO.

There is no verification of the PRODINFO backup besides its size.

# How To Use

You will need the latest release of [Hekate](https://github.com/CTCaer/hekate/releases) and [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer/releases).

Extract the `bootloader` from the Hekate release on your SD.
Place the `ProdinfoRestore.te` script on your sd.
Place your PRODINFO backup on your SD root and rename it to `prodinfo.bin`.
Insert your SD in your Switch and launch the TegraExplorer payload.
Browse your SD and launch the `ProdinfoRestore.te` script.
