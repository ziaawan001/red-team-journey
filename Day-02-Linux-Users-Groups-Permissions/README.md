# Day 2 - Linux Users, Groups & Permissions 🐧

## Topics Covered

- Users in Linux
- Who is the Root User?
- Groups in Linux
- Understanding File and Directory Permissions
- Read, Write, and Execute Permissions
- `chmod` - Changing File and Directory Permissions
- `chown` - Changing File and Directory Ownership
- Common Permission Sets

## Linux Users

Linux is a multi-user operating system where multiple users can work on the same system. Each user can have their own permissions and access levels.

## Root User

The root user is the superuser in Linux. It has the highest level of privileges and can perform administrative tasks across the system.

Root access should be used carefully because incorrect commands can affect the entire system.

## Groups

Groups allow multiple users to be managed together. Instead of assigning permissions to each user individually, permissions can be assigned to a group.

## Understanding Permissions

Linux uses three basic permission types:

- `r` - Read
- `w` - Write
- `x` - Execute

Permissions can be assigned to:

- Owner
- Group
- Others

## chmod

The `chmod` command is used to change the permissions of files and directories.

Example:

```bash
chmod 755 script.sh
chmod 644 file.txt
```

## chown

The `chown` command is used to change the ownership of files and directories.

Example:

```bash
chown user:group file.txt
```

## Common Permission Sets

| Permission | Numeric | Meaning |
|---|---:|---|
| `rwx------` | 700 | Owner has full access |
| `rw-r--r--` | 644 | Owner can read/write, others can read |
| `rwxr-xr-x` | 755 | Owner has full access, others can read/execute |
| `rwxrwxrwx` | 777 | Everyone has full access (Not Recommended) |

## Key Learning

**Linux users, groups, and permissions are fundamental concepts in system security.**

I learned how Linux controls access to files and directories through ownership and permissions. Understanding these concepts is important for cybersecurity professionals because misconfigured permissions can expose sensitive data or create security risks.

I also learned how `chmod` and `chown` are used to manage permissions and ownership.

## Cybersecurity Relevance

Understanding Linux permissions is important for:

- System security
- Access control
- Privilege management
- Security auditing
- Privilege escalation analysis

## Progress

Day 2 Completed ✅
