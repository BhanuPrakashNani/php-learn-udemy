<?php

	
	$myVar1 = 'Hello';
	echo $myVar1. ' World!';

	$numbers = array(12,45,56,78);
	$numbers = [12,45,22,34,65];

	print_r($numbers);

	echo $numbers[1];

	$ages = array(

		 "John" => 35,
		 "Mary" => 27,
		 "Bob" => 55,

	);

	array_pop($ages);

	echo $ages['Mary'];
	array_shift($ages);
	print_r($ages);

	for($i = 0;$i < 5; $i++){

		echo $i;
	}


$i = 0;
while ($i <= 10) {
		# code...
	echo 'Number '.$i.'<br />';
	$i++;
	}	


	$numbers = array(23,45,657,234,6456,47,63,5,7,2534,634,647,);
	foreach($numbers as $number){
		echo 'This is number '.$number.'</ br>';
	}
	

	$ages = array(

		 "John" => 35,
		 "Mary" => 27,
		 "Bob" => 55,

	);
	foreach($ages as $name => $age){
		echo $name.' is '. $age. 'years old<br />';
	}


	/*function greet(){
		echo 'Hey Sweety';
	} 

	greet();


	function greet($greeting, $name='Sweety'){
		echo strtoupper($greeting.' '.$name);
	}

	greet('Whats Up', 'Brad');


	$num = 101;
	if($num != 10){
		echo 'Correct';
	}*/
?>
