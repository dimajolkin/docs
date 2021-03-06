# Доступные команды

Список команд, доступных в ноутбуке, составлен из списка стандартных команд с некоторыми ограничениями и дополнениями. Ознакомьтесь со списком стандартных команд в [документации IPython](https://ipython.readthedocs.io/en/stable/interactive/magics.html). Ограничения и дополнения представлены ниже.

## Заблокированные стандартные команды {#block}

Стандартные команды, недоступные для выполнения в ноутбуке: 
* `%%bash`
* `%%perl`
* `%%python`
* `%%python2`
* `%%python3`
* `%%ruby`
* `%%script`
* `%%sh`

## Дополнительные команды {#extension}

Дополнительные команды, доступные для выполнения в ноутбуке: 
* `%%state_exclude [имена переменных]` — исключает указанные переменные из сохранения состояния.
* `%%state_include [имена переменных]` — добавляет указанные переменные в сохранение состояния.
* `%%state_include_all` — возвращает все переменные в сохранение состояния.
* `%%state_exclude_ls` — возвращает список всех переменных, которые были исключены из сохранения состояния.

#### См. также {#see-also}

* [{#T}](../operations/projects/install-dependencies.md)
* [{#T}](configurations.md)
* [{#T}](limits.md)
* [{#T}](../operations/index.md)