# MMO Guidance Page Fake

https://mmo-guidance-page-fake.herokuapp.com/

## Authentication

Basic auth is enabled by default. It requires two env vars setting when deployed:

```
USER
PASSWORD
```

This auth can be disabled by taking out the authentication middleware in server.js

## Configuration

Two further env vars are required by config.js:

```
GOOGLE_TAG_MANAGER_ID
SERVICE_URL
```

These need to be set for the GTM ID and for the URL the 'Start now' button should link to.