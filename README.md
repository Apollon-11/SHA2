<h1>SHA-256 (Educational Implementation)</h1>>
This repository contains a tutorial implementation of the SHA-256 algorithm in C++ without using third-party cryptographic libraries.
The goal of the project is to study the internals of hash functions and implement the algorithm at a low level.
This project is not intended for production use.
<h1>Development Timeline:</h1>
Initial Development: 2024
Revision and Publication: 2026

<h1>Usage:</h1>
Specify the input message in the program code:
uchar test[] = "hello world";
Run the program.
The output will be the SHA-256 hash in hex format.

<h1>Limitations and Warnings</h1>
This implementation is for educational and demonstration purposes only.
DO NOT use it in real-world security systems. The code has not undergone cryptographic auditing and is not optimized for performance.
Additional features such as streaming file hashing, a CLI interface, or test vectors are not implemented.
For production use, it is recommended to use proven libraries.
The project was created as a standalone implementation for studying the principles of SHA-256.

<h1>SHA-256 (учебная реализация)</h1>
Этот репозиторий содержит учебную реализацию алгоритма SHA-256 на C++ без использования сторонних криптографических библиотек.
Цель проекта — изучение внутреннего устройства хэш-функций и практическая реализация алгоритма на низком уровне.
Проект не предназначен для использования в производственных целях.
<h1>Сроки разработки:</h1>
Начальная разработка: 2024 г.
Доработка и публикация: 2026 г.


<h1>Использование:</h1>
Укажите входное сообщение в коде программы:
uchar test[] = "hello world";
Запустите программу.
На выходе будет выведен SHA-256 hash в hex формате.


<h1>Ограничения и предупреждения</h1>
Эта реализация предназначена только для образовательных и демонстрационных целей.
НЕ используйте её в реальных системах безопасности.
Код не проходил криптографический аудит и не оптимизирован по производительности.
Не реализованы дополнительные возможности вроде потокового хэширования файлов, CLI-интерфейса или тестовых векторов.
Для production-использования рекомендуется применять проверенные библиотеки.
Проект создан как самостоятельная реализация для изучения принципов работы SHA-256.
