# Trip Hotel API

## Overview
Trip is a hotel listing platform that provides hotel details from around the world. Users can filter hotels by category, amenities, and country, as well as sort by pricing, ratings, and reviews.

## Setup & Deployment
1. Clone the repository:
   ```sh
   git clone https://github.com/AkshAI-2030/Small-Trip-Project
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   npm start
   ```

## API Endpoints
### Hotel Sorting
- **By Pricing:** `/hotels/sort/pricing?pricing=low-to-high` or `high-to-low`
- **By Ratings:** `/hotels/sort/rating?rating=low-to-high` or `high-to-low`
- **By Reviews:** `/hotels/sort/reviews?reviews=least-to-most` or `most-to-least`

### Hotel Filtering
- **By Category:** `/hotels/filter/category?category=luxury`
- **By Amenity:** `/hotels/filter/amenity?amenity=spa`
- **By Country:** `/hotels/filter/country?country=india`

### Retrieve All Hotels
- **Endpoint:** `/hotels`
- Returns all available hotels.

## Integration with Trip Frontend UI
1. Deploy the backend API to Vercel.
2. Copy the deployment URL.
3. Open [Trip Frontend](https://bd2-hotel-listing.vercel.app/).
4. Paste the backend URL in the **Server URL** field and save.

## Features
- Sort hotels by pricing, ratings, and reviews.
- Filter hotels by category, amenities, and country.
- Seamless integration with Trip’s frontend UI.

### Notes
- Ensure `cors` is imported before API endpoints:
  ```javascript
  let cors = require('cors');
  app.use(cors());
  ```

## Live Demo & Resources
- **Live Video Demo:** [Click Here](#)
- **StackBlitz URL:** [StackBlitz Project](https://stackblitz.com/~/github.com/AkshAI-2030/Small-Trip-Project)
- **Deployed URL:** [Trip API](https://small-trip-project-akshay.vercel.app/)

## Conclusion
This API provides powerful filtering and sorting options for hotel listings, enhancing the Trip booking experience.

