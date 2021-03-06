---
title: How to copy configuration files
---
# How to copy configuration files
The first task you should do after installing Drupal Console is to execute the `init` command. Executing this command will copy the project configurations files to your `~/.console/` directory. Overriding values on these copied files is how you can change DrupalConsole behaviour.
 
 ```
 $ drupal init [--override]
 ```
 
### Which files are copied when executing the `init` command.
```
 ~/.console/ 
  ├── aliases.yml
  ├── chain
  │   ├── create-data.yml
  │   ├── form-sample.yml
  │   ├── quick-start-mysql.yml
  │   ├── quick-start.yml
  │   ├── sample.yml
  │   ├── site-drop-restore.yml
  │   ├── site-install.yml
  │   └── update-gitbook.yml
  ├── commands.yml
  ├── config.yml
  ├── console.rc
  ├── drupal.fish
  ├── phpcheck.yml
  ├── router.php
  ├── site.mode.yml
  └── sites
      └── sample.yml
```