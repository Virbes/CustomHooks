# useForm

Ejemplo de uso:

```javascript
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };

    const [formValues, handleInputChange, reset] = useForm(initialForm);

    const { name, age, email } = formValues;
```

```jsx
 <Input
    required
    type="text"
    name="name"
    placeholder="First Name"
    invalidFeedback="Please enter your first name"
    value={formData.firstname}
    onChange={handleInputChange}
    autoFocus={true}
/>
```
