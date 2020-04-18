tex_files = $(wildcard *.tex)

epub_files = $(tex_files:.tex=.epub)
pdf_files = $(tex_files:.tex=.pdf)

all: $(epub_files) $(pdf_files)

%.pdf: *.tex
	pdflatex $^

%.epub: *.tex
	pandoc -s $^ -o $@

.PHONY: clean

clean:
	-rm *.aux *.log *.epub *.log *.aux *.pdf
