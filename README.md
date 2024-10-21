<h3 align="center">config base by <a href="https://github.com/flawsv/apb/releases/" target="_blank">Flaws</a></h3>
<h3 align="center"></h3>

>[!NOTE]
> 🇷🇺
>
> # Перед установкой обратите внимание, что если ваша система имеет оперативной памяти больше чем 32 гигабайт
то производите установку из папки "Config 32GB RAM+", если же у вас оперативной памяти меньше 32 гигабайт,
производите установку из папки "Config 32GB RAM-".

>[!NOTE]
> 🇬🇧
>
> # Before installation, please note that if your system has more than 32 gigabytes of RAM, then install from the "Config 32GB RAM+" folder, but if you have less than 32 gigabytes of RAM, then install from the "Config 32GB RAM-" folder.

# Launch Arguments

- `-language=1031`                  - Sets game to load with custom localization
- `-nosteam`                        - Disables Steam integration so you'll have no overlay and no Steam login
- `-nomovies` / `-nomoviesstartup`  - Removes loading screens
- `-nosplash`                       - Removes initial splash screen upon boot

Target Field Example
`"C:\Games\Steam\steamapps\common\APB Reloaded\Binaries\APB.exe" -nomovies -nosplash -language=`

Language identifiers
`№:GER=1031; RUS=1049`
