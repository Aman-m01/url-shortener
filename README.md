## URL Shortener
- This is a simple `URL shortener` application that allows users to create short URLs, view a preview, and manage simple user authentication.

## Features
- `User Authentication`: Sign up and log in to access the URL shortener.
- `URL Generation and preview`: Generate short URLs from long links and view a preview of the homepage

## Routes 
- Login: `http://localhost:8001/login`
- Signup: `http://localhost:8001/signup`
- Generate url & preview: `http://localhost:8001/`


## started 
1. clone the repo
```bash
    git clone https://github.com/Aman-m01/url-shortener.git
    cd url-shortener
```

2. Install dependencies 
```bash
  npm install 
```

3. Set up environment variables
- Create a .env file in the root directory and add the following
 ```bash 
  MONGODB_URI=your_mongodb_connection_string
PORT=8001

 ```

4. Run the server
```bash 
   npm start 
```
The application will be available at `http://localhost:8001.`