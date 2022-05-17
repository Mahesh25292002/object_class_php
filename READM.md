# object_class_php
php object and class code

<?php 
class record
{
	public $fname;
  public $lname;

	function set_fname($fname)
	{
		$this->fname = $fname;
	}
    function set_lname($lname)
	{
		$this->lname = $lname;
	}
	
	function get_fname()
	{
		return $this->fname;
	}
	function get_lname()
	{
		return $this->lname;
	}
}
$student1 = new record();
$student2 = new record();

$student1->set_fname('Mahesh ');
$student1->set_lname('Dabhade');
$student2->set_fname('Ashwin ');
$student2->set_lname('Ingle');

			
echo $student1->get_fname();

echo $student1->get_lname();
echo "<br>";

echo $student2->get_fname();
echo $student2->get_lname();

?>

