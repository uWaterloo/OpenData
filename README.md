## Hello and welcome

All news and announcements related to Open Data and related APIs will be posted to our [news and announcements](https://wiki.uwaterloo.ca/pages/viewrecentblogposts.action?key=UWAPI) blog.

Thank you, and please file an issue here, or use the IST-Opendata queue in [RT](https://rt.uwaterloo.ca) to contact us. 

## About

The University of Waterloo Public Data API allows anyone to build applications using data from curated University of Waterloo datasets.

## License
- We're reviewing our options for licensing version 3 of the API. At present, it is covered by existing University policy, including, but not exclusively [Policy 46 - Information Management](https://uwaterloo.ca/secretariat/policies-procedures-guidelines/policies/policy-46-information-management).
- <a href="https://uwaterloo.ca/open-data/university-waterloo-open-data-license-agreement-v1">University of Waterloo Open Data Licensing (ODL) Agreement v1</a> applies strictly to version 2 of the API.

## Disclaimer
- Review the 'No Warranty' section of the University of Waterloo ODL before using this data. If building services upon this data, please inform your users of the inherent risks (as a best practice). It is the goal that version 3 datasets will not require this disclaimer, and the data can be treated as reviewed and authoritative where possible.

## About this Repository

**Note:** *This repository only servers as a [tracker](#contributing)*.

Please refer to the [contributing](#contributing) section for more information.

## Documentation

For current version 3, please see [getting started](https://wiki.uwaterloo.ca/display/UWAPI/Getting+Started+-+OpenAPI) documentation and the [live endpoint](https://openapi.data.uwaterloo.ca/api-docs/index.html) documentation.

For legacy version 2, API docs can be viewed by clicking on a dataset from the left sidebar on [https://github.com/uwaterloo/api-documentation](https://github.com/uWaterloo/api-documentation).

### Client Libraries (legacy version 2)

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


## Restrictions (v2 legacy)

### Usage

Currently, the API requests are restricted to **5000** calls per month for a given key. This number may increase in the future.

*If your implementation of the API requires additional requests, feel free to contact us regarding the removal of your limit.*

### Data

The intent of data offered through this API is limited to publicly visible data only.
Private data such as student specific information is out of the API's scope.


## Contact ##

If you have any inquiries or suggestions, please feel free to contact us by filing an issue here, or use the IST-Opendata queue in [RT](https://rt.uwaterloo.ca).
