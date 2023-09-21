# Pizza-Management-App-WebAPI
Pizza Management cross-platform RESTful service using ASP.NET Core controllers that supports create, read, update, delete (CRUD) operations using .NET and C#.

Create a web API with ASP.NET Core controllers <a href="https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/">link</a>
<ul>
  <li>~<code>dotnet new webapi -f net6.0</code> to create files for a basic web API project that uses controllers.
    <ul>
      <li>Controllers folder contains classes with public methods exposed as HTTP endpoints.</li>
    </ul>
  </li>
  <li>Open a web browser and go to: https://localhost:{PORT}/weatherforecast to see JSON output.</li>
  <li>~<code>dotnet tool install -g Microsoft.dotnet-httprepl</code> to install the .NET HTTP REPL command-line tool that you use to make HTTP requests to the web API.</li>
  <li>~<code>httprepl https://localhost:{PORT}</code> to connect to the web API.
    <ul>
      <li>~<code>ls</code> to explore available endpoints.</li>
      <li>~<code>exit</code> to end the current <code>HttpRepl</code> session.</li>
    </ul>
  </li>
  <li>Create a pizza model.</li>
  <li>Add a data service.</li>
  <li>~<code>dotnet build</code> to build the web API project.</li>
  <li>Create a controller. Create and test REST verb functions.</li>
</ul>
