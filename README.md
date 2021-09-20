<!DOCTYPE html>
<html>

<head>
    <title>Sample Form</title>
</head>

<body>
    <table border="1" style="width: auto;">
        <tr style="background-color:cyan;">
            <th>Name</th>
            <th>Value</th>
        </tr>
        <tr>
            <td>Name: </td>
            <td><input type="text" name="name" id="name"></td>
        </tr>
        <tr>
            <td>Gender: </td>
            <td>
                <input type="radio" name="gender" id="gender">Male <br>
                <input type="radio" name="gender" id="gender">Female
            </td>
        </tr>
        <tr>
            <td>Eye Color: </td>
            <td>
                <select name="eye_color" id="eye_color">
                    <option value="black">Black</option>
                    <option value="brown">Brown</option>
                    <option value="blue">Blue</option>
                    <option value="red">Red</option>
                </select>
            </td>
        </tr>
        <tr>
            <td>Check all that apply:</td>
            <td>
                <input type="checkbox" name="stats1" id="stats1">Over 6 feet tall <br>
                <input type="checkbox" name="stats2" id="stats2">Over 200 pounds
            </td>
        </tr>
        <tr>
            <td colspan="2">
                Describe Your Athletic Ability: <br>
                <textarea name="info" id="info" cols="42" rows="10"></textarea>
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                <input type="button" value="Register">
            </td>
        </tr>
    </table>

</body>

</html>
