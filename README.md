# cpp-digest-5

Название: C++ Дайджест №5 (2 октября – 15 октября 2023) 

Теги: дайджест, c++-дайджест, c++

Хабы: Программирование, C++

## Аннотация

Привет, Хабр! Сегодня я хочу вам представить подборку интересных новостей и материалов из мира C++ за последние две недели.

Приятного чтения!

## ⚡️️ Новости и релизы

1. [Qt 6.6](https://www.qt.io/blog/qt-6.6-released) — Добавление [LayoutItemProxy](https://doc.qt.io/qt-6/qml-qtquick-layouts-layoutitemproxy.html), призванного упростить создание адаптивных макетов (англ. layout); введение [Qt Graphs](https://doc.qt.io/qt-6/qtgraphs-index.html), объединяющего древние Qt DataVisualization и Qt Charts в один современный фреймворк; улучшенный [захват окон](https://doc-snapshots.qt.io/qt6-6.6/qwindowcapture.html); значительное упрощение конфигурации Qt GRPC и Qt Protobuf и прочее.
2.  [Qt Creator 12](https://www.qt.io/blog/qt-creator-12-cmake-update) — Мажорный релиз, принесший множество изменений в плане поддержки CMake: добавление поддержки CMake Debugger, CMake Profiler; улучшение навигации, добавление поддержки сниппетов и автодополнения для `CMakeLists.txt`.

## 📝 Статьи

1. 🇷🇺 Habr: [Compile Time Dependency Injection в С++: как обуздать зависимости не прибегая к позднему связыванию](https://habr.com/ru/articles/765080/) — Как работает внедрение зависимостей и какие каждодневные проблемы оно решает?
2. 🇷🇺 Habr: [Вглубь std::unordered_map: магические числа](https://habr.com/ru/articles/765760/) — О том, какое волшебство скрывают внутри себя стандартные хэш-таблицы с небольшим погружением в их реализацию в [libstdc++](https://gcc.gnu.org/onlinedocs/libstdc++/).
3. 🇷🇺 Habr: [Сборка мусора: как это делается в системном программировании](https://habr.com/ru/companies/timeweb/articles/766772/) — О RCU, одном из методов обеспечения неблокирующего совместного использования данных в разных потоках.
4. 🇷🇺 Habr: [Глубина кроличьей норы: бинарная граница и ABI C++](https://habr.com/ru/articles/710658/) — О том, что такое ABI и бинарные границы, и какие проблемы могут возникнуть при их пересечении.
5. Macro Arena: [SObjectizer Tales, Prelude](https://marcoarena.wordpress.com/2023/10/05/sobjectizer-tales-prelude/) — Знакомство с [SObjectizer](https://github.com/Stiffstream/sobjectizer), фреймворком для построения параллельных и многопоточных программ, поддерживающим [акторную](https://ru.wikipedia.org/wiki/%D0%9C%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C_%D0%B0%D0%BA%D1%82%D0%BE%D1%80%D0%BE%D0%B2), [Publish-Subscribe](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern) и [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes) модели.
6. Macro Arena: [SObjectizer Tales, Producing Images](https://marcoarena.wordpress.com/2023/10/12/sobjectizer-tales-1/) — Углубленное знакомство с [SObjectizer](https://github.com/Stiffstream/sobjectizer) на примере разработки программы, отображающей и анализирующей информацию с камеры.
7. Bartłomiej Filipek: [Spans, string_view, and Ranges — Four View types](https://www.cppstories.com/2023/four-views-in-cpp23/) — Обзор всех проекций данных (англ. views), сущствующих в С++: от `std::string_view` (C++17) до `std::mdpsan` (C++23).
8. Sandor Dargo: [How to compare signed and unsigned integers in C++20?](https://www.sandordargo.com/blog/2023/10/11/cpp20-intcmp-utilities) — О том, как современный C++ решает проблему сравнения знаковых и беззнаковых целых чисел между собой.
9. Andreas Fertig: [Using C++23s constexpr unique_ptr](https://andreasfertig.blog/2023/10/using-cpp23s-constexpr-unique_ptr/) — Знакомство с `constexpr unique_ptr` (С++23).
10. Arthur O’Dwyer: [How boost::is_base_of matches private and (or) ambiguous bases](https://quuxplusone.github.io/blog/2023/10/06/boost-is-base-of/) — Срыв покровов с механизмов работы `boost::is_base_of` (осторожно, в тексте 14 ссылок на стандарт!)
11. Rainer Grimm: [C++20: Module Support of the Big Three](https://www.modernescpp.com/index.php/c20-module-support-of-the-big-three-compilers/) — Обзор текущего состояния поддержки модулей в clang, gcc и msvc.
12. Rainer Grimm: [Special Allocators with C++17](https://www.modernescpp.com/index.php/special-allocators-with-c17/),  — Практические примеры использования [полиморфных аллокаторов](https://en.cppreference.com/w/cpp/memory/polymorphic_allocator).
13. Rainer Grimm: [Optimization with Allocators in C++17](https://www.modernescpp.com/index.php/optimization-with-allocators-in-c17/) — О том, как полиморфные аллокаторы позволяют оптимизировать наш код: добиться большей производительности и переиспользования памяти.

## 📺 Видео и доклады

1. Jason Turner: [C++ Weekly — Ep 396 — emplace vs emplace_hint! What's the difference?](https://www.youtube.com/watch?v=hW4NJF4RLnE) — Обзор всех `emplace`, существующих в стандартной библиотеке: `emplace_back`, `emplace_front`, `try_emplace`, `emplace_hint` и не только.
2. Jason Turner: [C++ Weekly — Ep 397 — std::chrono Quickstart With C++20 Calendars](https://www.youtube.com/watch?v=I53iT3gPXrk) — Быстрое введение в [std::chrono](https://en.cppreference.com/w/cpp/chrono), нововведение C++20.

### C++ Con 2023

1. Bjarne Stroustrup: [Delivering Safe C++](https://www.youtube.com/watch?v=I8UvQKvOSSw&list=PLHTh1InhhwT7gQEuYznhhvAYTel0qzl72&index=1) — О подходе к написанию программ на C++, исключающем наличие утечек памяти, висящих указателей и попыток обращения за границы выделенной памяти.
2. Bret Brown, Bill Hoffman: [Libraries: A First Step Toward Standard C++ Dependency Management](https://www.youtube.com/watch?v=IwuBZpLUq8Q&list=PLHTh1InhhwT7gQEuYznhhvAYTel0qzl72&index=2) — Презентация совместных наработок Bloomberg и Kitware (разработчика CMake) в области создания единого формата метаданных для описания плюсовых библиотек: header-only, статических и динамических.
3. Herb Sutter: [Cooperative C++ Evolution – Typescript for C++](https://www.youtube.com/watch?v=8U3hl8XMm8c&list=PLHTh1InhhwT7gQEuYznhhvAYTel0qzl72&index=4) — Личный взгляд председателя [WG21](https://www.open-std.org/jtc1/sc22/wg21/) (Комитет по стандартизации C++) на идеалы эволюции C++.
4. Andrei Alexandrescu: [Robots Are after Your Job: Exploring Generative AI for C++](https://www.youtube.com/watch?v=J48YTbdJNNc&list=PLHTh1InhhwT7gQEuYznhhvAYTel0qzl72&index=5) — Рассуждение: какую часть работы мы можем уверенно делегировать генеративному ИИ, а какие уникальные человеческие навыки мы должны сохранить и усовершенствовать?

## Послесловие

> Дайджест составлен и опубликован при поддержке московского сообщества программистов [C++ Moscow](https://t.me/cppmoscow_info)

Заметили ошибку или опечатку? Сообщите в личку ([telegram](https://t.me/eoanermine), [habr](https://habr.com/ru/conversations/eoanermine/))

Прислать ссылку можно [через форму](https://forms.yandex.ru/cloud/64f48043e010db921819c447/) или просто написав мне в личные сообщения ([telegram](https://t.me/eoanermine), [habr](https://habr.com/ru/conversations/eoanermine/))

← Предыдущий выпуск: [C++ Дайджест №5](https://habr.com/ru/articles/764922/)
