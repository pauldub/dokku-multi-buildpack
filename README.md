# #dokku-multi-buildpack [![Build Status](https://img.shields.io/travis/alexpauldub/dokku-multi-buildpack.svg?branch=master "Build Status")](https://travis-ci.org/pauldub/dokku-multi-buildpack)

dokku-multi-buildpack is a plugin for [dokku](https://github.com/progrium/dokku) that injects
[heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) into buildstep, allowing the use of multiple buildpacks.

## requirements

- dokku 0.3.0+ (0.4.x has this functionality built-in)
- docker 1.6.x+

## installation

```shell
# on 0.3.x
cd /var/lib/dokku/plugins
git clone https://github.com/pauldub/dokku-multi-buildpack.git dokku-multi-buildpack
dokku plugins-install
```

## License

The MIT License (MIT)
