# useForm

Demo:

```
  const inputsForm = {
    username: '',
    password: '',
  }

  const [inputs, handleInputsChange, reset] = useState(inputsForm)

  <input
    type="text"
    value={username}
    onChange={handleInputsChange}
    name="username"
  />
```