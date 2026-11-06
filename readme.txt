origin	git@github.com:kpharck/CriseTribunalConstitutionelPolonais.git

sudo apt update
sudo apt install pandoc texlive-xetex

pandoc input.md -o output.pdf --pdf-engine=xelatex
