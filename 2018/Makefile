rename:
	for i in `find . -type f -name "*\?*"`; do mv "$$i" "`echo $$i | cut -d? -f1`"; done

assets:
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/css/href="\/2018\/css/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/public/href="\/2018\/public/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/images/href="\/2018\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="\/images/src="\/2018\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="images/src="\/2018\/images/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/src="\/js/src="\/2018\/js/g'
# 	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/lt/href="\/2018\/lt/g'
# 	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/en/href="\/2018\/en/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/a href="\//a href="\/2018\//g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.json' -type f -print0 | xargs -0 sed -i '' -e 's/\/2018\/2018/\/2018/g'
	find . -name '*.css' -type f -print0 | xargs -0 sed -i '' -e "s/url('\/images\//url('\/2018\/images\//g"
