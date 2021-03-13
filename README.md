# CS:GO Market Analysis

> Some interesting stats from the [CS:GO Steam community market](https://steamcommunity.com/market/search?appid=730).

## Dataset

The data was collected by scraping Steam market pages using `CollectData.ipynb`. Collection took ~4 days with Steam's rate-limiting being the main bottleneck. Overall, `10,125` items were collected. My pre-collected `dataset.pkl` is available upon request.

### Counts

<details>
<summary>View Counts</summary>

|item_type|item_type (counts)|weapon|weapon (counts)|knife_type|knife_type (counts)|collection|collection (counts)|type_rare|type_rare (counts)|condition|condition (counts)|price_group|price_group (counts)|is_stattrak|is_stattrak (counts)|is_souvenir|is_souvenir (counts)|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|autographcap|`12`|MP5-SD|`93`|Skeleton|`65`|The Blacksite Collection|`3`|Base|`164`|Battle-Scarred|`1817`|$1000-$2000|`140`|True|`3289`|True|`827`|
|key|`24`|R8 Revolver|`121`|Nomad|`77`|The Assault Collection|`22`|Extraordinary|`268`|Well-Worn|`1882`|$10-$100|`1747`|False|`6404`|False|`9298`|
|case|`32`|Negev|`126`|Paracord|`78`|The Aztec Collection|`27`|Industrial|`802`|Factory New|`1905`|<$1|`2609`|||||
|package|`96`|M249|`128`|Survival|`83`|The Office Collection|`27`|Consumer|`927`|Field-Tested|`2130`|$100-$1000|`2620`|||||
|gloves|`268`|SSG 08|`183`|Classic|`88`|The Dust Collection|`36`|Classified|`1027`|Minimal Wear|`2227`|$1-$10|`3009`|||||
|weapon|`9693`|SCAR-20|`189`|Ursus|`111`|The Arms Deal Collection|`48`|Restricted|`1721`|||||||||
|||MAG-7|`199`|Butterfly|`113`|The Vertigo Collection|`50`|Mil-Spec|`2444`|||||||||
|||G3SG1|`200`|Talon|`114`|The Gods and Monsters Collection|`50`|Covert|`2772`|||||||||
|||MP9|`204`|Bowie|`115`|The Inferno Collection|`54`|||||||||||
|||P2000|`205`|Huntsman|`119`|The Militia Collection|`55`|||||||||||
|||MP7|`209`|Falchion|`124`|The Bank Collection|`62`|||||||||||
|||USP-S|`209`|Shadow Daggers|`124`|The Chop Shop Collection|`65`|||||||||||
|||FAMAS|`212`|Navaja|`126`|The eSports 2013 Collection|`66`|||||||||||
|||SG 553|`216`|Stiletto|`126`|The Alpha Collection|`71`|||||||||||
|||M4A1-S|`216`|Karambit|`142`|The Arms Deal 2 Collection|`72`|||||||||||
|||CZ75-Auto|`218`|M9|`154`|The Baggage Collection|`75`|||||||||||
|||Dual Berettas|`219`|Bayonet|`163`|The Rising Sun Collection|`75`|||||||||||
|||AWP|`220`|Flip|`163`|The Control Collection|`79`|||||||||||
|||Sawed-Off|`229`|Gut|`169`|The Norse Collection|`80`|||||||||||
|||Desert Eagle|`229`|||The eSports 2013 Winter Collection|`82`|||||||||||
|||Nova|`234`|||The Ancient Collection|`83`|||||||||||
|||M4A4|`234`|||The Canals Collection|`83`|||||||||||
|||XM1014|`235`|||The Havoc Collection|`85`|||||||||||
|||UMP-45|`235`|||The Nuke Collection|`87`|||||||||||
|||Galil AR|`238`|||The Arms Deal 3 Collection|`102`|||||||||||
|||Five-SeveN|`238`|||The Phoenix Collection|`104`|||||||||||
|||PP-Bizon|`246`|||The Cobblestone Collection|`105`|||||||||||
|||AUG|`246`|||The Winter Offensive Collection|`106`|||||||||||
|||Glock-18|`252`|||The Bravo Collection|`112`|||||||||||
|||Tec-9|`256`|||The Breakout Collection|`118`|||||||||||
|||MAC-10|`291`|||The Train Collection|`122`|||||||||||
|||P90|`293`|||The Chroma 2 Collection|`124`|||||||||||
|||AK-47|`302`|||The Italy Collection|`124`|||||||||||
|||P250|`314`|||The Vanguard Collection|`124`|||||||||||
|||Knife|`2254`|||The Chroma Collection|`126`|||||||||||
|||||||The Cache Collection|`128`|||||||||||
|||||||The Lake Collection|`130`|||||||||||
|||||||The Safehouse Collection|`130`|||||||||||
|||||||The Mirage Collection|`136`|||||||||||
|||||||The eSports 2014 Summer Collection|`138`|||||||||||
|||||||The Chroma 3 Collection|`140`|||||||||||
|||||||The Overpass Collection|`147`|||||||||||
|||||||The Clutch Collection|`150`|||||||||||
|||||||The Falchion Collection|`154`|||||||||||
|||||||The Dust 2 Collection|`154`|||||||||||
|||||||The Wildfire Collection|`156`|||||||||||
|||||||The Spectrum Collection|`156`|||||||||||
|||||||The 2018 Inferno Collection|`156`|||||||||||
|||||||The Danger Zone Collection|`156`|||||||||||
|||||||The Operation Hydra Collection|`157`|||||||||||
|||||||The CS20 Collection|`158`|||||||||||
|||||||The Horizon Collection|`160`|||||||||||
|||||||The Prisma Collection|`160`|||||||||||
|||||||The Revolver Case Collection|`160`|||||||||||
|||||||The Operation Broken Fang Collection|`160`|||||||||||
|||||||The Shadow Collection|`160`|||||||||||
|||||||The Fracture Collection|`160`|||||||||||
|||||||The Glove Collection|`162`|||||||||||
|||||||The Gamma 2 Collection|`164`|||||||||||
|||||||The Shattered Web Collection|`166`|||||||||||
|||||||The Gamma Collection|`166`|||||||||||
|||||||The 2018 Nuke Collection|`167`|||||||||||
|||||||The Prisma 2 Collection|`170`|||||||||||
|||||||The Spectrum 2 Collection|`170`|||||||||||
|||||||The Huntsman Collection|`178`|||||||||||

</details>

### Median Sell Price

<details>
<summary>View Median Sell Prices</summary>

|item_type|item_type (median price)|weapon|weapon (median price)|knife_type|knife_type (median price)|collection|collection (median price)|type_rare|type_rare (median price)|condition|condition (median price)|price_group|price_group (median price)|is_stattrak|is_stattrak (median price)|is_souvenir|is_souvenir (median price)|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|case|`0.59`|MP5-SD|`0.51`|Navaja|`96.77`|The Bank Collection|`0.16`|Consumer|`0.47`|Battle-Scarred|`4.09`|<$1|`0.34`|False|`4.19`|True|`4.55`|
|weapon|`5.69`|R8 Revolver|`0.66`|Shadow Daggers|`113.31`|The Blacksite Collection|`0.19`|Mil-Spec|`0.83`|Well-Worn|`4.2`|$1-$10|`3.23`|True|`11.33`|False|`6.95`|
|key|`6.3`|M249|`0.66`|Gut|`125.0`|The Train Collection|`0.42`|Industrial|`2.18`|Field-Tested|`5.07`|$10-$100|`28.21`|||||
|autographcap|`15.85`|SCAR-20|`0.77`|Falchion|`135.56`|The Clutch Collection|`0.64`|Restricted|`3.15`|Minimal Wear|`8.71`|$100-$1000|`214.52`|||||
|package|`16.4`|G3SG1|`0.88`|Huntsman|`161.0`|The Dust 2 Collection|`0.66`|Base|`10.69`|Factory New|`11.21`|$1000-$2000|`1355.14`|||||
|gloves|`294.7`|UMP-45|`0.96`|Nomad|`161.42`|The Spectrum 2 Collection|`0.86`|Classified|`13.34`|||||||||
|||Negev|`1.06`|Stiletto|`161.79`|The Gamma 2 Collection|`0.87`|Covert|`176.61`|||||||||
|||Sawed-Off|`1.08`|Ursus|`161.99`|The Spectrum Collection|`0.94`|Extraordinary|`294.7`|||||||||
|||Nova|`1.1`|Classic|`169.55`|The Chroma 3 Collection|`0.96`|||||||||||
|||MAG-7|`1.15`|Bowie|`170.17`|The Italy Collection|`0.96`|||||||||||
|||PP-Bizon|`1.16`|Survival|`174.06`|The Lake Collection|`0.98`|||||||||||
|||MP9|`1.2`|Flip|`185.58`|The CS20 Collection|`1.06`|||||||||||
|||CZ75-Auto|`1.26`|Paracord|`225.52`|The Danger Zone Collection|`1.12`|||||||||||
|||MP7|`1.31`|Bayonet|`305.02`|The Glove Collection|`1.14`|||||||||||
|||P2000|`1.34`|Talon|`308.5`|The Safehouse Collection|`1.18`|||||||||||
|||Dual Berettas|`1.38`|M9|`350.2`|The Horizon Collection|`1.28`|||||||||||
|||Tec-9|`1.6`|Karambit|`458.72`|The Gamma Collection|`1.31`|||||||||||
|||Galil AR|`1.8`|Skeleton|`480.72`|The Prisma Collection|`1.38`|||||||||||
|||MAC-10|`1.93`|Butterfly|`548.24`|The 2018 Nuke Collection|`1.38`|||||||||||
|||XM1014|`1.96`|||The Operation Broken Fang Collection|`1.49`|||||||||||
|||Five-SeveN|`2.04`|||The Prisma 2 Collection|`1.54`|||||||||||
|||SG 553|`2.04`|||The Fracture Collection|`1.59`|||||||||||
|||P250|`2.1`|||The 2018 Inferno Collection|`1.67`|||||||||||
|||SSG 08|`2.73`|||The Havoc Collection|`1.75`|||||||||||
|||P90|`2.8`|||The Inferno Collection|`1.84`|||||||||||
|||AUG|`3.12`|||The Shattered Web Collection|`1.85`|||||||||||
|||Glock-18|`3.37`|||The Breakout Collection|`1.87`|||||||||||
|||FAMAS|`3.94`|||The Overpass Collection|`1.95`|||||||||||
|||Desert Eagle|`8.71`|||The Chroma Collection|`2.19`|||||||||||
|||USP-S|`12.5`|||The Alpha Collection|`2.21`|||||||||||
|||M4A4|`14.62`|||The Shadow Collection|`2.24`|||||||||||
|||M4A1-S|`15.7`|||The Chroma 2 Collection|`2.26`|||||||||||
|||AWP|`28.6`|||The Revolver Case Collection|`2.45`|||||||||||
|||AK-47|`40.06`|||The Aztec Collection|`2.46`|||||||||||
|||Knife|`209.08`|||The Mirage Collection|`2.54`|||||||||||
|||||||The Control Collection|`2.62`|||||||||||
|||||||The Canals Collection|`2.81`|||||||||||
|||||||The Vertigo Collection|`2.81`|||||||||||
|||||||The Falchion Collection|`2.92`|||||||||||
|||||||The Phoenix Collection|`3.09`|||||||||||
|||||||The Wildfire Collection|`3.3`|||||||||||
|||||||The Office Collection|`3.31`|||||||||||
|||||||The Cache Collection|`3.35`|||||||||||
|||||||The Huntsman Collection|`3.51`|||||||||||
|||||||The eSports 2013 Winter Collection|`3.86`|||||||||||
|||||||The Chop Shop Collection|`4.05`|||||||||||
|||||||The Baggage Collection|`4.76`|||||||||||
|||||||The eSports 2014 Summer Collection|`4.76`|||||||||||
|||||||The Vanguard Collection|`4.82`|||||||||||
|||||||The Gods and Monsters Collection|`5.03`|||||||||||
|||||||The Norse Collection|`5.1`|||||||||||
|||||||The Cobblestone Collection|`5.36`|||||||||||
|||||||The Militia Collection|`5.79`|||||||||||
|||||||The Ancient Collection|`6.41`|||||||||||
|||||||The Winter Offensive Collection|`6.55`|||||||||||
|||||||The Arms Deal 3 Collection|`6.69`|||||||||||
|||||||The Operation Hydra Collection|`6.84`|||||||||||
|||||||The Nuke Collection|`7.41`|||||||||||
|||||||The Arms Deal 2 Collection|`8.26`|||||||||||
|||||||The eSports 2013 Collection|`11.96`|||||||||||
|||||||The Bravo Collection|`14.3`|||||||||||
|||||||The Dust Collection|`16.06`|||||||||||
|||||||The Assault Collection|`23.78`|||||||||||
|||||||The Rising Sun Collection|`42.33`|||||||||||
|||||||The Arms Deal Collection|`62.84`|||||||||||

</details>

### Average Annual Return

<details>
<summary>View Average Annual Returns</summary>

|item_type|item_type (annual return*)|weapon|weapon (annual return*)|knife_type|knife_type (annual return*)|collection|collection (annual return*)|type_rare|type_rare (annual return*)|condition|condition (annual return*)|price_group|price_group (annual return*)|is_stattrak|is_stattrak (annual return*)|is_souvenir|is_souvenir (annual return*)|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|gloves|`0.027`|M4A1-S|`0.026`|Paracord|`-0.015`|The Clutch Collection|`-0.172`|Extraordinary|`0.027`|Factory New|`0.141`|$100-$1000|`0.102`|True|`0.082`|False|`0.161`|
|weapon|`0.158`|AWP|`0.087`|Ursus|`-0.008`|The Prisma Collection|`-0.026`|Covert|`0.091`|Battle-Scarred|`0.15`|<$1|`0.129`|False|`0.202`|True|`0.164`|
|key|`0.282`|Knife|`0.091`|Stiletto|`0.014`|The Spectrum 2 Collection|`-0.006`|Classified|`0.134`|Well-Worn|`0.153`|$10-$100|`0.199`|||||
|package|`0.522`|Glock-18|`0.101`|Navaja|`0.018`|The Train Collection|`0.005`|Restricted|`0.175`|Minimal Wear|`0.161`|$1000-$2000|`0.218`|||||
|autographcap|`0.69`|Five-SeveN|`0.127`|Gut|`0.054`|The Gamma 2 Collection|`0.008`|Mil-Spec|`0.183`|Field-Tested|`0.171`|$1-$10|`0.22`|||||
|case|`0.693`|UMP-45|`0.128`|Huntsman|`0.075`|The Overpass Collection|`0.023`|Industrial|`0.257`|||||||||
|||CZ75-Auto|`0.135`|Flip|`0.076`|The Spectrum Collection|`0.031`|Consumer|`0.282`|||||||||
|||Sawed-Off|`0.146`|Bayonet|`0.087`|The Danger Zone Collection|`0.031`|Base|`0.52`|||||||||
|||P2000|`0.147`|Karambit|`0.087`|The Dust 2 Collection|`0.054`|||||||||||
|||P250|`0.157`|M9|`0.089`|The Gamma Collection|`0.056`|||||||||||
|||R8 Revolver|`0.158`|Bowie|`0.09`|The Blacksite Collection|`0.06`|||||||||||
|||M4A4|`0.166`|Falchion|`0.114`|The Breakout Collection|`0.064`|||||||||||
|||XM1014|`0.167`|Shadow Daggers|`0.13`|The Chroma 3 Collection|`0.078`|||||||||||
|||Tec-9|`0.171`|Talon|`0.139`|The Glove Collection|`0.088`|||||||||||
|||PP-Bizon|`0.171`|Classic|`0.154`|The Chroma 2 Collection|`0.095`|||||||||||
|||G3SG1|`0.175`|Butterfly|`0.286`|The Horizon Collection|`0.097`|||||||||||
|||AK-47|`0.178`|Nomad|`0.425`|The Bank Collection|`0.104`|||||||||||
|||SG 553|`0.185`|Skeleton|`0.465`|The Vanguard Collection|`0.108`|||||||||||
|||P90|`0.192`|Survival|`0.591`|The Italy Collection|`0.131`|||||||||||
|||SCAR-20|`0.197`|||The Revolver Case Collection|`0.134`|||||||||||
|||Nova|`0.198`|||The 2018 Inferno Collection|`0.136`|||||||||||
|||MP7|`0.215`|||The Safehouse Collection|`0.137`|||||||||||
|||AUG|`0.218`|||The Cache Collection|`0.143`|||||||||||
|||FAMAS|`0.224`|||The Lake Collection|`0.145`|||||||||||
|||SSG 08|`0.242`|||The Phoenix Collection|`0.149`|||||||||||
|||Dual Berettas|`0.243`|||The Nuke Collection|`0.152`|||||||||||
|||Galil AR|`0.248`|||The Inferno Collection|`0.183`|||||||||||
|||USP-S|`0.252`|||The Falchion Collection|`0.184`|||||||||||
|||Desert Eagle|`0.253`|||The Wildfire Collection|`0.184`|||||||||||
|||MP9|`0.264`|||The Arms Deal 3 Collection|`0.196`|||||||||||
|||Negev|`0.273`|||The eSports 2014 Summer Collection|`0.197`|||||||||||
|||MAG-7|`0.286`|||The Chroma Collection|`0.204`|||||||||||
|||MAC-10|`0.287`|||The Huntsman Collection|`0.21`|||||||||||
|||M249|`0.322`|||The Shadow Collection|`0.213`|||||||||||
|||MP5-SD|`0.413`|||The Mirage Collection|`0.248`|||||||||||
|||||||The Arms Deal 2 Collection|`0.249`|||||||||||
|||||||The eSports 2013 Collection|`0.254`|||||||||||
|||||||The Winter Offensive Collection|`0.285`|||||||||||
|||||||The Dust Collection|`0.293`|||||||||||
|||||||The eSports 2013 Winter Collection|`0.315`|||||||||||
|||||||The Aztec Collection|`0.331`|||||||||||
|||||||The Cobblestone Collection|`0.339`|||||||||||
|||||||The 2018 Nuke Collection|`0.348`|||||||||||
|||||||The Bravo Collection|`0.349`|||||||||||
|||||||The Militia Collection|`0.355`|||||||||||
|||||||The Alpha Collection|`0.368`|||||||||||
|||||||The Arms Deal Collection|`0.394`|||||||||||
|||||||The Chop Shop Collection|`0.431`|||||||||||
|||||||The Vertigo Collection|`0.44`|||||||||||
|||||||The Operation Hydra Collection|`0.453`|||||||||||
|||||||The Baggage Collection|`0.48`|||||||||||
|||||||The Office Collection|`0.492`|||||||||||
|||||||The Gods and Monsters Collection|`0.496`|||||||||||
|||||||The CS20 Collection|`0.606`|||||||||||
|||||||The Assault Collection|`0.613`|||||||||||
|||||||The Rising Sun Collection|`0.736`|||||||||||
|||||||The Shattered Web Collection|`1.048`|||||||||||
|||||||The Canals Collection|`4.382`|||||||||||
|||||||The Norse Collection|`6.485`|||||||||||
|||||||The Ancient Collection|`nan`|||||||||||
|||||||The Control Collection|`nan`|||||||||||
|||||||The Fracture Collection|`nan`|||||||||||
|||||||The Havoc Collection|`nan`|||||||||||
|||||||The Operation Broken Fang Collection|`nan`|||||||||||
|||||||The Prisma 2 Collection|`nan`|||||||||||

</details>

> (*) 10% of outliers in each group and the first year of item sales are removed. "0.2" represents a average annual gain of +20% value. Only unrealized P/L analyzed and market fees are not included.

### Average Daily Volume

<details>
<summary>View Average Daily Volumes</summary>

|item_type|item_type (avg daily volume*)|weapon|weapon (avg daily volume*)|knife_type|knife_type (avg daily volume*)|collection|collection (avg daily volume*)|type_rare|type_rare (avg daily volume*)|condition|condition (avg daily volume*)|price_group|price_group (avg daily volume*)|is_stattrak|is_stattrak (avg daily volume*)|is_souvenir|is_souvenir (avg daily volume*)|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|gloves|`1.187`|Knife|`0.95`|Skeleton|`0.371`|The Baggage Collection|`4.399`|Extraordinary|`1.187`|Well-Worn|`13.137`|$1000-$2000|`0.304`|True|`11.082`|True|`5.093`|
|package|`1.583`|XM1014|`24.804`|Paracord|`0.514`|The Alpha Collection|`4.597`|Covert|`1.56`|Battle-Scarred|`14.816`|$100-$1000|`0.995`|False|`42.83`|False|`30.909`|
|autographcap|`6.115`|M249|`31.816`|Talon|`0.551`|The Militia Collection|`4.799`|Classified|`21.313`|Factory New|`17.659`|$10-$100|`7.14`|||||
|weapon|`27.602`|P90|`33.249`|Nomad|`0.566`|The Office Collection|`5.213`|Restricted|`35.665`|Minimal Wear|`37.305`|$1-$10|`30.322`|||||
|key|`389.297`|Dual Berettas|`34.367`|Survival|`0.621`|The Assault Collection|`5.28`|Industrial|`48.094`|Field-Tested|`64.927`|<$1|`134.089`|||||
|case|`22857.922`|MAG-7|`35.229`|Ursus|`0.626`|The Operation Hydra Collection|`5.815`|Mil-Spec|`65.498`|||||||||
|||Sawed-Off|`35.941`|Stiletto|`0.681`|The Nuke Collection|`6.493`|Consumer|`82.593`|||||||||
|||SCAR-20|`36.393`|Bowie|`0.691`|The Bravo Collection|`7.19`|Base|`375.772`|||||||||
|||MAC-10|`38.383`|Classic|`0.699`|The Mirage Collection|`10.59`|||||||||||
|||Negev|`38.724`|Karambit|`0.998`|The eSports 2013 Collection|`14.196`|||||||||||
|||M4A4|`38.946`|M9|`1.033`|The Vertigo Collection|`15.208`|||||||||||
|||PP-Bizon|`39.068`|Navaja|`1.08`|The Norse Collection|`15.295`|||||||||||
|||CZ75-Auto|`39.157`|Shadow Daggers|`1.099`|The Revolver Case Collection|`18.79`|||||||||||
|||FAMAS|`39.619`|Bayonet|`1.123`|The Cache Collection|`20.004`|||||||||||
|||G3SG1|`39.821`|Flip|`1.348`|The Arms Deal 3 Collection|`20.08`|||||||||||
|||SSG 08|`41.887`|Falchion|`1.397`|The eSports 2014 Summer Collection|`21.003`|||||||||||
|||AK-47|`42.421`|Gut|`1.463`|The Canals Collection|`21.144`|||||||||||
|||SG 553|`43.276`|Huntsman|`1.498`|The Inferno Collection|`21.875`|||||||||||
|||Nova|`44.079`|Butterfly|`1.582`|The Vanguard Collection|`22.06`|||||||||||
|||AUG|`46.046`|||The Overpass Collection|`22.24`|||||||||||
|||Galil AR|`46.977`|||The Shattered Web Collection|`23.097`|||||||||||
|||P250|`47.893`|||The Arms Deal 2 Collection|`25.812`|||||||||||
|||M4A1-S|`48.903`|||The Cobblestone Collection|`26.303`|||||||||||
|||Five-SeveN|`50.994`|||The Arms Deal Collection|`26.673`|||||||||||
|||MP7|`51.513`|||The eSports 2013 Winter Collection|`28.503`|||||||||||
|||MP9|`52.179`|||The Rising Sun Collection|`31.023`|||||||||||
|||P2000|`52.699`|||The Dust Collection|`31.048`|||||||||||
|||Tec-9|`58.691`|||The Winter Offensive Collection|`32.348`|||||||||||
|||AWP|`59.345`|||The Aztec Collection|`32.621`|||||||||||
|||R8 Revolver|`59.87`|||The Wildfire Collection|`33.289`|||||||||||
|||USP-S|`63.567`|||The Chop Shop Collection|`34.624`|||||||||||
|||Desert Eagle|`64.328`|||The Shadow Collection|`34.945`|||||||||||
|||UMP-45|`69.345`|||The Huntsman Collection|`38.99`|||||||||||
|||Glock-18|`84.963`|||The Chroma 3 Collection|`40.94`|||||||||||
|||MP5-SD|`87.642`|||The Gods and Monsters Collection|`41.477`|||||||||||
|||||||The Chroma Collection|`47.401`|||||||||||
|||||||The Gamma Collection|`52.502`|||||||||||
|||||||The CS20 Collection|`57.393`|||||||||||
|||||||The Horizon Collection|`58.926`|||||||||||
|||||||The Falchion Collection|`60.599`|||||||||||
|||||||The Gamma 2 Collection|`61.959`|||||||||||
|||||||The 2018 Nuke Collection|`65.511`|||||||||||
|||||||The Glove Collection|`69.318`|||||||||||
|||||||The Spectrum Collection|`70.38`|||||||||||
|||||||The 2018 Inferno Collection|`75.107`|||||||||||
|||||||The Spectrum 2 Collection|`83.327`|||||||||||
|||||||The Chroma 2 Collection|`113.472`|||||||||||
|||||||The Clutch Collection|`119.712`|||||||||||
|||||||The Dust 2 Collection|`120.26`|||||||||||
|||||||The Prisma Collection|`124.489`|||||||||||
|||||||The Phoenix Collection|`124.939`|||||||||||
|||||||The Breakout Collection|`129.469`|||||||||||
|||||||The Danger Zone Collection|`139.348`|||||||||||
|||||||The Safehouse Collection|`140.04`|||||||||||
|||||||The Italy Collection|`156.474`|||||||||||
|||||||The Train Collection|`164.74`|||||||||||
|||||||The Lake Collection|`166.556`|||||||||||
|||||||The Bank Collection|`435.001`|||||||||||
|||||||The Blacksite Collection|`967.37`|||||||||||
|||||||The Ancient Collection|`nan`|||||||||||
|||||||The Control Collection|`nan`|||||||||||
|||||||The Fracture Collection|`nan`|||||||||||
|||||||The Havoc Collection|`nan`|||||||||||
|||||||The Operation Broken Fang Collection|`nan`|||||||||||
|||||||The Prisma 2 Collection|`nan`|||||||||||

</details>

### Condition

|Condition|Avg. Relative Price to Same-Skin Battle-Scarred |
|-|-|
| Factory New |` 4.564 `|
| Minimal Wear |` 1.745 `|
| Field-Tested |` 1.079 `|
| Well-Worn |` 1.131 `|
| Battle-Scarred |` 1.0 `|


### Model

> A [random forest regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html) was fit to (a random) 70% of the dataset. Given `['collection', 'condition', 'is_souvenir', 'is_stattrak', 'item_type', 'knife_type', 'log_avg_daily_volume', 'log_sell_listings', 'type_rare', 'weapon']` it was tasked with predicting `log_sell_price`. The model achieved a mean squared error of `0.100` and a r2 score of `0.925` on the test set. Below are the items with the highest disagreement between the model's predicted sell price and the items actually listed sell price.

|Undervalued Rank _(model price >>> actual)_|Item|
|-|-|
| 1 | [Boston 2018 Train Souvenir Package](https://steamcommunity.com/market/listings/730/Boston%202018%20Train%20Souvenir%20Package) |
| 2 | [G3SG1 \| Jungle Dashed (Battle-Scarred)](https://steamcommunity.com/market/listings/730/G3SG1%20%7C%20Jungle%20Dashed%20%28Battle-Scarred%29) |
| 3 | [UMP-45 \| Urban DDPAT (Battle-Scarred)](https://steamcommunity.com/market/listings/730/UMP-45%20%7C%20Urban%20DDPAT%20%28Battle-Scarred%29) |
| 4 | [R8 Revolver \| Bone Mask (Battle-Scarred)](https://steamcommunity.com/market/listings/730/R8%20Revolver%20%7C%20Bone%20Mask%20%28Battle-Scarred%29) |
| 5 | [MP9 \| Sand Dashed (Battle-Scarred)](https://steamcommunity.com/market/listings/730/MP9%20%7C%20Sand%20Dashed%20%28Battle-Scarred%29) |

|Overvalued Rank|Item|
|-|-|
| 1 | [MP7 \| Anodized Navy (Factory New)](https://steamcommunity.com/market/listings/730/MP7%20%7C%20Anodized%20Navy%20%28Factory%20New%29) |
| 2 | [Souvenir MAG-7 \| Irradiated Alert (Minimal Wear)](https://steamcommunity.com/market/listings/730/Souvenir%20MAG-7%20%7C%20Irradiated%20Alert%20%28Minimal%20Wear%29) |
| 3 | [StatTrak™ G3SG1 \| Black Sand (Well-Worn)](https://steamcommunity.com/market/listings/730/StatTrak%E2%84%A2%20G3SG1%20%7C%20Black%20Sand%20%28Well-Worn%29) |
| 4 | [Desert Eagle \| Light Rail (Field-Tested)](https://steamcommunity.com/market/listings/730/Desert%20Eagle%20%7C%20Light%20Rail%20%28Field-Tested%29) |
| 5 | [StatTrak™ UMP-45 \| Plastique (Battle-Scarred)](https://steamcommunity.com/market/listings/730/StatTrak%E2%84%A2%20UMP-45%20%7C%20Plastique%20%28Battle-Scarred%29) |

### Plots

![plots](https://user-images.githubusercontent.com/6625384/111043715-a273c400-8409-11eb-805c-20f392a1a232.png)