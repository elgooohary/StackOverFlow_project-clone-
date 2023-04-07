## Website Stack TECHNOLOHY 

#### Front-end

- Front-end Framework: `React.js (with Redux)`
- Styling: `SASS` and `BOOTSTRAP`

#### Back-end

-  `Node.js with Express.js Framework`
- As Database: `MySQL with Sequelize`

### Backend 
1. Open your local CLI -

   ```
   mkdir backend
   cd backend
   ```

2. Setup the backend code -

   - Create a `.env` file and the format should be as given in `.env.example
     ```
     cd Backend

     npm install
     ```

   - Open your MySQL Client -

     ```
     CREATE DATABASE stack_overflow;
     ```
     NOTE: Don't forget to keep the database name same in the `.env` and here.

   - Run the index `npm start`.
   
   
### To run  Docker images

- Build the Docker image:
  ```
  docker build -t stackoverflowclone .
  ```
- Run the container:
  ```
  docker run -d -p 5000:5000 stackoverflow
  ```

#### IMAGES

<img src="/images/1.png" width=400px /><img src="/images/2.png" width=400px />
<img src="/images/3.png" width=400px /><img src="/images/4.png" width=400px />
<img src="/images/5.png" width=400px /><img src="/images/6.png" width=400px />

