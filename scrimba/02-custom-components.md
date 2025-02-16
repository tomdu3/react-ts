1. What is a React component?
   A function that returns React elements. (UI)

2. What's wrong with this code?

```
function myComponent() {
    return (
        <small>I'm tiny text!</small>
    )
}
```

- the name of the component should be in PascalCase, in this case `MyComponent`.

3. What's wrong with this code?

```
function Header() {
    return (
        <header>
            <img src="./react-logo.png" width="40px" alt="React logo" />
        </header>
    )
}

root.render(Header())
```

- the rendering of the component is wrong, it should be `root.render(<Header />)`
