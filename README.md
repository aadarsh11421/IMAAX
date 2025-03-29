# IMAAX
Foundations of Spatial Data Science Assessment -  Inside AirBnB

Group members: Aadarsh Ajikumar, Abdulnasir Ibrahim, Miaoyi Li, Idris Baba


## 1. Who collected the InsideAirbnb data?

Murray Cox, the project's founder, gathers and examines much of the Inside Airbnb data, which is publicly accessible data from Airbnb's website. As the community of Inside Airbnb grows, residents, activists, and allies involved keep collecting data.

Taylor Higgins is working to build and organize the data and activist communities of Inside Airbnb.


## 2. Why did they collect the InsideAirbnb data?

1. Offer openness about Airbnb's activities and analyses its effects on local communities and housing markets.

2. The project also serves as a platform for fighting against the negative impacts of short-term rentals.

3. Their vision and mission is to provide data and advocacy about Airbnb’s impact on residential communities.


## 3. How was the InsideAirbnb data collected?

The data from this website was scraped directly from the Airbnb website – (https://www.airbnb.co.uk). The data from this website utilises information which is public and uses open-source technologies such as D3（Javascript library, Bootsrap, Python and Postgre SQL Open-source database to scrape the data

This dataset collects various data from each listing including Country, City, address, Host ID, Price, duration.


## 4. How does the method of collection impact the completeness and/or accuracy of the InsideAirbnb data set's representation of the process it seeks to study, and what wider issues does this raise?

Based on Q3 these process made it possible for Researchers to generally collect data directly from Airbnb, whom operates globally [].There are several discussions about the in accuracies of the inside Airbnb Data for instance a study by Prentice, C. and Pawlicz, A. (2024), suggest that webscraped data is nonetheless not free from errors or inaccuracies for a range of reasons. For instance, some tourists may use different distribution channels or book directly, while listings may be faked, duplicated, simply an inactive test or be booked occasionally (Adamiak, 2022). Moreover, the web scraping process may be constrained by the platform provider (Alsudais, 2021), while analytics provided by organizations may be inflated due to their innate business interest (Dolnicar, 2019). However, these constraints and limitations are rarely reported in academic publications. Despite these limitations, Inside Airbnb's data is widely used for research and advocacy purposes. It provides valuable insights into the impact of short-term rentals on housing markets and communities. However, researchers and data scientists should be aware of these limitations.

    1. Incomplete Listings: Not all Airbnb listings are publicly accessible, and some hosts may choose to keep their listings private, leading to gaps in the data.

    2. Data Quality: The accuracy of the data depends on the accuracy of the listings provided by hosts. Inaccurate or outdated information can skew the results.

    3. Bias: The data may be biased towards more popular or higher-rated listings, as these are more likely to be reviewed and updated frequently.

The wider issues raised by these limitations include the need for more comprehensive and accurate data collection methods, as well as the ethical considerations of using scraped data. Ensuring data quality and representativeness is crucial for making informed decisions and policies related to housing and tourism.

## 5. What ethical considerations does the use of the InsideAirbnb data raise?

The neutrality thesis claims that technological artifacts have no inherent values, politics, or consequences. technology is neither inherently good nor inherently bad. It is rather the human agency of those using the technology, which is responsible for the outcomes and consequently, for the technology’s social and political implications. In other words, according to the neutrality thesis, what matters is how we as individuals or as a society use technology (Pitt, 2014).

Looking at the morality of the usage of insideAirbnb data more broadly, decisions regarding technologies’ design, their use, and the contexts in which they are embedded can have not only ethical but also political consequences (Feenberg, 2002; Introna, 2007; Sclove, 1995; Winner, 1980).

Firstly, using InsideAirbnb data raises questions about who has the right to access and use the platform’s data. While the website collects data by scraping Airbnb's public information - a practice that violates Airbnb's terms of service (Stringam, Gerdes and Anderson, 2023), does so to enable important public interest research, such as reports to help us understand how short-term rentals affect our communities.

Secondly, there are significant privacy concerns. Although the information scraped is publicly visible on Airbnb's website, it contains personal details about hosts and guests through reviews and listings. When this data is collected and used for purposes beyond what users originally intended, it raises important privacy questions - even if the information was voluntarily shared on the platform.

Thirdly, there's the impact of commercial exploitation of this data. Companies use Inside Airbnb data to provide market analysis services, helping hosts optimize their pricing and operations (Scassa, 2019). While this creates new business opportunities, it could worsen housing affordability problems by making short-term rentals more profitable.


## With reference to the InsideAirbnb data (i.e. using numbers, figures, maps, and descriptive statistics), what does an analysis of Hosts and Listing types suggest about the nature of Airbnb lets in London?

### Airbnb: Moving Beyond Home Sharing? - Through Host Behavior and Categorization

The charts reveal Airbnb's shift from home-sharing to a commercialized short-term rental market. The proportion bar chart shows entire homes/apartments dominate (60%), while private rooms (35%) and shared/hotel rooms (5%) play minor roles, reflecting a professionalized market.

Superhost data highlights this further: Commercial and Mid-scale Hosts achieve higher Superhost proportions, indicating consistent, high-quality service tied to frequent bookings and professional management.

The availability boxplots show most listings are bookable for 90–270 days, suggesting hosts plan well in advance, typical of investment properties rather than casual home-sharing. Longer stays in entire homes target extended guests, while private/shared rooms focus on shorter durations due to space limitations. Combined, these insights point to Airbnb's evolution into a business-focused platform, prioritizing profitability over its original community-based concept.

### Airbnb: How are Listings spatially Distributed ?- Inner

The graph highlights a significant boom in Airbnb listings across Central London, particularly in areas such as Westminster, Camden, Lambeth, and Southwark. The data reveals that Airbnb listings have consistently increased over the years, with no borough showing negative growth during any of the observed time periods. This trend suggests that properties are continuously being converted into short-term Airbnb rentals, while the reverse — converting Airbnb listings back to long-term rentals — is virtually non-existent.

This surge in short-term rental listings has led to a concentration of Airbnb properties in Central London, creating a concerning trend. Property owners observing this market shift may increasingly feel incentivized to convert their properties to short-term rentals, drawn by the potential for higher revenue. Consequently, the supply of long-term rental properties decreases, while rents for the remaining long-term rentals rise due to the competitive rental market. This scenario places additional financial strain on tenants who may no longer afford rising rents, ultimately forcing them to move to outer boroughs. Over time, this dynamic contributes to gentrification in Central London, where affordability is drastically reduced, and lower-income residents are pushed out.

The data also shows emerging growth in Airbnb listings in outer boroughs such as Ealing, Barnet, and Croydon. This indicates a gradual outward expansion of the short-term rental market. As property owners in these areas recognize the revenue potential of Airbnb, they may also begin converting long-term rental properties into short-term rentals, exacerbating the issue further.

The proliferation of short-term rentals poses several challenges for communities:

    1. Housing Affordability: The increase in short-term rentals reduces the supply of long-term rental properties, driving up rents and making housing less affordable for local residents.

    2. Community Disruption: Short-term rentals typically lack long-term occupants, preventing the establishment of stable and cohesive communities. Areas dominated by short-term rentals often experience a floating population, undermining the sense of local identity which is important characterstic of for neighbourhoods.

## 7. Drawing on your previous answers, and supporting your response with evidence (e.g. figures, maps, EDA/ESDA, and simple statistical analysis/models drawing on experience from, e.g., CASA0007), how could the InsideAirbnb data set be used to inform the regulation of Short-Term Lets (STL) in London?

### Focus on Westminster

Westminster, being one of the most famous boroughs in London for its tourist attractions, hosts an overwhelming number of Airbnb listings — 9,504 in total. Analyzing the spatial distribution of these listings reveals four significant clusters that effectively span the entire borough. This clustering indicates that short-term rentals dominate Westminster's housing market, leaving little room for long-term rental stability.

Key Insights: 
    1. Presence of Duplicate Hosts: The data shows that within each cluster, there are numerous properties with duplicate host IDs. For instance, Cluster 3 alone has 415 properties managed by duplicate hosts. This trend suggests that property owners are capitalizing on Westminster's tourist market and its proximity to key services. Instead of renting properties for long-term use — which typically comes with more stable but lower revenue — hosts are converting multiple properties into short-term lets to maximize profits (even though risk is higher, but higher risk => higher reward).

    2. Decreased Housing Affordability: In Westminster and the neighboring districts, the practice of renting out several short-term properties has made housing affordability problems worse. Rents for the few long-term rental homes that are still available have increased, making them unaffordable for the typical renter, while long-term renting possibilities have declined. Short-term rental growth pushes lower-income tenants out of central neighborhoods, which fuels gentrification.

    3. Airbnb Hosts' as an "Occupation": Platforms like Airbnb were initially created as a side gig that let users rent out extra rooms or second residences. Nonetheless, in Westminster, professional property managers now rent several apartments all year round, making short-term rentals the main source of income for hosts. This change interferes with the development of long-term, stable communities in addition to decreasing the supply of affordable housing.

### Focus on Camden: How Professional Hosts Influence Local Neighbourhoods?

Camden, with its mix of residential neighborhoods and thriving commercial hubs, offers an ideal case study to explore the community-level impact of professional Airbnb hosts. The borough’s high concentration of short-term rentals (STRs), particularly entire properties [@doi:10.1177/0042098020970865], reflects its strong housing demand, cultural attractions, and economic activity.

Our analysis using reviews_per_month, a measure of property turnover, shows professional hosts dominate high-turnover areas like Camden Town and King’s Cross, which may reduce housing availability for long-term residents and increase pressure on the rental market [doi:10.1177/23998083211001836]. In contrast, non-professional hosts with single properties are more evenly distributed and play a more notable role in less commercial areas.

As shown in the POI count analysis, professional hosts are also clustered near key business amenities, particularly retail food establishments, and entertainment venues, indicating potential investment through visitor spending[@XU2021103670]. However, this economic benefit raises concerns about housing pressures, neighborhood stability, and cohesion.

As shown in the POI count analysis, professional hosts are also clustered near key business amenities, particularly retail food establishments, and entertainment venues, indicating potential investment through visitor spending[@XU2021103670]. However, this economic benefit raises concerns about housing pressures, neighborhood stability, and cohesion.

## Proposed Policy Recommendations

To regulate the impact of short-term rentals in high-density areas like Westminster, Camden, and other boroughs experiencing similar trends, we propose the following policy framework:

While outside the scope of this analysis, a more robust taxation system for short-term rentals could ensure these properties contribute fairly, which can be then used to improve the infrastructure or maybe even provide subsizdized housing or help tenants with their rents.

To regulate the impact of short-term rentals in high-density areas like Westminster, Camden, and other boroughs experiencing similar trends, we propose the following policy framework:

Firstly, the introduction of density caps this sets the maximum amount of Airbnb’s in a specific region. This is done when there are concerns regarding high concentration of STLs which then impact the availability and affordability of local rental (UK Government, 2024). Another suggestion is to ensure that properties rented as short-term lets must also be rented as long-term lets for at least double (double is an arbitrary number, it can be 1.5x, 1.75x, etc.) the number of short-term nights (e.g., 180 nights).

Strategic Short-Term Letting: By imposing such a cap, property owners would need to strategize when to list properties as short-term rentals (e.g., during peak tourist seasons like summer and winter breaks) while fulfilling their obligation to offer long-term rental options during off-seasons. This would strike a balance between tourism demand and housing stability.

Mandatory registration schemes give local councils the required information about STL in their boroughs. This is regulation is in place to “prevent a “hollowing out” of communities (UK Government, 2024). Finally, tiering tax policies by introducing higher tax rates for STR in areas that have more STL’s. This can be seen in Greece as they increased the tax on STR as of 2025 tax on STLs in the tourism season will increase 460% (Papadimas, 2024).[@vonbriel2021evolution]

Investment opportunities to support professional hosts The data shows that there are 2,264 hosts that have more than 5 listings. This suggests that there is an investment opportunity in place for these hosts to help manage these listings. There is the space to offer all in one service that include channel manager, which provides the ability to have bookings come in from multiple platforms, multi calendar which can help these multi hosts streamline bookings and automated tools for everyday tasks such as messaging the clients for updates and pricing requests. These tools and services are investment opportunity for these hosts as it provides efficiency and increased profitability.


