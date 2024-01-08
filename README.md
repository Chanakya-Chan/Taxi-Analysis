# Taxi-Analysis
An analysis on the reasons why the taxis are getting cancelled.
Conatins a Tableau dashboard.

----------------------------------------------------------------------------------------------------
Details on features:
<ul>
<li>M Order Eta - Estimated time of arrival from booking</li>
<li>Cancellation Time in seconds - The time from booking after which the taxi order has been cancelled.</li>
<li>Cancellation status - Mode of cancellation viz. "4" and "9" which refer to orders cancelled by user and orders cancelled by system respectively.</li>
<li>Order Datetime - Timestamp of booking</li>
</ul>



User Defined Parameters:
<ul>
<li>Arrival Factor - [M Order Eta]/[Cancellation Time in seconds]</li>
<li>Driver Late - Defines a probable reason why the order was cancelled</li>
  <ul>
    If the field Driver Late is:
    <ul>
      <li>Driver Late - Waiting time by customer has exceed the estimated time of arrival but the driver hasn't reached the pickup location yet.</li>
      <li>Driver was not Late - The user has cancelled the booking before the estimated arrival time.</li>
      <li>Driver Not Assigned - Driver hasn't been assigned to the customer.</li>
    </ul>
  </ul>
</ul>
