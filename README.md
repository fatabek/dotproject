# dotProject

Modernized dotProject for PHP 8.4 and MariaDB 11 while preserving the original ACL model, workflow and simplicity.

## Project Goals

- PHP 8.4 compatibility
- MariaDB 11 compatibility
- Preserve original ACL model
- Preserve original project hierarchy
- Preserve original workflow
- Keep the core lightweight and maintainable

## Core Modules

- Users
- ACL
- Companies
- Projects
- Tasks
- Task Logs
- Contacts

## Deferred Modules

The following modules are not a priority for the initial release:

- Files
- Calendar
- Tickets

### Files

A built-in file management system is not a project goal.

Future work may include integration with external file storage systems through links and references.

### Calendar

A built-in calendar is not a project goal.

Future work may include synchronization with external CalDAV servers.

### Contacts

Contacts will remain available for compatibility with the existing dotProject architecture.

No major enhancements are planned except maintenance and security fixes.

## Future Integrations

Potential future integrations:

- CalDAV
- OpenID Connect
- External file storage providers

## Project Philosophy

Modern infrastructure.

Classic dotProject workflow.

Preserve the original ACL model.

Preserve the original user experience whenever possible.

Modernize the platform without changing what made dotProject useful.
