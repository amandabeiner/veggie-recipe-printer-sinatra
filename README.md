# Veggie Recipe Printer Sinatra
A refactored version of Launch Academy's HTTP/Sinatra curriculum that puts erb in the context of Sinatra, rather than the command line/small Ruby Scripts.

The `server.rb` file defines the root (`/`) route, and passes along instance variables to `index.erb`. 

You should edit the `index.erb` file to grab these instance variables and display the information about the recipe on the page.

## Setup
To get set up, run the following
```no-highlight
  bundle
  ruby server.rb
```

And navigate to `localhost:4567`
