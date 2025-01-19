# Hotel Reservation Prediction

This repository contains the implementation of a predictive model for hotel reservation cancellations. The model uses various customer and reservation features to predict whether a booking will be canceled or not. It is designed to assist hotel management in improving revenue forecasting and customer service.

## Features

The dataset includes the following features:
- **no_of_adults**: Number of adults in the reservation.
- **no_of_children**: Number of children in the reservation.
- **no_of_weekend_nights**: Number of weekend nights in the reservation.
- **no_of_week_nights**: Number of weeknights in the reservation.
- **type_of_meal_plan**: Meal plan chosen by the customer.
- **required_car_parking_space**: Whether a car parking space is required.
- **room_type_reserved**: Type of room reserved by the customer.
- **lead_time**: Number of days between the booking date and the check-in date.
- **arrival_year**: Year of the arrival date.
- **arrival_month**: Month of the arrival date.
- **arrival_date**: Day of the arrival date.
- **market_segment_type**: Marketing segment classification for the booking.
- **repeated_guest**: Whether the customer is a repeat guest.
- **no_of_previous_cancellations**: Number of prior cancellations by the customer.
- **no_of_previous_bookings_not_canceled**: Number of prior bookings not canceled by the customer.
- **avg_price_per_room**: Average price per room for the reservation.
- **no_of_special_requests**: Number of special requests made by the customer.
- **Day**: Day of the week of the arrival date.
- **total_people**: Total number of people in the reservation.
- **total_nights**: Total number of nights in the reservation.

## Model

The predictive model was trained using the Random Forest algorithm. The training dataset consists of labeled data indicating whether a reservation was canceled or not. Key steps in the model pipeline include:
1. Data Preprocessing
   - Handling missing values
   - Encoding categorical variables
   - Scaling numerical features (if applicable)
2. Model Training
   - Random Forest classifier
3. Model Evaluation
   - Metrics: Accuracy, Precision, Recall, and F1-score

## Deployment

The model is deployed using R Shiny, providing an interactive user interface for predictions. Users can input reservation details and receive predictions in real-time.

## Files

- **Hotel_reservation.Rmd**: R Markdown file containing the model development and analysis.
- **HotelReservations.csv**: dataset used for training.
- **README.md**: Documentation for the repository.
- **HotelReservations.pbix**: Dashboard Interactive use Power BI
- **hotel_forest_model.rds**: Random Forest model has saved
- **Hotel_reservation.html**: Rpubs uploaded to shiny
- **Deploy_hotel_shiny.mp4**: Runing after Deployment and Runing dashboard use Power BI

## Publish

 - https://rpubs.com/amri11/1263958

