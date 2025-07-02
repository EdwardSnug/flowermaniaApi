## Flowermania API
- A mock RESTful API for the Flowermania project built using json-server.
- This API serves data for flowers, reviews, and other resources used in the Flowermania frontend.

## Getting Started
# Prerequisites
- Make sure you have Node.js and npm installed. Then install json-server globally:
-   npm install -g json-server
  
# Clone the Repository
  git clone https://github.com/EdwardSnug/flowermaniaApi.git
# Start the Server
-  npx --watch json-server db.json

## API Endpoints
# FLowers
GET	/flowers	Get all flowers
GET	/flowers/:id	Get a single flower by ID
POST	/flowers	Add a new flower
PUT	/flowers/:id	Update a flower
DELETE	/flowers/:id	Delete a flower

# db.json sample data structure
{
  "flowers": [
    {
      "id": 1,
      "image": "/images/flower-1.jpg",
      "price": "4000",
      "description": "Bouquet for romantic occasions."
    },
    {
      "id": 2,
      "image": "/images/flower-2.jpg",
      "price": "3000",
      "description": "Petalstone charm."
    },...

## Deployment
You can deploy this API using platforms like:
- Render
- Vercel (Serverless Functions)

  Example Render deployment:
1. Create a new Web Service.
2. Add your db.json as part of the Git repo.
3. Use json-server --watch db.json as the start command.

## Author
Edward Kamande Karogo
Documentation created on June 30, 2025

