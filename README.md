# Static Portfolio Website

This is a static website that acts as a landing page for basic information regarding my skill set, projects, and resume information.
There are also additional endpoints that are forwarded to a [Django webapp](https://github.com/cmadajski/openai_webapp) that integrates OpenAI services seamlessly into the site.

## Deployment (LIVE)

The static website is currently available [here](http://194.195.210.137/). I have already purchased a proper domain for the site, but
I'm unable to use the domain until my SSL certificates are authorized (my domain uses a .dev extension, which requires SSL). The site is being
served using Nginx, the server is being provided by [Linode](https://www.linode.com/), and the server OS is Fedora Server.

## Future Plans

There are some benefits to having a static site such as reduced latency and increased simplicity. However, for advanced interactions it is
necessary to have a real web application that can leverage logic and access APIs. The long term goal is to replace this static site with 
a Django frontend application that pulls data from a FastAPI backend. This will allow me to automate the publishing of blog posts, 
updating of personal info, and additional integrations. For now, the static site will remain a placeholder until I get those services 
up and running.
