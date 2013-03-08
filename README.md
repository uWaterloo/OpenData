![YouWaterlooBanner] (http://api.uwaterloo.ca/static/banner.png)


The University of Waterloo Public Data API allows anyone to build applications using data from the University of Waterloo websites.
The API currently features more than 25 methods of accessing various datasets accross the University of Waterloo network.


## About this Repository

**Note:** *This repository only servers as a [tracker](#contributing)*.

Please refer to the [contributing](#contributing) section for more information.

## Accessing the API

All calls are made to the following URL with the required parameters for a given service.


```url
http://api.uwaterloo.ca/public/v1/
```
In order to make an API call, you must have a valid [API Key](http://api.uwaterloo.ca/#!/keygen).


## Documentation

API docs can be viewed by clicking on a dataset from the left sidebar on [http://api.uwaterloo.ca/](http://api.uwaterloo.ca/).

### Client Libraries

- [Python](https://bitbucket.org/amjoconn/uwaterlooapi) by @amjoconn


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

## Licensing

The data from the API is offered under the [Open Data License Agreement v1.0](https://uwaterloo.ca/open-data/university-waterloo-open-data-license-agreement-v1) for the University of Waterloo.

## Contact ##

If you have any inquiries or suggestions, please feel free to contact us at:

[![email](http://api.uwaterloo.ca/static/e.png)](mailto:opendata.api@uwaterloo.ca)

Please consider subscribing to our [mailing list](https://lists.uwaterloo.ca/mailman/listinfo/opendata) in order to recieve updates on the API and follow discussions.

[![mailinglist](http://api.uwaterloo.ca/static/m.png)](https://lists.uwaterloo.ca/mailman/listinfo/opendata)
