
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marathon Registration</title>
</head>

<body>
    <h1>Race Registration!</h1>
    <form action="">
        <label for="fname">First Name</label>
        <input type="text" name="fname" id="fname" required>
        <label for="lname">Last Name</label>
        <input type="text" name="lname" id="lname" required>

        <p>Select a Race:</p>

        <div>
            <input type="radio" id="funrun" name="race" value="funrun">
            <label for="funrun">Fun Run 5k</label>
            <div>
                <input type="radio" id="half" name="race" value="half">
                <label for="half">Half Marathon</label>
                <div>
                    <input type="radio" id="full" name="race" value="full">
                    <label for="full">Full Marathon</label>
                </div>

                <div>
                    <label for="email">Email</label>
                    <input type="email" name="email" id="email" required>
                    <label for="password">Password</label>
                    <input type="password" name="password" id="password" required>
                    <div>
                        <label for="age">Select Age Group</label>
                        <select name="age" id="age">
                            <option value="kids">Under 18</option>
                            <option value="young">18-30</option>
                            <option value="adults">30-50</option>
                            <option value="seniors">50+</option>
                        </select>
                    </div>

                    <button>Register!</button>
