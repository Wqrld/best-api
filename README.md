# best-api
my view of what would be the best way to implement an api


## why?
i think that most apis are way too hard to use and these are some ideas to make them better

### Auth
apis should be able to be authenticated to in multiple ways including: url api key, headers, oath, and maybe some fancy ip-linking thingymagic

### Endpoints
i think that endpoints should be straightforward and not hard to understand, for example: if you want to query a user's followers count you would do: api.yoursite.com/user/{name}/followers
you should also be able to request data in multiple formats like: plain for for example a integer or json or yml for a full page
if you have a social site you should be able to prefix someones page with api. to view their data in a nice programmable format, maybe with url parameters for auth but the page should always be accessible in a ratelimited way without auth.
I personall really like REST but it just lacks a way to only query one field, graphql tries to fix this but their fault is that the query will  become really unreadable if you need a lot of very specific features
in the end a REST/graphql mix would be the best

### Ratelimiting
I know that ratelimiting is required but PLEASE dont force me to do less than 1 request per minute or something, this is really annoying and i strongly suggest to use either a monthly limit or use wundergrounds raindrop system

### errors
errors should be nicely formatted any should not just show a *** error for the thing you are trying to look up, the most useful way to do this is to make all fields shows up as "Not Found" instead of making the developer have to spend hours trying to figure out where he went wrong.

### old apis
keep old apis working for as long as possible so that even unmaintained but still used projects can be used or community-updated

### Docs
documentation is one of the biggest thing in a api, it should be simple at first glance but there should be like dropdowns for more advanced stuff

### Performance
try to make your api as fast as possible, this is common sense but some people still have their apis on cheap low end machines

### Community input
accept community input for the docs and for api ideas to make it usefull for everyone.



