# temp_checks


useEffect(() => {
        console.log('Component mounted');
        return () => {
            console.log('Component will be unmount')
        }
    }, []); # notice the empty array here, this is optional


react hooks:
https://medium.com/benextcompany/refactoring-react-class-components-to-typescript-functional-components-with-hooks-a4f42b2bd7b5
