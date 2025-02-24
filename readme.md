# In EduTex, we need rebase the cuda image to mapping without ndivia driver version
- In case we merged new version we need to to build new docker image
- Version will be using the current version of fooocus with specific cuda version

## Step build
`docker build -t adamduongit/fooocus:2.5.5-12.2.0 . `
`docker push adamduongit/fooocus:2.5.5-12.2.0`