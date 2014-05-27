fruitbots_game.html
===================
// An attempt at coding.

<html>
<head>
<link rel="stylesheet" type="text/css" href="assets/css/drawgame.css"/>
<script src="assets/js/seedrandom.js"></script>
<script src="assets/js/board.js"></script>
<script src="assets/js/grid.js"></script>
<script src="mybot.js"></script>
<script src="assets/js/simplebot.js"></script>
<script src="assets/js/player.js"></script>
<script src="assets/js/jquery.min.js"></script>
</head>
<body onload="GamePlay.init()">
<canvas id="grid"></canvas>
<canvas id="game_view"></canvas>
<div id="buttons">
<span class="newgame button">new</span>
<span class="reset button">reset</span>
<span class="pause button">pause</span>
<span class="play button">play</span>
<span class="forward button">forward</span>
<span class=""><label><input type="checkbox" id="check_breadcrumbs"/> Show breadcrumbs</label></span>
<br><br>
<label>Board Number: </label><input type="text" id="board_number"/><button id="set_board">Set</button>
<br>
<span id="select_largeboard" style="display:none;">
    <label>Board Size Range: </label>
    <select id="largeboard_dim">
        <option value="5;15">Small (5-15)</option>
        <option value="10;20">Medium (10-20)</option>
        <option value="15;40">Large (15-40)</option>
    </select>
</span>
</div>
</body>
</html>
