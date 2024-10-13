# Open problems for the advanced hands-on session

### Make a mini calatog from the CTA-SDC data subset:
1. Load the following obs ids: [5000002225, 5000002226, 5000002250, 5000002251, 5000002280,
5000002307, 5000002308, 5000002404, 5000002405, 5000002436, 5000002437, 5000002459, 
5000002461, 5000002635, 5000002636, 5000002652, 5000002653, 5000002666, 5000002667, 
5000002723, 5000002831, 5000002833, 5000002886, 5000002932, 5000002959, 5000002961, 
5000002964, 5000003155, 5000003156, 5000003164, 5000003165, 5000003184, 5000003270, 
5000003287, 5000003288, 5000003346, 5000003348]
2. Create a 3D map dataset from the above observations
3.Use a `TSMapEstimator` to make a quick list of source candidates in the field; 
follow : https://docs.gammapy.org/dev/tutorials/analysis-3d/cta_data_analysis.html#sphx-glr-tutorials-analysis-3d-cta-data-analysis-py
4. Use the Fermi-LAT 4fhl catalog or the HESS Galactic plane surve catalogs given in GAMMAPY_DATA to correlate against known sources; 
refer to https://docs.gammapy.org/dev/tutorials/api/catalog.html#sphx-glr-tutorials-api-catalog-py for details of using catalogs
5. Now, perform a detailed 3D analysis of the sources you see
