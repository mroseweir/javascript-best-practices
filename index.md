Avoid mixing with other technologies
    Even though you can do everything you would like to using JavaScript, it is not the most effective way of doing so. 

Avoid heavy nesting your code
    Although nesting your code can make it easier to read, nesting it too far can also make it hard to follow what you are trying to do.

Dont yield to browser whims
    Dont write code specific to one browser. It is a sure-fire way to keep your code hard to maintain and make it get dated really quickly. This causes issues when new browsers come out, and code that worked on one browser doesnt work on the new browser. 

Dont trust any data
    Make sure that the data that you are using from the web works exactly how you need it to. It needs to be secure as well as complete the task that you are trying to complete. 

        Source for 1-4: https://www.w3.org/wiki/JavaScript_best_practices


Avoid Global Variables
    This causes an issue because you run the danger of your code being overwritten by any other JavaScript added to the page after yours. 

Comment as much as needed, but not more. 
    "Comment what you consider needed - but dont tell others your life story."
    Also, use */ when commenting out a line, because if you use // as a line break, and the break is removed, it can cause errors. 

Use shortcut notations
    This will make your code easier to read. 

    var lunch = new Array();
    lunch[0]='Dosa';
    lunch[1]='Roti';
    lunch[2]='Rice';
    lunch[3]='what the heck is this';

    is the same as

    var lunch = [
        'Dosa',
        'Roti',
        'Rice',
        'what the heck is this?'
    ];

Keep your code modularized and specialized
    This is important when writing functions. Although it is nice to have one function that does everything, if you extend functionality you will find that you do the same things in several functions. 

Sources for 5-8: https://www.thinkful.com/learn/javascript-best-practices-1/#Modularize

Comment your code often
    Helps make the code easier to read. Helps future users be able to see what you were trying to accomplish. 

Use Script Mode to catch silent errors
    SCript mode has a few things that will fix mistakes that prevent JavaScript from optimizing your code. Silent errors that would previously make it past the compiler now throw errors, allowing you to fine-tune your code before it reaches your team members

Source for 9-10:  https://www.educative.io/blog/javascript-tips-simplify-code
