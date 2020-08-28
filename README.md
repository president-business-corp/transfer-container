# import-from-docker

Pull any package from Docker over to GitHub Container Registry (GHCR) for use.

![Screen Shot 2020-08-28 at 3 42 48 PM](https://user-images.githubusercontent.com/2134/91620558-21f5e600-e945-11ea-9b5c-76ae552b4da4.png)

Go to the [Docker Hub Pull Action](https://github.com/president-business-corp/import-from-docker/actions?query=workflow%3A%22Docker+Hub+Pull%22) and click *Run Workflow* to see the options available.

- *Old Image Name* is the image from Docker Hub `clarkbw/foo`
- *Version* is the image version, like `latest` for `clarkbw/foo:latest`
- *New Image Name* is the new image name under GHCR which looks like `ACCOUNT/IMAGE_NAME:VERSION`
