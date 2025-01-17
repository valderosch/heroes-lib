# heroes-lib repository
## Super Heroes library app
**Applicatication for Creating, Browsing and Exploring Superheroes by large community**

### App conception:
**Simple CRUD Operations on Entities named heroes (Superheroes)**

### Consist of:
- **server** application (NodeJs, Express)
- **client** application (React)
- **cloud db** (MongoDb)

### Tech stack:
- ReactJs
- Redux
- NodeJs
- Express
- Mongoose
- cors
- multer
- config

### Endpoints (for server app):
- **Get All Heroes** - [**GET**] `/api/heroes?page=[default:1]`
- **Get Hero By Hero ID** - [**GET**] `/api/heroes/:id`
- **Create New Hero** - [**POST**] `/api/heroes`
- **Update Hero By Hero ID** - [**PUT**] `/api/heroes/:id`
- **Delete Hero By Hero ID** - [**DELETE**] `/api/heroes/:id`

### How to use the app?
1. Check Requirements
2. Download archive
3. Install Dependencies
4. Run apps

### App Requirements:
- NodeJs installed on machine

### Proper start:
1. In root directory, use `npm install` to install all dependencies.
2. Navigate to server app. Use `cd ./server`.
3. Start server application, by using `npm run` command.
4. navigate to client app folder. Use `cd ../client`.
5. Start client application, by using `npm start`.
6. navigate to your browser to start use application.