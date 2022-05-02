# Onboarding-tutorial

To compile the daml code, start the sandbox, and launch navigator do:

```sh 
cd onboarding-tutorial
daml start
```

To regenerate the workflow diagrams, do 
```sh
cd onboarding-tutorial
daml damlc visual .daml/dist/passport-0.0.1.dar --dot passport.dot
dot -Tpng passport.dot o passport.png
```

