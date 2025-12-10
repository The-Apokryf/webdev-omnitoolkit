# WebDev OmniToolkit

> common tasks and standard procedures while making webapps, frontends, backends and other stuff we do around web hostings


---

# containerised

### Building and running your application

When you're ready, start your application by running:
`docker compose up --build`.

### Deploying your application to the cloud

First, build your image, e.g.: `docker build -t myapp .`.
If your cloud uses a different CPU architecture than your development
machine (e.g., you are on a Mac M1 and your cloud provider is amd64),
you'll want to build the image for that platform, e.g.:
`docker build --platform=linux/amd64 -t myapp .`.

Then, push it to your registry, e.g. `docker push myregistry.com/myapp`.

Consult Docker's [getting started](https://docs.docker.com/go/get-started-sharing/)
docs for more detail on building and pushing.

---

# referals

- https://gist.github.com/Sarverott/a9933eea3dd0e4fc54e8ff275bd79dcf
