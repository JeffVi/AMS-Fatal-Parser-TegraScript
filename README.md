# AMS Fatal Parser TegraScript
A script to parse AMS fatal report on your switch

Can parse reports stored in `atmosphere/fatal_errors`.

This script uses [TegraScript v3](https://github.com/suchmememanyskill/TegraScript).

# Features

Select the report you want to parse to display the error code and the title ID.
Display the title/sysmodule name (titles database from [SwitchBrew](https://switchbrew.org/wiki/Title_list) and sysmodules database from [ndeadly](https://gist.github.com/ndeadly/a4b8c01bb453028cd0008f282098f696)).

# How To Use

You will need the latest release of [Hekate](https://github.com/CTCaer/hekate/releases) and [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer/releases).

- Extract the `bootloader` from the Hekate release on your SD.
- Place the `FatalParse.te` script on your sd.
- Insert your SD in your Switch and launch the TegraExplorer payload.
- Browse your SD and launch the `FatalParse.te` script.
- Choose the report you want to parse.