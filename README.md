# Prodinfo Restore TegraScript
A script to restore a prodinfo backup on your Switch

Can restore a full PRODINFO backup, or an automatic backup from [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere), on sysMMC and emuMMC.

Before restoration, a backup of your current PRODINFO is made */tegraexplorer/prodinfo/PRODINFO_BACKUP.bin*

This script uses [TegraScript v3](https://github.com/suchmememanyskill/TegraScript).

You can restore from AMS automatic backup or from `prodinfo.bin` on the root of your sd.

# Warning

DO NOT USE THIS SCRIPT IF YOU DON'T KNOW WHAT IT DOES!

This will OVERWRITE your PRODINFO.

This should only be used as a recover attempt if you messed up with your PRODINFO.

There is no verification of the PRODINFO backup besides its size and if it starts with CAL0.

# How To Use

You will need the latest release of [Hekate](https://github.com/CTCaer/hekate/releases) and [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer/releases).

- Extract the `bootloader` from the Hekate release on your SD.
- Place the `ProdinfoRestore.te` script on your sd.
- Insert your SD in your Switch and launch the TegraExplorer payload.
- Browse your SD and launch the `ProdinfoRestore.te` script.


Thanks to [bleck9999](https://github.com/bleck9999) and [suchmememanyskill](https://github.com/suchmememanyskill) for their advices.