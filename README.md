Using Apache POI integrated with Cucumber / Selenium, Integrate a data provider for feeding the test data into the testing platform with your own example.

Console Output :

Scenario: User login with valid credentials                         # src/test/java/features/Log.feature:3
Starting ChromeDriver 123.0.6312.58 (6b4b19e9dfbb93aa414dc045bd445287977d8d7a-refs/branch-heads/6312_46@{#3}) on port 30774
Only local connections are allowed.
Please see https://chromedriver.chromium.org/security-considerations for suggestions on keeping ChromeDriver safe.
ChromeDriver was started successfully.
Mar 26, 2024 4:35:01 PM org.openqa.selenium.remote.ProtocolHandshake createSession
INFO: Detected dialect: W3C
  Given User is on the login page with valid credentials from Excel # features.Log.user_is_on_the_login_page_with_valid_credentials_from_excel()
  SimpleLogger to log to the console...
  When User enters username and password                            # features.Log.user_enters_username_and_password()
  Then User clicks on login button                                  # features.Log.user_clicks_on_login_button()
Loged in
  Then User should be logged in                                     # features.Log.user_should_be_logged_in()

1 Scenarios (1 passed)
4 Steps (4 passed)
3m16.658s



