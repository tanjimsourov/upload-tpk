# Host SMCSignagePlayer.wgt on Render (Static Site)

## 1) Create a GitHub repo
Upload the contents of this folder to a new GitHub repository.

## 2) Create Render Static Site
- Render Dashboard -> New -> Static Site
- Connect your repo
- Build Command: (leave empty)
- Publish Directory: public

Deploy.

## 3) Your WGT URL
After deploy, the WGT will be available at:
https://YOUR-SERVICE.onrender.com/SMCSignagePlayer.wgt

## 4) Install on TV (Custom App / URL Launcher)
On Samsung signage TV:
- Switch Play Via to Custom App / URL Launcher
- Choose Install Custom App
- Paste the WGT URL above

## 5) Important: Signing
If the TV refuses the WGT, re-sign the WGT using your Samsung certificate and redeploy the signed file.
