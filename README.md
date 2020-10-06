# Ansible Role: ansible-deploy-drupal

Manages Drupal site deployments.

## Requirements

None.

## Role Variables

See [defaults](defaults/main.yml) for all available variables and accompanying
documentation.

## Example Playbook

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

```yaml
    - hosts: all

      vars:
        deploydrupal_repo: "git@github.com:ChromaticHQ/site.git"

        deploydrupal_checkout_user: "jenkins"
        deploydrupal_apache_user: "www-data"

        deploydrupal_dir: "/var/www/html"
        deploydrupal_code: true

      roles:
        - ansible-deploy-drupal
```

## License

MIT
