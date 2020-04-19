<p align="center">
  <img src="nodpi.png" alt="NodPI">
</p>

# NodPI
The NodPI [Node + API] is a command-line interface that scaffolds a project or an extension by generating the basic code. The CLI provides the fastest way to get started with a Node API project that adheres to best practices.

## Built for API developers
- Create Project Structure with all basic users api
- Define your API endpoints and schemas
- Create new route in existing project with all basic CRUD functions
 
## See [NodPI](https://node-api.gitbook.io/nodpi/) for documentation and terms.

## Install the CLI globally by running
    npm i -g nodpi
## Usage
    nodpi [option] [name] [folder name optional]

### Eg :
    nodpi p nodeapi [folder name optional] ---    To create new node api project  

    nodpi r users  ---    To create new route with model, controller,service

    nodpi m users [folder name optional] ---    To create new node api model file

    nodpi p users [folder name optional] ---    To create new node api controller file

    nodpi s users [folder name optional] ---    To create new node api service file
