# Web3Forms Setup Instructions

## Step 1: Get Your Access Key

1. Go to https://web3forms.com
2. Enter your email: **royasmit345@gmail.com**
3. Click "Get Access Key"
4. Check your email inbox for the verification email
5. Copy the access key from the email

## Step 2: Update the Code

Once you have your access key, replace `YOUR_WEB3FORMS_ACCESS_KEY` in the file `/app/frontend/src/App.js`

Find this line (around line 90):
```javascript
access_key: 'YOUR_WEB3FORMS_ACCESS_KEY', // User needs to replace this
```

Replace it with:
```javascript
access_key: 'your-actual-access-key-here',
```

## Step 3: Test the Contact Form

1. Go to your portfolio website
2. Fill out the contact form
3. Submit it
4. You should receive an email at royasmit345@gmail.com

## Alternative: Quick Setup Command

If you have your access key, run this command (replace YOUR_KEY with your actual key):

```bash
sed -i "s/YOUR_WEB3FORMS_ACCESS_KEY/YOUR_KEY/g" /app/frontend/src/App.js
```

## Features

- ✅ Free tier: 250 submissions/month
- ✅ No backend required
- ✅ Spam protection included
- ✅ Email notifications to royasmit345@gmail.com
- ✅ Form data stored in Web3Forms dashboard

## Support

If you need help, visit: https://docs.web3forms.com
