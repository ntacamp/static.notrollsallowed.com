all: build

build:
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.gif' ! -name '*font*' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/apie/href="\/2013\/apie/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.gif' ! -name '*font*' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/vieta/href="\/2013\/vieta/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.gif' ! -name '*font*' -type f -print0 | xargs -0 sed -i '' -e 's/href="css/href="\/2013\/css/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.gif' ! -name '*font*' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/components/href="\/2013\/components/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.gif' ! -name '*font*' -type f -print0 | xargs -0 sed -i '' -e 's/href="\/assets/href="\/2013\/assets/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.gif' ! -name '*font*' -type f -print0 | xargs -0 sed -i '' -e 's/src="\/assets/src="\/2013\/assets/g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.gif' ! -name '*font*' -type f -print0 | xargs -0 sed -i '' -e 's/a href="\//a href="\/2013\//g'
	find . ! -name '.*' ! -name '*.css' ! -name '*.js' ! -name '*.png' ! -name '*.jpg' ! -name 'Makefile' ! -name '*.txt' ! -name '*.gif' ! -name '*font*' -type f -print0 | xargs -0 sed -i '' -e 's/\/2013\/2013/\/2013/g'
	find . -name '*.css' -type f -print0 | xargs -0 sed -i '' -e "s/url('\/images\//url('\/2013\/images\//g"
