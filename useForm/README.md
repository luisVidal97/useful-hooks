# useForm

Example of use:
````
    const initialForm= {
        name:'',
        age:'',
        email:''
    };
    const [formValues, handleInputChange, reset ] = useForm(initialForm);
````