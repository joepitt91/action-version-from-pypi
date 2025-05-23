<!--
SPDX-FileCopyrightText: 2025 Joe Pitt

SPDX-License-Identifier: GPL-3.0-only
-->
# GitHub Action - Get Current Version from PyPI Module

Get the current version of the specified PIP module.

## Inputs

| Input | Description | Required | Default |
|-------|-------------|----------|---------|
| module | The module to check. | Yes |  |

## Outputs

| Output | Description | Example |
|--------|-------------|---------|
| version | The current version of the module. | 2.5.3 |

## Example

```yaml
      - name: Get Current Version from PyPI Module
        id: version
        uses: joepitt91/action-version-from-pypi@v1
        with:
          module: requests
```
