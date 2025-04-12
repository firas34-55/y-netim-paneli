body {
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #69b3e7, #f6d365, #fda085);
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.login-container {
    text-align: center;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.login-container h1 {
    margin-bottom: 20px;
}

.form-group {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 15px;
}

label {
    flex: 1;
    margin-right: 10px;
    color: #000; /* Kullanıcı adı ve parola yazıları koyu siyah */
}

input {
    flex: 2;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    background-color: #007bff;
    color: #fff;
    padding: 10px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

#message {
    margin-top: 20px;
    color: #28a745;
}
