# used-cars-dataset

This notebook uses prettified Kaggle [used cars dataset](https://www.kaggle.com/datasets/thedevastator/uncovering-factors-that-affect-used-car-prices). Dataset contains data on car ads from eBay-Kleinanzeigen.

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
`Repair` | Was the car under repair or not  
`DateCreated` | Date of creation of the questionnaire  
`NumberOfPictures` | The number of photos of the car  
`PostalCode` | Postal code of the profile owner (user)  
`LastSeen` | Date of latest user activity  
`Price` (**target feature**) | Price (EUR)
