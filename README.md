# SPA 2016 Outside-In Development of a CDN

## Resources

#### Pull Docker Images!

```
$ docker pull rhargreaves/varnishtest
$ git clone git@github.com:rhargreaves/spa-demo-test-suite.git
$ cd spa-demo-test-suite
$ docker-compose pull
```

#### Customer site

* Front end: http://robh-spa-2016-demo-site.eu-west-1.elasticbeanstalk.com/
* API: http://robh-spa-2016-demo-site.eu-west-1.elasticbeanstalk.com/counter

######

#### Acceptance test suite

https://github.com/rhargreaves/spa-demo-test-suite

#### Completed Gists

Acceptance Test 2 - Site Loads Under 2 Seconds
https://gist.github.com/rhargreaves/f28af1d07bd5382d02d588c7732be966

Acceptance Test 3 - 

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

* VCL syntax: https://www.varnish-cache.org/docs/trunk/users-guide/vcl-syntax.html

* Example VCL: http://varnish-cache.org/trac/wiki/VCLExamples

* Fastly VCL Boilerplate: https://docs.fastly.com/guides/vcl/mixing-and-matching-fastly-vcl-with-custom-vcl

* Changing TTLs in VCL: https://www.fastly.com/blog/overriding-origin-ttl-varnish-or-my-beginners-mistake

* Fastly VCL Reference: https://docs.fastly.com/guides/vcl/

* Varnish 2.1 Reference: https://www.varnish-cache.org/docs/2.1/tutorial/vcl.html
