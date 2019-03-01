# Portfolio Notes

The intent of this file is to track notes, design decions, and resources as I work on this portfolio

## March 1st 2019

### Initial project set up

Setting up git repository https://github.com/KevinBrack/Portfolio

Initializing npm project, blank for now but I intend on using a custom Express server, to both serve the static pages that will be used in the site as well as any endpoints I would need to transfer data to the front end.

When done, and while in progress I will be deploying the node application in a Docker container to the droplet I have stored on Digital Ocean.

Domain purchased from Google domains. Domain points to droplet on Digital Ocean, so essentially the container I install that exposes port 80 will be the site represented at https://kevinbrack.com

I still need to add an ssl certificate to the site. Because I did not use a domain purchased and managed by Digital Ocean directly, I am unelegible for the built in tooling, that would automatically generate and install a cert from Let's Encrypt. I will work through the instructions for a manual install provided at Let's Encrypt at some point in the near future.

### Initial design thoughts
