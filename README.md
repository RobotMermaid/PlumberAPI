# Basic Plumber Runner

This example runs the [plumber.io](https://www.rplumber.io/) package for this [example]( https://www.rplumber.io/docs/quickstart.html#quickstart).

## Steps
in the terminal:
1. open `R` and run `install.packages("plumber")` and `install.packages("rscript")`
2. wait... the install took about 10 minutes
3. exit `R`
4. `cd` to root of your PlumberAPI repo 
5. run `Rscript run.R` it will return a message with a port number
`Starting server to listen on port 3229`
6. Open `http://localhost:3229/echo??msg=ohai` in your browser
7. It will return a response `{"msg": [ "The message is: 'ohai'"]}`