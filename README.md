# docker-makecatalogs

This is a docker image that will run makecatalogs on a Munki repo. It is designed for use during automated deployments.

## Example

``` bash
docker run --rm -v /var/www/munki_repo:/munki_repo macadmins/makecatalogs
```
