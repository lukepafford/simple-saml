# Simple Saml

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/lukepafford/simple-saml/main.svg)](https://results.pre-commit.ci/latest/github/lukepafford/simple-saml/main)
![python-app workflow status](https://github.com/lukepafford/simple-saml/actions/workflows/python-app.yml/badge.svg)
[![CodeFactor](https://www.codefactor.io/repository/github/lukepafford/simple-saml/badge)](https://www.codefactor.io/repository/github/lukepafford/simple-saml)
[![codecov](https://codecov.io/gh/lukepafford/simple-saml/branch/main/graph/badge.svg?token=CHPV5Y0J7Q)](https://codecov.io/gh/lukepafford/simple-saml)
[![Documentation Status](https://readthedocs.org/projects/simple-saml/badge/?version=latest)](https://simple-saml.readthedocs.io/en/latest/?badge=latest)

A Python library that implements the [Security Assertion Markup Language (SAML) V2.0](http://saml.xml.org/saml-specifications).


## SAML At A 10,000-Foot View

If you're completely new to SAML, the [Beer Drinkers Guide To SAML](https://duo.com/blog/the-beer-drinkers-guide-to-saml) really is the best place to start so that you can get your first "Aha moment" as to what SAML is really trying to achieve.

With that said, here is an alternative description:

SAML is all about three things:

* Browser Redirects
* Identity Providers (IDP)
* Service Providers (SP)

Before going further, if you aren't proficient with knowledge about HTTP, SAML will never click. You're trying to run before you can walk. You should familiarize yourself with the following subjects before trying to tackle SAML:

* [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) (The internet protocol used to send/receive websites that you're reading this document on)
* [HTTP Redirects](https://developer.mozilla.org/en-US/docs/Web/HTTP/Redirections)
* [X509 Certificates](https://en.wikipedia.org/wiki/X.509) - Certificates are used everywhere on the internet. Learning about Certificates provides benefits that extend far beyond SAML

## Why?

For too long SAML has ruled in the enterprise, and tormented millions for it's lack of simplicity. Make no mistake, SAML is inherently complex and requires a non trivial time investment to understand and adopt. **HOWEVER**, the tools and documentation surrounding the subject are doing SAML no favors. This library aims to make SAML as simple as possible to adopt (and no simpler).
