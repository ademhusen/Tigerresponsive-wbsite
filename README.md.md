Const header=document.querySelector(header);
Window.addEventListener ("Scroll", function() {
    header.ClassList.toggle ("stickly", window.scrollY> 100);
});