<html>
<head>
    <title>book list</title>
</head>
<body>
    <h1>book list</h1>
    <ul>
        {% for book in books %}
            <li>{{ book.title}} by {{ book.author }}</li>
        {% endfor %}
    </ul>
</body>
</html>
