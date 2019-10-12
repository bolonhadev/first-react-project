# first-react-project
My very first react project, taking classes from Rocketseat

# /backend
User request(method)        =>      Server.js

Server.js                   =>      Call routes.js + mydb.nosql + frameworks

Routes.js(request(method))  =>      Routes.method( '/path', xController.actionMethod) ;

Controllers.js              =>      Do.action( method, route, action_on_db) ;

Models.js                   =>      Db_framework( new db_Schema { name: type });

# /frontend

Index.html                  =>      #root

Index.js                    =>      ReactDOM.render(<App />, document.getElementById('root')); // the magic is here

App.js                      =>      JSX > img + Routes
  
Routes.js                   =>      BrowserRouter > Switch > Route's( path='/x' component='x' )

Pages_path_x                =>      Index.js > Dependencies( React + UseStates + UseEffect + React Router DOM ...

Pages_path_x                =>      Index.js > Dependencies ( ... + CSS + img's + ../../services/api ...

Pages_path_x                =>      Index.js > ComponentHEAD ( const's + api.method( '/x', Controller.action ...

Pages_path_x                =>      Index.js > ComponentHEAD ( History.push ? true : false )

Pages_path_x                =>      Index.js > Component_JSX_Return <JSX /> to -> Index.js

Index.js                    =>      ReactDOM.render( App.comp , document.getElementById( 'root' )); // new magic RETURN

# /user

Now we're (_app + api_) ready and waiting for the user interaction.

When the user Enter a URL or hit a button, then a Event happens on the page.

This Event, even the headers, some body part, or a query it's sent to the frontend.

The frontend handle the request (event, method, data, all stuffs).

Now the front can just RENDER something or...

Send that Request to the backend, if necessary, gets the results and made a decision.

This decision can be an history.push(), or just RENDER that something

Voilà ! That's it ! É nóis jão !
