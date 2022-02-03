# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json
  ?destination=place_id:ChIJzdqWrfHZ1IkR2LWLAmB6GZ4
  &mode=transit
  &duration_in_traffic:optimistic
  &avoid=highways
  &departure_time:2022-03-02T21:30z
  &origin=place_id:ChIJDS05ZYDQ1IkRWB3t2c92nUU
  &key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJDS05ZYDQ1IkRWB3t2c92nUU",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJzdqWrfHZ1IkR2LWLAmB6GZ4",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction", "zoo" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.8229049,
               "lng" : -79.163399
            },
            "southwest" : {
               "lat" : 43.7758741,
               "lng" : -79.20515829999999
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "arrival_time" : {
                  "text" : "11:18am",
                  "time_zone" : "America/Toronto",
                  "value" : 1643905118
               },
               "departure_time" : {
                  "text" : "10:24am",
                  "time_zone" : "America/Toronto",
                  "value" : 1643901884
               },
               "distance" : {
                  "text" : "8.7 km",
                  "value" : 8724
               },
               "duration" : {
                  "text" : "54 mins",
                  "value" : 3234
               },
               "end_address" : "2000 Meadowvale Rd, Toronto, ON M1B 5K7, Canada",
               "end_location" : {
                  "lat" : 43.8204569,
                  "lng" : -79.1815957
               },
               "start_address" : "Morningside Park, 390 Morningside Ave, Scarborough, ON M1E, Canada",
               "start_location" : {
                  "lat" : 43.7758741,
                  "lng" : -79.2018569
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 867
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 799
                     },
                     "end_location" : {
                        "lat" : 43.7824776,
                        "lng" : -79.2049906
                     },
                     "html_instructions" : "Walk to Ellesmere Rd at Neilson Rd",
                     "polyline" : {
                        "points" : "e~djGrblbNCAIAGAO?M?IAG?C@E@CBA@EDILMLEDE@E?G@M?M?E?CACACACCCEGKEKEICCACA?AAA?A?C?GHMFQJSJSHMFm@RJn@KXEFGHEFCHADCD?DAD?D?B@H@F?@?HADAFAFEFA@CFEFGDGDA?E@G@E@GDEBG@G?G?E?GAGCCAECECGGCAA?A?A?C?A?A?A@A?A?IB]JAI_@N_@NSHMFOD}Af@s@Tu@V]LC@a@P[HSHQD[LkA`@QLIBaA\\MDo@T"
                     },
                     "start_location" : {
                        "lat" : 43.7758741,
                        "lng" : -79.2018569
                     },
                     "steps" : [
                        {
                           "distance" : {
                              "text" : "0.2 km",
                              "value" : 230
                           },
                           "duration" : {
                              "text" : "3 mins",
                              "value" : 176
                           },
                           "end_location" : {
                              "lat" : 43.7777365,
                              "lng" : -79.2021898
                           },
                           "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e",
                           "polyline" : {
                              "points" : "e~djGrblbNCAIAGAO?M?IAG?C@E@CBA@EDILMLEDE@E?G@M?M?E?CACACACCCEGKEKEICCACA?AAA?A?C?GHMFQJSJSHMFm@R"
                           },
                           "start_location" : {
                              "lat" : 43.7758741,
                              "lng" : -79.2018569
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "22 m",
                              "value" : 22
                           },
                           "duration" : {
                              "text" : "1 min",
                              "value" : 16
                           },
                           "end_location" : {
                              "lat" : 43.7776789,
                              "lng" : -79.2024253
                           },
                           "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                           "maneuver" : "turn-left",
                           "polyline" : {
                              "points" : "{iejGtdlbNJn@"
                           },
                           "start_location" : {
                              "lat" : 43.7777365,
                              "lng" : -79.2021898
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "0.2 km",
                              "value" : 192
                           },
                           "duration" : {
                              "text" : "5 mins",
                              "value" : 273
                           },
                           "end_location" : {
                              "lat" : 43.778927,
                              "lng" : -79.20341259999999
                           },
                           "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eTake the stairs\u003c/div\u003e",
                           "maneuver" : "turn-right",
                           "polyline" : {
                              "points" : "oiejGdflbNKXEFGHEFCHADCD?DAD?D?B@H@F?@?HADAFAFEFA@CFEFGDGDA?E@G@E@GDEBG@G?G?E?GAGCCAECECGGCAA?A?A?C?A?A?A@A?A?IB]J"
                           },
                           "start_location" : {
                              "lat" : 43.7776789,
                              "lng" : -79.2024253
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "8 m",
                              "value" : 8
                           },
                           "duration" : {
                              "text" : "1 min",
                              "value" : 6
                           },
                           "end_location" : {
                              "lat" : 43.778939,
                              "lng" : -79.203363
                           },
                           "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eNeilson Rd\u003c/b\u003e",
                           "maneuver" : "turn-right",
                           "polyline" : {
                              "points" : "iqejGhllbNAI"
                           },
                           "start_location" : {
                              "lat" : 43.778927,
                              "lng" : -79.20341259999999
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "0.4 km",
                              "value" : 415
                           },
                           "duration" : {
                              "text" : "5 mins",
                              "value" : 328
                           },
                           "end_location" : {
                              "lat" : 43.7824776,
                              "lng" : -79.2049906
                           },
                           "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eNeilson Rd\u003c/b\u003e",
                           "maneuver" : "turn-left",
                           "polyline" : {
                              "points" : "kqejG~klbN_@N_@NSHMFOD}Af@s@Tu@V]LC@a@P[HSHQD[LkA`@QLIBaA\\MDo@T"
                           },
                           "start_location" : {
                              "lat" : 43.778939,
                              "lng" : -79.203363
                           },
                           "travel_mode" : "WALKING"
                        }
                     ],
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.5 km",
                        "value" : 3520
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 503
                     },
                     "end_location" : {
                        "lat" : 43.792313,
                        "lng" : -79.16384099999999
                     },
                     "html_instructions" : "Bus towards York Mills to Port Union",
                     "polyline" : {
                        "points" : "ggfjGxvlbN[LGe@Kq@CMKw@AIGa@E]Km@c@wCQkAAIiA_IM_AEWWeBKu@AIGa@Ik@COCSs@}EQoAk@yDSwAe@yCG[QoA[qBUqACIAGBK?C?CCYEs@EYI_@CQAKAG?AAGAC?AAA?CAAAAIIc@wCG_@AIAMAICMCOCMMu@Ii@m@qDKm@EYGYEYQmAKo@OaAAEE[G[OaAw@yEWyAaAiGUsAOaAMq@ESMy@O}@M_ASyAAIAKIi@E[OaACO]gCMu@Ge@SwACWEW]{B_@kC_@kCKy@Kw@U_Bg@kDM}@c@uCGc@Mw@Ge@WkBKs@Ik@Iq@Ie@CSEYCOEQAKCOKo@YeBm@_EGc@O}@YmBc@uCQkAW_BIg@g@eDAGAQU_BCOCMy@iFIc@OgASqARI"
                     },
                     "start_location" : {
                        "lat" : 43.78244,
                        "lng" : -79.20509299999999
                     },
                     "transit_details" : {
                        "arrival_stop" : {
                           "location" : {
                              "lat" : 43.792313,
                              "lng" : -79.16384099999999
                           },
                           "name" : "Ellesmere Rd at Meadowvale Rd"
                        },
                        "arrival_time" : {
                           "text" : "10:45am",
                           "time_zone" : "America/Toronto",
                           "value" : 1643903105
                        },
                        "departure_stop" : {
                           "location" : {
                              "lat" : 43.78244,
                              "lng" : -79.20509299999999
                           },
                           "name" : "Ellesmere Rd at Neilson Rd"
                        },
                        "departure_time" : {
                           "text" : "10:38am",
                           "time_zone" : "America/Toronto",
                           "value" : 1643902683
                        },
                        "headsign" : "York Mills to Port Union",
                        "line" : {
                           "agencies" : [
                              {
                                 "name" : "TTC",
                                 "phone" : "1 (416) 393-4636",
                                 "url" : "https://www.ttc.ca/"
                              }
                           ],
                           "color" : "#ffffff",
                           "name" : "York Mills",
                           "short_name" : "95A",
                           "text_color" : "#ed3237",
                           "vehicle" : {
                              "icon" : "//maps.gstatic.com/mapfiles/transit/iw2/6/bus2.png",
                              "name" : "Bus",
                              "type" : "BUS"
                           }
                        },
                        "num_stops" : 10
                     },
                     "travel_mode" : "TRANSIT"
                  },
                  {
                     "distance" : {
                        "text" : "42 m",
                        "value" : 42
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 43.7922839,
                        "lng" : -79.16379529999999
                     },
                     "html_instructions" : "Walk to Meadowvale Rd at Ellesmere Rd",
                     "polyline" : {
                        "points" : "wdhjGztdbN?C"
                     },
                     "start_location" : {
                        "lat" : 43.7922769,
                        "lng" : -79.16382419999999
                     },
                     "steps" : [
                        {
                           "distance" : {
                              "text" : "25 m",
                              "value" : 25
                           },
                           "duration" : {
                              "text" : "1 min",
                              "value" : 19
                           },
                           "end_location" : {
                              "lat" : 43.7922839,
                              "lng" : -79.16379529999999
                           },
                           "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eEllesmere Rd\u003c/b\u003e toward \u003cb\u003eMeadowvale Rd\u003c/b\u003e",
                           "polyline" : {
                              "points" : "wdhjGztdbN?C"
                           },
                           "start_location" : {
                              "lat" : 43.7922769,
                              "lng" : -79.16382419999999
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "17 m",
                              "value" : 17
                           },
                           "duration" : {
                              "text" : "1 min",
                              "value" : 21
                           },
                           "end_location" : {
                              "lat" : 43.7922839,
                              "lng" : -79.16379529999999
                           },
                           "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMeadowvale Rd\u003c/b\u003e",
                           "maneuver" : "turn-right",
                           "polyline" : {
                              "points" : "wdhjGvtdbN"
                           },
                           "start_location" : {
                              "lat" : 43.7922839,
                              "lng" : -79.16379529999999
                           },
                           "travel_mode" : "WALKING"
                        }
                     ],
                     "travel_mode" : "WALKING"
                  },
                  {
                     "distance" : {
                        "text" : "3.0 km",
                        "value" : 3050
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 418
                     },
                     "end_location" : {
                        "lat" : 43.818115,
                        "lng" : -79.17319499999999
                     },
                     "html_instructions" : "Bus towards Scarborough to Toronto Zoo",
                     "polyline" : {
                        "points" : "gehjGfrdbNB\\]FwAXOBiAVo@P[JmE|AkA`@oBr@WHEBWJm@JwAX{AVUD{@RQCKAO@mBd@WFsAb@u@Ts@VGFWJUFMD_@LIBu@Vu@Xo@TA?MFQHIBWJMDu@\\a@Ps@\\iAj@_@RWLGD]R}@d@EBWJGDMVo@^A@eAb@o@R]L[L_A\\e@PgBr@oBp@]L]Lc@Pm@VYLy@\\u@\\C@e@RIBUHOFUFYLc@PQFSFUH[LQFc@RODSJe@ZOJIDIHGFURA@q@p@IH_@^A?QRa@`@IFUTOLUROLKHGDKFGDEBGDEBA?C@EBIDIBC@IBEBGBKBG@IBI@KBK@KBK@K@M?I@E?E?G?E?I?E?IAE?IAI?SCC?MAKAIAA?IAKAIAA?MCOASCIAMAIAQCOAIAMAMAKCIAKAUCc@E_@EUCKAIAIAGAMAE?EAA?GAIAG?GAG?SCMQECGEEACAGAOAUCC?IAMAIAE?SCQ?CAK?C?IAE?M?I?I@I?E?K@A?C?G?G@I@E?IBG?OBIBE?A@e@HODUHE@QH[LUJ[P_@TIFGBEDKHEBEK"
                     },
                     "start_location" : {
                        "lat" : 43.792362,
                        "lng" : -79.163399
                     },
                     "transit_details" : {
                        "arrival_stop" : {
                           "location" : {
                              "lat" : 43.818115,
                              "lng" : -79.17319499999999
                           },
                           "name" : "Meadowvale Rd at Zoo Rd"
                        },
                        "arrival_time" : {
                           "text" : "11:03am",
                           "time_zone" : "America/Toronto",
                           "value" : 1643904192
                        },
                        "departure_stop" : {
                           "location" : {
                              "lat" : 43.792362,
                              "lng" : -79.163399
                           },
                           "name" : "Meadowvale Rd at Ellesmere Rd"
                        },
                        "departure_time" : {
                           "text" : "10:56am",
                           "time_zone" : "America/Toronto",
                           "value" : 1643903774
                        },
                        "headsign" : "Scarborough to Toronto Zoo",
                        "line" : {
                           "agencies" : [
                              {
                                 "name" : "TTC",
                                 "phone" : "1 (416) 393-4636",
                                 "url" : "https://www.ttc.ca/"
                              }
                           ],
                           "color" : "#ffffff",
                           "name" : "Scarborough",
                           "short_name" : "86A",
                           "text_color" : "#ed3237",
                           "vehicle" : {
                              "icon" : "//maps.gstatic.com/mapfiles/transit/iw2/6/bus2.png",
                              "name" : "Bus",
                              "type" : "BUS"
                           }
                        },
                        "num_stops" : 7
                     },
                     "travel_mode" : "TRANSIT"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1245
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 926
                     },
                     "end_location" : {
                        "lat" : 43.8204569,
                        "lng" : -79.1815957
                     },
                     "html_instructions" : "Walk to 2000 Meadowvale Rd, Toronto, ON M1B 5K7, Canada",
                     "polyline" : {
                        "points" : "qfmjGpofbN?H?V?b@?xA?J?N?`@?|@BV?DAv@?~@C^?BIXHT?LANAFALAJCNCJYSGEIKGKEGKIQGYIQGKGEAC?A?A?A@EBGBa@RWL[Lm@VA?OHQHA@MFOH[Rc@XULQH[Lg@RYLaA^c@Pa@Nc@ROHOF]LSHSJA@C@C?A?A?C?A?AAECQKAACAA?[PDNDHPXLVt@rAR\\RZz@zAPZHNDHHJdAjBJPDHDDDDDBB@D@B@D?DALKH?B?ZGDRBF@B@@B@@BLHJJJt@Bd@?BHfBGBABA@?BAB"
                     },
                     "start_location" : {
                        "lat" : 43.8181743,
                        "lng" : -79.1732081
                     },
                     "steps" : [
                        {
                           "distance" : {
                              "text" : "0.2 km",
                              "value" : 242
                           },
                           "duration" : {
                              "text" : "3 mins",
                              "value" : 191
                           },
                           "end_location" : {
                              "lat" : 43.8183899,
                              "lng" : -79.17616289999999
                           },
                           "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eZoo Rd\u003c/b\u003e",
                           "polyline" : {
                              "points" : "qfmjGpofbN?H?V?b@?xA?J?N?`@?|@BV?DAv@?~@C^?BIXHT?LANAFALAJCNCJYS"
                           },
                           "start_location" : {
                              "lat" : 43.8181743,
                              "lng" : -79.1732081
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "0.5 km",
                              "value" : 545
                           },
                           "duration" : {
                              "text" : "7 mins",
                              "value" : 406
                           },
                           "end_location" : {
                              "lat" : 43.8229049,
                              "lng" : -79.1776445
                           },
                           "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                           "maneuver" : "turn-right",
                           "polyline" : {
                              "points" : "}gmjG~agbNGEIKGKEGKIQGYIQGKGEAC?A?A?A@EBGBa@RWL[Lm@VA?OHQHA@MFOH[Rc@XULQH[Lg@RYLaA^c@Pa@Nc@ROHOF]LSHSJA@C@C?A?A?C?A?AAECQKAACAA?[P"
                           },
                           "start_location" : {
                              "lat" : 43.8183899,
                              "lng" : -79.17616289999999
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "0.3 km",
                              "value" : 329
                           },
                           "duration" : {
                              "text" : "4 mins",
                              "value" : 233
                           },
                           "end_location" : {
                              "lat" : 43.8207483,
                              "lng" : -79.18020229999999
                           },
                           "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eZoo Rd\u003c/b\u003e",
                           "maneuver" : "turn-left",
                           "polyline" : {
                              "points" : "cdnjGfkgbNDNDHPXLVt@rAR\\RZz@zAPZHNDHHJdAjBJPDHDDDDDBB@D@B@D?DALKH?B?ZG"
                           },
                           "start_location" : {
                              "lat" : 43.8229049,
                              "lng" : -79.1776445
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "0.1 km",
                              "value" : 118
                           },
                           "duration" : {
                              "text" : "1 min",
                              "value" : 88
                           },
                           "end_location" : {
                              "lat" : 43.8203913,
                              "lng" : -79.1815057
                           },
                           "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eZoo Rd\u003c/b\u003e",
                           "maneuver" : "turn-right",
                           "polyline" : {
                              "points" : "uvmjGf{gbNDRBF@B@@B@@BLHJJJt@Bd@?BHfB"
                           },
                           "start_location" : {
                              "lat" : 43.8207483,
                              "lng" : -79.18020229999999
                           },
                           "travel_mode" : "WALKING"
                        },
                        {
                           "distance" : {
                              "text" : "11 m",
                              "value" : 11
                           },
                           "duration" : {
                              "text" : "1 min",
                              "value" : 8
                           },
                           "end_location" : {
                              "lat" : 43.8204569,
                              "lng" : -79.1815957
                           },
                           "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                           "maneuver" : "turn-right",
                           "polyline" : {
                              "points" : "mtmjGlchbNGBABA@?BAB"
                           },
                           "start_location" : {
                              "lat" : 43.8203913,
                              "lng" : -79.1815057
                           },
                           "travel_mode" : "WALKING"
                        }
                     ],
                     "travel_mode" : "WALKING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "e~djGrblbNMCWAc@?QLWZKFi@@QEUa@MQIAUPe@Va@Pm@RJn@Q`@MPIZ?X?XKXINOJUD]J]EWQGAYD]JAI_A^oC~@kC|@cBj@gBn@[PoAb@o@TFR[LGe@O_A[aCyDyWmB_NmBgMgA}G@[ImAOy@Gg@CMEIIIc@wCIi@Ku@iA_HoAaIuEmYq@}De@oDkBsMuCuSoEa[mDkUyBcOwAcJSqARIDC?COoAB\\uB`@yAZkA\\aL|D]NeCd@qB\\{@RQC[?eCl@iCx@{@^{Af@qE`B}B`AuDjBiBbA_@PMVo@^gAd@mA`@iFpBoE~AwD`BmDrAwAf@yAl@_Al@i@f@qDnDaAx@a@Vq@ZkAZmAJ}@CqAKiEe@yEe@OASCMQMIICq@Ga@EoAGcABkAN}@PiAb@{Az@_@VEKIB?`@?xCB|BAvBCb@IXHTA\\Ip@CJYSQQMS]Q}@[I@cDxAq@\\gBdA_DnAeA`@s@\\uAj@KBG?[SEA[PDNVb@bAjBtBpD~ApC\\f@RHJALKH?^GHZHJXTNzAHjBIFCH"
         },
         "summary" : "",
         "warnings" : [
            "Walking directions are in beta. Use caution – This route may be missing sidewalks or pedestrian paths."
         ],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
