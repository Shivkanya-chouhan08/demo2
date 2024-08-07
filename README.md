# demo2
<?php
interface Vehicle{
  public function start();
  public function stop();
  }
  class Car imlements vehicle{
  public function start (){
   echo "car is starting engine.\n";
   }
  }
  class bicyle implements vehicle{
  public function start(){
    echo"bicycle is ready to pedal.\n";
    }
  }
  $car=new car();
  $car->start();
  $car->stop();

  $bicycle=new bicycle();
  $bicycle->start();
  $bicycle->stop();

?>

  
