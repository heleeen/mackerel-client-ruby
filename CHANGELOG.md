# Changelog

## v0.9.0 (2020-01-23)

* Use Faraday v1.0 #54 (onk)

## v0.8.0 (2019-06-26)

### Breaking change

Now mackerel-client raises `Mackerel::Error` when HTTP requests failed.
Previously various exceptions (mainly `RuntimeError` or `NoMethodError`) happened in such cases.

* Use Faraday::Response::RaiseError middleware #49 (onk)

## v0.7.0 (2018-10-22)

* fix unintended initializing http headers #47 (y_uuki)

## v0.6.0 (2018-07-04)

* Use Rspec v3.x #43 (onk)
