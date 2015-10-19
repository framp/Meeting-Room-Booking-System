# Meeting Room Booking System
It's hard to find an online booking system for meeting rooms that has all the feature that you need.

## Requirements
Expose everything as REST API
### User management
 * Single user signup/login
 * Company profile where N single user can be associated

### Payments
 * Stripe integration
 * Automatic refund
 * Send payment reminders / invoice

### Booking resources
 * Set opening times
 * Set hourly prices
 * Set minimum booking time (1 hour or 30 min or X)
 * Different locations (a way to group resources)
 * Set refund X hours before the booking
 * Set pre-book period (avoid people booking 3 months in advance)

### Extra
 * Discount codes
 * Simple configuration as JSON to get started

### Frontend UI
 * Clean and minimal
 * Signup / login / account page
 * Resources view
 * Calendar view
 * Booking wizard with payment
