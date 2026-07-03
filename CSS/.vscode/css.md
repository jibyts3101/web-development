2. combined Selector:-
---------------------
    -> It is combination of two or more than two simple selectors.

    1.descendant Selector:
        <div class="header">
        <h1>hi </h1>
        <div class="section">
        <h1>bye</h1>
        </div>>
        </div>

        .header h1{
            text-align:"center";        
            
        }

        -> This selector is used to target all the descendant of a particular element.
        -> It target the child, grand child, great grand child and so on.


    2. Direct child selector:-
        -> This selector is used to target direct/immediate children of the parent element.
        eg:
            .header > h1{
                color:red;
            }
            .header > .section > h1{
                color:green;
            }

    3. Adjacent sibiling:
        <ul>
        <li id="first">list 1</li>
        <li>list 2</li>
        <li>list 3</li>
        </ul>

        ul > #first+h1{
            color:red;
        }

        -> It will target the immediate next sibling element.
        -> i targets only one element.


    4.General siblings:
        It will target all sibiling after that selected

        eg:
            ul> #first~li{
                font-style:italic;
            }
