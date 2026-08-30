# Will-you-go-out-with-me-

## EmailJS setup

This app now sends the selected date/time summary email through EmailJS when the date form is submitted.

1. Create a free account at [EmailJS](https://www.emailjs.com/).
2. Create:
   - an Email Service
   - an Email Template
3. Configure EmailJS values by setting `window.EMAILJS_CONFIG` before the app script runs, for example:
   - `publicKey`
   - `serviceId`
   - `templateId`
4. In your EmailJS template, use these template variables:
   - `{{formatted_date}}`
   - `{{formatted_time}}`
   - `{{confirmation_message}}`
5. Configure the template recipient in your EmailJS dashboard.
6. In EmailJS, restrict allowed origins to your site/domain to prevent quota abuse.
7. Do not commit real EmailJS keys/IDs to the repository.
8. Note: EmailJS runs in the browser, so public keys and IDs are visible client-side; always use origin restrictions and EmailJS-side controls.