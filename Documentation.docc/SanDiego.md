# San Diego

Introduction comparison of raster tiles for San Diego at zoom 9.

@Metadata {
    @Available("GeoJSON.io", introduced: "")
    @Available("Mapbox", introduced: "")
    @Available("MapLibre", introduced: "")
    @Available("MapKit", introduced: "")

    @PageImage(purpose: icon, source: "512.jpeg", alt: "")
    @TitleHeading("XYZ Tile Data")
}

### Demo

@TabNavigator {
    @Tab("OpenStreetMap") {
        - term ZXY: `z/x/y` = `9/89/206`
        ![](OSM-206)
    }
    
    @Tab("256x256") {
        - term ZXY: `z/x/y` = `9/89/206`
        ![](256)
    }
    
    @Tab("512x512") {
        - term ZXY: `z/x/y` = `9/89/206`
        ![](512.jpeg)
    }
    
    @Tab("MapKit") {
        - term ZXY: `z/x/y` = `9/89/206`
        ![](MapKit-9-206)
    }
    
    @Tab("USDA NAIP") {
        - term ZYX: `z/y/x` = `9/206/89`
        ![](USDA_CONUS_PRIME-89)
    }
    
    @Tab("Esri World Imagery") {
        - term ZYX: `z/y/x` = `9/206/89`
        ![](World_Imagery-89)
    }
}
