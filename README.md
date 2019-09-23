# DOM-Node-Inserted-Mutation-Event

$(window).on('DOMNodeInsertedIntoDocument', function(){
  console.log('DOMNodeInsertedIntoDocument occurred');
});

$(window).on('DOMNodeInserted', function(){
  console.log('DOMNodeInserted occurred');
});

 jQuery('body').on('DOMNodeInserted', '#x-slider-testimonial', function(e) {
       console.log('DOMNodeInserted occurred');
 });
