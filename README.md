    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DCC202 layout 06- grid</title>
    <style>
        main {
            border: 1px solid rgb(0, 0, 0);
            overflow: hidden;
            resize: both;
            height: 200px;
            width: 300px;
        }

        ul > li {
            border: 1px solid hsl(240, 83%, 5%);
            background-color: hsl(271, 40%, 72%);

            ul {
            padding: 0;
            margin: 0;
            list-style: nome;
            display: grid;
            grid-template-columns: repeat(12, 1fr);
            grid-template-rows: repeat(12, 1fr);
        }
        ul > li:nth-child(1) {
            grid-column: 1 / 9;
            grid-row: 1 / 3;
        }


        ul > li:nth-child(2) {
            grid-column: 9 / 13;
            grid-row: 1 / 4;
        }


        ul > li:nth-child(3) {
            grid-column: 1 / 5;
            grid-row: 3 / 13;
        }

        }
        ul > li:nth-child(4) {
            grid-column: 1 / 5;
            grid-row: 3 / 13;
        }
        ul > li:nth-child(5) {
            grid-column: 5 / 9;
            grid-row: 3 / 13;
        }

        ul {
            padding: 0;
            margin: 0;
            list-style: nome;
            display: grid;
            grid-template-columns: repeat(12, 1fr);
            grid-template-rows: repeat(12, 1fr);
        }
        ul > li:nth-child(1) {
            grid-column: 1 / 9;
            grid-row: 1 / 3;
        }


        ul > li:nth-child(2) {
            grid-column: 9 / 13;
            grid-row: 1 / 4;
        }


        ul > li:nth-child(5) {
            grid-column: 5 / 9;
            grid-row: 3 / 13;
        }



    </style>

</head>


<body>
    <h1> DCC202 layout 06- grid</h1>
    <main>
        <ul>
          <li>Lorem ipsum dolor sit.</li>
          <li>Natus nobis tenetur temporibus?</li>
          <li>Itaque, reprehenderit voluptates. Voluptatem.</li>
          <li>Obcaecati eum dolore placeat.</li>
          <li>Tempora qui illo quod.</li>
          


        </ul>





    </main>
    
</body>
</html>
