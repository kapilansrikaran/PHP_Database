# PHP_Database

Database Connection
mysqli_connect($serverName, $userName, $password)

create DB
$sql = "CREATE DATABASE school" 
if (mysqli_query($conn, $sql)){
  echo "sucess"
}
