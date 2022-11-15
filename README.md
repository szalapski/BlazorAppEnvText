Notice in BlazorAppEnvText/Server/Properties/launchSettings.json that ASPNETCORE_ENVIRONMENT is "Foo".

`dotnet run --verbose --project BlazorAppEnvText/Server` to watch it fail

Then  in launchSettings.json, change ASPNETCORE_ENVIRONMENT to "Development", and run the same command, and it succeeds.

How can I get it working with "Foo"?

Please answer at https://stackoverflow.com/q/74435611/7453
