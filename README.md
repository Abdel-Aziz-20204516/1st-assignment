# 1st-assignment
<html>
<head>
<title>New Student</title>

</head>
<body>
<!--Start nav -->
<h1>New Student</h1>
 <!--End nav -->
<!--Start Sec-->

<form method="post">
    <p >
        <fieldset> <legend>Personal Information</legend>
    <table>
       <tr> 
            <td>Full Name: </td>
            <td> <input type="text" placeholder="Name" name="name"></td>
        </tr> 
       <tr>
             <td> Birthdate: </td>
             <td> <input type="date" name="date"></td>   
       </tr>
       <tr>
           <td>Gender: </td>
           <td> <input type="radio" name="gender">Male
                <input type="radio" name="gender">Female
           </td>
       </tr>
    </table> </fieldset> </p>

    <p> <fieldset> <legend>Contact Information</legend>
        <table>
            <tr>
                <td>Email: </td>
                <td> <input type="email" name="email" placeholder="Email"></td>
            </tr>
            <tr>
                <td>Phone</td>
                <td> <input type="phone" name="phone" placeholder="phone"></td>
            </tr>
            <tr>
                <td>Address: </td>
                <td> <textarea style="resize: none;" name="address"  cols="60" rows="10" ></textarea> </td>
            </tr>
        </table> </fieldset>
    </p>

    <p>
         <fieldset> <legend>Universty Information</legend>
             <table>
            <tr>
                <td>Choose your Faculty: </td>
                <td> <select>
                        <option> Faculty1</option>
                        <option >Faculty2</option>
                </select>
                </td>
            </tr>
        </table> </fieldset>
    </p>
    <p>
        <input type="submit" value="Add">
    </p>
</form>
<!--End sec-->
</body>
</html>
