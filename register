$(document).ready(function() {
	$('div.other').append('<button id="register">Register</button>');
	$('#register').bind('click', function() {
		var url = 'http://challenge.code2040.org/api/register';
		var obj = JSON.stringify({
			email: 'daniellawillocks@gmail.com',
			github: 'https://github.com/DaniellaWillocks/code2040.git'
		});
		$.post(url, obj, function(data) {
			console.log(data);
		});
	});
});