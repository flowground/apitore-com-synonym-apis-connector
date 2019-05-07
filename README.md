# ![LOGO](logo.png) Synonym APIs **flow**ground Connector

## Description

A generated **flow**ground connector for the Synonym APIs API (version 1.0.1).

Generated from: https://api.apis.guru/v2/specs/apitore.com/synonymApis/1.0.1/swagger.json<br/>
Generated at: 2019-05-07T17:36:43+03:00

## API Description

Return synonymous words. (equal to "word2vec distance")<BR />[Endpoint] https://api.apitore.com/api/9

## Authorization

This API does not require authorization.

## Actions

### Word2Vec distance

> Word2Vec JaWikipedia 2016-9-15 dump.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/word2vec-response">word2vec-response</a><BR />&nbsp; Class: com.apitore.banana.response.word2vec.DistanceResponseEntity<BR />

*Tags:* `word-2-vec-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `word` - _required_ - word
* `num` - _optional_ - num [max 10, default 1]

## License

**flow**ground :- Telekom iPaaS / apitore-com-synonym-apis-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
