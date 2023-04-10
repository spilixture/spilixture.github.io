<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background-color: white;
      color: black;
      font-family: Arial, sans-serif;
      transition: background-color 0.5s ease;
    }
    
    .toggle-wrapper {
      position: fixed;
      top: 10px;
      right: 10px;
      display: flex;
      align-items: center;
    }
    
    .toggle-label {
      margin-right: 10px;
      font-size: 14px;
    }
    
    .toggle-input {
      height: 0;
      width: 0;
      visibility: hidden;
    }
    
    .toggle-input:checked + .toggle-slider {
      background-color: #2196F3;
    }
    
    .toggle-slider {
      height: 20px;
      width: 40px;
      border-radius: 10px;
      background-color: grey;
      position: relative;
      transition: background-color 0.5s ease;
    }
    
    .toggle-slider:before {
      content: "";
      position: absolute;
      height: 16px;
      width: 16px;
      border-radius: 50%;
      background-color: white;
      top: 2px;
      left: 2px;
      transition: transform 0.5s ease;
    }
    
    .toggle-input:checked + .toggle-slider:before {
      transform: translateX(20px);
    }
    
    /* Dark mode styles */
    
    body.dark-mode {
      background-color: black;
      color: white;
    }
    
    body.dark-mode .toggle-slider {
      background-color: #777;
    }
    
    body.dark-mode .toggle-input:checked + .toggle-slider {
      background-color: #ccc;
    }
    
    body.dark-mode .toggle-slider:before {
      background-color: black;
    }
    
    body.dark-mode .toggle-input:checked + .toggle-slider:before {
      transform: translateX(20px);
      background-color: white;
    }
  </style>
</head>
<body>
  <div class="toggle-wrapper">
    <span class="toggle-label">Dark mode:</span>
    <label class="toggle">
      <input type="checkbox" class="toggle-input" onclick="toggleDarkMode()">
      <span class="toggle-slider"></span>
    </label>
  </div>

  <h1>Welcome to my website</h1>
  <p>This is an example of a website with a toggle switch to change between light and dark mode.</p>

  <script>
    function toggleDarkMode() {
      var body = document.body;
      body.classList.toggle("dark-mode");
    }
  </script>
</body>
</html>
