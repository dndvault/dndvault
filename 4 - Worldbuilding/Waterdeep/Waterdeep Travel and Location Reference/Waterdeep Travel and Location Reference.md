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

### **Subterranean Passages: An In-Depth Look at the Sewers and Dungeons of Waterdeep**

Beneath the bustling streets of Waterdeep lies a complex and dangerous network of tunnels that serves as the city's sanitation system. This subterranean environment, far from being merely a functional utility, is a location of intrigue, peril, and hidden pathways, connecting to nearly every part of the city and even the notorious Undermountain.

The sewers of Waterdeep are a varied and multi-leveled system, with some areas descending two or three sub-levels deep. This variation is a result of both the natural topography, such as Mount Waterdeep and the plateau on which the northern part of the city is built, and deliberate design choices to optimize the tidal flushing system. The layout of the sewer tunnels does not correspond to the street grid above, as their paths were dictated by the flow of natural springs from Mount Waterdeep to the sea. The only areas of the city not serviced by this network are the Field Ward, the harbor islands, and the very heart of Mount Waterdeep.

#### **Functionality and Maintenance**

The sewer system operates on a tidal flushing mechanism, where the ocean tides from Deepwater Harbor fill the tunnels and then flush them out. This is supplemented by street runoff from rain and fog, as well as spring water from Mount Waterdeep. To prevent the harbor from becoming a cesspool, the great wizard Ahghairon and other mages bound spells and elementals into the city's wards to aid in carrying the sewage away. Some powerful spells even teleport waste directly to the Rat Hills. The system also incorporates features like doors that close to prevent flooding and pressure plates to stop backwash.

The crucial task of maintaining this complex network falls to the **Cellarers' and Plumbers' Guild**. This guild is responsible for digging building foundations and ensuring the sewers remain functional and safe. Guild members are known to be well-versed in the general layout of the sewers, a knowledge acquired over two to five years of work. They undertake constant repairs on plumbing and are the primary workforce within the tunnels. While they possess maps of the sewers, these are not for sale.

#### **Structural and Environmental Details**

Constructed from masonry and paving bricks, the sewers are dark, pervaded by a terrible stench, and lack any form of lighting. Numerous feeder pipes, less than a foot in diameter, bring refuse and air down from the city above, ensuring a breathable, albeit foul, atmosphere. Iron gratings, many now suffering from rust, are found throughout the system. Some are fixed, while others can swing open on pivots.

Explorers of the sewers face numerous hazards. The water is tainted and can cause "blinding sickness," while open wounds are susceptible to "filth fever". The constant, echoing flow of water imposes a penalty on Listen checks, while the pervasive stench hampers tracking by scent.

The passages themselves are categorized into two main types:

- **Primary Passages:** These are the largest, measuring 20 feet across with 3-foot-wide walkway ledges on either side. They are more common in the northern sections of the city's sewers.
- **Secondary Passages:** These are smaller, at 12 feet across, with a single 3-foot-wide ledge, usually on the southern or eastern side. Human-sized creatures may need to crawl or swim in these passages. These are prevalent beneath the Dock Ward.

In addition to these, many older and smaller passages have been walled up over time, and some, like the "Smugglers' Run" beneath the Dock Ward, were once navigable by small boats.

### **Sewer Entry Points and Notable Locations**

Access to the sewers is gained through **Surface Shafts**, which are 6-foot diameter vertical tunnels with iron rungs for ladders, capped by removable metal or wooden covers. **Junction Rooms**, typically 30-by-30-foot stone chambers, connect various passages and provide a small, raised ledge for respite.

The following is a comprehensive index of known sewer access points and significant subterranean locations, with coordinates corresponding to their surface locations. The Z-coordinate `-1` indicates the sewer level.

|   |   |   |   |
|---|---|---|---|
|**Name**|**Coordinates**|**Ward/Location**|**Description**|
|**SF1**|`N/A`|Near Shrines of Nature, Sea Ward|A surface shaft located under trees northwest of the shrine to Silvanus.|
|**SF2**|`[842, 3664, -1]`|Sabbar's Alley, North Ward|A surface shaft in the northernmost corner of the alley.|
|**SF3**|`[N/A]`|Shank Alley|A surface shaft in the center of the alley.|
|**SF4**|`[923, 3562, -1]`|Sniff Alley, south of Street of Glances|A surface shaft located just south of a tree in the alley.|
|**SF5**|`[N/A]`|Heroes' Garden, North Ward|A surface shaft in the southern end of the garden, covered by a stone hut. A secret entrance to the Catacombs of Yintros is halfway down this shaft.|
|**SF6**|`[991, 3441, -1]` (Approx.)|West of Eltorchul Villa, Sea Ward|A surface shaft under a lone tree in an alley south of Ivory Street.|
|**SF7**|`[1180, 3409, -1]`|North of Chasso’s Trot|A surface shaft in the mouth of an alleyway.|
|**SF8**|`[N/A]`|South of Jhansczil Villa|A surface shaft in a cul-de-sac that opens into a junction room.|
|**SF9**|`[N/A]`|South of Brossfeather Villa|A surface shaft under a tree in an alley.|
|**SF10**|`[760, 3336, -1]`|South of the Ilitul Villa|A surface shaft at the northern end of a dead alley opening off Grimwald’s Way.|
|**SF11**|`[1133, 3258, -1]`|West of Mendever Street|A surface shaft in a cul-de-sac off the alley bounding Nesher Villa.|
|**SF12**|`[969, 3261, -1]`|West of Manthar Villa gates|A surface shaft in an alley off Delzorin Street that opens into a junction room.|
|**SF13**|`[1256, 3279, -1]` (Approx.)|Block surrounded by Copper, Delzorin, High, and Vordil Streets|A surface shaft in an alleyway.|
|**SF14**|`[N/A]`|Trollskull Alley|A surface shaft in the southwestern corner, near the intersection of Delzorin Street and Whaelgund Way. The ladder descends 20 feet.|
|**SF15**|`[1752, 3277, -1]`|North of Horn Street|A surface shaft in a cul-de-sac between Tower March and Whaelgund Way.|
|**SF16**|`[1362, 3148, -1]` (Approx.)|Block bounded by Delzorin, Vhesoar, Sulmor, and Ilzantil Streets|A surface shaft under trees in a dead-end alley.|
|**SF17**|`[857, 3068, -1]`|Intersection of Sharra's Flight and Street of Whispers|A surface shaft at this intersection.|
|**SF18**|`[739, 2833, -1]`|Northeast of Toalar's Lane|A surface shaft in a cul-de-sac.|
|**SF19**|`[922, 2835, -1]`|Intersection of Calamastyr Lane and Gothal Street|A surface shaft that opens into a junction room.|
|**SF20**|`[1030, 2899, -1]`|Runer's Alley|A surface shaft in the southwestern corner.|
|**SF21**|`[1181, 3035, -1]`|Under Cloaksweep Alley|A junction room with no surface entrance, located under the southern mouth of the alley.|
|**SF22**|`[1247, 3099, -1]` (Approx.)|Block bounded by Copper, Hassantyr's, High, and Julthoon Streets|A surface shaft in a copse of trees at the center of the block.|
|**SF23**|`[1013, 2604, -1]`|Marlar's Lane|A surface shaft at the western end of the lane.|
|**SF24**|`[1347, 2311, -1]`|Behind Blackstaff Tower, Castle Ward|A surface shaft at the base of a rocky cliff-face.|
|**SF25**|`[975, 2339, -1]` (Approx.)|Mount Waterdeep|A surface shaft near the top of the rocky slope, southwest of Turnback Court.|
|**SF26**|`[975, 2339, -1]`|Turnback Court|A surface shaft located in Turnback Court that opens into a junction room.|
|**SF27**|`[1297, 2399, -1]`|South of Cymbril's Walk|A surface shaft in the southwest corner of an alleyway.|
|**SF28**|`[1358, 2371, -1]` (Approx.)|Block bounded by Lamp, Bells, Cymbril's, and Sword Streets|A surface shaft in a dead-end alley that opens into a junction room.|
|**SF29**|`[1338, 2313, -1]` (Approx.)|Block bounded by Lamp, High, Selduth, and Bells Streets|A surface shaft at a northwestern junction of alleyways.|
|**SF30**|`[1643, 2480, -1]` (Approx.)|West of Andamaar's Street|A surface shaft at the southeastern corner of an alley off the High Road.|
|**SF31**|`[1691, 2696, -1]`|Beneath the Grinning Lion, Trades Ward|A junction room with no direct surface access. A secret passage connects it to the tavern's midden.|
|**SF32**|`[1772, 2672, -1]`|Off Golden Serpent and Nindabar Streets|A surface shaft in the northwest corner of an alleyway.|
|**SF33**|`N/A`|Belzound Street|A surface shaft located at the halfway point of Belzound Street.|
|**SF34**|`[1043, 2267, -1]`|South of Sevenlamps Cut|A surface shaft at the northern mouth of an alleyway.|
|**SF35**|`[1097, 2063, -1]`|Intersection of Lemontree and Shadows Alleys|A surface shaft at the intersection of these alleys.|
|**SF36**|`N/A`|North of The Pampered Traveler inn|A surface shaft in an alleyway.|
|**SF37**|`[1421, 2174, -1]` (Approx.)|Between High Road and Street of Bells|A surface shaft in a wide alleyway, north of Buckle Alley.|
|**SF38**|`[1723, 1803, -1]`|Under the House of the Fine Carvers, Trades Ward|A surface shaft beneath the guildhall leading into a junction room.|
|**SF39**|`[1583, 2282, -1]`|Spindle Street|A surface shaft located on the street, south of Selduth Street.|
|**SF40**|`[1569, 2446, -1]`|Parallel to Irimar's Walk|A surface shaft in the lane that parallels Irimar's Walk on the north.|
|**SF41**|`[1889, 1919, -1]`|West of Wall Way|A surface shaft in an alleyway of three trees that opens west off Wall Way.|
|**SF42**|`[1596, 2151, -1]`|West of Wall Way|A surface shaft in an alleyway just north of Ironpost Street.|
|**SF43**|`N/A`|North of the Costumers' Hall|A surface shaft in the trees in a dead-end alley.|
|**SF44**|`[1606, 2037, -1]`|East of the Street of the Tusks|A surface shaft at the mouth of a dead-end alley.|
|**SF45**|`[1638, 2023, -1]`|South of Spendthrift Alley|A junction room with no surface entrance, located under the alleyway.|
|**SF46**|`[1546, 1985, -1]`|Unicorn's Horn, Trades Ward|A surface shaft located in the cellar of the Unicorn's Horn inn.|
|**SF47**|`N/A`|Behind Olmhazan's Jewels|A surface shaft in the alley just behind the shop between the High Road and the Street of Bells.|
|**SF48**|`[1354, 1523, -1]`|South of Nelnuk's Walk|A surface shaft at the end of a dead-end alley opening south off Nelhuk's walk.|
|**SF49**|`[1568, 1641, -1]`|Off of Shesstra's Street|A surface shaft in the southwestern corner of a dead-end alley.|
|**SF50**|`[1544, 1601, -1]`|Under alleyways off Snail Street|A junction room with no surface entrance.|
|**SF51**|`[1324, 1637, -1]`|Off of Belnimbra's Street|A surface shaft in a cul-de-sac.|
|**SF52**|`[1549, 1919, -1]`|Quaff Alley|A surface shaft in the westernmost dead-end of Quaff Alley that opens into a junction room.|
|**SF53**|`[1484, 1811, -1]`|Soldier's Street, east of the Bell Tower|A surface shaft located on Soldier's Street.|
|**SF54**|`[1606, 1378, -1]`|North of the Three Pearls Nightclub, Dock Ward|A surface shaft at the intersection of alleyways.|
|**SF55**|`[1653, 1490, -1]`|Under Candle Lane|A junction room with no surface shaft, located under the wide part of the lane.|
|**SF56**|`[1603, 1817, -1]`|South of Simples Street|A surface shaft at the western end of a dead-end alley, opening into a junction room.|
|**SF57**|`[1694, 1838, -1]`|Intersection of Burdag Lane and Tsarnen Alley|A surface shaft at this intersection.|
|**SF58**|`[1768, 1930, -1]`|Quill Alley|A surface shaft in the mouth of a dead end alley, where it joins Quill Alley between the Wide Way and Nethpranter's Street.|
|**SF59**|`[1689, 2023, -1]`|East of Rivon Street|A surface shaft in the western end of a dead-end forked alley that opens east off Rivon Street.|
|**SF60**|`[1822, 1694, -1]`|East of Drovers' Street|A surface shaft in a cul-de-sac opening east off the north end of Drovers' Street.|
|**SF61**|`[1710, 1687, -1]`|Beacon Street|A surface shaft located halfway down Beacon Street.|
|**SF62**|`[1780, 1315, -1]`|Intersection of Grocer's Lane and Snake Alley|A junction room with no surface entrance.|
|**SF63**|`[1872, 1524, -1]`|Rednose Alley|A surface shaft in Rednose Alley.|
|**SF64**|`[1867, 1553, -1]`|Off the Rising Ride|A surface shaft in a cul-de-sac opening off the Rising Ride between Juth Alley and Caravan Court.|
|**SF65**|`[1938, 1363, -1]`|South of Olaim's Cut|A surface shaft in the wide part of the alley that opens south off Olaim's Cut.|
|**SF66**|`[1974, 1219, -1]`|North of Coach Street|A surface shaft in the wide alley north of Coach Street, just west of the High Road.|
|**SF67**|`[1934, 1262, -1]`|East of Carter's Way|A surface shaft in the alley east of the former Prestar's Furniture, immediately south of Coachlamp Lane.|
|**SF68**|`N/A`|The Spouting Fish tavern|A surface shaft located in the cellar.|
|**SF69**|`N/A`|North of Bellister's House|A surface shaft located in the second alleyway north of the house.|
|**SF70**|`[1347, 2311, -1]`|Piergeiron's Palace, Castle Ward|A locked surface shaft within the cellar of the palace, guarded at all times by five guard members and an armar.|
|**SF71**|`N/A`|N/A|A secret door that connects a secondary passage to the Dungeon of the Crypt.|
|**SF72**|`N/A`|Beneath the Philosopher's Court|The lair of the Xanathar, accessible via secret doors in the sewers and passages to basements and Undermountain.|
|**SF73**|`[1484, 1811, -1]` (Approx.)|Near SF53|Northern entrance to the Citadel of the Bloody Hand.|
|**SF74**|`[1354, 1523, -1]` (Approx.)|Near SF48|Southern entrance to the Citadel of the Bloody Hand.|
|**SF75**|`[1181, 3035, -1]`|Drain of Madness (at SF21)|A collapsed sewer floor in SF21 leading down to the flooded lair of the Savants of the Dark Tide.|
|**God Catcher Entrance**|`N/A`|Castle Ward|The hollowed-out leg of a sunken Walking Statue provides an access point to the sewers.|
|**Golden Hammer Inn Entrance**|`N/A`|N/A|A trapdoor in the inn opens into the sewers.|
|**Safehaven Inn Entrance**|`[1807, 1302, -1]`|Southern Ward|A hidden ladder behind a wine casket in the cellar leads to the sewers.|
|**Thirsty Sailor Entrance**|`N/A`|Dock Ward|An entrance to the Smugglers' Run section of the sewers is in the tavern's back alley.|

### **Underground Structures & Undermountain Levels**

The sewers serve as a veritable dungeon between the city's surface and the sprawling, deadly depths of Undermountain, the lair of the Mad Mage Halaster Blackcloak. This megadungeon consists of 23 known levels, each a unique and dangerous environment.

|           |                       |                                         |                                                                                                                                                                                                                                                                                                                                                                                               |
| --------- | --------------------- | --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Level** | **Name**              | **Coordinates**                         | **Description & Connections**                                                                                                                                                                                                                                                                                                                                                                 |
| 1         | **Dungeon Level**     | `[1465, 1746, -2]` (Via Yawning Portal) | The main entry level for adventurers. It connects to the sewers in several places, including a passage near the **Falling Stair** which leads from the dungeons of Castle Waterdeep, and another that connects to the **Dungeon of the Crypt** beneath the City of the Dead.                                                                                                                  |
| 2         | **Arcane Chambers**   | `Z = -2`                                | A series of chambers where Halaster's apprentices once practiced their magic. Contains a gate to the Sargauth Level (Level 3).                                                                                                                                                                                                                                                                |
| 3         | **Sargauth Level**    | `Z = -2`                                | Named for the subterranean River Sargauth that flows through it, this level contains the ruins of the dwarven settlement of Stromkuhldur. It connects directly to **Skullport** via the river and five other passages. A gate here also leads back to the Arcane Chambers (Level 2).                                                                                                          |
| -         | **Skullport**         | `Z = -2`                                | A grim, cutthroat port town for nefarious creatures and smugglers, currently under the sway of the Xanathar Guild. It is a massive cavern settlement with three tiers. Skullport can be reached via the **Sargauth Level (Level 3)**, through a series of sea caves connected to Waterdeep's harbor, or via a passage from the cellars of Castle Waterdeep known as the **Castle Corkscrew**. |
| 4         | **Twisted Caverns**   | `Z = -2`                                | A network of caverns dominated by a vast forest of fungi. It was once known as "The Farm Level" and served as a pantry for Undermountain's denizens. An aboleth currently taints the waters here. It features a gate to the Lost Level (Level 6).                                                                                                                                             |
| 5         | **Wyllowwood**        | `Z = -2`                                | A magically created temperate forest within a massive cavern, complete with an illusory sky that mimics the surface world. It is the domain of the archdruid Wyllow. It contains a gate to the Sargauth Level (Level 3).                                                                                                                                                                      |
| 6         | **Lost Level**        | `Z = -2`                                | A former temple complex dedicated to the dwarven god Dumathoin. Recently rediscovered by burrowing umber hulks, it is now being plundered by duergar. A special gate here, visible only on the night of a full moon in the month of Flamerule, leads to a different part of the sewers. Another gate connects to Wyllowwood (Level 5).                                                        |
| 7         | **Maddgoth's Castle** | `Z = -2`                                | This level is named for a miniature, one-twelfth scale castle that floats in the center of a vast cavern. It is the home of a serial-killer wizard named Maddgoth. Creatures approaching the castle are shrunk to a corresponding size.                                                                                                                                                       |
| ...       | **Deeper Levels**     | `Z = -2` and below                      | The levels of Undermountain continue down to a depth of 23 known layers, each with its own unique and increasingly dangerous inhabitants and environments, including drow cities, githyanki creches, and the lairs of ancient evils.                                                                                                                                                          |


### Waterdeep Waypoint Travel System (Homebrew for Dockworkers' Campaign)

The Waypoint network provides a magical means of transport between designated points within Waterdeep's wards. Access is granted to spellcasters who have learned the specific technique, at the cost of a 1st level or higher spell slot per creature. Non-spellcasters can purchase city-issued tickets for one-time travel at a cost of 1 GP per person, with some discounts available. Waypoints communicate with one another and keep a magical "log" of all travelers, making it not the best option if you want to stay anonymous - this makes public Waypoints a means of travel mostly for commoners of upper-class status.

Waypoints can be temporarily shut down by the City Watch for security reasons. While generally safe, damaged or overloaded Waypoints can be hazardous. The network consists of public, private, and military Waypoints, each with varying levels of access and surveillance.

### Public Waypoint Index

The following table details the public Waypoints available for use within the city of Waterdeep, along with their coordinates and a brief description.

|                               |                   |               |                                                                                                                                                                                                 |
| ----------------------------- | ----------------- | ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Waypoint Name**             | **Coordinates**   | **Ward**      | **Description**                                                                                                                                                                                 |
| **Castle Waterdeep Entrance** | `[1347, 2311, 0]` | Castle Ward   | The main entrance to Waterdeep's seat of government. This heavily guarded Waypoint is one of the oldest and is prone to long queues, especially during state holidays.                          |
| **The Market**                | `[1723, 1803, 0]` | Trades Ward   | Located in the central market area, this Waypoint is a hub for commerce. It is known for frequent maintenance shutdowns.                                                                        |
| **Sailor's Dock (Pier 1)**    | `[1518, 1401, 0]` | Dock Ward     | A bustling Waypoint on the Great Harbor docks used for hauling cargo and subject to customs surveillance. The original Waypoint was replaced after an accident.                                 |
| **The Spires of Morning**     | `[830, 3469, 0]`  | Sea Ward      | Situated at the grand temple of Lathander, this Waypoint was recently opened to the public and is popular with tourists. It provides an opportunity to blend in with crowds.                    |
| **Heroes' Garden**            | `[955, 3063, 0]`  | Sea Ward      | A Waypoint within a public park that honors Waterdeep's heroes. It is often crowded with tourists, making it easy to blend in. A sewer shaft is also located in the southern end of the garden. |
| **Pseudodragon Walk**         | `[1552, 3008, 0]` | North Ward    | This Waypoint is on a wide, tree-lined street in a reputable and heavily patrolled area of the North Ward.                                                                                      |
| **Caravan Court**             | `[1909, 1623, 0]` | Southern Ward | A large courtyard near the South Gate where caravans assemble. Cargo is subject to search by Customs, and random searches by the Watch are common.                                              |
| **The Yawning Portal**        | `[1465, 1746, 0]` | Castle Ward   | A renowned tavern with a Waypoint that is a popular tourist destination due to its famous entrance to the Undermountain dungeon.                                                                |
# Waterdeep: Factions & Hideouts

This document details the locations of various factions, criminal enterprises, and secret societies within Waterdeep. It is designed to be used with a map and coordinate system for precise location tracking.

## I. Underworld Lairs & Criminal Activity

This section covers known hideouts and centers of operation for Waterdeep's criminal factions.

|   |   |   |   |   |
|---|---|---|---|---|
|**Location/Operation**|**Faction/Group**|**Ward**|**Coordinates**|**Notes**|
|**Xanathar's Lair**|Xanathar Guild|Dock|`[1582, 1490, -1]`|Main lair of the Xanathar. Located beneath the Philosopher's Court, accessed via sewer junction SF72. Heavily guarded.|
|**Citadel of the Bloody Hand**|Shadow Thieves (formerly)|Castle|`[1274, 1799, -1]`|A former stronghold of the Shadow Thieves, now garrisoned by the City Guard. Accessed via sewer entrances SF73 (north) and SF74 (south).|
|**Old Xoblob Shop**|Xanathar Guild|Dock|`[1650, 1248, 0]`|A front for the Xanathar Guild, used for surveillance and selling curiosities. The stuffed beholder in the window is a key feature.|
|**The Skewered Dragon**|Zhentarim|Dock|`[1621, 1228, 0]`|A rough tavern used as a meeting place and recruitment ground for the Zhentarim.|
|**Yellowspire**|Xanathar Guild|Castle|`[1018, 2820, 1]`|A wizards' tower that secretly houses a teleportation circle connected to Xanathar's Lair.|
|**Grinda Garloth's Residence**|Xanathar Guild|Dock|`[829, 1459, 0]`|A private residence used as a safe house and for clandestine meetings by Xanathar's agents.|
|**Terasse Estate**|Cassalanter Family|Sea|`[991, 3211, 0]`|While a noble estate, it is the center of the Cassalanters' cult activities and illicit dealings.|
|**Various Warehouses**|Varies|Dock|N/A|Many warehouses in the Dock Ward, such as the Gralhund, Thomm, and Helmstar warehouses, are used as fronts or temporary safe houses.|

## II. Unions, Guilds, & Secret Societies

This section details the meeting places and headquarters of more legitimate, but often secretive, organizations.

|   |   |   |   |   |
|---|---|---|---|---|
|**Location/Operation**|**Faction/Group**|**Ward**|**Coordinates**|**Notes**|
|**Bugbear's Pub**|Dockers' Union|Dock|`[1400, 1450, -1]`|A secret, members-only pub for a workers' union, located in the cellar of an abandoned factory off Julbuck Alley.|
|**Tower of the Order**|Watchful Order of Magists & Protectors|Castle|`[1403, 2270, 1]`|The official headquarters of the city's most powerful wizard's guild. A center of magical learning and power.|
|**The Plinth**|Various Faiths|Trades|`[1717, 1842, 0]`|A public temple that secretly hosts meetings for various factions under the guise of religious services.|
|**The Grinning Lion**|The Unseen (rumored)|North|`[1691, 2696, 0]`|A tavern with a secret passage to sewer junction SF31, rumored to be a meeting spot for agents of The Unseen.|
|**Sea Elf Trading Outpost**|Sea Elves|Undersea (Harbor)|`[2160, 639, -1]`|An official trading post, but also a center for intelligence gathering among the aquatic races allied with Waterdeep.|
|**Tespergates**|The Confluence|Sea|`[1031, 3113, 0]`|The base of operations for this secret society, with hidden sewer access for lower-ranking members.|
|**The Raging Lion**|Dwarven Clans / Mercenaries|North|`[1880, 3190, 0]`|A popular inn for various dwarven clans and mercenary groups to conduct business and recruit members.|
|**House of Inspired Hands**|Gondar Priesthood|Sea|`[762, 3244, 0]`|While a public temple to Gond, its workshops are home to secretive inventor circles and unions.|

## III. Centers of Knowledge & Culture

This section details schools, libraries, museums, and other places of learning and art.

|                                |                       |                  |                   |                                                                                                             |
| ------------------------------ | --------------------- | ---------------- | ----------------- | ----------------------------------------------------------------------------------------------------------- |
| **Location**                   | **Type**              | **Ward**         | **Coordinates**   | **Notes**                                                                                                   |
| **New Olamn**                  | Bardic College        | Castle           | `[771, 2668, 0]`  | A prestigious and traditional bardic college.                                                               |
| **House of Wonder**            | Mage Academy / Temple | Sea              | `[997, 3348, 0]`  | A temple to Mystra that also functions as a prominent magical academy.                                      |
| **Eltorchul Academy**          | Mage Academy          | Sea              | `[1026, 3435, 0]` | A well-known magic academy housed within the Eltorchul Villa.                                               |
| **Font of Knowledge**          | Library / Temple      | Castle           | `[950, 2646, 0]`  | A grand temple to Oghma, the god of knowledge, serving as one of the city's foremost libraries.             |
| **The Zoarstar**               | Guildhall / Library   | Trades           | `[1760, 1936, 0]` | Headquarters of the Scriveners', Scribes', & Clerks' Guild, containing extensive records and a scriptorium. |
| **Map House**                  | Guildhall / Archive   | Trades           | `[1334, 1938, 0]` | Guildhall of the Surveyors', Map & Chart-Makers' Guild, holding the best collection of maps in the city.    |
| **Seven Masks Theater**        | Theater               | Dock             | `[1231, 1572, 0]` | A theater that caters to the masses, admitting ship captains and sailors for free.                          |
| **Lightsinger Theater**        | Theater               | Castle           | `[1387, 2562, 0]` | A high-end theater known for its sophisticated productions.                                                 |
| **Book Wyrm's Treasure**       | Bookstore             | North            | `[1595, 3251, 0]` | A bookshop specializing in rare and magical tomes.                                                          |
| **Berendarr's World of Words** | Newsstand / Shop      | South            | `[1892, 1057, 0]` | Specializes in selling broadsheets and news from across the realms.                                         |
| **Hall of the Sages**          | Tomb / Archive        | City of the Dead | `[1763, 2095, 0]` | A tomb reserved for sages, rumored to contain copies of their life's work.                                  |