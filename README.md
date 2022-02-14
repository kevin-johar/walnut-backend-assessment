# hatchways-backend
## Blog Posts API
- This repository consists of a Node + Express server application
- Consists of 2️⃣ endpoints ️
  - A server status check `GET /api/ping` 
  - A flexible blog posts querying endpoint (filter by tags, sort data by different properties) `GET /api/posts?tags=?&sortBy=?&direction=?`
- JEST is the testing framework used

## How to Run It
###Clone the repository by putting this in your terminal:
```
git clone https://github.com/kevin-johar/walnut-backend-assessment.git [set-folder-name](optional)
```

### Open up the repository
```
cd walnut-backend-assessment
```

###Install Dependencies:
```
npm install
```

### Start Application
```
npm run start
```

##Fun Notes
- Application has caching mechanism to reduce response time by up to 75% 🚀
  - Asynchronously the data is still updated, so you are never served super stale data 🤢
