all: download rename assets

download:
	cd pranesimai && wget -O index.html https://2015.notrollsallowed.com/pranesimai && cd ..

rename:
	for i in `find . -type f -name "*\?*"`; do mv "$$i" "`echo $$i | cut -d? -f1`"; done

assets:
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/css/href="\/2015\/css/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/public/href="\/2015\/public/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/images/href="\/2015\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="\/images/src="\/2015\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="images/src="\/2015\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="\/js/src="\/2015\/js/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/a href="\//a href="\/2015\//g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/\/2015\/2015/\/2015/g'
	find . -name '*.css' -type f -print0 | xargs -0 sed -i '' -e "s/url('\/images\//url('\/2015\/images\//g"
