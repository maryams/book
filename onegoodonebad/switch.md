
#Using Switch Statement Rather than If/Or Statements#

Using switches can be a great way to simplify more complicated else if statements in Javascript. It is a mechanism through which to keep your code neat and easily adjustable.

Modern Web recommends that you use this whenever you have more than two cases. 

Bad:
	if (example_variable == "cyan") {  
	    // do something here...  
	} else if (example_variable == "magenta") {  
	    // do something here...  
	} else if (example_variable == "yellow") {  
	    // do something here...  
	} else if (example_variable == "black") {  
	    // do something here...  
	} else {  
	    // do something here...  
	}  

Good:
	switch (example_variable) {  
	    case "cyan":  
	        // do something here...  
	        break;  
	    case "magenta":  
	        // do something here...  
	        break;  
	    case "yellow":  
	        // do something here...  
	        break;  
	    case "black":  
	        // do something here...  
	        break;  
	    default:  
	        // do something here...  
	        break;  
	}  
Breaks sole purpose is in my understanding to stop the code from running through the rest of the switch-case.

The second block of code does the exact same thing as the first — but the second one is cleaner, easier to read, and easier to maintain and modify.


Sources: 
http://modernweb.com/2013/12/23/45-useful-javascript-tips-tricks-and-best-practices/

http://programmers.stackexchange.com/questions/201777/break-on-default-case-in-switch
