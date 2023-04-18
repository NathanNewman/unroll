### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
  - React Router is a single page application used for browser based routing without a page refresh.
- What is a single page application?
  - A web application that dynamically renders it's content on a single page.

- What are some differences between client side and server side routing?
  - Location. Server side routing takes place on the server where as client side routing takes place in the browser.
  - Server side routing requires a page refresh to update information, unless a web socket is used.
  - Server side routing has direct access to a database.
  - Client side routing is generally faster.

- What are two ways of handling redirects with React Router? When would you use each?
  - Declarative Redirects use the Redirect component. They are used when a user navigates to a URL
  and needs to be navigated to different one.
  - Programmatic Redirects use the useHistory hook to redirect users to a different URL. They are
  used when a redirect is based on a dynamic condition.

- What are two different ways to handle page-not-found user experiences using React Router? 
  - Place a route with no path as the last route within a Switch component. Make sure the route
  has a defined 404 component.
  - Use redirect to redirect to a custom 404 page.

- How do you grab URL parameters from within a component using React Router?
  - use the hook useParams

- What is context in React? When would you use it?
  - Context is a way for components to pass data. Its global data available to all components.
  - It is used to pass data to components that aren't connected in the component hierarchy.
  - It is used to avoid prop drilling.

- Describe some differences between class-based components and function
  components in React.
  - Class-based components use lifecycle methods such as componentDidMount or componentDidUpdate
  - Functional components use hooks such as useState and useEffect.
  - Class-based components tend to be more complexed than functional components.
  - Functional components are currently generally more prefered that class-based components.

- What are some of the problems that hooks were designed to solve?
  - To give state to functional components.
  - To simplify code, as functional components are generally simpler than class-based components.
  - To improve performance as functional components are generally faster than class-based components.