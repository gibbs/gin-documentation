# aide

Advanced Intrusion Detection Environment (AIDE).

```yaml
gin::components:
  aide: true
```

## Example Usage

```yaml
--8<-- "data/rspec/aide_rspec.yaml"
```

## Default Configuration

```yaml
--8<-- "data/component/aide.yaml"
```

---

## Data Types

### AIDE

```puppet title="types/aide.pp"
--8<-- "types/aide.pp"
```

### AIDE::Rule

```puppet title="types/aide/rule.pp"
--8<-- "types/aide/rule.pp"
```

### AIDE::Watch

```puppet title="types/aide/watch.pp"
--8<-- "types/aide/watch.pp"
```

## Manifest Source

```puppet title="manifests/aide.pp"
--8<-- "manifests/aide.pp"
```
