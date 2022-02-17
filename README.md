# Virtual-method-handler

Virtual method handler for an OOP system implementing simple inheritance and dynamic method dispatch.

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