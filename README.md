# Ansible Role: PHP-XHProf

[![Build Status](https://travis-ci.org/revagomes/ansible-role-php-xhprof.svg?branch=master)](https://travis-ci.org/revagomes/ansible-role-php-xhprof)

Installs PHP [XHProf](http://php.net/manual/en/book.xhprof.php) on Linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    TODO

## Dependencies

  - nbz4live.php-fpm
  - revagomes.php-pecl

## Example Playbook

    - hosts: webservers
      roles:
        - { role: revagomes.php-xhprof }


## License

MIT / BSD

## Author Information

This role was created in 2015 by [Renato Vasconcellos Gomes](http://revagomes.com.br/).