# Rebase the cuda image to mapping correctly with ndivia driver version
- Merged new version we need to to build new docker image
- Version will be using the current version of fooocus with specific cuda version

## Step build
`docker build -t adamduongit/fooocus:2.5.5-12.2.0 . `
`docker push adamduongit/fooocus:2.5.5-12.2.0`