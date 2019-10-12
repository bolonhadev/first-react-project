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

Pages_path_x                =>      Index.js > ComponentHEAD ( const's + api.methot('/x', Controller.action ...

Pages_path_x                =>      Index.js > ComponentHEAD ( History.push ? true : false )

Pages_path_x                =>      Index.js > Component_JSX_Return <JSX /> to -> Index.js

Index.js                    =>      ReactDOM.render(<App />, document.getElementById('root')); // new magic RETURN
