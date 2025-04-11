# Formspree Setup Instructions

To complete the setup of your form submission service, follow these steps:

## 1. Create a Formspree Account

1. Go to [Formspree.io](https://formspree.io/) and sign up for an account
2. Log in to your account

## 2. Create a New Form

1. Click on "New Form"
2. Give your form a name (e.g., "Cooking School Application")
3. Select your preferred email to receive notifications

## 3. Get Your Form ID

1. After creating the form, you'll be given a form ID (it looks like "xrgpzweo")
2. Copy this form ID

## 4. Update Your Website

1. Open `index.html` in your code editor
2. Find the form tag (around line 823)
3. Replace `YOUR_FORMSPREE_FORM_ID` in the action attribute with your actual form ID:
   ```html
   <form id="applicationForm" method="post" action="https://formspree.io/f/YOUR_ACTUAL_FORM_ID">
   ```

## 5. Test Your Form

1. Upload your updated website files to your server
2. Visit your website and submit a test application
3. Check your email to confirm you received the submission
4. You can also view all submissions in your Formspree dashboard

## Additional Features

Formspree offers additional features that you might find useful:

- **Spam filtering**: Automatically enabled to protect your form
- **File uploads**: Available on paid plans
- **Custom redirects**: Set a custom thank you page
- **Webhooks**: Connect your form to other services
- **API access**: Programmatically access your form data

For more information, visit the [Formspree documentation](https://help.formspree.io/).
