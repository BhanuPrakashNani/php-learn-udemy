<?php
class User{
	
	public $id;
	public $username;
	public $password;
	public $email;

	public function __construct($username, $password) {
		//echo 'Constructor Called';
    	$this->username = $username;
		$this->password = $password;
	}


	public function register() {
		echo 'User Registered';
		echo ' ';
	}

	public function login($username, $password) {
		$this->auth_user();
	}


	public function auth_user() {
		echo $this->username. ' is authenticated';
	}
	public function __destruct() {
		//echo 'Destructor Called';
	}
}

$User = new User('bhanu', '53');

//$User->register();
//$User->login('bhanu', '53');