# fetch take-home exercise
requirements:<br>
<pre>
Python 3.9.6
requests 2.28.1
</pre>

python libraries:
<pre>
requests
yaml
time
collections
</pre>

Fixes:
<pre>
  1. Default method is not defined, Added condition to use GET if not defined
  2. Added Condition to check if reponse time is < 500 
  3. Added code to ignore port in url
  4. Added condition to only accept yaml file as argument
</pre>

execution:<br>
<pre>
python3 main.py file.yaml
</pre>
