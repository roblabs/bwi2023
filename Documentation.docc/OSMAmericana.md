# Good Maps come from Open Source Projects

@Metadata {
    @Available("MapLibreJS", introduced: "")
    @PageImage(purpose: icon, source: "map", alt: "")
    @TitleHeading("")
}

Experiments with the OSM Americana style with raster base maps.

## Swift Playgrounds

macOS users can explore MapLibre without requiring to build from source nor have an app to test styles.

* See <https://github.com/maplibre/maplibre-gl-native-distribution> and run the Swift Playground from macOS.

![](OSM-Swift-Playground)


## Demo OSM Americana

<http://zelonewolf.github.io/openstreetmap-americana/#map=10/32.716744/-117.162942&language=en>

The OSM Americana hosts their style at https://zelonewolf.github.io/openstreetmap-americana/style.json

@TabNavigator {
    @Tab("OSM Americana") {
        - term Web:  This is a Web first map; the shields and labels come in via JavaScript.
        ![](OSM-A-0)
    }
    
    @Tab("OSM Test on MapLibre Mobile") {
        - term MapLibre Mobile rendering: This has no labels.  Meaning the OSM American style only has vector styling, but limited labels and shields.
        ![](OSM-A-1)
    }

    @Tab("OSM Test with aerial imagery") {
        - term MapLibre Mobile rendering: no text labels.  No water fill. No protected areas fill.
        ![](OSM-A-2)
    }
}
