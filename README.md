# Will-you-go-out-with-me-

## EmailJS setup

This app now sends the selected date/time summary email through EmailJS when the date form is submitted.

1. Create a free account at [EmailJS](https://www.emailjs.com/).
2. Create:
   - an Email Service
   - an Email Template
3. In `index.html`, replace:
   - `YOUR_EMAILJS_PUBLIC_KEY`
   - `YOUR_EMAILJS_SERVICE_ID`
   - `YOUR_EMAILJS_TEMPLATE_ID`
4. In your EmailJS template, use these template variables:
   - `{{formatted_date}}`
   - `{{formatted_time}}`
   - `{{confirmation_message}}`
5. Configure the template recipient in your EmailJS dashboard.
6. In EmailJS, restrict allowed origins to your site/domain to prevent quota abuse.