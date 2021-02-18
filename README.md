# temp_checks


useEffect(() => {
        console.log('Component mounted');
        return () => {
            console.log('Component will be unmount')
        }
    }, []); # notice the empty array here, this is optional
