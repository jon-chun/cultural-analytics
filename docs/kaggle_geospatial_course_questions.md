Cultural Analytics Class Outlines

Week 2: Maps

Wednesday: Questions on Kaggle Notebooks

Kaggle Geospatial Course: [https://www.kaggle.com/learn/geospatial-analysis](https://www.kaggle.com/learn/geospatial-analysis)



1. Your First Map (Be sure to click on the black (&lt;>) icon under the right “Exercise” column) 
    * What does the library [learntools ](https://github.com/Kaggle/learntools)do ([README.md](https://github.com/Kaggle/learntools/blob/master/learntools/core/README.md) file)?
        - Uncomment q_1.[hint() and solution()]
    * Find what [3 datasets](https://stackoverflow.com/questions/51621615/which-geopandas-datasets-maps-are-available) are available in the [Geopandas API](https://geopandas.org/en/stable/docs/reference/api/geopandas.datasets.available.html#)
        -  What info does the dataset **naturalearth_lowres** have?
    * What does fig, ax = plt.subplot(1, 2) do?
        - Video [explanation1](https://www.youtube.com/watch?v=Tqph7_qMujk) 
    * What is the difference between:
        - PHL_loans = world_loans[world_loans['country'] == 'Philippines']
        - PHL_loans <strong>=</strong> world_loans.loc[world_loans.country<strong>==</strong>"Philippines"].copy()
    * What does the library [fiona](https://github.com/Toblerity/Fiona) do?
    * What is the file format [KML](https://developers.google.com/kml/documentation/kml_tut) below mean?
        - gpd.io.file.fiona.drvsupport.supported_drivers['KML'] = 'rw'
    * Done
2. Coordinate Reference System
    * What does the library [shapley ](https://shapely.readthedocs.io/en/stable/manual.html)do?
    * What is the purpose of the argument “parse_dates=” below?
        - birds_df = pd.read_csv("../input/geospatial-learn-course-data/purple_martin.csv", parse_dates=['timestamp'])
    *  Find the manual page for [GeoDataFrame.CRS](https://geopandas.org/en/stable/docs/reference/api/geopandas.GeoSeries.crs.html)()?
        - What is {‘init’: ‘[epsg:4326](https://epsg.io/4326)’}?
    *  What does: “ax.set_xlim([-110, -30])” do?
    *  Parse these statements:
        - path_df = birds.<strong>groupby</strong>("tag-local-identifier")['geometry']<strong>.apply(list)</strong>.apply(lambda x: LineString(x)).reset_index()
        -  start_df = birds.groupby("tag-local-identifier")['geometry'].apply(list)<strong>.apply(lambda x: </strong>x[0])<strong>.reset_index()</strong>
        -  end_df = birds.groupby("tag-local-identifier")['geometry'].apply(list).apply(lambda x: <strong>x[-1]</strong>).reset_index()
    *  Parse this statement:
        -  totalArea = sum(south_america.geometry<strong>.to_crs(epsg=3035)</strong>.area) / 10**6
        -  protected_areas[protected_areas['MARINE']!='2']<strong>.plot(ax=ax</strong>, <strong>alpha=0.4</strong>, zorder=1)
        -  birds[birds.geometry.y <strong>&lt;</strong> 0]<strong>.plot(ax=ax</strong>, color<strong>=</strong>'red', alpha<strong>=</strong>0.6, markersize<strong>=</strong>10,<strong> zorder=2</strong>) (is higher zorder top or bottom?)
    *  Done
3. Interactive Maps
    *  What does the library [folium ](https://github.com/python-visualization/folium)do?
    *  What does this statement mean?
        -  from IPython.display <strong>import IFrame</strong>
    *  What does the <strong>geometry </strong>column look like in <strong>plate_boundaries</strong>?
        -  Break up the cell and inspect the <strong>plate_boundaries </strong>GeoDataFrame.
        -  Another way to see this <strong>geometry </strong>column before dropping it?
    *  Experiment with the <strong>radius</strong>i argument in the call to the HeatMap() method
        -  HeatMap(data=earthquakes[['Latitude', 'Longitude']], <strong>radius=15</strong>).add_to(m_1)
    *  What critical assumption does the join statement make (potential source of bugs)?
        -  stats = population.join(area_sqkm)
    *  What does the GeoDataFrame.[__geo_interface__](https://geopandas.org/en/stable/docs/reference/api/geopandas.GeoDataFrame.__geo_interface__.html) do?
    *  Explain[ ](https://www.python-graph-gallery.com/292-choropleth-map-with-folium)how a [folium choropleth map](https://www.python-graph-gallery.com/292-choropleth-map-with-folium) works?
    *  Done
4. Manipulating Geospatial Data
    *  Questions in class
5. Proximity Analysis
    *  Questions in class