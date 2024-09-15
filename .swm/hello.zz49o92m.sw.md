---
title: hello
---
<SwmSnippet path="/.pre-commit-config.yaml" line="1">

---

| hello | this       | is |
| ----- | ---------- | -- |
| world | that&nbsp; | is |
| !     | !          | !  |

&nbsp;

```yaml
repos:
  - repo: https://github.com/pre-commit/pre-commit-hooks
    rev: v3.4.0
    hooks:
      - id: check-json
      - id: check-yaml
      - id: check-xml
        exclude: ^.*parsing-error\.bpmn20\.xml$
      - id: check-merge-conflict
      - id: fix-byte-order-marker
      - id: mixed-line-ending
        args: ['--fix=lf']
      - id: end-of-file-fixer
      - id: trailing-whitespace
  - repo: https://github.com/sirosen/check-jsonschema
    rev: 0.3.0
    hooks:
      - id: check-github-workflows

```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBQWN0aXZpdGklM0ElM0FTaGFuZURlYW4=" repo-name="Activiti"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
