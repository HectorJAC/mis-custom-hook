# useForm

Ejemplo de uso:
```
    const initialForm = {
        name: 'Hector',
        age: 20, 
        email: ''
    }
    const [formValues, handleInputChange, reset] = useForm(initialForm);
```