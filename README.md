# Personal-Blog_ReactApp


1) Download and install at least LTS or the latest version of Node.js from its web site.

2) Download the personal blog zip file.

3) Extract the zip file.

4) Open your favorite console application (Terminal, Command Prompt etc.), navigate into your work folder, run the following command and wait for it to finish.

``bash
npm install
```

This command will install all the required Node.js modules into the   node_modules directory inside your work folder.
And now, you are ready to run the Personal Blog React app for the first time.

5) Make changes in the website according to your needs.

6) While still in your work folder, run the following command in the console application:

``bash
npm start
```

This command usually runs a development server that compiles your app in memory and supports features like hot reloading.

And that's it. create-react-app will take care of everything and start the React web application.
You can check out your console application to get further information about the server. By default, it will run on [http://localhost:3000](http://localhost:3000) but it might change depending on your setup.

7) The following command builds the application into an output directory
``bash
npm run build
```
			compiles the application into /build directory.

Deployment using static server: For environments using Node, the easiest way to handle this would be to install serve and let it handle the rest:
npm install -g serve
serve -s build
The last command shown above will serve your static site on port 3000. Like many of serve’s internal settings, the port can be adjusted using the -l or --listen flags:
serve -s build -l 4000
