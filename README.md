# ATSOAA2025
Hello This is the general overview what we will gonna do. The extent of this project depends upon the your learning capabilities. Before we start with any hands on session, it is essential to have a theoritical background to understanding the science.

Lectures on Atmospheric science in ATSOAA 2025 will covered a general overview of it. Pay extra attention to lectures on DAY2.

Now talking about the project "Influence of biomass burning on Delhi Air pollution using ground and space based observation", I plan to cover PM2.5 (particute matter) and O3 (ozone) which is one of the very hot topic from last 2 decades. I am attaching ...... which will help you understand both PM2.5 and O3.

After you have understood the chemistry of ozone and dynamics of PM2.5 then we will download the data of both of them from CPCB (Central Pollution Control Board). Its a government organisation which was formed by central government to keep an eye on India air pollution. We can take any time period data for the analysis but we are taking 2023 year data. The data is found at https://airquality.cpcb.gov.in/ccr/#/caaqm-dashboard-all/caaqm-landing

You can explore the site and see how to download the data files. Before using any data we always need to clear the junk values and outlier using some filteration technique, we can discuss about it. To save you from the hustle of downloading I have downloaded data which is also filtered from 38 sites (Delhi region) https://drive.google.com/drive/folders/1RYs9-0Y1iWeJ9bjIbKKvWvQUgqQtBpzm?usp=share_link. Out of 38 sites we will choose few sites (~ 10-15 sites), because the data from each 38 sites may not be reliable, so we need to filter some of teh sites as well. This has to be done by analysing the data by plotting them (needs python or any language).

After filtering and selecting the data from sites, we will select a region over india (enclosing delhi). Fire counts from the MODIS (satellite data) will be incorporate. Since fire counts are high during spring and autumn, we will only download these 2 season fire counts data from the MODIS satellite https://firms.modaps.eosdis.nasa.gov. Go to Archive Downlaod after opening the link.

Now we to segregate the days of high biomass burning events over the selected region from the normal days. This will be done using fire counts time series in the defined region. Then we will try to see value of PM2.5 and O3 on those days or succeeding day. GEMS satellite data will also be used to see the spatial temporal variation over the defined region. Rest can be discussed after you reach here.
