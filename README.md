# Description of the dataset
Tinitaly DTM as Google Earth Engine image collection asset. 
Tinitaly Digital Terrain Model (DTM) is an Istituto Nazionale di Geofisica e Vulcanologia (INGV) product. It is an image collection of tiles of italian peninsula with a single band that corresponds to the (orthometric) elevation of bare ground. The spatial accuracy is 10m, projection is UTM WGS 84 zone 32 (EPSG: 32632). 
# Request of upload
The asset is available on my [Google Earth Engine project](https://code.earthengine.google.com/?asset=projects/ee-emanuelespiritowork/assets/Tinitaly_DTM). 
I suggested uploading as [official Earth Engine](https://issuetracker.google.com/issues/404066177) dataset and as a [Earth Engine Community](https://github.com/samapriya/awesome-gee-community-datasets/issues/339) dataset. 
# Earth Engine Community publication
The asset is now published in the [Earth Engine Community](https://gee-community-catalog.org/projects/tinitaly/?h=tinit) and can be added using the following snippet:
```r
var Tinitaly_DTM = ee.ImageCollection("projects/sat-io/open-datasets/Tinitaly_DTM");
print(Tinitaly_DTM);
```
# Italian nation shapefile
From the Tinitaly DTM I also extracted the italian nation shapefile, that is available on my [Google Earth Engine project](https://code.earthengine.google.com/?asset=projects/ee-emanuelespiritowork/assets/Italy_shapefile)
# License 
TINITALY 1.1 is published with a CC BY 4.0 license and can be used freely, even partly, but it must be cited as follows:
Tarquini S., I. Isola, M. Favalli, A. Battistini, G. Dotta, (2023). TINITALY, a digital elevation model of Italy with a 10 meters cell size (Version 1.1). Istituto Nazionale di Geofisica e Vulcanologia (INGV). https://doi.org/10.13127/tinitaly/1.1.
