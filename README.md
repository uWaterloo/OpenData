![YouWaterlooBanner](http://api.uwaterloo.ca/static/banner.png)

## Hello and Heads up! (Updated September 2018)

Hello! 

We've started to introduce elements of vNext, please see and follow the blog posts [here](https://wiki.uwaterloo.ca/pages/viewrecentblogposts.action?key=UWAPI)

Thank you and feel free to reach out to us (IIM Team in IST) at sbobkin@uwaterloo.ca [@tenkay](https://www.twitter.com/tenkay)  :)

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
