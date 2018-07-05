# DatingApp

### This is the back-end for the application. I use ASPNET Core

### Code Example

```c#
namespace DatingApp.API {
    public class Program {
        public static void Main (string[] args) {
            BuildWebHost (args).Run ();
        }

        public static IWebHost BuildWebHost (string[] args) =>
            WebHost.CreateDefaultBuilder (args)
            .UseStartup<Startup> ()
            .Build ();
    }
}
```
