
cd my-react
npx create-react-app my-react
yarn install


yarn add react-router-dom

(src/App.js)

[import {
  createBrowserRouter,
  RouterProvider,
} from "react-router-dom";

const router = createBrowserRouter([
  {
    path: "/",
    element: <span>Home</span>,
  },
  {
    path: "/products/:id",
    element: <span>Category</span>,
  },
  {
    path: "/products/:id",
    element: <span>product</span>,
  },
])

function App() {
  return (
    <div>
      <RouterProvider router={router} />
    </div>
  );
}

export default App; ]


