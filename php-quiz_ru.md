Перечень вопросов теста

#### В1. Результатом выполнения скрипта является?
echo 76 <=> '76 trombones';

a)	1
b)	-1
c)	ошибка синтаксического анализатора
d)	0

#### В2. Какой наиболее безопасный способ избежать хранения пароля в открытом виде в базе данных?
a)	$encrypted = shal($password);
b)	$encrypted = crypt($password, \$salt);
c)	$encrypted = md5($password);
d)	$encrypted = password_hash($password, PASSWORD_DEFAULT);
#### В3. Что делает этот скрипт?
$email = filter_input(INPUT_POST, 'email', FILTER_VALIDATE_EMAIL);
if ($email === false) {
    $emailErr = "Please re-enter valid email";
}
a)	Это гарантирует, что адрес электронной почты является хорошим и работоспособным адресом.
b)	Это делает ввод электронного письма в базу данных безопасным.
c)	Он присваивает адрес электронной почты переменной, а затем удаляет все недопустимые символы из переменной $email.
d)	Он проверяет правильность формирования адреса электронной почты.
#### В4. В следующем скрипте какая строка(и) вызовет ошибку(и)?
 <?php
       $count = 0;
       $_xval = 5;
       $_yval = 1.0;
       $some_string = "Hello there!";
       $some_string = "How are you?";
       $will i work = 6;
       $3blindmice = 3;
 ?>
a)	Строка 6 вызовет ошибку, поскольку вы не сможете переназначить новое значение переменной, которая уже была установлена.
b)	Строки 7 и 8 вызовут ошибку. В строке 7 есть пробел в $will i work, а должно быть $will_i_work. Строка 8 не может начинаться с числа, потому что это переменная.
c)	Строка 5 вызовет ошибку, поскольку some_string должна быть someString.
d)	Строки 3 и 4 вызовут ошибку, поскольку переменная не может начинаться с символа подчеркивания (_).

#### В5. В условном операторе вы хотите выполнить скрипт только если оба значения истинны. Какой оператор сравнения следует использовать?
a)	||
b)	&
c)	<=>
d)	&&
#### В6. С какого символа описываются переменные в PHP?
a)	&
b)	%
c)	_
d)	$
#### В7. В чем ключевое различие между GET и POST?
a)	GET используется с протоколом HTTP. POST используется с HTTPS.
b)	GET отображает отправленные данные как часть URL. При использовании POST эта информация не отображается, так как она закодирована в теле запроса.
c)	GET предназначен для изменения состояния сервера и переносит больше данных, чем POST.
d)	GET более безопасен, чем POST, и его следует использовать для конфиденциальной информации.
#### В8. Оператор ____ используют для операций сортировки. Он сравнивает два значения и возвращает целое число, меньшее, равное или большее 0, в зависимости от того, является ли значение ____ на меньше, равное или большее другого.
a)	greater-than; right
b)	spaceship; left
c)	equality; right
d)	comparison; left
#### В9. Какие ключевые слова являются допустимыми для обработки ошибок PHP?
a)	try, throw, catch, callable
b)	try, yield, catch, finally
c)	yield, throw, catch, finally
d)	try, throw, catch, finally
#### В10. Какое значение соответствует истине?
0
 NULL
 ''
 -1
#### В11. Укажите недостающий элемент в скрипте, который должен создавать тестовые куки?
$string_name = "testcookie";
$string_value = "This is a test cookie";
$expiry_info = info()+259200;
$string_domain = "localhost.localdomain";
a)	Отсутствует $_REQUEST.
b)	Массив $_COOKIES отсутствует.
c)	Сеанс cookie отсутствует.
d)	call setcookie() отсутствует.

#### В12. Чему равно значение $total?
$total = 2 + 5 * 20 - 6 / 3
a)	44
b)	138
c)	126
d)	100
#### В13. В чем смысл добавления строчной буквы "u" в качестве модификатора после конечного разделителя в регулярном выражении, совместимом с Perl?
a)	Он заставляет метасимвол точки соответствовать чему угодно, включая символы новой строки.
b)	Он заставляет шаблон соответствовать заглавным буквам.
c)	И шаблон, и строка темы обрабатываются как UTF-8.
d)	Он инвертирует жадность квантификаторов в шаблоне, так что они не являются жадными по умолчанию.
#### В14. Какой фрагмент скрипта использует корректный синтаксис для создания экземпляра класса Pet?
a)	$dog = new Pet;
b)	$horse = (new Pet);
c)	$cat = new Pet();
d)	все ответы правильные
#### В15. Выберите наиболее подходящее пояснение работы скрипта?
if (!$_SESSION['myusername'])
{
  header('locaton: /login.php');
  exit;
}
a)	Этот скрипт завершает сеанс для myusername.
b)	В результате работы этого скрипта начинают сохраняться файлы cookie.
c)	Этот скрипт проверяет имя пользователя и пароль.
d)	Этот скрипт находится на странице, требующей от пользователя входа в систему. Он проверяет, есть ли у пользователя действующий сеанс.
#### В16. Укажите, какой правильный формат для добавления комментария в PHP-скрипт?
a)	#This is a comment
b)	/* This is a comment */
c)	// This is a comment
d)	все ответы правильные
#### В17. PHP поддерживает несколько типов циклов. Если бы вы хотели выполнить цикл в блоке, если и пока заданное условие истинно, какой тип цикла вы бы использовали?
a)	for
b)	do-while
c)	while
d)	foreach
#### В18. ignore_user_abort( ) функция, которая устанавливает, наобходимо ли приотключении клиента прерывать выполнение скрипта. В каком сценарии веб-разработчики используют эту функцию?
a)	Ее используют, чтобы помешать пользователю нажать кнопку «Назад», если в результате нажатия он решит не просматривать страницу.
b)	Используют, если необходимо выполнить обработку данных без прерывания, даже если пользователи нажимают кнопку «Отмена».
c)	Эту функцию следует использовать, если требуется прервать выполнение скрипта для всех вошедших в систему пользователей, а не только для того, кто отключился.
d)	Эту функцию можно использовать, если требуется, чтобы PHP-скрипт выполнялся бесконечно.
#### В19. Функция PHP array_reduce() принимает функцию обратного вызова, которая принимает значение, которое используется на каждой итерации, текущим элементом в массиве, и уменьшает массив до одного значения. Какой пример скрипта будет суммировать и выводить значения в полученном массиве?
­
a)
<?php
  echo array_reduce([1, 2, 5, 10, 11], function ($item, $carry) {
      $carry = $carry + $item;
  });
?>
b)
  <?php
  echo array_reduce([1, 2, 5, 10, 11], function ($carry, $item) {
      return $carry = $item + $item;
  });
?>
c)
  <?php
  array_reduce([11 2, 5, 10, 11], function ($item, $carry) {
      echo $carry + $item;
  });
?>
d)
  <?php
  echo array_reduce([1, 2, 5, 10, 11], function ($carry, $item) {
      return $carry += $item;
  });
?>
#### В20. Какой PHP-скрипт использует конструктор для отображения строки «Winter is almost over!»?
a)
  class MyClass {
  public function _construct()
  {
  echo 'Winter is almost over!'."\n";
  }
  }
  $userclass = new MyClass;
b)
  class MyClass {
  public function _construct()
  {
  echo 'Winter is almost over!.."\n";
  }
  }
  $userclass = new MyClass;
c)
  class MyClass {
  public function _construct()
  {
  echo 'Winter is almost over!.."\n";
  }
  }
  $userclass = new MyClass;
d)
  class MyClass {
  public function _construct()
  {
  echo 'Winter is almost over!'."n";
  }
  }
  $userclass = MyClass;
#### В21. Как устранить ошибку «call to undefined function»?
a)	Убедитесь, что вы импортировали файл, содержащий функцию.
b)	Убедитесь, что вы правильно написали имя функции.
c)	Убедитесь, что объявление функции находится в более ранней точке кода, чем вызов функции.
d)	все ответы правильные
#### В22. Какую строку вы НЕ могли бы использовать для комментария «Space: the final frontier»?
a)	/* Space: the final frontier */
b)	*/ Space: the final frontier /*
c)	#Space: the final frontier
d)	// Space: the final frontier
#### В23. Что отображается в браузере при написании следующего кода?
<?php echo "How much are the bananas?"?>
a)	Браузер ничего не отображает из-за синтаксической ошибки.
b)	Браузер выдаст ошибку, поскольку вокруг строки нет скобок.
c)	Браузер отобразитHow much are the bananas?
d)	Браузер выдаст ошибку, так как в конце команды echo нет точки с запятой.

#### В24. Какой оператор используют, чтобы найти остаток от деления?
a)	/
b)	%
c)	//
d)	DIV
#### В25. Какоео значение трех точек в сигнатуре функции?
function process(...$vals) {
    // do some processing
}
a)	Это делает функцию вариативной, позволяя ей принимать в качестве аргумента массив, содержащий произвольное количество значений.
b)	Это делает функцию вариативной, позволяя ей принимать произвольное количество аргументов, которые преобразуются в массив внутри функции.
c)	Они временно отключает функцию на время отладки других частей скрипта.
d)	Это своего рода напоминание о том, что нужно сделать, автоматически выводит уведомление при запуске скрипта до завершения определения функции.
#### В26. Если Horse класс определен, какой пример наследования в PHP является допустимым?
a)	class Pegasus extends Horse {}
b)	class Alicorn imports Pegasus, Unicorn {}
c)	class Unicorn implements Horse {}
d)	class Horse inherits Unicorn {}
#### Q27. И тройное ===, и двойное == можно использовать для _____ переменных в PHP. Если необходимо проверить, что строка "33" и число 33 равны, следует использовать ____. Если необходимо проверить, содержит ли массив определенное строковое значение по определенному индексу, следует использовать ____
сравнение; двойное; тройное
сравнение; тройное; двойное
присвоение; тройное; двойное
присвоение; двойное; тройное 
#### В28. Страница PHP неожиданно отображается пустой страницей. Какое действие требуется выполнить? 
a)	Добавить этот код в начало скрипта: ini_set('display_errors',1);
b)	Проверить журнал ошибок сервера
c)	Убедиться, что не пропущено ни одной точки с запятой 
d)	все ответы правильные
#### В29. Какой способ создания массива "seasons" правильный?
seasons=array(
    1=>'spring',
    2=>'summer',
    3=>'autumn',
    4=>'winter',
);
a)	$seasons=array(spring,summer,autumn,winter);
b)	$seasons=('spring','summer','autumn','winter');
c)	$seasons=['spring','summer','autumn','winter'];
#### В30. И self`, и this являются ключевыми словами, которые можно использовать для ссылки на переменные-члены класса. Разница состоит в том, что $this->member следует использовать для ____ членов, а self::$member следует использовать для _____членов.
a)	частных, публичных
b)	объектных, примитивных
c)	нестатических, статических
d)	конкретных, абстрактных
#### В31. Что выведет этот код?
$mathe=array('archi','euler','pythagoras');
array_push($mathe,'hypatia');
array_push($mathe,'fibonacci');
array_pop($mathe);
echo array_pop($mathe);
echo sizeof($mathe);
a)	euler3
b)	hypatia5
c)	hypatia3
d)	fibonacci4
#### В32. Вы используете следующий скрипт для поиска любимой пользовательской группы, но он возвращает false. Какой шаг решит эту проблему?
isset ($_GET['fav_band'])
a)	проверить, включен ли fav_band в строку запроса в верхней части браузера
b)	просмотреть исходный код формы и убедиться, что есть поле ввода с именем fav_band
c)	вывести все, что было передано в запросе: print_r($_REQUEST);
d)	все ответы правильные
#### В33. Какой скрипт используется для вывода всех элементов массива 
a)	print_r($cupcakes);
b)	var_dump($cupcakes);
c)	foreach($cupcakes как &$cupcake) echo $cupcake;
d)	все ответы правильные
#### В34. Что является причиной 'Cannot modify header information - headers already sent'?
a)	Попытка изменить личное значение
b)	Пропущена точка с запятой
c)	Использование ключа в массиве, которого не существует
d)	Некоторые HTML отправляются перед командой header(), которая используется для перенаправления
#### В35. Какая структура управления PHP используется внутри цикла для пропуска оставшегося кода текущего цикла и возврата к началу цикла для последующей итерации?
a)	else
b)	break
c)	return
d)	continue
#### В36. Оператор php НЕ определяется спецсимволом !. Учитывая фрагмент ниже, есть ли выход из цикла и какой его результат?
<?php
$num = 21;

if ($num%2!=0) {

 echo "$num является нечетным числом";

} else {

 echo "$num является четным числом";
}
?>
a)	есть вывод '2 является четным числом'
b)	вывод '21 является нечетным числом'
c)	нет вывода. Синтаксическая ошибка из-за отсутствия точки с запятой в конце.
d)	нет вывода через % в $num%2!=0
#### В37. Необходимо просмотреть модули PHP, которые были установлены при установке, укажите правильную команду.
a)	php -h
b)	php info
c)	php -v
d)	php -m
#### Q38. Для HTML-формы ниже, какой корректно функционирующий скрипт проверяет входное поле «mail», чтобы убедиться, что оно заполнено, прежде чем продолжить?
<form method="post" action="test.php">
 Email: <input type="text" name="mail" />
 <input type="submit" />
</form>
a)
if (!empty($_POST["mail"])) {
 echo "Yes, mail is set";
} else {
 echo "No, mail is not set";
}

b)
if ($_POST["mail"] == "") {
 echo "No, mail is not set";
} else {
 echo "Yes, mail is set";
}
c)
if (isset($_POST["mail"])) {
 echo "Yes, mail is set";
} else {
 echo "No, mail is not set";
}
d)
if ($_POST["mail"]) {
 echo "Yes, mail is set";
} else {
 echo "No, mail is not set";
}
#### В39. Какое значение имеет $result в этом вычислении?
$result = 25 % 6;

a)	4.167
b)	1.5
c)	4
d)	1
#### В40. Какая роль контроллера как компонента в MVC?
a)	Контроллер обрабатывает данные, передаваемые ему представлением, а также передает данные представлению. Он интерпретирует данные, отправленные представлением, и передает эти данные соответствующим моделям, ожидая результатов для передачи обратно в представление.
b)	Контроллер – это механизм, позволяющий создавать многократный код в таких языках, как PHP, где множественное наследование не поддерживается.
c)	Контроллер представляет содержимое через пользовательский интерфейс после непосредственного общения с базой данных.
d)	Контроллер обрабатывает конкретные задачи, связанные с определенной областью функциональности, обрабатывает бизнес-логику, связанную с результатами, и напрямую взаимодействует с базой данных.
#### В41. Почему этот скрипт вызывает ошибку?
$string = Shylock in a Shakespeare's "Merchant of Venice" demands his pound of flesh.';
a)	Строки всегда следует обертывать в двойные кавычки, а двойные кавычки внутри строки следует экранировать обратными косыми рисками.
b)	Все одинарные и двойные кавычки внутри строки нужно экранировать обратными косыми рисками, чтобы избежать ошибки парсера.
c)	Открывающие и закрывающие одинарные кавычки следует заменить двойными кавычками, а апостроф следует экранировать обратной косой чертой.
d)	Апостроф нужно экранировать обратной косой чертой, чтобы он не воспринимался как закрывающая кавычка.
#### В42. Объект PDO под названием $db сконфигурирован в операциях с базой данных, включая проверку подлинности пользователей. свойства, связанные с пользователем на _______, если ни один пользователь не вошел в систему. будут правильно установлены функциями входа, когда пользователь войдет в систему.
 NULL
 TRUE
 FALSE
 0
#### В43. Предположим, что $first_name и $family_name являются валидными, какое выражение невалидно?
a)	echo $first_name. ‘ ‘. $family_name;
b)	print $first_name, ‘ ‘, $family_name;
c)	print $first_name. ‘ ‘. $family_name;
d)	echo $first_name, ‘ ‘, $family_name;
#### В44. Какой фрагмент скрипта демонстрирует инкапсуляцию?
a)
  class Cow extends Animal {
      private $milk;
  }
b)
  class Cow {
      public $milk;
  }
  $daisy = new Cow();
  $daisy->milk = "creamy";
c)
  class Cow {
      public $milk;
      function getMilk() {`
          return $this->milk;
      }
  }
d)
  class Cow {
      private $milk;
      public function getMilk() {
          return $this->milk;
      }
  }
#### В45. Следующий XML-документ находится в books.xml. Какой скрипт выведет "Historical"?
<books>
    <book>
        <title>A Tale of Two Cities</title>
        <author>Charles Dickens</author>
        <categories>
            <category>Classics</category>
            <category>Historical</category>
        </categories>
    </book>
    <book>
        <title>Then There Were None</title>
        <author>Agatha Christies</author>
        <categories>
            <category>Mystery</category>
        </categories>
    </book>
</books>
a)
  $books = simplexml_load_string('books.xml');
  echo $books->book[0]->categories->category[1];
b)
  $books = simplexml_load_file('books.xml');
  echo $books->book[0]->categories->category[1];
c)
  $books = SimpleXMLElement('books.xml');
  echo $books->book[0]->categories->category[1];
d)
  $books = SimpleXML('books.xml');
  echo $books->book[0]->categories->category[1];
#### В46. Когда речь идет о значении переменной, в чем разница между NULL и пустым значением?
a)	NULL — пустое значение; пустое значение — отсутствие значения.
b)	Значение NULL имеет выделенный адрес в памяти; пустое значение — нет.
c)	NULL относится к отсутствию значения для целого числа; пустое относится к отсутствию значения для строки.
d)	NULL — отсутствие значения; empty — пустое значение.
В47. Какое название подойдет для функции ниже?
function doStuff($haystack, $needle) {
      $length = strlen($needle)
      if (substr($haystack, 0, $length) == $needle)
        return true;
      else
        return false;
}
a)	equals
b)	endsWith
c)	startsWith
d)	contains
#### В48. Если необходимо передать поле формы на другую страницу при нажатии кнопки, вам следует использовать ________. Если вы хотите хранить информацию на нескольких страницах, вам следует использовать __________?
a)	request; response
b)	response; request
c)	session; request
d)	request; session 
#### В49. Дан скрипт, который позволяет определить, нажата ли кнопка, но он никогда не возвращает true. Какой шаг, скорее всего, поможет решить эту проблему?
isset($_POST['submit'])
a)	Убедитесь, что поле ввода, отображающее кнопку, называется «submit».
b)	Убедитесь, что вы не пропустили ни одной точки с запятой.
c)	Распечатать все в сеансе print_r($_SESSION);
d)	Посмотрите в строке запроса в верхней части браузера, присвоено ли значение параметру submit.
#### В50. Почему следует придерживаться стандарта PSR?
a)	поскольку стандарты кодирования часто различаются между разработчиками и компаниями
b)	поскольку стандарты кодирования контролируются на предмет соответствия разработчикам и компаниям
c)	потому что существуют обязательные стандарты кодирования среди разработчиков и компаний
d)	при использовании определенных платформ, поскольку правила PSR применяются только к этим платформам
#### В51. Что такое геттеры и сеттеры?
a)	Геттеры и сеттеры гарантируют, что если член данных объявлен закрытым, то к нему можно получить доступ только внутри той же функции, а не из внешнего класса.
b)	Геттеры и сеттеры — это вспомогательные функции в PHP, которые позволяют загружать данные из базы данных и сохранять их в ней.
c)	Геттеры и сеттеры инкапсулируют поля класса, делая их доступными только через его закрытые методы, а сами значения оставляют открытыми.
d)	Геттеры и сеттеры — это методы, используемые для объявления или получения значений переменных, обычно закрытых.
#### В52. Какие рекомендуемые настройки в файле конфигурации PHP(php.ini) для среды тестирования?
a)
  report_errors = E_ALL
  display_errors = On
b)
  error_reporting = E_ALL
  display_errors = On
c)
  error_reporting = E_ALL & ~E_NOTICE
  display_errors = Off
d)
  error_reporting = E_ALL & ~E_NOTICE
  display_errors = On
#### В53. Какое имя переменной PHP недопустимо?
a)	$Double
b)	$double
c)	$_2times
d)	$2times
#### В54. Какая команда извлечет подстроку домена («com») из строки $string = "https://cat-bounce.com";?
a)	sub($string, -3)
b)	substr($string, -3)
c)	substr($string, 3)
d)	$string.substr(-3)
#### В55. Где выполняется PHP-скрипт?
a)	в браузере клиента
b)	в виртуальной машине
c)	в памяти компьютера, просматривающего веб-страницу
d)	на веб-сервере
#### В56. Какая из констант не является допустимой магической константой?
a)	__RESOURCE__
b)	__FUNCTION__
c)	__CLASS__
d)	__TRAIT__
#### В57. Что будет отображено на дисплее в результате выполнения скрипта?
  if( 1 == true){
        echo "1";
  }

  if( 1 === true){
      echo "2";
  }

  if("php" == true){
      echo "3";
  }

  if("php" === false){
      echo "4";
  }
a)	134
b)	13
c)	1
d)	123
#### В58. Когда следует использовать этот PHP-скрипт?
$secret_word = 'if i ate spinach';
setcookie('login', $_REQUEST['username']. ','. md5($_REQUEST['username'].$secret_word));
a)	когда пользователь собирается оплатить товар онлайн
b)	когда товары помещаются в корзину
c)	при первой регистрации
d)	при каждом входе в систему, в целях безопасности
#### В59. PHP "variable variable" принимает значение переменной и обрабатывает его как имя переменной. Например, если $var это переменная, то $$var это переменная переменной, имя которой является значением $var. Какой скрипт создает вывод ниже, используя переменную переменных?
Cat
Dog
Dog
a)
  $name = "Cat";
  $name = "Dog";
  echo $name . "<br/>";
  echo $$name . "<br/>";
  echo $Dog;
b)
  $name = "Cat";
  $$name = "Dog";
  echo $name . "<br/>";
  echo $$name . "<br/>";
  echo $Dog;

c)
  $name = "Cat";
  $$name = "Dog";
  echo $name . "<br/>";
  echo $$name . "<br/>";
  echo $Cat;
d)
  $name = "Cat";
  $$name = "Dog";
  echo $name . "<br/>";
  echo $name . "<br/>";
  echo $Cat;
#### В60. Представьте себе веб-приложение, созданное по архитектуре MVC, которое содержит тест и кнопку для его оценки. Когда пользователь нажимает кнопку «Оценить», какой компонент должен обрабатывать запрос?
a)	router
b)	controller
c)	model
d)	view
#### В61. Какой скрипт можно использовать для продолжения поиска музыки пользователем на разных веб-страницах?
a)
  <?php
      start_session();
      $music = $_SESSION['music'];
  ?>
b)
  <?php
      session_start();
      $music = $SESSION['music'];
  ?>
c)
  <?php
      start_session();
      $music =$session['music'];
  ?>
d)
  <?php
      session_start();
      $music = $_SESSION['music'];
  ?>
#### В62. Какой PHP-скрипт находит самую раннюю и самую позднюю даты из массива?
a)
  <?php
  $dates = array('2018-02-01', '2017-02-02', '2015-02-03');
  echo "Latest Date: ". max($dates)."\n";
  echo "Earliest Date: ". min($dates)."\n";
  ?>
b)
  <?php
  $dates = array('2018-02-01', '2017-02-02', '2015-02-03');
  echo "Latest Date: ". min($dates)."\n";
  echo "Earliest Date: ". max($dates)."\n";
  ?>
c)
  <?php
  $dates = array('2018-02-01', '2017-02-02', '2015-02-03');
  echo "Latest Date: ". ($dates)."\n";
  echo "Earliest Date: ". ($dates)."\n";
  ?>
d)
  <?php
  $dates = array('2018-02-01', '2017-02-02', '2015-02-03');
  echo "Latest Date: " max($dates)."\n";
  echo "Earliest Date: " min($dates)."\n";
  ?>
#### В63. Какой результат выполнения выражения в скрипте?
$kilometers = 1;
for (;;) {
    if ($kilometers > 5) break;
       echo "$kilometers kilometers = ".$kilometers*0.62140. " miles. <br />";
    $kilometers++;
}
a)
  kilometers = 0.6214 miles.
  kilometers = 1.2428 miles.
  kilometers = 1.8642 miles.
  kilometers = 2.4856 miles.
  kilometers = 3.107 miles.
b)
  kilometers = 0.6214 miles.
  kilometers = 1.2428 miles.
  kilometers = 1.8642 miles
  kilometers = 2.4856 miles.
  kilometers = 3.107 miles.
  kilometers = 3.7284 miles.
c)
  kilometers = 1.2428 miles.
  kilometers = 1.8642 miles.
  kilometers = 2.4856 miles.
  kilometers = 3.107 miles.
d)
FATAL ERROR синтаксическая ошибка, неожиданный ')', ожидается ';' в строке номер 2
#### В64. Как правильно импортировать несколько классов из пространства имен в одном объявлении в PHP 8?
a)	use myApp\myNamespace{ClassA, ClassB, ClassC};
b)	use myApp\myNamespace\ClassA, ClassB, ClassC;
c)	use myApp\myNamespace[ClassA, ClassB, ClassC];
d)	use myApp\myNamespace(ClassA, ClassB, ClassC);
#### В65. Какой наиболее полный список типов данных, поддерживаемых PHP?
a)	string, integer, float, boolean, array, object, NULL, resource
b)	string, integer, boolean, array, object, NULL, resource
c)	string, integer, float, array, object, NULL, resource
d)	string, integer, float, boolean, array, object, NULL
#### В66. К какому типу языка программирования относится PHP?
a)	серверный язык сценариев
b)	скомпилированный язык
c)	машинный язык
d)	алгоритмический язык
#### В67. Какая суперглобальная переменная содержит информацию о заголовках, путях и местоположении скриптов?
a)	$_SERVER
b)	$SERVER_VARIABLES
c)	$_ENV
d)	$GLOBALS
#### В68. Опишите, что произойдет, если запустить этот скрипт в тестовой среде.
$capitals = ['UK' => 'London', 'France' => 'Paris'];
echo "$capitals['france'] is the capital of France.";
a)	Выведет: «Paris is the capital of France.».
b)	Выведет: «is the capital of France.».
c)	Это вызывает синтаксическую ошибку, поскольку ключи массива в строке 1 заключены в кавычки.
d)	Это вызывает синтаксическую ошибку, поскольку ключ массива в строке 2 заключен в кавычки.
#### В69. DRY (Don't Repeat Yourself) — принцип разработки программного обеспечения, направленный на сокращение повторения шаблонов программного обеспечения. Какой вариант не является способом написания кода DRYer на PHP?
a)	наследование
b)	классы
c)	пространство имен
d)	инъекция зависимости
#### В70. Какой скрипт вернет IP-адрес клиента?
a)	$HTTP_SERVER_VARS("REMOTE_IP")
b)	$_SESSION["REMOTE_ADDR"];
c)	$_SERVER["HTTP_X_FORWARDED_FOR"]
d)	getenv("REMOTE_ADDR")
#### В71. Ваш сайт должен разрешать загрузку больших файлов. Что вам может требуется сделать?
a)	Убедитесь, что у пользователя есть необходимые разрешения.
b)	Ведите подсчет размеров загружаемых файлов и регистрируйте их.
c)	Измените upload_max_filesize параметр конфигурации.
d)	Обязательно используйте кодирование передачи по частям.
#### В72. Что выводит этот скрипт?
$my_text = 'The quick grey [squirrel].';
preg_match('#\[(.*?)\]#', $my_text, $match);
print $match[1]."\n";
a)	squirrel
b)	The quick grey [squirrel].
c)	[squirrel]
d)	The quick grey squirrel.
#### В73. Что выводит этот скрипт?
$fruits = ['apple', 'orange', 'pear', 'mango', 'papaya']; $i = 0; echo $fruits[$i+=3];
a)	mango
b)	apple
c)	a parse error
d)	pear
#### В74. Укажите основные типы ошибок в PHP?
a)	notices, warnings, fatal
b)	runtime, logical, compile
c)	semantic, logical, syntax
d)	warnings, syntax, compile
#### В75. Как правильно включить файл gravy.php в HTML- скрипт?
a)	<!-- include file="gravy.php"; -->
b)	<?php include gravy.php; ?>
c)	<?php include "gravy.php"; ?>
d)	<?php include file="gravy.php"; ?>
#### В76. Какие две функции могут очищать текст и проверять форматы текста?
a)	session_start()иfilter_input()
b)	filter_var()иfilter_input()
c)	preg_match()иstrstr()
#### В77. Почему не рекомендуется делать все переменные класса публичными?
a)	Это делает ваш код тесно связанным.
b)	Доступ к атрибуту может получить только класс, определяющий этот член.
c)	У вас не будет контроля над тем, какие значения может принимать атрибут. Любой внешний код сможет изменить его без каких-либо ограничений.
d)	После этого вы сможете получить доступ к атрибуту только внутри самого класса, а также путем наследования родительских классов.
#### В78. Вы хотите использовать подстановочные знаки при поиске записей в базе данных MySQL/MariaDB с использованием подготовленного оператора PDO. Какой код следует использовать?
a)	$statement->bindValue(':name', '%' . $_GET['name'] . '%');
b)	$statement->bindValue('%' . $_GET['name'] . '%', ':name');
c)	$statement->bindParam(':name', '%' . $_GET['name'] . '%');
d)	$statement->bindParam('%' . $_GET['name'] . '%', ':name');
#### В79. Создайте ассоциативный массив, используя $array1 в качестве ключей и $array2 в качестве значений
$array1 = ['country', 'capital', 'language']; $array2 = ['France', 'Paris', 'French'];
a)	$array3 = array_merge($array1, $array2);
b)	$array3 = array_union($array1, $array2);
c)	$array3 = array_keys($array1, $array2);
d)	$array3 = array_combine($array1, $array2);
#### В80. Предположим, что $r равен 255, а $g и $b равны 0. Укажите правильный скрипт для вывода «#ff0000»?
a)	printf('#%2x%2x%2x', 255, 0, 0);
b)	printf('#%2X%2X%2X', $r, 0, 0);
c)	printf('#%x%x%x', 255, 0, 0);
d)	printf('#%02x%02x%02x', 255, 0, 0);
#### В81. Вы хотите узнать, на какой день после Рождества 2025 года приходится Двенадцатая ночь. Какой код следует использовать?
a)	$xmas = new DateTime('Dec 25, 2025'); $twelfth_night = $xmas->add(new DateInterval('P12D')); echo $twelfth_night->format('l');
b)	$twelfth_night = strtotime('December 25, 2025 + 12 days'); echo date('d', $twelfth_night);
c)	$twelfth_night = strtotime('December 25, 2025 + 12 days'); echo strftime('%d', $twelfth_night);
d)	$xmas = new DateTime('Dec 25, 2025'); $twelfth_night = $xmas->add(strtotime('12 days')); echo $twelfth_night->format('D');
#### В82. Какой цикл выводит все числа от 1 до 10 включительно?
a)	$i = 1; while ($i < 10) { echo $i++ . '<br/>'; }
b)	$i = 0; while ($i <= 10) { echo $i++ . '<br/>'; }
c)	while ($i &lt;= 10) { echo ++$i . '<br/>'; }
d)	$i = 0; while ($i < 10) { echo ++$i . '<br/>'; }
#### В83. Какие типы управляющих структур существуют в PHP?
a)	break, continue, do-while, exception, for, foreach, if, switch, throw,while
b)	values, operators, expressions, keywords,comments
c)	for, foreach, if, else, else if, switch, tries, throws,while
d)	if-then-else, do-while, for-each, go-to,stop-when
#### В84. Какую функцию можно использовать при обработке ошибок для остановки выполнения скрипта и она эквивалентна exit()?
a)	die
b)	return
c)	throw
d)	break
#### Q85. Результат выполнения скрипта: расположение элементов в порядке убывания, вертикально и с пробелами между числами. Выберите правильный ответ.
$numbers = array(4,6,2,22,11);
sort($numbers);
$arrlength = count($numbers);
for($x = 0; $x < $arrlength; $x++){
    echo $numbers[$x];
    echo "<br />";
    }
a)	Это не соответствует всем критериям, поскольку результирующие числа будут «2461122», что не имеет определенного порядка.
b)	Это соответствует критериям, поскольку присутствует и sort() сортирует списки в порядке убывания.
c)	Это не соответствует всем критериям, поскольку функция sort() сортирует индексированный массив в порядке возрастания. Таким образом, этот код отобразит "2 4 6 11 22" вертикально, но числа будут разделены.
d)	не соответствует всем критериям, поскольку echo просто выводит числа массива в порядке, указанном в массиве $numbers, который является возрастающим
#### В86. Что не соответствует функции toString() PHP?
a)	Это экономит массу времени, необходимого для использования методов-сеттеров для доступа к значениям объектов.
b)	Это экономит массу времени, необходимого для использования методов-геттеров для доступа к значениям объектов.
c)	Он позволяет вызвать объект и увидеть его компоненты в виде строки.
d)	Он автоматически вызывается при использовании echo или print.
#### В87. Что такое генератор и как он используется в PHP?
a)	Генератор — это функция, которая создает ряд случайных значений для кода модульного тестирования.
b)	Генератор — это простой итератор, способный производить ряд результатов. Он имеет тот же синтаксис, что и функция, за исключением того, что он использует «next» вместо «return».
c)	Генератор — это простой итератор, способный выполнять ряд результатов. Он имеет тот же синтаксис, что и функция, за исключением того, что он использует «yield» вместо «return».
d)	Генератор — это функция, способная выдавать ряд результатов. 
#### В88. Выбрать описание, которое лучше всего описывает предназначение скрипта?
if( isset($user_info['url']) ) {
  $_SESSION["loggedIn"] = true;
  $_SESSION["username"] = $myusername;
  header('Location: ' . $user_info['url']); //Redirects to the supplied url from the DB
} else {
  header("Location: error.htm");
}
a)	При входе в систему он направляет всех пользователей на одну и ту же страницу.
b)	Это скрипт входа в пользовательский портал на веб-сайте.
c)	Он позволяет пользователю оставаться в системе в разных браузерах.
d)	Он перенаправляет пользователя на страницу с ошибкой, если он вводит неправильный URL.
#### В89. Что выводит этот скрипт?
echo 5 % 0.75;
a)	0
b)	0.6666666666667
c)	1
d)	fatal error (division by zero) 
#### В90. Можно ли расширить окончательно определенный класс?
a)	Нет, поскольку окончательное объявление класса или метода предотвращает переопределение дочернего класса или метода.
b)	Специализированные версии встроенных классов можно расширить, вызвав конструктор родительского класса.
c)	Да, если конечный класс определен как закрытый в родительском классе.
d)	Да, окончательно определенный класс можно использовать для объявления констант.
#### В91. Как проверить, установлен ли checkbox?
a)	Использовать!empty($_GET['test'])
b)	Использоватьisset($_GET['test'])
c)	Использовать$_GET['test'] == ''
d)	все ответы правильные
#### В92. Форма подписки на рассылку отправляется методом POST. В форме есть только одно поле: поле ввода текста с именем "email". Как проверить, пустое ли поле, и если пустое, вывести на сообщение: "The email cannot be empty"?
a)
if(empty($_POST['email'])) {
    echo "The email cannot be empty";
}
b)
if(empty($_GET['email'])) {
    echo "The email cannot be empty";
}
c)
if(empty($_POST('email'))) {
    echo "The email cannot be empty";
}
d)
if(isset($email)) {
    echo "The email cannot be empty";
}
#### В93. Что такое тип fatal error PHP?
a)	Возникновение этого типа ошибки приводит к прекращению выполнения скрипта.
b)	Причины возникновения ошибок такого типа не определяются компилятором и приводят к неверным результатам.
c)	Этот тип ошибок приводит к ошибочным результатам или может привести к завершению работы программы.
d)	Этот тип ошибки приводит к завершению работы после отображения списка ошибок и номера строки, в которой они произошли.
#### В94. Какой скрипт правильно проверяет указанный IP-адрес?
a)
$valid = ip2long($ip) !== false;
b)
$ip_address = "164.12.2540.1";
if(filter_var($ip_address, FILTER_VALIDATE_IP)){
  echo "$ip_address is a valid IP address";
} else {
  echo "$ip_address is not a valid IP address";
}
c)
$ip_address = "164.12.2540.1";
if(validate_ip($ip_address)){
  echo "$ip_address is a valid IP address";
} else {
  echo "$ip_address is not a valid IP address";
}
d)
$ip_address = "164.12.2540.1"
echo is_valid($ip_address, VALIDATE_IP);
#### В95. Что выводит этот скрипт?
    $i = 0;
    while($i < 6) {
    if($i++ == 3) break;
    }
    echo "loop stopped at $i by break statement";
a)	цикл остановлен на 3 с помощью оператора break
b)	цикл остановлен на 4 с помощью оператора break
c)	цикл остановлен на 6 с помощью оператора break
d)	цикл остановлен на 2 оператором break
#### В96. После создания объектов вы можете вызывать элементы функции, связанные с этим объектом, например, устанавливать имена и цены для трех объектов "Pet". Какой результат выполнения этого фрагмента скрипта?    
$dof->setTitle("Spot");
    $cat->setTitle("Mimi");
    $horse-?setTitle("Trigger");
    $dog->setPrice(10);
    $cat->setPrice(15);
    $horse->setPrice(7);
    print_r($cat);
a)	Pet Object ( [title]=> Spot[price]=>10)
b)	Pet Object ( [title]=> Mimi [price]=>15 )
c)	Pet Object ( [title]=> Mimi[price]=>10 )
d)	Pet Object ( [title]=> Trigger [price]=> 7)
#### В97. Учитывая представленный ниже ассоциативный массив, какой PHP-код определяет элемент массива «яблоко»?
$array = array(
'fruit1' => 'apple',
'fruit2' => 'orange',
'fruit3' => 'grape',
'fruit4' => 'apple',
'fruit5' => 'apple');
a)
while ($fruit_name = current($array)) {
    if ($fruit_name == 'apple') {
        echo key($array).'<br />';
    }
    next($array);
}
b)
while ($fruit_name = current($array)) {
    if ($fruitname == 'apple') {
        echo key($array).'<br />';
    }
    next($array);
}
c)
while ($fruit_name = current($array)) {
    if ($fruit_name == 'apple')
        echo key($array).'<br />';
    }
    next($array);
}
d)
while ($fruit_name = current($array)) {
    if ($fruit_name == 'apple') {
        echo key($array).'<br />';
    }
#### В98. Что возвращает этот скрипт?
class Smurf {

  public $name = "Papa Smurf";

  public function __construct($name) {
    $this->name = $name;
  }

  public function set_name($name) {
    $name = $name;
  }
}

$smurf = new Smurf("Smurfette");
$smurf->set_name("Handy Smurf");
echo $smurf->name;
a)	Handy Smurf
b)	Smurfette
c)	Papa Smurf
#### В99. У вас есть онлайн-форма с полем ввода под названием "image" для загрузки файлов. Путь к каталогу загрузки - $path, какой код следует использовать, чтобы убедиться, что файл загружен из вашей формы в необходимый каталог?
a)
if ($_FILES['image']['error'] === 0) {
      move_uploaded_file($_FILES)['image']['temp_name'],
          $path . $_FILES['image']['name']);
 )
b)
if ($_FILES['image']['error'] === false) {
      move_uploaded_file($_FILES)['image']['temp_name'],
          $path . $_FILES['image']['name']);
 )
c)
if ($_FILES['image']['error'] == 0) {
      copy($_FILES)['image']['temp_name'],
          $path . $_FILES['image']['name']);
 )
d)
if ($_FILES['image']['error'] == false) {
      upload_file($_FILES)['image']['temp_name'],
          $path . $_FILES['image']['name']);
 )
#### В100. Какая суперглобальная переменная содержит информацию о заголовках, пути и местоположении скриптов?
a)	$_GET
b)	$GLOBALS
c)	$_SESSION
d)	$_SERVER
#### В101. Используя цикл for, как написать PHP- скрипт для обратного счета от 10 до 1 в указанном порядке?
a)
<?
for ($i=1; $i <= 10; $i++) {
    echo $i;
}
?>
b)
<?
$i = 10;
while($i>=0) {
    echo $i;
    $i--;
}
?>
c)
<?
    for($i = 10; $i > 0; $i++) {
        print "$i <br />\n";
    } // end for loop '''
?>
d)
<?
    for($i = 10; $i > 0; $i--) {
        print "$i <br />\n";
    } // end for loop
?>
#### В102. Что выводит этот скрипт?
function knights(){
return "a shrubbery";
}

if (knights())
printf "you are just and fair";
else
printf "NI!";
a)	NI!
b)	a syntax error
c)	a shrubbery
d)	you are just and fair
#### В103. Какой скрипт определяет Россия как константу?
Наша страна — Россия. В нашей стране всего 9 федеральных округов.

a)
<?php
$country = 'Россия';
echo "Наша страна — {$country}. ";
echo "В нашей стране всего 9 федеральных округов.";
?>
b)
<?php
define('COUNTRY', 'Россия');
echo "Наша страна — " . COUNTRY . ". ";
echo "В нашей стране всего 9 федеральных округов.";
?>
c)
<?php
const $country = "Россия";
print "Наша страна — $country. ";
print "В нашей стране всего 9 федеральных округов.";
?>
d)
<?php
static string COUNTRY = 'Россия';
echo "Наша страна — {COUNTRY}. ";
echo "В нашей стране всего 9 федеральных округов.";
?>
#### В104. Что выводит этот скрипт?
try{
echo "bodacious";
throw new Exception();
} catch (Exception $e) {
echo "egregious";
} finally {
echo "excellent";
}
a)	bodacious excellent
b)	egregious excellent
c)	bodacious egregious excellent
d)	bodacious egregious
#### В105. Что выводит этот скрипт?
$believable = 'false';
$myth = ' Луна сделана из зеленого сыра.';
$calc = 10**3+1;
if ($believable) {
    echo $myth;
}
else {
    echo $calc;
}
a)	10000
b)	31
c)	1001
d)	Луна сделана из зеленого сыра
#### В106. Какая структура управления PHP используется внутри цикла, чтобы пропустить оставшуюся часть кода текущего цикла и вернуться к началу цикла для следующей итерации?
a)	return
b)	else
c)	break
d)	continue
#### В107. Что выводит этот скрипт?
$x = "5";
$y = &$x;
$y = "2$y";
echo $x;
a)	5
b)	2
c)	25
d)	Выведет сообщение об ошибке
#### В108. Какая функция используется для проверки существования файла в PHP?
a)	file_exists()
b)	is_file()
c)	file_check()
d)	Both file_exists() and is_file()
#### В109. Что выводит следующий код?
$array = array(1, 2, 3, 4, 5);
echo array_sum($array) / count($array);
a)	15
b)	3
c)	5
d)	Выведет сообщение об ошибке
#### В110. Какой из перечисленных способов НЕ является допустимым для начала сеанса PHP?
a)	session_start();
b)	$_SESSION = массив();
c)	session_begin();
d)	ini_set('session.auto_start', 1);
#### Вопрос 111. Каково назначение блока «finally» в структуре try-catch-finally?
a)	Для обработки исключений, которые не были перехвачены в блоке catch
b)	Чтобы определить пользовательские исключения
c)	Выполнять код независимо от того, было ли выброшено или перехвачено исключение
d)	Чтобы завершить блок try-catch
#### В112. Какую функцию использовать для удаления HTML-тегов из строки?
a)	html_clean()
b)	strip_tags()
c)	remove_html()
d)	sanitize_string()
#### В113. Что выводит этот код?
$str = "Hello";
$str[0] = "J";
echo $str;
a)	Hello
b)	Jello
c)	Выведет сообщение об ошибке
d)	H
#### В114. Какой из перечисленных методов НЕ является магическим в PHP?
a)	__construct()
b)	__destruct()
c)	__toString()
d)	__change()
#### В115. Для чего необходимо ключевое слово «yield» в PHP?
a)	Используется для определения абстрактных методов.
b)	Используется для приостановки выполнения функции.
c)	Используется для определения функций генератора.
d)	Используется для принудительной сборки мусора.
#### Вопрос 116. Какую функцию необходимо использовать для получения ASCII-кода символа?
a)	ascii()
b)	char_to_ascii()
c)	ord()
d)	ascii_val()
#### В117. Что выводит этот скрипт?
$a = array(1, 2, 3);
$b = array("one", "two", "three");
$c = array_combine($a, $b);
print_r($c);
a)	Array ( [0] => 1 [1] => 2 [2] => 3 )
b)	Array ( [0] => one [1] => two [2] => three )
c)	Array ( [1] => one [2] => two [3] => three )
d)	Выведет сообщение об ошибке
#### В118. Какой из следующих операторов НЕ является допустимым оператором сравнения PHP?
a)	===
b)	!==
c)	<>
d)	=>
#### В119. Что делает ключевое слово static при использовании внутри функции?
a)	делает функцию доступной для всего скрипта.
b)	сохраняет значение переменной между вызовами функции.
c)	предотвращает повторный вызов функции.
d)	ускоряет работу функции.
#### В120. Какую функцию требуется использовать для получения текущей временной метки в PHP?
a)	now()
b)	current_time()
c)	time()
d)	timestamp()
#### В121. Что выводит этот скрипт?
$str = "abcdef";
echo substr($str, -2, 1);
a)	f
b)	e
c)	ef
d)	de
#### В122. Какой из перечисленных способов комментирования в PHP НЕ является допустимым?
a)	// Однострочный комментарий
b)	/_ Многострочный комментарий _/
c)	# Комментарий в стиле Shell
d)	' Одинарные кавычки без закрытия комментария
#### В123. Что делает оператор instanceof в PHP?
a)	Проверяет, является ли переменная экземпляром класса.
b)	Создает новый экземпляр класса.
c)	Проверяет, существует ли класс.
d)	Проверяет, является ли объект экземпляром класса или интерфейса.
#### В124. Какую функцию использовать, чтобы проверить, является ли переменная массивом?
a)	is_array()
b)	array_check()
c)	typeof()
d)	is_array()
#### В125. Что выводит этот скрипт?
$x = 5;
$y = 10;
function myTest() {
    global $x, $y;
    $y = $x + $y;
}
myTest();
echo $y;
a)	10
b)	5
c)	15
d)	Выведет сообщение об ошибке
#### В126. Какая из следующих функций НЕ является допустимой функцией массива PHP?
a)	array_push()
b)	array_pop()
c)	array_shift()
d)	array_delete()
#### В127. Что делает ключевое слово final, если оно используется перед объявлением класса?
a)	Это делает класс абстрактным.
b)	Это предотвращает наследование класса.
c)	Это делает класс статичным.
d)	Он делает все методы в классе закрытыми.
#### В128. Какую функцию использовать для получения длины строки в PHP?
count()
 length()
 strlen()
 size()
#### В129. Что выводит этот скрипт?
$a = "Hello";
$b = &$a;
$b = "World";
echo $a;
a)	Hello
b)	World
c)	HelloWorld
d)	Выведет сообщение об ошибке
#### В130. Какой элемент HTML используется для определения заголовка документа?
a) <title>
b) <header>
c) <heading>
d) <top>
#### В131. Как правильно подключить внешний JavaScript файл script.js?
a) <script href="script.js">
b) <script name="script.js">
c) <script src="script.js">
d) <script file="script.js">
#### В132. Какой язык используется для стилизации веб-страниц?
a) HTML
b) JavaScript
c) Python
d) CSS
#### В133. Какой метод HTTP используется для получения данных с сервера?
a) POST
b) GET
c) PUT
d) DELETE
#### В134. Как создать многомерный массив в PHP?
a) array(array(1,2), array(3,4))
b) [1,2][3,4]
c) array[1,2][3,4]
d) {[1,2],[3,4]}
#### В135. Какая команда используется для создания новой виртуальной машины в Vagrant?
a) vagrant new
b) vagrant create
c) vagrant init
d) vagrant start
#### В136. Какая команда Git используется для создания новой ветки?
a) git create branch
b) git branch new
c) git branch
d) git checkout -b
#### В137. Что такое PDO в PHP?
a) PHP Data Objects
b) PHP Database Operations
c) PHP Data Operations
d) PHP Database Objects
#### В138. Как объявить константу в PHP?
a) const NAME = value;
b) constant NAME = value;
c) define('NAME', value);
d) set NAME = value;
#### В139. Какой цикл в PHP выполняется минимум один раз?
a) while
b) for
c) do...while
d) foreach
#### В140. Что означает аббревиатура MVC?
a) Model View Connection
b) Model View Controller
c) Model View Computer
d) Model View Class
#### В141. Как получить длину массива в PHP?
a) len()
b) length()
c) count()
d) size()
#### В142. Какой оператор используется для слияния строк в PHP?
a) +
b) .
c) &
d) &&
#### В143. Как правильно начать PHP-скрипт?
a) <php>
b) <?php
c) <?
d) <script php>
#### В144. Какой метод HTTP используется для обновления данных?
a) POST
b) GET
c) PUT
d) DELETE
#### В145. Как объявить функцию в PHP?
a) function myFunction()
b) def myFunction()
c) void myFunction()
d) new function()
#### В146. Какой тип базы данных чаще всего используется с PHP?
a) MongoDB
b) MySQL
c) SQLite
d) PostgreSQL
#### В147. Что такое Laravel?
a) CMS
b) Framework
c) Database
d) Programming Language
#### В148. Как получить значение из GET-запроса в PHP?
a) request.GET['name']
b) $_GET['name']
c) GET('name')
d) get.value('name')
#### В149. Какой тег используется для создания таблицы в HTML?
a) <table>
b) <tab>
c) <grid>
d) <tabular>
#### В150. Как проверить существование файла в PHP?
a) file_exists()
b) is_file()
c) check_file()
d) exists()
#### В151. Что такое Composer в PHP?
a) Text editor
b) Package manager
c) Framework
d) Database
#### В152. Как объявить переменную в PHP?
a) var x = 5;
b) let x = 5;
c) $x = 5;
d) int x = 5;
#### В153. Какая функция используется для перенаправления в PHP?
a) redirect()
b) header()
c) location()
d) goto()
#### В154. Как получить текущую дату в PHP?
a) date('Y-m-d')
b) getDate()
c) currentDate()
d) now()
#### В155. Что такое Ajax?
a) Programming language
b) Database
c) Asynchronous JavaScript and XML
d) Web server
#### В156. Как закомментировать строку в PHP?
a) // Comment
b) # Comment
c) /* Comment */
d) Все варианты верны
#### В157. Какой метод массива удаляет последний элемент в PHP?
a) pop()
b) array_pop()
c) remove_last()
d) delete_last()
#### В158. Как получить тип переменной в PHP?
a) typeof()
b) gettype()
c) type()
d) vartype()
#### В159. Что такое SVN?
a) Source Version Network
b) Subversion
c) Source Version Native
d) System Version Network
#### В160. Как создать сессию в PHP?
a) session_start()
b) start_session()
c) create_session()
d) $_SESSION.start()
#### В161. Какой порт по умолчанию используется для HTTP?
a) 8080
b) 443
c) 80
d) 3306
#### В162. Как подключить файл в PHP (с проверкой)?
a) include()
b) require()
c) import()
d) using()
#### В163. Что такое cookie в веб-разработке?
a) Session data
b) Browser cache
c) Small data stored on client
d) Server configuration
#### В164. Как получить последнюю ошибку MySQL в PHP?
a) mysql_error()
b) get_last_error()
c) mysqli_error()
d) db_error()
#### В165. Какой метод HTTP используется для удаления данных?
a) REMOVE
b) DELETE
c) UNLINK
d) DESTROY
#### В166. Как проверить, существует ли переменная в PHP?
a) exists()
b) isset()
c) has_var()
d) defined()
#### В167. Что такое XSS?
a) XML Style Sheet
b) Cross-site Scripting
c) Extended Style Sheet
d) External Server Script
#### В168. Как получить IP-адрес клиента в PHP?
a) getIP()
b) $_SERVER['REMOTE_ADDR']
c) ip_address()
d) client_ip()
#### В169. Какой тип данных не существует в PHP?
a) string
b) integer
c) char
d) boolean

Тема «Инструментальные средства разработки Internet-приложений»
#### В170. Какой язык разметки используется для создания структуры веб-страницы?
a) CSS
b) JavaScript
c) HTML
d) PHP
#### В171. Что такое DOM в контексте веб-разработки?
a) Digital Object Model
b) Document Object Model
c) Data Object Model
d) Document Oriented Model
#### В172. Какой фреймворк написан на Ruby?
a) Laravel
b) Django
c) Ruby on Rails
d) Express.js
#### В173. Какой паттерн проектирования используется в большинстве современных фреймворков?
a) Singleton
b) MVC
c) Factory
d) Observer
#### В174. Какой тип данных отсутствует в JavaScript?
a) Number
b) String
c) Integer
d) Boolean

Тема «Технологии управления крупными web-проектами» (В175-В179)
#### В175. Какая команда используется для клонирования репозитория в Git?
a) git clone
b) git copy
c) git pull
d) git fetch
#### В176. Что такое Vagrant?
a) Система контроля версий
b) Средство виртуализации
c) Web-сервер
d) База данных
#### В177. Какая команда создает новую ветку в SVN?
a) svn branch
b) svn create
c) svn copy
d) svn new
#### В178. Что такое VirtualBox?
a) Облачное хранилище
b) Система виртуализации
c) Веб-сервер
d) Система контроля версий
#### В179. Какая команда в Git используется для отправки изменений на удаленный сервер?
a) git commit
b) git push
c) git send
d) git upload

Тема «Способы и средства тестирования и размещения web-проекта на хостинге»
#### В180. Какой протокол используется для безопасной передачи данных в web?
a) HTTP
b) FTP
c) HTTPS
d) SMTP
#### В181. Какой порт по умолчанию используется для FTP?
a) 80
b) 21
c) 443
d) 3306
#### В182. Что такое IP-адрес версии IPv4?
a) 32-битный адрес
b) 64-битный адрес
c) 128-битный адрес
d) 16-битный адрес
#### В183. Какой метод HTTP используется для отправки конфиденциальных данных?
a) GET
b) POST
c) PUT
d) HEAD
#### В184. Что такое DNS?
a) Data Network Service
b) Domain Name System
c) Digital Network Service
d) Domain Network Service

