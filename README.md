<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form</title>
</head>
<body>
    <form>
        <label for="name">name:</label>
        <input type="text" name="username" placeholder="enter your firstname" id="name"/><br>
        <br>
        <label for="name">lastname:</label>
        <input type="text" name="username" placeholder="enter your lastname"/><br>
        <br>
        <label for="name">email:</label>
        <input type="email" name="username" placeholder="enter your emailaddress"/><br>
        <br>
        <label for="password">password:</label>
        <input type="password" placeholder="enter your password"<br>
        <br>
        <label for="gender">gender:</label>
        <input type="radio" value="on">male
        <input type="radio" value="on">female<br>
        <br>
        <p>which languages you should know?</p>
        <select name="dropdown">
        <option value="c language">c language</option>
        <option value="c++">c++</option>
        <option value="python">python</option>
        <option value="java">java</option>
    </select><br>
    <br>
    birthday:
    <input type="date"><br>
    <br>
    <input type="week"><br>
    <br>
    <input type="range"<br><br>
    <p>which is your favourite subject</p>
    <input type="checkbox" name="maths">maths<br>
    <input type="checkbox" name="science">science<br>
    <br>
    <p>write your persinal information:</p>
    <textarea rows="5" cols="25">
    </textarea><br><br>
    <input type="submit" value="submit"><br><br>
    <input type="file" name="fishimage"><br><br>
    <fieldset>
        <legend>education section</legend>
        <label for="degree">degree:</label>
        <input type="text"><br><br>
        institue:
        <input type="text"><br><br>
        <p>enter cgpa:</p>
        <select name="dropdown">
            <option value="c language">9.5</option>
            <option value="c++">9.8</option>
            <option value="python">10.0</option>
            <option value="java">9.38</option>
        </select><br> <br>
        <input type="button" value="submit"/>
    </fieldset><br><br>
    <p>give your feedback</p>
    <textarea rows="3" cols="25"></textarea><br><br>
    <input type="submit" value="submit">
    <br><br>
    <input type="button" value="clickhere"/><br><br>
    <p>choose your country</p>
    <select name="dropdown">
        <option value="india">india</option>
        <option value="india">us</option>
        <option value="india">russia</option>
        <option value="india">britian</option>
        <option value="india">uk</option>
        <option value="india">australia</option>
    </select><br>
    <p>choose your favourite vehicles:</p>
    <select name="vehicles">
        <optgroup labels="car">
            <option>car</option>
            <option>bicycle</option>
            <option>auto</option>
            <option>tata</option>
            <option>hyunda</option>
        </optgroup>
    </select><br><br>
    <fieldset>
    <legend>choose your favourite items from veg and non-veg:</legend>
    <select name="vegetarian">
        <option value="veg">alupalak</option>
        <option value="veg">vegbiryani</option>
        <option value="veg">potatocury</option>
        <option value="veg">cauliflowercurry</option>
        <option value="veg">mushroom</option>
        <option value="veg">pulihora</option>
    </select>
    <select name="favdish">
        <optgroup labels="favdish">
            <option>biryani</option>
            <option>chickencurry</option>
            <option>fish</option>
            <option>prawns</option>
            <option>mutton</option>
        </optgroup>
    </select>
    </fieldset><br>
    <fieldset>
      <legend>dish3</legend>
      <select name="favdish">
        <optgroup labels="favdish">
            <option>biryani</option>
            <option>chickencurry</option>
            <option>fish</option>
            <option>prawns</option>
            <option>mutton</option>
        </optgroup>
    </select>
    </fieldset><br>
    <fieldset>
        <legend>reciepe</legend>
        <select name="dropdown">
        <option>chicken</option>
        <option>eggcurry</option>
        <option>fishfry</option>
        <option>prawnsfry</option>
    </select>
    </fieldset><br>
    <p>write your comments:</p>
    <input type="dialog" name=""><br><br>
    <input type="text" lists="browsers" name="browser" placeholder="enter your favourite browser name..."/>
    <datalist id="icecream" name="icecream">
        <option value="choclate">choclate</option>
        <option>firefox</option>
        <option>edge</option>
        <option>microsoft</option>
        <option>chrome</option>
    </datalist><br><br>
</form>
<form oninput="result.value=parseInt(a.value)+parseInt(a.value)">
    <input type="number" name="a" id="a">+
    <input typ<e="number"  name="b" id="b">+

</form>
</body>
</html>
