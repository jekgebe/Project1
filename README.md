<!DOCTYPE html>
<html>
<head>
    <title>Doctor's System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        h1 {
            text-align: center;
        }

        form {
            max-width: 400px;
            margin: 0 auto;
        }

        label, input[type="text"], textarea, select, input[type="submit"] {
            display: block;
            width: 100%;
            margin-bottom: 10px;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Doctor's System</h1>
    <form>
        <label for="patient-name">Patient Name:</label>
        <input type="text" id="patient-name" name="patient-name" required>

        <label for="patient-age">Patient Age:</label>
        <input type="text" id="patient-age" name="patient-age" required>

        <label for="gender">Patient Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select Gender</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>

        <label for="symptoms">Symptoms:</label>
        <textarea id="symptoms" name="symptoms" required></textarea>

        <label for="diagnosis">Diagnosis:</label>
        <textarea id="diagnosis" name="diagnosis" required></textarea>

        <input type="submit" value="Submit">
    </form>
</body>
</html>