# gitlab-firebase
Builds an image for deploying Firebase functions with gitlab CI

# Deployoing image

A new version of the image is deployed to docker hub everytime a commit is added to a branch.

A commit to master will build a new version of the `latest` tag.

For all other branches, it will deploy an image tagged with the branch name. eg. pushing to `foobar` branch will trigger a new image tag `foobar` in docker hub