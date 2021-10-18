# Predicting The Cancellation Hotel Booking
abdulaziz alkhonain


## Abstract
The goal of this project was to use classification models to predict wither the book is going to be cancelled or not depending on number of features to help the hoteles wither the book is most likly to cancel or not. This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. [data source]('https://www.kaggle.com/jessemostipak/hotel-booking-demand')

## Data
he dataset contains 119,390 books with 32 features for each, the features were spareted half of them were numerical, most of them are discrete, and the other is categorical. 
Features that may be confused:
* Hotels, there is two type of hotels, Resort Hotel and City Hotel.
* lead_time, Number of days that elapsed between the entering date of the booking into the PMS and the arrival date.
* reservation_status, Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer - Check-Out.
* adr, Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights.
* customer_type, Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to it; Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking.
* deposit_type, Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.
* previous_cancellations and previous_bookings_not_canceled, which are number representing the previous cancellations/bookings not canceled by the customer.


## Algorithms

