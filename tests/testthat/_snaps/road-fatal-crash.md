# test that the fatal crash dimensions are stable

    Code
      dim(dat_road_fatal_crash)
    Output
      [1] 49903    14

# test names of fatal crash are the same

    Code
      names(dat_road_fatal_crash)
    Output
       [1] "crash_id"          "n_fatalities"      "month"            
       [4] "year"              "weekday"           "time"             
       [7] "state"             "crash_type"        "bus"              
      [10] "heavy_rigid_truck" "articulated_truck" "speed_limit"      
      [13] "date"              "date_time"        

# Data frame has correct column classes

    Code
      classes(dat_road_fatal_crash)
    Output
               crash_id      n_fatalities             month              year 
              "numeric"         "numeric"         "numeric"         "numeric" 
                weekday              time             state        crash_type 
            "character"    "hms/difftime"       "character"       "character" 
                    bus heavy_rigid_truck articulated_truck       speed_limit 
            "character"       "character"       "character"         "numeric" 
                   date         date_time 
                 "Date"  "POSIXct/POSIXt" 

