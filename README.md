# HTML PAGE TO RE-CREATE THE IMAGE

### AIM
To re-create a HTML page based on the given image.

### HTML CODE

~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./assets'/css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
    <title>Assignment-01</title>
</head>
<body>
    <main class="main">
    <table class="outer-table">
        <thead >
            <tr>
                <td colspan="2" class="outer-table-heading">My Day</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><ol><li>wake up early</li></ol>
                <ul>
                    <li class ="list-squared">5AM</li>
                    <br>
                    <li>walk</li>
                    <li>jog</li>
                </ul>
            </td>
            <td class="second-table" rowspan="3">
                <table class="inner-table" >
                    <thead>
                        <tr>
                            <td colspan="2">Things to watch</td>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><img src="./assets'/images/walking-image.jpg" alt = "walking-image"></td>
                            <td><img src="./assets'/images/egg-image.jpg" alt="egg-image"></td>
                        </tr>
                        <tr>
                            <td><img src="./assets'/images/cofee-image.jpg" alt="coffee-image"></td>
                            <td><img src="./assets'/images/teaching-image.jpg" alt="teaching-image"></td>
                        </tr>
                    </tbody>
                </table>
            </td>
            </tr>
            <tr>
                <td><ol start="2"><li>breakfast</li></ol>
                    <ul>
                        <li class ="list-squared">8AM</li>
                        <br>
                        <li>eggs</li>
                        <li>coffee</li>
                    </ul>
                
                </td>
                
            </tr>
            <tr>
                <td><ol start="3"><li>go to saveetha</li></ol>
                    <ul>
                        <li class ="list-squared">8AM</li>
                        <br>
                        <li>attend classes</li>
                        <li>to be continued</li>
                    </ul>
                
                </td>
            </tr>
        </tbody>
    </table>
    </main>
</body>
</html>

    
</body>
</html>
~~~

### CSS CODE
~~~

*{
    font-family: Roboto;
    margin: auto;
    padding: auto;
}
.outer-table-heading{
    font-weight: bold;
    text-align: center;
}
.outer-table{
    height: 90vh;
}
table,th,td{
    border: 1px solid black;
}
t
thead{
    text-align: center;
}
.list-squared{
    list-style-type: square;
}
.inner-table{
    width: 25%;
    padding: auto;
    
}
~~~
### OUTPUT

![image](https://github.com/Ragupathi1/table/assets/143526042/9c9866dd-86b1-4446-99ab-35b06edb3e34)

