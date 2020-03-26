# ussal-notification



 - This is made by improving the toast notification style.
   
 - Notifications have title and description.

 - Turns off after remaining on the screen for the desired time.

 - Or you can close it by clicking on the close icon.
 - There are 3 notification icons. These are successful, information,   
   and error icons.

 - It is very easy to use and improve.

**Example/**

       - Add Style
        <link href="css/ussal-notification.css" rel="stylesheet" />
        - Add Javascript (Must be jquery)
        <!--script src="https://code.jquery.com/jquery-3.4.1.js"></script-->
        <script src="js/ussal-notification.js"></script>

# Using

Add in <body>

    <div class="toast__container">
    <div class="toast__cell">
Add before </body>

    <script>
    $("#Success").click(function () {
    notification("Subject","The Explanation Will Come Here.","success");
    });
    $("#Info").click(function () {
    notification("Subject","The Explanation Will Come Here.","info");
    });
    $("#Error").click(function () {
    notification("Subject","The Explanation Will Come Here.","error");
    });
    </script>

## Changeable Timeout

İf you add timeout to notification function, it runs with new timeout.
The default value is 3000 milliseconds.
Example/

    notification("Subject","The Explanation Will Come Here.","success",5000);

## Notification Image

![enter image description here](https://lh3.googleusercontent.com/YNjsQKseAUHQ2cR7nIcNopq26IMG_-cqENLAlvckmbYGmgouuR_lVNpuueaVqQDH5OV9jkD64V8BliOmt1b-hOiJaBSUURRf2cf82F0bGE72E-YD9v0COSq86mPKLznTwwufE2B_dA=w455-h402-no)
