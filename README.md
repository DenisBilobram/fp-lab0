# fp-lab0

Я выбрал язык программирования Elixir для выполнения лабораторных работ, потому что он считается популярным и востребованным выбором для задач, связанных с веб-разработкой и созданием распределенных систем. Elixir ипользует виртуальную машину BEAM, которая славится своей устойчивостью и возможностью работы с высоконагруженными системами. Поскольку для меня интересны веб-разработка и изучение/разработка распределенных систем, я думаю что Elixir является лучшим для меня выбором функционального языка для изучения и реализации лабораторных работ.

Elixir больше мне подходит, чем Erlang, по нескольким причинам, связанным с его современными возможностями и удобствами разработки.
Во-первых, Elixir предоставляет современный и элегантный синтаксис, который более интуитивен и приятен для чтения и написания по сравнению с Erlang. Это значительно упрощает разработку и поддержку сложных приложений.
Во-вторых, Elixir имеет встроенные средства для веб-разработки, такие как фреймворк Phoenix, который значительно упрощает создание современных веб-приложений. В то время как Erlang хорош для высоконагруженных систем, у него нет специализированных инструментов для веб-разработки, что требует больше времени и усилий для создания и настройки веб-приложений. Phoenix же предоставляет инструменты для работы с реальными временем (например, через Phoenix Channels), что делает разработку многопользовательских приложений проще и эффективнее.

У меня уже есть идея для лаболаторной работы №4, которая заключается в создании распределенной системы, похожей на чат. Elixir подходит для таких сценариев т.к язык предоставляет встроенные механизмы для параллельного выполнения задач и встроенная поддержка распределённых систем в Elixir позволяет запускать процессы на разных машинах в сети и общаться между ними через те же механизмы обмена сообщениями, что и внутри одного узла.

Планируемые к использованию инструментальные средства:
* Mix — основной инструмент управления проектом в Elixir. Он отвечает за сборку, управление зависимостями, запуск тестов и многое другое.
* Phoenix Framework — фреймворк для веб-разработки, построенный на Elixir. Он позволяет легко создавать распределённые системы и веб-приложения с поддержкой реального времени (через Phoenix Channels) для общения между клиентами. Phoenix также поддерживает кластеризацию для работы с несколькими узлами.
* Erlang/OTP (Open Telecom Platform) — набор инструментов и библиотек для разработки распределённых систем. Это включает в себя механизм работы с легковесными процессами, обменом сообщениями, обработкой ошибок, отказоустойчивостью. Elixir наследует эти возможности от Erlang.

Выбранная книга для изучения Elixir - "Elixir in action", Юрич С. 2 издание, 2020.