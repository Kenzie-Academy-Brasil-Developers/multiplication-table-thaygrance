<!DOCTYPE html>
<html>
    <head>
        <title>Multiplication Table</title>
    </head>

    <body>
        <h1>Multiplication Table</h1>
        <script>

            function criarTabela(n) { 
                let x = [];
                for (let i = 0; i <= n; i++) {
                    x[i] = [];
                 for (let j = 0; j <= n; j++) {
                     x[i][j] = i*j
                 }
                }
                console.table(x)
              
            }
        </script>
    </body>
</html>
