# Real Estate Price Prediction in Saint-Malo using DVF Data

Building predictive models to estimate real estate prices based on limited property features provided in the state 'DVF' dataset (https://app.dvf.etalab.gouv.fr/).

Three types of model explored: 
- A linear regression using scikit-learn
- A boosted tree using XGBoost
- A simple neural network using TensorFlow/Keras

Models input:
- total surface (feature 'surface_reelle_bati'), in sqm
- number of rooms (feature 'nombre_pieces_principales'), in #
- field surface (feature 'surface_terrain'), in sqm
- position (feature 'longitude', 'latitude')
- housing type (house=1 or flat=0 - feature 'maison'), 1 or 0

Models output: 
- total price (feature 'valeur_fonciere'), in kEUR

Notebook content: 
- Data import
- Data preprocessing and scaling
- Models building, evaluation and comparison

Note on the dataset: 
The dataset is sourced from DVF data portal, which is openly accessible and provides information on property transactions including transaction price, surface area, location details, and number of rooms. This dataset does not include detailed property conditions or specific features like electrical/plumbing systems, presence of kitchen/bathroom, floor level, brightness, or necessary repairs.



