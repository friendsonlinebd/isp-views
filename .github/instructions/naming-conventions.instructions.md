---
description: "Use when writing or editing PHP, JavaScript, or any code in this project. Enforces camelCase naming for variables, functions, and methods."
applyTo: "**/*.php,**/*.js"
---
# Naming Conventions

- Use **camelCase** for all variable names, function names, and method names.
  ```php
  // correct
  $userName = 'John';
  function getUserData() {}

  // wrong
  $user_name = 'John';
  function get_user_data() {}
  ```
- Classes use **PascalCase** (unchanged).
- Database column names and HTML `id`/`name` attributes are exempt — use whatever the schema or markup requires.
