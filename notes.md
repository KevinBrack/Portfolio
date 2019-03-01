# Portfolio Notes

The intent of this file is to track notes, design decions, and resources as I work on this portfolio

## March 1st 2019

### Initial Project Set Up

Setting up git repository https://github.com/KevinBrack/Portfolio

Initializing npm project, blank for now but I intend on using a custom Express server, to both serve the static pages that will be used in the site as well as any endpoints I would need to transfer data to the front end.

When done, and while in progress I will be deploying the node application in a Docker container to the droplet I have stored on Digital Ocean.

Domain purchased from Google domains. Domain points to droplet on Digital Ocean, so essentially the container I install that exposes port 80 will be the site represented at https://kevinbrack.com

I still need to add an ssl certificate to the site. Because I did not use a domain purchased and managed by Digital Ocean directly, I am unelegible for the built in tooling, that would automatically generate and install a cert from Let's Encrypt. I will work through the instructions for a manual install provided at Let's Encrypt at some point in the near future.

### Initial Design Thoughts

#### Color Palette

As with most of my design projects the first thing I look at pinning down is a color scheme to drive the rest of the design process. I have a few ways I go about this, and some sites I have used in the past, but this time a simple Google search for color palettes, led to an image that caught my eye. On further inspection it led to this blog post where I found my ultimate decision.

https://digitalsynopsis.com/design/minimal-web-color-palettes-combination-hex-code/

I will be going with 4 out of the 5 colors presented in sample #4 plus white, maybe black.

#### Overall Asthetic.

For the most part my inspiration for the design of this project is going to be contrast.

- A 90% flat UI with slight 3D parralax, and the ocasional 3D background object.
- A 80% greyscale color shcheme with a single ultra vibrant off-red.
- Overall neutral backgrounds with the ocasional pattern.
- A landing portion with the solid off-red background for maximum impact.

As opposed to the current trend of a Call To Action as the landing, I am going to try to use svg vector animation to create a landing reminescent of the early 2000's flash landing page, while maintaining speed, low load times, smooth animation, and responsive adaptiveness.
