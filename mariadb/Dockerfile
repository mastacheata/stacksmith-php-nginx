## BUILDING
##   (from project root directory)
##   $ docker build -t mariadb-for-mastacheata-stacksmith-php-nginx .
##
## RUNNING
##   $ docker run -p 3306:3306 mariadb-for-mastacheata-stacksmith-php-nginx
##
## CONNECTING
##   Lookup the IP of your active docker host using:
##     $ docker-machine ip $(docker-machine active)
##   Connect to the container at DOCKER_IP:3306
##     replacing DOCKER_IP for the IP of your active docker host
##
## NOTES
##   This is a prebuilt version of MariaDB.
##   For more information and documentation visit:
##     https://github.com/bitnami/bitnami-docker-mariadb

FROM gcr.io/bitnami-containers/mariadb:10.1.22-r1

ENV STACKSMITH_STACK_ID="t6q5uub" \
    STACKSMITH_STACK_NAME="MariaDB for mastacheata/stacksmith-php-nginx" \
    STACKSMITH_STACK_PRIVATE="1" \
    BITNAMI_CONTAINER_ORIGIN="stacksmith"

## STACKSMITH-END: Modifications below this line will be unchanged when regenerating
