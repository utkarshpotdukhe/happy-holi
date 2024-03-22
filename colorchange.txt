window.addEventListener("load", function() {
  let holiValue = 0;
  setInterval(function() {
    holiValue += 10; 
    document.querySelectorAll('.holi').forEach(function(element) {
      element.style.filter = 'hue-rotate(' + holiValue + 'deg)';
    });
  }, 100); 
});
