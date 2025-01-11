# Setup the environment of NUXT

NUXT is based on vue, and you can use vue toolchina to do the nuxt development.

## Play online
you can use online environment to quick start without install local development environment.

1. codesandbox https://codesandbox.io/p/sandbox/github/nuxt/starter/tree/v3/
2. stackblitz https://stackblitz.com/github/nuxt/starter/tree/v3

## Nuxi
Nuxi is the nuxt command interface, you can use npm or similiar package manager to run this tools.

```bash
npx nuxi --help
```

  COMMAND

OPTIONS

  --cwd=<directory>    Specify the working directory

COMMANDS

        add    Create a new template file.
    analyze    Build nuxt and analyze production bundle (experimental)
      build    Build Nuxt for production deployment
    cleanup    Clean up generated Nuxt files and caches
       _dev    Run Nuxt development server (internal command to start child process)
        dev    Run Nuxt development server
   devtools    Enable or disable devtools in a Nuxt project
   generate    Build Nuxt and prerender all routes
       info    Get information about Nuxt project
       init    Initialize a fresh project
     module    Manage Nuxt modules
    prepare    Prepare Nuxt for development/build
    preview    Launches Nitro server for local testing after nuxi build.
      start    Launches Nitro server for local testing after nuxi build.
       test    Run tests
  typecheck    Runs vue-tsc to check types throughout your app.
    upgrade    Upgrade Nuxt

Use nuxi <command> --help for more information about a command.

we can use Nuxi command to intial the nuxt project

```bash
pnpm dlx nuxi init 
```
it will ask a few question, and initialized the code repository and you can start you code with nuxt now.

