# alternatives

Maintain symbolic links determining default commands.

```yaml
gin::components:
  alternatives: true
```

## Example Usage

```yaml
--8<-- "data/rspec/alternatives_rspec.yaml"
```

## Default Configuration

```yaml
--8<-- "data/component/alternatives.yaml"
```

## Data Types

### Alternatives

```puppet title="types/alternatives.pp"
--8<-- "types/alternatives.pp"
```

### Alternatives::Entry

```puppet title="types/alternatives/entry.pp"
--8<-- "types/alternatives/entry.pp"
```

## Manifest Source

```puppet title="manifests/alternatives.pp"
--8<-- "manifests/alternatives.pp"
```
