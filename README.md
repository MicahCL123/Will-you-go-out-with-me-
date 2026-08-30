# Will-you-go-out-with-me-

## EmailJS setup

This app now sends the selected date/time summary email through EmailJS when the date form is submitted.

1. Create a free account at [EmailJS](https://www.emailjs.com/).
2. Create:
   - an Email Service
   - an Email Template
3. In `/home/runner/work/Will-you-go-out-with-me-/Will-you-go-out-with-me-/index.html`, replace:
   - `YOUR_EMAILJS_PUBLIC_KEY`
   - `YOUR_EMAILJS_SERVICE_ID`
   - `YOUR_EMAILJS_TEMPLATE_ID`
4. In your EmailJS template, use these template variables:
   - `{{to_email}}` (set to `micahbi@yahoo.com`)
   - `{{formatted_date}}`
   - `{{formatted_time}}`
   - `{{confirmation_message}}`