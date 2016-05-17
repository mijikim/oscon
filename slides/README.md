# Readme

These are the slides for the workshop "Docker in Production".
This is based on a fork of the Reveal.JS library.

## Running the slides

If you want this quick and easy, you can just fire up Chrome and open index.html. But there are a host of features that are useful for presenting that require you to run a local webserver. The easiest way to do this is:

1. [install nodejs](http://nodejs.org/)

2. Install Grunt:

	npm install grunt

3. Dependencies:


   ```sh
   $ npm install
   ```

4. Then launch the server using:

    ```sh
   $ grunt serve
   ```

5. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.
