# heat_equation_2D
<b>Задача 1</b><br/>
Численное решение двумерного нестационарного неоднородного уравнения теплопроводности в прямоугольной области. Следует использовать неявную разностную схему, метод переменных направлений, блочную прогонку.

**Задача 2**<br/>
Численное решение двумерного нестационарного неоднородного уравнения теплопроводности в прямоугольной области, с вырезами, заданными набором произвольно расположенных прямоугольников, расчет в которых не производится. Следует использовать явную разностную схему.<br/><br/>
Обратить внимание на необходимость использования метода равномерного распределения по процессам именно тех узлов расчетной области, в которых требуется выполнять расчет (вырезанные узлы в расчете не участвуют).

<b>Общие требования к выполненным заданиям</b><br/>
Требования к программе:
1. Программа должна быть гибридной: одновременно использовать технологию MPI, для обеспечения взаимодействия вычислительных узлов, и одну из двух технологий posix threads или OpenMP, для взаимодействия процессов, запущенных на ядрах процессоров<br/>
2. Программа должна демонстрировать эффективность не менее 80%, на числе вычислительных ядер, не менее 512

Отчет должен содержать:
1        постановку задачи
2        описание точного аналитического решения
3        описание метода решения и способа декомпозиции области
4        описание используемой вычислительной системы (число узлов, процессоров, ядер, вид интерконнекта, …)
5        аналитическую зависимость ожидаемого времени решения от параметров задачи и от параметров вычислительной системы
6        сведения о значении ошибки (отклонения от точного решения) при выполнении расчетов на последовательности сгущающихся сеток
7        таблицы и графики, содержащие сведения о размерах сеток, времени решения и эффективности распараллеливания
8        Анализ полученных результатов
9        Другие требуемые, с вашей точки зрения, материалы
10    Приложение (тексты программ: последовательной и параллельной). Прикладывать в pdf полезно (тогда на них в отчете ссылаться можно), но не обязательно.
! Обязательно прикладывать тексты программ отдельно в c/cpp формате.
