# Dating App

- its a full stack application with the backend written in .NET and Angular 16 for the front end (and bootstrap for the styling)
- some of the dependencies are like for the photos we will be using "ng-gallery" 
- note: make sure that b4 importing this module in our member details comp (make that as the standalone comp since this ng gallery will work along only with the standalone comp.
- and also imports every thing / comp that the member details comp relies on since its a standalone comp now. and make every single one of those imported comps (5 of em) as standalone comp.

### photo uploading features

- some of the things to keep in mind b4 implementing the photo upload feature.
- 1. any photos user upload should be unapproved by default.
- 2. only admin or moderators are allowed / can approve photos
- 3. No other user can be able to see un approved photos
- 4. The user who uploaded can be see, but it should be clearly identified as "waiting approval".
- 5. when the user uploads their first photo it should be their main/profile photo
- 6. when a moderator or admin approves the photo for the uesr that doesn't ve main photos then this should be set as the main photo.
- refer the pdf (notes) for the more details.
- check to see if any packages are outdated `npm outdated` and to perform the upgrade `npm i -g npm-check-updates && ncu -u && npm i -f`    