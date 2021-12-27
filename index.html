
<?php 

$conn = mysqli_connect("localhost", "root", "", "saturday");

if ($conn) {
  // code...
  // echo "databse connected";
}

ob_start();

 ?>

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
   
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>

    <title>saturday</title>
  </head>
  <body>
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-6">
          <!-- form -->
          <h2>Add a new employee</h2>
          <form  method="POST">
            <div class="form-group my-3">
              <input type="text" name="e_name" placeholder="Name" class="form-control">
            </div>
            <div class="form-group my-3">
              <textarea placeholder="Designation" class="form-control" name="e_des"  rows="3"></textarea>
            </div>

            <input type="submit"   value="Add Employee" class="btn btn-md btn-success" name="add_emp">

          </form>
          <!-- get data from table -->
          <?php 
          if (isset($_POST['add_emp'])) {

            $new_name = $_POST['e_name'];
            $new_des = $_POST['e_des'];

            $query = "INSERT INTO info(name, designation) VALUES ('$new_name', '$new_des')";
           $result = mysqli_query($conn, $query);

           if ($result) {
            header('Location: index.php');
            
           }
           else {
            echo "data insert failed";
           }
          }








           ?>







          
        </div>
         <div class="col-md-6">
           <table class="table table-dark table-hover">
 <!-- show databse datas            -->
<?php 

$query = "SELECT * FROM info";
$result = mysqli_query($conn, $query);

$serial = 0;

while ($row = mysqli_fetch_assoc($result)) {
  $id = $row['i_id'];
  $name = $row['name'];
  $des = $row['designation'];
  
  $serial++;
  ?>
                    <tr>
                      <th scope="row"><?php echo $serial  ?></th>
                      <td><?php echo $name  ?></td>
                      <td><?php echo $des  ?></td>
                      <td>
                        <a href="index.php?edit_id=<?php echo $id;?>"><i class="fa fa-edit text-success"></i></a>
                         <a type="button" class="btn " data-bs-toggle="modal" data-bs-target="#delete_id<?php echo $id;?>"><i class="fa fa-trash text-danger"></i></a>


<!-- Modal -->
<div class="modal fade" id="delete_id<?php echo $id;?>" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body text-center">
        <h2 class="text-dark mb-5">Are you sure?</h2>
        <a href="index.php?delete_id=<?php echo $id;?>" type="button" class="btn btn-danger" >Yes</a>
        <button type="button" class="btn btn-primary" data-bs-dismiss="modal">No</button>
      </div>
      
    </div>
  </div>
</div>


                      </td>
                    </tr>
                    <?php


}



 ?>

         
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">Name</th>
      <th scope="col">Designation</th>
      <th scope="col">Action</th>
    </tr>
   <!-- delete -->
    <?php 
    if (isset($_GET['delete_id'])) {

      $del = $_GET['delete_id'];

      $query = "DELETE FROM info WHERE i_id='$del'";
      $result = mysqli_query($conn, $query);

      if ($result) {
        header('Location: index.php');
      // code...
      }
      else{
        echo "eroor error";
      }
    }


     ?>




    
  </thead>
  <tbody>
   
  </tbody>


           </table>
         </div>
      </div>
    </div>
    

   

     <!-- edit -->
     <?php 
     if (isset($_GET['edit_id'])){
      $edit = $_GET['edit_id'];

      $query = "SELECT * FROM info WHERE i_id='$edit'";
      $result = mysqli_query($conn, $query);

      while ($row = mysqli_fetch_assoc($result)){

        $id = $row['i_id'];
        $name = $row['name'];
        $des = $row['designation'];

      }

?>
 <section
    class= "container mt-5">
    <div class="row">
      <div class="col-md-8"><h2>Update new category</h2>
          <form  method="POST">
            <div class="form-group my-3">
              <input type="text" name="e_name" placeholder="Name" class="form-control" value="<?php echo $name;?>">
            </div>
            <div class="form-group my-3">
              <textarea placeholder="Description" class="form-control" name="e_des"  rows="3" ><?php echo $des;?></textarea>
            </div>

            <input type="submit"   value="Update Employee" class="btn btn-md btn-success" name="update_emp">

            <?php 
            if (isset($_POST['update_emp'])) {
              $up_name = $_POST['e_name'];
              $up_des = $_POST['e_des'];


              $query = "UPDATE info SET name='$up_name', designation='$up_des' WHERE i_id='$edit'";
              $result = mysqli_query($conn, $query);

      if ($result) {
        header('Location: index.php');
      // code...
      }
            }










             ?>


          </form></div></div>
    </section>
    
<?php

     }









      ?>


 

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

     <?php ob_end_flush(); ?>

  </body>
</html>
