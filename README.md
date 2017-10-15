<!-- README.md is generated from README.Rmd. Please edit that file -->
OfflineGeocodeR
===============

`OfflineGeocodeR` provides a wrapper around calling a Docker container (`DeGAUSS/geocoder_slim`) in order to geocode addresses from R without using the internet. This is advantageous for several reasons, two of which are maintaining the privacy of protected health information and maintaining a reproducible research workflow. See our manuscript about using DeGAUSS (Decentralized Geomarker Assessment for Multi-Site Studies) [here]().

Installing
----------

OfflineGeocodeR is a private package hosted on GitHub.

Install with:

``` r
remotes::install_github('cole-brokamp/OfflineGeocodeR')
```

You must also have Docker installed and available on your system. In the future, it will hopefully be possible to use this package to call a remote docker machine, but for now, it must be local.

*Note: This package was originally designed as a personal convenience and has not been tested on setups other than unix-based operating systems with Docker running natively (i.e. not Docker Toolbox). Your mileage may vary*