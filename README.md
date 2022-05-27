# Investigate Business Hotel using Data Visualization

## Overview
Sangat penting bagi suatu perusahaan untuk selalu menganalisa performa bisnisnya. Pada
kesempatan kali ini, kita akan lebih mendalami bisnis dalam bidang perhotelan. Fokus yang kita
tuju adalah **untuk mengetahui bagaimana perilaku pelanggan kita dalam melakukan pemesanan
hotel, dan hubungannya terhadap tingkat pembatalan pemesanan hotel**. Hasil dari insight yang
kita temukan akan kita sajikan dalam bentuk data visualisasi agar lebih mudah dipahami dan
bersifat lebih persuasif.

## Dataset
Dataset yang digunakan sebenarnya berasal dari link Kaggle [berikut](https://www.kaggle.com/datasets/mojtaba142/hotel-booking) yang telah dimodifikasi oleh tim Rakamin Academy untuk keperluan Mini Project ini, berikut adalah deskripsi datanya.
- `hotel` : The datasets contains the booking information of two hotel. One of the hotels is a resort hotel and the other is a city hotel
- `is_canceled` : Value indicating if the booking was canceled (1) or not (0)
- `lead_time` : Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
- `arrival_date_year` : Year of arrival date
- `arrival_date_month` : Month of arrival date with 12 categories: “January” to “December”
- `arrival_date_week_number` : Week number of the arrival date
- `arrival_date_day_of_month` : Day of the month of the arrival date
- `stays_in_weekend_nights` : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
- `stays_in_weekdays_nights` : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel BO and BL/Calculated by counting the number of week nights
- `adults` : Number of adults
- `children` : Number of children
- `babies` : Number of babies
- `meal` : Meal menu
- `city` : City of origin
- `market_segment` : Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
- `distribution_channel` : Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
- `is_repeated_guest` : Value indicating if the booking name was from a repeated guest (1) or not (0)
- `previous_cancellations` : Number of previous bookings that were cancelled by the customer prior to the current booking
- `previous_bookings_not_canceled` : Number of previous bookings not cancelled by the customer prior to the current booking
- `booking_changes` : Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
- `deposit_type` : No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay
- `agent` : ID of the travel agency that made the booking
- `company` : ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
- `days_in_waiting_list` : Number of days the booking was in the waiting list before it was confirmed to the customer
- `customer_type` : Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking
- `adr` : Average Daily Rate (Calculated by dividing the sum of all lodging transactions by the total number of staying nights)
- `required_car_parking_spaces` : Number of car parking spaces required by the customer
- `total_of_special_requests` : Number of special requests made by the customer (e.g. twin bed or high floor)
- `reservation_status` : Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why