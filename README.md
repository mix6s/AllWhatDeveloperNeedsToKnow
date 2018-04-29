---


---

<h1 id="solid">SOLID</h1>
<blockquote>
<p><a href="https://ru.wikipedia.org/wiki/SOLID_(%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)">wiki</a></p>
</blockquote>
<h1 id="шаблоны-проектирования">Шаблоны проектирования</h1>
<p>пораждающие/структурные/поведенческие/антипаттерны</p>
<blockquote>
<p><a href="http://designpatternsphp.readthedocs.io/ru/latest/README.html">DesignPatternsPHP</a><br>
<a href="https://ru.wikipedia.org/wiki/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F">https://ru.wikipedia.org/wiki/Шаблон_проектирования</a></p>
</blockquote>
<h1 id="couplingcohesion">Coupling/Cohesion</h1>
<h3 id="coupling">Coupling</h3>
<p><em>Связанность</em>, характеристика взаимосвязи модуля сдругими модулями. Это степень, в которой каждый программный модуль полагается на другие модули. То есть характеризуют взаимодействие между модулями в системе. Слабая связанность - хорошо, (модули взаимодействуют с минимальной зависимостью, изменения в одном мудуле не требуют изменения в другом)</p>
<h3 id="cohesion">Cohesion</h3>
<p><em>Cвязность</em>, характеристика внутренней взаимосвязи между частями одного модуля, определяет на сколько узко специалезирован модуль, нацелен ли модуль на решение одной, конкретной задачи, Сильная связность - хорошо (модуль выполняет одну функцию, имеет мин. кол интерейфесов)</p>
<h1 id="масштабирование-приложений">Масштабирование приложений</h1>
<h3 id="вертикальное">Вертикальное</h3>
<p>Увеличение производительности каждого компонента системы с целью повышения общей производительности. Масштабируемость в этом контексте означает возможность заменять в существующей вычислительной системе компоненты более мощными и быстрыми по мере роста требований и развития технологий. Это самый простой способ масштабирования, так как не требует никаких изменений в прикладных программах, работающих на таких системах.</p>
<h3 id="горизонтальное">Горизонтальное</h3>
<p>Разбиение системы на более мелкие структурные компоненты и разнесение их по отдельным физическим машинам (или их группам), и (или) увеличение количества серверов, параллельно выполняющих одну и ту же функцию. Масштабируемость в этом контексте означает возможность добавлять к системе новые узлы, серверы, процессоры для увеличения общей производительности. Этот способ масштабирования может требовать внесения изменений в программы, чтобы программы могли в полной мере пользоваться возросшим количеством ресурсов.</p>
<h3 id="примеры">Примеры</h3>
<blockquote>
<p><a href="https://ru.wikipedia.org/wiki/%D0%9C%D0%B0%D1%81%D1%88%D1%82%D0%B0%D0%B1%D0%B8%D1%80%D1%83%D0%B5%D0%BC%D0%BE%D1%81%D1%82%D1%8C">https://ru.wikipedia.org/wiki/Масштабируемость</a></p>
</blockquote>
<h1 id="oop">OOP</h1>
<blockquote>
<p><a href="https://en.wikipedia.org/wiki/Object-oriented_programming">https://en.wikipedia.org/wiki/Object-oriented_programming</a></p>
</blockquote>
<h1 id="ddd">DDD</h1>
<h1 id="особеностиотличия-языков-программирования">Особености/Отличия языков программирования</h1>
<h3 id="php">php</h3>
<h3 id="java">java</h3>
<h3 id="javascript">javascript</h3>
<p>и другие :)</p>
<h1 id="concurrencyraceconditiondeadlockcriticalsection">Concurrency/RaceCondition/Deadlock/CriticalSection</h1>
<blockquote>
<p><a href="http://tutorials.jenkov.com/java-concurrency/race-conditions-and-critical-sections.html">http://tutorials.jenkov.com/java-concurrency/race-conditions-and-critical-sections.html</a></p>
</blockquote>
<h1 id="базы-данных">Базы данных</h1>
<h3 id="объектно-реляционная-субд">Объектно-реляционная СУБД</h3>
<p>что такое, примеры</p>
<h3 id="документоориентированная-субд">Документоориентированная СУБД</h3>
<p>особености, mongodb, noSQL</p>
<h3 id="транзакции-блокировки">Транзакции, Блокировки</h3>
<h3 id="денормализациянормализация">Денормализация/Нормализация</h3>
<h3 id="activerecord">ActiveRecord</h3>
<h3 id="orm">ORM</h3>
<h3 id="tdd">TDD</h3>
<p>Дабвить тест -&gt; Запуск тестов, fail -&gt;  Написать код -&gt;  Запуск тестов, success -&gt; Рефакторинг -&gt; Go To Start</p>
<blockquote>
<p><a href="https://ru.wikipedia.org/wiki/%D0%A0%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0_%D1%87%D0%B5%D1%80%D0%B5%D0%B7_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">https://ru.wikipedia.org/wiki/Разработка_через_тестирование</a></p>
</blockquote>
<h1 id="ссылки-на-почитать">Ссылки на почитать</h1>
<blockquote>
<p><a href="https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D0%B4_%D1%81_%D0%B7%D0%B0%D0%BF%D0%B0%D1%88%D0%BA%D0%BE%D0%BC">Код с запашком / wikipedia.org</a><br>
<a href="https://habr.com/post/273843/">От STUPID кода к SOLID коду / habr.com</a><br>
<a href="https://github.com/kamranahmedse/developer-roadmap">developer-roadmap / github.com</a><br>
<a href="https://habr.com/post/263765/">Структуры данных. Неформальный гайд / habr.com</a></p>
</blockquote>
<blockquote>
<p><a href="http://www.1024cores.net/">http://www.1024cores.net/</a><br>
<a href="https://github.com/ktlle/ddd-q-ly">https://github.com/ktlle/ddd-q-ly</a><br>
<a href="https://martinfowler.com/">https://martinfowler.com/</a><br>
<a href="https://medium.com/@ifesdjeen">https://medium.com/@ifesdjeen</a> /db<br>
<a href="http://www.phptherightway.com/">http://www.phptherightway.com/</a><br>
<a href="http://www.phpthewrongway.com/">http://www.phpthewrongway.com/</a><br>
<a href="https://martinfowler.com/tags/domain%20driven%20design.html">https://martinfowler.com/tags/domain driven design.html</a><br>
<a href="https://martinfowler.com/articles/microservice-trade-offs.html">https://martinfowler.com/articles/microservice-trade-offs.html</a><br>
<a href="https://habr.com/post/104219/">https://habr.com/post/104219/</a></p>
</blockquote>

