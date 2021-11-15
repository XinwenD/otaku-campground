# Otaku-Campground

This app creates a campground review website where users can

- view existing campgrounds added by other users/added by the userself;
- add/edit/delete campgrounds created by userself;
- login to check campgrounds details;
- register to create a new account;

## Routing

- `/`: Homepage;

- `/campgrounds`: Campgrounds list page, with a dynamic cluster map showing all campgrounds;
- `/campgrounds/new`: Page to add a new single campground info (need auth/login);
- `/campgrounds/:id`: Page to show corresponding single campground;
- `/campgrounds/:id/edit`: Page to edit a single campground info (need auth/login; should be the user who created this campground);

- `/register`: User registration;
- `/login`: User login;
- `/logout`: User logout;

- `/campgrounds/:id/reviews`: Post review to specific campground;
- `/campgrounds/:id/reviews/:reviewId`: Edit/Delete a review;

## Techs

### Frontend/UI

- HTML/CSS/Javascript/EJS/Bootstrap/Method-override

### Backend

- Node/MongoDB/Mongoose/Express/Cloudinary

### Modularization

- ES6+/CommonJS

### Code Building

- Heroku/MongoDB Atlas

### Security/Validation/Error Handling

- Helmet/passport/passport-local/

### Others

- Mapbox
