rename:
	for i in `find . -type f -name "*\?*"`; do mv "$$i" "`echo $$i | cut -d? -f1`"; done

assets:
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/css/href="\/2017\/css/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/public/href="\/2017\/public/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/images/href="\/2017\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="\/images/src="\/2017\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="images/src="\/2017\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="\/js/src="\/2017\/js/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/a href="\//a href="\/2017\//g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/\/2017\/2017/\/2017/g'
	find . -name '*.css' -type f -print0 | xargs -0 sed -i '' -e "s/url('\/images\//url('\/2017\/images\//g"
