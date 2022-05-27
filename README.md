# CF-05.BootStrapContactFormProject

## *Address book project using bootstrap, HTML5, and CSS*<hr>

## Technologies Used:
- Shell and scripting language: Powershell
- Frontend: HTML5, CSS, Bootstrap
<hr>

## Challenges
- initializing CSS
- creating dropdown
- creating checkbox
- Responsiveness
- Formatiing image
<hr>

## Attempt vs. Solution
![Attempt](img/Attempt.png)
![Solution](img/Solution.png)<hr>

## Solution

- Add the bscf-template-base
- Link CSS style sheet
- remove the body text
- Copy CSS code form uiGradient
- Navigate to CSS style sheet and create a body tag (do not put a period before it) and paste the CSS
- THE HTML PAGE WILL BE BLANK UNTIL YOU ADD CONTENT. You can add a height class to html tag and body tag to generate the background.
- add a header with the document name
- Create a new div, this will be the container for our form, and give it the following class: border border-2 shadow-lg p-2 bg-light *don't forget to make sure div's are properly wrapped
- create a form with a class of row g-3 p-2
- Set up two columns and perform the scaffolding to make sure the divs are properly nested
  ```
  
                   <div class="row">            --->    <div class="row">
                       <div class="col"></div>  --->        <div class="col">
                       <div class="col"></div>  --->        
                   </div>                       --->        </div>
                                                --->        <div calss="col">
                                                --->
                                                --->        </div>
                                                --->    </div>                    
  ```


- Taking a look at the reference we can see the image takes up a third of the container, therefore give the images column a width of 12 with a medium breakpoint of 4 and the address book container a column width of 12 with a medium breakpoint of 8
- add an image tag and give it a class of img-fluid (resposnive design); add the image source
- inside the second column container create another div with a row class
- We can use the column wrapping function built into bootstrap, this will allow us to create multiple columns with only using one row by setting some of the columns to six and if a column goes over 12 units it will automatically wrap.
- create two columns and give them a column size of 6 with a medium breakpoint. This will hold our first name and last name. Due to us using the built in styling in bootstrap, we need to ensure our labels have a name attached that's the same so they can share the styling
  ```
  <label for="inputFirstName" class="form-label">First Name</label>
  ```


- create our input and give it a type of text, a class of form-control, an id of inputFirstName (this matches the for class)
- follow the same process for the last name section
- Knowing that columns wrap after 12 units we can continue to create columns
- Create two 12 unit columns with 6-unit medium breakpoints columns and repeat the label and input steps for the email and phone fields
- create two 12 unit columns and repeat the process for the address 1 and address 2 fields
- Create three more 12-column divs medium colum breakpoints at 6, 4, and 2 units
- City will have a label and input
- State will have a label and a new tag called select, the id will be inputState and class will be form select and will have a class of form-select 
  - copy and paste the state html and all of the select options will have the tag option
- For the zip you will have a label and an input
- To create the checkbox create a 12-unit column and give it a div class called form-check
  - inside the check give it an input and class of form-check-input, a type of checkbox, and an id of checkFamily
  - give the checkbox a label with a class of form-check-label and a for classifcation of checkFamily, and name it Family
- Finally to create the button create a div class with a 12-unit column, dflex, and justify-conent-end
  - create the button with a type of button and a class of btn btn-lg btn-primary and name it Save
- To make the mobile modification
<hr>

## Credits
### Project References
  
- <a href="https://uigradients.com/">uiGradients</a>
- <a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet">Bootstrap Docs</a>
  
<hr>

## License
<hr>
