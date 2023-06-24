<!DOCTYPE html>
<html>
<head>
    <title>My GitHub Page</title>
    <script>
        
        fetch('Secret.txt') 
            .then(response => response.text())
            .then(content => {
                
                document.getElementById('content').textContent = content;
            })
            .catch(error => console.log(error));
    </script>
</head>
<body>
</body>
</html>
