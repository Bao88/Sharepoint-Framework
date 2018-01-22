Add to script in package json and run with npm run dev to execute, newest NodeJS runs with HTTP2 and gulp doesn't seem to 
be compatible with it yet.
 "dev" : "set NODE_NO_HTTP2=1&& gulp serve",