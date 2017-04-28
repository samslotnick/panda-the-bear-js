1

var pic = $('img.profile-image');
pic.replaceWith("<img src='http://www.pngall.com/wp-content/uploads/2016/06/Alien-PNG-Clipart.png'>");

2
$('.bio-info-name').text( "Sam");

3
$( 'div > h3').text("Rawr");

4
$( '#time-travel').remove();

5

$('body').css("background","black");


6

$('.highlight').css("color","red");

7

$('h1').css("font-family","monospace");


8

$('.action-icon-bg').css("background-color", "red");

9
$('#name').replaceWith('<input type="text" name="name" class="contact-info" id="name" placeholder="Identify Yourself">');


10


$('#message').attr('placeholder',"State Your business");

11
$('#name').attr('value', "your nemesis");

12

$('#email').attr('value', "koalathebear@gmail.com");

13
$('#submit').attr('value', "En Garde!");
