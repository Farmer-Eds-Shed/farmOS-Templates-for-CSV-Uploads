# ReadMe

Requires External JS library See: https://discourse.nodered.org/t/generation-of-uuid-in-function-node/2381/4

### Install UUID Library
npm install uuid

### Update functionGlobalContext in settings.js

    functionGlobalContext: {
        // os:require('os'),
	uuidv1:require('C:/Users/youruser/node_modules/uuid/v1')

    },
