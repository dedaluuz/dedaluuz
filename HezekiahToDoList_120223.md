# Hezekiah's To-Do List
# [12/02/23]

- Follow guide to set up app secrets in secrets manager for development and azure key vault in production
  - *Azure Key Vault configuration provider in ASP.NET Core* from 11/09/23 - https://learn.microsoft.com/en-us/aspnet/core/security/key-vault-configuration?view=aspnetcore-7.0
- Do database stuff
  - Concurrency [This will take a long time!] [p480-481]
    - add rowversion field to all tables + add as hidden field in views n such
    - add try catch statements to all database operations to catch concurrency exceptions
  - Referential integrity (i.e. make sure all add, edit, delete operations work properly)