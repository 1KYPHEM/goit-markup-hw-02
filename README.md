.prettierrc.json

{
	 "printWidth": 80,
	 "tabWidth": 2,
	 "useTabs": false,
	 "semi": true,
	 "singleQuote": true,
	 "trailingComma": "es5",
	 "bracketSpacing": true,
	 "jsxBracketSameLine": false,
	 "arrowParens": "avoid",
	 "proseWrap": "always"
	}

	https://validator.w3.org/nu/#textarea Перевіряємо код валідатор
	https://tinypng.com/ оптимізуймо картинки
	https://squoosh.app/ оптимізуймо картинки
	https://html.spec.whatwg.org/multipage/named-characters.html спец символи
	https://www.toptal.com/designers/htmlarrows/symbols/ спец символи
	https://docs.emmet.io/cheat-sheet/ швидкі команди Emmet
	https://caninclude.glitch.me/ вкладеність тегів
	git status - перевірити статус файлі по відношенню до віддаленого репозиторію 
	git add --all - добавити всі зміни 
	git commit -m "up" - добавити коментар до відпрацьованої частини проекту (якщо працюємо з кимось)
	git push - відправити зміни в репозиторій
	
	index.html
	styles.css
	prettier.json
	petro.png
	
	<!DOCTYPE html>
	<html lang="en">
	  <head>
		<meta charset="utf-8" />
		<meta name="description" content="Learning the basics of HTML for beginners" />
		<title>Текст, розміщений всередині тега <title>, відображається як назва вкладки браузера.</title>
	  </head>
	  <body>
		<!-- Вміст-->
	  </body>
	</html>
	name="description" Цей атрибут визначає, що тип метаінформаціїї у цьому тегу — опис вмісту сторінки.
	content="..." де значення — це короткий опис вмісту сторінки.
	Атрибути name та content йдуть у парі, як тип + значення.
	
	<!-- Заголовок, абзац, список, елементи списка -->
	<h1>Заголовок (может быть только один в коде) каждый след. h2, h3 </h1>
	<p>Описание, текст</p>
	<ol>нумерований перелік переваг</ol>
	
	<ul>
		<li>
			<a href="https://rabota.ua/">Посилання 1</a>
		</li>
		<li>
			<a href="https://jobs.dou.ua/">Посилання 2</a>
		</li>
	</ul>
	
	<a href="Ссылка" target="_blank">Значение ссылки</a>
	
	<section>
	<h2>Our Team</h2>
	<ul>
	<li>
	<img src="./images/img-3.jpg" alt="Mark Guerrero" width="264" height="260">
	<h3>Mark Guerrero</h3>
	<p>Product Designer</p>
	</li>
	</ul>
	</section>
	
	<address>
	  <a href="mailto:mango@mail.pig">mango@mail.pig</a><br />
	  <a href="tel:+11112223344">+1(111) 222-33-44</a><br />
	  м. Київ, <br />
	  Бульвар Лесі Українки, буд. 26, <br /> 
	  4й поверх офіс 427
	</address>
	Контактну інформацію розбито на рядки тегом <br />
	
	<a
	  href="https://goo.gl/maps/qBnEfK5AingPLZgb9" 
	  target="_blank">При натисканні посилання відкривається у новій вкладці браузера
	</a>
	
	<button type="button">Open sidebar</button>
	
	<!-- Після -->
	<main>
		<h1>Dental clinic website</h1>
		
		<section>
			<h2>About</h2>
			<p>Вміст секції About</p>
		</section>
		
		<section>
			<h2>Features</h2>
			<p>Вміст секції Features</p>
		</section>
		
		<section>
			<h2>Team</h2>
			<p>Вміст секції Team</p>
		</section>
		
		<section>
			<h2>Testimonials</h2>
			<p>Вміст секції Testimonials</p>
		</section>
	</main>
	
	
	Нехай кожна іконка буде 32 пікселя за висотою та шириною. При натисканні на посилання сторінки соцмереж повинні відкриватися в новій вкладці браузера. Використовуй наступні посилання на іконки та альтернативний текст.
	<footer>
	  <ul>
		<li>
		  <a href="https://www.instagram.com/" target="_blank">
			<img
			  src="https://ac.goit.global/fullstack/html-css-v2/module-1/autocheck/b04insta.svg"
			  width="32"
			  height="32"
			  alt="Instagram"
			/>
		  </a>
		</li>
		<li>
		  <a href="https://www.facebook.com/" target="_blank">
			<img
			  src="https://ac.goit.global/fullstack/html-css-v2/module-1/autocheck/b04facebook.svg"
			  width="32"
			  height="32"
			  alt="Facebook"
			/>
		  </a>
		</li>
		<li>
		  <a href="https://www.youtube.com/" target="_blank">
			<img
			  src="https://ac.goit.global/fullstack/html-css-v2/module-1/autocheck/b04youtube.svg"
			  width="32"
			  height="32"
			  alt="YouTube"
			/>
		  </a>
		</li>
	  </ul>
	</footer>