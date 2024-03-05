# BRMA-guidance-notes

Broad Rental Market Areas (BRMAs) are geographic areas used to set the amount of assistance with private rental housing costs that low income households can receive in the UK. Each BRMA has a Local Housing Allowance (LHA) rate that varies geographically according to the prevailing housing rents in that area, along with other restrictions that may be set by central government.  

Information on BRMAs across the UK is a little difficult to come by, so this repository contains some notes on these BRMAs along with shapefiles for those interested in conducting analysis about these areas.

BRMAs cover England, Wales, Scotland and Ireland, though they are administered by different agencies. They were defined and introduced in 2008. There are 192 BRMAs across the UK. 

Contacts: 

- England: Valuation Office Agency, sohelpdesk@voa.gov.uk
- Scotland: Rent Service Scotland, rss.dundee@gov.scot
- Wales: Rent Officers Wales, rentofficerhelpdesk@gov.wales
- Northern Ireland: Rent Officer for Northern Ireland, info.rentofficer@communities-ni.gov.uk

The Urban Big Data Centre has a [lookup file from postcodes to BRMAs](https://data.ubdc.ac.uk/dataset/postcode-to-broad-rental-market-areas-brmas-lookup) and a collection of [LHA rates for BRMAs](https://data.ubdc.ac.uk/dataset/local-housing-allowance-lha-rates-per-broad-rental-market-area-brma-2012-2023) from 2012 to 2023. 


## England

England BRMAs at May 2020: [boundary file in GML format](https://www.gov.uk/government/publications/broad-rental-market-area-boundary-layer-for-geographical-information-system-gis-applicable-may-2020)

As of February 2024 there have been two very small changes implemented at the boundary between Southampton and Portsmouth BRMAs (implemented on 1st April 2017) and the Barnsley and Wakefield BRMAs (implemented on 1st April 2023). Maps of these changes are included in this repository (see `changes` folder). I was told on 26 Feb 2024 that other BRMA reviews are currently in progress but yet to result in any changes.  


## Scotland

Scotland BRMAs: boundary files at [spatialdata.gov.uk](https://spatialdata.gov.scot/geonetwork/srv/eng/catalog.search;jsessionid=45DAF936F7807CBFE9B598F5128FBE08#/metadata/ecf60902-9e71-41bc-b822-6a1f37934dc1)

The boundaries have not changed since they were created, but there was a mapping error that was found and amended in 2015. Oban was showing up as being part of Highland and Islands Broad Rental Market Area (BRMA) when it was in fact part of the Argyll and Bute BRMA.

Some additional information on BRMAs and the calculation of LHA rents are available through Freedom of Information requests [here](https://www.gov.scot/publications/foi-202300343447/), [here](https://www.gov.scot/publications/foi-202200303624/) and [here](https://www.gov.scot/publications/foi-202300368850/). 


## Wales 

I am awaiting details of the BRMAs for Wales. 

The boundaries of these BRMAs have not changed. 


## Northern Ireland 

There are [8 BRMAs](images/ni-brmas-Feb2024.jpg) in Northern Ireland, defined by postcode.

Belfast BRMA: BT1-BT16
Lough Neagh Upper BRMA: BT29, BT36-BT46, BT80
Lough Neagh Lower BRMA: BT25, BT62-BT67, BT69-BT71
North BRMA: BT51-BT57
North West BRMA: BT47, BT48, BT49, BT82
South BRMA: BT32, BT34, BT35, BT60, BT61, BT68
South East BRMA: BT17-BT24, BT26, BT27, BT28, BT30, BT31, BT33
South West BRMA: BT74-BT79, BT81, BT92, BT93, BT94

The BRMA classification currently in use was defined following the introduction of LHA in 2008 and there has been no change.

