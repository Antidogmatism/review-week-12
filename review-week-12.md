<!-- //1:) -->
import { React } from 'react'
import { Welcome} from './components/Welcome'
import './index.css'

function App() {
  

  return (
    <h1>Welcome to React!</h1>
   
      
    
  )
}

export default App

<!-- //2:) -->
import { React } from 'react'
import { HelloWorld} from './components/HelloWorld'

import './index.css'

function App() {
  

  return (
   <p>Hello</p>
   <p>World</p>
   
      
    
  )
}

export default App
<!-- //3:) -->
import { React } from 'react'
import { ProfilePicture } from './components/ProfilePicture'
import './index.css'

function App() {
  

  return (
   <img src='../assets/images/profile-picture.jpg' alt='The users profile picture'><img/>
   
      
    
  )
}

export default App
<!-- //4:) -->
import { React } from 'react'
import { Welcome} from './components/Welcome'
import './index.css'

function App() {
            const name = "John Doe";
             const age = "30";

  return (
    <p>name</p>
    <p>age</p>
   
      
    
  )
}
<!-- //5:) -->
const apple = () => {
  return <li>Green Apple</li>;
};

const ShoppingList = () => {
  return (
    <section>
      <h1>Apples</h1>
      <apple />
      <apple />
      <apple />
    </section>
  );
};
<!-- I think it should work -->

<!-- //6:) -->
import { React } from 'react'
import { TableOfContents } from './components/TableOfContents'
import './index.css'

export function TableOfContents(props) {

    return (

    )
}
<!-- //7:) -->





<!-- //8:) -->
const ShoppingList = () => {
  return (
    <h2>Shopping List</h2>
    <ul>
      <li>Apples</li>
      <li>Bananas</li>
      <li>Oranges</li>
    </ul>
  );
};
<!-- I think its correct. it will list Apples, Bananas, Oranges -->


<!-- //9:) -->

const Summary = () => {
  return (
      <div class="title">
        <h1>My Site!</h1>
      </div>
      <p class="description">
        You can find my thoughts here
        And I have plenty of them!
      </p>
  );
}
<!-- //10:) -->

import { React } from 'react'
import { Greeting } from './components/Greeting'
import './index.css'

function App() {
  

  return (
    <WhereAreWe
    station="London" weather="the weather is sunny"
    />
      
    
  )
}

export default App


