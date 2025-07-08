# Waterdeep: The Ultimate Location Guide

## I. Travel & Movement

### **Coordinate System**

The map uses a standard `[X, Y, Z]` coordinate system.

- **X-axis:** Left to Right (0 to 3000)
    
- **Y-axis:** Bottom to Top (0 to 4524)
    
- **Z-axis:** Vertical Layer
    
    - `Z > 0`: Above-Ground Structures (Towers, Peaks)
        
    - `Z = 0`: Surface Level (City Streets)
        
    - `Z = -1`: Sewer Level / Shallow Underground
        
    - `Z = -2`: Deeper Dungeons / Undermountain
        

### **Distance & Time Calculation**

Use this formula to calculate the distance between two points on the same Z-level:

> **Distance (pixels)** = `√[ (X₂ - X₁)² + (Y₂ - Y₁)² ]`

_1 pixel is approximately 5 feet._

> **Travel Time (minutes)** = `(Distance in pixels * 5) / Pace`

### **Means of Travel & Pace**

|   |   |   |   |
|---|---|---|---|
|**Travel Method**|**Pace (per minute)**|**Time Modifier**|**Notes**|
|**Walking (Fast)**|400 feet|x 0.75||
|**Walking (Normal)**|300 feet|x 1||
|**Walking (Slow)**|200 feet|x 1.5|Allows for stealth or tracking.|
|**Coach**|N/A|x 0.5|Limited to main roads.|
|**Griffon**|N/A|x 0.1|Requires access to a roost and open landing area.|
|**Sewers**|150 feet|x 2|Difficult terrain, poor visibility, high chance of encounters. Requires a guide or successful navigation checks.|

## II. City Maps

_These maps are linked from your vault and will display as images in Obsidian._

### **City Overview**

![[4 - Worldbuilding/Waterdeep/Waterdeep 11255x15000 NO GRID.jpg]]

### **Wards**

|   |   |
|---|---|
|**Ward**|**Map**|
|**Field Ward**|![[4 - Worldbuilding/Waterdeep/0.0 FIELD WARD.jpg]]|
|**Sea Ward**|![[4 - Worldbuilding/Waterdeep/0.1 SEA WARD.jpg]]|
|**Castle Ward**|![[4 - Worldbuilding/Waterdeep/0.3 CASTLE WARD + MOUNTAINSIDE.jpg]]|
|**Trades Ward**|![[4 - Worldbuilding/Waterdeep/0.4 TRADES WARD.jpg]]|
|**South Ward**|![[4 - Worldbuilding/Waterdeep/0.5 SOUTH WARD.jpg]]|
|**Dock Ward**|![[4 - Worldbuilding/Waterdeep/0.6 DOCK WARD.jpg]]|
|**City of the Dead**|![[4 - Worldbuilding/Waterdeep/0.7 CITY OF THE DEAD.jpg]]|

### **Sewer System**

![[4 - Worldbuilding/Waterdeep/Waterdeep Sewer Map.jpg]]

## III. Comprehensive Location Index

### **Wards & Neighborhoods**

|   |   |   |
|---|---|---|
|**Name**|**Coordinates**|**Description**|
|Mistshore|`[829, 1492, 0]`|The dilapidated north shore of Waterdeep's harbor.|
|Dock Ward|`[1518, 1401, 0]`|Contained the docks, shipbuilding yards, and warehouses. Known for being dirty, smelly, and dangerous.|
|Southern Ward|`[1864, 1171, 0]`|The southeastern sector of the city.|
|Trades Ward|`[1723, 1803, 0]`|The main shopping district of Waterdeep, housing many guildhalls.|
|Castle Ward|`[1347, 2311, 0]`|The central ward of the city.|
|City of the Dead|`[1785, 2275, 0]`|A large cemetery that also doubled as a public park.|
|North Ward|`[1552, 3008, 0]`|The quietest ward of the city, consisting mostly of residential areas.|
|Sea Ward|`[955, 3063, 0]`|The wealthiest ward in Waterdeep, located in the northwest of the city.|
|Field Ward|`[1469, 3699, 0]`|The city's slums, located between the inner and outer walls.|
|Undercliff|`[2296, 2649, 0]`|A rural community just outside the walls of Waterdeep.|

### **Inns**

|   |   |   |   |
|---|---|---|---|
|**Name**|**Coordinates**|**Ward**|**Description**|
|The Pilgrim's Rest|`[721, 3152, 0]`|Sea|Moderately priced, caters to temple visitors.|
|The Wandering Wemic|`[744, 3156, 0]`|Sea|Rooms at 10 gp/night including stabling, valet service, and wine.|
|Dacer's Inn|`[760, 3214, 0]`|Sea||
|Maerghoun's Inn|`[806, 3181, 0]`|Sea||
|Golden Harp Inn|`[1428, 3547, 0]`|North||
|High Flagon|`[1454, 3481, 0]`|North|A gambling hall and inn.|
|Silent Shield|`[1675, 3293, 0]`|North||
|Yawning Portal|`[1465, 1746, 0]`|Castle|Famous for its entry to Undermountain.|
|Rearing Hippocampus|`[1343, 1509, 0]`|Dock||
|The Blackstar Inn|`[1496, 1541, 0]`|Dock|Owned by Asiyra Boldwinter. Armed guards protected the entryway and stables.|
|Gray Serpent|`[1686, 1644, 0]`|Dock||
|Wyrmbones Inn|`[1500, 2219, 0]`|Castle||
|Inn of the Dripping Dagger|`[1536, 2300, 0]`|Trades|Favored by adventurers and mercenaries.|
|Gentle Rest|`[1737, 1902, 0]`|Trades||
|Wyvern's Rest|`[840, 3691, 0]`|Sea|Originally a stone watch house, a favorite of guards and watchmen.|
|Sapphire House|`[943, 2605, 0]`|Castle|An expensive rooming house.|
|Tarth's Towers|`[1033, 3196, 0]`|Sea||
|Oblarth's Gryphon|`[1418, 3095, 0]`|North||
|Bard Inn|`[1237, 1515, 0]`|Dock||
|Sailor’s Corner|`[1259, 1448, 0]`|Dock||
|Ship's Prow|`[1386, 1363, 0]`|Dock|The inn's name derived from being converted from the prow of a ship.|
|Warm Beds|`[1465, 1318, 0]`|Dock||
|Blackstone House|`[1698, 1608, 0]`|South|Mercenaries could be hired at Blackstone House.|
|Maelstrom's Notch|`[1662, 2031, 0]`|Trades||
|The Splintered Stair|`[1427, 1475, 0]`|Dock|Known for its large, spiraling staircase damaged in an epic brawl.|
|Gondalim's|`[1555, 2128, 0]`|Trades||
|Cliffwatch Inn|`[1901, 2937, 0]`|North||
|Greenglade Tower|`[1549, 2672, 0]`|North|A popular and clean rooming house.|
|Safehaven Inn|`[1807, 1302, 0]`|South||
|Unicorn's Horn|`[1546, 1985, 0]`|Trades||
|Selûne's Smile|`[1279, 1498, 0]`|Dock|Also known as the Inn of the Crescent Moon, devoted to Selûne.|
|Shipmasters' Hall|`[1734, 1052, 0]`|South|An inn.|

### **Taverns, Restaurants & Festhalls**

|   |   |   |
|---|---|---|
|**Name**|**Coordinates**|**Category**|
|Endshift Tavern|`[1875, 3454, 0]`|Taverns/Restaurants|
|Demondraught|`[949, 3670, 0]`|Taverns/Restaurants|
|The Ship's Wheel|`[690, 3150, 0]`|Taverns/Restaurants|
|Fiery Flagon|`[733, 3243, 0]`|Taverns/Restaurants|
|Gournar's Tavern|`[773, 3130, 0]`|Taverns/Restaurants|
|The Red Gauntlet|`[1832, 1051, 0]`|Taverns/Restaurants|
|Bowels of the Earth|`[1566, 1813, 0]`|Taverns/Restaurants|
|The Red-Eyed Owl|`[1515, 1730, 0]`|Taverns/Restaurants|
|The Sleepy Sylph|`[1530, 1738, 0]`|Taverns/Restaurants|
|Elfstone Tavern|`[1386, 2018, 0]`|Taverns/Restaurants|
|Blue Jack|`[1508, 1993, 0]`|Taverns/Restaurants|
|The Misty Beard|`[1915, 3025, 0]`|Taverns/Restaurants|
|Singing Sword|`[1394, 2619, 0]`|Taverns/Restaurants|
|Grinning Lion|`[1691, 2696, 0]`|Taverns/Restaurants|
|Mighty Manticore|`[1147, 2297, 0]`|Taverns/Restaurants|
|The Asp's Strike|`[1051, 1959, 0]`|Taverns/Restaurants|
|Dragon's Head|`[1089, 2021, 0]`|Taverns/Restaurants|
|Crawling Spider|`[1322, 2127, 0]`|Taverns/Restaurants|
|Sated Satyr|`[938, 3831, 0]`|Taverns/Restaurants|
|Silken Slyph|`[778, 3351, 0]`|Taverns/Restaurants|
|Twilight Hunters|`[1851, 3089, 0]`|Taverns/Restaurants|
|Broken Lance|`[973, 3011, 0]`|Taverns/Restaurants|
|Tavern of the Flagon Dragon|`[950, 2594, 0]`|Taverns/Restaurants|
|Slaked Sylph|`[870, 2901, 0]`|Taverns/Restaurants|
|Quaffing Quaggoth|`[1054, 1629, 0]`|Taverns/Restaurants|
|Pickled Fisherman|`[1158, 1548, 0]`|Taverns/Restaurants|
|Soaring Pegasus|`[1203, 1533, 0]`|Taverns/Restaurants|
|The Grey Griffon|`[1223, 1683, 0]`|Taverns/Restaurants|
|Angry Coxswain|`[1331, 1347, 0]`|Taverns/Restaurants|
|Singed Bolt|`[1816, 1771, 0]`|Taverns/Restaurants|
|Underdark|`[1762, 1625, 0]`|Taverns/Restaurants|
|Sleepy Slyph|`[1528, 1648, 0]`|Taverns/Restaurants|
|Darth's Dolphyntyde|`[1363, 1590, 0]`|Taverns/Restaurants|
|The Sailors' Own|`[1040, 1539, 0]`|Taverns/Restaurants|
|The Sleeping Snake|`[1682, 1067, 0]`|Taverns/Restaurants|
|The Thirsty Throat|`[1685, 1454, 0]`|Taverns/Restaurants|
|The Full Cup|`[1951, 1209, 0]`|Taverns/Restaurants|
|Azuth’s Mug|`[1429, 1770, 0]`|Taverns/Restaurants|
|Hanged Man|`[1602, 1177, 0]`|Taverns/Restaurants|
|Beer Golem|`[1795, 1283, 0]`|Taverns/Restaurants|
|The Midnight Sun|`[1779, 1380, 0]`|Taverns/Restaurants|
|Tymora's Blessing|`[1746, 1288, 0]`|Taverns/Restaurants|
|Blue Mermaid|`[1526, 1189, 0]`|Taverns/Restaurants|
|Sleeping Wench|`[1584, 1219, 0]`|Taverns/Restaurants|
|The Bloody Fist|`[1560, 1352, 0]`|Taverns/Restaurants|
|Frewn's Brews|`[1577, 3237, 0]`|Taverns/Restaurants|
|Mermaid on a Dolphin|`[1090, 3300, 0]`|Taverns/Restaurants|
|Tao Wall Street's Pub|`[1936, 1741, 0]`|Taverns/Restaurants|
|Friendly Flounder|`[1611, 1501, 0]`|Taverns/Restaurants|
|House of Purple Silks|`[755, 3112, 0]`|Festhalls|
|The Gentle Mermaid|`[1434, 3018, 0]`|Festhalls|
|Golden Horn Gambling House|`[1518, 1919, 0]`|Festhalls|
|Mother Tathlorn's House of Pleasure and Healing|`[1314, 1911, 0]`|Festhalls|
|Three Pearls Nightclub|`[1606, 1378, 0]`|Festhalls|
|The Mermaid's Arms|`[1456, 1167, 0]`|Festhalls|
|Hanging Lantern|`[1547, 1232, 0]`|Festhalls|
|Purple Palace|`[1649, 1261, 0]`|Festhalls|
|Blushing Mermaid|`[1610, 1131, 0]`|Festhalls|
|Jade Dancer|`[1839, 1139, 0]`|Festhalls|
|Copper Cup|`[1937, 939, 0]`|Festhalls|
|Jhrual's Dance|`[928, 2576, 0]`|Festhalls|
|Smiling Siren|`[1095, 2510, 0]`|Festhalls|
|Blushing Nymph|`[1410, 1745, 0]`|Festhalls|
|Mother Salinka's House of Pleasures|`[1476, 1747, 0]`|Festhalls|
|Smiling Succubus|`[1691, 1102, 0]`|Festhalls|
|Silavene's|`[724, 2763, 0]`|Festhalls|

### **Complete Location List (All Categories)**

|   |   |   |
|---|---|---|
|**Name**|**Coordinates**|**Category**|
|Fieldway|`[986, 3905, 0]`|Streets|
|Firewine Alley|`[1099, 3862, 0]`|Streets|
|Flipcoin Alley|`[1163, 3714, 0]`|Streets|
|Boltspring Alley|`[1015, 3833, 0]`|Streets|
|Burnt Inn Street|`[1189, 3733, 0]`|Streets|
|Trollwall Way|`[1131, 3896, 0]`|Streets|
|Soot Alley|`[1277, 3805, 0]`|Streets|
|Nanze Street|`[1196, 3849, 0]`|Streets|
|Twelvedog Court|`[1277, 3691, 0]`|Streets|
|Slipgate Street|`[1436, 3753, 0]`|Streets|
|Saltpork Street|`[1363, 3676, 0]`|Streets|
|Prestige Lane|`[1359, 3712, 0]`|Streets|
|Stench Alley|`[1667, 3648, 0]`|Streets|
|Tanner Alley|`[1631, 3621, 0]`|Streets|
|Chop Street|`[1673, 3662, 0]`|Streets|
|Leanwall Alley|`[1660, 3695, 0]`|Streets|
|Shanty Lane|`[1805, 3555, 0]`|Streets|
|The Semize|`[1704, 3540, 0]`|Streets|
|Gawenknife Street|`[1697, 3564, 0]`|Streets|
|Endshift Street|`[1886, 3473, 0]`|Streets|
|Breezeway|`[1905, 3394, 0]`|Streets|
|Logan's Walk|`[1663, 3605, 0]`|Streets|
|Seawind Alley|`[844, 3785, 0]`|Streets|
|Breeze's Cut|`[779, 3683, 0]`|Streets|
|Aureenar Street|`[908, 3688, 0]`|Streets|
|Murlpar Street|`[864, 3667, 0]`|Streets|
|Morningstar Way|`[925, 3632, 0]`|Streets|
|Ghostwalk|`[842, 3600, 0]`|Streets|
|Stormstar's Ride|`[972, 3640, 0]`|Streets|
|Sanborim Street|`[1077, 3691, 0]`|Streets|
|Street of Glances|`[1047, 3589, 0]`|Streets|
|Phastal Street|`[1040, 3653, 0]`|Streets|
|Westwall Street|`[731, 3615, 0]`|Streets|
|Heroes' Walk|`[1111, 3652, 0]`|Streets|
|Trollkill Street|`[1255, 3658, 0]`|Streets|
|Kulzar's Alley|`[1220, 3610, 0]`|Streets|
|The Fanebar|`[1264, 3598, 0]`|Streets|
|Skulls Street|`[1250, 3550, 0]`|Streets|
|Ignorance Alley|`[720, 3418, 0]`|Streets|
|Bliss Street|`[719, 3472, 0]`|Streets|
|Telchar Lane|`[847, 3531, 0]`|Streets|
|Gorl Street|`[889, 3513, 0]`|Streets|
|Staghunter's Way|`[935, 3522, 0]`|Streets|
|Sighing Maiden's Walk|`[914, 3481, 0]`|Streets|
|Street of the Singing Dolphin|`[830, 3469, 0]`|Streets|
|Wrightstone Street|`[1181, 3507, 0]`|Streets|
|Ivory Street|`[991, 3441, 0]`|Streets|
|Thunderstaff Way|`[1372, 3475, 0]`|Streets|
|Brassfeather Lane|`[1528, 3515, 0]`|Streets|
|Anteos Lane|`[1632, 3481, 0]`|Streets|
|Phull Lane|`[1712, 3469, 0]`|Streets|
|Whaelgond Way|`[1676, 3413, 0]`|Streets|
|Torch Lane|`[1011, 3402, 0]`|Streets|
|Flint Street|`[979, 3326, 0]`|Streets|
|Pharra's Alley|`[1016, 3373, 0]`|Streets|
|Grimwald's Way|`[760, 3336, 0]`|Streets|
|Wagonslide Alley|`[717, 3265, 0]`|Streets|
|Seawatch Street|`[740, 3280, 0]`|Streets|
|Shark Street|`[774, 3264, 0]`|Streets|
|Street of Whispers|`[808, 3266, 0]`|Streets|
|Gondwatch Lane|`[793, 3199, 0]`|Streets|
|Satchel Alley|`[718, 3172, 0]`|Streets|
|Diamond Street|`[796, 3143, 0]`|Streets|
|Delzorin Street|`[969, 3261, 0]`|Streets|
|Chasso's Trot|`[1180, 3409, 0]`|Streets|
|Watch Alley|`[1806, 3401, 0]`|Streets|
|Tower March|`[1707, 3356, 0]`|Streets|
|Pony Way|`[1785, 3301, 0]`|Streets|
|Immar Street|`[1774, 3357, 0]`|Streets|
|Black Dog Alley|`[1833, 3359, 0]`|Streets|
|Stallion Street|`[1847, 3319, 0]`|Streets|
|Horn Street|`[1752, 3277, 0]`|Streets|
|Selrin Street|`[1854, 3260, 0]`|Streets|
|Trollmarch|`[1879, 3321, 0]`|Streets|
|Lion Street|`[1850, 3176, 0]`|Streets|
|Saerdoun Street|`[1791, 3185, 0]`|Streets|
|Brondar's Way|`[1655, 3139, 0]`|Streets|
|Windborne Way|`[1563, 3323, 0]`|Streets|
|Vhezoar Street|`[1598, 3134, 0]`|Streets|
|Ilzantil Street|`[1531, 3144, 0]`|Streets|
|Vondil Street|`[1180, 3304, 0]`|Streets|
|Mendever Street|`[1133, 3258, 0]`|Streets|
|Sul Street|`[1227, 3256, 0]`|Streets|
|Shield Street|`[1320, 3259, 0]`|Streets|
|Copper Street|`[1397, 3257, 0]`|Streets|
|Sidle Street|`[1436, 3144, 0]`|Streets|
|Rough Road|`[1180, 3096, 0]`|Streets|
|Feather Street|`[1030, 3157, 0]`|Streets|
|Moonstar Alley|`[859, 3106, 0]`|Streets|
|The Lions|`[724, 3052, 0]`|Streets|
|Seaeye's March|`[615, 2924, 0]`|Streets|
|Jelzar's Stride|`[691, 2942, 0]`|Streets|
|Dob's Loss|`[851, 2981, 0]`|Streets|
|Darselune Street|`[922, 2974, 0]`|Streets|
|Gulzindar Street|`[838, 2935, 0]`|Streets|
|Julthoon Street|`[841, 2866, 0]`|Streets|
|Zarimtar Street|`[1077, 3016, 0]`|Streets|
|Haltovar Street|`[996, 2942, 0]`|Streets|
|The Sutherlane|`[1044, 2950, 0]`|Streets|
|Whim Street|`[1183, 2939, 0]`|Streets|
|Hassantyr's Street|`[1272, 2980, 0]`|Streets|
|Sulmor Street|`[1350, 3055, 0]`|Streets|
|Street of the Manticore|`[1642, 2948, 0]`|Streets|
|Ussilbran Street|`[1786, 3060, 0]`|Streets|
|Nindabar Street|`[1860, 3030, 0]`|Streets|
|Stabbed Sailor Alley|`[1642, 2903, 0]`|Streets|
|Little Street|`[1709, 2904, 0]`|Streets|
|Shattercrock Alley|`[1664, 2850, 0]`|Streets|
|Endcliff Lane|`[1883, 2928, 0]`|Streets|
|Tarsar's Street|`[1829, 2897, 0]`|Streets|
|High Road|`[1479, 3293, 0]`|Streets|
|Cliffride|`[659, 2814, 0]`|Streets|
|Toalar's Lane|`[739, 2833, 0]`|Streets|
|Gothal Street|`[922, 2835, 0]`|Streets|
|Melshar's Street|`[962, 2839, 0]`|Streets|
|Tchozal's Race|`[1018, 2820, 0]`|Streets|
|Trader's Way|`[1273, 2728, 0]`|Streets|
|Elvarren's Lane|`[864, 2735, 0]`|Streets|
|Calamastyr Lane|`[945, 2740, 0]`|Streets|
|Heard Lane|`[1181, 2795, 0]`|Streets|
|Manycats Alley|`[1356, 2813, 0]`|Streets|
|Swords Street|`[913, 2677, 0]`|Streets|
|Marlar's Lane|`[1013, 2604, 0]`|Streets|
|Aka Way|`[1050, 2593, 0]`|Streets|
|Tharleon Street|`[1105, 2558, 0]`|Streets|
|Bazaar Street|`[1200, 2565, 0]`|Streets|
|Tarnath Street|`[1542, 2807, 0]`|Streets|
|Suldown Street|`[1549, 2719, 0]`|Streets|
|Shando Street|`[1622, 2720, 0]`|Streets|
|Aveen Street|`[1676, 2734, 0]`|Streets|
|Gelthoon Street|`[1722, 2741, 0]`|Streets|
|Brahiir's Street|`[1770, 2764, 0]`|Streets|
|The Passar|`[1876, 2730, 0]`|Streets|
|Catchthief Alley|`[1811, 2710, 0]`|Streets|
|Golden Serpent Street|`[1772, 2672, 0]`|Streets|
|Magecourt|`[1622, 2666, 0]`|Streets|
|Siren Lane|`[1114, 2484, 0]`|Streets|
|Alnether Street|`[1200, 2494, 0]`|Streets|
|Elsambul's Lane|`[1293, 2467, 0]`|Streets|
|Lamp Street|`[1366, 2508, 0]`|Streets|
|Cymbril's Walk|`[1297, 2399, 0]`|Streets|
|Street of the Sword|`[1331, 2458, 0]`|Streets|
|The Prowl|`[1230, 2436, 0]`|Streets|
|Undal's Lane|`[1614, 2595, 0]`|Streets|
|Mhalsymber's Way|`[1768, 2618, 0]`|Streets|
|Zendulth Street|`[1858, 2588, 0]`|Streets|
|The Beaconmarch|`[1906, 2518, 0]`|Streets|
|Sammarin's Street|`[1723, 2523, 0]`|Streets|
|Black Cat Way|`[1668, 2558, 0]`|Streets|
|Andamaar's Street|`[1643, 2480, 0]`|Streets|
|Theln Lane|`[1620, 2449, 0]`|Streets|
|Irimar's Walk|`[1569, 2446, 0]`|Streets|
|Keltarn Street|`[1111, 2435, 0]`|Streets|
|Spindle Street|`[1583, 2282, 0]`|Streets|
|Coffinmarch|`[1586, 2232, 0]`|Streets|
|Winter Path|`[1591, 2193, 0]`|Streets|
|Ironpost Street|`[1596, 2151, 0]`|Streets|
|Selduth Street|`[1210, 2311, 0]`|Streets|
|Jester's Court|`[1128, 2282, 0]`|Streets|
|Turnback Court|`[975, 2339, 0]`|Streets|
|The Rise|`[938, 2296, 0]`|Streets|
|Asmagh's Alley|`[1230, 2254, 0]`|Streets|
|Buckle Alley|`[1393, 2212, 0]`|Streets|
|Street of Bells|`[1438, 2119, 0]`|Streets|
|Burnt Wagon Way|`[1574, 2084, 0]`|Streets|
|Street of the Tusks|`[1606, 2037, 0]`|Streets|
|Mhaer's Alley|`[1648, 2052, 0]`|Streets|
|Cat Alley|`[1479, 2029, 0]`|Streets|
|Zeldan's Alley|`[1337, 2072, 0]`|Streets|
|Palfrey Lane|`[1214, 2086, 0]`|Streets|
|Fetlock Court|`[966, 2205, 0]`|Streets|
|Mulgomir's Way|`[1143, 2128, 0]`|Streets|
|Shadow Alley|`[1097, 2063, 0]`|Streets|
|Cage Street|`[1126, 2034, 0]`|Streets|
|Warrior's Way|`[1265, 2251, 0]`|Streets|
|Waterdeep Way|`[1372, 1959, 0]`|Streets|
|Revon Street|`[1689, 2023, 0]`|Streets|
|Spendthrift Alley|`[1638, 2023, 0]`|Streets|
|Vellarr's Lane|`[1611, 1975, 0]`|Streets|
|Sleepers' Walk|`[1698, 1968, 0]`|Streets|
|Slipstone Street|`[1721, 1951, 0]`|Streets|
|Nethpranter's Street|`[1770, 1966, 0]`|Streets|
|Quill Alley|`[1768, 1930, 0]`|Streets|
|Wall Way|`[1889, 1919, 0]`|Streets|
|Wide Way|`[1796, 1902, 0]`|Streets|
|Spoils Alley|`[1735, 1912, 0]`|Streets|
|Deloun Alley|`[1767, 1879, 0]`|Streets|
|Chelor's Alley|`[1807, 1862, 0]`|Streets|
|Sevenlamps Cut|`[1043, 2267, 0]`|Streets|
|Street of Silks|`[1077, 2255, 0]`|Streets|
|Gem Street|`[1378, 1923, 0]`|Streets|
|Niles Way|`[1448, 1920, 0]`|Streets|
|High Hillock Lane|`[1476, 1878, 0]`|Streets|
|Crossbow Lane|`[1509, 1845, 0]`|Streets|
|Hillock Court|`[1402, 1887, 0]`|Streets|
|Soldier's Street|`[1484, 1811, 0]`|Streets|
|Quaff Alley|`[1549, 1919, 0]`|Streets|
|Scroll Street|`[1602, 1896, 0]`|Streets|
|Virgin's Square|`[1607, 1845, 0]`|Streets|
|Simple's Street|`[1603, 1817, 0]`|Streets|
|Blackhorn Alley|`[1698, 1869, 0]`|Streets|
|Lathin's Cut|`[1732, 1815, 0]`|Streets|
|Salabar Street|`[1825, 1823, 0]`|Streets|
|Court of the White Bull|`[1843, 1884, 0]`|Streets|
|Sorn Street|`[1877, 1831, 0]`|Streets|
|Brindul Alley|`[1851, 1814, 0]`|Streets|
|River Street|`[1845, 1780, 0]`|Streets|
|Soothsayer's Way|`[1609, 1776, 0]`|Streets|
|Coin Alley|`[828, 1542, 0]`|Streets|
|Sea Lion Street|`[949, 1576, 0]`|Streets|
|Sail Street|`[933, 1504, 0]`|Streets|
|Tarnished Silver Alley|`[1002, 1591, 0]`|Streets|
|Lackpurse Lane|`[1069, 1602, 0]`|Streets|
|Dock Street|`[1131, 1505, 0]`|Streets|
|The Reach|`[1070, 1680, 0]`|Streets|
|Crook Street|`[1153, 1653, 0]`|Streets|
|Dretch Lane|`[1172, 1725, 0]`|Streets|
|Knife's Edge|`[1211, 1732, 0]`|Streets|
|Eel Street|`[1232, 1659, 0]`|Streets|
|The Slide|`[1232, 1590, 0]`|Streets|
|Ward's Way|`[1320, 1673, 0]`|Streets|
|Belnimbra's Street|`[1324, 1637, 0]`|Streets|
|Rainrun Street|`[1376, 1744, 0]`|Streets|
|Cook Street|`[1431, 1755, 0]`|Streets|
|Arun's Alley|`[1363, 1678, 0]`|Streets|
|Fishgut Court|`[1267, 1511, 0]`|Streets|
|Sakiir's Street|`[1275, 1592, 0]`|Streets|
|Wastrel Alley|`[1341, 1568, 0]`|Streets|
|Redcloak Lane|`[1414, 1627, 0]`|Streets|
|Nelnuk's Walk|`[1354, 1523, 0]`|Streets|
|Leera's Alley|`[1445, 1577, 0]`|Streets|
|Watchrun Alley|`[1388, 1563, 0]`|Streets|
|Adder Lane|`[1354, 1491, 0]`|Streets|
|Gut Alley|`[1476, 1648, 0]`|Streets|
|Snail Street|`[1544, 1601, 0]`|Streets|
|Blackstar Lane|`[1514, 1554, 0]`|Streets|
|Three Daggers Alley|`[1494, 1500, 0]`|Streets|
|Spiderweb Alley|`[1461, 1452, 0]`|Streets|
|Picklock Alley|`[1332, 1463, 0]`|Streets|
|Fish Street|`[1333, 1421, 0]`|Streets|
|Julbuck Alley|`[1386, 1421, 0]`|Streets|
|Shoor Street|`[1745, 1722, 0]`|Streets|
|Beacon Street|`[1710, 1687, 0]`|Streets|
|Blackmul Street|`[1739, 1665, 0]`|Streets|
|Shesstra's Street|`[1568, 1641, 0]`|Streets|
|Drakiir Street|`[1640, 1613, 0]`|Streets|
|Drovers' Street|`[1822, 1694, 0]`|Streets|
|Wagonrace|`[1898, 1715, 0]`|Streets|
|Wall Street|`[1950, 1687, 0]`|Streets|
|Quarrel's Flight|`[1908, 1685, 0]`|Streets|
|Sahtyra's Lane|`[1844, 1664, 0]`|Streets|
|Telshambra's Street|`[1737, 1601, 0]`|Streets|
|Buckle Street|`[1849, 1627, 0]`|Streets|
|Caravan Court|`[1909, 1623, 0]`|Streets|
|Ruid's Stroll|`[1945, 1592, 0]`|Streets|
|Robin's Way|`[1910, 1535, 0]`|Streets|
|Rising Ride|`[1867, 1553, 0]`|Streets|
|Tezambril's Street|`[1888, 1494, 0]`|Streets|
|Tulmaster's Street|`[1864, 1477, 0]`|Streets|
|Caravan Street|`[1913, 1485, 0]`|Streets|
|Book Street|`[1615, 1520, 0]`|Streets|
|Black Wagon Alley|`[1673, 1522, 0]`|Streets|
|Ilisar's Alley|`[1754, 1567, 0]`|Streets|
|Street of Smiths|`[1745, 1517, 0]`|Streets|
|Brian's Street|`[1761, 1469, 0]`|Streets|
|The Forcebar|`[1860, 1432, 0]`|Streets|
|Tilman's Lane|`[1925, 1439, 0]`|Streets|
|Olaim's Cut|`[1938, 1363, 0]`|Streets|
|Anchoret's Alley|`[1860, 1366, 0]`|Streets|
|Specterwalk|`[1906, 1310, 0]`|Streets|
|Carter's Way|`[1934, 1262, 0]`|Streets|
|Coach Street|`[1974, 1219, 0]`|Streets|
|Coachlamp Lane|`[1985, 1132, 0]`|Streets|
|Slop Street|`[1799, 1114, 0]`|Streets|
|Way of the Dragon|`[1805, 1042, 0]`|Streets|
|Odd Street|`[1360, 1355, 0]`|Streets|
|Siren Street|`[1390, 1326, 0]`|Streets|
|Ship Street|`[1428, 1326, 0]`|Streets|
|Two Flask Alley|`[1442, 1345, 0]`|Streets|
|Presper Street|`[1489, 1324, 0]`|Streets|
|Sternpost Street|`[1385, 1262, 0]`|Streets|
|Asteril's Way|`[1401, 1239, 0]`|Streets|
|Cod Lane|`[1469, 1264, 0]`|Streets|
|Street of Six Casks|`[1531, 1302, 0]`|Streets|
|Aline's Way|`[1495, 1144, 0]`|Streets|
|Keel Alley|`[1539, 1161, 0]`|Streets|
|Pressbow Lane|`[1568, 1242, 0]`|Streets|
|Zastrow Street|`[1655, 1336, 0]`|Streets|
|Street of Curtains|`[1591, 1465, 0]`|Streets|
|Trollcrook Alley|`[1620, 1407, 0]`|Streets|
|Pearl Alley|`[1599, 1372, 0]`|Streets|
|Shrimp Alley|`[1571, 1324, 0]`|Streets|
|Fillet Lane|`[1689, 1242, 0]`|Streets|
|Net Street|`[1669, 1185, 0]`|Streets|
|Oar Alley|`[1553, 1209, 0]`|Streets|
|Mouse Alley|`[1758, 1438, 0]`|Streets|
|Fishwife Alley|`[1768, 1412, 0]`|Streets|
|Curtain Alley|`[1803, 1400, 0]`|Streets|
|Blackcloak Alley|`[1740, 1375, 0]`|Streets|
|Spices Street|`[1640, 1112, 0]`|Streets|
|Fishgut Alley|`[1698, 1104, 0]`|Streets|
|Wharf Street|`[1724, 1106, 0]`|Streets|
|Cedar Street|`[1747, 1028, 0]`|Streets|
|Hog Street|`[1791, 1008, 0]`|Streets|
|Sambril Lane|`[1895, 970, 0]`|Streets|
|Nag Street|`[1860, 976, 0]`|Streets|
|Tower Trail|`[1833, 957, 0]`|Streets|
|Smuggler's Run|`[1926, 910, 0]`|Streets|
|Southcliff Way|`[2434, 1105, 0]`|Streets|
|Undercliff Way|`[2483, 1817, 0]`|Streets|
|Overlooked Alley|`[1432, 1812, 0]`|Streets|
|Murghir's Lane|`[1581, 1694, 0]`|Streets|
|Dust Alley|`[1521, 1506, 0]`|Streets|
|Hunter's Alley|`[1700, 1787, 0]`|Streets|
|Jembril Street|`[1730, 1757, 0]`|Streets|
|Burdag Lane|`[1708, 1818, 0]`|Streets|
|Tsarnen Alley|`[1694, 1838, 0]`|Streets|
|River Square|`[1800, 1808, 0]`|Streets|
|Tornsar Alley|`[1863, 1588, 0]`|Streets|
|Juth Alley|`[1892, 1562, 0]`|Streets|
|Ghemmer's Alley|`[1499, 1436, 0]`|Streets|
|Dancing Court|`[1829, 1134, 0]`|Streets|
|The Boomgarden|`[1787, 1292, 0]`|Streets|
|Anchoret's Court|`[1880, 1331, 0]`|Streets|
|Sethma's Court|`[1848, 1453, 0]`|Streets|
|Street of Nine Steps|`[1933, 1380, 0]`|Streets|
|The Jar|`[1937, 1424, 0]`|Streets|
|Howling Cat Court|`[1133, 2229, 0]`|Streets|
|Old Temple Lot|`[886, 1587, 0]`|Streets|
|Watchmen's Way|`[1436, 1873, 0]`|Streets|
|Guards Court|`[1494, 1892, 0]`|Streets|
|Atkiss Alley|`[1588, 1914, 0]`|Streets|
|Tuckpurse Alley|`[1678, 1958, 0]`|Streets|
|Gaustus Street|`[1843, 1949, 0]`|Streets|
|Walltower Walk|`[1887, 1879, 0]`|Streets|
|Urcandle Alley|`[1863, 1848, 0]`|Streets|
|Moarinskoar Alley|`[1163, 3251, 0]`|Streets|
|Court of the Well|`[1183, 2974, 0]`|Streets|
|Trollyard|`[859, 3911, 0]`|Streets|
|Shark Alley|`[997, 3764, 0]`|Streets|
|Roguerun Alley|`[759, 3628, 0]`|Streets|
|Skulkway|`[724, 3551, 0]`|Streets|
|Northyard|`[1504, 3740, 0]`|Streets|
|Southyard|`[1951, 944, 0]`|Streets|
|Waymoot|`[1915, 1007, 0]`|Streets|
|Ravencourt|`[1040, 3686, 0]`|Streets|
|Prayer Alley|`[1022, 3674, 0]`|Streets|
|Sabbar's Alley|`[842, 3664, 0]`|Streets|
|Sniff Alley|`[923, 3562, 0]`|Streets|
|Sharra's Flight|`[857, 3068, 0]`|Streets|
|Runer's Alley|`[1030, 2899, 0]`|Streets|
|Cloaksweep Alley|`[1181, 3035, 0]`|Streets|
|Soaring Delights|`[1327, 2100, 0]`|Taverns/Restaurants|
|Lemontree Alley|`[1122, 2088, 0]`|Streets|
|Belzer's Walk|`[1934, 1655, 0]`|Streets|
|Melody Mount Walk|`[857, 2644, 0]`|Streets|
|Weeping Maiden's Run|`[1777, 1333, 0]`|Streets|
|Snake Alley|`[1753, 1289, 0]`|Streets|
|Grocer's Lane|`[1780, 1315, 0]`|Streets|
|Candle Lane|`[1653, 1490, 0]`|Streets|
|Red Nose Alley|`[1872, 1524, 0]`|Streets|
