# Taxi-Analysis
An analysis on the reasons why the taxis are getting cancelled.
Conatins a Tableau dashboard.

---------------------------------------------------------------------------
Details on features:
M Order Eta - Estimated time of arrival from booking
Cancellation Time in seconds - The time from booking after which the taxi order has been cancelled.
Cancellation status - Mode of cancellation viz. "4" and "9" which refer to orders cancelled by user and orders cancelled by system respectively.
Order Datetime - Timestamp of booking

User Defined Parameters
Arrival Factor - [M Order Eta]/[Cancellation Time in seconds]
Driver Late - Defines a probable reason why the order was cancelled
  If the field Driver Late is:
    Driver Late - Waiting time by customer has exceed the estimated time of arrival but the driver hasn't reached the pickup location yet.
    Driver was not Late - The user has cancelled the booking before the estimated arrival time.
    Driver Not Assigned - Driver hasn't been assigned to the customer.
