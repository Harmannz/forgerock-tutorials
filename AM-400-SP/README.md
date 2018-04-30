# AM-400-SP: ForgeRock Access Management: Core Concepts (Self-Paced Learning)

The platform directory contains the environment setup and configuration for ForgeRock Access Manager core concepts tutorial.

## Getting Started

- You need [AM-5.5.1 war](https://backstage.forgerock.com/get/am/am/am-war/5.5.1/) and [Amster](https://backstage.forgerock.com/get/am/amster/amster-zip/5.5.0/) downloaded to the platform/SOURCES directory.

Run `vagrant up` in the platform directory to initialise a vagrant VM.

Place the following to your hosts file:

```hosts
###############################
##### AM-400-SP ForgeRock #####
###############################

10.123.10.2 host.am400sp.harmannz.github.io
10.123.10.3 app.am400sp.harmannz.github.io
```

## Accessing OpenAm

admin username: amadmin

admin password : password