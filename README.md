# ALX System Engineering & DevOps

A collection of shell scripting exercises from the ALX system engineering and DevOps curriculum.

## Topics covered

- Shell basics and filesystem navigation
- Linux file permissions
- Shell redirection and pipelines
- Shell variables and expansions

## Repository structure

| Directory | Focus |
|---|---|
| `0x00-shell_basics/` | Basic shell commands and filesystem operations |
| `0x01-shell_permissions/` | Users, groups, permissions, and ownership |
| `0x02-shell_redirections/` | Redirection, pipes, filters, and text processing |
| `0x03-shell_variables_expansions/` | Variables, aliases, expansions, and shell behavior |

## Running scripts

Most exercises are intended to run in a POSIX-compatible shell such as Bash. From the repository root:

```bash
chmod +x path/to/script
./path/to/script
```

Some exercises are deliberately written to teach specific shell behavior. Avoid changing them merely for style when doing so would obscure the original learning objective.

## Security and hygiene

Shell scripts can execute commands with the permissions of the current user. Review a script before running it, especially when it accepts external input or performs filesystem operations.

Do not commit passwords, private keys, API tokens, shell history, editor swap files, or generated artifacts.

## Learning approach

The exercises are preserved as coursework and are intended to build practical Linux, shell, and systems knowledge incrementally.
