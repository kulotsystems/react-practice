## react-practice
**MovieLand:**
Learning some fundamental concepts of [**React**](https://reactjs.org/) from
[React JS Crash Course 2022](https://www.youtube.com/watch?v=b9eMGE7QtTk&t)
by
[JavaScript Mastery](https://www.youtube.com/channel/UCmXmlB4-HJytD7wek0Uo97A)
but on [Vite](https://vitejs.dev/).

#### Development Setup
1. Generate and assign OMDb API Key

    a. Access <https://www.omdbapi.com/apikey.aspx>.
    
    b. Generate your FREE API Key.
    
    c. Copy [.env-example](.env-example) of this repository as [.env](.env) to its same directory.
    
    d. Write your OMDb API ID and Key to [.env](.env).
    ```.dotenv
    VITE_OMDB_API_ID=YOUR_OMDB_API_ID
    VITE_OMDB_API_KEY=YOUR_OMDB_API_KEY
    ```
    Note: The `API ID` is the value of `i` query parameter of your API URL.
2. Clone or download this repository.
3. CD into the project root directory.
4. Run local development server
    ```
    npm run dev
    ```
5. Build for production
   ```
   npm run build
   ```