# cpp-digest-5

Название: C++ Дайджест №5 (2 октября – 15 октября 2023) 

Теги: дайджест, c++-дайджест, c++

Хабы: Программирование, C++

## Аннотация

Привет, Хабр! Сегодня я хочу вам представить подборку интересных новостей и материалов из мира C++ за последние две недели.

Приятного чтения!

## ⚡️️ Новости и релизы

1. [Qt 6.6](https://www.qt.io/blog/qt-6.6-released) — Добавление LayoutItemProxy, призванного упростить создание адаптивных макетов (англ. layout); введение [Qt Graphs](https://doc.qt.io/qt-6/qtgraphs-index.html), объединяющего древние Qt DataVisualization и Qt Charts в один современный фреймворк; улучшенный [захват окон](https://doc-snapshots.qt.io/qt6-6.6/qwindowcapture.html); значительное упрощение конфигурации Qt GRPC и Qt Protobuf и прочее.
2.  [Qt Creator 12](https://www.qt.io/blog/qt-creator-12-cmake-update) — Мажорный релиз, принесший множество изменений в плане поддержки CMake: добавление поддержки CMake Debugger, CMake Profiler; улучшенную навигацию (теперь не только по файлам, но и, с некоторыми ограничениями, по функциям и локальным переменным), поддержку сниппетов и автодополнение для `CMakeLists.txt`.
3. [Crpyto++ 8.9](https://github.com/weidai11/cryptopp/releases/tag/CRYPTOPP_8_9_0) — Минорный релиз, исправляющий несколько ошибок.

## 📝 Статьи

1. Macro Arena: [SObjectizer Tales, Prelude](https://marcoarena.wordpress.com/2023/10/05/sobjectizer-tales-prelude/) — Знакомство с [SObjectizer](https://github.com/Stiffstream/sobjectizer), фреймворком для построения параллельных и многопоточных программ, поддерживающим [акторную](https://ru.wikipedia.org/wiki/%D0%9C%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C_%D0%B0%D0%BA%D1%82%D0%BE%D1%80%D0%BE%D0%B2), [Publish-Subscribe](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern) и [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes) модели.
2. Macro Arena: [SObjectizer Tales, Producing Images](https://marcoarena.wordpress.com/2023/10/12/sobjectizer-tales-1/) — Углубленное знакомство с [SObjectizer](https://github.com/Stiffstream/sobjectizer) на примере разработки программы, отображающей и анализирующей информацию с камеры.
3. Bartłomiej Filipek: [Spans, string_view, and Ranges — Four View types](https://www.cppstories.com/2023/four-views-in-cpp23/) — Обзор всех проекций данных (англ. views), сущствующих в С++: от `std::string_view` (C++17) до `std::mdpsan` (C++23).
4. Sandor Dargo: [How to compare signed and unsigned integers in C++20?](https://www.sandordargo.com/blog/2023/10/11/cpp20-intcmp-utilities) — О том, как современный C++ решает проблему сравнения знаковых и беззнаковых целых чисел между собой.

## 📺 Видео и доклады

1. Jason Turner: [C++ Weekly — Ep 396 — emplace vs emplace_hint! What's the difference?](https://www.youtube.com/watch?v=hW4NJF4RLnE) — Обзор всех `emplace`, существующих в стандартной библиотеке: `emplace_back`, `emplace_front`, `try_emplace`, `emplace_hint` и не только.
2. Jason Turner: [C++ Weekly — Ep 397 — std::chrono Quickstart With C++20 Calendars](https://www.youtube.com/watch?v=I53iT3gPXrk) — Быстрое введение в [std::chrono](https://en.cppreference.com/w/cpp/chrono), нововведение C++20.

## Послесловие

> Дайджест составлен и опубликован при поддержке московского сообщества программистов [C++ Moscow](https://t.me/cppmoscow_info)

Заметили ошибку или опечатку? Сообщите в личку ([telegram](https://t.me/eoanermine), [habr](https://habr.com/ru/conversations/eoanermine/))

Прислать ссылку можно [через форму](https://forms.yandex.ru/cloud/64f48043e010db921819c447/) или просто написав мне в личные сообщения ([telegram](https://t.me/eoanermine), [habr](https://habr.com/ru/conversations/eoanermine/))

← Предыдущий выпуск: [C++ Дайджест №5](https://habr.com/ru/articles/764922/)
