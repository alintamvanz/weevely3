# Change Log

## [Unreleased]
### Fixed
- Connection to HTTPS sites with wrong certificates

## [v3.4] - 2016-11-02
### Fixed
- Stored/Passed/Default arguments handling

### Added
- Backdoor_meterpreter module
- System_procs module by @paddlesteamer
- Support for database/schema selection for PostgreSQL by @caeaguilar

## [v3.3.1] - 2016-05-12
### Fixed
- File grep module wrong grepping folders
- 500 error testing pcntl_fork in shell sh module

### Added
- Clearlog and Mail module by @AppoPro
- Socat vector in backdoor tcp module
- Legacycookie generator
- Upload2web module content and simulate options
- Disable_function bypass module

## [v3.2.0] - 2015-06-29
### Fixed
- Basic Windows support
- OS X support
- Improve Stegaref channel referrer templates
- Reset on channel session variables changes

### Added
- Python requirements.txt
- Encoding support for sql_console
- Output redirection and inverse grep for file_grep
- Run actions on start depending from the session load
- Proxy and SOCKS support
- Unset session variables
- Show session variables

## [v3.1.0] - 2015-04-07
### Added
- Module bruteforce_sql
- Additional HTTP headers
- Direct command execution from weevely.py argument
- Whoami, hostname, pwd, uname aliases
- Module file_cp
- CHANGELOG

## v3.0.0 - 2015-01-17
### Added
- Module sql_dump
- Module sql_console
- Module bruteforce_sqlusers
- Module bruteforce_sql
- Module file_mount
- Module file_enum
- Module file_download
- Module file_touch
- Module file_rm
- Module file_edit
- Module file_read
- Module file_upload
- Module file_upload2web
- Module backdoor_reversetcp
- Module backdoor_tcp
- Module audit_suidsgid
- Module file_find
- Module audit_filesystem
- Module audit_phpconf
- Module audit_etcpasswd
- Module net_phpproxy
- Module net_ifconfig
- Module net_proxy
- Module net_scan
- Module file_grep
- Module net_curl
- Modules file_zip, file_tar, file_gzip, and file_bzip2
- Support of legacy LegacyCookie and LegacyReferrer channels

### Removed
- Module audit_userfiles
- Module audit_mapwebfiles


[unreleased]: https://github.com/epinna/weevely3/commit/HEAD
[v3.1.0]: https://github.com/epinna/weevely3/releases/tag/v3.1.0
[v3.2.0]: https://github.com/epinna/weevely3/releases/tag/v3.2.0
[v3.3.1]: https://github.com/epinna/weevely3/releases/tag/v3.3.1
[v3.4]: https://github.com/epinna/weevely3/releases/tag/v3.4
