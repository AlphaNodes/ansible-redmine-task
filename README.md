# Ansible Role: redmine-task

Run Redmine tasks for an installed redmine (rake tasks)

- send reminder mails
- receive helpdesk mails (redmine_contacts)
- receive redmine mails
- create recurrent tasks (https://www.redmine.org/plugins/recurring-tasks)
- maintenance tasks (see https://www.redmine.org/projects/redmine/wiki/RedmineRake)

## Dependencies

An installed redmine.

## Example Playbook

    - hosts: server-name
      vars:
        redmine_task_name: reminder
      roles:
        - AlphaNodes.redmine-task

## License

GPL Version 3

## Author Information

This role was created in 2017 by [AlphaNodes](https://alphanodes.com/).
