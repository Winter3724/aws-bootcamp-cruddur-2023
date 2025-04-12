# Week 1 — App Containerization

 - Linuxserver.io project contains many examples of container images that can be used.
 - DockerHub is a registry for container images.  Free to use.
 - OCI - Open Container Initiative standard.
 - "Scratch" is the base Docker image, an empty image.
 - Docker-compose.yml file:  runs both the front end and backend containers.  Right-click and select "Compose Up".  Select the URL for the front end port to launch the app.

 - Docker top 10 security practices:
   > Keep host & Docker updated with the latest security patches.
   > Run Docker daemon & containers in non-root user mode.
   > Image vulnerability scanning.
   > Trusting a private versus public image registry.
   > No sensitive data in Docker files or images.
   > No secrets stored in the container.
   > File system and volume should be read only.
   > Separate databases for long term storage.
   > Use DevSecOps practices while building app security.
   > Test all code for vulnerabiliteis before promoting to production.

- Snyk OpenSource Security - free tool for scanning container images.
- AWS Inspector and Clair can also scan images.
  


