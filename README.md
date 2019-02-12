# delivery_area
Draw polygons as delivery area on GoogleMaps and save them.

## What are the materials ?
```
bootstrap v3 cdn
jquery cdn
font-awesome cdn
```


### Demo 
* [See Demo](http://enginpinar.com/delivery_area/) - http://enginpinar.com/delivery_area/


## Using

First Shape for demo. You can add an other shape with
```
Add New Sahpe
```

Deleting Method:

```
Find : /* Delete shape panel actions */
```

POST Methods:

```
POST Shape
Find: Delivery Zones POST ->
Example Shape data : {update_delivery_zones:1,shapes:allShapes,datas:allShapes_datas}

POST Status
Find: Zone Status POST ->
Example Status data: {update_delivery_zone_status:1, zone_no: zone_no, status: thisInput.val()}
```


Start Point
```
map = new google.maps.Map(document.getElementById('map'), {
  ...
  center : Lat, Lng,
}
```

That's for software of online ordering, [RestApp.com](https://www.restapp.com). Draw your delivery zones, add parameters and use it.

Examples Live:
```
https://my.restapp.com/teras-restaurant/delivery_areas
```

Happy Coding !
