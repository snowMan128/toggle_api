Toggl API Documentation
====================

Toggl API is divided into two

* [Toggl API](toggl_api.md)
* [Reports API](reports.md)


For managing user/workspace/project data you need to use the **Toggl API**.

If you want to get time entries of all the workspace users and aggregated data for reporting, you need to use the **Reports API**, which gives you many options for filtering, grouping and sorting.

The two parts are actually on our side two different applications. Toggl API is written in [Go](http://golang.org/) and Reports API in [Ruby](http://www.ruby-lang.org/).


##The API Format##

The API accepts only JSON requests. Please make sure you're setting `Content-type: application/json`in your request header. Each request returns a **JSON-encoded** body.

The result of each action is communicated via standard HTTP response codes.

###Example requests###

The example requests here are done using a command line tool called [cURL](http://en.wikipedia.org/wiki/CURL). If you want to try the requests out yourself, you can download cURL from [here](http://curl.haxx.se/download.html). It is available for all possible operating systems.

Under Ubuntu installing cURL is very easy:

```shell
sudo apt-get install curl
```

##API token##

Each user in Toggl.com has an API token. They can find it under "My Profile" in their Toggl account.


##Help us towards a better API##

The Toggl API has moved to Github so you could actively participate in helping us making the API better. If you have any requests or you found a bug, you can use Github issues to let us know. You can also fork the docs and send a pull request with improvements
