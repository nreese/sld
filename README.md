# sld
Collection of SLD (Styled Layer Descriptor) XML files and corresponding html files that demonstrate how to use [elasticgeo](https://github.com/ngageoint/elasticgeo)/geoserver to generate WMS tiles from Elasticsearch aggregations.

## Loading dataset
* [mapping file](https://github.com/nreese/es-mappings)
* [earthquake data](https://github.com/nreese/rest2es)

## Configuring Geoserver

### Layouts
Save the following as `legend.xml` under `CATALINA_HOME/webapps/geoserver/data/layouts`
```
<layout>
    <decoration type="legend" affinity="top,right" offset="6,6" size="auto"/>
</layout>
```


## Useful links
* [Color map details](http://docs.geoserver.org/latest/en/user/styling/sld/reference/rastersymbolizer.html)
* [Legend formating](http://docs.geoserver.org/stable/en/user/services/wms/get_legend_graphic/index.html)
* [Legend as tile decoration](http://docs.geoserver.org/latest/en/user/services/wms/decoration.html)
* [Dynamic ranges](http://docs.geoserver.org/stable/en/user/community/colormap/index.html)
