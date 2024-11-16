# SimpleChess
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Playable Chessboard</title>
    <link rel="stylesheet" href="https://unpkg.com/@chriso/chessboardjs@1.0.0/dist/chessboard-1.0.0.min.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://unpkg.com/@chriso/chessboardjs@1.0.0/dist/chessboard-1.0.0.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        #board {
            width: 400px;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <h1>Playable Chess</h1>
    <div id="board"></div>
    <script>
        const board = ChessBoard('#board', {
            draggable: true,
            dropOffBoard: 'trash',
            sparePieces: true
        });
    </script>
</body>
</html>
