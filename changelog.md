# 3.3.0 — 18 July 2022
 - Added the ability to change the default Do Not Track option on tracking codes
 - Added the ability to change the Email Reports to Monthly or Weekly
 - Improved the cron jobs system
 - Fixed search not working on User Dashboard and the Websites API endpoint
 - Other minor improvements

# 3.2.0 — 7 July 2022
 - Improved adding new Website process: URL protocol is no longer required
 - Improved the API Documentation
 - Other minor improvements

# 3.1.0 — 26 June 2022
 - Added new payment gateway: Paystack (checkout using a credit card)
 - Added new payment gateway: Razorpay (checkout using a credit card)
 - Added new payment gateway: Crypto.com (checkout using a cryptocurrency)
 - Added Two-factor Authentication system
 - Added Webhooks on User Store, Update, and Delete events
 - Added both light and dark mode logos
 - Added the ability to create coupons with unlimited quantity number
 - Improved the dark mode
 - Updated all the dependencies to their latest versions
 - Fixed an issue that would immediately remove the User's plan features after cancellation
 - Fixed an issue that was preventing tracking Events with values between 0 and 1
 - Other minor improvements

# 3.0.0 — 18 April 2022
- Added new filters on all table lists (column order, order direction, per page limits)
- Added the ability to set the Plan's position on the Pricing listings
- Added the ability to set custom CSS code based on the color scheme
- Added the ability to block adding a Website containing certain keywords using the Bad Words filter
- Improved the codebase (code refactoring)
- Improved the CSV export functionality (it now includes the URL where the report was generated from)
- Improved the table lists filters (improved flexibility)
- Improved the API Documentation
- Improved the translation strings
- Improved the SEO capabilities side-wide by adding in-file head tags for all public pages
- Improved the iconography
- Fixed not being able to edit a User that was under a recurring subscription
- Fixed user's content being deleted when the user would get suspended
- Fixed the API Documentation URL path not pointing to the correct location
- Fixed the Plans not ending when being cancelled on Stripe and PayPal
- Other minor improvements

# 2.9.0 — 12 December 2021
- Added the ability to exclude entire IP classes using CIDR notation
- Added contextual menus on all table lists
- Updated all the dependencies to their latest versions
- Fixed an issue with specific currencies that would prevent the Checkout from working
- Fixed several missing language strings
- Other minor improvements

# 2.8.0 — 27 September 2021
- Added translation ability for the Page title and description
- Fixed an issue preventing redeeming coupons
- Fixed an issue preventing changing the user's plan when no ending date was defined
- Other minor improvements

# 2.7.0 — 13 September 2021
- Added email notification on successful Stripe, PayPal and Coinbase payments
- Improved the UI & UX of the Log-in, Register, Password reset, Contact and Page pages
- Fixed an issue that would display all tax rates on Checkout before the user would select his country
- Fixed an issue causing Checkout not to work when no Coupon was provided
- Fixed an issue causing Checkout interval switcher not to work
- Fixed the tracking ability not resetting when redeeming a plan
- Other minor improvements

# 2.6.0 — 5 September 2021
- Fixed the Pricing not showing up on the Home page unless Stripe was enabled
- Fixed not being able to create new Plans
- Fixed the Page links from the Footer not showing their name
- Other minor improvements

# 2.5.0 — 3 September 2021
- Added new payment gateway: PayPal (checkout using a PayPal account)
- Added new payment gateway: Coinbase (checkout using a cryptocurrency)
- Added new payment gateway: Bank (checkout using a bank transfer)
- Improved the codebase (name convention refactoring)
- Improved ARIA controls
- Improved the Invoices (they are now immutable)
- Improved the Installation process
- Fixed the new Website form not including the Exclude URL query parameters form
- Fixed the Stats API endpoint working with the website's URL rather than ID
- Fixed an issue with passwords being trimmed when changed
- Fixed several missing language strings
- Other minor improvements

# 2.4.0 — 26 March 2021
- Added the ability to exclude URL query parameters from tracked pages
- Improved the database structure (IDs are now unsigned)
- Fixed several missing language strings
- Other minor improvements

# 2.3.0 — 20 March 2021
- Fixed the Stats API endpoint not returning results
- Fixed the Stats API endpoint returning a success response even on missing resources
- Fixed the tracking ability not resetting when manually assigning a plan
- Other minor improvements

# 2.2.0 — 25 February 2021
- Added Cronjob for automatic cache deletion
- Fixed the pricing plans not showing Unlimited when pageviews set to -1
- Fixed Sort by on Stats pages not working on paginated tables
- Other minor improvements

# 2.1.0 — 29 January 2021
- Added the ability to toggle password visibility for Websites
- Improved the password encryption method for Websites
- Other minor improvements

# 2.0.0 — 25 January 2021
- Added PostCSS support
- Added context menu on Stats pages
- Added Delete option in the website's context menu on Dashboard
- Improved the CSS filesize (removed all unused CSS rules)
- Improved the API (added status code for the websites listing)
- Updated all the dependencies to their latest versions
- Fixed unknown countries not displaying an icon
- Other minor improvements

# 1.9.0 — 14 January 2021
- Updated all the dependencies to their latest versions
- Fixed the Developers link missing from the footer
- Other minor improvements

# 1.8.0 — 5 January 2021
- Added the ability to hide the Default (free) plan
- Improved the tooltips on charts (added dark mode support)
- Other minor improvements

# 1.7.0 — 2 January 2021
- Fixed the monthly email reports not including the stats count
- Fixed sending email reports when no websites had email notifications enabled
- Other minor improvements

# 1.6.0 — 1 January 2021
- Improved the Export functionality (added additional information to the file and filename)
- Updated all the dependencies to their latest versions
- Other minor improvements

# 1.5.0 — 29 December 2020
- Added Total stats for tables on each stats category
- Added new social network source (Pinterest)
- Added the ability to search trough stats resources via API
- Added the ability to sort the stats resources via API
- Added the ability to set custom pagination results value via API
- Improved the JS tracking code (reduced its size even further)
- Improved the SEO for the Home page
- Fixed an issue that was reporting pageviews as visitors in a specific scenario
- Fixed several timestamps showing wrong minutes value
- Other minor improvements

# 1.4.0 — 16 December 2020
- Added decimal support for Events that have a unit value
- Added support for both www and non-www tracking with a single domain entry
- Fixed the live chart showing NaN when the value of visitors was 0
- Other minor improvements

# 1.3.0 — 15 December 2020
- Improved email template (added support for wide aspect logos)
- Improved the checkout process (you can now cancel the coupon adding process)
- Fixed an issue that was preventing the Check cronjob from executing
- Fixed the tracking ability not resetting when subscribing to a plan
- Other minor improvements

# 1.2.0 — 12 December 2020
- Fixed an issue preventing the deletion of websites
- Fixed an issue that removed the js source path from the tracking code
- Other minor improvements

# 1.1.0 — 10 December 2020
- Added support for CDN hosted tracking code
- Added automatic language switching when the language is availabl
- Added modal to the Export functionality
- Improved RTL support
- Fixed stats data not being removed when a user is being deleted
- Fixed stats data not being removed when a user is being deleted

# 1.0.0 — 1 December 2020
- Initial release
