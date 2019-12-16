# solopicker
Javascript Simple DateTimePicker


This a single file datetimepicker without any library.



How to use:

HTML Code:
&lt;input id="datetimepicker"&gt; <br/>
JS Code:
Show Hour and Minute <br/>
datetimepicker('#datetimepicker'); <br/> 
datetimepicker({
  'target': '#datetimepicker',
	'time': true
}); <br/>

Hide Hour and Minute <br/>
datetimepicker({
  'target': '#datetimepicker',
	'time': false
}); <br/>
