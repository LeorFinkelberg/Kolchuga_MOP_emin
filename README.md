## Сносный пример python-сценария, использующего концепцию переиспользования кода

#### Структура проекта

```sh
project
  -- python_scripts
    -- summary_PEpipe_Kolchuga.py
  README.md
  config_SDR9.yaml
  config_SDR11.yaml
  config_SDR17.yaml
```

#### Использование
```sh
$ cd python_scripts
$ python summary_PEpipe_Kolchuga.py --config-path config_SDR9.yaml
```

#### Примечание
В репозитории приводится несколько конфигурационных файлов (\*.yaml) с различными стартовыми параметрами. Конфигурационные файлы позволяют управлять внешним видом графиков "на лету", без вненсения изменений в код сценария.
