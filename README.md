
![Latest Release](https://img.shields.io/github/v/release/GwendolyneFreddy/Trovador_REO?include_prereleases&color=darkred)<a name="top" id="top"> </a>
![GitHub (Pre-)Release Date](https://img.shields.io/github/release-date-pre/GwendolyneFreddy/Trovador_REO?color=gold)
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20macOS%20%7C%20linux%20%7C%20Project%20Infinity&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=Spanish&color=limegreen)

![Supported games](https://img.shields.io/static/v1?label=supported%20games&message=BGII%20%7C%20BGT%20%7C%20BG2%3AEE%20%7C%20EET&color=dodgerblue)


<div align="center"><h1></a>Trovador REO (WIP)</h1>

<h3>A Spellhold Studios mod for Baldur's Gate II: SoA and ToB (original and EE games),<br>
Baldur's Gate Trilogy and EET<h3>

</div><br>

**Original Author:** Riojano2002  
**Mod Website:** <a href="http://www.shsforums.net/forum/234-miscellaneous-released-mods/">Spellhold Studios</a>  
**Mod Forum:** <a href="TODO">Trovador REO</a><br>

## 

**Note:** This mod was first released at <a href="http://www.clanreo.net/">Clan REO</a> and has been officially mirrored at <a href="http://www.shsforums.net/files/category/95-clan-reo-mirror/">Spellhold Studios Clan REO mirror</a> by <a href="http://www.shsforums.net/user/11965-ancalagon-el-negro/">Ancalagon el Negro</a>.<br>

## 

[![Created Badge](https://badges.pufler.dev/created/GwendolyneFreddy/Trovador_REO?style=plastic)](https://badges.pufler.dev)
![GitHub repo size](https://img.shields.io/github/repo-size/GwendolyneFreddy/Trovador_REO?style=plastic)
[![Visits Badge](https://badges.pufler.dev/visits/GwendolyneFreddy/Trovador_REO?color=cyan&style=plastic)](https://badges.pufler.dev) 
![Maintenance](https://img.shields.io/static/v1?label=maintained%3F&message=yes&color=greenlight&style=plastic)
![GitHub contributors](https://img.shields.io/github/contributors/GwendolyneFreddy/Trovador_REO?color=blueviolet&style=plastic) [![Contributors Display](https://badges.pufler.dev/contributors/GwendolyneFreddy/Trovador_REO?size=30&padding=5&bots=true)](https://badges.pufler.dev)

## 

:page_facing_up: [Read the mod's readme](https://spellholdstudios.github.io/readmes/btl-readme-english.html)

:inbox_tray: [Download the mod at Spellhold Studios](http://www.shsforums.net/files/file/853-trovador-reo)<br>

## 

<div align="center">
<a href="#intro">Overview</a> &#8226; <a href="#compat">Compatibility</a> &#8226; <a href="#installation">Installation</a> &#8226; <a href="#credits">Credits and Acknowledgements</a> &#8226; <a href="#versions">Version History</a></br>
</div>


<hr>


## <a name="intro" id="intro"></a>Overview

<img style="float: left;" src="trovador/readme/images/lrm65s.jpg"> This mod adds to the game a very special troubadour who will tell some never belonged stories, for a few gold pieces. You can find him in Waukeen Promenade. It also adds a shop with curious objects. Is is available in Spanish only.


No solo Volo conoce historias dignas de ser contadas, hay muchos trovadores y bardos que recorren todo Faer�n arriesgando sus vidas para poder alegrar las tabernas que visitamos.

Este mod a�ade a un trovador muy especial, que por unas pocas piezas de oro os narrar� unas historias nunca oidas e incluso los or�genes de ciertos personajes, como el misterioso Riojano, o Artemis Entreri.

4) Updated readme-file

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibility


<hr>


## <a name="installation" id="installation"></a>Installation

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Version History


##### Version 2.5 &nbsp;(October, 2021)

- Renamed *setup-trovador.tp2* -> *trovador.tp2*, and moved it to mod top folder to support AL|EN's "Project Infinity".
- Added Immutability concept.
- Added native BG2:EE and EET compatibility:
    - Added WeiDU's built-in `HANDLE_CHARSETS` function to convert string entries for EE games.
    - Removed items usability restriction flags in description for EE games with `GW_UPDATE_ITM_DESCRIPTION_TO_EE` WeiDU function.
    - Added special item usability restrictions (EE games) with `GW_ITEM_RESTRICT_USABILITY_EE` WeiDU function.
    - Added immunity for opponents immune to poison or to sleep effects (op#324) in EE games.
    - Provided accurate sized NPC portraits for EE games.
- Appended "*tooltip.2da*" whenever relevant.
- Fixed items classes and kits restriction flags, removed useless abilities, fixed wrong effects values and icons...
- Hardcoded items' general names and descriptions (good news for translators!).
- Fixed items descriptions (added missing weight, restriction flags values...).
- Split setup.tra files into separate thematic files for more comfortable readability.
- Completed mod traification.
- TODO then moved it into new :file_folder: "*readme*" folder.
- Removed useless files and :file_folder: "*backup*" folder.
- Lower cased files.
- TODO Included Linux and Mac OS versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Added archive libiconv-1.9.2-1-src.7z with iconv licence info.
- Updated WeiDU installer to v247.
- Uploaded mod to official Spellhold Studios GitHub mirror account.

## 

##### Version 2.4a &nbsp;(November 28, 2009)

- Fixed a bug in the stories books.

## 

##### Version 2.3a &nbsp;(November 15, 2009)

- Provided .tra files.
- Revised and corrected texts.
- Updated WeiDU installer to v211.

## 

##### Version 2.2 &nbsp;(Unknown)

- Included Khaine and Artemis stories.

## 

##### Version 1.0 &nbsp;(Unknown)

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>
