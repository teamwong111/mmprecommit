# MMPrecommit

Some pre-commit hooks for OpenMMLab projects.

## Using pre-commit-hooks with pre-commit

Add this to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/zhouzaida/mmprecommit
    rev: v0.1.0  # Use the ref you want to point at
    hooks:
    -   id: say-hello
```
## Hooks available

### say-hello

A template to show how to implement a pre-commit hook

### check-copyright

 Check whether the code contains copyright

 * `src` - source files to add header.
 * `--exclude_dirs` - exclude folder.
 * `--include_suffixes` - header will be added to files with suffix.