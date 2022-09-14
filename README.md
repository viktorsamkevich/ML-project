## Test task #1 for Mimesis Inc. for the position of Data Quality Manager / QA for ML.

|ML-Project     <- название проекта
├───data        <- папка, которая содержит данные из разных источников по типу данных (картинки, текст, таблицы и т.д.)
│   └───images      <- папка, которая содержит картинки/фотографии
│       ├───interim     <- папка, которая содержит промежуточные данные
│       │   ├───humanPresence           <- папка, которая содержит данные после обработки скриптом humanPresence
│       │   │   ├───isHuman
│       │   │   └───noHuman
│       │   ├───manualSelection         <- папка, которая содержит данные после ручной обработки, распределенные по категориям
│       │   │   ├───anorexic
│       │   │   ├───athletic
│       │   │   ├───bodybuilder
│       │   │   ├───fat
│       │   │   ├───normal
│       │   │   └───veryFat
│       │   ├───removeDuplicates        <- папка, которая содержит данные после обработки скриптом humanPresence
│       │   ├───sexDetermination        <- папка, которая содержит данные после обработки скриптом humanPresence
│       │   │   ├───female
│       │   │   └───male
│       │   └───validPosesDetermination <- папка, которая содержит данные после обработки скриптом humanPresence
│       │       ├───badPoses
│       │       └───goodPoses
│       ├───processed   <- папка, которая содержит обработанные данные (полезные данными для ML отдела)
│       └───raw         <- папка, которая содержит исходные данные
│           ├───parsingPhotos
│           ├───photosFromModelAgencies
│           └───photosOfMobileAppUser
├───doc     <- папка, которая содержит документацию проекта
└───src     <- папка, которая содержит код проекта
    └───scripts     <- папка, которая содержит скрипты для обработки данных
            humanPresence.py            <- скрипт, который определяет наличие человека на фотографии (есть/нет)
            removeDuplicates.py         <- скрипт, который удаляет дубликаты
            sexDetermination.py         <- скрипт, который определяет пол человека (мужчина/женщина)
            validPosesDetermination.py  <- скрипт, который определяет валидные позы человека (хорошие/плохие позы)