# JavaScript SDK for csirtg.io

The Software Development Kit (SDK) for Javascript contains library code and examples designed to enable developers to build applications using csirtg.io


# Examples
## Client
```javascript
<script type="text/javascript" src="csirtgsdk.js"></script>

<script type="text/javascript" charset="utf-8">

    var cli = new CSIRTGSDK({user: 'wes', token: "1234", q: "example.com"});
    cli.search(function(err, success) {
        if (err) {
            throw err;
        }

    });

</script>
```
# License and Copyright
Copyright (C) 2017 the CSIRT Gadgets, LLC

Free use of this software is granted under the terms of the Mozilla Public License Version 2.0 (MPL2). For details see the file LICENSE included with the distribution.