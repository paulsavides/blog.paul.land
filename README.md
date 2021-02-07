[![Build Status](https://dev.azure.com/paulsavides/paulsavides.com/_apis/build/status/builds/StaticSites%20-%20blog.paul.land?repoName=StaticSites&branchName=master)](https://dev.azure.com/paulsavides/paulsavides.com/_build/latest?definitionId=54&repoName=StaticSites&branchName=master)

# Local Setup
## Installing Dependencies
**Installing Hugo** open admin command prompt and run:
```
choco install hugo -confirm
```

## Pulling Submodules
Run the following in your command prompt:
```
git submodule init
git submodule update
```

## Creating Static Site
Make certain you are in the root of this repository and run:
```
hugo
```

That will build the site and publish it to `/public`

run `hugo -h` to view extra options for the cli