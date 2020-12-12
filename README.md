# stack-templates

![](gang.jpg)

a haskell project skeleton

the main things that make this unique:
- defaulting to AGPL 3+, instead of MIT
- adding a massive amount of extensions to the `default-extensions` field
- adding an `hie.yaml` file

to use this, add this line to stack's config.yaml:
```
default-template: github:ikea-shark-official/skel
```

or call `stack new` using the template name above
