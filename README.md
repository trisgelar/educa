# README

Educa App From Django 2.0 by Examples 
By Antonio Mele

### PREV TEST DB
```
	GRANT ALL PRIVILEGES ON test_ujang_educa.* TO 'ujang_educa'@'localhost';
	REVOKE ALL ON test_ujang_educa.* FROM 'ujang_educa'@'localhost';	
```

### Git Push
```
	git remote add origin https://github.com/trisgelar/educa.git
	git push -u origin master
```

### DumpData
```
	python manage.py dumpdata courses --indent=2 --output=courses/fixtures/subject.json
	python	manage.py loaddata subjects.json
```