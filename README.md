### Pulling Submodules
Run the following in your command prompt:
```
git submodule init
git submodule update
```

### Installing Dependencies
**Installing Hugo** open admin command prompt and run:
```
choc install huge -confirm
```

### Creating Static Site
Make certain you are in the root of this repository and run:
```
hugo
```

That will build the site and publish it to `/public`

run `hugo -h` to view extra options for the cli