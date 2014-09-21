from box import BoxClient
from StringIO import StringIO
code='h1J9HeATdM4DHKVHZDjZOH3J9ALfCuza'

#response= {u'access_token': u'XnpOFtKpn2JUmAOPwKtUyzunZ0mOQAJt', u'restricted_to': [], u'expires_in': 4072, u'refresh_token': u'7PNqFf1Bmv6uM0zkoTxnFh3UOqYs2qIoLvGe04hlhDv76fDqI4n4JqRo0V8R53NY', u'token_type': u'bearer'}
#response= {u'access_token': u'VVeRMPOXltFoSWAckvADXTwQyrZsc906', u'restricted_to': [], u'token_type': u'bearer', u'expires_in': 4040, u'refresh_token': u'y5KyiuQstgWdEZsYifALo13EH5x7j5HGxBVlXOnIy6kfeKHSLsMTyA1MC4a5zfdP'}
response={u'access_token': u'rDMonxdCPfhJMAGU7qIA1QPEZf0tlnS8', u'restricted_to': [], u'token_type': u'bearer', u'expires_in': 3722, u'refresh_token': u'pCGF1OO4zsEGoAjXeAftqMLin250LeXqwpcL0caTcvGcmVy3TJq3Twxqo5SrSxf6'}
client = BoxClient(response['access_token'])
metadata=client.upload_file('fuckyou.txt', StringIO('hello world'))
print metadata
'''{u'shared_link': None, u'sha1': u'2aae6c35c94fcfb415dbe95f408b9ce91ee846ed', u'modified_by': {u'login': u'siddhanthgupta@gmail.com', u'type': u'user', u'id': u'216264056', u'name': u'Siddhanth Gupta'}, u'name': u'fuckyou.txt', u'parent': {u'sequence_id': None, u'etag': None, u'type': u'folder', u'id': u'0', u'name': u'All Files'}, u'purged_at': None, u'trashed_at': None, u'created_at': u'2014-06-28T13:56:35-07:00', u'modified_at': u'2014-06-28T13:56:35-07:00', u'item_status': u'active', u'created_by': {u'login': u'siddhanthgupta@gmail.com', u'type': u'user', u'id': u'216264056', u'name': u'Siddhanth Gupta'}, u'content_modified_at': u'2014-06-28T13:56:35-07:00', u'sequence_id': u'0', u'etag': u'0', u'owned_by': {u'login': u'siddhanthgupta@gmail.com', u'type': u'user', u'id': u'216264056', u'name': u'Siddhanth Gupta'}, u'path_collection': {u'total_count': 1, u'entries': [{u'sequence_id': None, u'etag': None, u'type': u'folder', u'id': u'0', u'name': u'All Files'}]}, u'size': 11, u'type': u'file', u'id': u'18532645558', u'content_created_at': u'2014-06-28T13:56:35-07:00', u'description': u''}
'''




