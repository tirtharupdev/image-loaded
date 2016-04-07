To implement this plugin,

/* Without jQuery */

document.querySelector('selector').imgLoad({
    complete : function(){
                          /* All images have been successfully loaded. */
              }
});

/* With jQuery */

jQuery('selector').imgLoad({
    complete : function(){
                          /* All images have been successfully loaded. */
              }
});
