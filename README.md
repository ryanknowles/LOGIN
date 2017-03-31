# LOGIN

<button onclick="myName()">Login</button>

<script>
	var myName = function{
		var person = prompt("Username:");
			if (person = Ryan){
	/* This only allows me to get to the passwaord step*/
		var password = prompt("Password:");
			if (password = "12345");
				confirm("Continue if you are Ryan");
	/* If anybody else's name is Ryan they won't know the password*/			
			else if (password != "12345");
				confirm("You are not Ryan");
	/* If their password isn't 12345 they can't login as me*/			
	}
			else if(person != Ryan);
				confirm("You are not Ryan");
	/* This just declines anybody without the name Ryan*/
}
</script>
