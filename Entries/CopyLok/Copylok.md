# Entry Information:

## DRML Entry Name:

**Copylok**

***

## Authors/Contributors:

* Morlit55 - Entry author

***

## Table of Contents:

* [Entry Information](#entry-information) ([Alt.](#Entry%20Information))
	* [DRML Entry Name](#drml-entry-name) ([Alt.](#DRML%20Entry%20Name))
	* [Authors/Contributors](#authorscontributors)
	* [Table of Contents](#table-of-contents) ([Alt.](#Table%20of%20Contents))
	* [Categories](#categories)
* [DRM Information](#drm-information) ([Alt.](#DRM%20Information))
	* [Names](#names)
	* [Developers](#developers)
	* [Protection Features](#protection-features) ([Alt.](#Protection%20Features))
	* [Overall Description](#overall-description) ([Alt.](#Overall%20Description))
	* [Timeline](#timeline)
	* [Versions & Differences](#versions--differences) ([Alt.](#Versions%20&%20Differences))
		* [Tested](#tested)
		* [Untested](#untested)
	* [Samples](#samples)
		* [Confirmed](#confirmed)
		* [Unconfirmed](#unconfirmed)
	* [Supported Platforms](#supported-platforms) ([Alt.](#Supported%20Platforms))
	* [Software Known to Detect](#software-known-to-detect) ([Alt.](#Software%20Known%20to%20Detect))
	* [Preservation Instructions](#preservation-instructions) ([Alt.](#Preservation%20Instructions))
	* [Compatibility](#Compatibility)
	* [Associated File Attributes](#associated-file-attributes) ([Alt.](#Associated%20File%20Attributes))
	* [Known Manufacturing Information](#known-manufacturing-information) ([Alt.](#Known%20Manufacturing%20Information))
		* [Known Manufacturing Plants](#known-manufacturing-plants) ([Alt.](#Known%20Manufacturing%20Plants))
		* [Known Ringcode Information](#known-ringcode-information) ([Alt.](#Known%20Ringcode%20Information))
			* [Mastering Code](#mastering-code)  ([Alt.](#Mastering%20Code))
			* [Mastering SID Code](#mastering-sid-code)  ([Alt.](#Mastering%20SID%20Code))
			* [Toolstamp or Mastering Code](#toolstamp-or-mastering-code)  ([Alt.](#Toolstamp%20or%20Mastering%20Code))
			* [Mould SID Code](#mould-sid-code)  ([Alt.](#Mould%20SID%20Code))
    	* [Companies Known to Use](#companies-known-to-use) ([Alt.](#Companies%20Known%20to%20Use))
* [Reference Material](#reference-material) ([Alt.](#Reference%20Material))
	* [Media](#media)
	* [Additional Resources](#additional-resources) ([Alt.](#Additional%20Resources))
	* [Footnotes](#footnotes)

*** 

## Categories: 

* Optical Copy Protection

***

## Protection Features:

* Bad Sectors[^Glossaries]
* Disc Check[^Glossaries]
* File Encryption[^Glossaries]
* Ring protection [^Glossaries]

[^Glossaries]: See the "glossaries" section on the main page for an explanation of these terms.

***

# DRM Information:

## Names: 

* CopyLok[^Copylok_website]
* CodeLok[^Codelok_website]
* CopyLock[^BOS_Codelok_definition]

[^Copylok_website]: [Website for Pan Technologies and Copylok](https://web.archive.org/web/20000310232254/http://www.pantechnology.com/)

[^Codelok_website]: [Website for PanLok and CodeLok](https://web.archive.org/web/20010429020714/http://www.panlok.com/productsframe.htm)

[^BOS_Codelok_definition]: Not an official name but the DRM is sometimes reffered to as such due to an old bug in BinaryObjectScanner. [See its Copylok definitions for more info](https://github.com/SabreTools/BinaryObjectScanner/blob/master/BinaryObjectScanner/Protection/CopyLok.cs)

***

## Developers:

* Pan Technologies Limited (August 1997 - July 2001)[^CopyLok_Trademark] [^Copylok_company_history]
* PanLok Limited (October 1999 - August 2001)[^PanLok_company_history]

[^CopyLok_Trademark]: [CopyLok's trademark information.](https://attorneus.com/EM/tm/000618512/)
[^PanLok_company_history]: [Panlok Limited company history trough its active upper management](https://confidam.com/search/company/03861409)
[^Copylok_company_history]: [History of Pan Technologies as seen through the history of its founder](https://confidam.com/search/director/002331520001)


***

## Overall Description:

CopyLok and CodeLok[^Codelok_CDMediaWorld] are both names referring to an optical disc DRM system created by the British company known as Pan Technologies Limited[^Copylok_website] (and later a subsidiary known as PanLok Limited[^Codelok_website]) used exclusively between mid 2000 to mid 2001 by a handfull of European publishers. The DRM is noteworthy for coming in two versions: One utilising SafeDisc style bad sectors and another that mixed bad sectors with LaserLock style ringed sectors[^Ringed_Normal] seemingly used interchangeably.[^Spreadsheet] With the DRM files themselves also being encrypted using TEA.[^CopyLok_by_kilby][^TEA_Wiki] 

[^Ringed_Normal]: [diit.cz testing both versions of Copylok/Codelok](https://diit.cz/clanek/testy-clonecd)

[^CopyLok_by_kilby]: [Killby talking about Codelok and how to break it](https://web.archive.org/web/20010830150527/http://208.50.16.104:80/fravia/kilby_Copylok_Tut_revised.txt)

[^Codelok_CDMediaWorld]: [CopyLok/CodeLok on CDMediaWorld](https://www.cdmediaworld.com/hardware/cdrom/cd_protections_copylok.shtml)

[^TEA_Wiki]: [Wikipedia page on TEA](https://en.wikipedia.org/wiki/Tiny_Encryption_Algorithm)


***

## Timeline: 

#### 1990-2000s
* **1997-08-29**: CopyLok is trademarked by PAN Technology Limited[^CopyLok_Trademark]
* **1999-08-26**: CopyLok is officially announced to the world in a team up between PAN Technology Limited and Media Morphics.[^CopyLok_reveal]
* **1999-10-xx**: PAN Technology Limited forms a subsidiary named PanLok Limited that handles CopyLok from this point on.[^PanLok_company_history][^Codelok_website]
* **2000-07-28**: First known game using CopyLok is released. PAL version of Kiss: Psycho Circus: The Nightmare Child released by Gathering of Developers.[^KISS_Psycho_Circus]
* **2001-xx-xx**: At some point during early 2001. CopyLok is renamed to CodeLok.[^Codelok_website]
* **2001-06-01**: Last known CodeLok game is released. Gangsters 2: Vendetta released by Eidos Interactive.[^Gangsters_2_PCGW]
* **2001-06-xx**: PAN Technology Limited is dissolved and by September the same year the founder had started a new company at the same location. And no more CodeLok games appears after this point.[^Copylok_company_history]
  
[^CopyLok_reveal]: [CopyLok original announcement](https://dns1.cdrinfo.com/d7/content/pan-technology-and-media-morphics-team-present-copylok)

[^KISS_Psycho_Circus]: [KISS Psycho Circus: The Nightmare Child Redump entry](http://redump.org/disc/35908/)

[^Gangsters_2_PCGW]: [Gangsters 2 PCGW entry](https://www.pcgamingwiki.com/wiki/Gangsters_2:_Vendetta)

***

## Versions & Differences: 

#### Tested:

* CopyLok/CodeLok (Normal version)[^Note]

Normal Codelok can be compared to SafeDisc in its function as it, like the aftermentioned DRM, combines erroneous sectors (usually ~750. But see Samples for outliers) within the first 10k sectors of the CD with a disc check relying on said errors.[^CopyLok_by_kilby] The biggest difference though and the main way to differentiate SafeDisc from normal CopyLok is that the associated files are baked into the main executable rather than found loose on the disc. Taking the form of two (sometimes three, see Associated File Attributes for more details) files known as .icd1 and .icd2 with the former being encrypted with TEA.[^CopyLok_by_kilby] 

* CopyLok/CodeLok (Ringed version)[^Note]

In term of function ringed Copylok is identical to normal Copylok in that it still consists of a disc check based on erroneous sectors.[^Testing] Difference here though is that each bad sector is also followed by a LaserLock style ringed sector making the errors come in pairs (for a total of ~1,500) and makes this version of CopyLok extra hard to dump.[^Ringed_CopyLok] 

[^Ringed_CopyLok]: [Redump Forum post talking about the ringed version of CopyLok](http://forum.redump.org/topic/29842/issues-dumping-pc-disc-with-code-lock-copy-protection/)

[^Testing]: Determined from personal testing

[^Note]: There are no known names that differentiates the ringed version of CopyLok from the one purely based on bad sectors. For the sake of this article, the later will be called "normal" and the other "ringed" CopyLok.  


#### Untested:

* BetaLok [^Codelok_website]:
  
A version of Copylok for CD-R discs. No examples have been found.

***

## Samples:
 
#### Confirmed:
> "*" = Ringed Copylok.

* Kiss: Psycho Circus: The Nightmare Child* [^35908][^Spreadsheet]
> Note: First known game with CopyLok. A slight outlier with 1868 erroneous sectors rather than the usual ~1500 for ringed CopyLok. The reason for this is unknown.
* Heavy Metal: F.A.K.K. 2[^49087][^Spreadsheet]
* Blair Witch Volume I: Rustin Parr[^44210][^Spreadsheet]
* Sudden Strike*[^37860][^Spreadsheet]
* Rune [^31708][^Spreadsheet]
* 4x4 Evo [^31557][^Spreadsheet]
* Motocross Mania [^31675][^Spreadsheet]
* Sheep* [^107930][^Spreadsheet]
* Jetfighter IV: Fortress America [^72183][^Spreadsheet]
* The Ward [^71985][^Spreadsheet]
> Note: An outlier with only 255 erroneous sectors rather than the usual ~750. The reason for this is unknown.
* Oni [^48360][^Spreadsheet]
* Cossacks: European Wars* [^38239][^Spreadsheet]
* Serious Sam: The First Encounter [^31674][^Spreadsheet]
* Sudden Strike Forever* [^37881][^Spreadsheet]


[^35908]: [KISS Psycho Circus: The Nightmare Child](http://redump.org/disc/35908/)
[^49087]: [Heavy Metal: F.A.K.K. 2](http://redump.org/disc/49087/)
[^44210]: [Blair Witch Volume I: Rustin Parr](http://redump.org/disc/44210/)
[^37860]: [Sudden Strike](http://redump.org/disc/37860/)
[^31708]: [Rune](http://redump.org/disc/31557/)
[^31557]: [4x4 Evo](http://redump.org/disc/44210/)
[^31675]: [Motocross Mania ](http://redump.org/disc/31675/)
[^107930]: [Sheep](http://redump.org/disc/107930/)
[^72183]: [Jetfighter IV: Fortress America)](http://redump.org/disc/71985/)
[^71985]: [The Ward)](http://redump.org/disc/72183/)
[^48360]: [Oni)](http://redump.org/disc/48360/)
[^38239]: [Cossacks: European Wars)](http://redump.org/disc/38239/)
[^31674]: [Serious Sam: The First Encounter)](http://redump.org/disc/31674/)
[^37881]: [Sudden Strike Forever)](http://redump.org/disc/37881/)


#### Unconfirmed: 

* Tropico* [^108375]
> Note: Only known US game with CopyLok.
* Gangsters 2: Vendetta [^Gangsters_2_PCGW]
> Note: Last known game to make use of CopyLok. Whether it's the ringed or normal version is unknown.

[^108375]: [Tropico](http://redump.org/disc/108375/)

***

## Supported Platforms:

* Microsoft Windows CD-ROM.

***

## Software Known to Detect:

* ProtectionID[^PID]
* BinaryObjectScanner[^BOS_List]
* A-Ray Scanner[^A-Ray_List]

[^BOS_List]: [Binary object scanner github page](https://github.com/SabreTools/BinaryObjectScanner)
[^A-Ray_List]: [Protections detected by A-Ray](https://gbatemp.net/download/a-ray-scanner.37818/)
[^PID]: [Old PiD website link listing PC protections](https://web.archive.org/web/20090830061942/http://pid.gamecopyworld.com/)

***

## Preservation Instructions:

The method for dumping CopyLok varies depending if one is facing the normal or ringed version. SafeDisc style dumping methods will generally work on normal CopyLok[^Ringed_Normal], but some drives (Plextor's and possible others) will "trip" on the erroneous sectors due to a firmware bug and damage the header of the sector following it. This won't stop the resulting dump from working though unless one also 0 or 0x55 the damaged sectors.[^Double_errors]

Ringed CopyLok meanwhile has to be dumped using LaserLock style methods.[^Ringed_Normal] And the same Plextor bug that merely damages a header in normal CopyLok will annihilate a whole bunch of sectors here. Using another drive is recommended.[^Testing] 

[^Double_errors]: [Redump guide to CopyLok talking about the Plextor Firmware bug](http://wiki.redump.org/index.php?title=CodeLock_/_CodeLok_/_CopyLok)

***

## Compatibility:

CopyLok will not work on any version of Windows beyond XP and even XP support is limited.[^Spreadsheet] Using a crack is generally ones only option for running CopyLok games on modern systems.[^Testing]

*** 

## Associated File Attributes:

### File Names

#### ".icd1":

Primary file associated with Copylok. Always found inside the main executable of the protected game and is in itself encrypted with TEA.[^CopyLok_by_kilby] Rip it out from the executable and you have essentially cracked Copylok.[^CopyLok_by_kilby] 

#### ".icd2"

A companion file to .icd1 always found alongside it. Unlike .icd1 it's not encrypted and its exact relationship to CopyLok is unknown.  

#### ".icd0"

Another companion file but unlike .icd2 it's not always present.[^Spreadsheet]

[^Spreadsheet]: [Spreadsheet with info about tested CopyLok games](https://docs.google.com/spreadsheets/d/1t8JFcreqioj8CHeYHDoAoNPI-MjA1cMq9vzYjbrFbTA/edit?gid=0#gid=0)

***

## Known Manufacturing Information:

### Known Manufacturing Plants:

* Only two Mastering Plants are known to have produced CopyLok discs. Disctronics and Sonopress.[^Spreadsheet]
  
### Known Ringcode Information:

* N/A

#### Mastering Code:

* N/A

#### Mastering SID Code:

* N/A

#### Toolstamp or Mastering Code:

* N/A

#### Mould SID Code:

* N/A

***

## Companies Known to Use:

* Take-Two Interactive
  
Used in pretty much all games released between mid 2000 and mid 2001. Also includes their subsidiaries, Gathering of Developers and Rockstar Games.[^Spreadsheet]

* CDV Software
  
The other major publisher to make use of CopyLok. Though not quite to the extent of Take-Two.[^Spreadsheet]

* Empire Interactive
  
Only one game from the company is known to have had CopyLok.[^107930]

* Eidos Interactive
  
Only one game from the company is known to have had CopyLok.[^Gangsters_2_PCGW]

***

# Reference Material:

## Media: 
1. Code 1 error for running a CopyLok game on an unsupported version of Windows [^49087]
   
![CopyLok Error](https://github.com/user-attachments/assets/43ad9099-7ee0-4bc3-8ded-4d100a75215c)

2. Error for running a CopyLok without a CD.[^107930]
 
![CopyLok error 2](https://github.com/user-attachments/assets/eb1fbd55-e65f-44e6-9442-adf6fd4f51b4)


***

## Additional Resources:

***

### Footnotes:


