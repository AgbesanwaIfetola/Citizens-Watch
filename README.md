# Citizens Watch

# Usage

1. First install all dependencies:

   ```bash
   # with npm
   npm install

   # or with yarn
   yarn
   ```

2. Open PHPMyAdmin, create a DB & import `db.sql` file.
3. Create a `.env` file and insert the following code. Replace values with yours!!

   ```javascript
   PORT = YOUR_PORT;
   MYSQL_HOST = 'host';
   MYSQL_USER = 'user';
   MYSQL_PASSWORD = 'password';
   MYSQL_DATABASE = 'db';
   SESSION_SECRET_LETTER = 'anything-secret';
   ```

4. Start the server

   ```javascript
   npm start [OR] yarn start
   ```

5. Open the app on

   ```javacript
   localhost:3917
   ```

6. Enjoy!!
