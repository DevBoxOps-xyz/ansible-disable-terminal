# disable-terminal

Role for disabling direct access to the terminal.

## Deploy example

```yaml
  roles:
    - role: disable-terminal
      install_nyancat: false
```

## Available parameters

### Main

| Param | Default | Description |
| -------- | -------- | -------- |
| `install_nyancat` | `true` | Install nyancat in terminal. |
