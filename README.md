# day-17-task
front end 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM Manipulation Example</title>
</head>
<body>
    <script>
        // Create a new ul element
        const ul = document.createElement('ul');
        ul.id = 'myList';
        
        // Create and append list items
        for (let i = 1; i <= 3; i++) {
            const li = document.createElement('li');
            li.textContent = `Item ${i}`;
            ul.appendChild(li);
        }
        
        // Append the ul to the body
        document.body.appendChild(ul);
    </script>
</body>
</html>

