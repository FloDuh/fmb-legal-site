# Find My Bartender – Legal Site (Firebase Hosting)

## Quick deploy
1) Install Node.js LTS (if needed), then:
```
npm install -g firebase-tools
firebase login
```
2) In this folder:
```
firebase init hosting
# Choose: Use an existing project -> your Firebase project
# Public directory: public
# Configure as a single-page app? n
# Set up automatic builds/deploys with GitHub? n
```
3) Deploy:
```
firebase deploy
```

## Custom domain
Add in Firebase Console → Hosting → Add custom domain. Verify with TXT record, then point A/AAAA to Firebase. Propagation can take up to an hour.

## Edit contact info
Search for `support@your-domain.com` and replace with your real address and company postal address.