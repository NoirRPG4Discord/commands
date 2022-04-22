<html>
<head>
	<title></title>
</head>
<body>
<h2>NoirRPG Discord Bot Commands</h2>

<p>&nbsp;</p>

<p><big>Format: exampleCommand (commandName) [param] (optionalParameter) &lt;param&gt; (requiredParameter)</big></p>

<p><strong>Command: info [user]</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>null</strong> - Displays information about the caller of the command.</li>
	<li><strong>user </strong>- Displays information about the targeted user. Displays an error if the target is not valid, or the target has information viewing on their profile disabled.</li>
</ul>

<p><strong>Command: currentLocation [user]</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>null</strong> - Displays the coordinates of the caller of the command.</li>
	<li><strong>user</strong> - Displays the coordinates of the targeted user. Displays an error if the targeted player is not valid.</li>
</ul>

<p><strong>Command: duel &lt;user&gt; &lt;send | accept | deny | cancel&gt;</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>player</strong> - Specifies the targeted player to perform the command on. Displays an error if the player is not valid.

	<ul>
		<li><strong>send -</strong> Sends a duel request to the specified player. Displays an error if that player already has an incoming duel request.</li>
		<li><strong>accept</strong> - Accepts a duel request from the specified player. Displays an error if that player has not sent a request to you.</li>
		<li><strong>deny </strong>- Denies a duel request from the specified player. Displays an error if that player has not sent a request to you.</li>
		<li><strong>cancel</strong> - Cancels a duel request to the specified player. Displays an error if you have not sent a request to specified player.</li>
	</ul>
	</li>
</ul>

<p><strong>Command: </strong><strong>craftItem &lt;item&gt; [recipe]</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>item</strong> - Specifies the item to craft. Displays an error if the item is not valid.

	<ul>
		<li><strong>recipe -</strong> Displays the recipe of the item.</li>
	</ul>
	</li>
</ul>

<p><strong>Command: inventory &lt;item&gt; [use]</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>null</strong> - Displays the inventory of the caller of the command.</li>
	<li><strong>item </strong>- Specifies the targeted item. If only this parameter is specified, then displays information about said item. Displays an error if the item is not valid.
	<ul>
		<li><strong>use </strong>- Consumes the targeted item. Displays an error if the item is not a Consumable.</li>
	</ul>
	</li>
</ul>

<p><strong>Command: move &lt;up | left | down | right&gt;</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>direction </strong>- Moves the player in that direction from a random range 10 to 16 units. Displays an error if the command caller is in combat.</li>
</ul>

<p><strong>Command: trade &lt;user&gt; &lt;start | accept | deny | add | remove | trade&gt;</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>player</strong> - Specifies the targeted player to perform the command on. Displays an error if the player is not valid.

	<ul>
		<li><strong>start -</strong> Sends a trade request to the specified player. Displays an error if that player already has an incoming trade request, or is currently in another trade.</li>
		<li><strong>accept</strong> - Accepts a duel request from the specified player. Displays an error if that player has not sent a request to you.</li>
		<li><strong>deny </strong>- Denies a duel request from the specified player. Displays an error if that player has not sent a request to you.</li>
		<li><strong>add </strong>- Adds a Tradeable (Item / Money) to the specified player&#39;s trade. Displays an error if you are not in a trade, you have stated that you are ready to trade, or the Tradeable is invalid.</li>
		<li><strong>remove </strong>- Removes a Tradeable (Item / Money) to the specified player&#39;s trade. Displays an error if you are not in a trade, you have stated that you are ready to trade, the Tradeable is invalid, or it is not in the current trade.</li>
		<li><strong>trade </strong>- Sends a request to the other person that you are ready. Displays an error if you are currently not in a trade. If the other person has signaled they are ready, the trade goes through and displays a summary of the Tradeables exchanged.</li>
	</ul>
	</li>
</ul>

<p><strong>Command: toggleview</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>null</strong> - Toggles the ability for people to view your profile. Displays an error if player scope is below PREMIUM</li>
</ul>

<p><strong>Command: username &lt;username&gt;</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>username</strong> - Changes your current username to that specified username. Displays an error if that username is already taken.</li>
</ul>

<p><strong>Command: class &lt;class&gt; &lt;obtain | use&gt;</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>class </strong>- Specifies the targeted class. Displays an error if the class does not exist.

	<ul>
		<li><strong>obtain</strong> - Attempts to obtain the specified class for the command caller. Displays an error if the caller does not have enough skill points.</li>
		<li><strong>use</strong> - Switches the caller&#39;s class to the targeted class. Displays an error if the caller does not possess that class.</li>
	</ul>
	</li>
</ul>

<p><strong>Command: learnspell &lt;spell&gt;</strong></p>

<p>Parameters:</p>

<ul>
	<li><strong>spell</strong> - Specifies the targeted spell to learn. Displays an error if the spell does not exist, or the command caller does not have enough skill points.</li>
</ul>
</body>
</html>
