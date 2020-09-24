Figure 1: 
Latitudinal distributions of cloud occurrence were plotted using the arrays "Figure1_2BCL5_ice", "Figure1_2BCL5_mixed", and "Figure1_2BCL5_water" across the grid given by the "Figure1_contour_height" and "Figure1_contour_lat" arrays.

Temperature isotherms were plotted using the "Figure1_contour_temperature" array across the grid given by the "Figure1_contour_temp_height" and "Figure1_contour_temp_latitude" arrays

Figure 2:
Differences in the latitudinal distributions of cloud occurrence between 2BCL5 and DARDAR can be plotted by subtracting the arrays used in Figure 1 from the "Figure2_DARDAR_ice", "Figure2_DARDAR_mixed" and "Figure2_DARDAR_water" arrays over the same grid. Temperature isotherms were plotted as in Figure 1.

Figure 3:
Mean vertical profiles of cloud occurrence for different cloud phases can be plotted using the "Figure3_2BCL5", "Figure3_2BCL5" and "Figure3_2BCL5" arrays. These arrays are of the shape (4,3,2667) where the first dimension gives the month (Jan, Oct, Nov, Dec) the second gives the phase (Liquid, Mixed, Ice for 2BCL5/DARDAR and Liquid, Ice, Total for AWARE), and the third gives the altitude which can be plotted using the "Figure3_altitude" array. The mean and max levels of the -38 degree isotherm can be plotted from the "Figure3_isotherm_levels" array. This array has the shape (2,4) where the first dimension gives the type (mean,max) and the second gives the month (Jan, Oct, Nov, Dec).

Figure 4:
Detection frequency as a function of altitude can be plotted using the "Figure4_panel" array for panels a,b,d,e,g,h panels c,f,i can be plotted by taking the difference between given arrays. Altitude is plotted using the array "Figure4_altitude".

Figure 5:
The ratio between satellite and ground–based cloud occurrence at different altitudes is plotted using the "Figure5_2BCL5_AWARE_ratio", "Figure5_2BCL5_DARDAR_ratio" and "Figure5_DARDAR_AWARE_ratio" arrays, with the medians gives by the "Figure5_2BCL5_AWARE_median", "Figure5_2BCL5_DARDAR_median" and "Figure5_DARDAR_AWARE_median" arrays. The arrays "Figure5_ratio_xaxis" and "Figure5_altitude" give the grid for plotting.

Figure 6:
The statistics can be plotted using the files "Figure7_2BCL5_stats" and "Figure7_2BCL5_stats". Arrays are of the shape (10,4) where the first dimension gives the altitude bins from 0 to 10 km and the second dimension gives the statistics of the form (t-value, p-value for the t-test, K-S value, p-value for the K-S test)

Figure 7:
Normalised cloud occurrences as a function of temperature can be plotted for 2BCL5, DARDAR and AWARE for the different phases (Ice, Mixed and Liquid for 2BCL5/DARDAR, Ice, Liquid and Unknown for AWARE), where "ECMWF" and "Radiosonde" is used to distinguish between the temprature datasets. "Figure7_temperatures" gives the temperatures across the x-axis values.

