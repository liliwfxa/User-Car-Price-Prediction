Data Source: Over 1GB from Kaggle's Used Cars Dataset, targeting listing prices.

Context: Tapping into the vast $138 billion US used car market, this project seeks to refine pricing strategies for sellers and guide buyers.

Approach: Employing decision trees and random forest models, the project aims to predict accurate car valuations, benefiting both sellers and buyers in the dynamic used car market.




2. Data Introduction
The dataset is a comprehensive collection of used vehicle listings from Craigslist across the United States. It has been compiled by scraping the platform every few months and contains detailed information about the car sales posted there. There are 426880 row, 26 columns and 9443544 non-null entities in the dataset. Here's an overview of the types of information included in the dataset, represented by each column:

id: Unique identifier for the listing.

url: URL of the vehicle listing on Craigslist.

region: Geographic region of the listing.

region_url: Craigslist URL for the region.

price: The listed price of the car

year: Year of the vehicle manufacture.

manufacturer: Vehicle manufacturer.

model: Specific model of the vehicle.

condition: Condition of the vehicle (e.g., new, used, etc.).

cylinders: Number of cylinders in the vehicle's engine.

fuel: Type of fuel the vehicle uses.

odometer: Mileage on the vehicle.

title_status: Legal status of the vehicle's title.

transmission: Type of vehicle transmission.

VIN: Vehicle Identification Number.

drive: Type of drivetrain.

size: Size category of the vehicle.

type: Type of vehicle body.

paint_color: Color of the vehicle.

image_url: URL of the vehicle's image.

description: Description provided in the listing.

county: County where the vehicle is located (often missing).

state: State where the vehicle is listed. lat: Latitude coordinate for the listing location.

long: Longitude coordinate for the listing location.

posting_date: Date and time when the listing was posted.
