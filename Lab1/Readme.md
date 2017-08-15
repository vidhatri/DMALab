<h2> Data Preprocessing </h2>
<hr>
<h3> Data descriptions </h3>
<ol>
  <li> train_users_2.csv - the training set of users </li>
  <li> test_users.csv - the test set of users </li>
  
  <ol>
  <li> id: user id </li>
  <li> date_account_created: the date of account creation </li>
  <li> timestamp_first_active: timestamp of the first activity, note that it can be earlier than date_account_created   or date_first_booking because a user can search before signing up </li>
  <li> date_first_booking: date of first booking </li>
  <li> gender </li>
  <li> age</li>
  <li> signup_method </li>
  <li> signup_flow: the page a user came to signup up from </li>
  <li> language: international language preference </li>
  <li> affiliate_channel: what kind of paid marketing </li>
  <li> affiliate_provider: where the marketing is e.g. google, craigslist, other </li>
  <li> first_affiliate_tracked: whats the first marketing the user interacted with before the signing up </li>
  <li> signup_app </li>
  <li> first_device_type </li>
  <li> first_browser </li>
  <li> country_destination: this is the <bold> target variable </bold> you are to predict </li>
  </ol>
  
  <li> sessions.csv - web sessions log for users </li>
  
  <ol>
  <li> user_id: to be joined with the column 'id' in users table </li>
  <li> action </li>
  <li> action_type </li>
  <li> action_detail </li>
  <li> device_type </li> 
  <li> secs_elapsed </li>
  </ol>
  
  <li> countries.csv - summary statistics of destination countries in this dataset and their locations </li>
  <li> age_gender_bkts.csv - summary statistics of users' age group, gender, country of destination </li>
  
  <ul>


