# Packages && Libraries

<table>
<tr>
<th>React Query</th>
<th>Resources</th>
</tr>
<tr>
<td>

### Query Config

```
const queryConfig: DefaultOptions = {
 queries: {
   refetchOnWindowsFocus: false,
   retry: false,
   cacheTime: 0
 }
}
```
 
### useQuery
 
```
const useSomething = (...params): QueryObserverResult<TData, TError> => {
 const fetch: QueryFunction<T> = async () => return; //TData
 
 return useQuery(['key', ...params], fetch, {
  enabled: true, 
  cacheTime: 5 * 1000 * 60, 
  staleTime: 5 * 1000 * 60
 })
}

const {data} = useSomething(...params)
```

### useMutation
 
```
const useSomethingValidate = (): UseMutationResult<TData, TError, TVariables> => {
 return useMutation<TData, TError, TVariables>( async (variables) => {
   return; // TData
 }
}

await useSomethingValidate().mutateAsync({...variables})
```
  
</td>
<td>

### React Query
 * #### [useQuery](https://react-query.tanstack.com/reference/useQuery)
 * #### [useMutation](https://react-query.tanstack.com/reference/useMutation)

### i18Next
 * #### [i18Next Repo](https://github.com/yeged/React-i18next)

### Mock Service Worker
* #### [Msw Getting Started](https://mswjs.io/docs/getting-started/install)
* #### [Msw Examples](https://github.com/mswjs/examples)

### Recoil
 * #### [Recoil Repo](https://github.com/yeged/React-Recoil)

### Styled Components
* #### [Styled Components Repo](https://github.com/yeged/React-Styled-Components)

### Npm Serve
 * #### [Static Server](https://create-react-app.dev/docs/deployment/#static-server)
```
"scripts": {
    "prod": "npm run-script build 
    && serve -s build"
}
```
</td>

</table>


# Resources

# Styling

* ### [Design Systems](https://fem-design-systems.netlify.app/)

<table>
<tr>
<th>Assets</th>
<th>React Styling && Packages</th>
<th>Tailwind Css</th>
</tr>
<tr>
<td>
 
* #### [CSS Button Generator](https://www.css3buttongenerator.com/)
* #### [Social Buttons for Bootstrap](https://lipis.github.io/bootstrap-social/)
* #### [Icons: the noun project](https://thenounproject.com/)
* #### [Pure CSS Social Media Icons](https://codepen.io/laurenclark/pen/hGiqo)
* #### [Illustrations: undraw](https://undraw.co/illustrations)
* #### [Fonts](https://fonts.google.com/specimen/Roboto)
* #### [CSS Font Stack](https://www.cssfontstack.com/)
* #### [Color Generator: coolors](https://coolors.co/)
* #### [Figma](https://www.figma.com/file/SUmUcxBaV4hnxqsUemiT6r/Buttons?node-id=1%3A383)
* #### [Discover the world???s top designers & creatives: dribble](https://dribbble.com/)
  
</td>
<td>
  
* #### [Styled Components](https://styled-components.com/)
* #### [Styled Comp Repo](https://github.com/yeged/React-Styled-Components)
* #### [Material Icons](https://material-ui.com/components/material-icons/)
* #### [Polished js](https://polished.js.org/)
* #### [React Strap(bootstrap)](https://reactstrap.github.io/components/alerts/)
  
### Animation Package
* #### [React Spring](https://react-spring.io/)
* #### [React Spring: useTransition example](https://codesandbox.io/s/fem-react-spring-exercises-forked-vvheu)

  
</td>
  <td>
</td>
</table>


# Courses - IDEs - Packages - Servers

<table>
<tr>
<th>Free Code Camp</th>
<th>Courses</th>
<th>IDEs</th>
<th>External Packages</th>
<th>Live Preview</th>
</tr>
<tr>
<td>
  
* #### [Frontend Libraries](https://www.freecodecamp.org/learn/front-end-libraries/)
* #### [Js Algorithms](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/)
* #### [Responsive Web Design](https://www.freecodecamp.org/learn/responsive-web-design/)
* #### [Web Developer Portfolios](https://www.freecodecamp.org/news/15-web-developer-portfolios-to-inspire-you-137fb1743cae/)
* #### [Fetch Data](https://www.freecodecamp.org/news/fetch-data-react/)
  
</td>
<td>
  
* #### [JS DOM Events Course](https://egghead.io/lessons/javascript-introduction-to-the-dom-events-course)
* #### [30 Days Of React](https://www.newline.co/fullstack-react/30-days-of-react/)
* #### [FreeCodeCamp](https://www.freecodecamp.org/)
* #### [Frontendmasters](https://frontendmasters.com/)
* #### [Coursera](https://www.coursera.org/)
* #### [Scrimba](https://scrimba.com/)
* #### [WesBos/Courses](https://wesbos.com/courses)
* #### [WesBos](https://courses.wesbos.com/account)

  
</td>
  <td>
    
* #### [Codesandbox](https://codesandbox.io/)
* #### [Codepen](https://codepen.io/)
* #### [Repl-it](https://replit.com/)
* #### [Codeply](https://www.codeply.com/)
    
</td>
  <td>
    
### Routers
* #### [React Router Quick Start](https://reactrouter.com/web/guides/quick-start)
* #### [Reach Router Tutorial](https://reach.tech/router/tutorial/02-installation)
    
### Redux
* #### [Redux Fundamentals, Part 5: UI and React](https://redux.js.org/tutorials/fundamentals/part-5-ui-react)
* #### [React Redux Blog](https://blog.jakoblind.no/react-redux-hooks/)
* #### [React Redux Form](https://davidkpiano.github.io/react-redux-form/docs.html)
* #### [Redux Thunk](https://stackoverflow.com/questions/50059724/how-do-i-resolve-actions-must-be-plain-objects-use-custom-middleware-for-async/54066862)

</td>
  
<td>

* #### [Vercel](https://vercel.com/dashboard)
* #### [Netlify](https://www.netlify.com/)
* #### [Heroku](https://www.heroku.com/)
    
</td>
</table>


# Web Development

* ### [App Brewery: Web Development Resources](https://www.appbrewery.co/p/web-development-course-resources/)
<table>
<tr>
<th>React</th>
 <th>Forms && Validations</th>
 <th>Testing</th>
</tr>
<td>

* #### [Brian Holt: Complete intro to React -v6 Repo](https://github.com/btholt/citr-v6-project)
* #### [React Hooks Examples](https://codesandbox.io/s/reverent-hellman-6pbp8)
* #### [Use Effect vs componentDidMount](https://stackoverflow.com/questions/53945763/componentdidmount-equivalent-on-a-react-function-hooks-component)
* #### [Portals](https://tr.reactjs.org/docs/portals.html)
* #### [Portal Modal Example](https://github.com/yeged/Adopt-Me-with-React/blob/master/src/Modal.js)
* #### [use Context API](https://tr.reactjs.org/docs/context.html)

</td>
 <td>

* #### [Formik](https://formik.org/)
* #### [React Hook Form](https://react-hook-form.com/)
  ### Validation Schema
* #### [Yup](https://www.npmjs.com/package/yup?activeTab=readme)
* #### [Joi](https://www.npmjs.com/package/joi)

</td>
  <td>
  
* #### [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
  ### Test Runners
* #### [Jest.js](https://jestjs.io/)
* #### [Enzyme.js](https://enzymejs.github.io/enzyme/)
  ### E2E
* #### [Puppeteer](https://pptr.dev/)

</td>
</table>


# Others

<table>
<tr>
<th>Fun</th>
<th>Extra</th>
</tr>
<tr>
<td>

* #### [Drive And Listen](https://driveandlisten.herokuapp.com/)
* #### [Internet Live Stats](https://www.internetlivestats.com/)
* #### [Wayback Machine](https://web.archive.org/)
* #### [sha256 Hash Generator](https://passwordsgenerator.net/sha256-hash-generator/)
* #### [Rehber Bul](https://rehber-2e983.web.app/)

</td>
 <td>
  
* #### [Any API](https://any-api.com/)
* #### [daily.dev](https://chrome.google.com/webstore/detail/dailydev-the-homepage-dev/jlmpjdjjbgclbocgajdjefcidcncaied)
* #### [dev.to](https://dev.to/)
* #### [Binary Search Tree](https://www.cs.usfca.edu/~galles/visualization/BST.html)
* #### [Minify](https://www.minifier.org/)
* #### [Unicode Table](https://unicode-table.com/)
* #### [Log Rocket](https://logrocket.com/)
 </td>
</table>





* #### []()
* #### []()
