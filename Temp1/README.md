# Dynamic email template

Open `email-template.html` in a browser to preview the layout. Its styles are stored separately in `email-template.css`.

## Replace before sending

- Replace `YOUR_COMPANY_LOGO_URL` with the publicly hosted URL for your company logo.
- Replace `{{aiImageUrl}}` with the merge tag supported by your email platform. It should resolve to a publicly hosted AI-generated image URL.
- Replace `YOUR_LINK_URL` with the destination for the button, or remove the button table if it is not needed.
- Replace the sample heading and paragraphs with your email content.
- Keep `{{userName}}` if your email platform uses this merge-tag syntax. If it uses another syntax, change it to the platform's user-name variable, such as `{{first_name}}`, `%%FirstName%%`, or `${userName}`.

The username is populated by the email platform when the message is sent. JavaScript was intentionally not used because most email clients block it.
