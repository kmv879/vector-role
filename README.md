Role Name
=========

Роль устанавливает и настраивает сервер Vector.


Role Variables
--------------

Переменные хранятся в [defaults/main.yml](defaults/main.yml) и могут быть изменены.

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `vector_version` | 0.27.0 | Версия Vector|
| `vector_config` |  [defaults/main.yml#L4](https://github.com/kmv879/vector-role/blob/main/defaults/main.yml#L4)   | Содержимое конфигурационного файла|


Example Playbook
----------------

    - hosts: servers
      roles:
         - kmv879.vector-role

License
-------

MIT

Author Information
------------------

------------------
Role by [Mikhail Kozhedub](https://github.com/kmv879).