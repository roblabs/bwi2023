# Good Maps come from Good Data

The raster data sources you can access *is* the quality of your map.

@Metadata {
    @PageImage(purpose: icon, source: "globe", alt: "")
    @TitleHeading("XYZ Tile Data")
}

## Overview

The color of the earth is much richer pallette of color vibrancy and description of a an area than what ever colors can possibly be chosen from the RGB color cube.  Some imagery is black and white which reflects the camera technology at the time an aerial survey was commissioned.  Modern aerial surveys vary with ambient weather, the angle of the sun, and literally an aerial device scanning over a perioud of time.

When you are building a map  from an aerial image you usually are happy to get what can.

@Links(visualStyle: compactGrid) {
    * <doc:Lebanon>
}

### Esri Data

- term World Imagery Wayback: a digital archive, providing users with access to the different versions of World Imagery created over time. Each layer in the archive represents a snapshot of the entire World Imagery map, as it existed on the date it was published.  

* [ESRI | World Imagery Wayback](livingatlas.arcgis.com/wayback)
* [Open source](https://github.com/vannizhang/wayback)
* [USGS Historical Topographic Map Explorer](https://livingatlas.arcgis.com/topoexplorer)

### Demo Baltimore

@TabNavigator {
    @Tab("Baltimore 16") {
        - term 16: Baltimore at zoom 16 with Camden Yards & FOSS4G Hotel.
        @Image(source: "wayback-imagery-animation-balto-16") { }
    }
    
    @Tab("Camden Yards 17") {
        - term 17: Camden Yards at zoom 17. 
        @Image(source: "wayback-imagery-animation-balto-17-Camden") { }
    }
    
    @Tab("Ravens Stadium 17") {
        - term 16: Ravens Stadium at zoom 17.
        @Image(source: "wayback-imagery-animation-balto-17-ravens") { }
    }
    
    @Tab("USGS Wayback") {
        - term 1896: 1:62,500 
        @Image(source: "historical-topographic-balto") { }
    }
}
