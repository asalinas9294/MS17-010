# MS17-010 - zzz_eploiat modifiation

This repo is a fork of Worawit's MS17-010 repo. contains a slightly modified version of zzz_exploit.py which includes support for command line args for username, password, and payload.

Currently, payloads are appended as a command in the form: `service_exec(conn, r'cmd /c ' + PAYLOAD)`.
