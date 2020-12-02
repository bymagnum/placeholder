# placeholder



/* reset */

select:focus, select:active,  
button:focus,  
textarea:focus,  
input[type="text"]:focus,  
input[type="password"]:focus,  
input[type="datetime"]:focus,  
input[type="datetime-local"]:focus,  
input[type="date"]:focus,  
input[type="month"]:focus,  
input[type="time"]:focus,  
input[type="week"]:focus,  
input[type="number"]:focus,  
input[type="email"]:focus,  
input[type="url"]:focus,  
input[type="search"]:focus,  
input[type="tel"]:focus,  
input[type="color"]:focus {     
	box-shadow: 0 1px 1px rgba(0, 0, 0, 0) !important;  
	outline: 0 none;  
}  
input::-webkit-input-placeholder {  
	opacity: 1;  
	transition: opacity 0.3s ease;  
}  
input::-moz-placeholder {  
	opacity: 1;  
	transition: opacity 0.3s ease;  
}  
input:-moz-placeholder {  
	opacity: 1;  
	transition: opacity 0.3s ease;  
}  
input:-ms-input-placeholder {  
	opacity: 1;  
	transition: opacity 0.3s ease;  
}  
input:focus::-webkit-input-placeholder {  
	opacity: 0;  
	transition: opacity 0.3s ease;  
}  
input:focus::-moz-placeholder {  
	opacity: 0;  
	transition: opacity 0.3s ease;  
}  
input:focus:-moz-placeholder {  
	opacity: 0;  
	transition: opacity 0.3s ease;  
}  
input:focus:-ms-input-placeholder {  
	opacity: 0;  
	transition: opacity 0.3s ease;  
}  
  
