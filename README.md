# MMO Guidance Page Fake

https://mmo-guidance-page-fake.herokuapp.com/

## Configuration

Two env vars are required by config.js:

```
GOOGLE_TAG_MANAGER_ID
SERVICE_URL
```

These need to be set for the GTM ID and for the URL the 'Start now' button should link to.

## Authentication

Basic auth is disabled by default. If you want to use it, it requires two env vars setting:

```
USER
PASSWORD
```

This auth can be enabled by uncommenting the authentication middleware in server.js