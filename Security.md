# Безопасные и небезопасные языки
Современные компьютеры представляют сложные данные реального мира в виде чисел в памяти компьютера. Это вводит в дисциплину программирования риск человеческого фактора, в том числе вероятность ошибок доступа к памяти.

Поэтому многие языки программирования сопровождаются средством контроля смысла операций над двоичными данными на основе сопровождающей их логической информации — *системой типов*.

## Системы типов:
- Динамические
- Статические
- Полиморфные


> В общем и целом, язык называется безопасным, если программы на нём, которые могут быть приняты компилятором как правильно построенные, в динамике никогда не выйдут за рамки допустимого поведения. Это не значит, что такие программы не содержат ошибок вообще.

> Языки Си и его потомок C++ являются небезопасными[29]. В программах на них обширно встречаются ситуации ослабления типизации (приведение типов) и прямого её нарушения (каламбур типизации), так что ошибки доступа к памяти являются в них статистической нормой (но крах программы наступает далеко не сразу, что затрудняет поиск места ошибки в коде).