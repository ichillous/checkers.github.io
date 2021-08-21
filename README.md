# Tic Tac Toe

Play 1 v 1 against your best friend, wife or mother in law. 

## Installation

No need to install anything. You can fork and clone this repo and you'll be able to deploy this in live server. 



## Snippet

```javascript


$("button").click(function() { // Reset button
    if($(this).hasClass("fa fa-times") || // Check if the button has the cross sign
            $(this).hasClass("fa fa-check")) // Check if the button has the check sign
    {       
        $(this).css("background-color", "red");
        setTimeout(() => {
            $(this).css("background-color", "white"); // Reset the button color
        }, 800);        
    }
});
```



