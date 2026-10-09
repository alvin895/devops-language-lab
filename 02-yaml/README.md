# Day 02 — YAML Intermediate

## Objectives

Learn intermediate YAML features and practice validating YAML files.

## Lessons

| File | Topic |
|---|---|
| `01-strings.yaml` | Plain strings, quoted strings, and values that resemble other data types |
| `02-multiline.yaml` | Multiline strings using `|` and `>` |
| `03-flow-style.yaml` | Compact mappings `{}` and lists `[]` |
| `04-anchors-aliases.yaml` | Anchors, aliases, and merge keys |
| `05-multiple-documents.yaml` | Multiple YAML documents separated by `---` |
| `06-real-config.yaml` | Combined application configuration |

## Validation

Validate all YAML files with:

```bash
yamllint 02-yaml/*.yaml
```

No output means the files pass the active yamllint rules.

## YAML Parsing Practice

PyYAML was used to inspect parsed values, test anchors and aliases, and read multiple YAML documents.

## Key Takeaways

- YAML indentation defines structure.
- Quoting can preserve values as strings.
- `|` preserves line breaks, while `>` folds lines into a paragraph.
- Anchors and aliases can reuse configuration values.
- `safe_load_all()` reads multiple YAML documents.
- Passing yamllint does not guarantee that an application-specific configuration is correct.
