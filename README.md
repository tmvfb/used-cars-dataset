# used-cars-dataset

[![image](https://raw.githubusercontent.com/jupyter/design/0ed7f5798358c203d8bc6c1ce0f46d9c8294fd4e/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/tmvfb/used-cars-dataset/blob/main/notebook.ipynb#)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tmvfb/used-cars-dataset/main?filepath=notebook.ipynb)

This notebook uses prettified Kaggle [used cars dataset](https://www.kaggle.com/datasets/thedevastator/uncovering-factors-that-affect-used-car-prices). Dataset contains car ads from eBay-Kleinanzeigen.

The task is to predict car price with minimum error and minimum model working time. Task metric is RMSE.

| Feature | Description |
| :----- | :-----|  
`DateCrawled` | Date of downloading questionnaires from the database  
`VehicleType` | Type of vehicle body  
`RegistrationYear` | Year of vehicle registration  
`Gearbox` | Gearbox type  
`Power` | Power (hp)  
`Model` | Car model  
`Kilometer` | Mileage (km)  
`RegistrationMonth` | Month of car registration  
`FuelType` | Type of fuel  
`Brand` | Brand of car  
`Repair` | Has the car been repaired or not 
`DateCreated` | Date of creation of the questionnaire  
`NumberOfPictures` | The number of photos of the car  
`PostalCode` | Postal code of the profile owner (user)  
`LastSeen` | Date of latest user activity  
`Price` (**target feature**) | Price (EUR)
