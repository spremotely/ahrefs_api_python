# ahrefs-api-python

This is the python library for using ahrefs.com API

## Install:
```
pip install ahrefs_api_python
```

## Usage example:

```
api = AhrefsApi('http://apiv2.ahrefs.com', 'b92188dg02d24dwc39ecdv0861fbb1eeac8c3g8c')
ahrefs_rank_result = api.ahrefs_rank('example.net').order_by('url:asc').where('url="http://example.net/"').get()
```

where b92188dg02d24dwc39ecdv0861fbb1eeac8c3g8c is your token

