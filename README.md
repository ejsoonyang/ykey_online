<!DOCTYPE html>
<html>
	<head>
		<title>雅虎奇摩倉頡在綫輸入法</title>
		<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
		<link rel="stylesheet" type="text/css" href="./cangjie.css" />
	</head>
	<body id="the_body" onload="body_onload()">
		<div id="center_board">
			<div id="whole_board">
				<div id="up_board">
					<span id="welcome" class="font_TWSung">尹杉網站-雅虎奇摩倉頡在綫輸入法</span>
				</div>
				<div id="input_board">
					<textarea id="input_area" class="font_TWSung" readonly=true onkeydown="return key_down(event);" onkeyup="key_up(event)">正在讀取碼表,請稍候...</textarea>
				</div>
				<div id="function_area">
					<input type="text" id="cc_code" class="font_TWSung" maxLength=5 readonly=ture oninput="cc_e()" onkeydown="return search_input(event);" />
					<input type="text" id="select_idiom" class="font_TWSung" maxLength=24 readonly=ture />
					<input type="button" id="input_mode_button" class="font_TWSung" value="倉頡" onclick="change_input_mode()" />
					<input type="button" id="help" class="font_TWSung" value=">>>" onclick="window.open('cangjie_help.html')" />
				</div>
			</div>
		</div>
		<footer>
			<script src="./cangjie.js"></script>
		</footer>
	</body>
</html>
