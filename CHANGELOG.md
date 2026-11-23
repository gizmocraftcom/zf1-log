# Changelog

## 2.0.0

Fork of `diablomedia/zendframework1-log`, published as `gizmocraft/zendframework1-log`.

### Breaking changes

- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-log` to `gizmocraft/zendframework1-log`. It now requires `gizmocraft/zendframework1-exception` `^2.0.0`, `gizmocraft/zendframework1-config` `^3.0.0` and `gizmocraft/zendframework1-loader` `^2.0.0`.
- The suggestion of `zendframework1-log-writer-firebug` (Zend_Wildfire based, not part of the gizmocraft forks) is dropped. `Zend_Log_Formatter_Firebug` is still included and does not depend on Zend_Wildfire.

### Other changes

- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 attributes. CI runs PHP 8.5 and 8.6.
- No library code changes and no public signature changes.
