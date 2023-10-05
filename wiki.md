# Wildfires Across Washington State

<br>![Wildfires in Washington State](https://www.wfpa.org/wp-content/uploads/2017/12/wildfire.jpg)

The topic I selected begins with a question, How has wildfires' size (in acres) changed over the decades <span style="color:red">*(1984 - 2022)*</span>?  

<span style="font-family:Times New Roman;">*(This is a project I started in Geog 360)*</span>

## Introduction
Wildfires are recurring natural disasters in Washington State that cause significant ecological and economic damage. In order to prepare for future wildfires it is necessary to understand the past patterns of wildfire sizes over the last 40 years caused by climate change. This report analyzes the exponential changes in wildfire sizes, measured in acres from 1984 to 2022.<br>

## Methodology
To get started on my research question I gathered my data from the Washington State Department of Natural Resources (Washington Large Fires 1973-2022) and the Washington State Department of Transportation (City Points). The data collected from the DNR included the year of the wildfire and the size reported in acres. The data from WSDOT contained 211 cities, 70 of which were categorized as major cities. To use this data, multiple spatial analysis operations were used. Since the data from the DNR Washington large fires contained over 1100 fires over the span of 50 years I only included fires that were considered large by the EPA (1000 acres). This was done by using Extract by Expression and only using wildfires greater than 1000 acres. Instead of 1100 wildfires the map now only shows 455. Once the wildfires were filtered there were no fires greater than 1000 acres from 1973-1983, so the data that I am presenting starts in 1984. The city points data from the WSDOT had 211 cities, I used Extract by Attribute to filter only the major cities which then resulted in only 70 cities. The last spatial analysis used was a ten-mile buffer around each city to show how close the large wildfires were and how it could have an impact on people's health and well-being, along with the buffer are labels of the cities to distinguish which cities are heavily impacted each year.<br>

![Map showcasing wildfires over 1000 acres](https://lh3.googleusercontent.com/pw/ADCreHcrGvQE9CbVQU00ldnniZHIYi-MqmxO__YRCshUoNiCHFVzlMQwqQ3vXMJwTCCiituzGztKjl6w5ph8umRxqczk16KLLh-8u1u50aQJXmTkwwbSEqNyFFbkJGY1qfR5P0HVKMS2t2mUIlMUKxMV5rwEadeYft0hNxwz0KTiOgPLuzD8vU23TJx9LeSZT9-ZjwrGx8HjRDhG5UbvjDgYQPGrjlLKoT66cmhPNGFON9BhbB7Kms626DmfRJkMUtEggMfGXTa3l7QZowp4HivpGfPUVETi-f48guQ-KjdnOKl4fkfu3HS25dx2qRaLwqKFV5Lad707t7g1enkL2bDVzVlZ9bCIvA3GGuAhRdLwECUanKcPqknQpnaWpe69nlVNB_LwESLE0qY0rAsu0UXGjst8mVVeybtMpk8ameZJJLOYzKz0GTlSh7Eu7wXAHpaFkFZW9KlerH_PiTpPnHoR5qfFAo0gmNoey2Vc5P18ZkhXYhaPKC_6dMJOeBLTxWj-ZAUzDLzwWoRVSA-Ps4sSMUCstWKuqucJPAb01ivx5STt6L2VLWZzmktxPoIpCAM1IZr81aGGUcKbWYc0xZnGz8RJqmNBPnXclOIm3hIpjKNNGGauwdcOlS7TJCJRsPcdJwv30yk8hoPwE2Tt-XpKaNo9C969FF9KtMqO_oeuh3TYprRnW4PYcoTUtPsInee9XdZJAV1z9rppiaRwPHuWyvH6_lg-1sA4kg5ZD0DYR3GuAuHDeGjpDncfKzeFSKGDnXAdxaTZdfRkojLf8JPg-ANqk1k_cpvk4O0HAqj_Gab4y1XUyl9jVpJyb8KVdSRcxYi7NhZgbUa8S6f0rjafhz-ns-9ZO2DBFJUXHwJvfJ23o7Cdc2dNO_VFSFJbkWKUDNnro_gHzPC9jDRwA7a1=w1996-h1412-s-no?authuser=0) 

## Results
The results from the data provided showcase that wildfires have been increasing in large amounts through the decades. For example, there was only one wildfire that took place in the 1970s, and that was in 1973 and it burned 499 acres. In 2022 alone 28 wildfires took place that were over 1000 acres. From 1984 - 2022 the average size of these wildfires has shown a gradual increase in size but has been more consistent.  There are notable wildfire sizes from year to year, some years did have very large wildfires, but overall as the years have progressed so have the size and the occurrence of the fires. From 1984 - 1989 saw 34 wildfires over 1000 acres, and from 1990 - 1999 there were 34 wildfires. In just ten years time from 2000 - 2009, the number of wildfires over 1000 acres tripled (97). The biggest change in any decade so far is from 2010 - 2019 and that decade saw 213 wildfires greater than 1000 acres. Just within the last three years, there has been a larger increase in wildfires in such a short time, 81 of them being over 1000 acres. Climate change has played a role in the increase in wildfire sizes. Some factors that could help these wildfires get bigger are rising temperatures and decreased precipitation across Washington State. Below I have added a chart I made in Google Sheets to represent the average amount of acres burned through the years of wildfires over 1000 acres. The chart can make a clear distinction that wildfires have been getting larger with the increasing frequency of wildfires and size. <br>

![Image of Size of Wildfires in Acres over the Decades](https://lh3.googleusercontent.com/pw/ADCreHcrtVtG9bwt_dm1wDEjObscgRXnq-rQeQrmZ4eHJz9zDWHsgzS_3Wo7IXx7CbQOMAeBjnDcbiJwkTeIsXUS48QN4w__xfsCd7b1SxKbctd0cUyElEytNf41E0l4wa6pD6MSWpjp3F06TJa5ljEQPN1JohhgpG-iaJRlLF-qcsW0GCMijNRkiLCu7HdUV01oJoA_WTlkBu5pEgAtw1CpjCatunnaXs8MBP-pvwt-v5HzUz_J7gVmazBFcVzMKpGELuXlPG7taaJmEubtf0zhxeuv7bRE-clMfDamXP5DRqF7fshoteP0yDavKkvh9VuwLndPLQF-BvaXOy0lV33pDj8dRiLHKOrNuyR4W3O4kBF13hnXgimd5k710FUW3n4I1vWeIBc70IyjjSBay_2tjAQP6psDHG4idLW38lXIJQ9c7u-1qN8xW8jXCF49J8welO0w5-fCEYlV4Hp5ub_RUivVAwquE0olyZw3r2X4XSQqXl706LvscAbwkhBjx274a5w0D6QP77tnZ2gyFQIy_eRBkSIkNNKPexGxY4p3vll1PoIyR2pE2fKIrEYVAabeW9gAK1ops3f4dIIrbQ5r8Zf3cNUM95Xj9hi1emOMegj9E_zrd84SK6SVB7B25nMst4NF3EFSirTzSd8dAx_UGr6i4oFK2DOz6PehJSd6L_HPoWSxhRxB5k0F5JzIJEtNqG4tT0DJ2hgPcvkC6Po3P2I1Vlh8glXEBqv5_tIBYqyjN7HWtG1zH7XIaryPwBZ83lRWiPBcQb4Hto8Egye2H4tpgcT2bHhiDx5T7ReRAPzoFiRluyYTwEbGYMIXYDOMv144hrMs30K0BBzNQo8LEnVeABBRBnMpcTJSwZGQhu1wV1ENLqjp0SMW1emcTBKvCAe2Hp07ureAuz17uN8Z=w1194-h734-s-no?authuser=0)


## Conclsion
The large wildfire sizes in Washington State from 1984 - 2022 show a clear increasing trend in size and in frequency. The findings from the data underscore the importance of long-term trends and climate factors in government planning and policy decisions related to wildfire prevention, response, and ecological restoration efforts here in Washington State. Continued data gathering and research are essential to better understand the relationship between wildfires, climate change, and the impacts it has on ecosystems and our communities.  


### Sources
<ul>

<li> 

[Washington Large Fires 1973-2020](https://data-wadnr.opendata.arcgis.com/datasets/wadnr::washington-large-fires-1973-2022/explore) </li>

<li>

[WSDOT-City Points](https://geo.wa.gov/datasets/cfc2b6503ecd45efa03052d7b9e28a95/about) </li>

<ul>



