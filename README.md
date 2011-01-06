# Bowler - A Scala based RESTful, Multi-Channel Web Framework with a functional flavor/style
A RESTful, multi-channel ready web framework in Scala with a functional flavour, built on top of Scalatra and Scalate, with Lift-JSON doing the heavy JSON lifting.

## Design Goals (some of them)
* RESTfulness - being true to RESTful principles and the intent of the HTTP protocol.
* Multi-Channel ready - the number of clients is increasing: desktop browsers, smartphones like Android & iPhone, tablets like the iPad, and API's for third parties. Bowler aims to ease targeting multiple platforms at once by maximizing re-use and minimising re-work while allowing Layouts and Templates to be selected based on User-Agent, domain and other criteria.
* JSON API "for free" - to ease creating dynamic websites with JQuery, or providing partners an API, the default settings give you a JSON API "for free", with JSON rendered to the client based on the View Model you've set and the HTTP "Accept" header being set to "application/json" from the client.
* Model first rendering - the default separates the View Model from the actual View in an even stronger way than other frameworks, in order to enable the Multi-Channel readiness. The idea behind this is explained here: 
* Sensible Defaults - Good to go out-of-the-box with sensible defaults and further extensions/plug-ins in the works for adding functionality.
* Composability - if you don't like the defaults, pick, choose and combine what you want. Bowler uses a "Micro Architecture" approach with strict code adherence to the single responsibility principle. Adding for instance a different validation framework or different templating mechanism or even entirely different rendering mechanism should be relatively pain free.