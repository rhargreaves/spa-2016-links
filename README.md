# SPA 2016 Outside-In Development of a CDN

## Resources

#### Customer site

http://robh-spa-2016-demo-site.eu-west-1.elasticbeanstalk.com/

#### Acceptance Test Suite

https://github.com/rhargreaves/spa-demo-test-suite

## Fastly

* Fastly: http://www.fastly.com/
* Dashboard: https://app.fastly.com/

### New Service Details

| Field       | Value          |
|-------------|:---------------|
| Service Name   | your_name |
| Domain      | your_name.spa2016demo.com |
| Backend     | robh-spa-2016-demo-site.eu-west-1.elasticbeanstalk.com:80 |
| Test URL    | http://your_name.spa2016demo.com.global.prod.fastly.net |

### VCL Reference

* Fastly VCL Boilerplate: https://docs.fastly.com/guides/vcl/mixing-and-matching-fastly-vcl-with-custom-vcl

* Changing TTLs in VCL: https://www.fastly.com/blog/overriding-origin-ttl-varnish-or-my-beginners-mistake

* Fastly VCL Reference: https://docs.fastly.com/guides/vcl/

* Varnish 2.1 Reference: https://www.varnish-cache.org/docs/2.1/tutorial/vcl.html
