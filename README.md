![YouWaterlooBanner](http://api.uwaterloo.ca/static/banner.png)

## Hello and Heads up! (September 18th, 2017)

Hello! 

I wanted to let you know that effective immediately the Open Data API project at Waterloo is under a new team. We're looking forward to understanding what exists now, getting feedback from current users, and having a clear plan to communicate before moving forward. We’d like to continue to build on the great work done by those before us that made this project possible. 

That said, we think it's safe to say that for the immediate future we will treat this version as a production system and fix only critical issues without introducing new features. Part of the motivation for this is to understand the users and our goals, and at the same time consider switching the code base to a stack we already develop on (C# on .NET Core). 

The main take away is there will likely be change, but for now everything you're used to will continue to work as is and we'll communicate a clear time line of any changes when it's available. 

Thank you and feel free to reach out to us (IIM Team in IST) at sbobkin@uwaterloo.ca @tenkay or joanne.mcclintock@uwaterloo.ca :)

## About

The University of Waterloo Public Data API allows anyone to build applications using data from the University of Waterloo websites.
The API currently features more than 25 methods of accessing various datasets accross the University of Waterloo network.

## License
- <a href="https://uwaterloo.ca/open-data/university-waterloo-open-data-license-agreement-v1">University of Waterloo Open Data Licensing (ODL) Agreement v1</a>

## Disclaimer
- Review the 'No Warranty' section of the University of Waterloo ODL before using this data. If building services upon this data, please inform your users of the inherent risks (as a best practice).

## About this Repository

**Note:** *This repository only servers as a [tracker](#contributing)*.

Please refer to the [contributing](#contributing) section for more information.

## Accessing the API

All calls are made to the following URL with the required parameters for a given service.


```url
https://api.uwaterloo.ca/v2/
```
In order to make an API call, you must have a valid [API Key](http://api.uwaterloo.ca/#!/keygen).


## Documentation

API docs can be viewed by clicking on a dataset from the left sidebar on [https://github.com/uwaterloo/api-documentation](https://github.com/uWaterloo/api-documentation).

### Client Libraries

- [Python](https://bitbucket.org/amjoconn/uwaterlooapi) by @amjoconn (v1)
- [Ruby Gem](https://rubygems.org/gems/uwapi) by @billxinli (v1)


## Contributing

This repository will serve as a progress and request tracker for the API.
If you would like to offer your suggestions or report any misfindings, simply create a new issue from the **issues** tab and assign it an appropriate label.

### Categories

- [Bug](https://github.com/uWaterloo/OpenData/issues?labels=bug&page=1&state=open)
- [Enhancement](https://github.com/uWaterloo/OpenData/issues?labels=enhancement&page=1&state=open)
- [Question](https://github.com/uWaterloo/OpenData/issues?labels=question&page=1&state=open)
- [Data Request](https://github.com/uWaterloo/OpenData/issues?labels=data+request&page=1&state=open)


## Restrictions

### Usage

Currently, the API requests are restricted to **5000** calls per month for a given key. This number may increase in the future.

*If your implementation of the API requires additional requests, feel free to contact us regarding the removal of your limit.*

### Data

The intent of data offered through this API is limited to publicly visible data only.
Private data such as student specific information is out of the API's scope.


## Contact ##

If you have any inquiries or suggestions, please feel free to contact us at [opendata.api@uwaterloo.ca](mailto:opendata.api@uwaterloo.ca).

Please consider subscribing to our [mailing list](https://lists.uwaterloo.ca/mailman/listinfo/opendata) in order to receive updates on the API and follow discussions.
