## Test task #1 for Mimesis Inc. for the position of Data Quality Manager / QA for ML.

>ML-project	<- название проекта
>>data		<- папка, которая содержит данные из разных источников по типу данных (картинки, текст, таблицы и т.д.)
>>>images		<- папка, которая содержит картинки/фотографии
>>>>raw				<- папка, которая содержит исходные данные

>>>>>parsingPhotos

>>>>>photosFromModelAgencies

>>>>>photosOfMobileAppUsers

>>>>interim			<- папка, которая содержит промежуточные данные
>>>>>removeDuplicates

>>>>>humanPresence
>>>>>>isHuman

>>>>>>noHuman

>>>>>sexDetermination
>>>>>>male

>>>>>>female

>>>>processed			<- папка, которая содержит обработанные данные (полезные данными для ML отдела)

>>src		<- папка, которая содержит код проекта
>>>scripts		<- папка, которая содержит скрипты для обработки данных

>>>>removeDuplicates.py		<- скрипт, который удаляет дубликаты

>>>>humanPresence.py		<- скрипт, который определяет наличие человека на фотографии (есть/нет)

>>>>sexDetermination.py		<- скрипт, который определяет пол человека (мужчина/женщина)

>>>>validPosesDetermination.py	<- скрипт, который определяет валидные позы человека (хорошие/плохие позы)

>>doc		<- папка, которая содержит документацию проекта


