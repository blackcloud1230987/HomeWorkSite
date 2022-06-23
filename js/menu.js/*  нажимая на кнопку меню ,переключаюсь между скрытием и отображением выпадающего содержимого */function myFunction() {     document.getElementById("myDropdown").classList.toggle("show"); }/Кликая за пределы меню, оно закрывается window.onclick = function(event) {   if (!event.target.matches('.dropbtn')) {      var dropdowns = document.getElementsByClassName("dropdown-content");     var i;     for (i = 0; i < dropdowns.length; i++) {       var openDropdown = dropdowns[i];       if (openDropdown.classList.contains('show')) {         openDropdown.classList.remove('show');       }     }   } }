/*  нажимая на кнопку меню ,переключаюсь между скрытием и отображением выпадающего содержимого */
function myFunction() {
    document.getElementById("myDropdown").classList.toggle("show");
}

// Кликая за пределы меню, оно закрывается
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {

    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
