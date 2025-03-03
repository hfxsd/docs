---
title: tiup cluster audit
summary: The tiup cluster audit command is used to view commands executed on all clusters in the history and the execution log of each command. If [audit-id] is specified, the corresponding execution log is output. If not specified, a table with fields ID, Time, and Command is output in reverse chronological order. The -h, --help option prints help information and is disabled by default.
---

# tiup cluster audit

The `tiup cluster audit` command is used to view commands executed on all clusters in the history and the execution log of each command.

## Syntax

```shell
tiup cluster audit [audit-id] [flags]
```

- If you do not fill in the `[audit-id]`, the table of operation records is output in reverse chronological order. The first column is the `audit-id`.
- If you fill in the `[audit-id]`, it means checking the execution log of the specified `audit-id`.

## Option

### -h, --help

- Prints the help information.
- Data type: `Boolean`
- This option is disabled by default and its default value is `false`. To enable this option, you can add this option to the command, and pass the `true` value or do not pass any value.

## Outputs

- If `[audit-id]` is specified, the corresponding execution log is output.
- If `[audit-id]` is not specified, a table with the following fields is output:
    - ID: the `audit-id` corresponding to the record
    - Time: the execution time of the command corresponding to the record
    - Command: the command corresponding to the record
