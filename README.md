osx-provisioning
====================

Inspired by [Craig Marvelley](https://github.com/craigmarvelley/macbook-provisioning)

Provision:

```ansible-playbook macbook.yml```

Provisioning work computer?

```ansible-playbook macbook.yml --extra-vars "email=ben@work.com"```

Want to update all brews?

```ansible-playbook macbook.yml --extra-vars "homebrew_update=true"```

