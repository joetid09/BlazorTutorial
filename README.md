##BlazorApp is the project which is created in this Microsoft Tutorial: https://dotnet.microsoft.com/en-us/learn/aspnet/blazor-tutorial/run

#Updates
1.) Created dotnet blazor app with the following: dotnet new blazorserver -o BlazorApp --no-https
2.) launched the new created app using: dotnet watch run
	-Remember, if you use "dotnet watch run", the app will launch in a new tab in current browser
3.) Explored file structure for the app.
	-the initial index page is listed in "Pages", and is .razor file
4.) Navigated to the Counter page, and saw that the "click me" button increments as expected
5.) Reused the "Counter" component that was created in Counter.razor buy listing <Counter /> in Index.Razor