# northeast_mid_atlantic_us_ep_seasons
A collection of scripts used to analyze the days that produce the most extreme precipitation in each season over the mid-Atlantic and Northeast United States

Script names and functions are listed below *in order*.  

#ar_detection# - detects ARs based on criteria outlined in paper  
ar_precip_sensitivity - determines sensitivity of various precipitation metrics to AR closeness  
tc_precip_sensitivity - determines sensitivity of various precipitation metrics to TC closeness  

station_extreme_precip_overview_geotrends - plots trends in season total 95th percentile precipitation at each station in each season  
station_extreme_precip_line_plots - plots time series of spatially-averaged seasonal amount of top 95% precipitation (with trend significance information)  

station_precip_wtype_classifications - classified each precipitation observation at each station into one of 11 weather types  
station_extreme_precip_wtype_geotrends - plots trends in season total 95th percentile precipitation at each station in each season for various weather types  

ep_days_define - choose stations with 95% completeness; define EP days for a range of threshold combinations  
ep_day_definition_testing - assessed means and trends for the sets of EP days defined in the previous script; plots tables with this information.  
ep_days_line_plots - display seasonal frequency and individual precipitation of EP days  
ep_days_bar_plots - plot seasonal frequency and cumulative precipitation from different types of EP days in different seasons  
ep_days_geoplots - plot mean daily precipitation and seasonal cumulative precipitation trends for different types of EP days in different seasons  

ep_day_classifications - sorts days according to which weather type produces the most extreme precipitation  
ep_day_classification_completeness_check - checks to make sure that all dates are accounted for and gets rid of overlaps (overlaps occur on days with little precipitation when two or more types have the same total extreme precipitation; this does NOT occur on EP days and was retained only for the case of a complete climatology of all days)  
binary_convert - converts the dates of EP days in each weather type to binary lists representing truth values for each weather type  

ep_day_composites - makes synoptic composites of EP days.  Shows 1000-500 hPa thickness (dashed contours), MSLP (solid contours), IVT above 250 kg m-1 s-1 (grey shading), and detected ARs (blue fill over IVT).  
ep_day_composite_trends - plots trends in atmospheric variables on EP days (independent of EP day frequency).  Trends are shown in: 1000-500 hPa thickness, MSLP, IVT, and AR detection (significance specified for all but the AR detection trend).    

maps_plot - plots detailed synoptic maps of all EP days, along with day classifications and station precipitation classifications. Shows 1000-500 hPa thickness (dashed contours), MSLP (solid contours), IVT above 250 kg m-1 s-1 (grey shading), detected ARs (blue fill over IVT), tropical (red stars) and non-tropical (brown stars) IBTrACS systems, station precipitation classified by weather type (colored dots), and day classification based on which type produces the most station extreme precipitation (upper left).  

(no specific order) seasonal_climatology_trends - plots means and trends of MSLP and IVT for each season as a whole (not just EP days)  
