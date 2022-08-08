# apt

Advanced package tool (APT).

```yaml
gin::components:
  apt: true
```

## Example Usage

```yaml
--8<-- "data/rspec/apt_rspec.yaml"
```

## Default Configuration

```yaml
--8<-- "data/component/apt.yaml"
```

### Debian 11

```yaml
--8<-- "data/component/Debian/Debian-11/apt.yaml"
```

### Ubuntu 20.04

```yaml
--8<-- "data/component/Debian/Ubuntu-20.04/apt.yaml"
```

## Data Types

### APT

```puppet title="types/apt.pp"
--8<-- "types/apt.pp"
```

### APT::Conf

```puppet title="types/apt/conf.pp"
--8<-- "types/apt/conf.pp"
```

### APT::Key

```puppet title="types/apt/key.pp"
--8<-- "types/apt/key.pp"
```

### APT::Mark

```puppet title="types/apt/mark.pp"
--8<-- "types/apt/mark.pp"
```

### APT::Pin

```puppet title="types/apt/pin.pp"
--8<-- "types/apt/pin.pp"
```

### APT::PPA

```puppet title="types/apt/ppa.pp"
--8<-- "types/apt/ppa.pp"
```

### APT::Setting

```puppet title="types/apt/setting.pp"
--8<-- "types/apt/setting.pp"
```

### APT::Source

```puppet title="types/apt/source.pp"
--8<-- "types/apt/source.pp"
```

## Manifest Source

```puppet title="manifests/apt.pp"
--8<-- "manifests/apt.pp"
```
