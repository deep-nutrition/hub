# Deep Nutrition Hub
The primary data repository for deep nutrition information.

These are JSON files that contain either complete nutrition information or a list of ingredients. By recursively defining foods as compositions of more basic components, and then having detailed nutritional information on the basic components (from the USDA), Deep Nutrition is designed to provide a fully open source library foods all with a deep nutritional profile.

Furthermore, since the majority of foods will be defined in terms of more basic components, as the nutritional profiling of these basic components improves, so does the information on all other foods in the database based on them.

To kick start the database a large number of nutrients have been chosen from the USDA database and missing values imputed using low rank matrix completion methods. This gives estimates of complete nutritional information for thousands of basic foods. 
