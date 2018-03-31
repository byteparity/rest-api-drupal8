# rest-api-drupal8
Demo REST api module drupal 8

This module uses basic_auth authentication module to access api resource.

Copy this module to your/drupal/installation/modules directory.
Enable the module.

Curl Code to call the service. (replace your drupal hostname in below command)

curl -X GET \
  'http://yourdrupalhost.com/api/demo_resource?_format=json' \
  -H 'Authorization: Basic YWRtaW46YWRtaW4=' \
  -H 'Cache-Control: no-cache' \
  -H 'Content-Type: application/json' \
  -H 'Postman-Token: 6ee8e333-561c-4dd0-b24b-d9fbe5fdd73e' \
  -H 'user: admin:admin'
