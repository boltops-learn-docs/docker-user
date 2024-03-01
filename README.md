<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/docker-user/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Docker Tutorial: Use Another User Aside From Root

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This tutorial focuses how to create another user as the user to use for the docker container.

* This a considered a best practice that few follow because it's an additional step and we live busy lives.


## Build

    docker build -t boltops/docker-user .

## Run

    docker run boltops/docker-user

## Push

    docker push boltops/docker-user

## Notes

Replace boltops with your own DockerHub username if you are going through the tutorial.

## Video

[![Watch the video](https://uploads-learn.boltops.com/pj4fd12e2nhvpdp3opl5duvls3ol)](https://learn.boltops.com/courses/docker/lessons/docker-use-another-user-aside-from-root)

Note: Premium video content requires a subscription.
