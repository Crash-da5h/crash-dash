CrashDashKe
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIDEO SUBMISSION FORM</title>
    <style>
        body{
            background: #0daad9;
            color: #f5f1f1;
        }
    </style>
    
</head>
<body>
    <h1>Submit your video</h1>
    <img src="crashdash.jpg" alt="crashdash" width="400" height="400">
    <form action="submit.php" method="post" enctype="multipart/form-data">
        <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="fullname" required>





        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required>





        <label for="credit">How would you like to get credited?</label>
        <input type="text" id="credit" name="credit" required>






        <label for="video">Select Your Video:</label>
        <input type="file" id="video" name="video" accept="video/*" required>
        










        <input type="checkbox" id="checkbox 1" name="confirm1" required>
        <label for="checkbox 1"> Please Confirm:</label>
        <p>I recorded this video by myself and I am the owner of any and all rights to it. I have not made any exclusive agreements for this video with anyone.</p>









        <input type="checkbox" id="checkbox2" name="confirm2" required>
        <label for="checkbox2">Please Confirm:</label>
        <p>I am at least 18 years of age or have the necessary parental or legal guardian's consent to warrant and agree to all terms stated here and to submit this form</p>








        <input type="SUBMIT" value="SUBMIT">
    </form>
    
</body>
</html>
