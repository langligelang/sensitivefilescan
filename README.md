# sensitivefilescan #

## introduce ##
- this tools can be searched web leak files

## install && environment ##

- python 2.7
- pip install -r requirements.txt

## usage ##

**1. scan single target **
	python sensitivefiles.py "http://www.baidu.com" -e 'php' -t 40 -d 10
**2. scan multiple target **
	python sensitivefiles.py -f example.txt
**3. scan whatweb --log-json result **
	python sensitivefiles.py --log-json test.json

## note ##

- 这里的字典都是自己精挑细选出来的，大家有好的字典或者bug,可以提交issue或者merger代码


