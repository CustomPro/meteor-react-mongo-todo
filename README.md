# meteor-react-mongo-todo
Meteor, Mongo and React demo


>mkdir meteor

>cd meteor

>meteor create meteor-react-mongo-todo

>git clone https://github.com/csjcode/meteor-react-mongo-todo.git meteor-react-mongo-todo2

>cp -Rf meteor-react-mongo-todo2/* meteor-react-mongo-todo

>cd meteor-react-mongo-todo

>atom .

>meteor npm install

>meteor

>meteor npm install --save react react-dom

2.2  Replace starter HTML code (see file changes)

delete client/main.js

2.3  Replace starter JS - client/main.jsx

2.4  Create App component - imports/ui/App.jsx

2.5  Create Task component - imports/ui/Task.jsx

Replace main.css with this code

3.1  Create tasks collection - imports/api/tasks.js

3.2  Load tasks collection on the server - server/main.js

> meteor npm install --save react-addons-pure-render-mixin

> meteor add react-meteor-data

3.4  Modify App component to get tasks from collection - imports/ui/App.jsx

>meteor mongo

>db.tasks.insert({ text: "Hello world!", createdAt: new Date() });

4.1  Add form for new tasks

4.2  Add handleSubmit method to App component - imports/ui/App.jsx - Listening for events in React ReactDOM.findDOMNode, inserting into a collection

4.3  Update data container to sort tasks by time

5.1  Update Task component to add features
