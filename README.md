﻿##BlazorApp is the project which is created in this Microsoft Tutorial: https://dotnet.microsoft.com/en-us/learn/aspnet/blazor-tutorial/run

#Updates
<ol>
	<li> Created dotnet blazor app with the following: dotnet new blazorserver -o BlazorApp --no-https</li>
	<li> launched the new created app using: dotnet watch run</li>
		<ul>
			<li>Remember, if you use "dotnet watch run", the app will launch in a new tab in current browser</li>
		</ul>
	<li> Explored file structure for the app.</li>
		<ul>
			<li>the initial index page is listed in "Pages", and is .razor file</li>
		</ul>
	<li> Navigated to the Counter page, and saw that the "click me" button increments as expected</li>
	<li> Reused the "Counter" component that was created in Counter.razor buy listing <Counter /> in Index.Razor</li>
	<li>Updated counter app to include a public parameter, which can set how much to increment each time</li>
	<li> added "IncrementAmount = 10" to Counter reference in homepage</li>
</ol>
