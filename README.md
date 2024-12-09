This repository contains data obtained via a survey conducted on Amazon Mechanical Turk. The survey presented various driving scenarios, including details such as destination, current time, weather, passenger presence, etc., and asked participants whether they would accept a 
coupon if they were the driver.

## Objective
The goal is to determine whether a customer will accept a coupon.

## Dataset Description

The dataset consists of responses to the survey questions, with each row representing a unique scenario. The columns include:

- `scenario`: A description of the driving scenario presented to the participant.
- `destination`: The intended destination for the drive.
- `time`: The current time of day.
- `weather`: The weather conditions during the drive.
- `passenger`: Whether a passenger was present in the vehicle.
- `accept_coupon`: A binary indicator of whether the participant would accept the coupon if they were the driver.

There are three possible answers people can choose from:

“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).

## Data Access

The original dataset is available for download in CSV format from https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation. 

## Contact

For any questions or concerns, please contact [priyadarsheeni@gmal.com].

