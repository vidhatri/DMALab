<h2> Data Preprocessing </h2>

<hr>
<h3> Walkthrough of Traveler Data </h3>

<h4> <i>Task</i>: Given a list of users along with their demographics, web session records, and some summary statistics. Predict which country a new user's first booking destination will be.</h4>

<hr>
<h3> Data descriptions </h3>
<ol>
  <li> <b>train_users_2.csv</b> - the training set of users </li>
  <li> <b>test_users.csv</b> - the test set of users </li>
  
  <ol>
  <li> <i><b>id</i></b>: user id </li>
  <li> <i><b>date_account_created</i></b>: the date of account creation </li>
  <li> <i><b>timestamp_first_active</i></b>: timestamp of the first activity, note that it can be earlier than date_account_created or date_first_booking because a user can search before signing up </li>
  <li> <i><b>date_first_booking</i></b>: date of first booking </li>
  <li> <i><b>gender</i></b> </li>
  <li> <i><b>age</i></b> </li>
  <li> <i><b>signup_method</i></b> </li>
  <li> <i><b>signup_flow</i></b>: the page a user came to signup up from </li>
  <li> <i><b>language</i></b>: international language preference </li>
  <li> <i><b>affiliate_channel</i></b>: what kind of paid marketing </li>
  <li> <i><b>affiliate_provider</i></b>: where the marketing is e.g. google, craigslist, other </li>
  <li> <i><b>first_affiliate_tracked</i></b>: whats the first marketing the user interacted with before the signing up </li>
  <li> <i><b>signup_app</i></b> </li>
  <li> <i><b>first_device_type</i></b> </li>
  <li> <i><b>first_browser</i></b> </li>
  <li> <i><b>country_destination</i></b>: this is the <i><b> target variable </b></i> you are to predict </li>
  </ol>
  
  <li> <b>sessions.csv</b> - web sessions log for users </li>
  
  <ol>
  <li> <i><b>user_id</i></b>: to be joined with the column 'id' in users table </li>
  <li> <i><b>action</i></b> </li>
  <li> <i><b>action_type</i></b> </li>
  <li> <i><b>action_detail</i></b> </li>
  <li> <i><b>device_type</i></b> </li> 
  <li> <i><b>secs_elapsed</i></b> </li>
  </ol>
  
  <li> <b>countries.csv</b> - summary statistics of destination countries in this dataset and their locations </li>
  <li> <b>age_gender_bkts.csv</b> - summary statistics of users' age group, gender, country of destination </li>
  
  <ul>


