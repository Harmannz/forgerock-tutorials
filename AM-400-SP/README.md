# AM-400-SP: ForgeRock Access Management: Core Concepts (Self-Paced Learning)

The platform directory contains the environment setup and configuration for ForgeRock Access Manager core concepts tutorial.

The code here setups you up with an installation of AM (6.0.0) and uses Amster (6.0.0). A basic hello world can also be deployed on a installed wildfly instance.

## Getting Started

Because AM and Amster are proprietary products you will need to download them into platform/SOURCES directory.

You need 
- AM-6.0.0 war 
- Amster-6.0.0 zip

You can download these from https://backstage.forgerock.com/downloads/browse/am/archive



Run `vagrant up` in the platform directory to create the vagrant environment.

Place the following to your hosts file:

```hosts
###############################
##### AM-400-SP ForgeRock #####
###############################

10.123.10.2 host.am400sp.harmannz.github.io
10.123.10.3 web.am400sp.harmannz.github.io
10.123.10.4 app.am400sp.harmannz.github.io

10.123.10.5 sso.am400sp.harmannz.github.io
```


### Links:
Web: https://web.am400sp.harmannz.github.io/app/index.xhtml
- Goes to Apache which proxy passes to the app

AM: http://sso.am400sp.harmannz.github.io:9990/sso/XUI/#login/
- Takes you to AM login. Default username: *amadmin*. Default password: *password*
- Tomcat: http://www.sso.am400sp.harmannz.github.io:9990

Wildfly (13): app.am400sp.harmannz.github.io:9990/
- Takes you to the admin console

