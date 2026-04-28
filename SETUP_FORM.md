# Contact Form Setup Instructions

Your contact form is now configured to send emails to **director@emiratixsolutions.com**

## To Activate the Form:

1. **Get Your Free Access Key:**
   - Visit: https://web3forms.com
   - Enter your email: **director@emiratixsolutions.com**
   - Click "Get Access Key"
   - Check your inbox and copy the access key

2. **Add the Access Key:**
   - Open `index.html`
   - Find line with: `<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">`
   - Replace `YOUR_ACCESS_KEY_HERE` with your actual access key
   - Save the file

3. **Push to GitHub:**
   ```bash
   cd /Users/mohammad.khan/Documents/Work/testing/emiratrix
   git add index.html
   git commit -m "Add Web3Forms access key"
   git push origin main
   ```

## Features Included:

✅ Sends email to director@emiratixsolutions.com
✅ Collects: Name, Email, Phone (optional), Message
✅ Custom subject line: "New Contact Form Submission from Emiratix Website"
✅ Success message after submission
✅ Automatic redirect back to website
✅ Professional email format
✅ Spam protection included

## Testing:

Once you add your access key and push to GitHub:
1. Wait 1-2 minutes for deployment
2. Visit: https://arafatkhan2198.github.io/emiratix-landing/
3. Scroll to contact form
4. Fill it out and test!

You'll receive submissions at: director@emiratixsolutions.com

## Notes:

- Web3Forms is 100% free
- No signup required (just verify email)
- Unlimited submissions
- No branding added to emails
- Works perfectly with GitHub Pages
