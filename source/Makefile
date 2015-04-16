run:
	cp -R static-files/* ..
	pelican -t theme -s settings.py -o .. content
	cp ../pages/* ../
	rm -rf ../pages/

init:
	pip install -r requirements.txt
