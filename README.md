# Angular-Route-resolve
What is AngularUI Router?

The UI-Router is a routing framework for AngularJS built by the AngularUI team. It provides a different approach than ngRoute in that it changes your application views based on state of the application and not just the route URL.
States vs URL Route
With this approach, your views and routes aren’t tied down to the site URL. This way, you can change the parts of your site using your routing even if the URL does not change.
When using ngRoute, you’d have to use ngInclude or other methods and this could get confusing. Now that all of your states, routing, and views are handled in your one .config(), this would help when using a top-down view of your application.
