

1. Clone the repository.

   ```
   git clone https://github.com/HeyGen-Official/StreamingAvatar.git
   ```

2. Open the `index.js` file and replace `'YourApiKey'` with your API key:

   ```
   "apiKey": "YourApiKey";
   ```
3. (optional) Open the `server.js` file and set your OpenAI API key to use talk mode:
   ```
   const openai = new OpenAI({
     apiKey: "<your openai api key>",
   });
   ```

4. open a terminal in the folder and then install the express and run the server.js:

   ```
   npm install express
   node server.js
   ```

5. you will see `App is listening on port 3000!`.
