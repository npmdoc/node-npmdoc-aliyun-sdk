# api documentation for  [aliyun-sdk (v1.9.22)](https://github.com/aliyun-UED/aliyun-sdk-js.git)  [![npm package](https://img.shields.io/npm/v/npmdoc-aliyun-sdk.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-aliyun-sdk) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-aliyun-sdk.svg)](https://travis-ci.org/npmdoc/node-npmdoc-aliyun-sdk)
#### Aliyun SDK for JavaScript

[![NPM](https://nodei.co/npm/aliyun-sdk.png?downloads=true)](https://www.npmjs.com/package/aliyun-sdk)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aliyun-sdk/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-aliyun-sdk_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aliyun-sdk/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-aliyun-sdk/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-aliyun-sdk/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "chylvina",
        "email": "chylvina@gmail.com"
    },
    "browser": {
        "./lib/util.js": "./lib/util-browser.js",
        "cdn-2014-11-11.json": "./apis/cdn-2014-11-11.json",
        "ecs-2014-05-26.json": "./apis/ecs-2014-05-26.json",
        "opensearch-2015-01-01.json": "./apis/opensearch-2015-01-01.json",
        "batchcompute-2015-06-30.json": "./apis/batchcompute-2015-06-30.json",
        "batchcompute-2015-11-11.json": "./apis/batchcompute-2015-11-11.json",
        "oss-2013-10-15.json": "./apis/oss-2013-10-15.json",
        "rds-2014-08-15.json": "./apis/rds-2014-08-15.json",
        "slb-2014-05-15.json": "./apis/slb-2014-05-15.json",
        "sls-2014-11-18.json": "./apis/sls-2014-11-18.json",
        "sts-2015-04-01.json": "./apis/sts-2015-04-01.json",
        "ram-2015-05-01.json": "./apis/ram-2015-05-01.json"
    },
    "bugs": {
        "url": "https://github.com/aliyun-UED/aliyun-sdk-js/issues"
    },
    "contributors": [],
    "dependencies": {
        "node_memcached": "1.1.3",
        "pomelo-protobuf": "^0.4.0",
        "protobufjs": "^4.1.2",
        "xml2js": "0.4.4",
        "xmlbuilder": "^2.4.5"
    },
    "description": "Aliyun SDK for JavaScript",
    "devDependencies": {
        "coffee-script": "1.6.3",
        "coffeeify": "",
        "cucumber": "",
        "jasmine-node": "",
        "jshint": "",
        "mocha": "~2.1.0",
        "repl.history": "",
        "semver": "",
        "should": "~4.6.3"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "5d7bcb18de91c05a7e2a22d746ab74a2c37602c6",
        "tarball": "https://registry.npmjs.org/aliyun-sdk/-/aliyun-sdk-1.9.22.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "24f276b8b79a9801661953f6ad0d3654fb444920",
    "homepage": "https://github.com/aliyun-UED/aliyun-sdk-js.git",
    "keywords": [],
    "main": "index.js",
    "maintainers": [
        {
            "name": "chylvina",
            "email": "chylvina@gmail.com"
        }
    ],
    "name": "aliyun-sdk",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/aliyun-UED/aliyun-sdk-js.git"
    },
    "scripts": {
        "test": "mocha test"
    },
    "version": "1.9.22"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module aliyun-sdk](#apidoc.module.aliyun-sdk)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>BatchCompute ()](#apidoc.element.aliyun-sdk.BatchCompute)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>CDN ()](#apidoc.element.aliyun-sdk.CDN)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>CMS ()](#apidoc.element.aliyun-sdk.CMS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Config (options)](#apidoc.element.aliyun-sdk.Config)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>DAYU ()](#apidoc.element.aliyun-sdk.DAYU)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>DRDS ()](#apidoc.element.aliyun-sdk.DRDS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>ECS ()](#apidoc.element.aliyun-sdk.ECS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>ESS ()](#apidoc.element.aliyun-sdk.ESS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Endpoint (endpoint)](#apidoc.element.aliyun-sdk.Endpoint)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>GREEN ()](#apidoc.element.aliyun-sdk.GREEN)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpClient ()](#apidoc.element.aliyun-sdk.HttpClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpRequest (endpoint, region)](#apidoc.element.aliyun-sdk.HttpRequest)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpResponse ()](#apidoc.element.aliyun-sdk.HttpResponse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>JAQ ()](#apidoc.element.aliyun-sdk.JAQ)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>JSON.Builder (rules, options)](#apidoc.element.aliyun-sdk.JSON.Builder)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>MEMCACHED.MemcachedClient (stream, options)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>MTS ()](#apidoc.element.aliyun-sdk.MTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>NodeHttpClient ()](#apidoc.element.aliyun-sdk.NodeHttpClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>OSS ()](#apidoc.element.aliyun-sdk.OSS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>OTS ()](#apidoc.element.aliyun-sdk.OTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>OpenSearch ()](#apidoc.element.aliyun-sdk.OpenSearch)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>PUSH ()](#apidoc.element.aliyun-sdk.PUSH)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>ParamValidator ()](#apidoc.element.aliyun-sdk.ParamValidator)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>QueryParamSerializer (rules, options)](#apidoc.element.aliyun-sdk.QueryParamSerializer)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>RAM ()](#apidoc.element.aliyun-sdk.RAM)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>RDS ()](#apidoc.element.aliyun-sdk.RDS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Request (service, operation, params)](#apidoc.element.aliyun-sdk.Request)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Response (request)](#apidoc.element.aliyun-sdk.Response)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>SLB ()](#apidoc.element.aliyun-sdk.SLB)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>SLS ()](#apidoc.element.aliyun-sdk.SLS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>STS ()](#apidoc.element.aliyun-sdk.STS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>SequentialExecutor ()](#apidoc.element.aliyun-sdk.SequentialExecutor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Service (config)](#apidoc.element.aliyun-sdk.Service)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.BatchCompute ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.CMS ()](#apidoc.element.aliyun-sdk.Signers.CMS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OSS ()](#apidoc.element.aliyun-sdk.Signers.OSS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OTS ()](#apidoc.element.aliyun-sdk.Signers.OTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OpenSearch ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.POP ()](#apidoc.element.aliyun-sdk.Signers.POP)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.RequestSigner (request)](#apidoc.element.aliyun-sdk.Signers.RequestSigner)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.SLS ()](#apidoc.element.aliyun-sdk.Signers.SLS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.TOP ()](#apidoc.element.aliyun-sdk.Signers.TOP)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>XML.Builder (root, rules, options)](#apidoc.element.aliyun-sdk.XML.Builder)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>XML.Parser (rules)](#apidoc.element.aliyun-sdk.XML.Parser)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>YunDun ()](#apidoc.element.aliyun-sdk.YunDun)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>util.Buffer (arg, encodingOrOffset, length)](#apidoc.element.aliyun-sdk.util.Buffer)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>BatchCompute.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>CDN.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>CMS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Config.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>DAYU.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>DRDS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>ECS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>ESS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Endpoint.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>EventListeners
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>GREEN.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpClient.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpRequest.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpResponse.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>JAQ.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>JSON
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>JSON.Builder.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>MEMCACHED
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>MEMCACHED.MemcachedClient.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>MTS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>OSS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>OTS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>OpenSearch.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>PUSH.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>ParamValidator.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>QueryParamSerializer.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>RAM.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>RDS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Request.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Response.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>SLB.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>SLS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>STS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>SequentialExecutor.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Service.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>ServiceInterface
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.BatchCompute.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.CMS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OSS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OTS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OpenSearch.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.POP.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.RequestSigner.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.SLS.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.TOP.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>XML
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>XML.Builder.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>XML.Parser.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>YunDun.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>api_loader
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>events
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>util
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>util.Buffer.prototype
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>util.base64
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>util.buffer
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>util.crypto
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>util.date
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>util.jamespath
1.  object <span class="apidocSignatureSpan">aliyun-sdk.</span>util.string
1.  string <span class="apidocSignatureSpan">aliyun-sdk.</span>VERSION

#### [module aliyun-sdk.BatchCompute](#apidoc.module.aliyun-sdk.BatchCompute)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>BatchCompute ()](#apidoc.element.aliyun-sdk.BatchCompute.BatchCompute)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.</span>__super__ (config)](#apidoc.element.aliyun-sdk.BatchCompute.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.</span>serviceIdentifier

#### [module aliyun-sdk.BatchCompute.prototype](#apidoc.module.aliyun-sdk.BatchCompute.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.addContentType)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.BatchCompute.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>extractData (resp, operation)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.extractData)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.extractError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>getFormatters ()](#apidoc.element.aliyun-sdk.BatchCompute.prototype.getFormatters)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.setupRequestListeners)

#### [module aliyun-sdk.CDN](#apidoc.module.aliyun-sdk.CDN)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>CDN ()](#apidoc.element.aliyun-sdk.CDN.CDN)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.CDN.</span>__super__ (config)](#apidoc.element.aliyun-sdk.CDN.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.CDN.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.CDN.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.CDN.</span>serviceIdentifier

#### [module aliyun-sdk.CDN.prototype](#apidoc.module.aliyun-sdk.CDN.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.CDN.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.CDN.prototype.constructor)

#### [module aliyun-sdk.CMS](#apidoc.module.aliyun-sdk.CMS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>CMS ()](#apidoc.element.aliyun-sdk.CMS.CMS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.CMS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.CMS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.CMS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.CMS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.CMS.</span>serviceIdentifier

#### [module aliyun-sdk.CMS.prototype](#apidoc.module.aliyun-sdk.CMS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.CMS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.CMS.prototype.extractData)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.CMS.prototype.extractError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.CMS.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.CMS.prototype.setupRequestListeners)

#### [module aliyun-sdk.Config](#apidoc.module.aliyun-sdk.Config)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Config (options)](#apidoc.element.aliyun-sdk.Config.Config)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Config.</span>__super__ ()](#apidoc.element.aliyun-sdk.Config.__super__)

#### [module aliyun-sdk.Config.prototype](#apidoc.module.aliyun-sdk.Config.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>clear ()](#apidoc.element.aliyun-sdk.Config.prototype.clear)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>constructor (options)](#apidoc.element.aliyun-sdk.Config.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>getCredentials ()](#apidoc.element.aliyun-sdk.Config.prototype.getCredentials)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>set (property, value, defaultValue)](#apidoc.element.aliyun-sdk.Config.prototype.set)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>keys

#### [module aliyun-sdk.DAYU](#apidoc.module.aliyun-sdk.DAYU)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>DAYU ()](#apidoc.element.aliyun-sdk.DAYU.DAYU)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.DAYU.</span>__super__ (config)](#apidoc.element.aliyun-sdk.DAYU.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.DAYU.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.DAYU.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.DAYU.</span>serviceIdentifier

#### [module aliyun-sdk.DAYU.prototype](#apidoc.module.aliyun-sdk.DAYU.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.DAYU.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.DAYU.prototype.constructor)

#### [module aliyun-sdk.DRDS](#apidoc.module.aliyun-sdk.DRDS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>DRDS ()](#apidoc.element.aliyun-sdk.DRDS.DRDS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.DRDS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.DRDS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.DRDS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.DRDS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.DRDS.</span>serviceIdentifier

#### [module aliyun-sdk.DRDS.prototype](#apidoc.module.aliyun-sdk.DRDS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.DRDS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.DRDS.prototype.constructor)

#### [module aliyun-sdk.ECS](#apidoc.module.aliyun-sdk.ECS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>ECS ()](#apidoc.element.aliyun-sdk.ECS.ECS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ECS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.ECS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.ECS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.ECS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.ECS.</span>serviceIdentifier

#### [module aliyun-sdk.ECS.prototype](#apidoc.module.aliyun-sdk.ECS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ECS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.ECS.prototype.constructor)

#### [module aliyun-sdk.ESS](#apidoc.module.aliyun-sdk.ESS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>ESS ()](#apidoc.element.aliyun-sdk.ESS.ESS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ESS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.ESS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.ESS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.ESS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.ESS.</span>serviceIdentifier

#### [module aliyun-sdk.ESS.prototype](#apidoc.module.aliyun-sdk.ESS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ESS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.ESS.prototype.constructor)

#### [module aliyun-sdk.Endpoint](#apidoc.module.aliyun-sdk.Endpoint)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Endpoint (endpoint)](#apidoc.element.aliyun-sdk.Endpoint.Endpoint)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Endpoint.</span>__super__ ()](#apidoc.element.aliyun-sdk.Endpoint.__super__)

#### [module aliyun-sdk.Endpoint.prototype](#apidoc.module.aliyun-sdk.Endpoint.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Endpoint.prototype.</span>constructor (endpoint)](#apidoc.element.aliyun-sdk.Endpoint.prototype.constructor)

#### [module aliyun-sdk.GREEN](#apidoc.module.aliyun-sdk.GREEN)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>GREEN ()](#apidoc.element.aliyun-sdk.GREEN.GREEN)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.GREEN.</span>__super__ (config)](#apidoc.element.aliyun-sdk.GREEN.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.GREEN.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.GREEN.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.GREEN.</span>serviceIdentifier

#### [module aliyun-sdk.GREEN.prototype](#apidoc.module.aliyun-sdk.GREEN.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.GREEN.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.GREEN.prototype.constructor)

#### [module aliyun-sdk.HttpClient](#apidoc.module.aliyun-sdk.HttpClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpClient ()](#apidoc.element.aliyun-sdk.HttpClient.HttpClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.</span>__super__ ()](#apidoc.element.aliyun-sdk.HttpClient.__super__)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.</span>getInstance ()](#apidoc.element.aliyun-sdk.HttpClient.getInstance)
1.  number <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.</span>streamsApiVersion

#### [module aliyun-sdk.HttpClient.prototype](#apidoc.module.aliyun-sdk.HttpClient.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>bufferToStream (buffer)](#apidoc.element.aliyun-sdk.HttpClient.prototype.bufferToStream)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.HttpClient.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>handleRequest (httpRequest, httpOptions, callback, errCallback)](#apidoc.element.aliyun-sdk.HttpClient.prototype.handleRequest)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>progressStream (stream, httpRequest)](#apidoc.element.aliyun-sdk.HttpClient.prototype.progressStream)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>sslAgent ()](#apidoc.element.aliyun-sdk.HttpClient.prototype.sslAgent)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>writeBody (stream, httpRequest)](#apidoc.element.aliyun-sdk.HttpClient.prototype.writeBody)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>emitter

#### [module aliyun-sdk.HttpRequest](#apidoc.module.aliyun-sdk.HttpRequest)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpRequest (endpoint, region)](#apidoc.element.aliyun-sdk.HttpRequest.HttpRequest)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.</span>__super__ ()](#apidoc.element.aliyun-sdk.HttpRequest.__super__)

#### [module aliyun-sdk.HttpRequest.prototype](#apidoc.module.aliyun-sdk.HttpRequest.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>constructor (endpoint, region)](#apidoc.element.aliyun-sdk.HttpRequest.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>debug ()](#apidoc.element.aliyun-sdk.HttpRequest.prototype.debug)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>pathname ()](#apidoc.element.aliyun-sdk.HttpRequest.prototype.pathname)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>search ()](#apidoc.element.aliyun-sdk.HttpRequest.prototype.search)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>setUserAgent ()](#apidoc.element.aliyun-sdk.HttpRequest.prototype.setUserAgent)

#### [module aliyun-sdk.HttpResponse](#apidoc.module.aliyun-sdk.HttpResponse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpResponse ()](#apidoc.element.aliyun-sdk.HttpResponse.HttpResponse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpResponse.</span>__super__ ()](#apidoc.element.aliyun-sdk.HttpResponse.__super__)

#### [module aliyun-sdk.HttpResponse.prototype](#apidoc.module.aliyun-sdk.HttpResponse.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.HttpResponse.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.HttpResponse.prototype.constructor)

#### [module aliyun-sdk.JAQ](#apidoc.module.aliyun-sdk.JAQ)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>JAQ ()](#apidoc.element.aliyun-sdk.JAQ.JAQ)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.JAQ.</span>__super__ (config)](#apidoc.element.aliyun-sdk.JAQ.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.JAQ.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.JAQ.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.JAQ.</span>serviceIdentifier

#### [module aliyun-sdk.JAQ.prototype](#apidoc.module.aliyun-sdk.JAQ.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.JAQ.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.JAQ.prototype.constructor)

#### [module aliyun-sdk.JSON](#apidoc.module.aliyun-sdk.JSON)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.JSON.</span>Builder (rules, options)](#apidoc.element.aliyun-sdk.JSON.Builder)

#### [module aliyun-sdk.JSON.Builder](#apidoc.module.aliyun-sdk.JSON.Builder)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.JSON.</span>Builder (rules, options)](#apidoc.element.aliyun-sdk.JSON.Builder.Builder)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.JSON.Builder.</span>__super__ ()](#apidoc.element.aliyun-sdk.JSON.Builder.__super__)

#### [module aliyun-sdk.JSON.Builder.prototype](#apidoc.module.aliyun-sdk.JSON.Builder.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.JSON.Builder.prototype.</span>build (params)](#apidoc.element.aliyun-sdk.JSON.Builder.prototype.build)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.JSON.Builder.prototype.</span>constructor (rules, options)](#apidoc.element.aliyun-sdk.JSON.Builder.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.JSON.Builder.prototype.</span>translate (rules, value)](#apidoc.element.aliyun-sdk.JSON.Builder.prototype.translate)

#### [module aliyun-sdk.MEMCACHED](#apidoc.module.aliyun-sdk.MEMCACHED)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>MemcachedClient (stream, options)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>createClient (port_arg, host_arg, options)](#apidoc.element.aliyun-sdk.MEMCACHED.createClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>createClientFromString (s)](#apidoc.element.aliyun-sdk.MEMCACHED.createClientFromString)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>protocol

#### [module aliyun-sdk.MEMCACHED.MemcachedClient](#apidoc.module.aliyun-sdk.MEMCACHED.MemcachedClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>MemcachedClient (stream, options)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.MemcachedClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.</span>super_ ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.super_)

#### [module aliyun-sdk.MEMCACHED.MemcachedClient.prototype](#apidoc.module.aliyun-sdk.MEMCACHED.MemcachedClient.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>ADD (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.ADD)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>APPEND (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.APPEND)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>AUTH (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.AUTH)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>DECREMENT (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.DECREMENT)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>DELETE (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.DELETE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>GET (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.GET)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>INCREMENT (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.INCREMENT)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>NOOP (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.NOOP)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>PREPEND (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.PREPEND)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>QUIT (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.QUIT)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>REPLACE (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.REPLACE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>SET (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.SET)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>VERSION (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.VERSION)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>add (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.add)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>append (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.append)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>auth (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.auth)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>connection_gone (why)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.connection_gone)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>decrement (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.decrement)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>delete (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.delete)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>do_auth ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.do_auth)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>end ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.end)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>flush_and_error (message)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.flush_and_error)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>get (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.get)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>increment (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.increment)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>init_parser ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.init_parser)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>initialize_retry_vars ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.initialize_retry_vars)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>noop (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.noop)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>on_connect ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_connect)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>on_data (data)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_data)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>on_error (msg)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_error)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>on_ready ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_ready)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>prepend (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.prepend)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>quit (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.quit)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>ready_check ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.ready_check)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>reconnect ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.reconnect)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>replace (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.replace)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>return_reply (reply)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.return_reply)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>send_command (command, args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.send_command)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>send_offline_queue ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.send_offline_queue)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>set (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.set)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>unref ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.unref)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>version (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.version)

#### [module aliyun-sdk.MTS](#apidoc.module.aliyun-sdk.MTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>MTS ()](#apidoc.element.aliyun-sdk.MTS.MTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MTS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.MTS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.MTS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.MTS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.MTS.</span>serviceIdentifier

#### [module aliyun-sdk.MTS.prototype](#apidoc.module.aliyun-sdk.MTS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.MTS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.MTS.prototype.constructor)

#### [module aliyun-sdk.NodeHttpClient](#apidoc.module.aliyun-sdk.NodeHttpClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>NodeHttpClient ()](#apidoc.element.aliyun-sdk.NodeHttpClient.NodeHttpClient)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.NodeHttpClient.</span>__super__ ()](#apidoc.element.aliyun-sdk.NodeHttpClient.__super__)

#### [module aliyun-sdk.OSS](#apidoc.module.aliyun-sdk.OSS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>OSS ()](#apidoc.element.aliyun-sdk.OSS.OSS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.OSS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.OSS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.OSS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.OSS.</span>serviceIdentifier

#### [module aliyun-sdk.OSS.prototype](#apidoc.module.aliyun-sdk.OSS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.OSS.prototype.addContentType)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>computeContentMd5 (req)](#apidoc.element.aliyun-sdk.OSS.prototype.computeContentMd5)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.OSS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>escapePathParam (value)](#apidoc.element.aliyun-sdk.OSS.prototype.escapePathParam)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.OSS.prototype.extractData)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.OSS.prototype.extractError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>getSignedUrl (operation, params, callback)](#apidoc.element.aliyun-sdk.OSS.prototype.getSignedUrl)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.OSS.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>populateURI (req)](#apidoc.element.aliyun-sdk.OSS.prototype.populateURI)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>retryableError (error, request)](#apidoc.element.aliyun-sdk.OSS.prototype.retryableError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.OSS.prototype.setupRequestListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.OSS.prototype.successfulResponse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>willComputeChecksums (req)](#apidoc.element.aliyun-sdk.OSS.prototype.willComputeChecksums)

#### [module aliyun-sdk.OTS](#apidoc.module.aliyun-sdk.OTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>OTS ()](#apidoc.element.aliyun-sdk.OTS.OTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.OTS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.OTS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.OTS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.OTS.</span>serviceIdentifier

#### [module aliyun-sdk.OTS.prototype](#apidoc.module.aliyun-sdk.OTS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.OTS.prototype.addContentType)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>buildContent (req)](#apidoc.element.aliyun-sdk.OTS.prototype.buildContent)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>computeContentMd5 (req)](#apidoc.element.aliyun-sdk.OTS.prototype.computeContentMd5)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.OTS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>escapePathParam (value)](#apidoc.element.aliyun-sdk.OTS.prototype.escapePathParam)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.OTS.prototype.extractData)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.OTS.prototype.extractError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.OTS.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>populateURI (req)](#apidoc.element.aliyun-sdk.OTS.prototype.populateURI)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>retryableError (error, request)](#apidoc.element.aliyun-sdk.OTS.prototype.retryableError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.OTS.prototype.setupRequestListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.OTS.prototype.successfulResponse)

#### [module aliyun-sdk.OpenSearch](#apidoc.module.aliyun-sdk.OpenSearch)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>OpenSearch ()](#apidoc.element.aliyun-sdk.OpenSearch.OpenSearch)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.</span>__super__ (config)](#apidoc.element.aliyun-sdk.OpenSearch.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.</span>serviceIdentifier

#### [module aliyun-sdk.OpenSearch.prototype](#apidoc.module.aliyun-sdk.OpenSearch.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.addContentType)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>buildContent (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.buildContent)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>computeContentMd5 (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.computeContentMd5)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>computeSha256 (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.computeSha256)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.OpenSearch.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>escapePathParam (value)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.escapePathParam)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.extractData)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.extractError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>populateURI (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.populateURI)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>retryableError (error, request)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.retryableError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.setupRequestListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.successfulResponse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>willComputeChecksums (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.willComputeChecksums)

#### [module aliyun-sdk.PUSH](#apidoc.module.aliyun-sdk.PUSH)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>PUSH ()](#apidoc.element.aliyun-sdk.PUSH.PUSH)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.PUSH.</span>__super__ (config)](#apidoc.element.aliyun-sdk.PUSH.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.PUSH.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.PUSH.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.PUSH.</span>serviceIdentifier

#### [module aliyun-sdk.PUSH.prototype](#apidoc.module.aliyun-sdk.PUSH.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.PUSH.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.PUSH.prototype.constructor)

#### [module aliyun-sdk.ParamValidator](#apidoc.module.aliyun-sdk.ParamValidator)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>ParamValidator ()](#apidoc.element.aliyun-sdk.ParamValidator.ParamValidator)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.</span>__super__ ()](#apidoc.element.aliyun-sdk.ParamValidator.__super__)

#### [module aliyun-sdk.ParamValidator.prototype](#apidoc.module.aliyun-sdk.ParamValidator.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.ParamValidator.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>fail (code, message)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.fail)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validate (rules, params, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validate)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateList (rules, params, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateList)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateMap (rules, params, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateMap)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateMember (rules, param, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateMember)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateNumber (context, value)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateNumber)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validatePayload (context, value)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validatePayload)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateScalar (rules, value, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateScalar)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateStructure (rules, params, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateStructure)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateType (context, value, acceptedTypes, type)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateType)

#### [module aliyun-sdk.QueryParamSerializer](#apidoc.module.aliyun-sdk.QueryParamSerializer)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>QueryParamSerializer (rules, options)](#apidoc.element.aliyun-sdk.QueryParamSerializer.QueryParamSerializer)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.</span>__super__ ()](#apidoc.element.aliyun-sdk.QueryParamSerializer.__super__)

#### [module aliyun-sdk.QueryParamSerializer.prototype](#apidoc.module.aliyun-sdk.QueryParamSerializer.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>constructor (rules, options)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serialize (params, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serialize)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serializeList (name, list, rules, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeList)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serializeMap (name, map, rules, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeMap)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serializeMember (name, value, rules, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeMember)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serializeStructure (prefix, struct, rules, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeStructure)

#### [module aliyun-sdk.RAM](#apidoc.module.aliyun-sdk.RAM)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>RAM ()](#apidoc.element.aliyun-sdk.RAM.RAM)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.RAM.</span>__super__ (config)](#apidoc.element.aliyun-sdk.RAM.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.RAM.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.RAM.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.RAM.</span>serviceIdentifier

#### [module aliyun-sdk.RAM.prototype](#apidoc.module.aliyun-sdk.RAM.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.RAM.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.RAM.prototype.constructor)

#### [module aliyun-sdk.RDS](#apidoc.module.aliyun-sdk.RDS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>RDS ()](#apidoc.element.aliyun-sdk.RDS.RDS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.RDS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.RDS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.RDS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.RDS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.RDS.</span>serviceIdentifier

#### [module aliyun-sdk.RDS.prototype](#apidoc.module.aliyun-sdk.RDS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.RDS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.RDS.prototype.constructor)

#### [module aliyun-sdk.Request](#apidoc.module.aliyun-sdk.Request)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Request (service, operation, params)](#apidoc.element.aliyun-sdk.Request.Request)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.</span>__super__ ()](#apidoc.element.aliyun-sdk.Request.__super__)

#### [module aliyun-sdk.Request.prototype](#apidoc.module.aliyun-sdk.Request.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>abort ()](#apidoc.element.aliyun-sdk.Request.prototype.abort)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addAsyncListener (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.addAsyncListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addListener (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addListeners (listeners)](#apidoc.element.aliyun-sdk.Request.prototype.addListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addNamedAsyncListener (name, eventName, callback)](#apidoc.element.aliyun-sdk.Request.prototype.addNamedAsyncListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addNamedListener (name, eventName, callback)](#apidoc.element.aliyun-sdk.Request.prototype.addNamedListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addNamedListeners (callback)](#apidoc.element.aliyun-sdk.Request.prototype.addNamedListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>build (callback)](#apidoc.element.aliyun-sdk.Request.prototype.build)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>callListeners (listeners, args, doneCallback)](#apidoc.element.aliyun-sdk.Request.prototype.callListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>constructor (service, operation, params)](#apidoc.element.aliyun-sdk.Request.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>createReadStream ()](#apidoc.element.aliyun-sdk.Request.prototype.createReadStream)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>eachItem (callback)](#apidoc.element.aliyun-sdk.Request.prototype.eachItem)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>eachPage (callback)](#apidoc.element.aliyun-sdk.Request.prototype.eachPage)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>emit (eventName, eventArgs, doneCallback)](#apidoc.element.aliyun-sdk.Request.prototype.emit)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>emitEvent (eventName, args, done)](#apidoc.element.aliyun-sdk.Request.prototype.emitEvent)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>eventParameters (eventName)](#apidoc.element.aliyun-sdk.Request.prototype.eventParameters)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>isPageable ()](#apidoc.element.aliyun-sdk.Request.prototype.isPageable)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>listeners (eventName)](#apidoc.element.aliyun-sdk.Request.prototype.listeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>on (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.on)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>onAsync (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.onAsync)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>removeAllListeners (eventName)](#apidoc.element.aliyun-sdk.Request.prototype.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>removeListener (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.removeListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>runTo (state, done)](#apidoc.element.aliyun-sdk.Request.prototype.runTo)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>send (callback)](#apidoc.element.aliyun-sdk.Request.prototype.send)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>unhandledErrorCallback (err)](#apidoc.element.aliyun-sdk.Request.prototype.unhandledErrorCallback)

#### [module aliyun-sdk.Response](#apidoc.module.aliyun-sdk.Response)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Response (request)](#apidoc.element.aliyun-sdk.Response.Response)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Response.</span>__super__ ()](#apidoc.element.aliyun-sdk.Response.__super__)

#### [module aliyun-sdk.Response.prototype](#apidoc.module.aliyun-sdk.Response.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Response.prototype.</span>cacheNextPageTokens ()](#apidoc.element.aliyun-sdk.Response.prototype.cacheNextPageTokens)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Response.prototype.</span>constructor (request)](#apidoc.element.aliyun-sdk.Response.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Response.prototype.</span>hasNextPage ()](#apidoc.element.aliyun-sdk.Response.prototype.hasNextPage)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Response.prototype.</span>nextPage (callback)](#apidoc.element.aliyun-sdk.Response.prototype.nextPage)

#### [module aliyun-sdk.SLB](#apidoc.module.aliyun-sdk.SLB)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>SLB ()](#apidoc.element.aliyun-sdk.SLB.SLB)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLB.</span>__super__ (config)](#apidoc.element.aliyun-sdk.SLB.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.SLB.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.SLB.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.SLB.</span>serviceIdentifier

#### [module aliyun-sdk.SLB.prototype](#apidoc.module.aliyun-sdk.SLB.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLB.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.SLB.prototype.constructor)

#### [module aliyun-sdk.SLS](#apidoc.module.aliyun-sdk.SLS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>SLS ()](#apidoc.element.aliyun-sdk.SLS.SLS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.SLS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.SLS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.SLS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.SLS.</span>serviceIdentifier

#### [module aliyun-sdk.SLS.prototype](#apidoc.module.aliyun-sdk.SLS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.SLS.prototype.addContentType)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>buildContent (req, done)](#apidoc.element.aliyun-sdk.SLS.prototype.buildContent)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>computeContentMd5 (req)](#apidoc.element.aliyun-sdk.SLS.prototype.computeContentMd5)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>computeSha256 (req)](#apidoc.element.aliyun-sdk.SLS.prototype.computeSha256)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.SLS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>escapePathParam (value)](#apidoc.element.aliyun-sdk.SLS.prototype.escapePathParam)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.SLS.prototype.extractData)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.SLS.prototype.extractError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.SLS.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>populateURI (req)](#apidoc.element.aliyun-sdk.SLS.prototype.populateURI)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>retryableError (error, request)](#apidoc.element.aliyun-sdk.SLS.prototype.retryableError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.SLS.prototype.setupRequestListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.SLS.prototype.successfulResponse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>willComputeChecksums (req)](#apidoc.element.aliyun-sdk.SLS.prototype.willComputeChecksums)

#### [module aliyun-sdk.STS](#apidoc.module.aliyun-sdk.STS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>STS ()](#apidoc.element.aliyun-sdk.STS.STS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.STS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.STS.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.STS.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.STS.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.STS.</span>serviceIdentifier

#### [module aliyun-sdk.STS.prototype](#apidoc.module.aliyun-sdk.STS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.STS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.STS.prototype.constructor)

#### [module aliyun-sdk.SequentialExecutor](#apidoc.module.aliyun-sdk.SequentialExecutor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>SequentialExecutor ()](#apidoc.element.aliyun-sdk.SequentialExecutor.SequentialExecutor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.</span>__super__ ()](#apidoc.element.aliyun-sdk.SequentialExecutor.__super__)

#### [module aliyun-sdk.SequentialExecutor.prototype](#apidoc.module.aliyun-sdk.SequentialExecutor.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addAsyncListener (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addAsyncListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addListener (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addListeners (listeners)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addNamedAsyncListener (name, eventName, callback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedAsyncListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addNamedListener (name, eventName, callback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addNamedListeners (callback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>callListeners (listeners, args, doneCallback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.callListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>emit (eventName, eventArgs, doneCallback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.emit)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>listeners (eventName)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.listeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>on (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.on)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>onAsync (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.onAsync)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>removeAllListeners (eventName)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>removeListener (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.removeListener)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>unhandledErrorCallback (err)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.unhandledErrorCallback)

#### [module aliyun-sdk.Service](#apidoc.module.aliyun-sdk.Service)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>Service (config)](#apidoc.element.aliyun-sdk.Service.Service)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.</span>__super__ ()](#apidoc.element.aliyun-sdk.Service.__super__)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.</span>defineMethods (svc)](#apidoc.element.aliyun-sdk.Service.defineMethods)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.</span>defineService (serviceIdentifier, versions, features)](#apidoc.element.aliyun-sdk.Service.defineService)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.</span>defineServiceApi (superclass, version)](#apidoc.element.aliyun-sdk.Service.defineServiceApi)

#### [module aliyun-sdk.Service.prototype](#apidoc.module.aliyun-sdk.Service.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>addAllRequestListeners (request)](#apidoc.element.aliyun-sdk.Service.prototype.addAllRequestListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>constructor (config)](#apidoc.element.aliyun-sdk.Service.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>getLatestServiceClass (version)](#apidoc.element.aliyun-sdk.Service.prototype.getLatestServiceClass)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>getSignerClass ()](#apidoc.element.aliyun-sdk.Service.prototype.getSignerClass)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>initialize (config)](#apidoc.element.aliyun-sdk.Service.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>isRegionCN ()](#apidoc.element.aliyun-sdk.Service.prototype.isRegionCN)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>isRegionV4 ()](#apidoc.element.aliyun-sdk.Service.prototype.isRegionV4)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>loadServiceClass (serviceConfig)](#apidoc.element.aliyun-sdk.Service.prototype.loadServiceClass)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>makeRequest (operation, params, callback)](#apidoc.element.aliyun-sdk.Service.prototype.makeRequest)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>makeUnauthenticatedRequest (operation, params, callback)](#apidoc.element.aliyun-sdk.Service.prototype.makeUnauthenticatedRequest)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>networkingError (error)](#apidoc.element.aliyun-sdk.Service.prototype.networkingError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>numRetries ()](#apidoc.element.aliyun-sdk.Service.prototype.numRetries)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>paginationConfig (operation, throwException)](#apidoc.element.aliyun-sdk.Service.prototype.paginationConfig)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>retryDelays ()](#apidoc.element.aliyun-sdk.Service.prototype.retryDelays)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>retryableError (error)](#apidoc.element.aliyun-sdk.Service.prototype.retryableError)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>serviceInterface ()](#apidoc.element.aliyun-sdk.Service.prototype.serviceInterface)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>setupRequestListeners ()](#apidoc.element.aliyun-sdk.Service.prototype.setupRequestListeners)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.Service.prototype.successfulResponse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>throttledError (error)](#apidoc.element.aliyun-sdk.Service.prototype.throttledError)
1.  number <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>defaultRetryCount
1.  object <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>api

#### [module aliyun-sdk.Signers](#apidoc.module.aliyun-sdk.Signers)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>BatchCompute ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>CMS ()](#apidoc.element.aliyun-sdk.Signers.CMS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OSS ()](#apidoc.element.aliyun-sdk.Signers.OSS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OTS ()](#apidoc.element.aliyun-sdk.Signers.OTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OpenSearch ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>POP ()](#apidoc.element.aliyun-sdk.Signers.POP)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>RequestSigner (request)](#apidoc.element.aliyun-sdk.Signers.RequestSigner)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>SLS ()](#apidoc.element.aliyun-sdk.Signers.SLS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>TOP ()](#apidoc.element.aliyun-sdk.Signers.TOP)

#### [module aliyun-sdk.Signers.BatchCompute](#apidoc.module.aliyun-sdk.Signers.BatchCompute)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>BatchCompute ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.BatchCompute)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.BatchCompute.__super__)

#### [module aliyun-sdk.Signers.BatchCompute.prototype](#apidoc.module.aliyun-sdk.Signers.BatchCompute.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.addAuthorization)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>canonicalizedAmzHeaders ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.canonicalizedAmzHeaders)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>canonicalizedResource ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.canonicalizedResource)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.sign)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.stringToSign)

#### [module aliyun-sdk.Signers.CMS](#apidoc.module.aliyun-sdk.Signers.CMS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>CMS ()](#apidoc.element.aliyun-sdk.Signers.CMS.CMS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.CMS.__super__)

#### [module aliyun-sdk.Signers.CMS.prototype](#apidoc.module.aliyun-sdk.Signers.CMS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.addAuthorization)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>canonicalizedQueryString ()](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.canonicalizedQueryString)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>cmsEscape (clearString)](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.cmsEscape)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.sign)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.stringToSign)

#### [module aliyun-sdk.Signers.OSS](#apidoc.module.aliyun-sdk.Signers.OSS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OSS ()](#apidoc.element.aliyun-sdk.Signers.OSS.OSS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.OSS.__super__)

#### [module aliyun-sdk.Signers.OSS.prototype](#apidoc.module.aliyun-sdk.Signers.OSS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.addAuthorization)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>canonicalizedHeaders ()](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.canonicalizedHeaders)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>canonicalizedResource ()](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.canonicalizedResource)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.sign)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.stringToSign)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>responseHeaders
1.  object <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>subResources

#### [module aliyun-sdk.Signers.OTS](#apidoc.module.aliyun-sdk.Signers.OTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OTS ()](#apidoc.element.aliyun-sdk.Signers.OTS.OTS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.OTS.__super__)

#### [module aliyun-sdk.Signers.OTS.prototype](#apidoc.module.aliyun-sdk.Signers.OTS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.addAuthorization)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>canonicalizedHeaders ()](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.canonicalizedHeaders)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>canonicalizedResource ()](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.canonicalizedResource)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.sign)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.stringToSign)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>responseHeaders
1.  object <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>subResources

#### [module aliyun-sdk.Signers.OpenSearch](#apidoc.module.aliyun-sdk.Signers.OpenSearch)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OpenSearch ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch.OpenSearch)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.OpenSearch.__super__)

#### [module aliyun-sdk.Signers.OpenSearch.prototype](#apidoc.module.aliyun-sdk.Signers.OpenSearch.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.addAuthorization)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>canonicalizedQueryString ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.canonicalizedQueryString)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.sign)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.stringToSign)

#### [module aliyun-sdk.Signers.POP](#apidoc.module.aliyun-sdk.Signers.POP)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>POP ()](#apidoc.element.aliyun-sdk.Signers.POP.POP)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.POP.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.POP.__super__)

#### [module aliyun-sdk.Signers.POP.prototype](#apidoc.module.aliyun-sdk.Signers.POP.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.POP.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.POP.prototype.addAuthorization)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.POP.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.POP.prototype.constructor)

#### [module aliyun-sdk.Signers.RequestSigner](#apidoc.module.aliyun-sdk.Signers.RequestSigner)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>RequestSigner (request)](#apidoc.element.aliyun-sdk.Signers.RequestSigner.RequestSigner)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.RequestSigner.</span>__super__ ()](#apidoc.element.aliyun-sdk.Signers.RequestSigner.__super__)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.RequestSigner.</span>getVersion (version)](#apidoc.element.aliyun-sdk.Signers.RequestSigner.getVersion)

#### [module aliyun-sdk.Signers.RequestSigner.prototype](#apidoc.module.aliyun-sdk.Signers.RequestSigner.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.RequestSigner.prototype.</span>constructor (request)](#apidoc.element.aliyun-sdk.Signers.RequestSigner.prototype.constructor)

#### [module aliyun-sdk.Signers.SLS](#apidoc.module.aliyun-sdk.Signers.SLS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>SLS ()](#apidoc.element.aliyun-sdk.Signers.SLS.SLS)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.SLS.__super__)

#### [module aliyun-sdk.Signers.SLS.prototype](#apidoc.module.aliyun-sdk.Signers.SLS.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.addAuthorization)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>canonicalizedAmzHeaders ()](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.canonicalizedAmzHeaders)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>canonicalizedResource ()](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.canonicalizedResource)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.sign)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.stringToSign)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>responseHeaders

#### [module aliyun-sdk.Signers.TOP](#apidoc.module.aliyun-sdk.Signers.TOP)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>TOP ()](#apidoc.element.aliyun-sdk.Signers.TOP.TOP)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.TOP.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.TOP.__super__)

#### [module aliyun-sdk.Signers.TOP.prototype](#apidoc.module.aliyun-sdk.Signers.TOP.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.TOP.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.TOP.prototype.addAuthorization)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.Signers.TOP.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.TOP.prototype.constructor)

#### [module aliyun-sdk.XML](#apidoc.module.aliyun-sdk.XML)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.</span>Builder (root, rules, options)](#apidoc.element.aliyun-sdk.XML.Builder)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.</span>Parser (rules)](#apidoc.element.aliyun-sdk.XML.Parser)

#### [module aliyun-sdk.XML.Builder](#apidoc.module.aliyun-sdk.XML.Builder)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.</span>Builder (root, rules, options)](#apidoc.element.aliyun-sdk.XML.Builder.Builder)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.</span>__super__ ()](#apidoc.element.aliyun-sdk.XML.Builder.__super__)

#### [module aliyun-sdk.XML.Builder.prototype](#apidoc.module.aliyun-sdk.XML.Builder.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>applyNamespaces (xml, rules)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.applyNamespaces)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>constructor (root, rules, options)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>serializeList (name, rules, list, xml)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeList)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>serializeMember (memberName, rules, params, xml)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeMember)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>serializeStructure (rules, params, xml)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeStructure)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>toXML (params)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.toXML)

#### [module aliyun-sdk.XML.Parser](#apidoc.module.aliyun-sdk.XML.Parser)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.</span>Parser (rules)](#apidoc.element.aliyun-sdk.XML.Parser.Parser)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.</span>__super__ ()](#apidoc.element.aliyun-sdk.XML.Parser.__super__)

#### [module aliyun-sdk.XML.Parser.prototype](#apidoc.module.aliyun-sdk.XML.Parser.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>constructor (rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parse (xml)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseList (list, rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseList)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseMap (map, rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseMap)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseMember (values, rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseMember)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseStructure (structure, rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseStructure)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseTimestamp (value)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseTimestamp)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>options

#### [module aliyun-sdk.YunDun](#apidoc.module.aliyun-sdk.YunDun)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.</span>YunDun ()](#apidoc.element.aliyun-sdk.YunDun.YunDun)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.YunDun.</span>__super__ (config)](#apidoc.element.aliyun-sdk.YunDun.__super__)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.YunDun.</span>apiVersions
1.  object <span class="apidocSignatureSpan">aliyun-sdk.YunDun.</span>services
1.  string <span class="apidocSignatureSpan">aliyun-sdk.YunDun.</span>serviceIdentifier

#### [module aliyun-sdk.YunDun.prototype](#apidoc.module.aliyun-sdk.YunDun.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.YunDun.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.YunDun.prototype.constructor)

#### [module aliyun-sdk.api_loader](#apidoc.module.aliyun-sdk.api_loader)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceFile (svc, version)](#apidoc.element.aliyun-sdk.api_loader.serviceFile)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceIdentifier (svc)](#apidoc.element.aliyun-sdk.api_loader.serviceIdentifier)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceName (svc)](#apidoc.element.aliyun-sdk.api_loader.serviceName)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceVersions (svc)](#apidoc.element.aliyun-sdk.api_loader.serviceVersions)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceNames
1.  object <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>services

#### [module aliyun-sdk.util](#apidoc.module.aliyun-sdk.util)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>Buffer (arg, encodingOrOffset, length)](#apidoc.element.aliyun-sdk.util.Buffer)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>arrayEach (array, iterFunction)](#apidoc.element.aliyun-sdk.util.arrayEach)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>copy (object)](#apidoc.element.aliyun-sdk.util.copy)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>each (object, iterFunction)](#apidoc.element.aliyun-sdk.util.each)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>engine ()](#apidoc.element.aliyun-sdk.util.engine)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>error (err, options)](#apidoc.element.aliyun-sdk.util.error)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>hideProperties (obj, props)](#apidoc.element.aliyun-sdk.util.hideProperties)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>inherit (klass, features)](#apidoc.element.aliyun-sdk.util.inherit)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>isBrowser ()](#apidoc.element.aliyun-sdk.util.isBrowser)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>isEmpty (obj)](#apidoc.element.aliyun-sdk.util.isEmpty)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>isNode ()](#apidoc.element.aliyun-sdk.util.isNode)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>isType (obj, type)](#apidoc.element.aliyun-sdk.util.isType)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>merge (obj1, obj2)](#apidoc.element.aliyun-sdk.util.merge)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>mixin ()](#apidoc.element.aliyun-sdk.util.mixin)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>nodeRequire (module)](#apidoc.element.aliyun-sdk.util.nodeRequire)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>opensearchEscape (clearString)](#apidoc.element.aliyun-sdk.util.opensearchEscape)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>popEscape (clearString)](#apidoc.element.aliyun-sdk.util.popEscape)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>queryParamsToString (params)](#apidoc.element.aliyun-sdk.util.queryParamsToString)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>readFileSync (path)](#apidoc.element.aliyun-sdk.util.readFileSync)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>topEscape (clearString)](#apidoc.element.aliyun-sdk.util.topEscape)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>typeName (type)](#apidoc.element.aliyun-sdk.util.typeName)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>update (obj1, obj2)](#apidoc.element.aliyun-sdk.util.update)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>uriEscape (string)](#apidoc.element.aliyun-sdk.util.uriEscape)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>uriEscapePath (string)](#apidoc.element.aliyun-sdk.util.uriEscapePath)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>urlFormat (url)](#apidoc.element.aliyun-sdk.util.urlFormat)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>urlParse (url)](#apidoc.element.aliyun-sdk.util.urlParse)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>userAgent ()](#apidoc.element.aliyun-sdk.util.userAgent)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>uuid ()](#apidoc.element.aliyun-sdk.util.uuid)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.util.</span>abort
1.  object <span class="apidocSignatureSpan">aliyun-sdk.util.</span>base64
1.  object <span class="apidocSignatureSpan">aliyun-sdk.util.</span>buffer
1.  object <span class="apidocSignatureSpan">aliyun-sdk.util.</span>crypto
1.  object <span class="apidocSignatureSpan">aliyun-sdk.util.</span>date
1.  object <span class="apidocSignatureSpan">aliyun-sdk.util.</span>jamespath
1.  object <span class="apidocSignatureSpan">aliyun-sdk.util.</span>string

#### [module aliyun-sdk.util.Buffer](#apidoc.module.aliyun-sdk.util.Buffer)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>Buffer (arg, encodingOrOffset, length)](#apidoc.element.aliyun-sdk.util.Buffer.Buffer)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>alloc (size, fill, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.alloc)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>allocUnsafe (size)](#apidoc.element.aliyun-sdk.util.Buffer.allocUnsafe)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>allocUnsafeSlow (size)](#apidoc.element.aliyun-sdk.util.Buffer.allocUnsafeSlow)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>byteLength (string, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.byteLength)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>compare (a, b)](#apidoc.element.aliyun-sdk.util.Buffer.compare)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>concat (list, length)](#apidoc.element.aliyun-sdk.util.Buffer.concat)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>from (value, encodingOrOffset, length)](#apidoc.element.aliyun-sdk.util.Buffer.from)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>isBuffer (b)](#apidoc.element.aliyun-sdk.util.Buffer.isBuffer)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>isEncoding (encoding)](#apidoc.element.aliyun-sdk.util.Buffer.isEncoding)
1.  number <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>poolSize

#### [module aliyun-sdk.util.Buffer.prototype](#apidoc.module.aliyun-sdk.util.Buffer.prototype)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>asciiSlice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.asciiSlice)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>asciiWrite ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.asciiWrite)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>base64Slice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.base64Slice)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>base64Write ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.base64Write)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>compare (target, start, end, thisStart, thisEnd)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.compare)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>copy ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.copy)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>equals (b)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.equals)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>fill (val, start, end, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.fill)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>hexSlice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.hexSlice)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>hexWrite ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.hexWrite)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>includes (val, byteOffset, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.includes)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>indexOf (val, byteOffset, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.indexOf)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>inspect ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>lastIndexOf (val, byteOffset, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>latin1Slice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.latin1Slice)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>latin1Write ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.latin1Write)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readDoubleBE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readDoubleBE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readDoubleLE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readDoubleLE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readFloatBE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readFloatBE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readFloatLE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readFloatLE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt16BE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt16BE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt16LE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt16LE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt32BE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt32BE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt32LE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt32LE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt8 (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt8)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readIntBE (offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readIntBE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readIntLE (offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readIntLE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt16BE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt16BE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt16LE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt16LE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt32BE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt32BE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt32LE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt32LE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt8 (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt8)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUIntBE (offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUIntBE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUIntLE (offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUIntLE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>slice (start, end)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.slice)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>swap16 ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.swap16)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>swap32 ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.swap32)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>swap64 ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.swap64)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>toJSON ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>toString ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.toString)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>ucs2Slice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.ucs2Slice)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>ucs2Write ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.ucs2Write)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>utf8Slice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.utf8Slice)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>utf8Write ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.utf8Write)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>write (string, offset, length, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.write)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeDoubleBE (val, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeDoubleBE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeDoubleLE (val, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeDoubleLE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeFloatBE (val, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeFloatBE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeFloatLE (val, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeFloatLE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt16BE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt16BE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt16LE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt16LE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt32BE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt32BE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt32LE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt32LE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt8 (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt8)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeIntBE (value, offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeIntBE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeIntLE (value, offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeIntLE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt16BE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt16BE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt16LE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt16LE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt32BE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt32BE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt32LE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt32LE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt8 (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt8)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUIntBE (value, offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUIntBE)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUIntLE (value, offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUIntLE)

#### [module aliyun-sdk.util.base64](#apidoc.module.aliyun-sdk.util.base64)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.base64.</span>decode (string)](#apidoc.element.aliyun-sdk.util.base64.decode)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.base64.</span>encode (string)](#apidoc.element.aliyun-sdk.util.base64.encode)

#### [module aliyun-sdk.util.buffer](#apidoc.module.aliyun-sdk.util.buffer)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.buffer.</span>concat (buffers)](#apidoc.element.aliyun-sdk.util.buffer.concat)

#### [module aliyun-sdk.util.crypto](#apidoc.module.aliyun-sdk.util.crypto)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>crc32 (data)](#apidoc.element.aliyun-sdk.util.crypto.crc32)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>createHash (algorithm)](#apidoc.element.aliyun-sdk.util.crypto.createHash)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>hmac (key, string, digest, fn)](#apidoc.element.aliyun-sdk.util.crypto.hmac)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>md5 (data, digest)](#apidoc.element.aliyun-sdk.util.crypto.md5)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>sha256 (string, digest)](#apidoc.element.aliyun-sdk.util.crypto.sha256)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>toHex (data)](#apidoc.element.aliyun-sdk.util.crypto.toHex)
1.  object <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>crc32Table

#### [module aliyun-sdk.util.date](#apidoc.module.aliyun-sdk.util.date)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>format (date, formatter)](#apidoc.element.aliyun-sdk.util.date.format)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>from (date)](#apidoc.element.aliyun-sdk.util.date.from)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>getDate ()](#apidoc.element.aliyun-sdk.util.date.getDate)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>iso8601 (date)](#apidoc.element.aliyun-sdk.util.date.iso8601)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>rfc822 (date)](#apidoc.element.aliyun-sdk.util.date.rfc822)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>top (date, fmt)](#apidoc.element.aliyun-sdk.util.date.top)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>unixMilliseconds (date)](#apidoc.element.aliyun-sdk.util.date.unixMilliseconds)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>unixSeconds (date)](#apidoc.element.aliyun-sdk.util.date.unixSeconds)

#### [module aliyun-sdk.util.jamespath](#apidoc.module.aliyun-sdk.util.jamespath)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.jamespath.</span>find (expression, data)](#apidoc.element.aliyun-sdk.util.jamespath.find)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.jamespath.</span>query (expression, data)](#apidoc.element.aliyun-sdk.util.jamespath.query)

#### [module aliyun-sdk.util.string](#apidoc.module.aliyun-sdk.util.string)
1.  [function <span class="apidocSignatureSpan">aliyun-sdk.util.string.</span>byteLength (string)](#apidoc.element.aliyun-sdk.util.string.byteLength)



# <a name="apidoc.module.aliyun-sdk"></a>[module aliyun-sdk](#apidoc.module.aliyun-sdk)

#### <a name="apidoc.element.aliyun-sdk.BatchCompute"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>BatchCompute ()](#apidoc.element.aliyun-sdk.BatchCompute)
- description and source-code
```javascript
BatchCompute = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.CDN"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>CDN ()](#apidoc.element.aliyun-sdk.CDN)
- description and source-code
```javascript
CDN = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.CMS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>CMS ()](#apidoc.element.aliyun-sdk.CMS)
- description and source-code
```javascript
CMS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Config"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Config (options)](#apidoc.element.aliyun-sdk.Config)
- description and source-code
```javascript
function Config(options) {
  if (options === undefined) options = {};

  ALY.util.each.call(this, this.keys, function (key, value) {
    this.set(key, options[key], value);
  });
}
```
- example usage
```shell
...
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
},

/**
 * @api private
 */
loadServiceClass: function loadServiceClass(serviceConfig) {
  if (!ALY.util.isEmpty(this.api)) {
...
```

#### <a name="apidoc.element.aliyun-sdk.DAYU"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>DAYU ()](#apidoc.element.aliyun-sdk.DAYU)
- description and source-code
```javascript
DAYU = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.DRDS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>DRDS ()](#apidoc.element.aliyun-sdk.DRDS)
- description and source-code
```javascript
DRDS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.ECS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>ECS ()](#apidoc.element.aliyun-sdk.ECS)
- description and source-code
```javascript
ECS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.ESS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>ESS ()](#apidoc.element.aliyun-sdk.ESS)
- description and source-code
```javascript
ESS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Endpoint"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Endpoint (endpoint)](#apidoc.element.aliyun-sdk.Endpoint)
- description and source-code
```javascript
function Endpoint(endpoint) {
  ALY.util.hideProperties(this, ['slashes', 'auth', 'hash', 'search', 'query']);

  if (typeof endpoint === 'undefined' || endpoint === null) {
    throw new Error('Invalid endpoint: ' + endpoint);
  }

  if (!endpoint.match(/^http/)) {
    throw new Error('错误的 endpoint 格式, 需要以 http 或者 https 开头');
  }

  ALY.util.update(this, ALY.util.urlParse(endpoint));

  // Ensure the port property is set as an integer
  if (this.port) {
    this.port = parseInt(this.port, 10);
  } else {
    this.port = this.protocol === 'https:' ? 443 : 80;
  }
}
```
- example usage
```shell
...
   * @param service [ALY.Service] the service to perform the operation on
   * @param operation [String] the operation to perform on the service
   * @param params [Object] parameters to send to the operation.
   *   See the operation's documentation for the format of the
   *   parameters.
   */
  constructor: function Request(service, operation, params) {
var endpoint = new ALY.Endpoint(service.config.endpoint);
var region = service.config.region;

this.service = service;
this.operation = operation;
this.params = params || {};
this.httpRequest = new ALY.HttpRequest(endpoint, region);
this.startTime = ALY.util.date.getDate();
...
```

#### <a name="apidoc.element.aliyun-sdk.GREEN"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>GREEN ()](#apidoc.element.aliyun-sdk.GREEN)
- description and source-code
```javascript
GREEN = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpClient"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpClient ()](#apidoc.element.aliyun-sdk.HttpClient)
- description and source-code
```javascript
HttpClient = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpRequest"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpRequest (endpoint, region)](#apidoc.element.aliyun-sdk.HttpRequest)
- description and source-code
```javascript
function HttpRequest(endpoint, region) {
  this.method = 'POST';
  this.path = endpoint.path || '/';
  this.headers = {};
  this.body = '';
  this.endpoint = endpoint;
  this.region = region;
  this.setUserAgent();
}
```
- example usage
```shell
...
  constructor: function Request(service, operation, params) {
var endpoint = new ALY.Endpoint(service.config.endpoint);
var region = service.config.region;

this.service = service;
this.operation = operation;
this.params = params || {};
this.httpRequest = new ALY.HttpRequest(endpoint, region);
this.startTime = ALY.util.date.getDate();

this.response = new ALY.Response(this);
this.restartCount = 0;
this._asm = new AcceptorStateMachine(fsm.states, 'validate');

ALY.SequentialExecutor.call(this);
...
```

#### <a name="apidoc.element.aliyun-sdk.HttpResponse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpResponse ()](#apidoc.element.aliyun-sdk.HttpResponse)
- description and source-code
```javascript
function HttpResponse() {
  this.statusCode = undefined;
  this.headers = {};
  this.body = undefined;
}
```
- example usage
```shell
...
 */
constructor: function Response(request) {
  this.request = request;
  this.data = null;
  this.error = null;
  this.retryCount = 0;
  this.redirectCount = 0;
  this.httpResponse = new ALY.HttpResponse();
},

nextPage: function nextPage(callback) {
  var config;
  var service = this.request.service;
  var operation = this.request.operation;
  try {
...
```

#### <a name="apidoc.element.aliyun-sdk.JAQ"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>JAQ ()](#apidoc.element.aliyun-sdk.JAQ)
- description and source-code
```javascript
JAQ = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.JSON.Builder"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>JSON.Builder (rules, options)](#apidoc.element.aliyun-sdk.JSON.Builder)
- description and source-code
```javascript
function JSONBuilder(rules, options) {
  this.rules = rules;
  this.timestampFormat = options.timestampFormat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>MEMCACHED.MemcachedClient (stream, options)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient)
- description and source-code
```javascript
function MemcachedClient(stream, options) {
  this.stream = stream;
  this.options = options = options || {};

  this.connection_id = ++connection_id;
  this.connected = false;
  this.ready = false;
  this.should_buffer = false;
  this.command_queue_high_water = this.options.command_queue_high_water || 1000;
  this.command_queue_low_water = this.options.command_queue_low_water || 0;
  this.command_queue = new Queue(); // holds sent commands to de-pipeline them
  this.offline_queue = new Queue(); // holds commands issued but not able to be sent
  options.expires = 0;
  this.enable_offline_queue = true;
  if (typeof this.options.enable_offline_queue === "boolean") {
    this.enable_offline_queue = this.options.enable_offline_queue;
  }

  this.initialize_retry_vars();

  this.closing = false;
  this.auth_username = null;
  if (options.username !== undefined) {
    this.auth_username = options.username;
  }
  this.auth_pass = null;
  if (options.password !== undefined) {
    this.auth_pass = options.password;
  }
  this.parser_module = null;

  var self = this;

  this.stream.on("connect", function () {
    debug('event: connect');
    self.on_connect();
  });

  this.stream.on("data", function (buffer_from_socket) {
    self.on_data(buffer_from_socket);
  });

  this.stream.on("error", function (msg) {
    self.on_error(msg.message);
  });

  this.stream.on("close", function () {
    self.connection_gone("close");
  });

  this.stream.on("end", function () {
    self.connection_gone("end");
  });

  this.stream.on("drain", function () {
    self.should_buffer = false;
    self.emit("drain");
  });

  events.EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MTS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>MTS ()](#apidoc.element.aliyun-sdk.MTS)
- description and source-code
```javascript
MTS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.NodeHttpClient"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>NodeHttpClient ()](#apidoc.element.aliyun-sdk.NodeHttpClient)
- description and source-code
```javascript
NodeHttpClient = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>OSS ()](#apidoc.element.aliyun-sdk.OSS)
- description and source-code
```javascript
OSS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
...
'''

目前在浏览器端运行的 sdk 还在测试阶段, 如果有问题请随时提出.

## 初始化

'''javascript
var oss = new ALY.OSS({
  accessKeyId: "在阿里云OSS申请的 accessKeyId",
  secretAccessKey: "在阿里云OSS申请的 secretAccessKey",
  securityToken: "",
  endpoint: 'http://oss-cn-hangzhou.aliyuncs.com',
  apiVersion: '2013-10-15'
});
'''
...
```

#### <a name="apidoc.element.aliyun-sdk.OTS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>OTS ()](#apidoc.element.aliyun-sdk.OTS)
- description and source-code
```javascript
OTS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>OpenSearch ()](#apidoc.element.aliyun-sdk.OpenSearch)
- description and source-code
```javascript
OpenSearch = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.PUSH"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>PUSH ()](#apidoc.element.aliyun-sdk.PUSH)
- description and source-code
```javascript
PUSH = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>ParamValidator ()](#apidoc.element.aliyun-sdk.ParamValidator)
- description and source-code
```javascript
ParamValidator = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
...
};

ALY.EventListeners = {
  Core: new ALY.SequentialExecutor().addNamedListeners(function(add, addAsync) {

add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
  if (req.httpRequest.headers['Content-Length'] === undefined) {
    var length = ALY.util.string.byteLength(req.httpRequest.body);
    req.httpRequest.headers['Content-Length'] = length;
  }
...
```

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>QueryParamSerializer (rules, options)](#apidoc.element.aliyun-sdk.QueryParamSerializer)
- description and source-code
```javascript
function QueryParamSerializer(rules, options) {
  this.rules = rules;
  this.timestampFormat = options ? options.timestampFormat : 'iso8601';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.RAM"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>RAM ()](#apidoc.element.aliyun-sdk.RAM)
- description and source-code
```javascript
RAM = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.RDS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>RDS ()](#apidoc.element.aliyun-sdk.RDS)
- description and source-code
```javascript
RDS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Request (service, operation, params)](#apidoc.element.aliyun-sdk.Request)
- description and source-code
```javascript
function Request(service, operation, params) {
  var endpoint = new ALY.Endpoint(service.config.endpoint);
  var region = service.config.region;

  this.service = service;
  this.operation = operation;
  this.params = params || {};
  this.httpRequest = new ALY.HttpRequest(endpoint, region);
  this.startTime = ALY.util.date.getDate();

  this.response = new ALY.Response(this);
  this.restartCount = 0;
  this._asm = new AcceptorStateMachine(fsm.states, 'validate');

  ALY.SequentialExecutor.call(this);
  this.emit = this.emitEvent;
}
```
- example usage
```shell
...
            params[key] = value;
          }
        }
      });
    }
  }

  var request = new ALY.Request(this, operation, params);
  this.addAllRequestListeners(request);

  if (callback) request.send(callback);
  return request;
},

/**
...
```

#### <a name="apidoc.element.aliyun-sdk.Response"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Response (request)](#apidoc.element.aliyun-sdk.Response)
- description and source-code
```javascript
function Response(request) {
  this.request = request;
  this.data = null;
  this.error = null;
  this.retryCount = 0;
  this.redirectCount = 0;
  this.httpResponse = new ALY.HttpResponse();
}
```
- example usage
```shell
...

  this.service = service;
  this.operation = operation;
  this.params = params || {};
  this.httpRequest = new ALY.HttpRequest(endpoint, region);
  this.startTime = ALY.util.date.getDate();

  this.response = new ALY.Response(this);
  this.restartCount = 0;
  this._asm = new AcceptorStateMachine(fsm.states, 'validate');

  ALY.SequentialExecutor.call(this);
  this.emit = this.emitEvent;
},
...
```

#### <a name="apidoc.element.aliyun-sdk.SLB"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>SLB ()](#apidoc.element.aliyun-sdk.SLB)
- description and source-code
```javascript
SLB = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>SLS ()](#apidoc.element.aliyun-sdk.SLS)
- description and source-code
```javascript
SLS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.STS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>STS ()](#apidoc.element.aliyun-sdk.STS)
- description and source-code
```javascript
STS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>SequentialExecutor ()](#apidoc.element.aliyun-sdk.SequentialExecutor)
- description and source-code
```javascript
function SequentialExecutor() {
  this.domain = domain && domain.active;
  this._events = {};
}
```
- example usage
```shell
...
require('./service_interface/top');

ALY.EventListeners = {
  Core: {}
};

ALY.EventListeners = {
  Core: new ALY.SequentialExecutor().addNamedListeners(function(add, addAsync) {

add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Service"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Service (config)](#apidoc.element.aliyun-sdk.Service)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.BatchCompute ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute)
- description and source-code
```javascript
Signers.BatchCompute = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.CMS ()](#apidoc.element.aliyun-sdk.Signers.CMS)
- description and source-code
```javascript
Signers.CMS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OSS ()](#apidoc.element.aliyun-sdk.Signers.OSS)
- description and source-code
```javascript
Signers.OSS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OTS ()](#apidoc.element.aliyun-sdk.Signers.OTS)
- description and source-code
```javascript
Signers.OTS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.OpenSearch ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch)
- description and source-code
```javascript
Signers.OpenSearch = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.POP"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.POP ()](#apidoc.element.aliyun-sdk.Signers.POP)
- description and source-code
```javascript
Signers.POP = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.RequestSigner"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.RequestSigner (request)](#apidoc.element.aliyun-sdk.Signers.RequestSigner)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.SLS ()](#apidoc.element.aliyun-sdk.Signers.SLS)
- description and source-code
```javascript
Signers.SLS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.TOP"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Signers.TOP ()](#apidoc.element.aliyun-sdk.Signers.TOP)
- description and source-code
```javascript
Signers.TOP = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Builder"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>XML.Builder (root, rules, options)](#apidoc.element.aliyun-sdk.XML.Builder)
- description and source-code
```javascript
function XMLBuilder(root, rules, options) {
  this.root = root;
  this.rules = rules;
  this.xmlns = options.xmlnamespace;
  this.timestampFormat = options.timestampFormat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>XML.Parser (rules)](#apidoc.element.aliyun-sdk.XML.Parser)
- description and source-code
```javascript
function XMLParser(rules) {
  this.rules = (rules || {}).members || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.YunDun"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>YunDun ()](#apidoc.element.aliyun-sdk.YunDun)
- description and source-code
```javascript
YunDun = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>util.Buffer (arg, encodingOrOffset, length)](#apidoc.element.aliyun-sdk.util.Buffer)
- description and source-code
```javascript
function Buffer(arg, encodingOrOffset, length) {
  // Common case.
  if (typeof arg === 'number') {
    if (typeof encodingOrOffset === 'string') {
      throw new Error(
        'If encoding is specified then the first argument must be a string'
      );
    }
    return Buffer.allocUnsafe(arg);
  }
  return Buffer.from(arg, encodingOrOffset, length);
}
```
- example usage
```shell
...
  progress(s);
});

add('HTTP_HEADERS', 'httpHeaders',
    function HTTP_HEADERS(statusCode, headers, resp) {
  resp.httpResponse.statusCode = statusCode;
  resp.httpResponse.headers = headers;
  resp.httpResponse.body = new ALY.util.Buffer('');
  resp.httpResponse.buffers = [];
  resp.httpResponse.numBytes = 0;
});

add('HTTP_DATA', 'httpData', function HTTP_DATA(chunk, resp) {
  if (chunk) {
    if (ALY.util.isNode()) {
...
```



# <a name="apidoc.module.aliyun-sdk.BatchCompute"></a>[module aliyun-sdk.BatchCompute](#apidoc.module.aliyun-sdk.BatchCompute)

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.BatchCompute"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>BatchCompute ()](#apidoc.element.aliyun-sdk.BatchCompute.BatchCompute)
- description and source-code
```javascript
BatchCompute = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.</span>__super__ (config)](#apidoc.element.aliyun-sdk.BatchCompute.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.BatchCompute.prototype"></a>[module aliyun-sdk.BatchCompute.prototype](#apidoc.module.aliyun-sdk.BatchCompute.prototype)

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.prototype.addContentType"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.addContentType)
- description and source-code
```javascript
addContentType = function (req){
    var httpRequest = req.httpRequest;
    var headers = httpRequest.headers;

    headers['x-acs-version'] = req.service.config.apiVersion;

    if(req.operation==='updateJobPriority'){
        httpRequest.body = JSON.parse(httpRequest.body).priority+'';
        headers['Content-Type'] = 'application/octet-stream';
        //headers['Content-Length']= httpRequest.body.length;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.BatchCompute.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.prototype.extractData"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>extractData (resp, operation)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.extractData)
- description and source-code
```javascript
function extractData(resp, operation) {

    resp.data = JSON.parse(resp.httpResponse.body.toString().trim() || '{}');

    var result = resp.data;
    delete result['RequestId'];


    var headers = resp.httpResponse.headers;
    var reqId = headers['x-acs-request-id'] || headers['request-id'];


    resp.data = {
        code: resp.httpResponse.statusCode,
        message: headers.status,
        headers: headers,
        requestId: reqId || ''
    };

    if(headers['x-acs-version']=='2015-06-30') {

        switch (operation) {
            case 'listJobs':
                resp.data.data = this.getFormatters().formatJobList(result);
                break;
            case 'getJob':
                resp.data.data = this.getFormatters().formatJob(result);
                break;
            case 'getJobDescription':
                resp.data.data = this.getFormatters().formatJobDescription(result);
                break;
            case 'listTasks':
                resp.data.data = this.getFormatters().formatTaskList(result);
                break;
            case 'listImages':
                resp.data.data = this.getFormatters().formatImageList(result);
                break;
            case 'createJob':
                resp.data.data = this.getFormatters().formatJob(result);
                break;
        }
    }
    else{
        resp.data.data = result;
    }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.prototype.extractError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.extractError)
- description and source-code
```javascript
function extractError(resp) {

    var headers = resp.httpResponse.headers;

    var body = resp.httpResponse.body;
    var error = body.toString();

    try {
        error = JSON.parse(error);
    } catch (e) {
        error = {};
    }

    resp.error = ALY.util.error(new Error(error.Message), {
        code: error.Code || error.ErrorCode,
        headers: headers,
        requestId: headers['x-acs-request-id'] || headers['request-id']
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.prototype.getFormatters"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>getFormatters ()](#apidoc.element.aliyun-sdk.BatchCompute.prototype.getFormatters)
- description and source-code
```javascript
getFormatters = function () {

    function getState(state) {
        switch (state) {
            case 0:
                return 'Init';
            case 1:
                return 'Waiting';
            case 2:
                return 'Running';
            case 3:
                return 'Finished';
            case 4:
                return 'Failed';
            case 5:
                return 'Stopped';
            default:
                return 'Unkowned';
        }
    }

    return {
        formatJob: function (v) {

            v['JobId'] = v['ResourceId'];
            v['JobName'] = v['Name'];
            v['CreationTime'] = v['CreateTime'];

            delete v['Name'];
            delete v['ResourceId'];
            delete v['CreateTime'];

            if (v['State'] == 'Terminated') v['State'] = 'Finished';

            return v;
        },
        formatJobList: function (data) {
            var that = this;
            var t = [];
            Object.keys(data).forEach(function (k) {
                t.push(that.formatJob(data[k]));
            });

            t.sort(function (a, b) {
                return a['JobId'] > b['JobId'] ? 1 : -1;
            });
            return t;
        },
        formatTaskList: function (data) {
<span class="apidocCodeCommentSpan">            /*{ CountTask:
             { EndTime: 1435520792,
             InstanceStatusVector: [Object],
             StartTime: 1435519721,
             State: 5,
             UnfinishedInstances: [Object] } },
             */
</span>            var t = [];
            Object.keys(data).forEach(function (k) {
                var v = data[k];
                v['TaskName'] = k;
                v['State'] = getState(v['State']);
                v['InstanceList'] = v['InstanceStatusVector'];

                delete v['InstanceStatusVector'];
                delete v['UnfinishedInstances'];

                if (v['InstanceList']) {
                    v['InstanceList'].forEach(function (n) {
                        n.State = getState(n.State);
                        delete n['WorkerStartTime'];
                        delete n['WorkerEndTime'];
                    });
                }
                t.push(data[k]);
            });

            //sort by StartTime, TaskName
            t.sort(function (a, b) {
                if (a['StartTime'] == 0) {
                    if (b['StartTime'] == 0) {
                        return a['TaskName'] > b['TaskName'] ? 1 : -1;
                    } else {
                        return -1;
                    }
                } else {
                    if (b['StartTime'] == 0) {
                        return -1;
                    } else {
                        return a['StartTime'] > b['StartTime'] ? 1 : -1;
                    }
                }
            });
            return t;
        },
        formatImageList: function (data) {
            var t = [];

            Object.keys(data).forEach(function (k) {
                var v = data[k];
                v['ImageId'] = k;
                v['ImageName'] = v['Name'];

                delete v['Name'];

                t.push(data[k]);
            });

            t.sort(function (a, b) {
                return a['ImageId'] > b['ImageId'] ? 1 : -1;
            });
            return t;
        },
        formatJobDescription: function (data) {
            var taskMap = data.TaskDag.TaskDescMap;
            Object.keys(taskMap).forEach(function (k) {
                var v = taskMap[k];
                delete v['BlockDeviceMapping'];
                delete v['CreateSnapshotAfterTerminated'];
                delete v['LoadImage'];
                delete v['SaveImage'];
                delete v['LoadPreparedData'];
                delete v['MaxReplica'];
                delete v['MinReplica'];
            });
            return data;
        }

    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.prototype.initialize"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.initialize)
- description and source-code
```javascript
function initialize(options) {
    ALY.Service.prototype.initialize.call(this, options);
}
```
- example usage
```shell
...
constructor: function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
...
```

#### <a name="apidoc.element.aliyun-sdk.BatchCompute.prototype.setupRequestListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.BatchCompute.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.BatchCompute.prototype.setupRequestListeners)
- description and source-code
```javascript
function setupRequestListeners(request) {

    var that = this;
    var svc = ALY.ServiceInterface.RestJson;

    request.addListener('build', this.addContentType);

    request.removeListener('extractData', svc.extractData);

    request.addListener('extractError', this.extractError);
    request.addListener('extractData', function (response) {
        that.extractData(response, request['operation']);
    });
}
```
- example usage
```shell
...
      ALY.EventListeners.Core.VALIDATE_PARAMETERS);
  }

  if (this.config.logger) { // add logging events
    request.addListeners(ALY.EventListeners.Logger);
  }

  this.setupRequestListeners(request);
},

/**
 * Override this method to setup any custom request listeners for each
 * new request to the service.
 *
 * @abstract
...
```



# <a name="apidoc.module.aliyun-sdk.CDN"></a>[module aliyun-sdk.CDN](#apidoc.module.aliyun-sdk.CDN)

#### <a name="apidoc.element.aliyun-sdk.CDN.CDN"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>CDN ()](#apidoc.element.aliyun-sdk.CDN.CDN)
- description and source-code
```javascript
CDN = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.CDN.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.CDN.</span>__super__ (config)](#apidoc.element.aliyun-sdk.CDN.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.CDN.prototype"></a>[module aliyun-sdk.CDN.prototype](#apidoc.module.aliyun-sdk.CDN.prototype)

#### <a name="apidoc.element.aliyun-sdk.CDN.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.CDN.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.CDN.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.CMS"></a>[module aliyun-sdk.CMS](#apidoc.module.aliyun-sdk.CMS)

#### <a name="apidoc.element.aliyun-sdk.CMS.CMS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>CMS ()](#apidoc.element.aliyun-sdk.CMS.CMS)
- description and source-code
```javascript
CMS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.CMS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.CMS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.CMS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.CMS.prototype"></a>[module aliyun-sdk.CMS.prototype](#apidoc.module.aliyun-sdk.CMS.prototype)

#### <a name="apidoc.element.aliyun-sdk.CMS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.CMS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.CMS.prototype.extractData"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.CMS.prototype.extractData)
- description and source-code
```javascript
function extractData(resp) {

    if(process.env.DEBUG == 'aliyun') {
        console.log("-------response status-------");
        console.log(resp.httpResponse.statusCode);

        console.log("-------response header-------");
        console.log(resp.httpResponse.headers);

        console.log("-------response body-------");
        console.log(resp.httpResponse.body.toString());
        console.log("-------response end-------");
    }


    resp.data = JSON.parse(resp.httpResponse.body.toString().trim() || '{}');

    var result = resp.data;
    //delete result['RequestId'];

    //var reqId = resp.httpResponse.headers['request-id'];

    resp.data = {
        code: resp.httpResponse.statusCode,
        //message: resp.httpResponse.headers.status,
        headers: resp.httpResponse.headers
    };

    resp.data.data = result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.CMS.prototype.extractError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.CMS.prototype.extractError)
- description and source-code
```javascript
function extractError(resp) {
    if(process.env.DEBUG == 'aliyun') {
        console.log("-------response status-------");
        console.log(resp.httpResponse.statusCode);

        console.log("-------response header-------");
        console.log(resp.httpResponse.headers);

        console.log("-------response error-------");
        console.log(resp.httpResponse.body.toString());
        console.log("-------response end-------");
    }

    var headers = resp.httpResponse.headers;

    var error = resp.httpResponse.body.toString();

    try {
        error = JSON.parse(error);
    } catch (e) {
        error = {};
    }


    resp.error = ALY.util.error(new Error(), {
        code: error.Code,
        headers: headers
        //requestId: headers['request-id']
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.CMS.prototype.initialize"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.CMS.prototype.initialize)
- description and source-code
```javascript
function initialize(options) {
    ALY.Service.prototype.initialize.call(this, options);
}
```
- example usage
```shell
...
constructor: function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
...
```

#### <a name="apidoc.element.aliyun-sdk.CMS.prototype.setupRequestListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.CMS.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.CMS.prototype.setupRequestListeners)
- description and source-code
```javascript
function setupRequestListeners(request) {

    //request.addListener('build', this.addContentType);
    request.addListener('extractError', this.extractError);
    request.addListener('extractData', this.extractData);
}
```
- example usage
```shell
...
      ALY.EventListeners.Core.VALIDATE_PARAMETERS);
  }

  if (this.config.logger) { // add logging events
    request.addListeners(ALY.EventListeners.Logger);
  }

  this.setupRequestListeners(request);
},

/**
 * Override this method to setup any custom request listeners for each
 * new request to the service.
 *
 * @abstract
...
```



# <a name="apidoc.module.aliyun-sdk.Config"></a>[module aliyun-sdk.Config](#apidoc.module.aliyun-sdk.Config)

#### <a name="apidoc.element.aliyun-sdk.Config.Config"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Config (options)](#apidoc.element.aliyun-sdk.Config.Config)
- description and source-code
```javascript
function Config(options) {
  if (options === undefined) options = {};

  ALY.util.each.call(this, this.keys, function (key, value) {
    this.set(key, options[key], value);
  });
}
```
- example usage
```shell
...
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
},

/**
 * @api private
 */
loadServiceClass: function loadServiceClass(serviceConfig) {
  if (!ALY.util.isEmpty(this.api)) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Config.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Config.</span>__super__ ()](#apidoc.element.aliyun-sdk.Config.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Config.prototype"></a>[module aliyun-sdk.Config.prototype](#apidoc.module.aliyun-sdk.Config.prototype)

#### <a name="apidoc.element.aliyun-sdk.Config.prototype.clear"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>clear ()](#apidoc.element.aliyun-sdk.Config.prototype.clear)
- description and source-code
```javascript
function clear() {
<span class="apidocCodeCommentSpan">  /*jshint forin:false */
</span>  ALY.util.each.call(this, this.keys, function (key) {
    delete this[key];
  });

  // reset credential provider
  this.set('credentials', undefined);
  this.set('credentialProvider', undefined);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Config.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>constructor (options)](#apidoc.element.aliyun-sdk.Config.prototype.constructor)
- description and source-code
```javascript
function Config(options) {
  if (options === undefined) options = {};

  ALY.util.each.call(this, this.keys, function (key, value) {
    this.set(key, options[key], value);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Config.prototype.getCredentials"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>getCredentials ()](#apidoc.element.aliyun-sdk.Config.prototype.getCredentials)
- description and source-code
```javascript
function getCredentials() {
  return {
    accessKeyId: this.accessKeyId,
    secretAccessKey: this.secretAccessKey,
    securityToken: this.securityToken
  };
}
```
- example usage
```shell
...
    add('SET_HTTP_HOST', 'afterBuild', function SET_HTTP_HOST(req) {
      req.httpRequest.headers['Host'] = req.httpRequest.endpoint.host;
    });

    addAsync('SIGN', 'sign', function SIGN(req, done) {
      if (!req.service.api.signatureVersion) return done(); // none

      var credentials = req.service.config.getCredentials();

      try {
var date = ALY.util.date.getDate();
var SignerClass = req.service.getSignerClass(req);
var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

// add new authorization
...
```

#### <a name="apidoc.element.aliyun-sdk.Config.prototype.set"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Config.prototype.</span>set (property, value, defaultValue)](#apidoc.element.aliyun-sdk.Config.prototype.set)
- description and source-code
```javascript
function set(property, value, defaultValue) {
  if (value === undefined) {
    if (defaultValue === undefined) {
      defaultValue = this.keys[property];
    }
    if (typeof defaultValue === 'function') {
      this[property] = defaultValue.call(this);
    } else {
      this[property] = defaultValue;
    }
  } else {
    this[property] = value;
  }
}
```
- example usage
```shell
...

ALY.Config = ALY.util.inherit({

constructor: function Config(options) {
  if (options === undefined) options = {};

  ALY.util.each.call(this, this.keys, function (key, value) {
    this.set(key, options[key], value);
  });
},

clear: function clear() {
  /*jshint forin:false */
  ALY.util.each.call(this, this.keys, function (key) {
    delete this[key];
...
```



# <a name="apidoc.module.aliyun-sdk.DAYU"></a>[module aliyun-sdk.DAYU](#apidoc.module.aliyun-sdk.DAYU)

#### <a name="apidoc.element.aliyun-sdk.DAYU.DAYU"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>DAYU ()](#apidoc.element.aliyun-sdk.DAYU.DAYU)
- description and source-code
```javascript
DAYU = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.DAYU.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.DAYU.</span>__super__ (config)](#apidoc.element.aliyun-sdk.DAYU.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.DAYU.prototype"></a>[module aliyun-sdk.DAYU.prototype](#apidoc.module.aliyun-sdk.DAYU.prototype)

#### <a name="apidoc.element.aliyun-sdk.DAYU.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.DAYU.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.DAYU.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.DRDS"></a>[module aliyun-sdk.DRDS](#apidoc.module.aliyun-sdk.DRDS)

#### <a name="apidoc.element.aliyun-sdk.DRDS.DRDS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>DRDS ()](#apidoc.element.aliyun-sdk.DRDS.DRDS)
- description and source-code
```javascript
DRDS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.DRDS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.DRDS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.DRDS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.DRDS.prototype"></a>[module aliyun-sdk.DRDS.prototype](#apidoc.module.aliyun-sdk.DRDS.prototype)

#### <a name="apidoc.element.aliyun-sdk.DRDS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.DRDS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.DRDS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.ECS"></a>[module aliyun-sdk.ECS](#apidoc.module.aliyun-sdk.ECS)

#### <a name="apidoc.element.aliyun-sdk.ECS.ECS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>ECS ()](#apidoc.element.aliyun-sdk.ECS.ECS)
- description and source-code
```javascript
ECS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.ECS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ECS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.ECS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.ECS.prototype"></a>[module aliyun-sdk.ECS.prototype](#apidoc.module.aliyun-sdk.ECS.prototype)

#### <a name="apidoc.element.aliyun-sdk.ECS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ECS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.ECS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.ESS"></a>[module aliyun-sdk.ESS](#apidoc.module.aliyun-sdk.ESS)

#### <a name="apidoc.element.aliyun-sdk.ESS.ESS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>ESS ()](#apidoc.element.aliyun-sdk.ESS.ESS)
- description and source-code
```javascript
ESS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.ESS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ESS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.ESS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.ESS.prototype"></a>[module aliyun-sdk.ESS.prototype](#apidoc.module.aliyun-sdk.ESS.prototype)

#### <a name="apidoc.element.aliyun-sdk.ESS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ESS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.ESS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Endpoint"></a>[module aliyun-sdk.Endpoint](#apidoc.module.aliyun-sdk.Endpoint)

#### <a name="apidoc.element.aliyun-sdk.Endpoint.Endpoint"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Endpoint (endpoint)](#apidoc.element.aliyun-sdk.Endpoint.Endpoint)
- description and source-code
```javascript
function Endpoint(endpoint) {
  ALY.util.hideProperties(this, ['slashes', 'auth', 'hash', 'search', 'query']);

  if (typeof endpoint === 'undefined' || endpoint === null) {
    throw new Error('Invalid endpoint: ' + endpoint);
  }

  if (!endpoint.match(/^http/)) {
    throw new Error('错误的 endpoint 格式, 需要以 http 或者 https 开头');
  }

  ALY.util.update(this, ALY.util.urlParse(endpoint));

  // Ensure the port property is set as an integer
  if (this.port) {
    this.port = parseInt(this.port, 10);
  } else {
    this.port = this.protocol === 'https:' ? 443 : 80;
  }
}
```
- example usage
```shell
...
   * @param service [ALY.Service] the service to perform the operation on
   * @param operation [String] the operation to perform on the service
   * @param params [Object] parameters to send to the operation.
   *   See the operation's documentation for the format of the
   *   parameters.
   */
  constructor: function Request(service, operation, params) {
var endpoint = new ALY.Endpoint(service.config.endpoint);
var region = service.config.region;

this.service = service;
this.operation = operation;
this.params = params || {};
this.httpRequest = new ALY.HttpRequest(endpoint, region);
this.startTime = ALY.util.date.getDate();
...
```

#### <a name="apidoc.element.aliyun-sdk.Endpoint.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Endpoint.</span>__super__ ()](#apidoc.element.aliyun-sdk.Endpoint.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Endpoint.prototype"></a>[module aliyun-sdk.Endpoint.prototype](#apidoc.module.aliyun-sdk.Endpoint.prototype)

#### <a name="apidoc.element.aliyun-sdk.Endpoint.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Endpoint.prototype.</span>constructor (endpoint)](#apidoc.element.aliyun-sdk.Endpoint.prototype.constructor)
- description and source-code
```javascript
function Endpoint(endpoint) {
  ALY.util.hideProperties(this, ['slashes', 'auth', 'hash', 'search', 'query']);

  if (typeof endpoint === 'undefined' || endpoint === null) {
    throw new Error('Invalid endpoint: ' + endpoint);
  }

  if (!endpoint.match(/^http/)) {
    throw new Error('错误的 endpoint 格式, 需要以 http 或者 https 开头');
  }

  ALY.util.update(this, ALY.util.urlParse(endpoint));

  // Ensure the port property is set as an integer
  if (this.port) {
    this.port = parseInt(this.port, 10);
  } else {
    this.port = this.protocol === 'https:' ? 443 : 80;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.GREEN"></a>[module aliyun-sdk.GREEN](#apidoc.module.aliyun-sdk.GREEN)

#### <a name="apidoc.element.aliyun-sdk.GREEN.GREEN"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>GREEN ()](#apidoc.element.aliyun-sdk.GREEN.GREEN)
- description and source-code
```javascript
GREEN = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.GREEN.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.GREEN.</span>__super__ (config)](#apidoc.element.aliyun-sdk.GREEN.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.GREEN.prototype"></a>[module aliyun-sdk.GREEN.prototype](#apidoc.module.aliyun-sdk.GREEN.prototype)

#### <a name="apidoc.element.aliyun-sdk.GREEN.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.GREEN.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.GREEN.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.HttpClient"></a>[module aliyun-sdk.HttpClient](#apidoc.module.aliyun-sdk.HttpClient)

#### <a name="apidoc.element.aliyun-sdk.HttpClient.HttpClient"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpClient ()](#apidoc.element.aliyun-sdk.HttpClient.HttpClient)
- description and source-code
```javascript
HttpClient = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpClient.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.</span>__super__ ()](#apidoc.element.aliyun-sdk.HttpClient.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpClient.getInstance"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.</span>getInstance ()](#apidoc.element.aliyun-sdk.HttpClient.getInstance)
- description and source-code
```javascript
function getInstance() {
<span class="apidocCodeCommentSpan">  /*jshint newcap:false */
</span>  if (this.singleton === undefined) {
    this.singleton = new this();
  }
  return this.singleton;
}
```
- example usage
```shell
...
      done();
    });
  }

  resp.error = null;
  resp.data = null;

  var http = ALY.HttpClient.getInstance();
  var httpOptions = resp.request.service.config.httpOptions || {};
  this.httpRequest.debug();
  var s = http.handleRequest(this.httpRequest, httpOptions, callback, error);
  progress(s);
});

add('HTTP_HEADERS', 'httpHeaders',
...
```



# <a name="apidoc.module.aliyun-sdk.HttpClient.prototype"></a>[module aliyun-sdk.HttpClient.prototype](#apidoc.module.aliyun-sdk.HttpClient.prototype)

#### <a name="apidoc.element.aliyun-sdk.HttpClient.prototype.bufferToStream"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>bufferToStream (buffer)](#apidoc.element.aliyun-sdk.HttpClient.prototype.bufferToStream)
- description and source-code
```javascript
function bufferToStream(buffer) {
  if (!ALY.util.Buffer.isBuffer(buffer)) buffer = new ALY.util.Buffer(buffer);

  var readable = new ReadableStream();
  var pos = 0;
  readable._read = function(size) {
    if (pos >= buffer.length) return readable.push(null);

    var end = pos + size;
    if (end > buffer.length) end = buffer.length;
    readable.push(buffer.slice(pos, end));
    pos = end;
  };

  return readable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpClient.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.HttpClient.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpClient.prototype.handleRequest"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>handleRequest (httpRequest, httpOptions, callback, errCallback)](#apidoc.element.aliyun-sdk.HttpClient.prototype.handleRequest)
- description and source-code
```javascript
function handleRequest(httpRequest, httpOptions, callback, errCallback) {
  var endpoint = httpRequest.endpoint;
  var pathPrefix = '';
  if (!httpOptions) httpOptions = {};

  var useSSL = endpoint.protocol === 'https:';
  var http = useSSL ? require('https') : require('http');
  var options = {
    host: endpoint.hostname,
    port: endpoint.port,
    method: httpRequest.method,
    headers: httpRequest.headers,
    path: pathPrefix + httpRequest.path
  };

  if (useSSL && !httpOptions.agent) {
    options.agent = this.sslAgent();
  }

  ALY.util.update(options, httpOptions);
  delete options.proxy; // proxy isn't an HTTP option
  delete options.timeout; // timeout isn't an HTTP option

  var stream = http.request(options, function (httpResp) {
    callback(httpResp);
    httpResp.emit('headers', httpResp.statusCode, httpResp.headers);
  });
  httpRequest.stream = stream; // attach stream to httpRequest

  // timeout support
  stream.setTimeout(httpOptions.timeout || 0);
  stream.once('timeout', function() {
    var msg = 'Connection timed out after ' + httpOptions.timeout + 'ms';
    errCallback(ALY.util.error(new Error(msg), {code: 'TimeoutError'}));

    // HACK - abort the connection without tripping our error handler
    // since we already raised our TimeoutError. Otherwise the connection
    // comes back with ECONNRESET, which is not a helpful error message
    stream.removeListener('error', errCallback);
    stream.on('error', function() { });
    stream.abort();
  });

  stream.on('error', errCallback);
  this.writeBody(stream, httpRequest);
  return stream;
}
```
- example usage
```shell
...

  resp.error = null;
  resp.data = null;

  var http = ALY.HttpClient.getInstance();
  var httpOptions = resp.request.service.config.httpOptions || {};
  this.httpRequest.debug();
  var s = http.handleRequest(this.httpRequest, httpOptions, callback, error);
  progress(s);
});

add('HTTP_HEADERS', 'httpHeaders',
    function HTTP_HEADERS(statusCode, headers, resp) {
  resp.httpResponse.statusCode = statusCode;
  resp.httpResponse.headers = headers;
...
```

#### <a name="apidoc.element.aliyun-sdk.HttpClient.prototype.progressStream"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>progressStream (stream, httpRequest)](#apidoc.element.aliyun-sdk.HttpClient.prototype.progressStream)
- description and source-code
```javascript
function progressStream(stream, httpRequest) {
  var numBytes = 0;
  var totalBytes = httpRequest.headers['Content-Length'];
  var writer = new WritableStream();
  writer._write = function(chunk, encoding, callback) {
    if (chunk) {
      numBytes += chunk.length;
      stream.emit('sendProgress', {
        loaded: numBytes, total: totalBytes
      });
    }
    callback();
  };
  return writer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpClient.prototype.sslAgent"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>sslAgent ()](#apidoc.element.aliyun-sdk.HttpClient.prototype.sslAgent)
- description and source-code
```javascript
function sslAgent() {
  var https = require('https');

  if (!ALY.NodeHttpClient.sslAgent) {
    ALY.NodeHttpClient.sslAgent = new https.Agent({rejectUnauthorized: true});
    ALY.NodeHttpClient.sslAgent.setMaxListeners(0);

    // delegate maxSockets to globalAgent
    Object.defineProperty(ALY.NodeHttpClient.sslAgent, 'maxSockets', {
      enumerable: true,
      get: function() { return https.globalAgent.maxSockets; }
    });
  }
  return ALY.NodeHttpClient.sslAgent;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpClient.prototype.writeBody"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpClient.prototype.</span>writeBody (stream, httpRequest)](#apidoc.element.aliyun-sdk.HttpClient.prototype.writeBody)
- description and source-code
```javascript
function writeBody(stream, httpRequest) {
  var body = httpRequest.body;

  if (body && WritableStream && ReadableStream) { // progress support
    if (!(body instanceof Stream)) body = this.bufferToStream(body);
    body.pipe(this.progressStream(stream, httpRequest));
  }

  if (body instanceof Stream) {
    body.pipe(stream);
  } else if (body) {
    stream.end(body);
  } else {
    stream.end();
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.HttpRequest"></a>[module aliyun-sdk.HttpRequest](#apidoc.module.aliyun-sdk.HttpRequest)

#### <a name="apidoc.element.aliyun-sdk.HttpRequest.HttpRequest"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpRequest (endpoint, region)](#apidoc.element.aliyun-sdk.HttpRequest.HttpRequest)
- description and source-code
```javascript
function HttpRequest(endpoint, region) {
  this.method = 'POST';
  this.path = endpoint.path || '/';
  this.headers = {};
  this.body = '';
  this.endpoint = endpoint;
  this.region = region;
  this.setUserAgent();
}
```
- example usage
```shell
...
  constructor: function Request(service, operation, params) {
var endpoint = new ALY.Endpoint(service.config.endpoint);
var region = service.config.region;

this.service = service;
this.operation = operation;
this.params = params || {};
this.httpRequest = new ALY.HttpRequest(endpoint, region);
this.startTime = ALY.util.date.getDate();

this.response = new ALY.Response(this);
this.restartCount = 0;
this._asm = new AcceptorStateMachine(fsm.states, 'validate');

ALY.SequentialExecutor.call(this);
...
```

#### <a name="apidoc.element.aliyun-sdk.HttpRequest.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.</span>__super__ ()](#apidoc.element.aliyun-sdk.HttpRequest.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.HttpRequest.prototype"></a>[module aliyun-sdk.HttpRequest.prototype](#apidoc.module.aliyun-sdk.HttpRequest.prototype)

#### <a name="apidoc.element.aliyun-sdk.HttpRequest.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>constructor (endpoint, region)](#apidoc.element.aliyun-sdk.HttpRequest.prototype.constructor)
- description and source-code
```javascript
function HttpRequest(endpoint, region) {
  this.method = 'POST';
  this.path = endpoint.path || '/';
  this.headers = {};
  this.body = '';
  this.endpoint = endpoint;
  this.region = region;
  this.setUserAgent();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpRequest.prototype.debug"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>debug ()](#apidoc.element.aliyun-sdk.HttpRequest.prototype.debug)
- description and source-code
```javascript
debug = function () {
  if(process.env.DEBUG == 'aliyun') {
    console.log('-------- HttpRequest Start: --------');
    console.log('method:', this.method);
    console.log('path:', this.path);
    console.log('headers:');
    for(var i in this.headers) {
      if (i == 'constructor')
        continue;
      console.log(i, ':', this.headers[i]);
    };
  }
}
```
- example usage
```shell
...
  }

  resp.error = null;
  resp.data = null;

  var http = ALY.HttpClient.getInstance();
  var httpOptions = resp.request.service.config.httpOptions || {};
  this.httpRequest.debug();
  var s = http.handleRequest(this.httpRequest, httpOptions, callback, error);
  progress(s);
});

add('HTTP_HEADERS', 'httpHeaders',
    function HTTP_HEADERS(statusCode, headers, resp) {
  resp.httpResponse.statusCode = statusCode;
...
```

#### <a name="apidoc.element.aliyun-sdk.HttpRequest.prototype.pathname"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>pathname ()](#apidoc.element.aliyun-sdk.HttpRequest.prototype.pathname)
- description and source-code
```javascript
function pathname() {
  return this.path.split('?', 1)[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpRequest.prototype.search"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>search ()](#apidoc.element.aliyun-sdk.HttpRequest.prototype.search)
- description and source-code
```javascript
function search() {
  return this.path.split('?', 2)[1] || '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.HttpRequest.prototype.setUserAgent"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpRequest.prototype.</span>setUserAgent ()](#apidoc.element.aliyun-sdk.HttpRequest.prototype.setUserAgent)
- description and source-code
```javascript
function setUserAgent() {
  //var prefix = ALY.util.isBrowser() ? 'X-Aly-' : '';
  //this.headers[prefix + 'User-Agent'] = ALY.util.userAgent();
  //this.headers['x-sdk-client'] = this.headers['User-Agent'] = ALY.util.userAgent();
  // pop 现在不支持 x-sdk-client 在浏览器设置
  this.headers['User-Agent'] = ALY.util.userAgent();
}
```
- example usage
```shell
...
constructor: function HttpRequest(endpoint, region) {
  this.method = 'POST';
  this.path = endpoint.path || '/';
  this.headers = {};
  this.body = '';
  this.endpoint = endpoint;
  this.region = region;
  this.setUserAgent();
},

setUserAgent: function setUserAgent() {
  //var prefix = ALY.util.isBrowser() ? 'X-Aly-' : '';
  //this.headers[prefix + 'User-Agent'] = ALY.util.userAgent();
  //this.headers['x-sdk-client'] = this.headers['User-Agent'] = ALY.util.userAgent();
  // pop 现在不支持 x-sdk-client 在浏览器设置
...
```



# <a name="apidoc.module.aliyun-sdk.HttpResponse"></a>[module aliyun-sdk.HttpResponse](#apidoc.module.aliyun-sdk.HttpResponse)

#### <a name="apidoc.element.aliyun-sdk.HttpResponse.HttpResponse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>HttpResponse ()](#apidoc.element.aliyun-sdk.HttpResponse.HttpResponse)
- description and source-code
```javascript
function HttpResponse() {
  this.statusCode = undefined;
  this.headers = {};
  this.body = undefined;
}
```
- example usage
```shell
...
 */
constructor: function Response(request) {
  this.request = request;
  this.data = null;
  this.error = null;
  this.retryCount = 0;
  this.redirectCount = 0;
  this.httpResponse = new ALY.HttpResponse();
},

nextPage: function nextPage(callback) {
  var config;
  var service = this.request.service;
  var operation = this.request.operation;
  try {
...
```

#### <a name="apidoc.element.aliyun-sdk.HttpResponse.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpResponse.</span>__super__ ()](#apidoc.element.aliyun-sdk.HttpResponse.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.HttpResponse.prototype"></a>[module aliyun-sdk.HttpResponse.prototype](#apidoc.module.aliyun-sdk.HttpResponse.prototype)

#### <a name="apidoc.element.aliyun-sdk.HttpResponse.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.HttpResponse.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.HttpResponse.prototype.constructor)
- description and source-code
```javascript
function HttpResponse() {
  this.statusCode = undefined;
  this.headers = {};
  this.body = undefined;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.JAQ"></a>[module aliyun-sdk.JAQ](#apidoc.module.aliyun-sdk.JAQ)

#### <a name="apidoc.element.aliyun-sdk.JAQ.JAQ"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>JAQ ()](#apidoc.element.aliyun-sdk.JAQ.JAQ)
- description and source-code
```javascript
JAQ = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.JAQ.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.JAQ.</span>__super__ (config)](#apidoc.element.aliyun-sdk.JAQ.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.JAQ.prototype"></a>[module aliyun-sdk.JAQ.prototype](#apidoc.module.aliyun-sdk.JAQ.prototype)

#### <a name="apidoc.element.aliyun-sdk.JAQ.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.JAQ.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.JAQ.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.JSON"></a>[module aliyun-sdk.JSON](#apidoc.module.aliyun-sdk.JSON)

#### <a name="apidoc.element.aliyun-sdk.JSON.Builder"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.JSON.</span>Builder (rules, options)](#apidoc.element.aliyun-sdk.JSON.Builder)
- description and source-code
```javascript
function JSONBuilder(rules, options) {
  this.rules = rules;
  this.timestampFormat = options.timestampFormat;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.JSON.Builder"></a>[module aliyun-sdk.JSON.Builder](#apidoc.module.aliyun-sdk.JSON.Builder)

#### <a name="apidoc.element.aliyun-sdk.JSON.Builder.Builder"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.JSON.</span>Builder (rules, options)](#apidoc.element.aliyun-sdk.JSON.Builder.Builder)
- description and source-code
```javascript
function JSONBuilder(rules, options) {
  this.rules = rules;
  this.timestampFormat = options.timestampFormat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.JSON.Builder.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.JSON.Builder.</span>__super__ ()](#apidoc.element.aliyun-sdk.JSON.Builder.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.JSON.Builder.prototype"></a>[module aliyun-sdk.JSON.Builder.prototype](#apidoc.module.aliyun-sdk.JSON.Builder.prototype)

#### <a name="apidoc.element.aliyun-sdk.JSON.Builder.prototype.build"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.JSON.Builder.prototype.</span>build (params)](#apidoc.element.aliyun-sdk.JSON.Builder.prototype.build)
- description and source-code
```javascript
function build(params) {
  return JSON.stringify(this.translate(this.rules, params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.JSON.Builder.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.JSON.Builder.prototype.</span>constructor (rules, options)](#apidoc.element.aliyun-sdk.JSON.Builder.prototype.constructor)
- description and source-code
```javascript
function JSONBuilder(rules, options) {
  this.rules = rules;
  this.timestampFormat = options.timestampFormat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.JSON.Builder.prototype.translate"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.JSON.Builder.prototype.</span>translate (rules, value)](#apidoc.element.aliyun-sdk.JSON.Builder.prototype.translate)
- description and source-code
```javascript
function translate(rules, value) {
  if (value === null || value === undefined) return undefined;

  if (rules.type == 'structure') {

    // translate structures (hashes with pre-defined keys)
    var struct = {};
    ALY.util.each.call(this, value, function (memberName, memberValue) {
      var memberRules = rules.members[memberName] || {};
      var result = this.translate(memberRules, memberValue);
      if (result !== undefined) struct[memberName] = result;
    });
    return struct;

  } else if (rules.type == 'list') {

    // translate each member of the list
    var list = [];
    ALY.util.arrayEach.call(this, value, function (memberValue) {
      var memberRules = rules.members || {};
      var result = this.translate(memberRules, memberValue);
      if (result !== undefined) list.push(result);
    });
    return list;

  } else if (rules.type == 'map') {

    // translate maps (hashes with user supplied keys)
    var map = {};
    ALY.util.each.call(this, value, function (memberName, memberValue) {
      var memberRules = rules.members || {};
      var result = this.translate(memberRules, memberValue);
      if (result !== undefined) map[memberName] = result;
    });
    return map;

  } else if (rules.type == 'timestamp') {

    var timestampFormat = rules.format || this.timestampFormat;
    return ALY.util.date.format(value, timestampFormat);

  } else if (rules.type == 'integer') {
    return parseInt(value, 10);
  } else if (rules.type == 'float') {
    return parseFloat(value);
  } else {

    // all other shapes
    return value;

  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.MEMCACHED"></a>[module aliyun-sdk.MEMCACHED](#apidoc.module.aliyun-sdk.MEMCACHED)

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>MemcachedClient (stream, options)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient)
- description and source-code
```javascript
function MemcachedClient(stream, options) {
  this.stream = stream;
  this.options = options = options || {};

  this.connection_id = ++connection_id;
  this.connected = false;
  this.ready = false;
  this.should_buffer = false;
  this.command_queue_high_water = this.options.command_queue_high_water || 1000;
  this.command_queue_low_water = this.options.command_queue_low_water || 0;
  this.command_queue = new Queue(); // holds sent commands to de-pipeline them
  this.offline_queue = new Queue(); // holds commands issued but not able to be sent
  options.expires = 0;
  this.enable_offline_queue = true;
  if (typeof this.options.enable_offline_queue === "boolean") {
    this.enable_offline_queue = this.options.enable_offline_queue;
  }

  this.initialize_retry_vars();

  this.closing = false;
  this.auth_username = null;
  if (options.username !== undefined) {
    this.auth_username = options.username;
  }
  this.auth_pass = null;
  if (options.password !== undefined) {
    this.auth_pass = options.password;
  }
  this.parser_module = null;

  var self = this;

  this.stream.on("connect", function () {
    debug('event: connect');
    self.on_connect();
  });

  this.stream.on("data", function (buffer_from_socket) {
    self.on_data(buffer_from_socket);
  });

  this.stream.on("error", function (msg) {
    self.on_error(msg.message);
  });

  this.stream.on("close", function () {
    self.connection_gone("close");
  });

  this.stream.on("end", function () {
    self.connection_gone("end");
  });

  this.stream.on("drain", function () {
    self.should_buffer = false;
    self.emit("drain");
  });

  events.EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.createClient"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>createClient (port_arg, host_arg, options)](#apidoc.element.aliyun-sdk.MEMCACHED.createClient)
- description and source-code
```javascript
createClient = function (port_arg, host_arg, options) {
  var port = port_arg || default_port,
    host = host_arg || default_host,
    memcached_client, net_client;

  net_client = net.createConnection(port, host);

  memcached_client = new MemcachedClient(net_client, options);

  memcached_client.port = port;
  memcached_client.host = host;

  return memcached_client;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.createClientFromString"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>createClientFromString (s)](#apidoc.element.aliyun-sdk.MEMCACHED.createClientFromString)
- description and source-code
```javascript
createClientFromString = function (s) {

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.MEMCACHED.MemcachedClient"></a>[module aliyun-sdk.MEMCACHED.MemcachedClient](#apidoc.module.aliyun-sdk.MEMCACHED.MemcachedClient)

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.MemcachedClient"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.</span>MemcachedClient (stream, options)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.MemcachedClient)
- description and source-code
```javascript
function MemcachedClient(stream, options) {
  this.stream = stream;
  this.options = options = options || {};

  this.connection_id = ++connection_id;
  this.connected = false;
  this.ready = false;
  this.should_buffer = false;
  this.command_queue_high_water = this.options.command_queue_high_water || 1000;
  this.command_queue_low_water = this.options.command_queue_low_water || 0;
  this.command_queue = new Queue(); // holds sent commands to de-pipeline them
  this.offline_queue = new Queue(); // holds commands issued but not able to be sent
  options.expires = 0;
  this.enable_offline_queue = true;
  if (typeof this.options.enable_offline_queue === "boolean") {
    this.enable_offline_queue = this.options.enable_offline_queue;
  }

  this.initialize_retry_vars();

  this.closing = false;
  this.auth_username = null;
  if (options.username !== undefined) {
    this.auth_username = options.username;
  }
  this.auth_pass = null;
  if (options.password !== undefined) {
    this.auth_pass = options.password;
  }
  this.parser_module = null;

  var self = this;

  this.stream.on("connect", function () {
    debug('event: connect');
    self.on_connect();
  });

  this.stream.on("data", function (buffer_from_socket) {
    self.on_data(buffer_from_socket);
  });

  this.stream.on("error", function (msg) {
    self.on_error(msg.message);
  });

  this.stream.on("close", function () {
    self.connection_gone("close");
  });

  this.stream.on("end", function () {
    self.connection_gone("end");
  });

  this.stream.on("drain", function () {
    self.should_buffer = false;
    self.emit("drain");
  });

  events.EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.super_"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.</span>super_ ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.MEMCACHED.MemcachedClient.prototype"></a>[module aliyun-sdk.MEMCACHED.MemcachedClient.prototype](#apidoc.module.aliyun-sdk.MEMCACHED.MemcachedClient.prototype)

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.ADD"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>ADD (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.ADD)
- description and source-code
```javascript
ADD = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.APPEND"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>APPEND (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.APPEND)
- description and source-code
```javascript
APPEND = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.AUTH"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>AUTH (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.AUTH)
- description and source-code
```javascript
AUTH = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.DECREMENT"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>DECREMENT (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.DECREMENT)
- description and source-code
```javascript
DECREMENT = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.DELETE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>DELETE (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.DELETE)
- description and source-code
```javascript
DELETE = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.GET"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>GET (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.GET)
- description and source-code
```javascript
GET = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.INCREMENT"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>INCREMENT (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.INCREMENT)
- description and source-code
```javascript
INCREMENT = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.NOOP"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>NOOP (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.NOOP)
- description and source-code
```javascript
NOOP = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.PREPEND"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>PREPEND (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.PREPEND)
- description and source-code
```javascript
PREPEND = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.QUIT"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>QUIT (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.QUIT)
- description and source-code
```javascript
QUIT = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.REPLACE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>REPLACE (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.REPLACE)
- description and source-code
```javascript
REPLACE = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.SET"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>SET (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.SET)
- description and source-code
```javascript
SET = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.VERSION"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>VERSION (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.VERSION)
- description and source-code
```javascript
VERSION = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.add"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>add (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.add)
- description and source-code
```javascript
add = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.append"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>append (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.append)
- description and source-code
```javascript
append = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.auth"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>auth (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.auth)
- description and source-code
```javascript
auth = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.connection_gone"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>connection_gone (why)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.connection_gone)
- description and source-code
```javascript
connection_gone = function (why) {
  var self = this;

  // If a retry is already in progress, just let that happen
  if (this.retry_timer) {
    return;
  }

  debug("Memcached connection is gone from " + why + " event.");
  this.connected = false;
  this.ready = false;

  // since we are collapsing end and close, users don't expect to be called twice
  if (!this.emitted_end) {
    this.emit("end");
    this.emitted_end = true;
  }

  this.flush_and_error("Memcached connection gone from " + why + " event.");

  // If this is a requested shutdown, then don't retry
  if (this.closing) {
    this.retry_timer = null;
    debug("connection ended from quit command, not retrying.");
    return;
  }

  var nextDelay = Math.floor(this.retry_delay * this.retry_backoff);
  if (nextDelay > this.retry_max_delay) {
    this.retry_delay = this.retry_max_delay;
  }
  else {
    this.retry_delay = nextDelay;
  }

  debug("Retry connection in " + this.retry_delay + " ms");

  this.attempts += 1;
  this.emit("reconnecting", {
    delay: self.retry_delay,
    attempt: self.attempts
  });
  this.retry_timer = setTimeout(function () {
    debug("Retrying connection...");

    self.stream.connect(self.port, self.host);
    self.retry_timer = null;
  }, this.retry_delay);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.decrement"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>decrement (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.decrement)
- description and source-code
```javascript
decrement = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.delete"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>delete (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.delete)
- description and source-code
```javascript
delete = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.do_auth"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>do_auth ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.do_auth)
- description and source-code
```javascript
do_auth = function () {
  var self = this;

  debug("Sending auth to " + self.host + ":" + self.port + " id " + self.connection_id);

  self.send_anyway = true;
  self.send_command("auth", [this.auth_username, this.auth_pass], function (err, res) {
    if (err) {
      return self.emit("error", new Error("Auth error"));
    }

    debug("Auth succeeded " + self.host + ":" + self.port + " id " + self.connection_id);

    if (self.auth_callback) {
      self.auth_callback(err, res);
      self.auth_callback = null;
    }

    // now we are really connected
    self.emit("connect");
    self.initialize_retry_vars();

    self.ready_check();
  });
  self.send_anyway = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.end"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>end ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.end)
- description and source-code
```javascript
end = function () {
  this.stream._events = {};
  this.connected = false;
  this.ready = false;
  this.closing = true;
  return this.stream.destroySoon();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.flush_and_error"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>flush_and_error (message)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.flush_and_error)
- description and source-code
```javascript
flush_and_error = function (message) {
  var command_obj, error;

  error = new Error(message);

  while (this.offline_queue.length > 0) {
    command_obj = this.offline_queue.shift();
    if (typeof command_obj.callback === "function") {
      try {
        command_obj.callback(error);
      } catch (callback_err) {
        this.emit("error", callback_err);
      }
    }
  }
  this.offline_queue = new Queue();

  while (this.command_queue.length > 0) {
    command_obj = this.command_queue.shift();
    if (typeof command_obj.callback === "function") {
      try {
        command_obj.callback(error);
      } catch (callback_err) {
        this.emit("error", callback_err);
      }
    }
  }
  this.command_queue = new Queue();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.get"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>get (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.get)
- description and source-code
```javascript
get = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.increment"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>increment (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.increment)
- description and source-code
```javascript
increment = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.init_parser"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>init_parser ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.init_parser)
- description and source-code
```javascript
init_parser = function () {
  var self = this;

  debug("Using default parser module: " + parsers[0].name);
  this.parser_module = parsers[0];

  // return_buffers sends back Buffers from parser to callback. detect_buffers sends back Buffers from parser, but
  // converts to Strings if the input arguments are not Buffers.
  this.reply_parser = new this.parser_module.Parser({ });

  this.reply_parser.on("reply", function (reply) {
    self.return_reply(reply);
  });
  // "error" is bad.  Somehow the parser got confused.  It'll try to reset and continue.
  this.reply_parser.on("error", function (err) {
    self.emit("error", new Error("Memcached reply parser error: " + err.stack));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.initialize_retry_vars"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>initialize_retry_vars ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.initialize_retry_vars)
- description and source-code
```javascript
initialize_retry_vars = function () {
  this.retry_timer = null;
  this.retry_delay = 150;
  this.retry_backoff = 1.7;
  this.attempts = 1;
  this.retry_max_delay = 60000; // 1 minute
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.noop"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>noop (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.noop)
- description and source-code
```javascript
noop = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_connect"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>on_connect ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_connect)
- description and source-code
```javascript
on_connect = function () {
  debug("Stream connected " + this.host + ":" + this.port + " id " + this.connection_id);

  this.connected = true;
  this.ready = false;
  this.command_queue = new Queue();
  this.emitted_end = false;
  this.stream.setNoDelay();
  this.stream.setKeepAlive(true);
  this.stream.setTimeout(0);

  this.init_parser();

  if (this.auth_username && this.auth_pass) {
    this.do_auth();
  }
  else {

    this.emit("connect");
    this.initialize_retry_vars();

    this.ready_check();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_data"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>on_data (data)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_data)
- description and source-code
```javascript
on_data = function (data) {
<span class="apidocCodeCommentSpan">  /*  if (exports.debug_mode) {
   console.log("net read " + this.host + ":" + this.port + " id " + this.connection_id + ": " + data.toString());
   }*/
</span>
  try {
    this.reply_parser.execute(data);
  } catch (err) {
    // This is an unexpected parser problem, an exception that came from the parser code itself.
    // Parser should emit "error" events if it notices things are out of whack.
    // Callbacks that throw exceptions will land in return_reply(), below.
    // TODO - it might be nice to have a different "error" event for different types of errors
    this.emit("error", err);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_error"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>on_error (msg)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_error)
- description and source-code
```javascript
on_error = function (msg) {
  var message = "Memcached connection to " + this.host + ":" + this.port + " failed - " + msg;

  if (this.closing) {
    return;
  }

  debug(message);

  this.flush_and_error(message);

  this.connected = false;
  this.ready = false;

  this.emit("error", new Error(message));
  // "error" events get turned into exceptions if they aren't listened for.  If the user handled this error
  // then we should try to reconnect.
  this.connection_gone("error");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_ready"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>on_ready ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.on_ready)
- description and source-code
```javascript
on_ready = function () {
  debug('memcached client is ready.');

  this.ready = true;

  this.send_offline_queue();

  this.emit("ready");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.prepend"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>prepend (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.prepend)
- description and source-code
```javascript
prepend = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.quit"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>quit (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.quit)
- description and source-code
```javascript
quit = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.ready_check"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>ready_check ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.ready_check)
- description and source-code
```javascript
ready_check = function () {
  var self = this;

  debug("checking server ready state...");

  this.send_anyway = true;  // secret flag to send_command to send something even if not "ready"
  this.noop(function (err, res) {
    if (err) {
      return self.emit("error", "Ready check failed");
    }

    self.on_ready();
  });
  this.send_anyway = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.reconnect"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>reconnect ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.reconnect)
- description and source-code
```javascript
reconnect = function () {
  if (this.connected) {
    debug("Retrying connect, but this.connected == true.");
    return;
  }

  var self = this;

  self.emit("reconnecting");

  debug("Retrying connection...");

  // if we still can not connect to server here, will NOT reconnect automatically
  // because this.attempts >= this.max_attempts)
  self.stream.connect(self.port, self.host);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.replace"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>replace (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.replace)
- description and source-code
```javascript
replace = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
...
    }
    foundInvalidType = true;
  }

  var acceptedType = type;
  if (!acceptedType) {
    /*jshint regexp:false*/
    acceptedType = acceptedTypes.join(', ').replace(/,([^,]+)$/, ', or$1');
  }

  var vowel = acceptedType.match(/^[aeiou]/i) ? 'n' : '';
  this.fail('InvalidParameterType', 'Expected ' + context + ' to be a' +
      vowel + ' ' + acceptedType);
},
...
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.return_reply"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>return_reply (reply)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.return_reply)
- description and source-code
```javascript
return_reply = function (reply) {
  var command_obj;

  command_obj = this.command_queue.shift();

  if (command_obj) {
    if (typeof command_obj.callback === "function") {
      try_callback(this, command_obj.callback, reply);
    }
    else {
      debug("no callback for reply: " + (reply && reply.toString && reply.toString()));
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.send_command"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>send_command (command, args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.send_command)
- description and source-code
```javascript
send_command = function (command, args, callback) {
  var arg, command_obj, i, il, elem_count, buffer_args, stream = this.stream, command_str = "", buffered_writes = 0, last_arg_type
, lcaseCommand;

  if (typeof command !== "string") {
    throw new Error("First argument to send_command must be the command name string, not " + typeof command);
  }

  if (Array.isArray(args)) {
    if (typeof callback === "function") {
      // probably the fastest way:
      //     client.command([arg1, arg2], cb);  (straight passthrough)
      //         send_command(command, [arg1, arg2], cb);
    } else if (!callback) {
      // most people find this variable argument length form more convenient, but it uses arguments, which is slower
      //     client.command(arg1, arg2, cb);   (wraps up arguments into an array)
      //       send_command(command, [arg1, arg2, cb]);
      //     client.command(arg1, arg2);   (callback is optional)
      //       send_command(command, [arg1, arg2]);
      //     client.command(arg1, arg2, undefined);   (callback is undefined)
      //       send_command(command, [arg1, arg2, undefined]);
      last_arg_type = typeof args[args.length - 1];
      if (last_arg_type === "function" || last_arg_type === "undefined") {
        callback = args.pop();
      }
    } else {
      throw new Error("send_command: last argument must be a callback or undefined");
    }
  } else {
    throw new Error("send_command: second argument must be an array");
  }

  // if the value is undefined or null and command is set or setx, need not to send message to redis
  if (command === 'set') {
    if (args[args.length - 1] === undefined || args[args.length - 1] === null) {
      var err = new Error('send_command: ' + command + ' value must not be undefined or null');
      return callback && callback(err);
    }
  }

  buffer_args = false;
  for (i = 0, il = args.length, arg; i < il; i += 1) {
    if (Buffer.isBuffer(args[i])) {
      buffer_args = true;
    }
  }

  command_obj = new Command(command, args, false, buffer_args, callback);

  if ((!this.ready && !this.send_anyway) || !stream.writable) {
    if (!stream.writable) {
      debug("send command: stream is not writeable.");
    }

    if (this.enable_offline_queue) {
      debug("Queueing " + command + " for next server connection.");
      this.offline_queue.push(command_obj);
      this.should_buffer = true;
    } else {
      var not_writeable_error = new Error('send_command: stream not writeable. enable_offline_queue is false');
      if (command_obj.callback) {
        command_obj.callback(not_writeable_error);
      } else {
        throw not_writeable_error;
      }
    }

    return false;
  }

  this.command_queue.push(command_obj);

  var buf;
  var extras;
  // Always use "Multi bulk commands", but if passed any Buffer args, then do multiple writes, one for each arg.
  // This means that using Buffers in commands is going to be slower, so use Strings if you don't already have a Buffer.
  if (command === "auth") {
    command_str = "\0" + args[0] + "\0" + args[1];

    buf = makeRequestBuffer(protocol.opcode.SASL_AUTH, 'PLAIN', '', command_str);

    buffered_writes += !stream.write(buf);
  }
  else if (command === "get") {
    buf = makeRequestBuffer(protocol.opcode.GET, args[0], '', '', '');

    buffered_writes += !stream.write(buf);
  }
  else if (command === "delete") {
    buf = makeRequestBuffer(protocol.opcode.DELETE, args[0], '', '', '');

    buffered_writes += !stream.write(buf);
  }
  else if (command === "set") {
    extras = Buffer.concat([new Buffer('00000000', 'hex'), makeExpiration(args[2] || this.options.expires)]);

    buf = makeRequestBuffer(protocol.opcode.SET, args[0], extras, args[1].toString(), '');

    buffered_writes += !stream.write(buf);
  }
  else if (command === "add") {
    extras = Buffer.concat([new Buffer('00000000', 'hex'), makeExpiration(args[2] || this.options.expires)]);

    buf = makeRequestBuffer(protocol.opcode.ADD, args[0], extras, args[1].toString(), '');

    buffered_writes += !stream.write(buf);
  }
  else if (command === "r ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.send_offline_queue"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>send_offline_queue ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.send_offline_queue)
- description and source-code
```javascript
send_offline_queue = function () {
  var command_obj, buffered_writes = 0;

  while (this.offline_queue.length > 0) {
    command_obj = this.offline_queue.shift();
    debug("Sending offline command: " + command_obj.command);
    buffered_writes += !this.send_command(command_obj.command, command_obj.args, command_obj.callback);
  }
  this.offline_queue = new Queue();
  // Even though items were shifted off, Queue backing store still uses memory until next add, so just get a new Queue

  if (!buffered_writes) {
    this.should_buffer = false;
    this.emit("drain");
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.set"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>set (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.set)
- description and source-code
```javascript
set = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
...

ALY.Config = ALY.util.inherit({

constructor: function Config(options) {
  if (options === undefined) options = {};

  ALY.util.each.call(this, this.keys, function (key, value) {
    this.set(key, options[key], value);
  });
},

clear: function clear() {
  /*jshint forin:false */
  ALY.util.each.call(this, this.keys, function (key) {
    delete this[key];
...
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.unref"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>unref ()](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.unref)
- description and source-code
```javascript
unref = function () {
  debug("User requesting to unref the connection");
  if (this.connected) {
    debug("unref'ing the socket connection");
    this.stream.unref();
  }
  else {
    debug("Not connected yet, will unref later");
    this.once("connect", function () {
      this.unref();
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.version"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MEMCACHED.MemcachedClient.prototype.</span>version (args, callback)](#apidoc.element.aliyun-sdk.MEMCACHED.MemcachedClient.prototype.version)
- description and source-code
```javascript
version = function (args, callback) {
  if (Array.isArray(args) && typeof callback === "function") {
    return this.send_command(command, args, callback);
  } else {
    return this.send_command(command, to_array(arguments));
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.MTS"></a>[module aliyun-sdk.MTS](#apidoc.module.aliyun-sdk.MTS)

#### <a name="apidoc.element.aliyun-sdk.MTS.MTS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>MTS ()](#apidoc.element.aliyun-sdk.MTS.MTS)
- description and source-code
```javascript
MTS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.MTS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MTS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.MTS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.MTS.prototype"></a>[module aliyun-sdk.MTS.prototype](#apidoc.module.aliyun-sdk.MTS.prototype)

#### <a name="apidoc.element.aliyun-sdk.MTS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.MTS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.MTS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.NodeHttpClient"></a>[module aliyun-sdk.NodeHttpClient](#apidoc.module.aliyun-sdk.NodeHttpClient)

#### <a name="apidoc.element.aliyun-sdk.NodeHttpClient.NodeHttpClient"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>NodeHttpClient ()](#apidoc.element.aliyun-sdk.NodeHttpClient.NodeHttpClient)
- description and source-code
```javascript
NodeHttpClient = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.NodeHttpClient.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.NodeHttpClient.</span>__super__ ()](#apidoc.element.aliyun-sdk.NodeHttpClient.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.OSS"></a>[module aliyun-sdk.OSS](#apidoc.module.aliyun-sdk.OSS)

#### <a name="apidoc.element.aliyun-sdk.OSS.OSS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>OSS ()](#apidoc.element.aliyun-sdk.OSS.OSS)
- description and source-code
```javascript
OSS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
...
'''

目前在浏览器端运行的 sdk 还在测试阶段, 如果有问题请随时提出.

## 初始化

'''javascript
var oss = new ALY.OSS({
  accessKeyId: "在阿里云OSS申请的 accessKeyId",
  secretAccessKey: "在阿里云OSS申请的 secretAccessKey",
  securityToken: "",
  endpoint: 'http://oss-cn-hangzhou.aliyuncs.com',
  apiVersion: '2013-10-15'
});
'''
...
```

#### <a name="apidoc.element.aliyun-sdk.OSS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.OSS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.OSS.prototype"></a>[module aliyun-sdk.OSS.prototype](#apidoc.module.aliyun-sdk.OSS.prototype)

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.addContentType"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.OSS.prototype.addContentType)
- description and source-code
```javascript
function addContentType(req) {
  var httpRequest = req.httpRequest;
  if (!httpRequest.headers['Content-Type']) { // always have a Content-Type
    httpRequest.headers['Content-Type'] = 'application/octet-stream';
  }
  if (ALY.util.isBrowser() && window.navigator.userAgent.match(/Firefox/)) {
    if (!httpRequest.headers['Content-Type'].match(/;/)) {
      var charset = '; charset=UTF-8';
      httpRequest.headers['Content-Type'] += charset;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.computeContentMd5"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>computeContentMd5 (req)](#apidoc.element.aliyun-sdk.OSS.prototype.computeContentMd5)
- description and source-code
```javascript
function computeContentMd5(req) {
  if (req.service.willComputeChecksums(req)) {
    var md5 = ALY.util.crypto.md5(req.httpRequest.body, 'base64');
    req.httpRequest.headers['Content-MD5'] = md5;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.OSS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.escapePathParam"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>escapePathParam (value)](#apidoc.element.aliyun-sdk.OSS.prototype.escapePathParam)
- description and source-code
```javascript
function escapePathParam(value) {
  return ALY.util.uriEscapePath(String(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.extractData"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.OSS.prototype.extractData)
- description and source-code
```javascript
function extractData(resp) {
  var req = resp.request;
  if (req.operation === 'getBucketLocation') {
<span class="apidocCodeCommentSpan">    /*jshint regexp:false*/
</span>    var match = resp.httpResponse.body.toString().match(/>(.+)<\/Location/);
    if (match) {
      delete resp.data['_'];
      resp.data.LocationConstraint = match[1];
    }
  }

  // extract request id
  resp.data.RequestId = resp.httpResponse.headers['x-oss-request-id'] ||
      resp.httpResponse.headers['x-oss-requestid'];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.extractError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.OSS.prototype.extractError)
- description and source-code
```javascript
function extractError(resp) {
  var codes = {
    304: 'NotModified',
    403: 'Forbidden',
    400: 'BadRequest',
    404: 'NotFound'
  };

  var code = resp.httpResponse.statusCode;
  var body = resp.httpResponse.body;
  if (codes[code] && body.length === 0) {
    resp.error = ALY.util.error(new Error(), {
      code: codes[resp.httpResponse.statusCode],
      message: null,
      headers: resp.httpResponse.headers
    });
  } else {
    var data;
    try {
      data = new ALY.XML.Parser({}).parse(body.toString());
      resp.error = ALY.util.error(new Error(), {
        code: data.Code || code,
        message: data.Message || null,
        headers: resp.httpResponse.headers
      });
    }
    catch(e) {
      data = body.toString();
      resp.error = ALY.util.error(new Error(), {
        code: code,
        message: data,
        headers: resp.httpResponse.headers
      });
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.getSignedUrl"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>getSignedUrl (operation, params, callback)](#apidoc.element.aliyun-sdk.OSS.prototype.getSignedUrl)
- description and source-code
```javascript
function getSignedUrl(operation, params, callback) {
  params = ALY.util.copy(params || {});
  var expires = params.Expires || 900;
  delete params.Expires; // we can't validate this
  var request = this.makeRequest(operation, params);

  var expiresHeader = 'presigned-expires';

  function signedUrlBuilder() {
    delete request.httpRequest.headers['User-Agent'];

    if (request.service.getSignerClass() === ALY.Signers.V4) {
      //if (expires > 604800) { // one week expiry is invalid
      //  var message = 'getSignedUrl() does not support expiry time greater ' +
      //    'than a week with SigV4 signing.';
      //  throw ALY.util.error(new Error(), {
      //    code: 'InvalidExpiryTime', message: message, retryable: false
      //  });
      //}
      request.httpRequest.headers[expiresHeader] = expires;
    } else {
      request.httpRequest.headers[expiresHeader] = parseInt(
        ALY.util.date.unixSeconds() + expires, 10).toString();
    }
  }

  function signedUrlSigner() {
    var queryParams = {};

    ALY.util.each(request.httpRequest.headers, function (key, value) {
      if (key === expiresHeader) key = 'Expires';
      queryParams[key] = value;
    });
    delete request.httpRequest.headers[expiresHeader];

    var auth = queryParams['Authorization'].split(' ');
    if (auth[0] === 'OSS') {
      auth = auth[1].split(':');
      queryParams['OSSAccessKeyId'] = auth[0];
      queryParams['Signature'] = auth[1];
    }
    delete queryParams['Authorization'];
    delete queryParams['Host'];

    // build URL
    var endpoint = request.httpRequest.endpoint;
    var parsedUrl = ALY.util.urlParse(request.httpRequest.path);
    var querystring = ALY.util.queryParamsToString(queryParams);
    endpoint.pathname = parsedUrl.pathname;
    endpoint.search = !parsedUrl.search ? querystring :
      parsedUrl.search + '&' + querystring;
  }

  request.on('build', signedUrlBuilder);
  request.on('sign', signedUrlSigner);
  request.removeListener('build', this.addContentType);
  request.removeAllListeners('afterBuild');
  if (!params.Body) { // no Content-MD5/SHA-256 if body is not provided
    request.removeListener('build', this.computeContentMd5);
  }

  if (callback) {
    request.build(function() {
      if (request.response.error) callback(request.response.error, null);
      else callback(null, ALY.util.urlFormat(request.httpRequest.endpoint));
    });
  } else {
    request.build();
    return ALY.util.urlFormat(request.httpRequest.endpoint);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.initialize"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.OSS.prototype.initialize)
- description and source-code
```javascript
function initialize(options) {
  ALY.Service.prototype.initialize.call(this, options);
}
```
- example usage
```shell
...
constructor: function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
...
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.populateURI"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>populateURI (req)](#apidoc.element.aliyun-sdk.OSS.prototype.populateURI)
- description and source-code
```javascript
function populateURI(req) {
  var httpRequest = req.httpRequest;
  var b = req.params.Bucket;

  if (b) {
    // 确保 host 只被 set 一次，因为 endpoint 只在 service 唯一
    httpRequest.endpoint.host = httpRequest.endpoint.hostname = b + '.' + httpRequest.endpoint.hostname;

    httpRequest.virtualHostedBucket = b;
    httpRequest.path = httpRequest.path.replace(new RegExp('^/' + b), '');
    if (httpRequest.path[0] !== '/') {
      httpRequest.path = '/' + httpRequest.path;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.retryableError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>retryableError (error, request)](#apidoc.element.aliyun-sdk.OSS.prototype.retryableError)
- description and source-code
```javascript
function retryableError(error, request) {
  if (request.operation == 'completeMultipartUpload' &&
    error.statusCode === 200) {
    return true;
  } else {
    var _super = ALY.Service.prototype.retryableError;
    return _super.call(this, error, request);
  }
}
```
- example usage
```shell
...
    delete resp.httpResponse.buffers;
  });

  add('FINALIZE_ERROR', 'retry', function FINALIZE_ERROR(resp) {
    if (resp.httpResponse.statusCode) {
      resp.error.statusCode = resp.httpResponse.statusCode;
      if (resp.error.retryable === undefined) {
        resp.error.retryable = this.service.retryableError(resp.error, this);
      }
    }
  });

}),

Logger: new ALY.SequentialExecutor().addNamedListeners(function(add) {
...
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.setupRequestListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.OSS.prototype.setupRequestListeners)
- description and source-code
```javascript
function setupRequestListeners(request) {
  request.addListener('build', this.addContentType);
  request.addListener('build', this.populateURI);
  request.addListener('build', this.computeContentMd5);
  request.addListener('extractError', this.extractError);
  request.addListener('extractData', this.extractData);
}
```
- example usage
```shell
...
      ALY.EventListeners.Core.VALIDATE_PARAMETERS);
  }

  if (this.config.logger) { // add logging events
    request.addListeners(ALY.EventListeners.Logger);
  }

  this.setupRequestListeners(request);
},

/**
 * Override this method to setup any custom request listeners for each
 * new request to the service.
 *
 * @abstract
...
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.successfulResponse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.OSS.prototype.successfulResponse)
- description and source-code
```javascript
function successfulResponse(resp) {
  var req = resp.request;
  var httpResponse = resp.httpResponse;
  if (req.operation === 'completeMultipartUpload' &&
    httpResponse.body.toString().match('<Error>'))
    return false;
  else
    return httpResponse.statusCode < 300;
}
```
- example usage
```shell
...
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
  if (this.service.successfulResponse(resp, this)) {
    resp.data = {};
    resp.error = null;
  } else {
    resp.data = null;
    resp.error = ALY.util.error(new Error(),
      {code: 'UnknownError', message: 'An unknown error occurred.'});
  }
...
```

#### <a name="apidoc.element.aliyun-sdk.OSS.prototype.willComputeChecksums"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OSS.prototype.</span>willComputeChecksums (req)](#apidoc.element.aliyun-sdk.OSS.prototype.willComputeChecksums)
- description and source-code
```javascript
function willComputeChecksums(req) {
  // TODO: compute checksums for Stream objects
  //if (!ALY.util.Buffer.isBuffer(req.httpRequest.body) &&
  //  typeof req.httpRequest.body !== 'string') {
  //  return false;
  //}

  var rules = req.service.api.operations[req.operation].input.members;

  if (rules.ContentMD5 && !req.params.ContentMD5) return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.OTS"></a>[module aliyun-sdk.OTS](#apidoc.module.aliyun-sdk.OTS)

#### <a name="apidoc.element.aliyun-sdk.OTS.OTS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>OTS ()](#apidoc.element.aliyun-sdk.OTS.OTS)
- description and source-code
```javascript
OTS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.OTS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.OTS.prototype"></a>[module aliyun-sdk.OTS.prototype](#apidoc.module.aliyun-sdk.OTS.prototype)

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.addContentType"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.OTS.prototype.addContentType)
- description and source-code
```javascript
function addContentType(req) {
  var httpRequest = req.httpRequest;
  //httpRequest.headers['x-ots-contenttype'] = 'protocol buffer';
  httpRequest.headers['x-ots-apiversion'] = '2014-08-08';
  httpRequest.headers['x-ots-instancename'] = req.params.instance_name;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.buildContent"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>buildContent (req)](#apidoc.element.aliyun-sdk.OTS.prototype.buildContent)
- description and source-code
```javascript
function buildContent(req) {
  var request;

  switch(req.operation) {
    case 'createTable':
      request = new protos.CreateTableRequest({
        table_meta: req.params.table_meta,
        reserved_throughput: req.params.reserved_throughput
      });
      break;
    case 'listTable':
      request = new protos.ListTableRequest({});
      break;
    case 'deleteTable':
      request = new protos.DeleteTableRequest({
        table_name: req.params.table_name
      });
      break;
    case 'updateTable':
      request = new protos.UpdateTableRequest({
        table_name: req.params.table_name
      });
      break;
    case 'describeTable':
      request = new protos.DescribeTableRequest({
        table_name: req.params.table_name,
        reserved_throughput: req.params.reserved_throughput
      });
      break;
    case 'getRow':
      request = new protos.GetRowRequest({
        table_name: req.params.table_name,
        primary_key: req.params.primary_key,
        columns_to_get: req.params.columns_to_get
      });
      break;
    case 'putRow':
      request = new protos.PutRowRequest({
        table_name: req.params.table_name,
        condition: req.params.condition,
        primary_key: req.params.primary_key,
        attribute_columns: req.params.attribute_columns
      });
      break;
    case 'updateRow':
      request = new protos.UpdateRowRequest({
        table_name: req.params.table_name,
        condition: req.params.condition,
        primary_key: req.params.primary_key,
        attribute_columns: req.params.attribute_columns
      });
      break;
    case 'deleteRow':
      request = new protos.DeleteRowRequest({
        table_name: req.params.table_name,
        condition: req.params.condition,
        primary_key: req.params.primary_key
      });
      break;
    case 'getRange':
      request = new protos.GetRangeRequest({
        table_name: req.params.table_name,
        direction: req.params.direction,
        columns_to_get: req.params.columns_to_get,
        limit: req.params.limit,
        inclusive_start_primary_key: req.params.inclusive_start_primary_key,
        exclusive_end_primary_key: req.params.exclusive_end_primary_key,
      });
      break;
    case 'batchGetRow':
      request = new protos.BatchGetRowRequest({
        tables: req.params.tables
      });
      break;
    case 'batchWriteRow':
      request = new protos.BatchWriteRowRequest({
        tables: req.params.tables
      });
      break;
  }

  var buffer = request.encode();

  req.httpRequest.body = buffer.toBuffer();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.computeContentMd5"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>computeContentMd5 (req)](#apidoc.element.aliyun-sdk.OTS.prototype.computeContentMd5)
- description and source-code
```javascript
function computeContentMd5(req) {
  var md5 = ALY.util.crypto.md5(req.httpRequest.body, 'base64');
  req.httpRequest.headers['x-ots-contentmd5'] = md5;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.OTS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.escapePathParam"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>escapePathParam (value)](#apidoc.element.aliyun-sdk.OTS.prototype.escapePathParam)
- description and source-code
```javascript
function escapePathParam(value) {
  return ALY.util.uriEscapePath(String(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.extractData"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.OTS.prototype.extractData)
- description and source-code
```javascript
function extractData(resp) {
  resp.data = protos[capitalizeFirstLetter(resp.request.operation) + "Response"].decode(resp.httpResponse.body);

  // extract request id
  resp.data.RequestId = resp.httpResponse.headers['x-ots-request-id'] ||
      resp.httpResponse.headers['x-ots-requestid'];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.extractError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.OTS.prototype.extractError)
- description and source-code
```javascript
function extractError(resp) {
  var codes = {
    304: 'NotModified',
    403: 'Forbidden',
    400: 'BadRequest',
    404: 'NotFound'
  };

  var code = resp.httpResponse.statusCode;
  var body = resp.httpResponse.body;
  if (codes[code] && body.length === 0) {
    resp.error = ALY.util.error(new Error(), {
      code: codes[resp.httpResponse.statusCode],
      message: null,
      headers: resp.httpResponse.headers
    });
  } else {
    var data;
    try {
      data = new ALY.XML.Parser({}).parse(body.toString());
      resp.error = ALY.util.error(new Error(), {
        code: data.Code || code,
        message: data.Message || null,
        headers: resp.httpResponse.headers
      });
    }
    catch (e) {
      data = body.toString();
      resp.error = ALY.util.error(new Error(), {
        code: code,
        message: data,
        headers: resp.httpResponse.headers
      });
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.initialize"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.OTS.prototype.initialize)
- description and source-code
```javascript
function initialize(options) {
  var builder = ProtoBuf.newBuilder();
  builder.define("ots2");
  builder.create(
      [
        {
          "name": "Error",
          "fields": [
            {
              "rule": "required",
              "type": "string",
              "name": "code",
              "id": 1
            },
            {
              "rule": "optional",
              "type": "string",
              "name": "message",
              "id": 2
            }
          ]
        },
        {
          "name": "ColumnType",
          "values": [
            {
              "name": "INF_MIN",
              "id": 0
            },
            {
              "name": "INF_MAX",
              "id": 1
            },
            {
              "name": "INTEGER",
              "id": 2
            },
            {
              "name": "STRING",
              "id": 3
            },
            {
              "name": "BOOLEAN",
              "id": 4
            },
            {
              "name": "DOUBLE",
              "id": 5
            },
            {
              "name": "BINARY",
              "id": 6
            }
          ]
        },
        {
          "name": "ColumnSchema",
          "fields": [
            {
              "rule": "required",
              "type": "string",
              "name": "name",
              "id": 1
            },
            {
              "rule": "required",
              "type": "ColumnType",
              "name": "type",
              "id": 2
            }
          ]
        },
        {
          "name": "ColumnValue",
          "fields": [
            {
              "rule": "required",
              "type": "ColumnType",
              "name": "type",
              "id": 1
            },
            {
              "rule": "optional",
              "type": "int64",
              "name": "v_int",
              "id": 2
            },
            {
              "rule": "optional",
              "type": "string",
              "name": "v_string",
              "id": 3
            },
            {
              "rule": "optional",
              "type": "bool",
              "name": "v_bool",
              "id": 4
            },
            {
              "rule": "optional",
              "type": "double",
              "name": "v_double",
              "id": 5
            },
            {
              "rule": "optional",
              "type": "bytes",
              "name": "v_binary",
              "id": 6
            }
          ]
        },
        {
          "name": "Column",
          "fields": [
            {
              "rule": "required",
              "type": "string",
              "name": "name",
              "id": 1
            },
            {
              "rule": "required",
              "type": "ColumnValue",
              "name": "value",
              "id": 2
            }
          ]
        },
        {
          "name": "Row",
          "fields": [
            {
              "rule": "repeated",
              "type": "Column",
              "name": "primary_key_columns",
              "id": 1
            },
            {
              "rule": "repeated",
              "type": "Column",
              "name": "attribute_columns",
              "id": 2
            }
          ]
        },
        {
          "name": "TableMeta",
          "fields": [
            {
              "rule": "required",
              "type": "string",
              "name": "table_name",
              "id": 1
            },
            {
              "rule": "repeated",
              "type": "ColumnSchema",
              "name": "primary_key",
              "id": 2
            }
          ]
        },
        {
          "name": "RowExistenceExpectation",
          "values": [
            {
              "name": "IGNORE",
              "id": 0
            },
            {
              "name": "EXPECT_EXIST",
              "id": 1
            },
            {
              "name": "EXPECT_NOT_EXIST",
              "id": 2
            }
          ]
        },
        { ...
```
- example usage
```shell
...
constructor: function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
...
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.populateURI"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>populateURI (req)](#apidoc.element.aliyun-sdk.OTS.prototype.populateURI)
- description and source-code
```javascript
function populateURI(req) {
  var httpRequest = req.httpRequest;
  var b = req.params.instance_name;

  // 固定 endpoint
  if (req.service.config.endpointFixed) {
    return;
  }

  if (b) {
    // 确保 host 只被 set 一次，因为 endpoint 只在 service 唯一
    httpRequest.endpoint.host = httpRequest.endpoint.hostname = b + '.' + httpRequest.endpoint.hostname;

    httpRequest.virtualHostedBucket = b;
    httpRequest.path = httpRequest.path.replace(new RegExp('^/' + b), '');
    if (httpRequest.path[0] !== '/') {
      httpRequest.path = '/' + httpRequest.path;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.retryableError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>retryableError (error, request)](#apidoc.element.aliyun-sdk.OTS.prototype.retryableError)
- description and source-code
```javascript
function retryableError(error, request) {
  if (request.operation == 'completeMultipartUpload' &&
      error.statusCode === 200) {
    return true;
  } else {
    var _super = ALY.Service.prototype.retryableError;
    return _super.call(this, error, request);
  }
}
```
- example usage
```shell
...
    delete resp.httpResponse.buffers;
  });

  add('FINALIZE_ERROR', 'retry', function FINALIZE_ERROR(resp) {
    if (resp.httpResponse.statusCode) {
      resp.error.statusCode = resp.httpResponse.statusCode;
      if (resp.error.retryable === undefined) {
        resp.error.retryable = this.service.retryableError(resp.error, this);
      }
    }
  });

}),

Logger: new ALY.SequentialExecutor().addNamedListeners(function(add) {
...
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.setupRequestListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.OTS.prototype.setupRequestListeners)
- description and source-code
```javascript
function setupRequestListeners(request) {
  request.addListener('build', this.addContentType);
  request.addListener('build', this.populateURI);
  request.addListener('build', this.buildContent);
  request.addListener('build', this.computeContentMd5);
  request.addListener('extractError', this.extractError);
  request.addListener('extractData', this.extractData);
}
```
- example usage
```shell
...
      ALY.EventListeners.Core.VALIDATE_PARAMETERS);
  }

  if (this.config.logger) { // add logging events
    request.addListeners(ALY.EventListeners.Logger);
  }

  this.setupRequestListeners(request);
},

/**
 * Override this method to setup any custom request listeners for each
 * new request to the service.
 *
 * @abstract
...
```

#### <a name="apidoc.element.aliyun-sdk.OTS.prototype.successfulResponse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OTS.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.OTS.prototype.successfulResponse)
- description and source-code
```javascript
function successfulResponse(resp) {
  var req = resp.request;
  var httpResponse = resp.httpResponse;
  if (req.operation === 'completeMultipartUpload' &&
      httpResponse.body.toString().match('<Error>'))
    return false;
  else
    return httpResponse.statusCode < 300;
}
```
- example usage
```shell
...
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
  if (this.service.successfulResponse(resp, this)) {
    resp.data = {};
    resp.error = null;
  } else {
    resp.data = null;
    resp.error = ALY.util.error(new Error(),
      {code: 'UnknownError', message: 'An unknown error occurred.'});
  }
...
```



# <a name="apidoc.module.aliyun-sdk.OpenSearch"></a>[module aliyun-sdk.OpenSearch](#apidoc.module.aliyun-sdk.OpenSearch)

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.OpenSearch"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>OpenSearch ()](#apidoc.element.aliyun-sdk.OpenSearch.OpenSearch)
- description and source-code
```javascript
OpenSearch = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.</span>__super__ (config)](#apidoc.element.aliyun-sdk.OpenSearch.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.OpenSearch.prototype"></a>[module aliyun-sdk.OpenSearch.prototype](#apidoc.module.aliyun-sdk.OpenSearch.prototype)

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.addContentType"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.addContentType)
- description and source-code
```javascript
function addContentType(req) {
  var httpRequest = req.httpRequest;

  httpRequest.headers['Content-Type'] = 'application/x-www-form-urlencoded;charset=UTF-8';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.buildContent"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>buildContent (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.buildContent)
- description and source-code
```javascript
function buildContent(req) {
  var input = req.service.api.operations[req.operation].input;
  var payload = input.payload;
  var params = {};

  // todo: payload 是否有可能为 string
  if (typeof payload === 'string') {

    var rules = input.members[payload];
    params = req.params[payload];

    if (params === undefined) return;

    if (rules.type === 'structure') {
      req.httpRequest.body = this.buildJSON(params, input, req.service.api);
    } else {
      // non-xml paylaod
      req.httpRequest.body = params;
    }

  } else if (payload) {
    var arr = [];

    ALY.util.arrayEach(payload, function (param) {
      if (req.params[param] !== undefined) {
        params[param] = req.params[param];
        if(param == 'items') {
          arr.push(param + '=' + encodeURIComponent(JSON.stringify(req.params[param])));
        }
        else {
          arr.push(param + '=' + req.params[param]);
        }
      }
    });

    req.httpRequest.body = arr.join('&');
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.computeContentMd5"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>computeContentMd5 (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.computeContentMd5)
- description and source-code
```javascript
function computeContentMd5(req) {
  if (req.service.willComputeChecksums(req)) {
    var md5 = ALY.util.crypto.md5(req.httpRequest.body, 'hex').toUpperCase();
    req.httpRequest.headers['Content-MD5'] = md5;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.computeSha256"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>computeSha256 (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.computeSha256)
- description and source-code
```javascript
function computeSha256(req) {
  if (req.service.getSignerClass(req) === ALY.Signers.V4) {
    req.httpRequest.headers['X-Amz-Content-Sha256'] =
        ALY.util.crypto.sha256(req.httpRequest.body || '', 'hex');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.OpenSearch.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.escapePathParam"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>escapePathParam (value)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.escapePathParam)
- description and source-code
```javascript
function escapePathParam(value) {
  return ALY.util.uriEscapePath(String(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.extractData"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.extractData)
- description and source-code
```javascript
function extractData(resp) {
  ALY.ServiceInterface.Rest.extractData(resp);

  var req = resp.request;
  var rules = req.service.api.operations[req.operation].output || {};
  if (rules.payload && rules.members[rules.payload]) {
    if (rules.members[rules.payload].streaming) {
      resp.data[rules.payload] = resp.httpResponse.body;
    } else {
      resp.data[rules.payload] = resp.httpResponse.body.toString();
    }
  } else {
    var data = resp.data;
    ALY.ServiceInterface.Json.extractData(resp);
    resp.data = ALY.util.merge(data, resp.data);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.extractError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.extractError)
- description and source-code
```javascript
function extractError(resp) {
  var error = {};
  var httpResponse = resp.httpResponse;

  if (httpResponse.body.length > 0) {
    var e = JSON.parse(httpResponse.body.toString());
    if (e.__type || e.code) {
      error.code = (e.__type || e.code).split('#').pop();
    } else {
      error.code = 'UnknownError';
    }
    if (error.code === 'RequestEntityTooLarge') {
      error.message = 'Request body must be less than 1 MB';
    } else {
      error.message = (e.message || e.Message || null);
    }
  } else {
    error.code = httpResponse.statusCode;
    error.message = null;
  }

  resp.error = ALY.util.error(new Error(), error);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.initialize"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.initialize)
- description and source-code
```javascript
function initialize(options) {
  ALY.Service.prototype.initialize.call(this, options);
}
```
- example usage
```shell
...
constructor: function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
...
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.populateURI"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>populateURI (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.populateURI)
- description and source-code
```javascript
function populateURI(req) {
  var hostname = req.httpRequest.endpoint.hostname;

  var projectName = req.params['projectName'];
  var host = projectName + '.' + hostname;

  if (!/^[0-9.]+$/.test(hostname)) {
    //不是ip,  是域名, 则需要拼接project名
    var protocol = req.httpRequest.endpoint.protocol;
    var port = req.httpRequest.endpoint.port;

    //real endpoint
    var endpointObj = parseURL(protocol + '//' + host + ':' + port);

    ALY.util.update(req.httpRequest, {endpoint: endpointObj});
    // ALY.util.update(req.service, {endpoint: endpointObj });
  }

  //final host， 不管是ip还是域名，都要拼接project名
  req.httpRequest.headers['Host'] = host;

  //头中的 projectName 不需要
  delete req.httpRequest.headers['projectName'];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.retryableError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>retryableError (error, request)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.retryableError)
- description and source-code
```javascript
function retryableError(error, request) {

  var _super = ALY.Service.prototype.retryableError;
  return _super.call(this, error, request);

}
```
- example usage
```shell
...
    delete resp.httpResponse.buffers;
  });

  add('FINALIZE_ERROR', 'retry', function FINALIZE_ERROR(resp) {
    if (resp.httpResponse.statusCode) {
      resp.error.statusCode = resp.httpResponse.statusCode;
      if (resp.error.retryable === undefined) {
        resp.error.retryable = this.service.retryableError(resp.error, this);
      }
    }
  });

}),

Logger: new ALY.SequentialExecutor().addNamedListeners(function(add) {
...
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.setupRequestListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.setupRequestListeners)
- description and source-code
```javascript
function setupRequestListeners(request) {
  request.addListener('build', this.addContentType);
  request.addListener('build', this.buildContent);
  //request.addListener('build', this.populateURI);
  //
  //request.addListener('build', this.computeContentMd5);
  //request.addListener('build', this.computeSha256);

  request.removeListener('validate',
      ALY.EventListeners.Core.VALIDATE_REGION);

  request.addListener('extractError', this.extractError);
  request.addListener('extractData', this.extractData);

  //request.addListener('afterBuild', function (req) {
  //    //Host in request.header
  //    console.log(req.httpRequest.headers['projectName'], req.params['projectName']);
  //
  //    req.httpRequest.headers['Host'] = req.params['projectName']
  //       +'.'+req.httpRequest.endpoint.hostname;
  //    //头中的 projectName 不需要
  //    delete req.httpRequest.headers['projectName'];
  //});
}
```
- example usage
```shell
...
      ALY.EventListeners.Core.VALIDATE_PARAMETERS);
  }

  if (this.config.logger) { // add logging events
    request.addListeners(ALY.EventListeners.Logger);
  }

  this.setupRequestListeners(request);
},

/**
 * Override this method to setup any custom request listeners for each
 * new request to the service.
 *
 * @abstract
...
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.successfulResponse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.successfulResponse)
- description and source-code
```javascript
function successfulResponse(resp) {
  //var req = resp.request;
  var httpResponse = resp.httpResponse;
  return httpResponse.statusCode < 300;
}
```
- example usage
```shell
...
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
  if (this.service.successfulResponse(resp, this)) {
    resp.data = {};
    resp.error = null;
  } else {
    resp.data = null;
    resp.error = ALY.util.error(new Error(),
      {code: 'UnknownError', message: 'An unknown error occurred.'});
  }
...
```

#### <a name="apidoc.element.aliyun-sdk.OpenSearch.prototype.willComputeChecksums"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.OpenSearch.prototype.</span>willComputeChecksums (req)](#apidoc.element.aliyun-sdk.OpenSearch.prototype.willComputeChecksums)
- description and source-code
```javascript
function willComputeChecksums(req) {

  // // TODO: compute checksums for Stream objects
  // if (!ALY.util.Buffer.isBuffer(req.httpRequest.body) &&
  //     typeof req.httpRequest.body !== 'string') {
  //     return false;
  // }

  var rules = req.service.api.operations[req.operation].input;

  // // V4 signer uses SHA256 signatures so only compute MD5 if it is required
  // if (req.service.getSignerClass(req) === ALY.Signers.V4) {
  //     if (rules.ContentMD5 && !rules.ContentMD5.required) return false;
  // }

  if (rules.ContentMD5) return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.PUSH"></a>[module aliyun-sdk.PUSH](#apidoc.module.aliyun-sdk.PUSH)

#### <a name="apidoc.element.aliyun-sdk.PUSH.PUSH"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>PUSH ()](#apidoc.element.aliyun-sdk.PUSH.PUSH)
- description and source-code
```javascript
PUSH = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.PUSH.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.PUSH.</span>__super__ (config)](#apidoc.element.aliyun-sdk.PUSH.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.PUSH.prototype"></a>[module aliyun-sdk.PUSH.prototype](#apidoc.module.aliyun-sdk.PUSH.prototype)

#### <a name="apidoc.element.aliyun-sdk.PUSH.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.PUSH.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.PUSH.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.ParamValidator"></a>[module aliyun-sdk.ParamValidator](#apidoc.module.aliyun-sdk.ParamValidator)

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.ParamValidator"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>ParamValidator ()](#apidoc.element.aliyun-sdk.ParamValidator.ParamValidator)
- description and source-code
```javascript
ParamValidator = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
...
};

ALY.EventListeners = {
  Core: new ALY.SequentialExecutor().addNamedListeners(function(add, addAsync) {

add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
  if (req.httpRequest.headers['Content-Length'] === undefined) {
    var length = ALY.util.string.byteLength(req.httpRequest.body);
    req.httpRequest.headers['Content-Length'] = length;
  }
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.</span>__super__ ()](#apidoc.element.aliyun-sdk.ParamValidator.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.ParamValidator.prototype"></a>[module aliyun-sdk.ParamValidator.prototype](#apidoc.module.aliyun-sdk.ParamValidator.prototype)

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.ParamValidator.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.fail"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>fail (code, message)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.fail)
- description and source-code
```javascript
function fail(code, message) {
  throw ALY.util.error(new Error(message), {code: code});
}
```
- example usage
```shell
...
var value = params[paramName];
var notSet = value === undefined || value === null;
if (notSet) {
  if (rules[paramName].default) {
    params[paramName] = rules[paramName].default;
  }
  else if (rules[paramName].required) {
    this.fail('MissingRequiredParameter',
        'Missing required key \'' + paramName + '\' in ' + context);
  }
}
//if (rules[paramName].location == 'uri' && value) {
//  if (typeof value == 'string' && value.indexOf('/') == 0) {
//    this.fail('UnexpectedParameter',
//        'the value of ' + paramName + ' can not start with /');
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validate"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validate (rules, params, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validate)
- description and source-code
```javascript
function validate(rules, params, context) {
  var cRules = (rules || {}).members || {};
  var payload = rules ? rules.xml : null;
  if (payload) {
    cRules = ALY.util.merge(cRules, (cRules[payload] || {}).members || {});
    delete cRules[payload];
  }

  return this.validateStructure(cRules, params || {}, context || 'params');
}
```
- example usage
```shell
...
};

ALY.EventListeners = {
  Core: new ALY.SequentialExecutor().addNamedListeners(function(add, addAsync) {

add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
  if (req.httpRequest.headers['Content-Length'] === undefined) {
    var length = ALY.util.string.byteLength(req.httpRequest.body);
    req.httpRequest.headers['Content-Length'] = length;
  }
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validateList"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateList (rules, params, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateList)
- description and source-code
```javascript
function validateList(rules, params, context) {
  this.validateType(context, params, [Array]);

  // validate array members
  for (var i = 0; i < params.length; i++) {
    this.validateMember(rules, params[i], context + '[' + i + ']');
  }
}
```
- example usage
```shell
...

validateMember: function validateMember(rules, param, context) {
  var memberRules = rules.members || {};
  switch(rules.type) {
    case 'structure':
      return this.validateStructure(memberRules, param, context);
    case 'list':
      return this.validateList(memberRules, param, context);
    case 'map':
      return this.validateMap(memberRules, param, context);
    default:
      return this.validateScalar(rules, param, context);
  }
},
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validateMap"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateMap (rules, params, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateMap)
- description and source-code
```javascript
function validateMap(rules, params, context) {
  this.validateType(context, params, ['object'], 'map');

<span class="apidocCodeCommentSpan">  /*jshint forin:false*/
</span>  for (var param in params) {
    if (!params.hasOwnProperty(param)) continue;
    this.validateMember(rules, params[param],
        context + '[\'' +  param + '\']');
  }
}
```
- example usage
```shell
...
  var memberRules = rules.members || {};
  switch(rules.type) {
    case 'structure':
      return this.validateStructure(memberRules, param, context);
    case 'list':
      return this.validateList(memberRules, param, context);
    case 'map':
      return this.validateMap(memberRules, param, context);
    default:
      return this.validateScalar(rules, param, context);
  }
},

validateList: function validateList(rules, params, context) {
  this.validateType(context, params, [Array]);
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validateMember"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateMember (rules, param, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateMember)
- description and source-code
```javascript
function validateMember(rules, param, context) {
  var memberRules = rules.members || {};
  switch(rules.type) {
    case 'structure':
      return this.validateStructure(memberRules, param, context);
    case 'list':
      return this.validateList(memberRules, param, context);
    case 'map':
      return this.validateMap(memberRules, param, context);
    default:
      return this.validateScalar(rules, param, context);
  }
}
```
- example usage
```shell
...
  if (!params.hasOwnProperty(paramName)) continue;

  var paramValue = params[paramName],
      paramRules = rules[paramName];

  if (paramRules !== undefined) {
    var memberContext = [context, paramName].join('.');
    this.validateMember(paramRules, paramValue, memberContext);
  } else {
    this.fail('UnexpectedParameter',
        'Unexpected key \'' + paramName + '\' found in ' + context);
  }
}

return true;
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validateNumber"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateNumber (context, value)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateNumber)
- description and source-code
```javascript
function validateNumber(context, value) {
  if (value === null || value === undefined) return;
  if (typeof value === 'string') {
    var castedValue = parseFloat(value);
    if (castedValue.toString() === value) value = castedValue;
  }
  return this.validateType(context, value, ['number']);
}
```
- example usage
```shell
...
case 'string':
  return this.validateType(context, value, ['string']);
case 'base64':
case 'binary':
  return this.validatePayload(context, value);
case 'integer':
case 'float':
  return this.validateNumber(context, value);
case 'boolean':
  return this.validateType(context, value, ['boolean']);
case 'timestamp':
  return this.validateType(context, value, [Date,
        /^\d{4}-\d{2}-\d{2}T\d{2}:\d{2}:\d{2}(\.\d+)?Z$/, 'number'],
      'Date object, ISO-8601 string, or a UNIX timestamp');
default:
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validatePayload"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validatePayload (context, value)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validatePayload)
- description and source-code
```javascript
function validatePayload(context, value) {
<span class="apidocCodeCommentSpan">  /*jshint maxcomplexity:14*/
</span>  if (value === null || value === undefined) return;
  if (typeof value === 'string') return;
  if (value && typeof value.byteLength === 'number') return; // typed arrays
  if (ALY.util.isNode()) { // special check for buffer/stream in Node.js
    var Stream = require('stream').Stream;
    if (ALY.util.Buffer.isBuffer(value) || value instanceof Stream) return;
  }

  var types = ['Buffer', 'Stream', 'File', 'Blob', 'ArrayBuffer', 'DataView'];
  if (value) {
    for (var i = 0; i < types.length; i++) {
      if (ALY.util.isType(value, types[i])) return;
      if (ALY.util.typeName(value.constructor) === types[i]) return;
    }
  }

  this.fail('InvalidParameterType', 'Expected ' + context + ' to be a ' +
      'string, Buffer, Stream, Blob, or typed array object');
}
```
- example usage
```shell
...
    switch (rules.type) {
case null:
case undefined:
case 'string':
  return this.validateType(context, value, ['string']);
case 'base64':
case 'binary':
  return this.validatePayload(context, value);
case 'integer':
case 'float':
  return this.validateNumber(context, value);
case 'boolean':
  return this.validateType(context, value, ['boolean']);
case 'timestamp':
  return this.validateType(context, value, [Date,
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validateScalar"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateScalar (rules, value, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateScalar)
- description and source-code
```javascript
function validateScalar(rules, value, context) {
<span class="apidocCodeCommentSpan">  /*jshint maxcomplexity:12*/
</span>  switch (rules.type) {
    case null:
    case undefined:
    case 'string':
      return this.validateType(context, value, ['string']);
    case 'base64':
    case 'binary':
      return this.validatePayload(context, value);
    case 'integer':
    case 'float':
      return this.validateNumber(context, value);
    case 'boolean':
      return this.validateType(context, value, ['boolean']);
    case 'timestamp':
      return this.validateType(context, value, [Date,
            /^\d{4}-\d{2}-\d{2}T\d{2}:\d{2}:\d{2}(\.\d+)?Z$/, 'number'],
          'Date object, ISO-8601 string, or a UNIX timestamp');
    default:
      return this.fail('UnkownType', 'Unhandled type ' +
          rules.type + ' for ' + context);
  }
}
```
- example usage
```shell
...
  case 'structure':
    return this.validateStructure(memberRules, param, context);
  case 'list':
    return this.validateList(memberRules, param, context);
  case 'map':
    return this.validateMap(memberRules, param, context);
  default:
    return this.validateScalar(rules, param, context);
}
  },

  validateList: function validateList(rules, params, context) {
this.validateType(context, params, [Array]);

// validate array members
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validateStructure"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateStructure (rules, params, context)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateStructure)
- description and source-code
```javascript
function validateStructure(rules, params, context) {
<span class="apidocCodeCommentSpan">  /*jshint maxcomplexity:12*/
</span>  this.validateType(context, params, ['object'], 'structure');

  /*jshint forin:false*/
  for (var paramName in rules) {
    if (!rules.hasOwnProperty(paramName)) continue;
    var value = params[paramName];
    var notSet = value === undefined || value === null;
    if (notSet) {
      if (rules[paramName].default) {
        params[paramName] = rules[paramName].default;
      }
      else if (rules[paramName].required) {
        this.fail('MissingRequiredParameter',
            'Missing required key \'' + paramName + '\' in ' + context);
      }
    }
    //if (rules[paramName].location == 'uri' && value) {
    //  if (typeof value == 'string' && value.indexOf('/') == 0) {
    //    this.fail('UnexpectedParameter',
    //        'the value of ' + paramName + ' can not start with /');
    //  }
    //}
  }

  // validate hash members
  for (paramName in params) {
    if (!params.hasOwnProperty(paramName)) continue;

    var paramValue = params[paramName],
        paramRules = rules[paramName];

    if (paramRules !== undefined) {
      var memberContext = [context, paramName].join('.');
      this.validateMember(paramRules, paramValue, memberContext);
    } else {
      this.fail('UnexpectedParameter',
          'Unexpected key \'' + paramName + '\' found in ' + context);
    }
  }

  return true;
}
```
- example usage
```shell
...
var cRules = (rules || {}).members || {};
var payload = rules ? rules.xml : null;
if (payload) {
  cRules = ALY.util.merge(cRules, (cRules[payload] || {}).members || {});
  delete cRules[payload];
}

return this.validateStructure(cRules, params || {}, context || 'params');
  },

  validateStructure: function validateStructure(rules, params, context) {
/*jshint maxcomplexity:12*/
this.validateType(context, params, ['object'], 'structure');

/*jshint forin:false*/
...
```

#### <a name="apidoc.element.aliyun-sdk.ParamValidator.prototype.validateType"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.ParamValidator.prototype.</span>validateType (context, value, acceptedTypes, type)](#apidoc.element.aliyun-sdk.ParamValidator.prototype.validateType)
- description and source-code
```javascript
function validateType(context, value, acceptedTypes, type) {
<span class="apidocCodeCommentSpan">  /*jshint maxcomplexity:14*/
</span>  if (value === null || value === undefined) return;

  var foundInvalidType = false;
  for (var i = 0; i < acceptedTypes.length; i++) {
    if (typeof acceptedTypes[i] === 'string') {
      if (typeof value === acceptedTypes[i]) return;
    } else if (acceptedTypes[i] instanceof RegExp) {
      if ((value || '').toString().match(acceptedTypes[i])) return;
    } else {
      if (value instanceof acceptedTypes[i]) return;
      if (ALY.util.isType(value, acceptedTypes[i])) return;
      if (!type && !foundInvalidType) acceptedTypes = acceptedTypes.slice();
      acceptedTypes[i] = ALY.util.typeName(acceptedTypes[i]);
    }
    foundInvalidType = true;
  }

  var acceptedType = type;
  if (!acceptedType) {
    /*jshint regexp:false*/
    acceptedType = acceptedTypes.join(', ').replace(/,([^,]+)$/, ', or$1');
  }

  var vowel = acceptedType.match(/^[aeiou]/i) ? 'n' : '';
  this.fail('InvalidParameterType', 'Expected ' + context + ' to be a' +
      vowel + ' ' + acceptedType);
}
```
- example usage
```shell
...
}

return this.validateStructure(cRules, params || {}, context || 'params');
  },

  validateStructure: function validateStructure(rules, params, context) {
/*jshint maxcomplexity:12*/
this.validateType(context, params, ['object'], 'structure');

/*jshint forin:false*/
for (var paramName in rules) {
  if (!rules.hasOwnProperty(paramName)) continue;
  var value = params[paramName];
  var notSet = value === undefined || value === null;
  if (notSet) {
...
```



# <a name="apidoc.module.aliyun-sdk.QueryParamSerializer"></a>[module aliyun-sdk.QueryParamSerializer](#apidoc.module.aliyun-sdk.QueryParamSerializer)

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer.QueryParamSerializer"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>QueryParamSerializer (rules, options)](#apidoc.element.aliyun-sdk.QueryParamSerializer.QueryParamSerializer)
- description and source-code
```javascript
function QueryParamSerializer(rules, options) {
  this.rules = rules;
  this.timestampFormat = options ? options.timestampFormat : 'iso8601';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.</span>__super__ ()](#apidoc.element.aliyun-sdk.QueryParamSerializer.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.QueryParamSerializer.prototype"></a>[module aliyun-sdk.QueryParamSerializer.prototype](#apidoc.module.aliyun-sdk.QueryParamSerializer.prototype)

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>constructor (rules, options)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.constructor)
- description and source-code
```javascript
function QueryParamSerializer(rules, options) {
  this.rules = rules;
  this.timestampFormat = options ? options.timestampFormat : 'iso8601';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serialize"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serialize (params, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serialize)
- description and source-code
```javascript
function serialize(params, fn) {
  this.serializeStructure('', params, this.rules, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeList"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serializeList (name, list, rules, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeList)
- description and source-code
```javascript
function serializeList(name, list, rules, fn) {
  var that = this;
  var memberRules = rules.members || {};
  ALY.util.arrayEach(list, function (v, n) {
    var suffix = '.' + (n + 1);
    if (rules.flattened) {
      if (memberRules.name) {
        var parts = name.split('.');
        parts.pop();
        parts.push(memberRules.name);
        name = parts.join('.');
      }
    } else {
      suffix = '.member' + suffix;
    }
    that.serializeMember(name + suffix, v, memberRules, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeMap"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serializeMap (name, map, rules, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeMap)
- description and source-code
```javascript
function serialzeMap(name, map, rules, fn) {
  var i = 1;
  var that = this;
  ALY.util.each(map, function (key, value) {
    var prefix = rules.flattened ? '.' : '.entry.';
    var position = prefix + (i++) + '.';
    var keyName = position + (rules.keys.name || 'key');
    var valueName = position + (rules.members.name || 'value');
    that.serializeMember(name + keyName, key, rules.keys, fn);
    that.serializeMember(name + valueName, value, rules.members, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeMember"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serializeMember (name, value, rules, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeMember)
- description and source-code
```javascript
function serializeMember(name, value, rules, fn) {
  if (value === null || value === undefined) return;
  if (rules.type === 'structure') {
    this.serializeStructure(name, value, rules.members, fn);
  } else if (rules.type === 'list') {
    this.serializeList(name, value, rules, fn);
  } else if (rules.type === 'map') {
    this.serializeMap(name, value, rules, fn);
  } else if (rules.type === 'timestamp') {
    var timestampFormat = rules.format || this.timestampFormat;
    fn.call(this, name, ALY.util.date.format(value, timestampFormat));
  } else {
    fn.call(this, name, String(value));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeStructure"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.QueryParamSerializer.prototype.</span>serializeStructure (prefix, struct, rules, fn)](#apidoc.element.aliyun-sdk.QueryParamSerializer.prototype.serializeStructure)
- description and source-code
```javascript
function serializeStructure(prefix, struct, rules, fn) {
  var that = this;
  ALY.util.each(struct, function (name, member) {
    var n = rules[name].name || name;
    var memberName = prefix ? prefix + '.' + n : n;
    that.serializeMember(memberName, member, rules[name], fn);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.RAM"></a>[module aliyun-sdk.RAM](#apidoc.module.aliyun-sdk.RAM)

#### <a name="apidoc.element.aliyun-sdk.RAM.RAM"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>RAM ()](#apidoc.element.aliyun-sdk.RAM.RAM)
- description and source-code
```javascript
RAM = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.RAM.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.RAM.</span>__super__ (config)](#apidoc.element.aliyun-sdk.RAM.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.RAM.prototype"></a>[module aliyun-sdk.RAM.prototype](#apidoc.module.aliyun-sdk.RAM.prototype)

#### <a name="apidoc.element.aliyun-sdk.RAM.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.RAM.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.RAM.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.RDS"></a>[module aliyun-sdk.RDS](#apidoc.module.aliyun-sdk.RDS)

#### <a name="apidoc.element.aliyun-sdk.RDS.RDS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>RDS ()](#apidoc.element.aliyun-sdk.RDS.RDS)
- description and source-code
```javascript
RDS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.RDS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.RDS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.RDS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.RDS.prototype"></a>[module aliyun-sdk.RDS.prototype](#apidoc.module.aliyun-sdk.RDS.prototype)

#### <a name="apidoc.element.aliyun-sdk.RDS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.RDS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.RDS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Request"></a>[module aliyun-sdk.Request](#apidoc.module.aliyun-sdk.Request)

#### <a name="apidoc.element.aliyun-sdk.Request.Request"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Request (service, operation, params)](#apidoc.element.aliyun-sdk.Request.Request)
- description and source-code
```javascript
function Request(service, operation, params) {
  var endpoint = new ALY.Endpoint(service.config.endpoint);
  var region = service.config.region;

  this.service = service;
  this.operation = operation;
  this.params = params || {};
  this.httpRequest = new ALY.HttpRequest(endpoint, region);
  this.startTime = ALY.util.date.getDate();

  this.response = new ALY.Response(this);
  this.restartCount = 0;
  this._asm = new AcceptorStateMachine(fsm.states, 'validate');

  ALY.SequentialExecutor.call(this);
  this.emit = this.emitEvent;
}
```
- example usage
```shell
...
            params[key] = value;
          }
        }
      });
    }
  }

  var request = new ALY.Request(this, operation, params);
  this.addAllRequestListeners(request);

  if (callback) request.send(callback);
  return request;
},

/**
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.</span>__super__ ()](#apidoc.element.aliyun-sdk.Request.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Request.prototype"></a>[module aliyun-sdk.Request.prototype](#apidoc.module.aliyun-sdk.Request.prototype)

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.abort"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>abort ()](#apidoc.element.aliyun-sdk.Request.prototype.abort)
- description and source-code
```javascript
function abort() {
  this.removeAllListeners('validateResponse');
  this.removeAllListeners('extractError');
  this.on('validateResponse', function addAbortedError(resp) {
    resp.error = ALY.util.error(new Error('Request aborted by user'), {
       code: 'RequestAbortedError', retryable: false
    });
  });

  if (this.httpRequest.stream) { // abort HTTP stream
    this.httpRequest.stream.abort();
    this.httpRequest._abortCallback();
  }

  return this;
}
```
- example usage
```shell
...
  this.on('validateResponse', function addAbortedError(resp) {
    resp.error = ALY.util.error(new Error('Request aborted by user'), {
       code: 'RequestAbortedError', retryable: false
    });
  });

  if (this.httpRequest.stream) { // abort HTTP stream
    this.httpRequest.stream.abort();
    this.httpRequest._abortCallback();
  }

  return this;
},

/**
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.addAsyncListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addAsyncListener (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.addAsyncListener)
- description and source-code
```javascript
function onAsync(eventName, listener) {
  listener._isAsync = true;
  return this.on(eventName, listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.addListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addListener (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.addListener)
- description and source-code
```javascript
function on(eventName, listener) {
  if (this._events[eventName]) {
    this._events[eventName].push(listener);
  } else {
    this._events[eventName] = [listener];
  }
  return this;
}
```
- example usage
```shell
...
 *   emitter.addNamedListener('DATA_CALLBACK', 'data', listener);
 *
 *   // the following prints: true
 *   console.log(emitter.DATA_CALLBACK == listener);
 */
addNamedListener: function addNamedListener(name, eventName, callback) {
  this[name] = callback;
  this.addListener(eventName, callback);
  return this;
},

/**
 * @api private
 */
addNamedAsyncListener: function addNamedAsyncListener(name, eventName, callback) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.addListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addListeners (listeners)](#apidoc.element.aliyun-sdk.Request.prototype.addListeners)
- description and source-code
```javascript
function addListeners(listeners) {
  var self = this;

  // extract listeners if parameter is an SequentialExecutor object
  if (listeners._events) listeners = listeners._events;

  ALY.util.each(listeners, function(event, callbacks) {
    if (typeof callbacks === 'function') callbacks = [callbacks];
    ALY.util.arrayEach(callbacks, function(callback) {
      self.on(event, callback);
    });
  });

  return self;
}
```
- example usage
```shell
...
* listeners or SequentialExecutor object.
*
* @param listeners [map<String,Array<Function>>, ALY.SequentialExecutor]
*   a list of events and callbacks, or an event emitter object
*   containing listeners to add to this emitter object.
* @return [ALY.SequentialExecutor] the emitter object, for chaining.
* @example Adding listeners from a map of listeners
*   emitter.addListeners({
*     event1: [function() { ... }, function() { ... }],
*     event2: [function() { ... }]
*   });
*   emitter.emit('event1'); // emitter has event1
*   emitter.emit('event2'); // emitter has event2
* @example Adding listeners from another emitter object
*   var emitter1 = new ALY.SequentialExecutor();
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.addNamedAsyncListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addNamedAsyncListener (name, eventName, callback)](#apidoc.element.aliyun-sdk.Request.prototype.addNamedAsyncListener)
- description and source-code
```javascript
function addNamedAsyncListener(name, eventName, callback) {
  callback._isAsync = true;
  return this.addNamedListener(name, eventName, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.addNamedListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addNamedListener (name, eventName, callback)](#apidoc.element.aliyun-sdk.Request.prototype.addNamedListener)
- description and source-code
```javascript
function addNamedListener(name, eventName, callback) {
  this[name] = callback;
  this.addListener(eventName, callback);
  return this;
}
```
- example usage
```shell
...
 * @param name [String] the property name to set on this object containing
 *   the callback function handle so that the listener can be removed in
 *   the future.
 * @param (see on)
 * @return (see on)
 * @example Adding a named listener DATA_CALLBACK
 *   var listener = function() { doSomething(); };
 *   emitter.addNamedListener('DATA_CALLBACK', 'data', listener);
 *
 *   // the following prints: true
 *   console.log(emitter.DATA_CALLBACK == listener);
 */
addNamedListener: function addNamedListener(name, eventName, callback) {
  this[name] = callback;
  this.addListener(eventName, callback);
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.addNamedListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>addNamedListeners (callback)](#apidoc.element.aliyun-sdk.Request.prototype.addNamedListeners)
- description and source-code
```javascript
function addNamedListeners(callback) {
  var self = this;
  callback(
    function() {
      self.addNamedListener.apply(self, arguments);
    },
    function() {
      self.addNamedAsyncListener.apply(self, arguments);
    }
  );
  return this;
}
```
- example usage
```shell
...
require('./service_interface/top');

ALY.EventListeners = {
  Core: {}
};

ALY.EventListeners = {
  Core: new ALY.SequentialExecutor().addNamedListeners(function(add, addAsync) {

add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.build"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>build (callback)](#apidoc.element.aliyun-sdk.Request.prototype.build)
- description and source-code
```javascript
function build(callback) {
  this._hardError = callback ? false : true;
  return this.runTo('send', callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.callListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>callListeners (listeners, args, doneCallback)](#apidoc.element.aliyun-sdk.Request.prototype.callListeners)
- description and source-code
```javascript
function callListeners(listeners, args, doneCallback) {
  if (listeners.length === 0) {
    doneCallback.call(this);
    if (domain && this.domain instanceof domain.Domain)
      this.domain.exit();
  } else {
    var listener = listeners.shift();
    if (listener._isAsync) {

      // asynchronous listener
      var callNextListener = function(err) {
        if (err) {
          doneCallback.call(this, err);
          if (domain && this.domain instanceof domain.Domain)
            this.domain.exit();
        } else {
          this.callListeners(listeners, args, doneCallback);
        }
      }.bind(this);
      listener.apply(this, args.concat([callNextListener]));

    } else {

      // synchronous listener
      try {
        listener.apply(this, args);
        this.callListeners(listeners, args, doneCallback);
      } catch (err) {
        doneCallback.call(this, err);
        if (domain && this.domain instanceof domain.Domain)
          this.domain.exit();
      }

    }
  }
}
```
- example usage
```shell
...
    this.domain.enter();

  if(process.env.DEBUG == 'aliyun') {
    console.log('emit', eventName);
  }
  var listeners = this.listeners(eventName);
  var count = listeners.length;
  this.callListeners(listeners, eventArgs, doneCallback);
  return count > 0;
},

/**
 * @api private
 */
callListeners: function callListeners(listeners, args, doneCallback) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>constructor (service, operation, params)](#apidoc.element.aliyun-sdk.Request.prototype.constructor)
- description and source-code
```javascript
function Request(service, operation, params) {
  var endpoint = new ALY.Endpoint(service.config.endpoint);
  var region = service.config.region;

  this.service = service;
  this.operation = operation;
  this.params = params || {};
  this.httpRequest = new ALY.HttpRequest(endpoint, region);
  this.startTime = ALY.util.date.getDate();

  this.response = new ALY.Response(this);
  this.restartCount = 0;
  this._asm = new AcceptorStateMachine(fsm.states, 'validate');

  ALY.SequentialExecutor.call(this);
  this.emit = this.emitEvent;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.createReadStream"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>createReadStream ()](#apidoc.element.aliyun-sdk.Request.prototype.createReadStream)
- description and source-code
```javascript
function createReadStream() {
  var streams = require('stream');
  var req = this;
  var stream = null;
  var legacyStreams = false;

  if (ALY.HttpClient.streamsApiVersion === 2) {
    stream = new streams.Readable();
    stream._read = function() { stream.push(''); };
  } else {
    stream = new streams.Stream();
    stream.readable = true;
  }

  stream.sent = false;
  stream.on('newListener', function(event) {
    if (!stream.sent && (event === 'data' || event === 'readable')) {
      if (event === 'data') legacyStreams = true;
      stream.sent = true;
      process.nextTick(function() { req.send(function() { }); });
    }
  });

  this.on('httpHeaders', function streamHeaders(statusCode, headers, resp) {
    if (statusCode < 300) {
      this.httpRequest._streaming = true;

      req.removeListener('httpData', ALY.EventListeners.Core.HTTP_DATA);
      req.removeListener('httpError', ALY.EventListeners.Core.HTTP_ERROR);
      req.on('httpError', function streamHttpError(error, resp) {
        resp.error = error;
        resp.error.retryable = false;
      });

      var httpStream = resp.httpResponse.stream;
      stream.response = resp;
      stream._read = function() {
        var data;
<span class="apidocCodeCommentSpan">        /*jshint boss:true*/
</span>        while (data = httpStream.read()) {
          stream.push(data);
        }
        stream.push('');
      };

      var events = ['end', 'error', (legacyStreams ? 'data' : 'readable')];
      ALY.util.arrayEach(events, function(event) {
        httpStream.on(event, function(arg) {
          stream.emit(event, arg);
        });
      });
    }
  });

  this.on('error', function(err) {
    stream.emit('error', err);
  });

  return stream;
}
```
- example usage
```shell
...
  /**
* Converts the request object into a readable stream that
* can be read from or piped into a writable stream.
*
* @note The data read from a readable stream contains only
*   the raw HTTP body contents.
* @example Manually reading from a stream
*   request.createReadStream().on('data', function(data) {
*     console.log("Got data:", data.toString());
*   });
* @example Piping a request body into a file
*   var out = fs.createWriteStream('/path/to/outfile.jpg');
*   s3.service.getObject(params).createReadStream().pipe(out);
* @return [Stream] the readable stream object that can be piped
*   or read from (by registering 'data' event listeners).
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.eachItem"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>eachItem (callback)](#apidoc.element.aliyun-sdk.Request.prototype.eachItem)
- description and source-code
```javascript
function eachItem(callback) {
  function wrappedCallback(err, data) {
    if (err) return callback(err, null);
    if (data === null) return callback(null, null);

    var config = this.request.service.paginationConfig(this.request.operation);
    var resultKey = config.resultKey;
    if (Array.isArray(resultKey)) resultKey = resultKey[0];
    var results = ALY.util.jamespath.query(resultKey, data);
    ALY.util.arrayEach(results, function(result) {
      ALY.util.arrayEach(result, function(item) { callback(null, item); });
    });
  }

  this.eachPage(wrappedCallback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.eachPage"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>eachPage (callback)](#apidoc.element.aliyun-sdk.Request.prototype.eachPage)
- description and source-code
```javascript
function eachPage(callback) {
  function wrappedCallback(response) {
    var result = callback.call(response, response.error, response.data);
    if (result === false) return;

    if (response.hasNextPage()) {
      response.nextPage().on('complete', wrappedCallback).send();
    } else {
      callback.call(response, null, null);
    }
  }

  this.on('complete', wrappedCallback).send();
}
```
- example usage
```shell
...
* Iterates over each page of results given a pageable request, calling
* the provided callback with each page of data. After all pages have been
* retrieved, the callback is called with 'null' data.
*
* @note This operation can generate multiple requests to a service.
* @example Iterating over multiple pages of objects in an S3 bucket
*   var pages = 1;
*   s3.listObjects().eachPage(function(err, data) {
*     if (err) return;
*     console.log("Page", pages++);
*     console.log(data);
*   });
* @callback callback function(err, data)
*   Called with each page of resulting data from the request.
*
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.emit"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>emit (eventName, eventArgs, doneCallback)](#apidoc.element.aliyun-sdk.Request.prototype.emit)
- description and source-code
```javascript
function emit(eventName, eventArgs, doneCallback) {
  if (!doneCallback) doneCallback = this.unhandledErrorCallback;
  if (domain && this.domain instanceof domain.Domain)
    this.domain.enter();

  if(process.env.DEBUG == 'aliyun') {
    console.log('emit', eventName);
  }
  var listeners = this.listeners(eventName);
  var count = listeners.length;
  this.callListeners(listeners, eventArgs, doneCallback);
  return count > 0;
}
```
- example usage
```shell
...

    addAsync('SEND', 'send', function SEND(resp, done) {
      function callback(httpResp) {
        resp.httpResponse.stream = httpResp;
        resp.httpResponse._abortCallback = done;

        httpResp.on('headers', function onHeaders(statusCode, headers) {
resp.request.emit('httpHeaders', [statusCode, headers, resp]);

if (!resp.request.httpRequest._streaming) {
  if (ALY.HttpClient.streamsApiVersion === 2) { // streams2 API check
    httpResp.on('readable', function onReadable() {
      var data = httpResp.read();
      if (data !== null) {
        resp.request.emit('httpData', [data, resp]);
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.emitEvent"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>emitEvent (eventName, args, done)](#apidoc.element.aliyun-sdk.Request.prototype.emitEvent)
- description and source-code
```javascript
function emit(eventName, args, done) {
  if (typeof args === 'function') { done = args; args = null; }
  if (!done) done = this.unhandledErrorCallback;
  if (!args) args = this.eventParameters(eventName, this.response);

  var origEmit = ALY.SequentialExecutor.prototype.emit;
  origEmit.call(this, eventName, args, function (err) {
    if (err) this.response.error = err;
    done.call(this, err);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.eventParameters"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>eventParameters (eventName)](#apidoc.element.aliyun-sdk.Request.prototype.eventParameters)
- description and source-code
```javascript
function eventParameters(eventName) {
  switch (eventName) {
    case 'validate':
    case 'sign':
    case 'build':
    case 'afterBuild':
      return [this];
    case 'error':
      return [this.response.error, this.response];
    default:
      return [this.response];
  }
}
```
- example usage
```shell
...
 * @param [Array,Response] args This should be the response object,
 *   or an array of args to send to the event.
 * @api private
 */
emitEvent: function emit(eventName, args, done) {
  if (typeof args === 'function') { done = args; args = null; }
  if (!done) done = this.unhandledErrorCallback;
  if (!args) args = this.eventParameters(eventName, this.response);

  var origEmit = ALY.SequentialExecutor.prototype.emit;
  origEmit.call(this, eventName, args, function (err) {
    if (err) this.response.error = err;
    done.call(this, err);
  });
},
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.isPageable"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>isPageable ()](#apidoc.element.aliyun-sdk.Request.prototype.isPageable)
- description and source-code
```javascript
function isPageable() {
  return this.service.paginationConfig(this.operation) ? true : false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.listeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>listeners (eventName)](#apidoc.element.aliyun-sdk.Request.prototype.listeners)
- description and source-code
```javascript
function listeners(eventName) {
  return this._events[eventName] ? this._events[eventName].slice(0) : [];
}
```
- example usage
```shell
...
  if (!doneCallback) doneCallback = this.unhandledErrorCallback;
  if (domain && this.domain instanceof domain.Domain)
    this.domain.enter();

  if(process.env.DEBUG == 'aliyun') {
    console.log('emit', eventName);
  }
  var listeners = this.listeners(eventName);
  var count = listeners.length;
  this.callListeners(listeners, eventArgs, doneCallback);
  return count > 0;
},

/**
 * @api private
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.on"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>on (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.on)
- description and source-code
```javascript
function on(eventName, listener) {
  if (this._events[eventName]) {
    this._events[eventName].push(listener);
  } else {
    this._events[eventName] = [listener];
  }
  return this;
}
```
- example usage
```shell
...
    });

    addAsync('SEND', 'send', function SEND(resp, done) {
      function callback(httpResp) {
        resp.httpResponse.stream = httpResp;
        resp.httpResponse._abortCallback = done;

        httpResp.on('headers', function onHeaders(statusCode, headers) {
resp.request.emit('httpHeaders', [statusCode, headers, resp]);

if (!resp.request.httpRequest._streaming) {
  if (ALY.HttpClient.streamsApiVersion === 2) { // streams2 API check
    httpResp.on('readable', function onReadable() {
      var data = httpResp.read();
      if (data !== null) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.onAsync"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>onAsync (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.onAsync)
- description and source-code
```javascript
function onAsync(eventName, listener) {
  listener._isAsync = true;
  return this.on(eventName, listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>removeAllListeners (eventName)](#apidoc.element.aliyun-sdk.Request.prototype.removeAllListeners)
- description and source-code
```javascript
function removeAllListeners(eventName) {
  if (eventName) {
    delete this._events[eventName];
  } else {
    this._events = {};
  }
  return this;
}
```
- example usage
```shell
...
 *   setTimeout(request.abort.bind(request), 1000);
 *
 *   // prints "Error: RequestAbortedError Request aborted by user"
 * @return [ALY.Request] the same request object, for chaining.
 * @since v1.4.0
 */
abort: function abort() {
  this.removeAllListeners('validateResponse');
  this.removeAllListeners('extractError');
  this.on('validateResponse', function addAbortedError(resp) {
    resp.error = ALY.util.error(new Error('Request aborted by user'), {
       code: 'RequestAbortedError', retryable: false
    });
  });
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.removeListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>removeListener (eventName, listener)](#apidoc.element.aliyun-sdk.Request.prototype.removeListener)
- description and source-code
```javascript
function removeListener(eventName, listener) {
  var listeners = this._events[eventName];
  if (listeners) {
    var length = listeners.length;
    var position = -1;
    for (var i = 0; i < length; ++i) {
      if (listeners[i] === listener) {
        position = i;
      }
    }
    if (position > -1) {
      listeners.splice(position, 1);
    }
  }
  return this;
}
```
- example usage
```shell
...
      }
    });

    this.on('httpHeaders', function streamHeaders(statusCode, headers, resp) {
      if (statusCode < 300) {
this.httpRequest._streaming = true;

req.removeListener('httpData', ALY.EventListeners.Core.HTTP_DATA);
req.removeListener('httpError', ALY.EventListeners.Core.HTTP_ERROR);
req.on('httpError', function streamHttpError(error, resp) {
  resp.error = error;
  resp.error.retryable = false;
});

var httpStream = resp.httpResponse.stream;
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.runTo"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>runTo (state, done)](#apidoc.element.aliyun-sdk.Request.prototype.runTo)
- description and source-code
```javascript
function runTo(state, done) {
  this._asm.runTo(state, done, this);
  return this;
}
```
- example usage
```shell
...
  } else {
    if (bindObject.logger) bindObject.logger.log(self.currentState, '->', state.accept);
    if (state.accept) self.currentState = state.accept;
    else return done ? done() : null;
  }
  if (self.currentState === finalState) return done ? done(err) : null;

  self.runTo(finalState, done, bindObject, err);
});
};

AcceptorStateMachine.prototype.addState = function addState(name, acceptState, failState, fn) {
if (typeof acceptState === 'function') {
  fn = acceptState; acceptState = null; failState = null;
} else if (typeof failState === 'function') {
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.send"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>send (callback)](#apidoc.element.aliyun-sdk.Request.prototype.send)
- description and source-code
```javascript
function send(callback) {
  if (callback) {
    this.on('complete', function (resp) {
      try {
        callback.call(resp, resp.error, resp.data);
      } catch (e) {
        resp.request._hardError = true;
        throw e;
      }
    });
  }
  this.runTo();

  return this.response;
}
```
- example usage
```shell
...
 *     from the service.
 *     @param err [Error] the error object returned from the request.
 *       Set to 'null' if the request is successful.
 *     @param data [Object] the de-serialized data returned from
 *       the request. Set to 'null' if a request error occurs.
 *   @example Sending a request with a callback
 *     request = s3.putObject({Bucket: 'bucket', Key: 'key'});
 *     request.send(function(err, data) { console.log(err, data); });
 *   @example Sending a request with no callback (using event handlers)
 *     request = s3.putObject({Bucket: 'bucket', Key: 'key'});
 *     request.on('complete', function(response) { ... }); // register a callback
 *     request.send();
 */
send: function send(callback) {
  if (callback) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Request.prototype.unhandledErrorCallback"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Request.prototype.</span>unhandledErrorCallback (err)](#apidoc.element.aliyun-sdk.Request.prototype.unhandledErrorCallback)
- description and source-code
```javascript
function unhandledErrorCallback(err) {
  if (err) {
    if (domain && this.domain instanceof domain.Domain) {
      err.domainEmitter = this;
      err.domain = this.domain;
      err.domainThrown = false;
      this.domain.emit('error', err);
    } else {
      throw err;
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Response"></a>[module aliyun-sdk.Response](#apidoc.module.aliyun-sdk.Response)

#### <a name="apidoc.element.aliyun-sdk.Response.Response"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Response (request)](#apidoc.element.aliyun-sdk.Response.Response)
- description and source-code
```javascript
function Response(request) {
  this.request = request;
  this.data = null;
  this.error = null;
  this.retryCount = 0;
  this.redirectCount = 0;
  this.httpResponse = new ALY.HttpResponse();
}
```
- example usage
```shell
...

  this.service = service;
  this.operation = operation;
  this.params = params || {};
  this.httpRequest = new ALY.HttpRequest(endpoint, region);
  this.startTime = ALY.util.date.getDate();

  this.response = new ALY.Response(this);
  this.restartCount = 0;
  this._asm = new AcceptorStateMachine(fsm.states, 'validate');

  ALY.SequentialExecutor.call(this);
  this.emit = this.emitEvent;
},
...
```

#### <a name="apidoc.element.aliyun-sdk.Response.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Response.</span>__super__ ()](#apidoc.element.aliyun-sdk.Response.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Response.prototype"></a>[module aliyun-sdk.Response.prototype](#apidoc.module.aliyun-sdk.Response.prototype)

#### <a name="apidoc.element.aliyun-sdk.Response.prototype.cacheNextPageTokens"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Response.prototype.</span>cacheNextPageTokens ()](#apidoc.element.aliyun-sdk.Response.prototype.cacheNextPageTokens)
- description and source-code
```javascript
function cacheNextPageTokens() {
  if (this.hasOwnProperty('nextPageTokens')) return this.nextPageTokens;
  this.nextPageTokens = undefined;

  var config = this.request.service.paginationConfig(this.request.operation);
  if (!config) return this.nextPageTokens;

  this.nextPageTokens = null;
  if (config.moreResults) {
    if (!ALY.util.jamespath.find(config.moreResults, this.data)) {
      return this.nextPageTokens;
    }
  }

  var exprs = config.outputToken;
  if (typeof exprs === 'string') exprs = [exprs];
  ALY.util.arrayEach.call(this, exprs, function (expr) {
    var output = ALY.util.jamespath.find(expr, this.data);
    if (output) {
      this.nextPageTokens = this.nextPageTokens || [];
      this.nextPageTokens.push(output);
    }
  });

  return this.nextPageTokens;
}
```
- example usage
```shell
...
/**
 * @return [Boolean] whether more pages of data can be returned by further
 *   requests
 * @api experimental
 * @since v1.4.0
 */
hasNextPage: function hasNextPage() {
  this.cacheNextPageTokens();
  if (this.nextPageTokens) return true;
  if (this.nextPageTokens === undefined) return undefined;
  else return false;
},

/**
 * @api private
...
```

#### <a name="apidoc.element.aliyun-sdk.Response.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Response.prototype.</span>constructor (request)](#apidoc.element.aliyun-sdk.Response.prototype.constructor)
- description and source-code
```javascript
function Response(request) {
  this.request = request;
  this.data = null;
  this.error = null;
  this.retryCount = 0;
  this.redirectCount = 0;
  this.httpResponse = new ALY.HttpResponse();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Response.prototype.hasNextPage"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Response.prototype.</span>hasNextPage ()](#apidoc.element.aliyun-sdk.Response.prototype.hasNextPage)
- description and source-code
```javascript
function hasNextPage() {
  this.cacheNextPageTokens();
  if (this.nextPageTokens) return true;
  if (this.nextPageTokens === undefined) return undefined;
  else return false;
}
```
- example usage
```shell
...
   * @since v1.4.0
   */
  eachPage: function eachPage(callback) {
function wrappedCallback(response) {
  var result = callback.call(response, response.error, response.data);
  if (result === false) return;

  if (response.hasNextPage()) {
    response.nextPage().on('complete', wrappedCallback).send();
  } else {
    callback.call(response, null, null);
  }
}

this.on('complete', wrappedCallback).send();
...
```

#### <a name="apidoc.element.aliyun-sdk.Response.prototype.nextPage"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Response.prototype.</span>nextPage (callback)](#apidoc.element.aliyun-sdk.Response.prototype.nextPage)
- description and source-code
```javascript
function nextPage(callback) {
  var config;
  var service = this.request.service;
  var operation = this.request.operation;
  try {
    config = service.paginationConfig(operation, true);
  } catch (e) { this.error = e; }

  if (!this.hasNextPage()) {
    if (callback) callback(this.error, null);
    else if (this.error) throw this.error;
    return null;
  }

  var params = ALY.util.copy(this.request.params);
  if (!this.nextPageTokens) {
    return callback ? callback(null, null) : null;
  } else {
    var inputTokens = config.inputToken;
    if (typeof inputTokens === 'string') inputTokens = [inputTokens];
    for (var i = 0; i < inputTokens.length; i++) {
      params[inputTokens[i]] = this.nextPageTokens[i];
    }
    return service.makeRequest(this.request.operation, params, callback);
  }
}
```
- example usage
```shell
...
 */
eachPage: function eachPage(callback) {
  function wrappedCallback(response) {
    var result = callback.call(response, response.error, response.data);
    if (result === false) return;

    if (response.hasNextPage()) {
      response.nextPage().on('complete', wrappedCallback).send();
    } else {
      callback.call(response, null, null);
    }
  }

  this.on('complete', wrappedCallback).send();
},
...
```



# <a name="apidoc.module.aliyun-sdk.SLB"></a>[module aliyun-sdk.SLB](#apidoc.module.aliyun-sdk.SLB)

#### <a name="apidoc.element.aliyun-sdk.SLB.SLB"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>SLB ()](#apidoc.element.aliyun-sdk.SLB.SLB)
- description and source-code
```javascript
SLB = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLB.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLB.</span>__super__ (config)](#apidoc.element.aliyun-sdk.SLB.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.SLB.prototype"></a>[module aliyun-sdk.SLB.prototype](#apidoc.module.aliyun-sdk.SLB.prototype)

#### <a name="apidoc.element.aliyun-sdk.SLB.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLB.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.SLB.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.SLS"></a>[module aliyun-sdk.SLS](#apidoc.module.aliyun-sdk.SLS)

#### <a name="apidoc.element.aliyun-sdk.SLS.SLS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>SLS ()](#apidoc.element.aliyun-sdk.SLS.SLS)
- description and source-code
```javascript
SLS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.SLS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.SLS.prototype"></a>[module aliyun-sdk.SLS.prototype](#apidoc.module.aliyun-sdk.SLS.prototype)

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.addContentType"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>addContentType (req)](#apidoc.element.aliyun-sdk.SLS.prototype.addContentType)
- description and source-code
```javascript
function addContentType(req) {
  var httpRequest = req.httpRequest;
  var headers = httpRequest.headers;

  headers['x-log-signaturemethod'] = 'hmac-sha1';
  headers['x-log-apiversion'] = '0.6.0';
  headers['x-log-bodyrawsize'] = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.buildContent"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>buildContent (req, done)](#apidoc.element.aliyun-sdk.SLS.prototype.buildContent)
- description and source-code
```javascript
function addContentType(req, done) {
  var httpRequest = req.httpRequest;
  var headers = httpRequest.headers;

  if(req.operation === 'putLogs'){

    headers['Content-Type'] = 'application/x-protobuf';
    headers['x-log-compresstype'] = 'deflate';

    var protoBufferEncode = function(name, json) {
      po_protobuf.init({
        encoderProtos: protos,
        decoderProtos: protos
      });
      return po_protobuf.encode(name, json);
    };

    var deflate = function(pb, fn){
      zlib.deflate(pb, function(err, buf) {
        fn(err, buf);
      });
    };


    var logGroup = JSON.parse(req.httpRequest.body);


    if(!logGroup.logs){
      throw ALY.util.error(new Error(), {
        code: 'ContentError', message: 'Logitems is empty.', retryable: false
      });
    }
    if(logGroup.logs.length>4096){
      throw ALY.util.error(new Error(), {
        code: 'ContentError', message: 'Logitems length exceed 4096.', retryable: false
      });
    }


    var pb = protoBufferEncode('LogGroup', logGroup);

    if(pb.length>3*1024*1024){
      throw ALY.util.error(new Error(), {
        code: 'ContentError', message: 'Logitems size exceed 5MB', retryable: false
      });
    }

    httpRequest.headers['x-log-bodyrawsize'] = pb.length;

    deflate(pb, function(err, buf) {
      if(err){
        throw ALY.util.error(new Error(), {
          code: 'ContentError', message: err.message, retryable: false
        });
      }
      else{
        req.httpRequest.body = buf;
        done();
      }
    });

  }
  else if (req.operation == "batchGetLogs")
  {
      headers["Accept"] = "application/x-protobuf";
      headers["Accept-Encoding"] = "";
      done();
  }
  else{
      if(req.httpRequest.body != null && req.httpRequest.body != "")
          headers['Content-Type'] = 'application/json';
    done();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.computeContentMd5"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>computeContentMd5 (req)](#apidoc.element.aliyun-sdk.SLS.prototype.computeContentMd5)
- description and source-code
```javascript
function computeContentMd5(req) {
  if (req.service.willComputeChecksums(req)) {
    var md5 = ALY.util.crypto.md5(req.httpRequest.body, 'hex').toUpperCase();
    req.httpRequest.headers['Content-MD5'] = md5;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.computeSha256"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>computeSha256 (req)](#apidoc.element.aliyun-sdk.SLS.prototype.computeSha256)
- description and source-code
```javascript
function computeSha256(req) {
  if (req.service.getSignerClass(req) === ALY.Signers.V4) {
    req.httpRequest.headers['X-Amz-Content-Sha256'] =
        ALY.util.crypto.sha256(req.httpRequest.body || '', 'hex');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.SLS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.escapePathParam"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>escapePathParam (value)](#apidoc.element.aliyun-sdk.SLS.prototype.escapePathParam)
- description and source-code
```javascript
function escapePathParam(value) {
  return ALY.util.uriEscapePath(String(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.extractData"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>extractData (resp)](#apidoc.element.aliyun-sdk.SLS.prototype.extractData)
- description and source-code
```javascript
function extractData(resp) {
  //去掉RequestId
  delete resp.data.RequestId;
  var body =  resp.data;
  resp.data = {};
  var reqId = resp.httpResponse.headers['x-log-requestid'];
  if (reqId) {
      resp.data.request_id = reqId;
  }
  resp.data.headers = resp.httpResponse.headers;

  var protoBufferDecode= function(name, data) {
              po_protobuf.init({
                encoderProtos: protos,
                decoderProtos: protos
              });
              return po_protobuf.decode(name, data);
            };

   if (resp.httpResponse.headers['x-log-compresstype'] == "deflate")
   {
       if(body.logGroupListBuf != null)
       {
           uncompressed = zlib.inflateSync(body.logGroupListBuf);
       }
       else
       {
           uncompressed = resp.data.logGroupListBuf;
       }
       var pb = protoBufferDecode("LogGroupList",uncompressed);
       resp.data.body = pb;
   }
   else
   {
       if(resp.data.headers['content-type']== 'application/x-protobuf')
       {
           var pb = protoBufferDecode("LogGroupList",body.logGroupListBuf);
           resp.data.body = pb;
       }
       else
           resp.data.body = body;
   }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.extractError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>extractError (resp)](#apidoc.element.aliyun-sdk.SLS.prototype.extractError)
- description and source-code
```javascript
function extractError(resp) {
  var headers = resp.httpResponse.headers;

  var body = resp.httpResponse.body;
  var error = body.toString();

  try{
    error = JSON.parse(error);
  }catch(e){
    error = {};
  }

  error = ALY.util.update(error, {
    request_id : headers['x-log-requestid'] || null,
    code: resp.httpResponse.statusCode,
    message: body.toString(),
    headers: headers
  });

  resp.error = ALY.util.error(new Error(), error);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.initialize"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>initialize (options)](#apidoc.element.aliyun-sdk.SLS.prototype.initialize)
- description and source-code
```javascript
function initialize(options) {
  ALY.Service.prototype.initialize.call(this, options);
}
```
- example usage
```shell
...
constructor: function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
...
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.populateURI"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>populateURI (req)](#apidoc.element.aliyun-sdk.SLS.prototype.populateURI)
- description and source-code
```javascript
function populateURI(req) {
  var hostname = req.httpRequest.endpoint.hostname;

  var projectName = req.params['projectName'];
  var host = projectName+'.'+ hostname;


  if(!/^[0-9.]+$/.test(hostname)){
    //不是ip,  是域名, 则需要拼接project名
    var protocol = req.httpRequest.endpoint.protocol;
    var port = req.httpRequest.endpoint.port;

    //real endpoint
    var endpointObj = parseURL(protocol+'//'+host+':'+port);

    ALY.util.update(req.httpRequest, {endpoint: endpointObj });
    // ALY.util.update(req.service, {endpoint: endpointObj });
  }

  //final host， 不管是ip还是域名，都要拼接project名
  req.httpRequest.headers['Host'] = host;

  //头中的 projectName 不需要
  delete req.httpRequest.headers['projectName'];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.retryableError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>retryableError (error, request)](#apidoc.element.aliyun-sdk.SLS.prototype.retryableError)
- description and source-code
```javascript
function retryableError(error, request) {

  var _super = ALY.Service.prototype.retryableError;
  return _super.call(this, error, request);

}
```
- example usage
```shell
...
    delete resp.httpResponse.buffers;
  });

  add('FINALIZE_ERROR', 'retry', function FINALIZE_ERROR(resp) {
    if (resp.httpResponse.statusCode) {
      resp.error.statusCode = resp.httpResponse.statusCode;
      if (resp.error.retryable === undefined) {
        resp.error.retryable = this.service.retryableError(resp.error, this);
      }
    }
  });

}),

Logger: new ALY.SequentialExecutor().addNamedListeners(function(add) {
...
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.setupRequestListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>setupRequestListeners (request)](#apidoc.element.aliyun-sdk.SLS.prototype.setupRequestListeners)
- description and source-code
```javascript
function setupRequestListeners(request) {

  request.addListener('build', this.addContentType);
  request.addAsyncListener('build', this.buildContent);
  request.addListener('build', this.populateURI);

  request.addListener('build', this.computeContentMd5);
  request.addListener('build', this.computeSha256);

  request.removeListener('validate',
      ALY.EventListeners.Core.VALIDATE_REGION);

  request.addListener('extractError', this.extractError);
  request.addListener('extractData', this.extractData);

  //request.addListener('afterBuild', function (req) {
  //    //Host in request.header
  //    console.log(req.httpRequest.headers['projectName'], req.params['projectName']);
  //
  //    req.httpRequest.headers['Host'] = req.params['projectName']
  //       +'.'+req.httpRequest.endpoint.hostname;
  //    //头中的 projectName 不需要
  //    delete req.httpRequest.headers['projectName'];
  //});

}
```
- example usage
```shell
...
      ALY.EventListeners.Core.VALIDATE_PARAMETERS);
  }

  if (this.config.logger) { // add logging events
    request.addListeners(ALY.EventListeners.Logger);
  }

  this.setupRequestListeners(request);
},

/**
 * Override this method to setup any custom request listeners for each
 * new request to the service.
 *
 * @abstract
...
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.successfulResponse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.SLS.prototype.successfulResponse)
- description and source-code
```javascript
function successfulResponse(resp) {
  //var req = resp.request;
  var httpResponse = resp.httpResponse;
  return httpResponse.statusCode < 300;
}
```
- example usage
```shell
...
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
  if (this.service.successfulResponse(resp, this)) {
    resp.data = {};
    resp.error = null;
  } else {
    resp.data = null;
    resp.error = ALY.util.error(new Error(),
      {code: 'UnknownError', message: 'An unknown error occurred.'});
  }
...
```

#### <a name="apidoc.element.aliyun-sdk.SLS.prototype.willComputeChecksums"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SLS.prototype.</span>willComputeChecksums (req)](#apidoc.element.aliyun-sdk.SLS.prototype.willComputeChecksums)
- description and source-code
```javascript
function willComputeChecksums(req) {

  // // TODO: compute checksums for Stream objects
  // if (!ALY.util.Buffer.isBuffer(req.httpRequest.body) &&
  //     typeof req.httpRequest.body !== 'string') {
  //     return false;
  // }

  var rules = req.service.api.operations[req.operation].input;

  // // V4 signer uses SHA256 signatures so only compute MD5 if it is required
  // if (req.service.getSignerClass(req) === ALY.Signers.V4) {
  //     if (rules.ContentMD5 && !rules.ContentMD5.required) return false;
  // }

  if (rules.ContentMD5) return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.STS"></a>[module aliyun-sdk.STS](#apidoc.module.aliyun-sdk.STS)

#### <a name="apidoc.element.aliyun-sdk.STS.STS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>STS ()](#apidoc.element.aliyun-sdk.STS.STS)
- description and source-code
```javascript
STS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.STS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.STS.</span>__super__ (config)](#apidoc.element.aliyun-sdk.STS.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.STS.prototype"></a>[module aliyun-sdk.STS.prototype](#apidoc.module.aliyun-sdk.STS.prototype)

#### <a name="apidoc.element.aliyun-sdk.STS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.STS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.STS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.SequentialExecutor"></a>[module aliyun-sdk.SequentialExecutor](#apidoc.module.aliyun-sdk.SequentialExecutor)

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.SequentialExecutor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>SequentialExecutor ()](#apidoc.element.aliyun-sdk.SequentialExecutor.SequentialExecutor)
- description and source-code
```javascript
function SequentialExecutor() {
  this.domain = domain && domain.active;
  this._events = {};
}
```
- example usage
```shell
...
require('./service_interface/top');

ALY.EventListeners = {
  Core: {}
};

ALY.EventListeners = {
  Core: new ALY.SequentialExecutor().addNamedListeners(function(add, addAsync) {

add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.</span>__super__ ()](#apidoc.element.aliyun-sdk.SequentialExecutor.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.SequentialExecutor.prototype"></a>[module aliyun-sdk.SequentialExecutor.prototype](#apidoc.module.aliyun-sdk.SequentialExecutor.prototype)

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addAsyncListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addAsyncListener (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addAsyncListener)
- description and source-code
```javascript
function onAsync(eventName, listener) {
  listener._isAsync = true;
  return this.on(eventName, listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addListener (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addListener)
- description and source-code
```javascript
function on(eventName, listener) {
  if (this._events[eventName]) {
    this._events[eventName].push(listener);
  } else {
    this._events[eventName] = [listener];
  }
  return this;
}
```
- example usage
```shell
...
 *   emitter.addNamedListener('DATA_CALLBACK', 'data', listener);
 *
 *   // the following prints: true
 *   console.log(emitter.DATA_CALLBACK == listener);
 */
addNamedListener: function addNamedListener(name, eventName, callback) {
  this[name] = callback;
  this.addListener(eventName, callback);
  return this;
},

/**
 * @api private
 */
addNamedAsyncListener: function addNamedAsyncListener(name, eventName, callback) {
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addListeners (listeners)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addListeners)
- description and source-code
```javascript
function addListeners(listeners) {
  var self = this;

  // extract listeners if parameter is an SequentialExecutor object
  if (listeners._events) listeners = listeners._events;

  ALY.util.each(listeners, function(event, callbacks) {
    if (typeof callbacks === 'function') callbacks = [callbacks];
    ALY.util.arrayEach(callbacks, function(callback) {
      self.on(event, callback);
    });
  });

  return self;
}
```
- example usage
```shell
...
* listeners or SequentialExecutor object.
*
* @param listeners [map<String,Array<Function>>, ALY.SequentialExecutor]
*   a list of events and callbacks, or an event emitter object
*   containing listeners to add to this emitter object.
* @return [ALY.SequentialExecutor] the emitter object, for chaining.
* @example Adding listeners from a map of listeners
*   emitter.addListeners({
*     event1: [function() { ... }, function() { ... }],
*     event2: [function() { ... }]
*   });
*   emitter.emit('event1'); // emitter has event1
*   emitter.emit('event2'); // emitter has event2
* @example Adding listeners from another emitter object
*   var emitter1 = new ALY.SequentialExecutor();
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedAsyncListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addNamedAsyncListener (name, eventName, callback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedAsyncListener)
- description and source-code
```javascript
function addNamedAsyncListener(name, eventName, callback) {
  callback._isAsync = true;
  return this.addNamedListener(name, eventName, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addNamedListener (name, eventName, callback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedListener)
- description and source-code
```javascript
function addNamedListener(name, eventName, callback) {
  this[name] = callback;
  this.addListener(eventName, callback);
  return this;
}
```
- example usage
```shell
...
 * @param name [String] the property name to set on this object containing
 *   the callback function handle so that the listener can be removed in
 *   the future.
 * @param (see on)
 * @return (see on)
 * @example Adding a named listener DATA_CALLBACK
 *   var listener = function() { doSomething(); };
 *   emitter.addNamedListener('DATA_CALLBACK', 'data', listener);
 *
 *   // the following prints: true
 *   console.log(emitter.DATA_CALLBACK == listener);
 */
addNamedListener: function addNamedListener(name, eventName, callback) {
  this[name] = callback;
  this.addListener(eventName, callback);
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>addNamedListeners (callback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.addNamedListeners)
- description and source-code
```javascript
function addNamedListeners(callback) {
  var self = this;
  callback(
    function() {
      self.addNamedListener.apply(self, arguments);
    },
    function() {
      self.addNamedAsyncListener.apply(self, arguments);
    }
  );
  return this;
}
```
- example usage
```shell
...
require('./service_interface/top');

ALY.EventListeners = {
  Core: {}
};

ALY.EventListeners = {
  Core: new ALY.SequentialExecutor().addNamedListeners(function(add, addAsync) {

add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.callListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>callListeners (listeners, args, doneCallback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.callListeners)
- description and source-code
```javascript
function callListeners(listeners, args, doneCallback) {
  if (listeners.length === 0) {
    doneCallback.call(this);
    if (domain && this.domain instanceof domain.Domain)
      this.domain.exit();
  } else {
    var listener = listeners.shift();
    if (listener._isAsync) {

      // asynchronous listener
      var callNextListener = function(err) {
        if (err) {
          doneCallback.call(this, err);
          if (domain && this.domain instanceof domain.Domain)
            this.domain.exit();
        } else {
          this.callListeners(listeners, args, doneCallback);
        }
      }.bind(this);
      listener.apply(this, args.concat([callNextListener]));

    } else {

      // synchronous listener
      try {
        listener.apply(this, args);
        this.callListeners(listeners, args, doneCallback);
      } catch (err) {
        doneCallback.call(this, err);
        if (domain && this.domain instanceof domain.Domain)
          this.domain.exit();
      }

    }
  }
}
```
- example usage
```shell
...
    this.domain.enter();

  if(process.env.DEBUG == 'aliyun') {
    console.log('emit', eventName);
  }
  var listeners = this.listeners(eventName);
  var count = listeners.length;
  this.callListeners(listeners, eventArgs, doneCallback);
  return count > 0;
},

/**
 * @api private
 */
callListeners: function callListeners(listeners, args, doneCallback) {
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.constructor)
- description and source-code
```javascript
function SequentialExecutor() {
  this.domain = domain && domain.active;
  this._events = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.emit"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>emit (eventName, eventArgs, doneCallback)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.emit)
- description and source-code
```javascript
function emit(eventName, eventArgs, doneCallback) {
  if (!doneCallback) doneCallback = this.unhandledErrorCallback;
  if (domain && this.domain instanceof domain.Domain)
    this.domain.enter();

  if(process.env.DEBUG == 'aliyun') {
    console.log('emit', eventName);
  }
  var listeners = this.listeners(eventName);
  var count = listeners.length;
  this.callListeners(listeners, eventArgs, doneCallback);
  return count > 0;
}
```
- example usage
```shell
...

    addAsync('SEND', 'send', function SEND(resp, done) {
      function callback(httpResp) {
        resp.httpResponse.stream = httpResp;
        resp.httpResponse._abortCallback = done;

        httpResp.on('headers', function onHeaders(statusCode, headers) {
resp.request.emit('httpHeaders', [statusCode, headers, resp]);

if (!resp.request.httpRequest._streaming) {
  if (ALY.HttpClient.streamsApiVersion === 2) { // streams2 API check
    httpResp.on('readable', function onReadable() {
      var data = httpResp.read();
      if (data !== null) {
        resp.request.emit('httpData', [data, resp]);
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.listeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>listeners (eventName)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.listeners)
- description and source-code
```javascript
function listeners(eventName) {
  return this._events[eventName] ? this._events[eventName].slice(0) : [];
}
```
- example usage
```shell
...
  if (!doneCallback) doneCallback = this.unhandledErrorCallback;
  if (domain && this.domain instanceof domain.Domain)
    this.domain.enter();

  if(process.env.DEBUG == 'aliyun') {
    console.log('emit', eventName);
  }
  var listeners = this.listeners(eventName);
  var count = listeners.length;
  this.callListeners(listeners, eventArgs, doneCallback);
  return count > 0;
},

/**
 * @api private
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.on"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>on (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.on)
- description and source-code
```javascript
function on(eventName, listener) {
  if (this._events[eventName]) {
    this._events[eventName].push(listener);
  } else {
    this._events[eventName] = [listener];
  }
  return this;
}
```
- example usage
```shell
...
    });

    addAsync('SEND', 'send', function SEND(resp, done) {
      function callback(httpResp) {
        resp.httpResponse.stream = httpResp;
        resp.httpResponse._abortCallback = done;

        httpResp.on('headers', function onHeaders(statusCode, headers) {
resp.request.emit('httpHeaders', [statusCode, headers, resp]);

if (!resp.request.httpRequest._streaming) {
  if (ALY.HttpClient.streamsApiVersion === 2) { // streams2 API check
    httpResp.on('readable', function onReadable() {
      var data = httpResp.read();
      if (data !== null) {
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.onAsync"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>onAsync (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.onAsync)
- description and source-code
```javascript
function onAsync(eventName, listener) {
  listener._isAsync = true;
  return this.on(eventName, listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>removeAllListeners (eventName)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.removeAllListeners)
- description and source-code
```javascript
function removeAllListeners(eventName) {
  if (eventName) {
    delete this._events[eventName];
  } else {
    this._events = {};
  }
  return this;
}
```
- example usage
```shell
...
 *   setTimeout(request.abort.bind(request), 1000);
 *
 *   // prints "Error: RequestAbortedError Request aborted by user"
 * @return [ALY.Request] the same request object, for chaining.
 * @since v1.4.0
 */
abort: function abort() {
  this.removeAllListeners('validateResponse');
  this.removeAllListeners('extractError');
  this.on('validateResponse', function addAbortedError(resp) {
    resp.error = ALY.util.error(new Error('Request aborted by user'), {
       code: 'RequestAbortedError', retryable: false
    });
  });
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.removeListener"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>removeListener (eventName, listener)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.removeListener)
- description and source-code
```javascript
function removeListener(eventName, listener) {
  var listeners = this._events[eventName];
  if (listeners) {
    var length = listeners.length;
    var position = -1;
    for (var i = 0; i < length; ++i) {
      if (listeners[i] === listener) {
        position = i;
      }
    }
    if (position > -1) {
      listeners.splice(position, 1);
    }
  }
  return this;
}
```
- example usage
```shell
...
      }
    });

    this.on('httpHeaders', function streamHeaders(statusCode, headers, resp) {
      if (statusCode < 300) {
this.httpRequest._streaming = true;

req.removeListener('httpData', ALY.EventListeners.Core.HTTP_DATA);
req.removeListener('httpError', ALY.EventListeners.Core.HTTP_ERROR);
req.on('httpError', function streamHttpError(error, resp) {
  resp.error = error;
  resp.error.retryable = false;
});

var httpStream = resp.httpResponse.stream;
...
```

#### <a name="apidoc.element.aliyun-sdk.SequentialExecutor.prototype.unhandledErrorCallback"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.SequentialExecutor.prototype.</span>unhandledErrorCallback (err)](#apidoc.element.aliyun-sdk.SequentialExecutor.prototype.unhandledErrorCallback)
- description and source-code
```javascript
function unhandledErrorCallback(err) {
  if (err) {
    if (domain && this.domain instanceof domain.Domain) {
      err.domainEmitter = this;
      err.domain = this.domain;
      err.domainThrown = false;
      this.domain.emit('error', err);
    } else {
      throw err;
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Service"></a>[module aliyun-sdk.Service](#apidoc.module.aliyun-sdk.Service)

#### <a name="apidoc.element.aliyun-sdk.Service.Service"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>Service (config)](#apidoc.element.aliyun-sdk.Service.Service)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Service.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.</span>__super__ ()](#apidoc.element.aliyun-sdk.Service.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Service.defineMethods"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.</span>defineMethods (svc)](#apidoc.element.aliyun-sdk.Service.defineMethods)
- description and source-code
```javascript
function defineMethods(svc) {
  ALY.util.each(svc.prototype.api.operations, function iterator(method) {
    if (svc.prototype[method]) return;
    svc.prototype[method] = function (params, callback) {
      return this.makeRequest(method, params, callback);
    };
  });
}
```
- example usage
```shell
...
    }

    svc.services = svc.services || services;
    svc.apiVersions = Object.keys(svc.services).sort();
    svc.serviceIdentifier = svc.serviceIdentifier || serviceIdentifier;
  } else { // defineService called with an API
    svc.prototype.api = serviceIdentifier;
    ALY.Service.defineMethods(svc);
  }

  return svc;
},

/**
 * @api private
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.defineService"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.</span>defineService (serviceIdentifier, versions, features)](#apidoc.element.aliyun-sdk.Service.defineService)
- description and source-code
```javascript
function defineService(serviceIdentifier, versions, features) {
  if (!Array.isArray(versions)) {
    features = versions;
    versions = [];
  }

  var svc = inherit(ALY.Service, features || {});

  if (typeof serviceIdentifier === 'string') {
    // create versions hash
    var services = {};
    for (var i = 0; i < versions.length; i++) {
      services[versions[i]] = null;
    }

    svc.services = svc.services || services;
    svc.apiVersions = Object.keys(svc.services).sort();
    svc.serviceIdentifier = svc.serviceIdentifier || serviceIdentifier;
  } else { // defineService called with an API
    svc.prototype.api = serviceIdentifier;
    ALY.Service.defineMethods(svc);
  }

  return svc;
}
```
- example usage
```shell
...
var ALY = require('./core');

//require('./services/oss');
//require('./services/sls');
//require('./services/opensearch');
//require('./services/batchcompute');

//ALY.ECS = ALY.Service.defineService('ecs', ['2014-05-26']);
//ALY.RDS = ALY.Service.defineService('rds', ['2014-08-15']);
//ALY.SLB = ALY.Service.defineService('slb', ['2014-05-15']);
//ALY.CDN = ALY.Service.defineService('cdn', ['2014-11-11']);
//ALY.STS = ALY.Service.defineService('sts', ['2015-04-01']);

var apis = require('./api_loader');
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.defineServiceApi"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.</span>defineServiceApi (superclass, version)](#apidoc.element.aliyun-sdk.Service.defineServiceApi)
- description and source-code
```javascript
function defineServiceApi(superclass, version) {
  var svc = inherit(superclass, {
    serviceIdentifier: superclass.serviceIdentifier
  });

  if (typeof version === 'string') {
    var file = superclass.serviceIdentifier + '-' + version;
    var path = __dirname + '/../apis/' + file + '.json';
    try {
      if(ALY.util.isBrowser()) {
        svc.prototype.api = require(file + '.json');
      }
      else {
        var fs = require('fs');
        svc.prototype.api = JSON.parse(fs.readFileSync(path));
      }
    } catch (err) {
      throw ALY.util.error(err, {
        message: 'Could not find API configuration ' + file
      });
    }

    if (!superclass.services.hasOwnProperty(version)) {
      superclass.apiVersions.push(version);
    }
    superclass.services[version] = svc;
  } else {
    setApi(version);
  }

  ALY.Service.defineMethods(svc);
  return svc;
}
```
- example usage
```shell
...
},

/**
 * @api private
 */
getLatestServiceClass: function getLatestServiceClass(version) {
  if (this.constructor.services[version] === null) {
    ALY.Service.defineServiceApi(this.constructor, version);
  }

  return this.constructor.services[version];
},

/**
 * @api private
...
```



# <a name="apidoc.module.aliyun-sdk.Service.prototype"></a>[module aliyun-sdk.Service.prototype](#apidoc.module.aliyun-sdk.Service.prototype)

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.addAllRequestListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>addAllRequestListeners (request)](#apidoc.element.aliyun-sdk.Service.prototype.addAllRequestListeners)
- description and source-code
```javascript
function addAllRequestListeners(request) {
  var list = [ALY.events, ALY.EventListeners.Core,
              this.serviceInterface()];
  for (var i = 0; i < list.length; i++) {
    if (list[i]) request.addListeners(list[i]);
  }

  // disable parameter validation
  if (!this.config.paramValidation) {
    request.removeListener('validate',
      ALY.EventListeners.Core.VALIDATE_PARAMETERS);
  }

  if (this.config.logger) { // add logging events
    request.addListeners(ALY.EventListeners.Logger);
  }

  this.setupRequestListeners(request);
}
```
- example usage
```shell
...
          }
        }
      });
    }
  }

  var request = new ALY.Request(this, operation, params);
  this.addAllRequestListeners(request);

  if (callback) request.send(callback);
  return request;
},

/**
 * Calls an operation on a service with the given input parameters, without
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>constructor (config)](#apidoc.element.aliyun-sdk.Service.prototype.constructor)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.getLatestServiceClass"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>getLatestServiceClass (version)](#apidoc.element.aliyun-sdk.Service.prototype.getLatestServiceClass)
- description and source-code
```javascript
function getLatestServiceClass(version) {
  if (this.constructor.services[version] === null) {
    ALY.Service.defineServiceApi(this.constructor, version);
  }

  return this.constructor.services[version];
}
```
- example usage
```shell
...
 */
loadServiceClass: function loadServiceClass(serviceConfig) {
  if (!ALY.util.isEmpty(this.api)) {
    return;
  } else if (!this.constructor.services) {
    return;
  } else {
    return this.getLatestServiceClass(serviceConfig.apiVersion);
  }
},

/**
 * @api private
 */
getLatestServiceClass: function getLatestServiceClass(version) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.getSignerClass"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>getSignerClass ()](#apidoc.element.aliyun-sdk.Service.prototype.getSignerClass)
- description and source-code
```javascript
function getSignerClass() {
  var version = this.api.signatureVersion;
  return ALY.Signers.RequestSigner.getVersion(version);
}
```
- example usage
```shell
...
    addAsync('SIGN', 'sign', function SIGN(req, done) {
if (!req.service.api.signatureVersion) return done(); // none

var credentials = req.service.config.getCredentials();

try {
  var date = ALY.util.date.getDate();
  var SignerClass = req.service.getSignerClass(req);
  var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

  // add new authorization
  signer.addAuthorization(credentials, date);
} catch (e) {
  req.response.error = e;
}
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.initialize"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>initialize (config)](#apidoc.element.aliyun-sdk.Service.prototype.initialize)
- description and source-code
```javascript
function initialize(config) {
  this.config = new ALY.Config(config);
}
```
- example usage
```shell
...
constructor: function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
},

/**
 * @api private
 */
initialize: function initialize(config) {
  this.config = new ALY.Config(config);
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.isRegionCN"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>isRegionCN ()](#apidoc.element.aliyun-sdk.Service.prototype.isRegionCN)
- description and source-code
```javascript
function isRegionCN() {
  if (!this.config.region) return false;
  return this.config.region.match(/^cn-/) ? true : false;
}
```
- example usage
```shell
...
  return this.config.region.match(/^cn-/) ? true : false;
},

/**
 * @api private
 */
isRegionV4: function isRegionV4() {
  return this.isRegionCN();
},

/**
 * @api private
 */
paginationConfig: function paginationConfig(operation, throwException) {
  function fail(name) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.isRegionV4"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>isRegionV4 ()](#apidoc.element.aliyun-sdk.Service.prototype.isRegionV4)
- description and source-code
```javascript
function isRegionV4() {
  return this.isRegionCN();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.loadServiceClass"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>loadServiceClass (serviceConfig)](#apidoc.element.aliyun-sdk.Service.prototype.loadServiceClass)
- description and source-code
```javascript
function loadServiceClass(serviceConfig) {
  if (!ALY.util.isEmpty(this.api)) {
    return;
  } else if (!this.constructor.services) {
    return;
  } else {
    return this.getLatestServiceClass(serviceConfig.apiVersion);
  }
}
```
- example usage
```shell
...
 * @param config [map] a map of configuration options
 */
constructor: function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
},

/**
 * @api private
 */
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.makeRequest"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>makeRequest (operation, params, callback)](#apidoc.element.aliyun-sdk.Service.prototype.makeRequest)
- description and source-code
```javascript
function makeRequest(operation, params, callback) {
  if (typeof params === 'function') {
    callback = params;
    params = null;
  }

  params = params || {};
  if (this.config.params) { // copy only toplevel bound params
    var rules = this.api.operations[operation];
    if (rules) {
      params = ALY.util.copy(params);
      ALY.util.each(this.config.params, function(key, value) {
        if (rules.input.members[key]) {
          if (params[key] === undefined || params[key] === null) {
            params[key] = value;
          }
        }
      });
    }
  }

  var request = new ALY.Request(this, operation, params);
  this.addAllRequestListeners(request);

  if (callback) request.send(callback);
  return request;
}
```
- example usage
```shell
...
    return callback ? callback(null, null) : null;
  } else {
    var inputTokens = config.inputToken;
    if (typeof inputTokens === 'string') inputTokens = [inputTokens];
    for (var i = 0; i < inputTokens.length; i++) {
      params[inputTokens[i]] = this.nextPageTokens[i];
    }
    return service.makeRequest(this.request.operation, params, callback);
  }
},

/**
 * @return [Boolean] whether more pages of data can be returned by further
 *   requests
 * @api experimental
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.makeUnauthenticatedRequest"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>makeUnauthenticatedRequest (operation, params, callback)](#apidoc.element.aliyun-sdk.Service.prototype.makeUnauthenticatedRequest)
- description and source-code
```javascript
function makeUnauthenticatedRequest(operation, params, callback) {
  if (typeof params === 'function') {
    callback = params;
    params = {};
  }

  var request = this.makeRequest(operation, params);
  request.removeListener('sign', ALY.EventListeners.Core.SIGN);
  if (this.api.format === 'query') { // query services turn into GET requests
    request.addListener('build', function convertToGET(request) {
      request.httpRequest.method = 'GET';
      request.httpRequest.path = '/?' + request.httpRequest.body;
      request.httpRequest.body = '';

      // don't need these headers on a GET request
      delete request.httpRequest.headers['Content-Length'];
      delete request.httpRequest.headers['Content-Type'];
    });
  }

  return callback ? request.send(callback) : request;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.networkingError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>networkingError (error)](#apidoc.element.aliyun-sdk.Service.prototype.networkingError)
- description and source-code
```javascript
function networkingError(error) {
  return error.code == 'NetworkingError';
}
```
- example usage
```shell
...
  return delays;
},

/**
 * @api private
 */
retryableError: function retryableError(error) {
  if (this.networkingError(error)) return true;
  if (this.throttledError(error)) return true;
  if (error.statusCode >= 500) return true;
  return false;
},

/**
 * @api private
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.numRetries"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>numRetries ()](#apidoc.element.aliyun-sdk.Service.prototype.numRetries)
- description and source-code
```javascript
function numRetries() {
  if (this.config.maxRetries !== undefined) {
    return this.config.maxRetries;
  } else {
    return this.defaultRetryCount;
  }
}
```
- example usage
```shell
...
  }
},

/**
 * @api private
 */
retryDelays: function retryDelays() {
  var retryCount = this.numRetries();
  var delays = [];
  for (var i = 0; i < retryCount; ++i) {
    delays[i] = Math.pow(2, i) * 30;
  }
  return delays;
},
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.paginationConfig"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>paginationConfig (operation, throwException)](#apidoc.element.aliyun-sdk.Service.prototype.paginationConfig)
- description and source-code
```javascript
function paginationConfig(operation, throwException) {
  function fail(name) {
    if (throwException) {
      var e = new Error();
      throw ALY.util.error(e, 'No pagination configuration for ' + name);
    }
    return null;
  }

  if (!this.api.pagination) return fail('service');
  if (!this.api.pagination[operation]) return fail(operation);
  return this.api.pagination[operation];
}
```
- example usage
```shell
...
   * @since v1.4.0
   */
  eachItem: function eachItem(callback) {
function wrappedCallback(err, data) {
  if (err) return callback(err, null);
  if (data === null) return callback(null, null);

  var config = this.request.service.paginationConfig(this.request.operation);
  var resultKey = config.resultKey;
  if (Array.isArray(resultKey)) resultKey = resultKey[0];
  var results = ALY.util.jamespath.query(resultKey, data);
  ALY.util.arrayEach(results, function(result) {
    ALY.util.arrayEach(result, function(item) { callback(null, item); });
  });
}
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.retryDelays"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>retryDelays ()](#apidoc.element.aliyun-sdk.Service.prototype.retryDelays)
- description and source-code
```javascript
function retryDelays() {
  var retryCount = this.numRetries();
  var delays = [];
  for (var i = 0; i < retryCount; ++i) {
    delays[i] = Math.pow(2, i) * 30;
  }
  return delays;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.retryableError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>retryableError (error)](#apidoc.element.aliyun-sdk.Service.prototype.retryableError)
- description and source-code
```javascript
function retryableError(error) {
  if (this.networkingError(error)) return true;
  if (this.throttledError(error)) return true;
  if (error.statusCode >= 500) return true;
  return false;
}
```
- example usage
```shell
...
    delete resp.httpResponse.buffers;
  });

  add('FINALIZE_ERROR', 'retry', function FINALIZE_ERROR(resp) {
    if (resp.httpResponse.statusCode) {
      resp.error.statusCode = resp.httpResponse.statusCode;
      if (resp.error.retryable === undefined) {
        resp.error.retryable = this.service.retryableError(resp.error, this);
      }
    }
  });

}),

Logger: new ALY.SequentialExecutor().addNamedListeners(function(add) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.serviceInterface"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>serviceInterface ()](#apidoc.element.aliyun-sdk.Service.prototype.serviceInterface)
- description and source-code
```javascript
function serviceInterface() {
  switch (this.api.format) {
    case 'query': return ALY.EventListeners.Query;
    case 'json': return ALY.EventListeners.Json;
    case 'rest': return ALY.EventListeners.Rest;
    case 'rest-json': return ALY.EventListeners.RestJson;
    case 'pop': return ALY.EventListeners.Pop;
    case 'top': return ALY.EventListeners.Top;
    case 'rest-xml': return ALY.EventListeners.RestXml;
  }
  if (this.api.format) {
    throw new Error('Invalid service 'format\' ' +
      this.api.format + ' in API config');
  }
}
```
- example usage
```shell
...
  },

  /**
   * @api private
   */
  addAllRequestListeners: function addAllRequestListeners(request) {
var list = [ALY.events, ALY.EventListeners.Core,
            this.serviceInterface()];
for (var i = 0; i < list.length; i++) {
  if (list[i]) request.addListeners(list[i]);
}

// disable parameter validation
if (!this.config.paramValidation) {
  request.removeListener('validate',
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.setupRequestListeners"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>setupRequestListeners ()](#apidoc.element.aliyun-sdk.Service.prototype.setupRequestListeners)
- description and source-code
```javascript
function setupRequestListeners() {
}
```
- example usage
```shell
...
      ALY.EventListeners.Core.VALIDATE_PARAMETERS);
  }

  if (this.config.logger) { // add logging events
    request.addListeners(ALY.EventListeners.Logger);
  }

  this.setupRequestListeners(request);
},

/**
 * Override this method to setup any custom request listeners for each
 * new request to the service.
 *
 * @abstract
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.successfulResponse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>successfulResponse (resp)](#apidoc.element.aliyun-sdk.Service.prototype.successfulResponse)
- description and source-code
```javascript
function successfulResponse(resp) {
  return resp.httpResponse.statusCode < 300;
}
```
- example usage
```shell
...
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
  if (this.service.successfulResponse(resp, this)) {
    resp.data = {};
    resp.error = null;
  } else {
    resp.data = null;
    resp.error = ALY.util.error(new Error(),
      {code: 'UnknownError', message: 'An unknown error occurred.'});
  }
...
```

#### <a name="apidoc.element.aliyun-sdk.Service.prototype.throttledError"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Service.prototype.</span>throttledError (error)](#apidoc.element.aliyun-sdk.Service.prototype.throttledError)
- description and source-code
```javascript
function throttledError(error) {
  // this logic varies between services
  return (error.code == 'ProvisionedThroughputExceededException');
}
```
- example usage
```shell
...
},

/**
 * @api private
 */
retryableError: function retryableError(error) {
  if (this.networkingError(error)) return true;
  if (this.throttledError(error)) return true;
  if (error.statusCode >= 500) return true;
  return false;
},

/**
 * @api private
 */
...
```



# <a name="apidoc.module.aliyun-sdk.Signers"></a>[module aliyun-sdk.Signers](#apidoc.module.aliyun-sdk.Signers)

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>BatchCompute ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute)
- description and source-code
```javascript
BatchCompute = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>CMS ()](#apidoc.element.aliyun-sdk.Signers.CMS)
- description and source-code
```javascript
CMS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OSS ()](#apidoc.element.aliyun-sdk.Signers.OSS)
- description and source-code
```javascript
OSS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
...
'''

目前在浏览器端运行的 sdk 还在测试阶段, 如果有问题请随时提出.

## 初始化

'''javascript
var oss = new ALY.OSS({
  accessKeyId: "在阿里云OSS申请的 accessKeyId",
  secretAccessKey: "在阿里云OSS申请的 secretAccessKey",
  securityToken: "",
  endpoint: 'http://oss-cn-hangzhou.aliyuncs.com',
  apiVersion: '2013-10-15'
});
'''
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OTS ()](#apidoc.element.aliyun-sdk.Signers.OTS)
- description and source-code
```javascript
OTS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OpenSearch ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch)
- description and source-code
```javascript
OpenSearch = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.POP"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>POP ()](#apidoc.element.aliyun-sdk.Signers.POP)
- description and source-code
```javascript
POP = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.RequestSigner"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>RequestSigner (request)](#apidoc.element.aliyun-sdk.Signers.RequestSigner)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>SLS ()](#apidoc.element.aliyun-sdk.Signers.SLS)
- description and source-code
```javascript
SLS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.TOP"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>TOP ()](#apidoc.element.aliyun-sdk.Signers.TOP)
- description and source-code
```javascript
TOP = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.BatchCompute"></a>[module aliyun-sdk.Signers.BatchCompute](#apidoc.module.aliyun-sdk.Signers.BatchCompute)

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute.BatchCompute"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>BatchCompute ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.BatchCompute)
- description and source-code
```javascript
BatchCompute = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.BatchCompute.__super__)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.BatchCompute.prototype"></a>[module aliyun-sdk.Signers.BatchCompute.prototype](#apidoc.module.aliyun-sdk.Signers.BatchCompute.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.addAuthorization"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.addAuthorization)
- description and source-code
```javascript
function addAuthorization(credentials, date) {
  var headers = this.request.headers;

  //headers['Date'] = ALY.util.date.rfc822(date);
  headers['x-acs-date'] = ALY.util.date.rfc822(date);
  //headers['Date'] = new Date().toGMTString();


  //var bodyStr;
  //var body = this.request.body;
  //if(body){
  //  bodyStr = typeof(body)=='object'? JSON.stringify(body):body;
  //  headers['Content-MD5'] = ALY.util.crypto.md5(bodyStr,'hex').toUpperCase();
  //}

  headers['x-acs-signature-method'] = 'HMAC-SHA1';
  headers['x-acs-signature-version'] = '1.0';
  //headers['x-acs-version'] = API_VERSION;
  headers['x-sdk-client'] = 'node.js/1.0.0';
  headers['Accept'] = 'application/json';

  var signature = this.sign(credentials.secretAccessKey, this.stringToSign());
  var auth = 'acs ' + credentials.accessKeyId + ':' + signature;

  headers['Authorization'] = auth;
}
```
- example usage
```shell
...

  try {
    var date = ALY.util.date.getDate();
    var SignerClass = req.service.getSignerClass(req);
    var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

    // add new authorization
    signer.addAuthorization(credentials, date);
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.canonicalizedAmzHeaders"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>canonicalizedAmzHeaders ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.canonicalizedAmzHeaders)
- description and source-code
```javascript
function canonicalizedAmzHeaders() {

  var acsHeaders = [];

  ALY.util.each(this.request.headers, function (name) {
    if (name.match(/^x-acs-/i))
      acsHeaders.push(name);
  });

  acsHeaders.sort(function (a, b) {
    return a.toLowerCase() < b.toLowerCase() ? -1 : 1;
  });

  var parts = [];
  ALY.util.arrayEach.call(this, acsHeaders, function (name) {
    parts.push(name.toLowerCase() + ':' + String(this.request.headers[name]));
  });

  return parts.join('\n');

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.canonicalizedResource"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>canonicalizedResource ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.canonicalizedResource)
- description and source-code
```javascript
function canonicalizedResource() {

  var r = this.request;

  var parts = r.path.split('?');
  var path = parts[0];
  var querystring = parts[1];

  var resource = '';


  resource += decodeURIComponent(path);


  if (querystring) {

    // collect a list of sub resources and query params that need to be signed
    var resources = [];

    var arr = querystring.replace(/(^&*)|(&*$)/g,'').split('&');


    ALY.util.arrayEach.call(this, arr, function (param) {
      var kv = param.split('=');

      var name = kv[0];

      var value = (kv.length>1)? decodeURIComponent(kv[1]):'';
<span class="apidocCodeCommentSpan">      /*jshint undef:false */
</span>
      var resource = { name: name };
      if (value !== undefined) {
        resource.value = value;
      }
      resources.push(resource);

    });

    resources.sort(function (a, b) { return a.name < b.name ? -1 : 1; });

    if (resources.length) {

      querystring = [];
      ALY.util.arrayEach(resources, function (resource) {
        if (resource.value === undefined)
          querystring.push(resource.name);
        else {

          if(resource.value!=null && resource.value!=''){
            querystring.push(resource.name + '=' + resource.value);
          }else{
            querystring.push(resource.name);
          }
        }
      });

      resource += '?' + querystring.join('&');
    }

  }

  return resource;

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.sign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.sign)
- description and source-code
```javascript
function sign(secret, string) {
  if(process.env.DEBUG == 'aliyun') {
    console.log('----------- sign string start -----------');
    console.log(string);
    console.log('----------- sign string end -----------');
  }
  return ALY.util.crypto.hmac(secret, string, 'base64', 'sha1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.stringToSign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.BatchCompute.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.BatchCompute.prototype.stringToSign)
- description and source-code
```javascript
function stringToSign() {
  var r = this.request;

  //fix signature not match in browser
  if(r.method!='GET' && r.method!='HEAD'){
     r.headers['Content-Type'] = r.headers['Content-Type'] || 'text/plain;charset=UTF-8';
  }

  var parts = [];
  parts.push(r.method);
  parts.push(r.headers['Accept'] || '');
  parts.push(r.headers['Content-MD5'] || '');
  parts.push(r.headers['Content-Type'] || '');
  parts.push(r.headers['x-acs-date'] || r.headers['Date'] ||'');

  var headers = this.canonicalizedAmzHeaders();
  if (headers) parts.push(headers);
  parts.push(this.canonicalizedResource());

  return parts.join('\n');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.CMS"></a>[module aliyun-sdk.Signers.CMS](#apidoc.module.aliyun-sdk.Signers.CMS)

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS.CMS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>CMS ()](#apidoc.element.aliyun-sdk.Signers.CMS.CMS)
- description and source-code
```javascript
CMS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.CMS.__super__)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.CMS.prototype"></a>[module aliyun-sdk.Signers.CMS.prototype](#apidoc.module.aliyun-sdk.Signers.CMS.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS.prototype.addAuthorization"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.addAuthorization)
- description and source-code
```javascript
function addAuthorization(credentials, date) {
  // if (!this.request.headers['presigned-expires']) {
  //   this.request.headers['Date'] = ALY.util.date.rfc822(date);
  // }

  // if (credentials.sessionToken) {
  //   // presigned URLs require this header to be lowercased
  //   this.request.headers['x-amz-security-token'] = credentials.sessionToken;
  // }
  var date = new Date();

  var globalQuery = {
    'Format': 'JSON',
    'Version': '2015-10-20',
    'AccessKeyId': credentials.accessKeyId,
    'SignatureMethod': 'HMAC-SHA1',
    'SignatureVersion': '1.0',
    'SignatureNonce': String(date.getTime()) + randomNumbers(4),
    'Timestamp': date.toISOString().replace(/\.\d{3}/, '')
  };

  var parts = [];
  Object.keys(globalQuery).forEach(function(key) {
    parts.push(key + '=' + encodeURIComponent(globalQuery[key]));
  });
  this.request.path += (this.request.path.indexOf('?') == -1? '?' : '&') + parts.join('&');

  var signature = this.sign(credentials.secretAccessKey, this.stringToSign());
  this.request.path += '&Signature=' + encodeURIComponent(signature);
  // var auth = 'OSS ' + credentials.accessKeyId + ':' + signature;

  // this.request.headers['Authorization'] = auth;
}
```
- example usage
```shell
...

  try {
    var date = ALY.util.date.getDate();
    var SignerClass = req.service.getSignerClass(req);
    var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

    // add new authorization
    signer.addAuthorization(credentials, date);
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS.prototype.canonicalizedQueryString"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>canonicalizedQueryString ()](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.canonicalizedQueryString)
- description and source-code
```javascript
function canonicalizedQueryString() {
  var that = this;
  var r = this.request;
  var querystring = r.path.split('?')[1];
  var resource = '';
  if (r.body) {
    querystring += '&' + r.body;
  }

  if (querystring) {

    // collect a list of sub resources and query params that need to be signed
    var resources = [];

    ALY.util.arrayEach.call(this, querystring.split('&'), function (param) {
      var pos = param.indexOf('=');
      var name = param.slice(0, pos);
      var value = param.slice(pos + 1);

      var resource = { name: name };
      if (value !== undefined) {
        resource.value = decodeURIComponent(value);
      }

      resources.push(resource);
    });

    resources.sort(function (a, b) { return a.name < b.name ? -1 : 1; });

    if (resources.length) {

      querystring = [];
      ALY.util.arrayEach(resources, function (resource) {
        if (resource.value === undefined)
          querystring.push(that.cmsEscape(resource.name));
        else
          querystring.push(that.cmsEscape(resource.name) + '=' + that.cmsEscape(resource.value));
      });

      resource += querystring.join('&');
    }
  }

  return resource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS.prototype.cmsEscape"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>cmsEscape (clearString)](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.cmsEscape)
- description and source-code
```javascript
cmsEscape = function (clearString) {
  // http://v8.googlecode.com/svn/trunk/src/uri.js
  return encodeURIComponent(clearString)
      .replace(/\!/gi, '%21')
      .replace(/\'/gi, '%27')
      .replace(/\(/gi, '%28')
      .replace(/\)/gi, '%29')
      .replace(/\*/gi, '%2A')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS.prototype.sign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.sign)
- description and source-code
```javascript
function sign(secret, string) {
  if(process.env.DEBUG == 'aliyun') {
    console.log('----------- sign string start -----------');
    console.log(string);
    console.log('----------- sign string end -----------');
  }
  return ALY.util.crypto.hmac(secret + '&', string, 'base64', 'sha1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.CMS.prototype.stringToSign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.CMS.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.CMS.prototype.stringToSign)
- description and source-code
```javascript
function stringToSign() {
  var r = this.request;

  var s = r.method + '&%2F&' + encodeURIComponent(this.canonicalizedQueryString());

  return s;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.OSS"></a>[module aliyun-sdk.Signers.OSS](#apidoc.module.aliyun-sdk.Signers.OSS)

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS.OSS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OSS ()](#apidoc.element.aliyun-sdk.Signers.OSS.OSS)
- description and source-code
```javascript
OSS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
...
'''

目前在浏览器端运行的 sdk 还在测试阶段, 如果有问题请随时提出.

## 初始化

'''javascript
var oss = new ALY.OSS({
  accessKeyId: "在阿里云OSS申请的 accessKeyId",
  secretAccessKey: "在阿里云OSS申请的 secretAccessKey",
  securityToken: "",
  endpoint: 'http://oss-cn-hangzhou.aliyuncs.com',
  apiVersion: '2013-10-15'
});
'''
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.OSS.__super__)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.OSS.prototype"></a>[module aliyun-sdk.Signers.OSS.prototype](#apidoc.module.aliyun-sdk.Signers.OSS.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS.prototype.addAuthorization"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.addAuthorization)
- description and source-code
```javascript
function addAuthorization(credentials, date) {
  if (!this.request.headers['presigned-expires']) {
    // 在浏览器中不能设置 date header
    if(ALY.util.isBrowser()) {
      this.request.headers['x-oss-date'] = ALY.util.date.rfc822(date);
    }
    else {
      this.request.headers['Date'] = ALY.util.date.rfc822(date);
    }
  }

  var signature = this.sign(credentials.secretAccessKey, this.stringToSign());
  var auth = 'OSS ' + credentials.accessKeyId + ':' + signature;

  this.request.headers['Authorization'] = auth;
}
```
- example usage
```shell
...

  try {
    var date = ALY.util.date.getDate();
    var SignerClass = req.service.getSignerClass(req);
    var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

    // add new authorization
    signer.addAuthorization(credentials, date);
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS.prototype.canonicalizedHeaders"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>canonicalizedHeaders ()](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.canonicalizedHeaders)
- description and source-code
```javascript
function canonicalizedHeaders() {

  var headers = [];

  ALY.util.each(this.request.headers, function (name) {
    if (name.match(/^x-oss-/i))
      headers.push(name);
  });

  headers.sort(function (a, b) {
    return a.toLowerCase() < b.toLowerCase() ? -1 : 1;
  });

  var parts = [];
  ALY.util.arrayEach.call(this, headers, function (name) {
    parts.push(name.toLowerCase() + ':' + String(this.request.headers[name]));
  });

  return parts.join('\n');

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS.prototype.canonicalizedResource"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>canonicalizedResource ()](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.canonicalizedResource)
- description and source-code
```javascript
function canonicalizedResource() {

  var r = this.request;

  var parts = r.path.split('?');
  var path = parts[0];
  var querystring = parts[1];

  var resource = '';

  if (r.virtualHostedBucket)
    resource += '/' + r.virtualHostedBucket;

  // OSS 遗留问题，header 中的 Key 不能 url encode
  resource += decodeURIComponent(path);

  if (querystring) {

    // collect a list of sub resources and query params that need to be signed
    var resources = [];

    ALY.util.arrayEach.call(this, querystring.split('&'), function (param) {
      var name = param.split('=')[0];
      var value = param.split('=')[1];
      if (this.subResources[name] || this.responseHeaders[name]) {
        var subresource = { name: name };
        if (value !== undefined) {
          if (this.subResources[name]) {
            subresource.value = value;
          } else {
            subresource.value = decodeURIComponent(value);
          }
        }
        resources.push(subresource);
      }
    });

    resources.sort(function (a, b) { return a.name < b.name ? -1 : 1; });

    if (resources.length) {

      querystring = [];
      ALY.util.arrayEach(resources, function (res) {
        if (res.value === undefined)
          querystring.push(res.name);
        else
          querystring.push(res.name + '=' + res.value);
      });

      resource += '?' + querystring.join('&');
    }

  }

  return resource;

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS.prototype.sign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.sign)
- description and source-code
```javascript
function sign(secret, string) {
  if(process.env.DEBUG == 'aliyun') {
    console.log('----------- sign string start -----------');
    console.log(string);
    console.log('----------- sign string end -----------');
  }
  return ALY.util.crypto.hmac(secret, string, 'base64', 'sha1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OSS.prototype.stringToSign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OSS.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.OSS.prototype.stringToSign)
- description and source-code
```javascript
function stringToSign() {
  var r = this.request;

  var parts = [];
  parts.push(r.method);
  parts.push(r.headers['Content-MD5'] || '');
  parts.push(r.headers['Content-Type'] || '');

  // This is the "Date" header, but we use X-Amz-Date.
  // The S3 signing mechanism requires us to pass an empty
  // string for this Date header regardless.
  // this works:
  // getSignedUrl use 'presigned-expires'
  // other request use 'Date'
  parts.push(r.headers['presigned-expires'] || r.headers['x-oss-date'] || r.headers['Date'] || '');

  var headers = this.canonicalizedHeaders();
  if (headers) parts.push(headers);
  parts.push(this.canonicalizedResource());

  return parts.join('\n');

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.OTS"></a>[module aliyun-sdk.Signers.OTS](#apidoc.module.aliyun-sdk.Signers.OTS)

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS.OTS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OTS ()](#apidoc.element.aliyun-sdk.Signers.OTS.OTS)
- description and source-code
```javascript
OTS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.OTS.__super__)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.OTS.prototype"></a>[module aliyun-sdk.Signers.OTS.prototype](#apidoc.module.aliyun-sdk.Signers.OTS.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS.prototype.addAuthorization"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.addAuthorization)
- description and source-code
```javascript
function addAuthorization(credentials, date) {
  this.request.headers['x-ots-date'] = ALY.util.date.rfc822(date);
  this.request.headers['x-ots-accesskeyid'] = credentials.accessKeyId;

  var signature = this.sign(credentials.secretAccessKey, this.stringToSign());

  this.request.headers['x-ots-signature'] = signature;
}
```
- example usage
```shell
...

  try {
    var date = ALY.util.date.getDate();
    var SignerClass = req.service.getSignerClass(req);
    var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

    // add new authorization
    signer.addAuthorization(credentials, date);
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS.prototype.canonicalizedHeaders"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>canonicalizedHeaders ()](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.canonicalizedHeaders)
- description and source-code
```javascript
function canonicalizedHeaders() {

  var headers = [];

  ALY.util.each(this.request.headers, function (name) {
    if (name.match(/^x-ots-/i))
      headers.push(name);
  });

  headers.sort(function (a, b) {
    return a.toLowerCase() < b.toLowerCase() ? -1 : 1;
  });

  var parts = [];
  ALY.util.arrayEach.call(this, headers, function (name) {
    parts.push(name.toLowerCase() + ':' + String(this.request.headers[name]));
  });

  return parts.join('\n');

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS.prototype.canonicalizedResource"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>canonicalizedResource ()](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.canonicalizedResource)
- description and source-code
```javascript
function canonicalizedResource() {

  var r = this.request;

  var parts = r.path.split('?');
  var path = parts[0];
  var querystring = parts[1];

  var resource = '';

  if (r.virtualHostedBucket)
    resource += '/' + r.virtualHostedBucket;

  // OSS 遗留问题，header 中的 Key 不能 url encode
  resource += decodeURIComponent(path);

  if (querystring) {

    // collect a list of sub resources and query params that need to be signed
    var resources = [];

    ALY.util.arrayEach.call(this, querystring.split('&'), function (param) {
      var name = param.split('=')[0];
      var value = param.split('=')[1];
      if (this.subResources[name] || this.responseHeaders[name]) {
        var subresource = { name: name };
        if (value !== undefined) {
          if (this.subResources[name]) {
            subresource.value = value;
          } else {
            subresource.value = decodeURIComponent(value);
          }
        }
        resources.push(subresource);
      }
    });

    resources.sort(function (a, b) { return a.name < b.name ? -1 : 1; });

    if (resources.length) {

      querystring = [];
      ALY.util.arrayEach(resources, function (res) {
        if (res.value === undefined)
          querystring.push(res.name);
        else
          querystring.push(res.name + '=' + res.value);
      });

      resource += '?' + querystring.join('&');
    }

  }

  return resource;

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS.prototype.sign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.sign)
- description and source-code
```javascript
function sign(secret, string) {
  if(process.env.DEBUG == 'aliyun') {
    console.log('----------- sign string start -----------');
    console.log(string);
    console.log('----------- sign string end -----------');
  }
  return ALY.util.crypto.hmac(secret, string, 'base64', 'sha1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OTS.prototype.stringToSign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OTS.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.OTS.prototype.stringToSign)
- description and source-code
```javascript
function stringToSign() {
  var r = this.request;

  var parts = [];

  parts.push(r.path);

  parts.push(r.method + '\n');

  var headers = this.canonicalizedHeaders();
  if (headers) parts.push(headers);
  //parts.push(this.canonicalizedResource());

  return parts.join('\n') + '\n';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.OpenSearch"></a>[module aliyun-sdk.Signers.OpenSearch](#apidoc.module.aliyun-sdk.Signers.OpenSearch)

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch.OpenSearch"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>OpenSearch ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch.OpenSearch)
- description and source-code
```javascript
OpenSearch = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.OpenSearch.__super__)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.OpenSearch.prototype"></a>[module aliyun-sdk.Signers.OpenSearch.prototype](#apidoc.module.aliyun-sdk.Signers.OpenSearch.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.addAuthorization"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.addAuthorization)
- description and source-code
```javascript
function addAuthorization(credentials, date) {
  // if (!this.request.headers['presigned-expires']) {
  //   this.request.headers['Date'] = ALY.util.date.rfc822(date);
  // }

  // if (credentials.sessionToken) {
  //   // presigned URLs require this header to be lowercased
  //   this.request.headers['x-amz-security-token'] = credentials.sessionToken;
  // }
  var date = new Date();

  var globalQuery = {
    'Version': 'v2',
    'AccessKeyId': credentials.accessKeyId,
    'SignatureMethod': 'HMAC-SHA1',
    'SignatureVersion': '1.0',
    'SignatureNonce': String(date.getTime()) + randomNumbers(4),
    'Timestamp': date.toISOString().replace(/\.\d{3}/, '')
  };

  var parts = [];
  Object.keys(globalQuery).forEach(function(key) {
    parts.push(key + '=' + encodeURIComponent(globalQuery[key]));
  });
  this.request.path += (this.request.path.indexOf('?') == -1? '?' : '&') + parts.join('&');

  var signature = this.sign(credentials.secretAccessKey, this.stringToSign());
  this.request.path += '&Signature=' + encodeURIComponent(signature);
  // var auth = 'OSS ' + credentials.accessKeyId + ':' + signature;

  // this.request.headers['Authorization'] = auth;
}
```
- example usage
```shell
...

  try {
    var date = ALY.util.date.getDate();
    var SignerClass = req.service.getSignerClass(req);
    var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

    // add new authorization
    signer.addAuthorization(credentials, date);
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.canonicalizedQueryString"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>canonicalizedQueryString ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.canonicalizedQueryString)
- description and source-code
```javascript
function canonicalizedQueryString() {

  var r = this.request;
  var querystring = r.path.split('?')[1];
  var resource = '';
  if (r.body) {
    querystring += '&' + r.body;
  }

  if (querystring) {

    // collect a list of sub resources and query params that need to be signed
    var resources = [];

    ALY.util.arrayEach.call(this, querystring.split('&'), function (param) {
      var pos = param.indexOf('=');
      var name = param.slice(0, pos);
      var value = param.slice(pos + 1);

      var resource = { name: name };
      if (value !== undefined) {
        resource.value = decodeURIComponent(value);
      }

      resources.push(resource);
    });

    resources.sort(function (a, b) { return a.name < b.name ? -1 : 1; });

    if (resources.length) {

      querystring = [];
      ALY.util.arrayEach(resources, function (resource) {
        if (resource.value === undefined)
          querystring.push(ALY.util.opensearchEscape(resource.name));
        else
          querystring.push(ALY.util.opensearchEscape(resource.name) + '=' + ALY.util.opensearchEscape(resource.value));
      });

      resource += querystring.join('&');
    }
  }

  return resource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.sign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.sign)
- description and source-code
```javascript
function sign(secret, string) {
  if(process.env.DEBUG == 'aliyun') {
    console.log('----------- sign string start -----------');
    console.log(string);
    console.log('----------- sign string end -----------');
  }
  return ALY.util.crypto.hmac(secret + '&', string, 'base64', 'sha1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.stringToSign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.OpenSearch.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.OpenSearch.prototype.stringToSign)
- description and source-code
```javascript
function stringToSign() {
  var r = this.request;

  var s = r.method + '&%2F&' + encodeURIComponent(this.canonicalizedQueryString());

  return s;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.POP"></a>[module aliyun-sdk.Signers.POP](#apidoc.module.aliyun-sdk.Signers.POP)

#### <a name="apidoc.element.aliyun-sdk.Signers.POP.POP"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>POP ()](#apidoc.element.aliyun-sdk.Signers.POP.POP)
- description and source-code
```javascript
POP = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.POP.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.POP.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.POP.__super__)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.POP.prototype"></a>[module aliyun-sdk.Signers.POP.prototype](#apidoc.module.aliyun-sdk.Signers.POP.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.POP.prototype.addAuthorization"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.POP.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.POP.prototype.addAuthorization)
- description and source-code
```javascript
function addAuthorization(credentials, date) {
}
```
- example usage
```shell
...

  try {
    var date = ALY.util.date.getDate();
    var SignerClass = req.service.getSignerClass(req);
    var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

    // add new authorization
    signer.addAuthorization(credentials, date);
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.POP.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.POP.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.POP.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.RequestSigner"></a>[module aliyun-sdk.Signers.RequestSigner](#apidoc.module.aliyun-sdk.Signers.RequestSigner)

#### <a name="apidoc.element.aliyun-sdk.Signers.RequestSigner.RequestSigner"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>RequestSigner (request)](#apidoc.element.aliyun-sdk.Signers.RequestSigner.RequestSigner)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.RequestSigner.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.RequestSigner.</span>__super__ ()](#apidoc.element.aliyun-sdk.Signers.RequestSigner.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.RequestSigner.getVersion"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.RequestSigner.</span>getVersion (version)](#apidoc.element.aliyun-sdk.Signers.RequestSigner.getVersion)
- description and source-code
```javascript
function getVersion(version) {
  switch (version) {
    case 'oss': return ALY.Signers.OSS;
    case 'ots': return ALY.Signers.OTS;
    case 'sls': return ALY.Signers.SLS;
    case 'top': return ALY.Signers.TOP;
    case 'pop': return ALY.Signers.POP;
    case 'opensearch': return ALY.Signers.OpenSearch;
    case 'batchcompute': return ALY.Signers.BatchCompute;
    case 'cms': return ALY.Signers.CMS;
  }
  throw new Error('Unknown signing version ' + version);
}
```
- example usage
```shell
...

/**
 * Gets the signer class for a given request
 * @api private
 */
getSignerClass: function getSignerClass() {
  var version = this.api.signatureVersion;
  return ALY.Signers.RequestSigner.getVersion(version);
},

/**
 * @api private
 */
serviceInterface: function serviceInterface() {
  switch (this.api.format) {
...
```



# <a name="apidoc.module.aliyun-sdk.Signers.RequestSigner.prototype"></a>[module aliyun-sdk.Signers.RequestSigner.prototype](#apidoc.module.aliyun-sdk.Signers.RequestSigner.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.RequestSigner.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.RequestSigner.prototype.</span>constructor (request)](#apidoc.element.aliyun-sdk.Signers.RequestSigner.prototype.constructor)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.SLS"></a>[module aliyun-sdk.Signers.SLS](#apidoc.module.aliyun-sdk.Signers.SLS)

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS.SLS"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>SLS ()](#apidoc.element.aliyun-sdk.Signers.SLS.SLS)
- description and source-code
```javascript
SLS = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.SLS.__super__)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.SLS.prototype"></a>[module aliyun-sdk.Signers.SLS.prototype](#apidoc.module.aliyun-sdk.Signers.SLS.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS.prototype.addAuthorization"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.addAuthorization)
- description and source-code
```javascript
function addAuthorization(credentials, date) {
  this.request.headers['Date'] = ALY.util.date.rfc822(date);

  var signature = this.sign(credentials.secretAccessKey, this.stringToSign());
  var auth = 'LOG ' + credentials.accessKeyId + ':' + signature;

  this.request.headers['Authorization'] = auth;
}
```
- example usage
```shell
...

  try {
    var date = ALY.util.date.getDate();
    var SignerClass = req.service.getSignerClass(req);
    var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

    // add new authorization
    signer.addAuthorization(credentials, date);
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS.prototype.canonicalizedAmzHeaders"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>canonicalizedAmzHeaders ()](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.canonicalizedAmzHeaders)
- description and source-code
```javascript
function canonicalizedAmzHeaders() {

  var amzHeaders = [];

  ALY.util.each(this.request.headers, function (name) {
    if (name.match(/^x-log-/i))
      amzHeaders.push(name);
  });

  amzHeaders.sort(function (a, b) {
    return a.toLowerCase() < b.toLowerCase() ? -1 : 1;
  });

  var parts = [];
  ALY.util.arrayEach.call(this, amzHeaders, function (name) {
    parts.push(name.toLowerCase() + ':' + String(this.request.headers[name]));
  });

  return parts.join('\n');

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS.prototype.canonicalizedResource"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>canonicalizedResource ()](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.canonicalizedResource)
- description and source-code
```javascript
function canonicalizedResource() {

  var r = this.request;

  var parts = r.path.split('?');
  var path = parts[0];
  var querystring = parts[1];

  var resource = '';


  resource += decodeURIComponent(path);


  if (querystring) {

    // collect a list of sub resources and query params that need to be signed
    var resources = [];

    var arr = querystring.replace(/(^&*)|(&*$)/g,'').split('&');


    ALY.util.arrayEach.call(this, arr, function (param) {
      var kv = param.split('=');

      var name = kv[0];
      //修复topic中带有 / 等字符，签名报错
      var value = (kv.length>1)? decodeURIComponent(kv[1]):'';
<span class="apidocCodeCommentSpan">      /*jshint undef:false */
</span>
      var resource = { name: name };
      if (value !== undefined) {
        resource.value = value;
      }
      resources.push(resource);

    });

    resources.sort(function (a, b) { return a.name < b.name ? -1 : 1; });

    if (resources.length) {

      querystring = [];
      ALY.util.arrayEach(resources, function (resource) {
        if (resource.value === undefined)
          querystring.push(resource.name);
        else
          querystring.push(resource.name + '=' + resource.value);
      });

      resource += '?' + querystring.join('&');
    }

  }

  return resource;

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS.prototype.sign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>sign (secret, string)](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.sign)
- description and source-code
```javascript
function sign(secret, string) {
  if(process.env.DEBUG == 'aliyun') {
    console.log('----------- sign string start -----------');
    console.log(string);
    console.log('----------- sign string end -----------');
  }
  return ALY.util.crypto.hmac(secret, string, 'base64', 'sha1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.SLS.prototype.stringToSign"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.SLS.prototype.</span>stringToSign ()](#apidoc.element.aliyun-sdk.Signers.SLS.prototype.stringToSign)
- description and source-code
```javascript
function stringToSign() {
  var r = this.request;

  var parts = [];
  parts.push(r.method);
  parts.push(r.headers['Content-MD5'] || '');
  parts.push(r.headers['Content-Type'] || '');

  // This is the "Date" header, but we use X-Amz-Date.
  // The S3 signing mechanism requires us to pass an empty
  // string for this Date header regardless.
  // this works:
  // getSignedUrl use 'presigned-expires'
  // other request use 'Date'
  parts.push(r.headers['Date'] || '');

  var headers = this.canonicalizedAmzHeaders();
  if (headers) parts.push(headers);
  parts.push(this.canonicalizedResource());

  return parts.join('\n');

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.TOP"></a>[module aliyun-sdk.Signers.TOP](#apidoc.module.aliyun-sdk.Signers.TOP)

#### <a name="apidoc.element.aliyun-sdk.Signers.TOP.TOP"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.</span>TOP ()](#apidoc.element.aliyun-sdk.Signers.TOP.TOP)
- description and source-code
```javascript
TOP = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.Signers.TOP.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.TOP.</span>__super__ (request)](#apidoc.element.aliyun-sdk.Signers.TOP.__super__)
- description and source-code
```javascript
function RequestSigner(request) {
  this.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.Signers.TOP.prototype"></a>[module aliyun-sdk.Signers.TOP.prototype](#apidoc.module.aliyun-sdk.Signers.TOP.prototype)

#### <a name="apidoc.element.aliyun-sdk.Signers.TOP.prototype.addAuthorization"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.TOP.prototype.</span>addAuthorization (credentials, date)](#apidoc.element.aliyun-sdk.Signers.TOP.prototype.addAuthorization)
- description and source-code
```javascript
function addAuthorization(credentials, date) {

}
```
- example usage
```shell
...

  try {
    var date = ALY.util.date.getDate();
    var SignerClass = req.service.getSignerClass(req);
    var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

    // add new authorization
    signer.addAuthorization(credentials, date);
  } catch (e) {
    req.response.error = e;
  }
  done();
});

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.Signers.TOP.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.Signers.TOP.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.Signers.TOP.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.XML"></a>[module aliyun-sdk.XML](#apidoc.module.aliyun-sdk.XML)

#### <a name="apidoc.element.aliyun-sdk.XML.Builder"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.</span>Builder (root, rules, options)](#apidoc.element.aliyun-sdk.XML.Builder)
- description and source-code
```javascript
function XMLBuilder(root, rules, options) {
  this.root = root;
  this.rules = rules;
  this.xmlns = options.xmlnamespace;
  this.timestampFormat = options.timestampFormat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.</span>Parser (rules)](#apidoc.element.aliyun-sdk.XML.Parser)
- description and source-code
```javascript
function XMLParser(rules) {
  this.rules = (rules || {}).members || {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.XML.Builder"></a>[module aliyun-sdk.XML.Builder](#apidoc.module.aliyun-sdk.XML.Builder)

#### <a name="apidoc.element.aliyun-sdk.XML.Builder.Builder"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.</span>Builder (root, rules, options)](#apidoc.element.aliyun-sdk.XML.Builder.Builder)
- description and source-code
```javascript
function XMLBuilder(root, rules, options) {
  this.root = root;
  this.rules = rules;
  this.xmlns = options.xmlnamespace;
  this.timestampFormat = options.timestampFormat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Builder.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.</span>__super__ ()](#apidoc.element.aliyun-sdk.XML.Builder.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.XML.Builder.prototype"></a>[module aliyun-sdk.XML.Builder.prototype](#apidoc.module.aliyun-sdk.XML.Builder.prototype)

#### <a name="apidoc.element.aliyun-sdk.XML.Builder.prototype.applyNamespaces"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>applyNamespaces (xml, rules)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.applyNamespaces)
- description and source-code
```javascript
function applyNamespaces(xml, rules) {
  if (rules.xmlns) {
    var attr = 'xmlns';
    if (rules.xmlns.prefix) attr += ':' + rules.xmlns.prefix;
    xml.att(attr, rules.xmlns.uri);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Builder.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>constructor (root, rules, options)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.constructor)
- description and source-code
```javascript
function XMLBuilder(root, rules, options) {
  this.root = root;
  this.rules = rules;
  this.xmlns = options.xmlnamespace;
  this.timestampFormat = options.timestampFormat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeList"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>serializeList (name, rules, list, xml)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeList)
- description and source-code
```javascript
function serializeList(name, rules, list, xml) {
  if (rules.flattened) {
    ALY.util.arrayEach.call(this, list, function (value) {
      this.serializeMember(rules.name || name, rules.members, value, xml);
    });
  } else {
    xml = xml.ele(rules.name || name);
    ALY.util.arrayEach.call(this, list, function (value) {
      var memberName = rules.members.name || 'member';
      this.serializeMember(memberName, rules.members, value, xml);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeMember"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>serializeMember (memberName, rules, params, xml)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeMember)
- description and source-code
```javascript
function serializeMember(memberName, rules, params, xml) {
  if (params === null || params === undefined) return;

  var name = memberName;
  if (rules.type === 'structure') {
    xml = xml.ele(name);
    this.serializeStructure(rules.members, params, xml);
  } else if (rules.type === 'list') {
    this.serializeList(name, rules, params, xml);
  } else if (rules.type === 'timestamp') {
    var timestampFormat = rules.format || this.timestampFormat;
    var date = ALY.util.date.format(params, timestampFormat);
    xml = xml.ele(name, String(date));
  } else {
    xml = xml.ele(name, String(params));
  }
  this.applyNamespaces(xml, rules);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeStructure"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>serializeStructure (rules, params, xml)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.serializeStructure)
- description and source-code
```javascript
function serializeStructure(rules, params, xml) {
  ALY.util.each.call(this, rules || {}, function (memberName, memberRules) {
    var value = params[memberName];
    if (value !== undefined) {
      if (memberRules.attribute) {
        xml.att(memberRules.name, value);
      } else {
        this.serializeMember(memberName, memberRules, value, xml);
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Builder.prototype.toXML"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Builder.prototype.</span>toXML (params)](#apidoc.element.aliyun-sdk.XML.Builder.prototype.toXML)
- description and source-code
```javascript
function toXML(params) {
  var xml = builder.create(this.root);
  if (this.xmlns) xml.att('xmlns', this.xmlns);
  this.serializeStructure(this.rules, params, xml);
  return xml.root().toString();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.XML.Parser"></a>[module aliyun-sdk.XML.Parser](#apidoc.module.aliyun-sdk.XML.Parser)

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.Parser"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.</span>Parser (rules)](#apidoc.element.aliyun-sdk.XML.Parser.Parser)
- description and source-code
```javascript
function XMLParser(rules) {
  this.rules = (rules || {}).members || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.</span>__super__ ()](#apidoc.element.aliyun-sdk.XML.Parser.__super__)
- description and source-code
```javascript
function Object() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.XML.Parser.prototype"></a>[module aliyun-sdk.XML.Parser.prototype](#apidoc.module.aliyun-sdk.XML.Parser.prototype)

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>constructor (rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.constructor)
- description and source-code
```javascript
function XMLParser(rules) {
  this.rules = (rules || {}).members || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.prototype.parse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parse (xml)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parse)
- description and source-code
```javascript
function parse(xml) {

  var result = null;
  var error = null;
  var parser = new xml2js.Parser(this.options);
  parser.parseString(xml, function (e, r) {
    error = e;
    result = r;
  });

  if (result) {
    delete result.xmlns;
    return this.parseStructure(result, this.rules);
  } else if (error) {
    throw ALY.util.error(error, {code: 'XMLParserError'});
  } else { // empty xml document
    return this.parseStructure({}, this.rules);
  }

}
```
- example usage
```shell
...
var path = __dirname + '/../apis/' + file + '.json';
try {
  if(ALY.util.isBrowser()) {
    svc.prototype.api = require(file + '.json');
  }
  else {
    var fs = require('fs');
    svc.prototype.api = JSON.parse(fs.readFileSync(path));
  }
} catch (err) {
  throw ALY.util.error(err, {
    message: 'Could not find API configuration ' + file
  });
}
...
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.prototype.parseList"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseList (list, rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseList)
- description and source-code
```javascript
function parseList(list, rules) {
  var data = [];
  var memberRules = rules.members || {};
  var memberName = memberRules.name || 'member';
  if (rules.flattened) {
    ALY.util.arrayEach.call(this, list, function (value) {
      data.push(this.parseMember([value], memberRules));
    });
  } else {
    ALY.util.arrayEach.call(this, list, function (member) {
      ALY.util.arrayEach.call(this, member[memberName], function (value) {
        data.push(this.parseMember([value], memberRules));
      });
    });
  }
  return data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.prototype.parseMap"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseMap (map, rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseMap)
- description and source-code
```javascript
function parseMap(map, rules) {
  var data = {};
  var keyRules = rules.keys || {};
  var valueRules = rules.members || {};
  var keyName = keyRules.name || 'key';
  var valueName = valueRules.name || 'value';
  if (!rules.flattened) {
    map = map[0].entry;
  }
  ALY.util.arrayEach.call(this, map, function (entry) {
    var value = this.parseMember(entry[valueName], valueRules);
    data[entry[keyName][0]] = value;
  });
  return data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.prototype.parseMember"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseMember (values, rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseMember)
- description and source-code
```javascript
function parseMember(values, rules) {
<span class="apidocCodeCommentSpan">  /*jshint maxcomplexity:20*/
</span>
  if (values[0] === null) {
    if (rules.type === 'structure') return {};
    if (rules.type === 'list') return [];
    if (rules.type === 'map') return {};
    return null;
  }

  if (values[0]['$'] && values[0]['$'].encoding == 'base64') {
    return ALY.util.base64.decode(values[0]['_']);
  }

  if (!rules.type) {
    if (typeof values[0] === 'string') {
      rules.type = 'string';
    } else if (values[0]['_']) {
      rules.type = 'string';
      values = [values[0]['_']];
    } else {
      rules.type = 'structure';
    }
  }

  if (rules.type === 'string') {

    return values[0];

  } else if (rules.type === 'structure') {

    return this.parseStructure(values[0], rules.members || {});

  } else if (rules.type === 'list') {

    return this.parseList(values, rules);

  } else if (rules.type === 'map') {

    return this.parseMap(values, rules);

  } else if (rules.type === 'integer') {

    return parseInt(values[0], 10);

  } else if (rules.type === 'float') {

    return parseFloat(values[0]);

  } else if (rules.type === 'timestamp') {

    return this.parseTimestamp(values[0]);

  } else if (rules.type === 'boolean') {

    return values[0] === 'true';

  } else {

    var msg = 'unhandled type: ' + rules.type;
    throw ALY.util.error(new Error(msg), {code: 'XMLParserError'});

  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.prototype.parseStructure"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseStructure (structure, rules)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseStructure)
- description and source-code
```javascript
function parseStructure(structure, rules) {
  var data = {};

  // force array members to always be present
  ALY.util.each.call(this, rules, function(memberName, memberRules) {
    if (memberRules.type == 'list') {
      data[memberRules.name || memberName] = [];
    }
  });

  ALY.util.each.call(this, structure, function (xmlName, value) {
    if (xmlName == '$') {
      ALY.util.each.call(this, value, function (attrName, attrValue) {
        if (rules[attrName]) {
          var rule = rules[attrName];
          data[rule.name || xmlName] = this.parseMember([attrValue], rule);
        }
      });
    } else {
      var rule = rules[xmlName] || {};
      data[rule.name || xmlName] = this.parseMember(value, rule);
    }
  });

  return data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.XML.Parser.prototype.parseTimestamp"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.XML.Parser.prototype.</span>parseTimestamp (value)](#apidoc.element.aliyun-sdk.XML.Parser.prototype.parseTimestamp)
- description and source-code
```javascript
function parseTimestamp(value) {

  if (value.match(/^\d+$/)) { // unix timestamp

    return new Date(value * 1000);

  } else if (value.match(/^\d{4}/)) { // iso8601

    return new Date(value);

  } else if (value.match(/^\w{3},/)) { // rfc822

    return new Date(value);

  } else {

    throw ALY.util.error(
      new Error('unhandled timestamp format: ' + value),
      {code: 'TimestampParserError'});

  }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.YunDun"></a>[module aliyun-sdk.YunDun](#apidoc.module.aliyun-sdk.YunDun)

#### <a name="apidoc.element.aliyun-sdk.YunDun.YunDun"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.</span>YunDun ()](#apidoc.element.aliyun-sdk.YunDun.YunDun)
- description and source-code
```javascript
YunDun = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.YunDun.__super__"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.YunDun.</span>__super__ (config)](#apidoc.element.aliyun-sdk.YunDun.__super__)
- description and source-code
```javascript
function Service(config) {
  if (!this.loadServiceClass) {
    throw ALY.util.error(new Error(),
      'Service must be constructed with 'new\' operator');
  }
  var ServiceClass = this.loadServiceClass(config || {});
  if (ServiceClass) return new ServiceClass(config);
  this.initialize(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.YunDun.prototype"></a>[module aliyun-sdk.YunDun.prototype](#apidoc.module.aliyun-sdk.YunDun.prototype)

#### <a name="apidoc.element.aliyun-sdk.YunDun.prototype.constructor"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.YunDun.prototype.</span>constructor ()](#apidoc.element.aliyun-sdk.YunDun.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
  if (klass !== Object) {
    return klass.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.api_loader"></a>[module aliyun-sdk.api_loader](#apidoc.module.aliyun-sdk.api_loader)

#### <a name="apidoc.element.aliyun-sdk.api_loader.serviceFile"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceFile (svc, version)](#apidoc.element.aliyun-sdk.api_loader.serviceFile)
- description and source-code
```javascript
function serviceFile(svc, version) {
  buildServiceMap();
  svc = serviceIdentifier(svc);
  if (!serviceMap[svc]) return null;

  var prefix = serviceMap[svc].prefix || svc;
  var filePath;
  ['min', 'api', 'normal'].some(function(testSuffix) {
    filePath = apiRoot + '/' + prefix.toLowerCase() + '-' + version + '.' +
        testSuffix + '.json';

    return fs.existsSync(filePath);
  });
  return filePath;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.api_loader.serviceIdentifier"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceIdentifier (svc)](#apidoc.element.aliyun-sdk.api_loader.serviceIdentifier)
- description and source-code
```javascript
function serviceIdentifier(svc) {
  return svc.toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.api_loader.serviceName"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceName (svc)](#apidoc.element.aliyun-sdk.api_loader.serviceName)
- description and source-code
```javascript
function serviceName(svc) {
  buildServiceMap();
  svc = serviceIdentifier(svc);
  return serviceMap[svc] ? serviceMap[svc].name : null;
}
```
- example usage
```shell
...
//ALY.CDN = ALY.Service.defineService('cdn', ['2014-11-11']);
//ALY.STS = ALY.Service.defineService('sts', ['2015-04-01']);

var apis = require('./api_loader');

// define services using map
apis.services.forEach(function(identifier) {
  var name = apis.serviceName(identifier);
  var versions = apis.serviceVersions(identifier);
  ALY[name] = ALY.Service.defineService(identifier, versions);

  // load any customizations from lib/services/<svcidentifier>.js
  var svcFile = path.join(__dirname, 'services', identifier + '.js');
  if (fs.existsSync(svcFile)) require('./services/' + identifier);
});
...
```

#### <a name="apidoc.element.aliyun-sdk.api_loader.serviceVersions"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.api_loader.</span>serviceVersions (svc)](#apidoc.element.aliyun-sdk.api_loader.serviceVersions)
- description and source-code
```javascript
function serviceVersions(svc) {
  buildServiceMap();
  svc = serviceIdentifier(svc);
  return serviceMap[svc] ? serviceMap[svc].versions : null;
}
```
- example usage
```shell
...
//ALY.STS = ALY.Service.defineService('sts', ['2015-04-01']);

var apis = require('./api_loader');

// define services using map
apis.services.forEach(function(identifier) {
  var name = apis.serviceName(identifier);
  var versions = apis.serviceVersions(identifier);
  ALY[name] = ALY.Service.defineService(identifier, versions);

  // load any customizations from lib/services/<svcidentifier>.js
  var svcFile = path.join(__dirname, 'services', identifier + '.js');
  if (fs.existsSync(svcFile)) require('./services/' + identifier);
});
...
```



# <a name="apidoc.module.aliyun-sdk.util"></a>[module aliyun-sdk.util](#apidoc.module.aliyun-sdk.util)

#### <a name="apidoc.element.aliyun-sdk.util.Buffer"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>Buffer (arg, encodingOrOffset, length)](#apidoc.element.aliyun-sdk.util.Buffer)
- description and source-code
```javascript
function Buffer(arg, encodingOrOffset, length) {
  // Common case.
  if (typeof arg === 'number') {
    if (typeof encodingOrOffset === 'string') {
      throw new Error(
        'If encoding is specified then the first argument must be a string'
      );
    }
    return Buffer.allocUnsafe(arg);
  }
  return Buffer.from(arg, encodingOrOffset, length);
}
```
- example usage
```shell
...
  progress(s);
});

add('HTTP_HEADERS', 'httpHeaders',
    function HTTP_HEADERS(statusCode, headers, resp) {
  resp.httpResponse.statusCode = statusCode;
  resp.httpResponse.headers = headers;
  resp.httpResponse.body = new ALY.util.Buffer('');
  resp.httpResponse.buffers = [];
  resp.httpResponse.numBytes = 0;
});

add('HTTP_DATA', 'httpData', function HTTP_DATA(chunk, resp) {
  if (chunk) {
    if (ALY.util.isNode()) {
...
```

#### <a name="apidoc.element.aliyun-sdk.util.arrayEach"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>arrayEach (array, iterFunction)](#apidoc.element.aliyun-sdk.util.arrayEach)
- description and source-code
```javascript
function arrayEach(array, iterFunction) {
  for (var idx in array) {
    if (array.hasOwnProperty(idx)) {
      var ret = iterFunction.call(this, array[idx], parseInt(idx, 10));
      if (ret === ALY.util.abort) break;
    }
  }
}
```
- example usage
```shell
...
    if (err) return callback(err, null);
    if (data === null) return callback(null, null);

    var config = this.request.service.paginationConfig(this.request.operation);
    var resultKey = config.resultKey;
    if (Array.isArray(resultKey)) resultKey = resultKey[0];
    var results = ALY.util.jamespath.query(resultKey, data);
    ALY.util.arrayEach(results, function(result) {
      ALY.util.arrayEach(result, function(item) { callback(null, item); });
    });
  }

  this.eachPage(wrappedCallback);
},
...
```

#### <a name="apidoc.element.aliyun-sdk.util.copy"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>copy (object)](#apidoc.element.aliyun-sdk.util.copy)
- description and source-code
```javascript
function copy(object) {
  if (object === null || object === undefined) return object;
  var dupe = {};
<span class="apidocCodeCommentSpan">  /*jshint forin:false */
</span>  for (var key in object) {
    dupe[key] = object[key];
  }
  return dupe;
}
```
- example usage
```shell
...

if (!this.hasNextPage()) {
  if (callback) callback(this.error, null);
  else if (this.error) throw this.error;
  return null;
}

var params = ALY.util.copy(this.request.params);
if (!this.nextPageTokens) {
  return callback ? callback(null, null) : null;
} else {
  var inputTokens = config.inputToken;
  if (typeof inputTokens === 'string') inputTokens = [inputTokens];
  for (var i = 0; i < inputTokens.length; i++) {
    params[inputTokens[i]] = this.nextPageTokens[i];
...
```

#### <a name="apidoc.element.aliyun-sdk.util.each"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>each (object, iterFunction)](#apidoc.element.aliyun-sdk.util.each)
- description and source-code
```javascript
function each(object, iterFunction) {
  for (var key in object) {
    if (object.hasOwnProperty(key)) {
      var ret = iterFunction.call(this, key, object[key]);
      if (ret === ALY.util.abort) break;
    }
  }
}
```
- example usage
```shell
...
   */
  addListeners: function addListeners(listeners) {
var self = this;

// extract listeners if parameter is an SequentialExecutor object
if (listeners._events) listeners = listeners._events;

ALY.util.each(listeners, function(event, callbacks) {
  if (typeof callbacks === 'function') callbacks = [callbacks];
  ALY.util.arrayEach(callbacks, function(callback) {
    self.on(event, callback);
  });
});

return self;
...
```

#### <a name="apidoc.element.aliyun-sdk.util.engine"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>engine ()](#apidoc.element.aliyun-sdk.util.engine)
- description and source-code
```javascript
function engine() {
  if (ALY.util.isBrowser() && typeof navigator !== 'undefined') {
    return navigator.userAgent;
  } else {
    return process.platform + '/' + process.version;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.error"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>error (err, options)](#apidoc.element.aliyun-sdk.util.error)
- description and source-code
```javascript
function error(err, options) {
  var originalError = null;
  if (typeof err.message === 'string' && err.message !== '') {
    if (typeof options === 'string' || (options && options.message)) {
      originalError = ALY.util.copy(err);
      originalError.message = err.message;
    }
  }
  err.message = err.message || null;

  if (typeof options === 'string') {
    err.message = options;
  }
  else if (typeof options === 'object') {
    ALY.util.update(err, options);
    if (options.message)
      err.message = options.message;
    if (options.code || options.name)
      err.code = options.code || options.name;
    if (options.stack)
      err.stack = options.stack;
  }

  if (typeof Object.defineProperty === 'function') {
    Object.defineProperty(err, 'name', {writable: true, enumerable: false});
    Object.defineProperty(err, 'message', {enumerable: true});
  }

  err.name = err.name || err.code || 'Error';
  err.time = new Date();

  if (originalError) err.originalError = originalError;

  return err;
}
```
- example usage
```shell
...

add('VALIDATE_RESPONSE', 'validateResponse', function VALIDATE_RESPONSE(resp) {
  if (this.service.successfulResponse(resp, this)) {
    resp.data = {};
    resp.error = null;
  } else {
    resp.data = null;
    resp.error = ALY.util.error(new Error(),
      {code: 'UnknownError', message: 'An unknown error occurred.'});
  }
});

addAsync('SEND', 'send', function SEND(resp, done) {
  function callback(httpResp) {
    resp.httpResponse.stream = httpResp;
...
```

#### <a name="apidoc.element.aliyun-sdk.util.hideProperties"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>hideProperties (obj, props)](#apidoc.element.aliyun-sdk.util.hideProperties)
- description and source-code
```javascript
function hideProperties(obj, props) {
  if (typeof Object.defineProperty !== 'function') return;

  ALY.util.arrayEach(props, function (key) {
    Object.defineProperty(obj, key, {
      enumerable: false, writable: true, configurable: true });
  });
}
```
- example usage
```shell
...

var ALY = require('./core');
var inherit = ALY.util.inherit;

ALY.Endpoint = inherit({

  constructor: function Endpoint(endpoint) {
ALY.util.hideProperties(this, ['slashes', 'auth', 'hash', 'search', 'query']);

if (typeof endpoint === 'undefined' || endpoint === null) {
  throw new Error('Invalid endpoint: ' + endpoint);
}

if (!endpoint.match(/^http/)) {
  throw new Error('错误的 endpoint 格式, 需要以 http 或者 https 开头');
...
```

#### <a name="apidoc.element.aliyun-sdk.util.inherit"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>inherit (klass, features)](#apidoc.element.aliyun-sdk.util.inherit)
- description and source-code
```javascript
function inherit(klass, features) {
  var newObject = null;
  if (features === undefined) {
    features = klass;
    klass = Object;
    newObject = {};
  } else {
<span class="apidocCodeCommentSpan">    /*jshint newcap:false */
</span>    /*jshint camelcase:false */
    var ctor = function __ctor_wrapper__() {};
    ctor.prototype = klass.prototype;
    newObject = new ctor();
  }

  // constructor not supplied, create pass-through ctor
  if (features.constructor === Object) {
    features.constructor = function() {
      if (klass !== Object) {
        return klass.apply(this, arguments);
      }
    };
  }

  features.constructor.prototype = newObject;
  ALY.util.update(features.constructor.prototype, features);
  features.constructor.__super__ = klass;
  return features.constructor;
}
```
- example usage
```shell
...





var ALY = require('./core');

ALY.Config = ALY.util.inherit({

  constructor: function Config(options) {
if (options === undefined) options = {};

ALY.util.each.call(this, this.keys, function (key, value) {
  this.set(key, options[key], value);
});
...
```

#### <a name="apidoc.element.aliyun-sdk.util.isBrowser"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>isBrowser ()](#apidoc.element.aliyun-sdk.util.isBrowser)
- description and source-code
```javascript
function isBrowser() { return typeof window !== 'undefined'; }
```
- example usage
```shell
...
  this.body = '';
  this.endpoint = endpoint;
  this.region = region;
  this.setUserAgent();
},

setUserAgent: function setUserAgent() {
  //var prefix = ALY.util.isBrowser() ? 'X-Aly-' : '';
  //this.headers[prefix + 'User-Agent'] = ALY.util.userAgent();
  //this.headers['x-sdk-client'] = this.headers['User-Agent'] = ALY.util.userAgent();
  // pop 现在不支持 x-sdk-client 在浏览器设置
  this.headers['User-Agent'] = ALY.util.userAgent();
},

pathname: function pathname() {
...
```

#### <a name="apidoc.element.aliyun-sdk.util.isEmpty"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>isEmpty (obj)](#apidoc.element.aliyun-sdk.util.isEmpty)
- description and source-code
```javascript
function isEmpty(obj) {
  for (var prop in obj) {
    if (obj.hasOwnProperty(prop)) {
      return false;
    }
  }
  return true;
}
```
- example usage
```shell
...
  this.config = new ALY.Config(config);
},

/**
 * @api private
 */
loadServiceClass: function loadServiceClass(serviceConfig) {
  if (!ALY.util.isEmpty(this.api)) {
    return;
  } else if (!this.constructor.services) {
    return;
  } else {
    return this.getLatestServiceClass(serviceConfig.apiVersion);
  }
},
...
```

#### <a name="apidoc.element.aliyun-sdk.util.isNode"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>isNode ()](#apidoc.element.aliyun-sdk.util.isNode)
- description and source-code
```javascript
function isNode() { return !ALY.util.isBrowser(); }
```
- example usage
```shell
...
      resp.httpResponse.body = new ALY.util.Buffer('');
      resp.httpResponse.buffers = [];
      resp.httpResponse.numBytes = 0;
    });

    add('HTTP_DATA', 'httpData', function HTTP_DATA(chunk, resp) {
      if (chunk) {
if (ALY.util.isNode()) {
  resp.httpResponse.numBytes += chunk.length;

  var total = resp.httpResponse.headers['content-length'];
  var progress = { loaded: resp.httpResponse.numBytes, total: total };
  resp.request.emit('httpDownloadProgress', [progress, resp]);
}
...
```

#### <a name="apidoc.element.aliyun-sdk.util.isType"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>isType (obj, type)](#apidoc.element.aliyun-sdk.util.isType)
- description and source-code
```javascript
function isType(obj, type) {
  // handle cross-"frame" objects
  if (typeof type === 'function') type = ALY.util.typeName(type);
  return Object.prototype.toString.call(obj) === '[object ' + type + ']';
}
```
- example usage
```shell
...
for (var i = 0; i < acceptedTypes.length; i++) {
  if (typeof acceptedTypes[i] === 'string') {
    if (typeof value === acceptedTypes[i]) return;
  } else if (acceptedTypes[i] instanceof RegExp) {
    if ((value || '').toString().match(acceptedTypes[i])) return;
  } else {
    if (value instanceof acceptedTypes[i]) return;
    if (ALY.util.isType(value, acceptedTypes[i])) return;
    if (!type && !foundInvalidType) acceptedTypes = acceptedTypes.slice();
    acceptedTypes[i] = ALY.util.typeName(acceptedTypes[i]);
  }
  foundInvalidType = true;
}

var acceptedType = type;
...
```

#### <a name="apidoc.element.aliyun-sdk.util.merge"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>merge (obj1, obj2)](#apidoc.element.aliyun-sdk.util.merge)
- description and source-code
```javascript
function merge(obj1, obj2) {
  return ALY.util.update(ALY.util.copy(obj1), obj2);
}
```
- example usage
```shell
...
 * @api private
 */
ALY.ParamValidator = ALY.util.inherit({
validate: function validate(rules, params, context) {
  var cRules = (rules || {}).members || {};
  var payload = rules ? rules.xml : null;
  if (payload) {
    cRules = ALY.util.merge(cRules, (cRules[payload] || {}).members || {});
    delete cRules[payload];
  }

  return this.validateStructure(cRules, params || {}, context || 'params');
},

validateStructure: function validateStructure(rules, params, context) {
...
```

#### <a name="apidoc.element.aliyun-sdk.util.mixin"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>mixin ()](#apidoc.element.aliyun-sdk.util.mixin)
- description and source-code
```javascript
function mixin() {
  var klass = arguments[0];
  for (var i = 1; i < arguments.length; i++) {
<span class="apidocCodeCommentSpan">    /*jshint forin:false*/
</span>    for (var prop in arguments[i].prototype) {
      var fn = arguments[i].prototype[prop];
      if (prop != 'constructor') {
        klass.prototype[prop] = fn;
      }
    }
  }
  return klass;
}
```
- example usage
```shell
...
      return [this.response.error, this.response];
    default:
      return [this.response];
  }
}
});

ALY.util.mixin(ALY.Request, ALY.SequentialExecutor);

ALY.Response = inherit({

/**
 * @api private
 */
constructor: function Response(request) {
...
```

#### <a name="apidoc.element.aliyun-sdk.util.nodeRequire"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>nodeRequire (module)](#apidoc.element.aliyun-sdk.util.nodeRequire)
- description and source-code
```javascript
function nodeRequire(module) {
  if (ALY.util.isNode()) return require(module);
}
```
- example usage
```shell
...






var ALY = require('./core');
var domain = ALY.util.nodeRequire('domain');

/**
* @!method on(eventName, callback)
*   Registers an event listener callback for the event given by 'eventName'.
*   Parameters passed to the callback function depend on the individual event
*   being triggered. See the event documentation for those parameters.
*
...
```

#### <a name="apidoc.element.aliyun-sdk.util.opensearchEscape"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>opensearchEscape (clearString)](#apidoc.element.aliyun-sdk.util.opensearchEscape)
- description and source-code
```javascript
opensearchEscape = function (clearString) {
  // http://v8.googlecode.com/svn/trunk/src/uri.js
  return encodeURIComponent(clearString)
    .replace(/\!/gi, '%21')
    .replace(/\'/gi, '%27')
    .replace(/\(/gi, '%28')
    .replace(/\)/gi, '%29')
    .replace(/\*/gi, '%2A')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.popEscape"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>popEscape (clearString)](#apidoc.element.aliyun-sdk.util.popEscape)
- description and source-code
```javascript
popEscape = function (clearString) {
  clearString = clearString.toString();
  clearString = encodeURIComponent(clearString)
      .replace(/\!/gi, '%21')
      .replace(/\'/gi, '%27')
      .replace(/\(/gi, '%28')
      .replace(/\)/gi, '%29')
      .replace(/\*/gi, '%2A')
  return clearString;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.queryParamsToString"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>queryParamsToString (params)](#apidoc.element.aliyun-sdk.util.queryParamsToString)
- description and source-code
```javascript
function queryParamsToString(params) {
  var items = [];
  var escape = ALY.util.uriEscape;
  var sortedKeys = Object.keys(params).sort();

  ALY.util.arrayEach(sortedKeys, function(name) {
    var value = params[name];
    var ename = escape(name);
    var result = ename;
    if (Array.isArray(value)) {
      var vals = [];
      ALY.util.arrayEach(value, function(item) { vals.push(escape(item)); });
      result = ename + '=' + vals.sort().join('&' + ename + '=');
    } else if (value !== undefined && value !== null) {
      result = ename + '=' + escape(value);
    }
    items.push(result);
  });

  return items.join('&');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.readFileSync"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>readFileSync (path)](#apidoc.element.aliyun-sdk.util.readFileSync)
- description and source-code
```javascript
function readFileSync(path) {
  if (typeof window !== 'undefined') return null;
  return require('fs').readFileSync(path, 'utf-8');
}
```
- example usage
```shell
...
var path = __dirname + '/../apis/' + file + '.json';
try {
  if(ALY.util.isBrowser()) {
    svc.prototype.api = require(file + '.json');
  }
  else {
    var fs = require('fs');
    svc.prototype.api = JSON.parse(fs.readFileSync(path));
  }
} catch (err) {
  throw ALY.util.error(err, {
    message: 'Could not find API configuration ' + file
  });
}
...
```

#### <a name="apidoc.element.aliyun-sdk.util.topEscape"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>topEscape (clearString)](#apidoc.element.aliyun-sdk.util.topEscape)
- description and source-code
```javascript
topEscape = function (clearString) {
  var output = '';
  var x = 0;
  clearString = clearString.toString();
  var regex = /(^[a-zA-Z0-9-_.~]*)/;
  while (x < clearString.length) {
    var match = regex.exec(clearString.substr(x));
    if (match != null && match.length > 1 && match[1] != '') {
      output += match[1];
      x += match[1].length;
    } else {
      if (clearString[x] == ' ')
        output += '%20';
      else {
        var charCode = clearString.charCodeAt(x);
        var hexVal = charCode.toString(16);
        output += '%' + ( hexVal.length < 2 ? '0' : '' ) + hexVal.toUpperCase();
      }
      x++;
    }
  }
  return output;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.typeName"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>typeName (type)](#apidoc.element.aliyun-sdk.util.typeName)
- description and source-code
```javascript
function typeName(type) {
  if (type.hasOwnProperty('name')) return type.name;
  var str = type.toString();
  var match = str.match(/^\s*function (.+)\(/);
  return match ? match[1] : str;
}
```
- example usage
```shell
...
    if (typeof value === acceptedTypes[i]) return;
  } else if (acceptedTypes[i] instanceof RegExp) {
    if ((value || '').toString().match(acceptedTypes[i])) return;
  } else {
    if (value instanceof acceptedTypes[i]) return;
    if (ALY.util.isType(value, acceptedTypes[i])) return;
    if (!type && !foundInvalidType) acceptedTypes = acceptedTypes.slice();
    acceptedTypes[i] = ALY.util.typeName(acceptedTypes[i]);
  }
  foundInvalidType = true;
}

var acceptedType = type;
if (!acceptedType) {
  /*jshint regexp:false*/
...
```

#### <a name="apidoc.element.aliyun-sdk.util.update"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>update (obj1, obj2)](#apidoc.element.aliyun-sdk.util.update)
- description and source-code
```javascript
function update(obj1, obj2) {
  ALY.util.each(obj2, function iterator(key, item) {
    obj1[key] = item;
  });
  return obj1;
}
```
- example usage
```shell
...
  throw new Error('Invalid endpoint: ' + endpoint);
}

if (!endpoint.match(/^http/)) {
  throw new Error('错误的 endpoint 格式, 需要以 http 或者 https 开头');
}

ALY.util.update(this, ALY.util.urlParse(endpoint));

// Ensure the port property is set as an integer
if (this.port) {
  this.port = parseInt(this.port, 10);
} else {
  this.port = this.protocol === 'https:' ? 443 : 80;
}
...
```

#### <a name="apidoc.element.aliyun-sdk.util.uriEscape"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>uriEscape (string)](#apidoc.element.aliyun-sdk.util.uriEscape)
- description and source-code
```javascript
function uriEscape(string) {
<span class="apidocCodeCommentSpan">  /*jshint undef:false */
</span>  var output = encodeURIComponent(string);
  output = output.replace(/[^A-Za-z0-9_.~\-%]+/g, escape);

  // percent-encodes some extra non-standard characters in a URI
  output = output.replace(/[*]/g, function(ch) {
    return '%' + ch.charCodeAt(0).toString(16).toUpperCase();
  });

  return output;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.uriEscapePath"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>uriEscapePath (string)](#apidoc.element.aliyun-sdk.util.uriEscapePath)
- description and source-code
```javascript
function uriEscapePath(string) {
  var parts = [];
  ALY.util.arrayEach(string.split('/'), function (part) {
    parts.push(ALY.util.uriEscape(part));
  });
  return parts.join('/');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.urlFormat"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>urlFormat (url)](#apidoc.element.aliyun-sdk.util.urlFormat)
- description and source-code
```javascript
function urlFormat(url) {
  return require('url').format(url);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.urlParse"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>urlParse (url)](#apidoc.element.aliyun-sdk.util.urlParse)
- description and source-code
```javascript
function urlParse(url) {
  return require('url').parse(url);
}
```
- example usage
```shell
...
  throw new Error('Invalid endpoint: ' + endpoint);
}

if (!endpoint.match(/^http/)) {
  throw new Error('错误的 endpoint 格式, 需要以 http 或者 https 开头');
}

ALY.util.update(this, ALY.util.urlParse(endpoint));

// Ensure the port property is set as an integer
if (this.port) {
  this.port = parseInt(this.port, 10);
} else {
  this.port = this.protocol === 'https:' ? 443 : 80;
}
...
```

#### <a name="apidoc.element.aliyun-sdk.util.userAgent"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>userAgent ()](#apidoc.element.aliyun-sdk.util.userAgent)
- description and source-code
```javascript
function userAgent() {
  var name = ALY.util.isBrowser() ? 'js' : 'nodejs';
  var agent = 'aliyun-sdk-' + name + '/' + require('../package.json').version + '(' + os.platform() + '/'
    + os.release() + '/' + os.arch() + ';' + process.version + ')';
  return agent;
}
```
- example usage
```shell
...
  this.endpoint = endpoint;
  this.region = region;
  this.setUserAgent();
},

setUserAgent: function setUserAgent() {
  //var prefix = ALY.util.isBrowser() ? 'X-Aly-' : '';
  //this.headers[prefix + 'User-Agent'] = ALY.util.userAgent();
  //this.headers['x-sdk-client'] = this.headers['User-Agent'] = ALY.util.userAgent();
  // pop 现在不支持 x-sdk-client 在浏览器设置
  this.headers['User-Agent'] = ALY.util.userAgent();
},

pathname: function pathname() {
  return this.path.split('?', 1)[0];
...
```

#### <a name="apidoc.element.aliyun-sdk.util.uuid"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>uuid ()](#apidoc.element.aliyun-sdk.util.uuid)
- description and source-code
```javascript
function generateUUID(){
  var d = new Date().getTime();
  if(window.performance && typeof window.performance.now === "function"){
    d += performance.now(); //use high-precision timer if available
  }
  var uuid = 'xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx'.replace(/[xy]/g, function(c) {
    var r = (d + Math.random()*16)%16 | 0;
    d = Math.floor(d/16);
    return (c=='x' ? r : (r&0x3|0x8)).toString(16);
  });
  return uuid;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.util.Buffer"></a>[module aliyun-sdk.util.Buffer](#apidoc.module.aliyun-sdk.util.Buffer)

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.Buffer"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.</span>Buffer (arg, encodingOrOffset, length)](#apidoc.element.aliyun-sdk.util.Buffer.Buffer)
- description and source-code
```javascript
function Buffer(arg, encodingOrOffset, length) {
  // Common case.
  if (typeof arg === 'number') {
    if (typeof encodingOrOffset === 'string') {
      throw new Error(
        'If encoding is specified then the first argument must be a string'
      );
    }
    return Buffer.allocUnsafe(arg);
  }
  return Buffer.from(arg, encodingOrOffset, length);
}
```
- example usage
```shell
...
  progress(s);
});

add('HTTP_HEADERS', 'httpHeaders',
    function HTTP_HEADERS(statusCode, headers, resp) {
  resp.httpResponse.statusCode = statusCode;
  resp.httpResponse.headers = headers;
  resp.httpResponse.body = new ALY.util.Buffer('');
  resp.httpResponse.buffers = [];
  resp.httpResponse.numBytes = 0;
});

add('HTTP_DATA', 'httpData', function HTTP_DATA(chunk, resp) {
  if (chunk) {
    if (ALY.util.isNode()) {
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.alloc"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>alloc (size, fill, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.alloc)
- description and source-code
```javascript
alloc = function (size, fill, encoding) {
  assertSize(size);
  if (size > 0 && fill !== undefined) {
    // Since we are filling anyway, don't zero fill initially.
    // Only pay attention to encoding if it's a string. This
    // prevents accidentally sending in a number that would
    // be interpretted as a start offset.
    if (typeof encoding !== 'string')
      encoding = undefined;
    return createUnsafeBuffer(size).fill(fill, encoding);
  }
  return new FastBuffer(size);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.allocUnsafe"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>allocUnsafe (size)](#apidoc.element.aliyun-sdk.util.Buffer.allocUnsafe)
- description and source-code
```javascript
allocUnsafe = function (size) {
  assertSize(size);
  return allocate(size);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.allocUnsafeSlow"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>allocUnsafeSlow (size)](#apidoc.element.aliyun-sdk.util.Buffer.allocUnsafeSlow)
- description and source-code
```javascript
allocUnsafeSlow = function (size) {
  assertSize(size);
  return createUnsafeBuffer(size);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.byteLength"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>byteLength (string, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.byteLength)
- description and source-code
```javascript
function byteLength(string, encoding) {
  if (typeof string !== 'string') {
    if (ArrayBuffer.isView(string) || isArrayBuffer(string) ||
        isSharedArrayBuffer(string)) {
      return string.byteLength;
    }

    string = '' + string;
  }

  var len = string.length;
  if (len === 0)
    return 0;

  // Use a for loop to avoid recursion
  var loweredCase = false;
  for (;;) {
    switch (encoding) {
      case 'ascii':
      case 'latin1':
      case 'binary':
        return len;

      case 'utf8':
      case 'utf-8':
      case undefined:
        return binding.byteLengthUtf8(string);

      case 'ucs2':
      case 'ucs-2':
      case 'utf16le':
      case 'utf-16le':
        return len * 2;

      case 'hex':
        return len >>> 1;

      case 'base64':
        return base64ByteLength(string, len);

      default:
        // The C++ binding defaulted to UTF8, we should too.
        if (loweredCase)
          return binding.byteLengthUtf8(string);

        encoding = ('' + encoding).toLowerCase();
        loweredCase = true;
    }
  }
}
```
- example usage
```shell
...
add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
  if (req.httpRequest.headers['Content-Length'] === undefined) {
    var length = ALY.util.string.byteLength(req.httpRequest.body);
    req.httpRequest.headers['Content-Length'] = length;
  }
});

add('SET_HTTP_HOST', 'afterBuild', function SET_HTTP_HOST(req) {
  req.httpRequest.headers['Host'] = req.httpRequest.endpoint.host;
});
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.compare"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>compare (a, b)](#apidoc.element.aliyun-sdk.util.Buffer.compare)
- description and source-code
```javascript
function compare(a, b) {
  if (!(a instanceof Buffer) ||
      !(b instanceof Buffer)) {
    throw new TypeError('Arguments must be Buffers');
  }

  if (a === b) {
    return 0;
  }

  return binding.compare(a, b);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.concat"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>concat (list, length)](#apidoc.element.aliyun-sdk.util.Buffer.concat)
- description and source-code
```javascript
concat = function (list, length) {
  var i;
  if (!Array.isArray(list))
    throw new TypeError('"list" argument must be an Array of Buffers');

  if (list.length === 0)
    return new FastBuffer();

  if (length === undefined) {
    length = 0;
    for (i = 0; i < list.length; i++)
      length += list[i].length;
  } else {
    length = length >>> 0;
  }

  var buffer = Buffer.allocUnsafe(length);
  var pos = 0;
  for (i = 0; i < list.length; i++) {
    var buf = list[i];
    if (!Buffer.isBuffer(buf))
      throw new TypeError('"list" argument must be an Array of Buffers');
    buf.copy(buffer, pos);
    pos += buf.length;
  }

  // Note: 'length' is always equal to 'buffer.length' at this point
  if (pos < length) {
    // Zero-fill the remaining bytes if the specified 'length' was more than
    // the actual total length, i.e. if we have some remaining allocated bytes
    // there were not initialized.
    buffer.fill(0, pos, length);
  }

  return buffer;
}
```
- example usage
```shell
...
    resp.httpResponse.buffers.push(new ALY.util.Buffer(chunk));
  }
});

add('HTTP_DONE', 'httpDone', function HTTP_DONE(resp) {
  // convert buffers array into single buffer
  if (resp.httpResponse.buffers && resp.httpResponse.buffers.length > 0) {
    var body = ALY.util.buffer.concat(resp.httpResponse.buffers);
    resp.httpResponse.body = body;
  }
  delete resp.httpResponse.numBytes;
  delete resp.httpResponse.buffers;
});

add('FINALIZE_ERROR', 'retry', function FINALIZE_ERROR(resp) {
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.from"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>from (value, encodingOrOffset, length)](#apidoc.element.aliyun-sdk.util.Buffer.from)
- description and source-code
```javascript
from = function (value, encodingOrOffset, length) {
  if (typeof value === 'number')
    throw new TypeError('"value" argument must not be a number');

  if (isArrayBuffer(value) || isSharedArrayBuffer(value))
    return fromArrayBuffer(value, encodingOrOffset, length);

  if (typeof value === 'string')
    return fromString(value, encodingOrOffset);

  return fromObject(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.isBuffer"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>isBuffer (b)](#apidoc.element.aliyun-sdk.util.Buffer.isBuffer)
- description and source-code
```javascript
function isBuffer(b) {
  return b instanceof Buffer;
}
```
- example usage
```shell
...
  validatePayload: function validatePayload(context, value) {
/*jshint maxcomplexity:14*/
if (value === null || value === undefined) return;
if (typeof value === 'string') return;
if (value && typeof value.byteLength === 'number') return; // typed arrays
if (ALY.util.isNode()) { // special check for buffer/stream in Node.js
  var Stream = require('stream').Stream;
  if (ALY.util.Buffer.isBuffer(value) || value instanceof Stream) return;
}

var types = ['Buffer', 'Stream', 'File', 'Blob', 'ArrayBuffer', 'DataView'];
if (value) {
  for (var i = 0; i < types.length; i++) {
    if (ALY.util.isType(value, types[i])) return;
    if (ALY.util.typeName(value.constructor) === types[i]) return;
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.isEncoding"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.</span>isEncoding (encoding)](#apidoc.element.aliyun-sdk.util.Buffer.isEncoding)
- description and source-code
```javascript
isEncoding = function (encoding) {
  return typeof encoding === 'string' &&
         typeof internalUtil.normalizeEncoding(encoding) === 'string';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.util.Buffer.prototype"></a>[module aliyun-sdk.util.Buffer.prototype](#apidoc.module.aliyun-sdk.util.Buffer.prototype)

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.asciiSlice"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>asciiSlice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.asciiSlice)
- description and source-code
```javascript
function asciiSlice() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.asciiWrite"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>asciiWrite ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.asciiWrite)
- description and source-code
```javascript
function asciiWrite() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.base64Slice"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>base64Slice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.base64Slice)
- description and source-code
```javascript
function base64Slice() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.base64Write"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>base64Write ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.base64Write)
- description and source-code
```javascript
function base64Write() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.compare"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>compare (target, start, end, thisStart, thisEnd)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.compare)
- description and source-code
```javascript
function compare(target, start, end, thisStart, thisEnd) {

  if (!(target instanceof Buffer))
    throw new TypeError('Argument must be a Buffer');
  if (arguments.length === 1)
    return compare_(this, target);

  if (start === undefined)
    start = 0;
  else if (start < 0)
    throw new RangeError('out of range index');
  else
    start >>>= 0;

  if (end === undefined)
    end = target.length;
  else if (end > target.length)
    throw new RangeError('out of range index');
  else
    end >>>= 0;

  if (thisStart === undefined)
    thisStart = 0;
  else if (thisStart < 0)
    throw new RangeError('out of range index');
  else
    thisStart >>>= 0;

  if (thisEnd === undefined)
    thisEnd = this.length;
  else if (thisEnd > this.length)
    throw new RangeError('out of range index');
  else
    thisEnd >>>= 0;

  if (thisStart >= thisEnd)
    return (start >= end ? 0 : -1);
  else if (start >= end)
    return 1;

  return compareOffset(this, target, start, thisStart, end, thisEnd);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.copy"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>copy ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.copy)
- description and source-code
```javascript
function copy() { [native code] }
```
- example usage
```shell
...

if (!this.hasNextPage()) {
  if (callback) callback(this.error, null);
  else if (this.error) throw this.error;
  return null;
}

var params = ALY.util.copy(this.request.params);
if (!this.nextPageTokens) {
  return callback ? callback(null, null) : null;
} else {
  var inputTokens = config.inputToken;
  if (typeof inputTokens === 'string') inputTokens = [inputTokens];
  for (var i = 0; i < inputTokens.length; i++) {
    params[inputTokens[i]] = this.nextPageTokens[i];
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.equals"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>equals (b)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.equals)
- description and source-code
```javascript
function equals(b) {
  if (!(b instanceof Buffer))
    throw new TypeError('Argument must be a Buffer');

  if (this === b)
    return true;

  return binding.compare(this, b) === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.fill"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>fill (val, start, end, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.fill)
- description and source-code
```javascript
function fill(val, start, end, encoding) {
  // Handle string cases:
  if (typeof val === 'string') {
    if (typeof start === 'string') {
      encoding = start;
      start = 0;
      end = this.length;
    } else if (typeof end === 'string') {
      encoding = end;
      end = this.length;
    }

    if (encoding !== undefined && typeof encoding !== 'string') {
      throw new TypeError('encoding must be a string');
    }
    var normalizedEncoding = internalUtil.normalizeEncoding(encoding);
    if (normalizedEncoding === undefined) {
      throw new TypeError('Unknown encoding: ' + encoding);
    }

    if (val.length === 0) {
      // Previously, if val === '', the Buffer would not fill,
      // which is rather surprising.
      val = 0;
    } else if (val.length === 1) {
      var code = val.charCodeAt(0);
      if ((normalizedEncoding === 'utf8' && code < 128) ||
          normalizedEncoding === 'latin1') {
        // Fast path: If 'val' fits into a single byte, use that numeric value.
        val = code;
      }
    }
  } else if (typeof val === 'number') {
    val = val & 255;
  }

  // Invalid ranges are not set to a default, so can range check early.
  if (start < 0 || end > this.length)
    throw new RangeError('Out of range index');

  if (end <= start)
    return this;

  start = start >>> 0;
  end = end === undefined ? this.length : end >>> 0;

  binding.fill(this, val, start, end, encoding);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.hexSlice"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>hexSlice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.hexSlice)
- description and source-code
```javascript
function hexSlice() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.hexWrite"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>hexWrite ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.hexWrite)
- description and source-code
```javascript
function hexWrite() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.includes"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>includes (val, byteOffset, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.includes)
- description and source-code
```javascript
function includes(val, byteOffset, encoding) {
  return this.indexOf(val, byteOffset, encoding) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.indexOf"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>indexOf (val, byteOffset, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.indexOf)
- description and source-code
```javascript
function indexOf(val, byteOffset, encoding) {
  return bidirectionalIndexOf(this, val, byteOffset, encoding, true);
}
```
- example usage
```shell
...
      serviceMap[id] = {};
    }

    //console.log("loading", file);
    serviceMap[id].name = require(apiRoot + "/" + file).serviceAbbreviation;

    serviceMap[id].versions = serviceMap[id].versions || [];
    if (serviceMap[id].versions.indexOf(version) < 0) {
      serviceMap[id].versions.push(version);
    }
  }
});

Object.keys(serviceMap).forEach(function(identifier) {
  serviceMap[identifier].versions = serviceMap[identifier].versions.sort();
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.inspect"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>inspect ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.inspect)
- description and source-code
```javascript
function inspect() {
  var str = '';
  var max = exports.INSPECT_MAX_BYTES;
  if (this.length > 0) {
    str = this.toString('hex', 0, max).match(/.{2}/g).join(' ');
    if (this.length > max)
      str += ' ... ';
  }
  return '<' + this.constructor.name + ' ' + str + '>';
}
```
- example usage
```shell
...
      if (!logger) return;

      function buildMessage() {
var time = ALY.util.date.getDate().getTime();
var delta = (time - req.startTime.getTime()) / 1000;
var ansi = logger.isTTY ? true : false;
var status = resp.httpResponse.statusCode;
var params = require('util').inspect(req.params, true, true);

var message = '';
if (ansi) message += '\x1B[33m';
message += '[ALY ' + req.service.serviceIdentifier + ' ' + status;
message += ' ' + delta.toString() + 's ' + resp.retryCount + ' retries]';
if (ansi) message += '\x1B[0;1m';
message += ' ' + req.operation + '(' + params + ')';
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.lastIndexOf"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>lastIndexOf (val, byteOffset, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.lastIndexOf)
- description and source-code
```javascript
function lastIndexOf(val, byteOffset, encoding) {
  return bidirectionalIndexOf(this, val, byteOffset, encoding, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.latin1Slice"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>latin1Slice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.latin1Slice)
- description and source-code
```javascript
function latin1Slice() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.latin1Write"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>latin1Write ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.latin1Write)
- description and source-code
```javascript
function latin1Write() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readDoubleBE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readDoubleBE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readDoubleBE)
- description and source-code
```javascript
function readDoubleBE(offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 8, this.length);
  return binding.readDoubleBE(this, offset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readDoubleLE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readDoubleLE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readDoubleLE)
- description and source-code
```javascript
function readDoubleLE(offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 8, this.length);
  return binding.readDoubleLE(this, offset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readFloatBE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readFloatBE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readFloatBE)
- description and source-code
```javascript
function readFloatBE(offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 4, this.length);
  return binding.readFloatBE(this, offset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readFloatLE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readFloatLE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readFloatLE)
- description and source-code
```javascript
function readFloatLE(offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 4, this.length);
  return binding.readFloatLE(this, offset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt16BE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt16BE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt16BE)
- description and source-code
```javascript
readInt16BE = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 2, this.length);
  var val = this[offset + 1] | (this[offset] << 8);
  return (val & 0x8000) ? val | 0xFFFF0000 : val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt16LE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt16LE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt16LE)
- description and source-code
```javascript
readInt16LE = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 2, this.length);
  var val = this[offset] | (this[offset + 1] << 8);
  return (val & 0x8000) ? val | 0xFFFF0000 : val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt32BE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt32BE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt32BE)
- description and source-code
```javascript
readInt32BE = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 4, this.length);

  return (this[offset] << 24) |
      (this[offset + 1] << 16) |
      (this[offset + 2] << 8) |
      (this[offset + 3]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt32LE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt32LE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt32LE)
- description and source-code
```javascript
readInt32LE = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 4, this.length);

  return (this[offset]) |
      (this[offset + 1] << 8) |
      (this[offset + 2] << 16) |
      (this[offset + 3] << 24);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt8"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readInt8 (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readInt8)
- description and source-code
```javascript
readInt8 = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 1, this.length);
  var val = this[offset];
  return !(val & 0x80) ? val : (0xff - val + 1) * -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readIntBE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readIntBE (offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readIntBE)
- description and source-code
```javascript
readIntBE = function (offset, byteLength, noAssert) {
  offset = offset >>> 0;
  byteLength = byteLength >>> 0;
  if (!noAssert)
    checkOffset(offset, byteLength, this.length);

  var i = byteLength;
  var mul = 1;
  var val = this[offset + --i];
  while (i > 0 && (mul *= 0x100))
    val += this[offset + --i] * mul;
  mul *= 0x80;

  if (val >= mul)
    val -= Math.pow(2, 8 * byteLength);

  return val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readIntLE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readIntLE (offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readIntLE)
- description and source-code
```javascript
readIntLE = function (offset, byteLength, noAssert) {
  offset = offset >>> 0;
  byteLength = byteLength >>> 0;
  if (!noAssert)
    checkOffset(offset, byteLength, this.length);

  var val = this[offset];
  var mul = 1;
  var i = 0;
  while (++i < byteLength && (mul *= 0x100))
    val += this[offset + i] * mul;
  mul *= 0x80;

  if (val >= mul)
    val -= Math.pow(2, 8 * byteLength);

  return val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt16BE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt16BE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt16BE)
- description and source-code
```javascript
readUInt16BE = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 2, this.length);
  return (this[offset] << 8) | this[offset + 1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt16LE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt16LE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt16LE)
- description and source-code
```javascript
readUInt16LE = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 2, this.length);
  return this[offset] | (this[offset + 1] << 8);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt32BE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt32BE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt32BE)
- description and source-code
```javascript
readUInt32BE = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 4, this.length);

  return (this[offset] * 0x1000000) +
      ((this[offset + 1] << 16) |
      (this[offset + 2] << 8) |
      this[offset + 3]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt32LE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt32LE (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt32LE)
- description and source-code
```javascript
readUInt32LE = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 4, this.length);

  return ((this[offset]) |
      (this[offset + 1] << 8) |
      (this[offset + 2] << 16)) +
      (this[offset + 3] * 0x1000000);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt8"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUInt8 (offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUInt8)
- description and source-code
```javascript
readUInt8 = function (offset, noAssert) {
  offset = offset >>> 0;
  if (!noAssert)
    checkOffset(offset, 1, this.length);
  return this[offset];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readUIntBE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUIntBE (offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUIntBE)
- description and source-code
```javascript
readUIntBE = function (offset, byteLength, noAssert) {
  offset = offset >>> 0;
  byteLength = byteLength >>> 0;
  if (!noAssert)
    checkOffset(offset, byteLength, this.length);

  var val = this[offset + --byteLength];
  var mul = 1;
  while (byteLength > 0 && (mul *= 0x100))
    val += this[offset + --byteLength] * mul;

  return val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.readUIntLE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>readUIntLE (offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.readUIntLE)
- description and source-code
```javascript
readUIntLE = function (offset, byteLength, noAssert) {
  offset = offset >>> 0;
  byteLength = byteLength >>> 0;
  if (!noAssert)
    checkOffset(offset, byteLength, this.length);

  var val = this[offset];
  var mul = 1;
  var i = 0;
  while (++i < byteLength && (mul *= 0x100))
    val += this[offset + i] * mul;

  return val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.slice"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>slice (start, end)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.slice)
- description and source-code
```javascript
function slice(start, end) {
  const srcLength = this.length;
  start = adjustOffset(start, srcLength);
  end = end !== undefined ? adjustOffset(end, srcLength) : srcLength;
  const newLength = end > start ? end - start : 0;
  return new FastBuffer(this.buffer, this.byteOffset + start, newLength);
}
```
- example usage
```shell
...
  if (typeof acceptedTypes[i] === 'string') {
    if (typeof value === acceptedTypes[i]) return;
  } else if (acceptedTypes[i] instanceof RegExp) {
    if ((value || '').toString().match(acceptedTypes[i])) return;
  } else {
    if (value instanceof acceptedTypes[i]) return;
    if (ALY.util.isType(value, acceptedTypes[i])) return;
    if (!type && !foundInvalidType) acceptedTypes = acceptedTypes.slice();
    acceptedTypes[i] = ALY.util.typeName(acceptedTypes[i]);
  }
  foundInvalidType = true;
}

var acceptedType = type;
if (!acceptedType) {
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.swap16"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>swap16 ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.swap16)
- description and source-code
```javascript
function swap16() {
  // For Buffer.length < 128, it's generally faster to
  // do the swap in javascript. For larger buffers,
  // dropping down to the native code is faster.
  const len = this.length;
  if (len % 2 !== 0)
    throw new RangeError('Buffer size must be a multiple of 16-bits');
  if (len < 128) {
    for (var i = 0; i < len; i += 2)
      swap(this, i, i + 1);
    return this;
  }
  return swap16n(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.swap32"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>swap32 ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.swap32)
- description and source-code
```javascript
function swap32() {
  // For Buffer.length < 192, it's generally faster to
  // do the swap in javascript. For larger buffers,
  // dropping down to the native code is faster.
  const len = this.length;
  if (len % 4 !== 0)
    throw new RangeError('Buffer size must be a multiple of 32-bits');
  if (len < 192) {
    for (var i = 0; i < len; i += 4) {
      swap(this, i, i + 3);
      swap(this, i + 1, i + 2);
    }
    return this;
  }
  return swap32n(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.swap64"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>swap64 ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.swap64)
- description and source-code
```javascript
function swap64() {
  // For Buffer.length < 192, it's generally faster to
  // do the swap in javascript. For larger buffers,
  // dropping down to the native code is faster.
  const len = this.length;
  if (len % 8 !== 0)
    throw new RangeError('Buffer size must be a multiple of 64-bits');
  if (len < 192) {
    for (var i = 0; i < len; i += 8) {
      swap(this, i, i + 7);
      swap(this, i + 1, i + 6);
      swap(this, i + 2, i + 5);
      swap(this, i + 3, i + 4);
    }
    return this;
  }
  return swap64n(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>toJSON ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  if (this.length) {
    const data = [];
    for (var i = 0; i < this.length; ++i)
      data[i] = this[i];
    return { type: 'Buffer', data };
  } else {
    return { type: 'Buffer', data: [] };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.toString"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>toString ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.toString)
- description and source-code
```javascript
toString = function () {
  let result;
  if (arguments.length === 0) {
    result = this.utf8Slice(0, this.length);
  } else {
    result = slowToString.apply(this, arguments);
  }
  if (result === undefined)
    throw new Error('"toString()" failed');
  return result;
}
```
- example usage
```shell
...
  var ansi = logger.isTTY ? true : false;
  var status = resp.httpResponse.statusCode;
  var params = require('util').inspect(req.params, true, true);

  var message = '';
  if (ansi) message += '\x1B[33m';
  message += '[ALY ' + req.service.serviceIdentifier + ' ' + status;
  message += ' ' + delta.toString() + 's ' + resp.retryCount + ' retries]';
  if (ansi) message += '\x1B[0;1m';
  message += ' ' + req.operation + '(' + params + ')';
  if (ansi) message += '\x1B[0m';
  return message;
}

var message = buildMessage();
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.ucs2Slice"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>ucs2Slice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.ucs2Slice)
- description and source-code
```javascript
function ucs2Slice() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.ucs2Write"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>ucs2Write ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.ucs2Write)
- description and source-code
```javascript
function ucs2Write() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.utf8Slice"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>utf8Slice ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.utf8Slice)
- description and source-code
```javascript
function utf8Slice() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.utf8Write"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>utf8Write ()](#apidoc.element.aliyun-sdk.util.Buffer.prototype.utf8Write)
- description and source-code
```javascript
function utf8Write() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.write"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>write (string, offset, length, encoding)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.write)
- description and source-code
```javascript
write = function (string, offset, length, encoding) {
  // Buffer#write(string);
  if (offset === undefined) {
    encoding = 'utf8';
    length = this.length;
    offset = 0;

  // Buffer#write(string, encoding)
  } else if (length === undefined && typeof offset === 'string') {
    encoding = offset;
    length = this.length;
    offset = 0;

  // Buffer#write(string, offset[, length][, encoding])
  } else if (isFinite(offset)) {
    offset = offset >>> 0;
    if (isFinite(length)) {
      length = length >>> 0;
      if (encoding === undefined)
        encoding = 'utf8';
    } else {
      encoding = length;
      length = undefined;
    }
  } else {
    // if someone is still calling the obsolete form of write(), tell them.
    // we don't want eg buf.write("foo", "utf8", 10) to silently turn into
    // buf.write("foo", "utf8"), so we can't ignore extra args
    throw new Error('Buffer.write(string, encoding, offset[, length]) ' +
                    'is no longer supported');
  }

  var remaining = this.length - offset;
  if (length === undefined || length > remaining)
    length = remaining;

  if (string.length > 0 && (length < 0 || offset < 0))
    throw new RangeError('Attempt to write outside buffer bounds');

  if (!encoding)
    encoding = 'utf8';

  var loweredCase = false;
  for (;;) {
    switch (encoding) {
      case 'hex':
        return this.hexWrite(string, offset, length);

      case 'utf8':
      case 'utf-8':
        return this.utf8Write(string, offset, length);

      case 'ascii':
        return this.asciiWrite(string, offset, length);

      case 'latin1':
      case 'binary':
        return this.latin1Write(string, offset, length);

      case 'base64':
        // Warning: maxLength not taken into account in base64Write
        return this.base64Write(string, offset, length);

      case 'ucs2':
      case 'ucs-2':
      case 'utf16le':
      case 'utf-16le':
        return this.ucs2Write(string, offset, length);

      default:
        if (loweredCase)
          throw new TypeError('Unknown encoding: ' + encoding);
        encoding = ('' + encoding).toLowerCase();
        loweredCase = true;
    }
  }
}
```
- example usage
```shell
...
      return message;
    }

    var message = buildMessage();
    if (typeof logger.log === 'function') {
      logger.log(message);
    } else if (typeof logger.write === 'function') {
      logger.write(message + '\n');
    }
  });
}),

Json: new ALY.SequentialExecutor().addNamedListeners(function(add) {
  var svc = ALY.ServiceInterface.Json;
  add('BUILD', 'build', svc.buildRequest);
...
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeDoubleBE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeDoubleBE (val, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeDoubleBE)
- description and source-code
```javascript
function writeDoubleBE(val, offset, noAssert) {
  val = +val;
  offset = offset >>> 0;
  if (!noAssert)
    binding.writeDoubleBE(this, val, offset);
  else
    binding.writeDoubleBE(this, val, offset, true);
  return offset + 8;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeDoubleLE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeDoubleLE (val, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeDoubleLE)
- description and source-code
```javascript
function writeDoubleLE(val, offset, noAssert) {
  val = +val;
  offset = offset >>> 0;
  if (!noAssert)
    binding.writeDoubleLE(this, val, offset);
  else
    binding.writeDoubleLE(this, val, offset, true);
  return offset + 8;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeFloatBE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeFloatBE (val, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeFloatBE)
- description and source-code
```javascript
function writeFloatBE(val, offset, noAssert) {
  val = +val;
  offset = offset >>> 0;
  if (!noAssert)
    binding.writeFloatBE(this, val, offset);
  else
    binding.writeFloatBE(this, val, offset, true);
  return offset + 4;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeFloatLE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeFloatLE (val, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeFloatLE)
- description and source-code
```javascript
function writeFloatLE(val, offset, noAssert) {
  val = +val;
  offset = offset >>> 0;
  if (!noAssert)
    binding.writeFloatLE(this, val, offset);
  else
    binding.writeFloatLE(this, val, offset, true);
  return offset + 4;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt16BE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt16BE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt16BE)
- description and source-code
```javascript
writeInt16BE = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 2, 0x7fff, -0x8000);
  this[offset] = (value >>> 8);
  this[offset + 1] = value;
  return offset + 2;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt16LE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt16LE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt16LE)
- description and source-code
```javascript
writeInt16LE = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 2, 0x7fff, -0x8000);
  this[offset] = value;
  this[offset + 1] = (value >>> 8);
  return offset + 2;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt32BE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt32BE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt32BE)
- description and source-code
```javascript
writeInt32BE = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 4, 0x7fffffff, -0x80000000);
  this[offset] = (value >>> 24);
  this[offset + 1] = (value >>> 16);
  this[offset + 2] = (value >>> 8);
  this[offset + 3] = value;
  return offset + 4;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt32LE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt32LE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt32LE)
- description and source-code
```javascript
writeInt32LE = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 4, 0x7fffffff, -0x80000000);
  this[offset] = value;
  this[offset + 1] = (value >>> 8);
  this[offset + 2] = (value >>> 16);
  this[offset + 3] = (value >>> 24);
  return offset + 4;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt8"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeInt8 (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeInt8)
- description and source-code
```javascript
writeInt8 = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 1, 0x7f, -0x80);
  this[offset] = value;
  return offset + 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeIntBE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeIntBE (value, offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeIntBE)
- description and source-code
```javascript
writeIntBE = function (value, offset, byteLength, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert) {
    checkInt(this,
             value,
             offset,
             byteLength,
             Math.pow(2, 8 * byteLength - 1) - 1,
             -Math.pow(2, 8 * byteLength - 1));
  }

  var i = byteLength - 1;
  var mul = 1;
  var sub = 0;
  this[offset + i] = value;
  while (--i >= 0 && (mul *= 0x100)) {
    if (value < 0 && sub === 0 && this[offset + i + 1] !== 0)
      sub = 1;
    this[offset + i] = ((value / mul) >> 0) - sub;
  }

  return offset + byteLength;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeIntLE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeIntLE (value, offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeIntLE)
- description and source-code
```javascript
writeIntLE = function (value, offset, byteLength, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert) {
    checkInt(this,
             value,
             offset,
             byteLength,
             Math.pow(2, 8 * byteLength - 1) - 1,
             -Math.pow(2, 8 * byteLength - 1));
  }

  var i = 0;
  var mul = 1;
  var sub = 0;
  this[offset] = value;
  while (++i < byteLength && (mul *= 0x100)) {
    if (value < 0 && sub === 0 && this[offset + i - 1] !== 0)
      sub = 1;
    this[offset + i] = ((value / mul) >> 0) - sub;
  }

  return offset + byteLength;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt16BE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt16BE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt16BE)
- description and source-code
```javascript
writeUInt16BE = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 2, 0xffff, 0);
  this[offset] = (value >>> 8);
  this[offset + 1] = value;
  return offset + 2;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt16LE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt16LE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt16LE)
- description and source-code
```javascript
writeUInt16LE = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 2, 0xffff, 0);
  this[offset] = value;
  this[offset + 1] = (value >>> 8);
  return offset + 2;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt32BE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt32BE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt32BE)
- description and source-code
```javascript
writeUInt32BE = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 4, 0xffffffff, 0);
  this[offset] = (value >>> 24);
  this[offset + 1] = (value >>> 16);
  this[offset + 2] = (value >>> 8);
  this[offset + 3] = value;
  return offset + 4;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt32LE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt32LE (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt32LE)
- description and source-code
```javascript
writeUInt32LE = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 4, 0xffffffff, 0);
  this[offset + 3] = (value >>> 24);
  this[offset + 2] = (value >>> 16);
  this[offset + 1] = (value >>> 8);
  this[offset] = value;
  return offset + 4;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt8"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUInt8 (value, offset, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUInt8)
- description and source-code
```javascript
writeUInt8 = function (value, offset, noAssert) {
  value = +value;
  offset = offset >>> 0;
  if (!noAssert)
    checkInt(this, value, offset, 1, 0xff, 0);
  this[offset] = value;
  return offset + 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUIntBE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUIntBE (value, offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUIntBE)
- description and source-code
```javascript
writeUIntBE = function (value, offset, byteLength, noAssert) {
  value = +value;
  offset = offset >>> 0;
  byteLength = byteLength >>> 0;
  if (!noAssert) {
    const maxBytes = Math.pow(2, 8 * byteLength) - 1;
    checkInt(this, value, offset, byteLength, maxBytes, 0);
  }

  var i = byteLength - 1;
  var mul = 1;
  this[offset + i] = value;
  while (--i >= 0 && (mul *= 0x100))
    this[offset + i] = (value / mul) >>> 0;

  return offset + byteLength;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUIntLE"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.Buffer.prototype.</span>writeUIntLE (value, offset, byteLength, noAssert)](#apidoc.element.aliyun-sdk.util.Buffer.prototype.writeUIntLE)
- description and source-code
```javascript
writeUIntLE = function (value, offset, byteLength, noAssert) {
  value = +value;
  offset = offset >>> 0;
  byteLength = byteLength >>> 0;
  if (!noAssert) {
    const maxBytes = Math.pow(2, 8 * byteLength) - 1;
    checkInt(this, value, offset, byteLength, maxBytes, 0);
  }

  var mul = 1;
  var i = 0;
  this[offset] = value;
  while (++i < byteLength && (mul *= 0x100))
    this[offset + i] = (value / mul) >>> 0;

  return offset + byteLength;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.util.base64"></a>[module aliyun-sdk.util.base64](#apidoc.module.aliyun-sdk.util.base64)

#### <a name="apidoc.element.aliyun-sdk.util.base64.decode"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.base64.</span>decode (string)](#apidoc.element.aliyun-sdk.util.base64.decode)
- description and source-code
```javascript
function decode64(string) {
  return new Buffer(string, 'base64').toString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.base64.encode"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.base64.</span>encode (string)](#apidoc.element.aliyun-sdk.util.base64.encode)
- description and source-code
```javascript
function encode64(string) {
  return new Buffer(string).toString('base64');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.util.buffer"></a>[module aliyun-sdk.util.buffer](#apidoc.module.aliyun-sdk.util.buffer)

#### <a name="apidoc.element.aliyun-sdk.util.buffer.concat"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.buffer.</span>concat (buffers)](#apidoc.element.aliyun-sdk.util.buffer.concat)
- description and source-code
```javascript
concat = function (buffers) {
  var length = 0,
      offset = 0,
      buffer = null, i;

  for (i = 0; i < buffers.length; i++) {
    length += buffers[i].length;
  }

  buffer = new Buffer(length);

  for (i = 0; i < buffers.length; i++) {
    buffers[i].copy(buffer, offset);
    offset += buffers[i].length;
  }

  return buffer;
}
```
- example usage
```shell
...
    resp.httpResponse.buffers.push(new ALY.util.Buffer(chunk));
  }
});

add('HTTP_DONE', 'httpDone', function HTTP_DONE(resp) {
  // convert buffers array into single buffer
  if (resp.httpResponse.buffers && resp.httpResponse.buffers.length > 0) {
    var body = ALY.util.buffer.concat(resp.httpResponse.buffers);
    resp.httpResponse.body = body;
  }
  delete resp.httpResponse.numBytes;
  delete resp.httpResponse.buffers;
});

add('FINALIZE_ERROR', 'retry', function FINALIZE_ERROR(resp) {
...
```



# <a name="apidoc.module.aliyun-sdk.util.crypto"></a>[module aliyun-sdk.util.crypto](#apidoc.module.aliyun-sdk.util.crypto)

#### <a name="apidoc.element.aliyun-sdk.util.crypto.crc32"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>crc32 (data)](#apidoc.element.aliyun-sdk.util.crypto.crc32)
- description and source-code
```javascript
function crc32(data) {
<span class="apidocCodeCommentSpan">  /*jshint bitwise:false*/
</span>  var tbl = ALY.util.crypto.crc32Table;
  var crc = 0 ^ -1;

  if (typeof data === 'string') {
    data = new Buffer(data);
  }

  for (var i = 0; i < data.length; i++) {
    var code = data.readUInt8(i);
    crc = (crc>>>8) ^ tbl[(crc^code)&0xFF];
  }
  return (crc ^ -1) >>> 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.crypto.createHash"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>createHash (algorithm)](#apidoc.element.aliyun-sdk.util.crypto.createHash)
- description and source-code
```javascript
function createHash(algorithm) {
  return cryptoLib.createHash(algorithm);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.crypto.hmac"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>hmac (key, string, digest, fn)](#apidoc.element.aliyun-sdk.util.crypto.hmac)
- description and source-code
```javascript
function hmac(key, string, digest, fn) {
  if (!digest) digest = 'binary';
  if (digest === 'buffer') { digest = undefined; }
  if (!fn) fn = 'sha256';
  if (typeof string === 'string') string = new Buffer(string);
  return cryptoLib.createHmac(fn, key).update(string).digest(digest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.crypto.md5"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>md5 (data, digest)](#apidoc.element.aliyun-sdk.util.crypto.md5)
- description and source-code
```javascript
function md5(data, digest) {
  if (!digest) { digest = 'binary'; }
  if (digest === 'buffer') { digest = undefined; }
  if (typeof data === 'string') data = new Buffer(data);
  return ALY.util.crypto.createHash('md5').update(data).digest(digest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.crypto.sha256"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>sha256 (string, digest)](#apidoc.element.aliyun-sdk.util.crypto.sha256)
- description and source-code
```javascript
function sha256(string, digest) {
  if (!digest) { digest = 'binary'; }
  if (digest === 'buffer') { digest = undefined; }
  if (typeof string === 'string') string = new Buffer(string);
  return ALY.util.crypto.createHash('sha256').update(string).digest(digest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.crypto.toHex"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.crypto.</span>toHex (data)](#apidoc.element.aliyun-sdk.util.crypto.toHex)
- description and source-code
```javascript
function toHex(data) {
  var out = [];
  for (var i = 0; i < data.length; i++) {
    out.push(('0' + data.charCodeAt(i).toString(16)).substr(-2, 2));
  }
  return out.join('');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.util.date"></a>[module aliyun-sdk.util.date](#apidoc.module.aliyun-sdk.util.date)

#### <a name="apidoc.element.aliyun-sdk.util.date.format"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>format (date, formatter)](#apidoc.element.aliyun-sdk.util.date.format)
- description and source-code
```javascript
function format(date, formatter) {
  if (!formatter) formatter = 'unixSeconds';
  return ALY.util.date[formatter](ALY.util.date.from(date));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.date.from"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>from (date)](#apidoc.element.aliyun-sdk.util.date.from)
- description and source-code
```javascript
function format(date) {
  if (typeof date === 'number') {
    if(date.toString().length == 10) {
      return new Date(date * 1000); // unix timestamp in seconds
    }
    return new Date(date); // unix timestamp in mill seconds
  }
  else if(Object.prototype.toString.call(date) === '[object Date]') {
    return date;
  }
  else {
    return new Date(date);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.date.getDate"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>getDate ()](#apidoc.element.aliyun-sdk.util.date.getDate)
- description and source-code
```javascript
function getDate() { return new Date(); }
```
- example usage
```shell
...

    addAsync('SIGN', 'sign', function SIGN(req, done) {
if (!req.service.api.signatureVersion) return done(); // none

var credentials = req.service.config.getCredentials();

try {
  var date = ALY.util.date.getDate();
  var SignerClass = req.service.getSignerClass(req);
  var signer = new SignerClass(req.httpRequest, req.service.api.signingName);

  // add new authorization
  signer.addAuthorization(credentials, date);
} catch (e) {
  req.response.error = e;
...
```

#### <a name="apidoc.element.aliyun-sdk.util.date.iso8601"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>iso8601 (date)](#apidoc.element.aliyun-sdk.util.date.iso8601)
- description and source-code
```javascript
function iso8601(date) {
  if (date === undefined) { date = ALY.util.date.getDate(); }
  return date.toISOString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.date.rfc822"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>rfc822 (date)](#apidoc.element.aliyun-sdk.util.date.rfc822)
- description and source-code
```javascript
function rfc822(date) {
  if (date === undefined) { date = ALY.util.date.getDate(); }
  return date.toUTCString().replace("UTC", "GMT");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.date.top"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>top (date, fmt)](#apidoc.element.aliyun-sdk.util.date.top)
- description and source-code
```javascript
function top(date, fmt) {
  fmt = fmt || '%Y-%M-%dT%H:%m:%sZ';

  function pad(value) {
    return (value.toString().length < 2) ? '0' + value : value;
  };

  return fmt.replace(/%([a-zA-Z])/g, function (_, fmtCode) {
    switch (fmtCode) {
      case 'Y':
        return date.getUTCFullYear();
      case 'M':
        return pad(date.getUTCMonth() + 1);
      case 'd':
        return pad(date.getUTCDate());
      case 'H':
        return pad(date.getUTCHours());
      case 'm':
        return pad(date.getUTCMinutes());
      case 's':
        return pad(date.getUTCSeconds());
      default:
        throw new Error('Unsupported format code: ' + fmtCode);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.date.unixMilliseconds"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>unixMilliseconds (date)](#apidoc.element.aliyun-sdk.util.date.unixMilliseconds)
- description and source-code
```javascript
function unixMilliseconds(date) {
  if (date === undefined) { date = ALY.util.date.getDate(); }
  return date.getTime();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.aliyun-sdk.util.date.unixSeconds"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.date.</span>unixSeconds (date)](#apidoc.element.aliyun-sdk.util.date.unixSeconds)
- description and source-code
```javascript
function unixSeconds(date) {
  if (date === undefined) { date = ALY.util.date.getDate(); }
  return Math.floor(date.getTime() / 1000);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.aliyun-sdk.util.jamespath"></a>[module aliyun-sdk.util.jamespath](#apidoc.module.aliyun-sdk.util.jamespath)

#### <a name="apidoc.element.aliyun-sdk.util.jamespath.find"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.jamespath.</span>find (expression, data)](#apidoc.element.aliyun-sdk.util.jamespath.find)
- description and source-code
```javascript
function find(expression, data) {
  return ALY.util.jamespath.query(expression, data)[0];
}
```
- example usage
```shell
...
this.nextPageTokens = undefined;

var config = this.request.service.paginationConfig(this.request.operation);
if (!config) return this.nextPageTokens;

this.nextPageTokens = null;
if (config.moreResults) {
  if (!ALY.util.jamespath.find(config.moreResults, this.data)) {
    return this.nextPageTokens;
  }
}

var exprs = config.outputToken;
if (typeof exprs === 'string') exprs = [exprs];
ALY.util.arrayEach.call(this, exprs, function (expr) {
...
```

#### <a name="apidoc.element.aliyun-sdk.util.jamespath.query"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.jamespath.</span>query (expression, data)](#apidoc.element.aliyun-sdk.util.jamespath.query)
- description and source-code
```javascript
function query(expression, data) {
  if (!data) return [];

  var results = [];
  var expressions = expression.split(/\s+or\s+/);
  ALY.util.arrayEach.call(this, expressions, function (expr) {
    var objects = [data];
    var tokens = expr.split('.');
    ALY.util.arrayEach.call(this, tokens, function (token) {
      var match = token.match('^(.+?)(?:\\[(-?\\d+|\\*)\\])?$');
      var newObjects = [];
      ALY.util.arrayEach.call(this, objects, function (obj) {
        if (match[1] === '*') {
          ALY.util.arrayEach.call(this, obj, function (value) {
            newObjects.push(value);
          });
        } else if (obj.hasOwnProperty(match[1])) {
          newObjects.push(obj[match[1]]);
        }
      });
      objects = newObjects;

      // handle indexing (token[0], token[-1])
      if (match[2]) {
        newObjects = [];
        ALY.util.arrayEach.call(this, objects, function (obj) {
          if (Array.isArray(obj)) {
            if (match[2] === '*') {
              newObjects = newObjects.concat(obj);
            } else {
              var idx = parseInt(match[2], 10);
              if (idx < 0) idx = obj.length + idx; // negative indexing
              newObjects.push(obj[idx]);
            }
          }
        });
        objects = newObjects;
      }

      if (objects.length === 0) return ALY.util.abort;
    });

    if (objects.length > 0) {
      results = objects;
      return ALY.util.abort;
    }
  });

  return results;
}
```
- example usage
```shell
...
  function wrappedCallback(err, data) {
    if (err) return callback(err, null);
    if (data === null) return callback(null, null);

    var config = this.request.service.paginationConfig(this.request.operation);
    var resultKey = config.resultKey;
    if (Array.isArray(resultKey)) resultKey = resultKey[0];
    var results = ALY.util.jamespath.query(resultKey, data);
    ALY.util.arrayEach(results, function(result) {
      ALY.util.arrayEach(result, function(item) { callback(null, item); });
    });
  }

  this.eachPage(wrappedCallback);
},
...
```



# <a name="apidoc.module.aliyun-sdk.util.string"></a>[module aliyun-sdk.util.string](#apidoc.module.aliyun-sdk.util.string)

#### <a name="apidoc.element.aliyun-sdk.util.string.byteLength"></a>[function <span class="apidocSignatureSpan">aliyun-sdk.util.string.</span>byteLength (string)](#apidoc.element.aliyun-sdk.util.string.byteLength)
- description and source-code
```javascript
function byteLength(string) {
  if (string === null || string === undefined) return 0;
  if (typeof string === 'string') string = new Buffer(string);

  if (typeof string.byteLength === 'number') {
    return string.byteLength;
  } else if (typeof string.length === 'number') {
    return string.length;
  } else if (typeof string.size === 'number') {
    return string.size;
  } else if (typeof string.path === 'string') {
    return require('fs').lstatSync(string.path).size;
  } else {
    throw ALY.util.error(new Error('Cannot determine length of ' + string),
      { object: string });
  }
}
```
- example usage
```shell
...
add('VALIDATE_PARAMETERS', 'validate', function VALIDATE_PARAMETERS(req) {
  var rules = req.service.api.operations[req.operation].input;
  new ALY.ParamValidator().validate(rules, req.params);
});

add('SET_CONTENT_LENGTH', 'afterBuild', function SET_CONTENT_LENGTH(req) {
  if (req.httpRequest.headers['Content-Length'] === undefined) {
    var length = ALY.util.string.byteLength(req.httpRequest.body);
    req.httpRequest.headers['Content-Length'] = length;
  }
});

add('SET_HTTP_HOST', 'afterBuild', function SET_HTTP_HOST(req) {
  req.httpRequest.headers['Host'] = req.httpRequest.endpoint.host;
});
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
