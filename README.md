#Data information#

city_boundary_shapefiles: Provides urban boundary vector data for 3,280 cities as of 2018. The original data is sourced from the global urban boundary dataset.

--------------------------------------------------------------------------------------------------------------------

city_dataset: This dataset provides key metrics for global cities, including urban heat island (UHI) intensity, vegetation coverage index (EVI), and albedo intensity during cold and warm seasons. It also details the cooling effects of five different vegetation and albedo adjustment strategies with varying intensities.

The table columns are described as follows:

CityID: Unique identifier for each city, corresponding to the GUB data ID.
urbanArea: Area of the urban region (unit: km2), as provided by the GUB data.
X_1/Y_1: Core latitude and longitude coordinates of the city.
UHI_intensity_heat/UHI_intensity_cold: UHI intensity values for the warm and cold seasons, respectively (unit:  °C).
EVI_value_heat/EVI_value_cold: EVI values for the warm and cold seasons, respectively.
albedo_value_heat/albedo_value_cold: Albedo intensity values for the warm and cold seasons, respectively.


"EVI_CE_inten1_heat
EVI_CE_inten2_heat
EVI_CE_inten3_heat
EVI_CE_inten4_heat
EVI_CE_inten5_heat": Indicates the cooling intensity (in °C) of five vegetation cooling strategies, ranging from low to high regulation intensity, during the warm season.

"EVI_CE_inten1_cold
EVI_CE_inten2_cold
EVI_CE_inten3_cold
EVI_CE_inten4_cold
EVI_CE_inten5_cold": Indicates the cooling intensity (in °C) of five vegetation cooling strategies, ranging from low to high regulation intensity, during the cold season.

"albedo_CE_inten1_heat
albedo_CE_inten2_heat
albedo_CE_inten3_heat
albedo_CE_inten4_heat
albedo_CE_inten5_heat": Indicates the cooling intensity (in °C) of five albedo cooling strategies, ranging from low to high regulation intensity, during the warm season.

"albedo_CE_inten1_cold
albedo_CE_inten2_cold
albedo_CE_inten3_cold
albedo_CE_inten4_cold
albedo_CE_inten5_cold": Indicates the cooling intensity (in °C) of five albedo cooling strategies, ranging from low to high regulation intensity, during the cold season.

GID_0: Abbreviated name of the country to which the city belongs.
Country_Name: Full name of the country to which the city belongs.

--------------------------------------------------------------------------------------------------------------------

urban_heat_mortality: This dataset presents estimates of the Minimum Mortality Temperature (MMT) and temperature-related mortality across four temperature percentiles. The temperature-related mortality reflects the proportion of deaths attributable to non-optimal temperatures among all-cause deaths in the population. The table also provides the effects of the UHI phenomenon and various vegetation and albedo cooling strategies on heat-related, cold-related, and annual mortality. These values represent cumulative outcomes derived from daily analyses.

The table columns are described as follows:

CityID: Represents the city's identification number, corresponding to the GUB data ID.
X/Y: Denotes the city's core latitude and longitude coordinates.
MMT: Indicates the city's Minimum Mortality Temperature, i.e., optimal temperature (unit: °C).
MMP: Represents the temperature percentile of the city's MMT within the annual daily temperature range (unit: %).
0_5: Shows induced mortality within the daily temperature percentile range of 0–5% for the city.
5_mmp: Displays induced mortality within the daily temperature percentile range of 5%–MMP for the city.
MMP_95: Indicates induced mortality within the daily temperature percentile range of MMP–95% for the city.
95_100%: Represents induced mortality within the daily temperature percentile range of 95%–100% for the city.
heat_UHI / cold_UHI / annual_UHI: Reflects the impact of the UHI effect on heat-related, cold-related, and annual net mortality, respectively.
heat_EVI / cold_EVI / annual_EVI: Represents the impact of vegetation cooling strategies (at the highest adjustment intensity among five levels) on heat-related, cold-related, and annual net mortality, respectively.
heat_albedo / cold_albedo / annual_albedo: Indicates the impact of albedo cooling strategies (at the highest adjustment intensity among five levels) on heat-related, cold-related, and annual net mortality, respectively.


"futureheat_albedo1
futureheat_albedo2
futureheat_albedo3
futureheat_albedo4
futureheat_albedo5": Represents the impact of five albedo cooling strategies, ranging from low to high adjustment intensity, on future heat-related mortality.

"futureheat_EVI1
futureheat_EVI2
futureheat_EVI3
futureheat_EVI4
futureheat_EVI5": Represents the impact of five vegetation cooling strategies, ranging from low to high adjustment intensity, on future heat-related mortality.

"futurecold_albedo1
futurecold_albedo2
futurecold_albedo3
futurecold_albedo4
futurecold_albedo5": Represents the impact of five albedo cooling strategies, ranging from low to high adjustment intensity, on future cold-related mortality.

"futurecold_EVI1
futurecold_EVI2
futurecold_EVI3
futurecold_EVI4
futurecold_EVI5": Represents the impact of five vegetation cooling strategies, ranging from low to high adjustment intensity, on future cold-related mortality.

"futureannual_albedo1
futureannual_albedo2
futureannual_albedo3
futureannual_albedo4
futureannual_albedo5": Represents the impact of five albedo cooling strategies, ranging from low to high adjustment intensity, on future annual net mortality.

"futureannual_EVI1
futureannual_EVI2
futureannual_EVI3
futureannual_EVI4
futureannual_EVI5":Represents the impact of five vegetation cooling strategies, ranging from low to high adjustment intensity, on future annual net mortality.

"futureannual_seasonal_albedo1
futureannual_seasonal_albedo2
futureannual_seasonal_albedo3
futureannual_seasonal_albedo4
futureannual_seasonal_albedo5": Represents the impact of five seasonal albedo cooling strategies, with adjustment intensity from low to high, on future annual net mortality. This uses a seasonal adjustment approach for the albedo cooling strategies;  In this modified strategy, surface albedo was increased with different intensity strategies during warm seasons, and then decreased during cold seasons.

--------------------------------------------------------------------------------------------------------------------

temperature-related mortality estimation.txt: Offers estimation framework for estimating mortality (or MMT) at each temperature percentile interval.

--------------------------------------------------------------------------------------------------------------------

cooling effect correction.txt:  Contains the correction model for slope values in the linear relationship between vegetation (or albedo) and air temperature. The slope values are then used to assess the cooling intensity of specific vegetation or albedo regulation strategies.




