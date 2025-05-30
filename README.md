### Fix
- Show error messages correctly

### Production Changes

- Change Google OAuth credentials
- Change email client credentials
- Create a GVCL SendGrid Account to send mails
- Set Secure app secret
- use Gunicorn
- Setup a routine to clear the files-upload,results,emails
  - https://chat.deepseek.com/a/chat/s/0978da71-d64c-42e4-9b7a-1cad335c1260

- if user opens email link, and he is not logged in, then when he logs in, redirect to same url
- instead of checking logged in status again and again, store user data in local storage


- make pages responsive to screen sizes
- 404 Page
- Footer w/o tailwindscss
- LOGO/Icon

- ensure proper permissions for folders
- LOGGING

### Security
- check firewall exposed ports
- CSRF token in form
- cookies
  - expiry
  - rules (samesite, etc.)

### Testing
- Test with unseen images

### VM

`ssh iiitb@cma-vm -L 4040:localhost:4040`

### Production
- cookie secure true