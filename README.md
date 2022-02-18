# Virtual-method-handler

Virtual method handler for an OOP system implementing simple inheritance and dynamic method dispatch.

This is an interactive program. Instructions follow.

* `CLASS <type> [<name>]`: This creates a new type `<type>` whose methods are named in the list `[<name>]`. `<type>` can be either a simple name (a type that doesn't inherit from any other) or an expresion of the form `<name> : <super>` where `<super>` indicates that `<name>` inherits from `<super>`. 
* `DESCRIBIR <name>`: Describes the type `<name>` by displaying its virtual method table.
* `SALIR`: exit program.

## Testing instructions

To test IO:

```bash
cabal clean  
cabal build 
cabal test 
```

For coverage tests do:

```bash
cabal clean

cabal configure --enable-tests --enable-coverage 

cabal test 
```

then check HTML under **./dist/hpc/vanilla/html/**
