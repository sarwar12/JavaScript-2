# JavaScript-2

### JavaScript Work:

	1) You can write in HTML with js:
	           (EX) <h1><script>document.write('This is my Home!')</script></h1>
		<p><script>document.write('This is my Home!')</script></p> 

	------------------------------------------------------------------------------------------------
	2) Variable :

		var myname="Sarwar Khan";
		document.write(myname + '<br />');

	       (i) With Sum,Minus,Multiple, Divided:
		var a = 5;
		var b = 4;
		var sum = a+b;
		var min = a-b;
		var pro = a*b;
		var div = a/b;
		document.write(sum);
		document.write(min);
		document.write(pro);
	   (or) document.write(sum + min + pro + div );
	--------------------------------------------------------------------------------------------------------
	3) Function:
	
		var color = "green"    		(Global Variable)
		function myself(){
			var color = "yellow"   	 ( Local Variable)
			document.write(color);
			document.write('<br/>');
		}
		myself();     		 (you call Function Name)
		document.write(color);

	(Note) You Create Local To Global  (you just remove local "var" word and you get Global Variable) 
		var color = "green"    		(Global Variable)
		function myself(){
			color = "yellow"   	 ( Global Variable)
			document.write(color);
			document.write('<br/>');
		}
		myself();     		 (you call Function Name)
		document.write(color);
***

### javaScript Output show :
	1) innerHTML (its define HTML Element)
		var a = 'g sarwar ';
		var b = 'nahin';
		var myname = a+b;
		document.getElementById('show').innerHTML = myname;
	----------------------------------------------------------------------------------
	2) document.write();
		var a = 'g sarwar ';
		var b = 'nahin';
		var myname = a+b;
		document.write(myname);
	--------------------------------------------------------------------------------
	3) window.alert();  or alert();
		var a = 'g sarwar ';
		var b = 'nahin';
		var myname = a+b;
		window.alert(myname); 	(OR)      alert(myname);
	 Note:: Its showing popup window on screen.
	---------------------------------------------------------------------------------------
	4) console.log(); 
		var a = 'g sarwar ';
		var b = 'nahin';
		var myname = a+b;
		console.log(myname);
	 Note:: Its show Browser Developer Tool console

	(***) More On Console command: (its text browser console panel)
		console.info('You have a nice information.');   ---> Its show information icon.
		console.warn('Do you go here');   --> Its show warning icon.
		console.error(Its Undefined);  --> Its show error (x) icon.
	(***) You showing variable/function run/excutive time;
		console.time('Check Time');
		var sum = 5+2;
		console.log(sum);
		console.timeEnd('Check Time';) 
***

### Include variables Symbole:
	concate/concatination --> +
	
### Function Scope:: (In JavaScript there are two types of scope)
	1) Local Scope
	2) Global Scope

### Sanke Case:  (use underscore ( _ ) Symbol )
	one_two 

### Camel Case: (Use first word Uppercase and other lowercase)
	One
	oneTwo
***	
## G SARWAR
#### Web Instructor
