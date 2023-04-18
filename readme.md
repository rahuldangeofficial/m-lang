# मराठीLang - you can write code in मराठी!
## Syntax & Documentation  

##### [important] Semicolon are mandatory. 


### Variable Declaration & Assignment  

    ऐका x आहे "therahuldange";
    ऐका x आहे 0;
    ऐका x आहे 5.5;
    ऐका x आहे खरे; /* खरे means true */
    ऐका x आहे खोटे; /* खोटे means false */
    
    /* ऐका perform declaration */
    /* आहे perform assignment */

### Showing output

    दाखवा(10); 
    /* shows output as 10 */

### Arithmetic Expressions  

    दाखवा(10 अधिक 2); /* 12 */ 
    /* अधिक perform addition */

    दाखवा(10 वजा 2); /* 8 */
    /* वजा perform subtraction */

    दाखवा(10 गुणिले 2); /* 20 */
    /* गुणिले perform multiplication */ 

    दाखवा(10 भागिले 2); /* 5 */
    /* भागिले perform division */

### Conditional Statements

    जर(खरे) {       
      दाखवा(1);
    }
    
    जर(खरे) {       
      दाखवा(1);
    }अन्यथा{
      दाखवा(0);
    }

### Loops 

    लूप(ऐका i आहे 0; i < 10; i आहे i अधिक 1){
      दाखवा(i);
    };  

    असताना(खोटे){
        दाखवा(1);
    }

    करा{
      दाखवा(1);
    }असताना(खोटे);

### Functions 
    
    कार्य reflect(yourName){
      परतकरा yourName; 
    }

    दाखवा(reflect('rahul'));

### Switch Cases

    ऐका x आहे 0;

    स्विच(x) {
       समान 0:
        दाखवा(0);
        थांबा;
       समान 1:
        दाखवा(1);
        थांबा;
       डीफॉल्ट:
        दाखवा(x);
    }


    /*  "थांबा" work like break */
    /* "पुढेजा" work like continue */
    