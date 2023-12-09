# Dating App Hypothesis Test

## Conducting statistical research for payment system changes at dating application. Including AA and AB tests for several application metrics, and conclusions about experiment.

Full datasets describtion:<br><br>

There are three similar datasets for two control and one test groups:<br>
users_test<br>
users_control_1<br>
users_control_2<br>
transactions_test<br>
transactions_control_1<br>
transactions_control_2<br><br>

**users_*.csv** - users data<br>
uid - user ID<br>
age - age<br>
attraction_coeff - attractiveness factor<br>
coins - number of coins (in app currency)<br>
country - users country<br>
visit_days - on which days after registration the user visited the application<br>
gender - gender<br>
age_filter_start - search filter, min age<br>
age_filter_end - search filter, max age<br>
views_count - number of user's ratings received<br>
was_premium - was there ever a premium account<br>
is_premium - is it premium account<br>
total_revenue - total revenue<br><br>

**transactions_*.csv** - transactions data<br>
uid - user ID<br>
country - country<br>
joined_at - date and time of registration<br>
paid_at - date and time of purchase<br>
revenue - revenue<br>
payment_id - payment ID<br>
from_page - from where the user went to the payment page<br>
product_type - subscription type<br>