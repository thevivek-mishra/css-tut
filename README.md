# css flexbox for 1D layout design

for parent

            display: flex;
            flex-direction: row | row-reverse | column | column-reverse;
            flex-wrap: nowrap | wrap | wrap-reverse;
            justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe;
            align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end + ... safe | unsafe;

            align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline + ... safe | unsafe;

            gap: 10px;
            gap: 10px 20px; 
            row-gap: 10px;
            column-gap: 20px; 

for children    


            
            order: 5;
            flex-grow: 4; 
            flex-shrink: 3;
            flex-basis:  | auto;
            flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]
            align-self: auto | flex-start | flex-end | center | baseline | stretch;

### Position



