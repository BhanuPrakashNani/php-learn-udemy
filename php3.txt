<?php

// class Post{
// 	private $name;

// 	public function __set($name, $value) {
// 		echo 'Setting ' .$name. ' to  <strong>'.$value.'</strong><br />';
// 		$this->name = $value;
// 	}

// 	public function __get($name) {
// 		echo 'Getting ' .$name. '<strong>'.$this->name.'</strong><br />
// 	}
// }

// $Post = new Post;
// $Post->name = 'Testing';
// echo $Post->name;

class First{
	public $id = 23;
	protected $name = 'John doe ';
	public function saySomething($word){
		echo $word;
	}
}
/**
 * 
 */
class Second extends First{
	public function getName(){
		echo $this->name;
	}
}
$second = new Second;
echo $second->getName();
echo $second->saySomething('Bhanu Prakash');