# References


useEffect(() => {
        console.log('Component mounted');
        return () => {
            console.log('Component will be unmount')
        }
    }, []); # notice the empty array here, this is optional


react hooks:
https://medium.com/benextcompany/refactoring-react-class-components-to-typescript-functional-components-with-hooks-a4f42b2bd7b5

typescript passing props to child comp (function component):
prefer this only : https://stackoverflow.com/questions/61432089/react-typescript-how-send-props-and-use-it-in-child-component
reference : https://dev.to/mconner89/passing-props-in-react-using-typescript-20lm


datepicker error:
12.34 gs toolkit version.
npm install jquery


Fetch API and Promises:
This tells about Promise(reject, response):
https://codeburst.io/the-es6-promises-87a979ab27e4


resolve localhost certficate error: chrome flags edit:
https://stackoverflow.com/questions/47700269/google-chrome-localhost-neterr-cert-authority-invalid


get client IP address:
using geolocation-db.com.
https://stackoverflow.com/questions/49257729/retrieving-the-client-request-ip-address


async issue within React useEffect Hooks:
setState is async.
https://stackoverflow.com/questions/55521912/multiple-fetch-data-axios-with-react-hooks

handling async errors:
https://www.valentinog.com/blog/await-react/





optimisations for add-user:
1 - include redux?
2 - bage page link to is fine? any optimisation need to be done? 
3 - Add Form code optim.
4 - error handling.
