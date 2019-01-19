
| SSD BRAND     | NAND | 128GB  | `256GB`  | 500GB  | 1TB  | Source | Warrany | Review sort by negative |
| :---------- |:-------------:| -----:| -----:| -----:| :-----:| -----:| -----:| -----:|
| `Samsun 860 PRO` | 3D NAND |  -- |  300TBW  |  600TBW | 1,200TBW  | [HTML](https://www.samsung.com/semiconductor/minisite/ssd/product/consumer/860pro/) | `5-years` | [*](https://www.amazon.com/Samsung-512GB-V-NAND-Solid-MZ-76P512BW/product-reviews/B07836C6YV/ref=cm_cr_arp_d_viewopt_sr?ie=UTF8&filterByStar=critical&reviewerType=all_reviews&pageNumber=1#reviews-filter-bar) |
| `Adata SSD Ultimate SU900` | 3D TLC |  100TBW |  200TBW  |  400TBW  |  800TBW  | [PDF](https://www.adata.com/upload/downloadfile/Datasheet_SU900_EN_20170710.pdf) | `5-years`  | [*](https://www.amazon.com/ADATA-SU900-Ultimate-Internal-Solid/product-reviews/B01N5JJ7H9/ref=cm_cr_arp_d_viewopt_sr?ie=UTF8&filterByStar=critical&reviewerType=all_reviews&pageNumber=1#reviews-filter-bar) |
| `ADATA Ultimate SU800 ` | 3D NAND |  100TBW |  200TBW  |  400TBW | 800TBW | [HTML](https://www.adata.com/upload/downloadfile/Datasheet_SU800_EN_20180503.pdf) | _3-years_  | [*](https://www.amazon.com/ADATA-SU800-128GB-3D-NAND-ASU800SS-128GT-C/product-reviews/B01K8A29BE/ref=cm_cr_dp_d_hist_1?ie=UTF8&filterByStar=one_star&reviewerType=all_reviews#reviews-filter-bar) |
| `Samsung SSD 860 EVO`      | 3D TLC |  --- |  150TBW  |  300TBW  |  1,200TBW  | [HTML](https://www.samsung.com/semiconductor/minisite/ssd/product/consumer/860evo/) | `5-years` | [*](https://www.amazon.com/Samsung-500GB-Internal-MZ-76E500B-AM/product-reviews/B0781Z7Y3S/ref=cm_cr_arp_d_viewopt_sr?ie=UTF8&filterByStar=critical&reviewerType=all_reviews&pageNumber=1#reviews-filter-bar) |
| `Adata Ultimate SU650` | 3D NAND |  70TBW |  140TBW  |  280TBW | ---  | [PDF](https://www.adata.com/upload/downloadfile/Datasheet%20-%20Ultimate%20SU650_EN_20170908.pdf) | _3-years_  |-- |
| `KINGSTON SSD Now  V300` | 3D NAND |  64TBW  |  128TBW  |  256TBW | --  | [HTML](https://www.kingston.com/datasheets/sv300s3_us.pdf) | _3-years_  |-- |
| `WD Blue 3D NAND` | 3D NAND |  --- | 100TBW | 200TBW | 400TBW | [PDF](https://www.wd.com/content/dam/wdc/website/downloadable_assets/eng/spec_data_sheet/2879-800092.pdf) | `5-years`  | [*](https://www.amazon.com/Blue-NAND-500GB-SSD-WDS500G2B0A/product-reviews/B073SBZ8YH/ref=cm_cr_arp_d_viewopt_sr?ie=UTF8&filterByStar=critical&reviewerType=all_reviews&pageNumber=1#reviews-filter-bar) |
| `Crucial MX500` | 3D NAND |  -- |  100TBW  |  180TBW  |  360TBW  | [HTML](https://www.crucial.com/usa/en/storage-ssd-comparison) | `5-years`  |-- |
| `Sandisk Ultra 3D` | 3D NAND |  -- |  100TBW  |  200TBW | 400 TBW  | [HTML](https://www.sandisk.com/home/ssd/ultra-3d-ssd) | _3-years_  |-- |
| `Crucial BX500` | 3D NAND |  40TBW |  80TBW  |  120TBW | 240 TBW  | [HTML](https://www.crucial.com/usa/en/storage-ssd-comparison) | _3-years_  |-- |
| `Kingston A400 SSD ` | TLC | 40TBW  | 80TBW   | 160TBW   |  300TBW  | [PDF](https://www.kingston.com/datasheets/SA400S37_us.pdf) | _3-years_  |-- |
| `SanDisk SSD Plus` | TLC |  40TWB?*1 | *1 |  *1 | *1  | [HTML](http://webcache.googleusercontent.com/search?client=firefox-b&q=cache%3Ahttps%3A%2F%2Fus.hardware.info%2Fproduct%2F417369%2Fsandisk-ssd-plus-tlc-120gb%2Fspecifications) | _3-years_  |-- |
| `WD Green SSD` | 3D NAND |  40TB| 80TBW |  -- | --  | [HTML](https://www.wd.com/content/dam/wdc/website/downloadable_assets/eng/spec_data_sheet/2879-800083.pdf) | _3-years_  |-- |



*1 - hard to find even on: [official forum](https://forums.sandisk.com/t5/SanDisk-SSD-Plus/TBW/td-p/367680) :: type this in google to get some spec include TBW `cache:https://us.hardware.info/product/417369/sandisk-ssd-plus-tlc-120gb/specifications`

# Todo with new SSD
- Download [Discmark](http://crystalmark.info/en/download/#h2) and write test data 32GiB some of them crash afert write some data to disk, you do this at your own risk.
- Download [discinfo](http://crystalmark.info/en/download/) and monitor "Total NAND Write" some SSD has only "Total Host write"
- You can monitor SSD life with [SSD life](http://ssd-life.com/eng/download-ssdlife.html)
- Yo can free some space on windows by disbale hibernation `powercfg.exe /hibernate off` or even disbale swap when you get more than 8Gb of RAM



### Screenshots SSD LIFE
This is my 3 years Crucial on Windows 7
- disabled swap, hibernation
- Firefox cache on RamDisk 300MB
- half os space free, download dir on SD card, games ond other big files on HDD

![SSD LIFE my](https://github.com/Usernameisalreadytaken5/SSDTWB/blob/master/SSDLIFE.png)

### Screenshots Crystal Disk info ADATA SU800
![ADATA SU800](https://github.com/Usernameisalreadytaken5/SSDTWB/blob/master/ADATA%20SU800.png)

### Screenshots Crystal Disk SanDiskSSDPlus240GB
![SanDiskSSDPlus240GB](https://github.com/Usernameisalreadytaken5/SSDTWB/blob/master/SanDiskSSDPlus240GB.png)






