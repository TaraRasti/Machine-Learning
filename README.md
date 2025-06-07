# Machine-Learning
| Column Name         | Description                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| `transaction_id`    | A unique identifier for each property sale (UUID).                                                                             |
| `price`             | Price paid for the property (in GBP, not adjusted for inflation).                                                              |
| `date_of_transfer`  | The date the sale was registered (format: YYYY-MM-DD).                                                                         |
| `postcode`          | Full UK postcode of the property (e.g., BS1 5AH).                                                                              |
| `property_type`     | Type of property sold: <br>`D` = Detached <br>`S` = Semi-detached <br>`T` = Terraced <br>`F` = Flat/Maisonette <br>`O` = Other |
| `duration`          | Tenure type of the property: <br>`Freehold` or `Leasehold`                                                                     |
| `paon`              | Primary Addressable Object Name — usually the house number or name.                                                            |
| `saon`              | Secondary Addressable Object Name — e.g., apartment number (can be blank).                                                     |
| `street`            | Street name of the property.                                                                                                   |
| `locality`          | Local area or neighborhood (may be blank).                                                                                     |
| `town_city`         | Town or city in which the property is located.                                                                                 |
| `district`          | Local authority district.                                                                                                      |
| `county`            | County name (e.g., Bristol, Hampshire).                                                                                        |
| `ppd_category_type` | Type of transaction: <br>`A` = Standard sale <br>`B` = Additional details (e.g., repossession, buy-to-let, etc.)               |
| `record_status`     | Indicates if the record is added or changed: <br>`A` = Added <br>`C` = Changed                                                 |
