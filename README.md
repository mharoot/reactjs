# reactjs


<table>
 <thead>
    <tr>
        <th width="100%"><h3>What is React?</h3></th>
    </tr>
  </thead> 
    <tbody>
        <tr>
            <td>
            <p>React is a UI library developed at Facebook to facilitate the creation of interactive, stateful &amp; reusable UI components. It is used at Facebook in production, and Instagram.com is written entirely in React.  </p>
            <p>One of it's unique selling points is that not only does it perform on the client side, but it can also be rendered server side, and they can work together inter-operably.</p>
            <p>It also uses a concept called the Virtual DOM that selectively renders subtrees of nodes based upon state changes. It does the least amount of DOM manipulation possible in order to keep your components up to date.</p>
            </td>
        </tr>
    </tbody>
</table>

<table>
 <thead>
    <tr>
        <th width="100%"><h3>How does the Virtual DOM work?</h3></th>
    </tr>
  </thead> 
    <tbody>
        <tr>
            <td>
            <p><span>    </span>Imagine you had an object that you modeled around a person. It had every relevant property a person could possibly have, and mirrored the persons current state. This is basically what React does with the DOM.</p>
            <p><span>    </span>Now think about if you took that object and made some changes. Added a mustache, some sweet biceps and Steve Buscemi eyes. In React-land, when we apply these changes, two things take place. First, React runs a "diffing" algorithm, which identifies what has changed. The second step is reconciliation, where it updates the DOM with the results of diff.</p>
            <p><span>    </span>The way React works, rather than taking the real person and rebuilding them from the ground up, it would only change the face and the arms. This means that if you had text in an input and a render took place, as long as the input's parent node wasn't scheduled for reconciliation, the text would stay undisturbed.</p>
            <p><span>    </span>Because React is using a fake DOM and not a real one, it also opens up a fun new possibility. We can render that fake DOM on the server, and boom, server side React views.</p>
            </td>
        </tr>
    </tbody>
</table>





<table>
 <thead>
    <tr>
        <th width="100%"><h3>Getting Started</h3></th>
    </tr>
  </thead> 
    <tbody>
        <tr>
            <td>
            <p>Getting started with React is as simple as downloading their provided starter kit: <a href="https://facebook.github.io/react/downloads/react-0.11.2.zip">React Starter Kit</a></p>
            </td>
        </tr>
    </tbody>
</table>

<table>
 <thead>
    <tr>
        <th width="100%"><h3>Getting Started Using NPM</h3></th>
    </tr>
  </thead> 
    <tbody>
        <tr>
            <td>
            <p><h4>Step 1 - Install Global Packages</h4></p>
            <p>You will need to install several packages for this setup. We will need some of the babel plugins so let's first install babel by running the following code in command prompt window:</p>
            <p>sudo npm install -g babel babel-cli</p>
            </td>
        </tr>
        <tr>
            <td>
            <p><h4>Step 2 - Add Dependencies and plugins</h4></p>
            <p>
            You will need to install several packages for this setup. We will need some of the babel plugins so let's first install babel by running the following code in command prompt window:</p>
            <p>npm install webpack webpack-dev-server react react-dom babel-core babel-loader babel-preset-react babel-preset-es2015 --save</p>
            </td>
        </tr>
        <tr>
            <td>
            <p><h4>Step 3 - Create files </h4></p>
            <p>
            touch index.html app.jsx main.js webpack.config.js
            </p>
            </td>
        </tr>
    </tbody>
</table>


<table>
 <thead>
    <tr>
        <th width="100%"><h3>Page Setup</h3></th>
    </tr>
  </thead> 
    <tbody>
        <tr>
            <td>
            <p>When setting up your page, you want to include react.js and JSXTransformer.js, and then write your component in a script node with type set to text/jsx:</p>
            <p><a class="btn btn-primary" href="https://github.com/mharoot/reactjs/tree/master/react-starter-kit/templates">Get Skeleton page here</a></p>
            </td>
        </tr>
    </tbody>
</table>


            






<!-- template

<table>
 <thead>
    <tr>
        <th width="100%"><h3> </h3></th>
    </tr>
  </thead> 
    <tbody>
        <tr>
            <td>
            <p>


            </p>
            <p>


            </p>
            <p>


            </p>
            </td>
        </tr>
    </tbody>
</table>
  -->