1.Obtain the elements of the union between two character vectors. vec1 = c(rownames(mtcars[1:15,])) vec2 = c(rownames(mtcars[10:32,]))

> vec1 = c(rownames(mtcars[1:15,]))
> vec2 = c(rownames(mtcars[10:32,]))
> union(vec1, vec2)
 [1] "Mazda RX4"           "Mazda RX4 Wag"       "Datsun 710"          "Hornet 4 Drive"     
 [5] "Hornet Sportabout"   "Valiant"             "Duster 360"          "Merc 240D"          
 [9] "Merc 230"            "Merc 280"            "Merc 280C"           "Merc 450SE"         
[13] "Merc 450SL"          "Merc 450SLC"         "Cadillac Fleetwood"  "Lincoln Continental"
[17] "Chrysler Imperial"   "Fiat 128"            "Honda Civic"         "Toyota Corolla"     
[21] "Toyota Corona"       "Dodge Challenger"    "AMC Javelin"         "Camaro Z28"         
[25] "Pontiac Firebird"    "Fiat X1-9"           "Porsche 914-2"       "Lotus Europa"       
[29] "Ford Pantera L"      "Ferrari Dino"        "Maserati Bora"       "Volvo 142E"

2. Get those elements that are common to both vectors. vec1 = c(rownames(mtcars[1:15,])) vec2 = c(rownames(mtcars[10:32,]))

> intersect(vec1, vec2)
[1] "Merc 280"           "Merc 280C"          "Merc 450SE"         "Merc 450SL"        
[5] "Merc 450SLC"        "Cadillac Fleetwood"


3. Get the difference of the elements between two character vectors. vec1 = c(rownames(mtcars[1:15,])) vec2 = c(rownames(mtcars[10:32,]))

> setdiff(vec1, vec2)
[1] "Mazda RX4"         "Mazda RX4 Wag"     "Datsun 710"        "Hornet 4 Drive"   
[5] "Hornet Sportabout" "Valiant"           "Duster 360"        "Merc 240D"        
[9] "Merc 230"
