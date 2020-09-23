## JQuery
Targeting elements: by type: $("button"), by class: $(".btn"), and by id $("#target1")

### Add Class to Element
```
.addClass("classNames")
```
### Remove Class from Element
```
.removeClass("className")
```
### Add css
```
.css('color', 'red')
```
### Adjust the properties of elements.
```
$("button").prop("disabled", true);
```
### Add Html or Text
```
.html("<em>Welcome</em>")
.text("Welcome")
```
### Remove an Element from HTML
```
$("#target4").remove()
```
### Select HTML elements and append them to another element
```
$("#target2").appendTo("#right-well");
```
### Copy of an element
```
$("#target2").clone().appendTo("#right-well");
```
###  Access the parent
```
$("#left-well").parent().css("background-color", "blue")
```
### Access the children
```
$("#left-well").children().css("color", "blue")
```
### Targeting the right elements
Usin CSS Selectors
```
$(".target:nth-child(3)").addClass("animated bounce");
```
### Target Even Elements
```
//:odd or :even
$(".target:odd").addClass("animated shake");
```
### Target Body
```
$("body").addClass("animated hinge");
```
