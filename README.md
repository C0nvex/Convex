# Convex

Convex is a novel machine learning contrail prediction algorithm.

Contrails are heavily damaging to the environment because of their greenhouse effect, making up around half of aircraft-induced warming. Alarmingly, global air passengers are projected to quadruple to up to 16 million by 2050, meaning the industry's environmental impact will also increase dramatically unless we make major changes. 

Contrails could be avoided by rerouting flights around contrail formation regions. Convex uses an innovative approach to predict these regions combining open data and LightGBM, a gradient boosting model.

After testing multiple models and undergoing an extensive tuning process, the algorithm achieved a combined accuracy of 89.5% on two contrail formation criteria.

These results show that Convex is a crucial part of the fight against climate change, and with it we could reduce the impact of aviation by half. Not in 20 or 10 years, but right now.

This is a project for the 2024 South Fraser Regional Science Fair. [See more about the Convex here]([https://www.openai.com](https://projectboard.world/ysc/project/convex-foresight-into-contrail-forecasting?utm_source=shareLink_share_160422&postID=953381&rc=jownnmqj))

To download data directly from the Climate Data Store, see [here.](https://cds.climate.copernicus.eu/cdsapp#!/search?type=dataset&text=era5)

# Setup

You may have to reconfigure the file locations that point to the dataset files, especially if you are not using Google Colab.
The datasets used are too large for GitHub, you can find them [here](https://drive.google.com/drive/folders/1mkCzbjkBUyjbBR0jBj8TyAS7OZD1iqnS?usp=drive_link)

Note that the non-legacy datasets are more comprehensive, but you may run into memory issues with them like I did when testing them on my model.


Convex may be migrated to a user-friendly .py file or Python library in the future, stay tuned for updates!
