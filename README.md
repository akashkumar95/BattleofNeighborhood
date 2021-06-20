# BattleofNeighborhood

## **Table of contents**


*   [Business understanding](#intro)
*   [Data requirements](#requirements)
*   [Data collection](#collection)
*   [Data visualization]
*   [Data understanding]
*   [Data analytics]
*   [Model evaluation]
*   [Result analysis]

## **Business understanding** <a name="intro"></a>

Chennai is one of the largest cultural, economic and educational centres of South India. Chennai's various recreational spots attracts a huge amount of tourists. Considering the mobility across the city being it tourists, college students or office goers, starting a **cafe business** at a right spot will be a great success. 

This project analyses various aspects such as **population density, recreational centers, existing food outlets,** etc. and suggests a right locality for opening a cafe.

## Data requirements <a name="requirements"></a>

Various aspects such as **list of areas** in the city, **population distribution**, **recreational spots**, available **restaurants** in each locality, etc. are required for analysing our problem. Let us discuss the collection of these data in the following section.

## Data collection <a name="collections"></a>
The primary data to be collected is list of **latitudes and longitudes** of Chennai city. Let us collect this information from https://chennaiiq.com/chennai/latitude_longitude_areas.asp. We will be using **BeautifulSoup** to **scrap** the necessary details from the above link. The processed data will be passed to **Foursquare API** in order to extract further information regarding the localities.
