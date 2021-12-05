# Laptop carbon footprints

This is a list of carbon footprints compiled from various sources for common laptops. I have compiled these from various sources in case you need a new laptop. If you would like to add more to this list, please issue a pull request.

**kg CO2e** (kg. CO2 equivalent) is the total expected lifetime (4-year) carbon footprint of the device.

**kg CO2e w/o use** is the total footprint of the device to make it and send it to you. If your electricity sources are carbon-neutral, this number is the one that matters.

### Laptop footprints, in perspective

Aside from the outlier X270, the worst laptop on this list is the Thinkpad P52 at 693 kg CO2e over a four-year lifespan. [A single cheeseburger has a carbon footprint of about 4.35 kg CO2e](http://www.openthefuture.com/cheeseburger_CF.html). Buying a P52 is the same cost as eating 159 cheeseburgers over the course of that four years - or eating a single cheeseburger every 1.3 weeks. There is a reason why environmentalists push vehicle emissions first and animal agriculture second - the cost of eating _red meat_ is substantially worse than even other meat options. It is good to minimise carbon emissions wherever you can, but remember that driving less and avoiding beef consumption will drastically outweigh your laptop purchasing choices in terms of carbon footprint.

Note that organisations do play with these numbers a bit, because the science to calculate these is relatively inexact. Lenovo reports the 95th percentile worst-case as their footprints in the data sheet; some other organizations will quote the median +/- a specific value. Use this as a guide, and read the attached documents for more information.


## tl;dr

Microsoft's Surface series usually beats Apple. If you can use Windows 10 Pro, the Surface series has the lowest overall manufacturing footprint in the CSR reports. Apple is a close second, with Lenovo coming in last place. Note that the Microsoft and Apple laptops are not repairable. Let's all be happy that the Thinkpad X270 is no longer in production - each one cost the world 0.8 MT CO2e.

Chromebooks may be an option for you when using [Crostini](https://chromium.googlesource.com/chromiumos/docs/+/master/containers_and_vms.md), but make sure that the device you buy supports the Linux container functionality before purchasing. Support is getting better as of 2019 but some devices (e.g. Skylake-based devices) still do not have Crostini support at the time of this writing.

## Apple

Macs have insanely low carbon footprints compared to respective Lenovo models. The most carbon-friendly MacBook **at manufacture** is the new MacBook Air, at 176kg CO2e with use and 165.44 without. However, the new Apple Silicon M1 MacBook Pro 13" has a better after-use calculation at 149.85 according to Apple's documentation.

Note the four-year lifespan of these. **These Apple products are virtually nonrepairable**, so the lifetime of them will likely be much less than a Thinkpad or Latitude. Keep that in mind - most of the footprint is up front with the laptop's manufacture. If you are keeping it for a long time, you're probably better off with the Thinkpad.

|Model|kg CO2e|kg CO2e w/o use|Source|
|---|---|---|---|
|Macbook 12"|233|205.04|[Apple](https://www.apple.com/environment/pdf/products/notebooks/12-inch_MacBook_PER_oct2018.pdf)|
|Macbook Air 13" (Non-Retina)|339|294.93|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookAir_PER_June2017.pdf)|
|Macbook Air 13" (Retina, Thunderbolt)|176|165.44|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookAir_w_Retina_PER_oct2018.pdf)|
|Macbook Air 13" (Retina, 2019)|176|166.04|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookAir_w_Retina_PER_June2019.pdf)|
|Macbook Air 13" M1 (2020) 256GB SSD|**161**|**136.85**|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookAir_PER_Nov2020.pdf)|
|Macbook Air 13" M1 (2020) 512GB SSD|181|153.85|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookAir_PER_Nov2020.pdf)|
|Macbook Air 13" Intel (2020) 256GB SSD|170|144.5|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookAir_PER_Nov2020.pdf)|
|Macbook Air 13" Intel (2020) 512GB SSD|198|168.3|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookAir_PER_Nov2020.pdf)|
|Macbook Pro 13" (Skylake and newer)|222|184.26|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookPro_PER_may2019.pdf)|
|Macbook Pro 15" (Skylake and newer)|334|263.86|[Apple](https://www.apple.com/environment/pdf/products/notebooks/15-inch_MacBookPro_PER_may2019.pdf)|
|Macbook Pro 13" (2019)|210|198.11|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookPro_PER_June2019.pdf)|
|Macbook Pro 16" (2019)|394|331.09|[Apple](https://www.apple.com/environment/pdf/products/notebooks/16-inch_MacBookPro_PER_Nov2019.pdf)|
|Macbook Pro 13" M1 (2020) 256GB SSD|185|149.85*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookPro_PER_Nov2020.pdf)|
|Macbook Pro 13" M1 (2020) 512GB SSD|207|167.67*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/13-inch_MacBookPro_PER_Nov2020.pdf)|
|Macbook Pro 14" M1 Pro (2021) 256GB SSD|271|211.38*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/14-inch_MacBook_Pro_PER_Oct2021.pdf)|
|Macbook Pro 14" M1 Pro (2021) 512GB SSD|307|239.46*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/14-inch_MacBook_Pro_PER_Oct2021.pdf)|
|Macbook Pro 14" Intel (2021) 256GB SSD|252|196.56*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/14-inch_MacBook_Pro_PER_Oct2021.pdf)|
|Macbook Pro 14" Intel (2021) 512GB SSD|300|234*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/14-inch_MacBook_Pro_PER_Oct2021.pdf)|
|Macbook Pro 16" M1 Pro (2021) 512GB SSD|349|254.77*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/16-inch_MacBook_Pro_PER_Oct2021.pdf)|
|Macbook Pro 16" M1 Pro (2021) 1TB SSD|382|278.86*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/16-inch_MacBook_Pro_PER_Oct2021.pdf)|
|Macbook Pro 16" M1 Max (2021) 1TB SSD|395|288.35*|[Apple](https://www.apple.com/environment/pdf/products/notebooks/16-inch_MacBook_Pro_PER_Oct2021.pdf)|

\* Apple does not change the "use" proportion for any 2020 MacBook Pro, so the M1 uses the same amount of energy as the Intel variants.

## Chromebooks

Chromebook product carbon footprints vary widely. In order to normalise the numbers, the 95th percentile number is quoted where appropriate in this table (as Lenovo and HP both report). Note that HP's data is generally pretty bad; the 95th percentile is far off from their expected range so they are likely over-reported in this table.

I cannot locate Acer's carbon footprint calculations; they talk about environmental responsibility in a PR-like page and the data for the old Chromebook C740 is included, so I have added it to this list.

|Model|kg CO2e|kg CO2e w/o use|Source|
|---|---|---|---|
|Acer Chromebook C740|123.70|81.679|[Press Release](https://www.acer-group.com/sustainability/en/energy-climate-change.html)|
|Google Pixelbook|200.6|126.5|[Google PER](https://storage.googleapis.com/gweb-sustainability.appspot.com/pdf/MAR2018_PRODUCT-REPORTS/Pixelbook_ProductEnvironmentalReport.pdf)|
|HP Chromebook 11 G7 Education Edition|275|&approx;257&dagger;|[HP Report](http://h22235.www2.hp.com/hpinfo/globalcitizenship/environment/productdata/Countries/_MultiCountry/productcarbonfootprint_notebo_2019416223433906.pdf)|
|HP Chromebook Enterprise 14A G5|295|&approx;260&dagger;|[HP Report](http://h22235.www2.hp.com/hpinfo/globalcitizenship/environment/productdata/Countries/_MultiCountry/productcarbonfootprint_notebo_20191010233353436.pdf)|
|HP Chromebook Enterprise x360 14E G1|505*|&approx;475&dagger;|[HP Report](http://h22235.www2.hp.com/hpinfo/globalcitizenship/environment/productdata/Countries/_MultiCountry/productcarbonfootprint_notebo_20191021223117676.pdf)|
|HP Chromebook x360 11 G2 Education Edition|745*|&approx;715&dagger;|[HP Report](http://h22235.www2.hp.com/hpinfo/globalcitizenship/environment/productdata/Countries/_MultiCountry/productcarbonfootprint_notebo_2019412224038116.pdf)|
|HP Chromebook x360 14 G1|305|&approx;272.5&dagger;|[HP Report](http://h22235.www2.hp.com/hpinfo/globalcitizenship/environment/productdata/Countries/_MultiCountry/productcarbonfootprint_notebo_201924225842986.pdf)|
|Lenovo YOGA Chromebook C630|293|187.52|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/eco-declaration/PCF_YOGA_Chromebook_C630.pdf)|
|Lenovo 100e Chromebook (2nd Gen)|303|236.34|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/PCF_Chromebook_100e_2nd_Gen.pdf)|
|Lenovo 300e Chromebook (2nd Gen)|305|237.9|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/PCF_Chromebook_300e_2nd_Gen.pdf)|
|Lenovo 500e Chromebook (2nd Gen)|303|236.34|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/PCF_Chromebook_500e_2nd_Gen.pdf)|
|Lenovo 14e Chromebook|368|272.32|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/PCF_Lenovo_14e_Chromebook.pdf)|

\* The data for this Chromebook has extreme outliers in estimation. Please see the report for more info.

&dagger; HP does not give percentages for use; this is done by trying to approximate the average from the plots displayed without adjacent data.

## Dell

Dell does not produce as many carbon footprint sheets, but does for
some specific models.

The Latitude 7280/7390 has the best footprint, at 187.81 without use and
222 with use included. This may be the best all-around deal, because the
Latitude series is relatively repairable, reliable being business-class,
and gets very close to Apple's numbers.

|Model|kg CO2e|kg CO2e w/o use|Source|
|---|---|---|---|
|XPS 13 9370|297|260.17|[Dell CFA](https://i.dell.com/sites/csdocuments/CorpComm_Docs/en/carbon-footprint-xps-9370.pdf)|
|XPS 15 9560|337|265.22|[Dell CFA](https://i.dell.com/sites/csdocuments/CorpComm_Docs/en/carbon-footprint-xps-9560.pdf?newtab=true)|
|XPS 15 9570|324|266|[Dell CFA](https://i.dell.com/sites/csdocuments/CorpComm_Docs/en/carbon-footprint-xps-15-9570.pdf)|
|Latitude 7280|222|187.81|[Dell CFA](https://i.dell.com/sites/csdocuments/CorpComm_Docs/en/carbon-footprint-latitude-7280.pdf?newtab=true)|
|Latitude 7390|**222**|**187.81**|[Dell CFA](https://i.dell.com/sites/csdocuments/CorpComm_Docs/en/carbon-footprint-latitude-7390.pdf?newtab=true)|
|Latitude 7490|241|210.63|[Dell CFA](https://i.dell.com/sites/csdocuments/CorpComm_Docs/en/carbon-footprint-latitude-7390.pdf?newtab=true)|
|Precision 5530|340|285.59|[Dell CFA](https://i.dell.com/sites/csdocuments/CorpComm_Docs/en/carbon-footprint-precision-5530.pdf?newtab=true)|
|Precision 7720|416|319.9|[Dell CFA](https://i.dell.com/sites/csdocuments/CorpComm_Docs/en/carbon-footprint-precision-7720.pdf?newtab=true)|



## Lenovo Thinkpad

Without use included, the best Thinkpad in this list is the Thinkpad A285, with 225.28 kg CO2e. If you want Intel (or Thunderbolt 3), your choice is the Thinkpad X390, with 246.5 kg CO2e. However, the A285's architecture is old and it is power hungry.

With use included, the best Thinkpad in this list is the X395, with 286 kg CO2e (and the X280 following up with 334.)


|Model|kg CO2e|kg CO2e w/o use|Source|
|---|---|---|---|
|Thinkpad 25|390|280.8|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-25.pdf)|
|Thinkpad 11e 5th Gen|326|260.8|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF-ThinkPad-11e-Yoga-11e-5th.pdf)|
|Thinkpad A275|511|352.59|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-A275.pdf)|
|Thinkpad A285|352|**225.28**|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-A285.pdf)|
|Thinkpad A485|419|272.35|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-A485.pdf)|
|Thinkpad E14 2nd Gen|349|N/A&dagger;|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/eco-declaration/pcf-thinkpad-e14-2nd.pdf)|
|Thinkpad L14|593|N/A&dagger;|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/eco-declaration/pcf-thinkpad-l14.pdf)|
|Thinkpad L380|406|328.86|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF-ThinkPad-L380-S2-Yoga-3rd.pdf)|
|Thinkpad L480|455|318.5|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF-ThinkPad-L480.pdf)|
|Thinkpad L490|499|394.21|[Lenovo PCF](https://www.lenovo.com/us/en/pdf/social_responsibility/PCF_ThinkPad_L490.pdf)|
|Thinkpad P1|477|400.68|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF_ThinkPad_P1_X1_Extreme.pdf)|
|Thinkpad P52|693|540.54|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-P52.pdf)|
|Thinkpad P72|610|469.7|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF_ThinkPad_P72.pdf)|
|Thinkpad P73|611|403.25|[Lenovo PCF](https://www.lenovo.com/us/en/pdf/social_responsibility/PCF_ThinkPad_P73.pdf)|
|Thinkpad T14 AMD|361|N/A&dagger;|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/eco-declaration/pcf-thinkpad-t14-amd.pdf)|
|Thinkpad X1 Carbon 4th Gen|457|370.17|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-X1-Carbon-4th.pdf)|
|Thinkpad X1 Carbon 5th Gen|369|306.27|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-X1-Carbon-5th.pdf)|
|Thinkpad X1 Carbon 6th Gen|333|279.71|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF-ThinkPad-X1-Carbon-6th.pdf)|
|Thinkpad X1 Carbon 7th Gen|461|401.07|[Lenovo PCF](https://www.lenovo.com/us/en/pdf/social_responsibility/PCF_ThinkPad_X1_Carbon_X1_Carbon_LTE_7th.pdf)|
|Thinkpad X1 Extreme|477|400.68|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF_ThinkPad_P1_X1_Extreme.pdf)|
|Thinkpad X1 Extreme (P1) Gen 2|497|422.45|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/eco-declaration/2019/PCF_ThinkPad_P1_X1_Extreme_2nd.pdf)|
|Thinkpad X13|313|N/A&dagger;|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/eco-declaration/pcf-thinkpad-x13.pdf)|
|Thinkpad X250|338|256.88|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-X250.pdf)|
|Thinkpad X260|489|400.98|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-X260.pdf)|
|Thinkpad X270|851.68|766.51|[Lenovo PCF](https://www.lenovo.com/medias/PCF-ThinkPad-X270.pdf)|
|Thinkpad X280|334|257.18|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF-ThinkPad-X280.pdf)|
|Thinkpad X380 Yoga|339|267.81|[Lenovo PCF](https://www.lenovo.com/us/en/social_responsibility/PCF-ThinkPad-S1-Yoga-4th-X380-Yoga.pdf)|
|Thinkpad X390|290|246.5|[Lenovo PCF](https://static.lenovo.com/ww/docs/regulatory/PCF_ThinkPad_X390.pdf)|
|Thinkpad X395|**286**|N/A&dagger;|[Lenovo PCF](https://www.lenovo.com/us/en/pdf/social_responsibility/PCF_ThinkPad_X395.pdf)|

&dagger; "Use" is not displayed in the PCF piechart for this model, so it cannot be calculated.


## Microsoft

My girlfriend recently asked me what the carbon footprint of the Surface devices is, and I did not know. Microsoft makes this easy and [provides eco profiles for download](https://www.microsoft.com/en-us/download/details.aspx?id=55974). This is a list of all Surface hardware included in that download as of 18 November 2021.

It is important to note that the Surface Pro/Go numbers are _just for the device_. The keyboard is considered an accessory and there is an associated manufacturing footprint that is not accounted for there. Microsoft's eco profiles even list the exact specs of the machines they are using for calculations. Note that while the Surface Go is definitely the lowest in this list, it's not really a developer-friendly laptop.

The same nonrepairability warning that goes into the Apple products holds true for the Surface line, as well.

|Model|kg CO2e|kg CO2e w/o use|Source|
|---|---|---|---|
|Surface Go|93.8|66.97|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Go 2|107|80|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Go 3|106|86|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Pro X|130|86|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Pro 4|149|108.77|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Pro 5|121|87.241|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Pro 6|121|87.8|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Pro 7|164|133|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Pro 7+|181|153|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Pro 8|141|118|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Book|225|173.25|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Book 2 (13.5 inch)|183|134.13|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Book 2 (15 inch)|232|179.57|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Book 3 (13.5 inch)|303|256|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Book 3 (15 inch)|421|368|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop|152|119.16|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop 2|152|119.16|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop 3 (Alcantara, 13.5 inch)|**127**|**100**|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop 3 (Metal, 13.5 inch)|138|112|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop 3 (Alcantara, 15 inch)|178|140|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop 3 (Metal, 15 inch)|181|143|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop 4 (Alcantara, 13.5 inch)|145|123|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop 4 (Metal, 13.5 inch)|165|143|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
|Surface Laptop 4 (Metal, 15 inch)|199|177|[Eco Profiles](https://www.microsoft.com/en-us/download/details.aspx?id=55974)|
