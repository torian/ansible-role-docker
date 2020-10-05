# Ansible Role for Docker Changelog

## 2020-10-20: 0.4.0

- Add docker credential helper for ECR
- Add docker client config var (`docker_client_config`) to configure client
  settings. Takes a YAML definition that is translated to json
- Apply linting

## 2017-07-10: 0.3.0

  - Docker configuration (json) through the variable `docker_daemon_config`

## 2017-03-17: 0.2.1

  - Ansible lint - Fixed trailing whitespaces
  - Ansible lint - Fixed bare vars in `with_items` loop

## 2016-06-08: 0.2.0

  - Bugfix: use ansible_distribution_release and ansible_os_release
    to enable apt repos to use the correct distribution

## 2016-06-08: 0.1.0

  - Initial release

