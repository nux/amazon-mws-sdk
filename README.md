Amazon MWS API Installation
========================

Into a symfony2 project
-----------------------

Add the reference into your composer.json : 

"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/nux/amazon-mws-sdk"
        }
    ],
    "minimum-stability": "dev",
    "prefer-stable": true

    "nux/amazon-mws-sdk": "dev-master"

Use in controller :

     $client = new \MwsSearchClient(/* args */);
