.DEFAULT_GOAL = default

default:
	@ echo default target
	cp modern-pdf.html modern-html.html
	sed "s{/\*letter-spacing:\ 5px\;\ PDFs\ hate\ letter-spacing\ \*/{letter-spacing:\ 5px\;\ /\*\ PDFs\ hate\ letter-spacing\ \*/{" < modern-pdf.css > modern-html.css
