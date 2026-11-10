# vector-role

Устанавливает и настраивает [Vector](https://vector.dev) на Rocky Linux 9.

## Переменные (defaults)

| Переменная | Описание | Значение |
|---|---|---|
| `vector_version` | Версия Vector | `0.61.0` |
| `vector_install_dir` | Каталог установки | `/opt/vector` |
| `vector_config_dir` | Каталог конфигов | `/etc/vector` |
| `vector_data_dir` | Каталог данных | `/var/lib/vector` |

## Пример использования

```yaml
- hosts: vector
  roles:
    - vector-role