===============
Release history
===============


v1.0.0 (2026-03-02)
===================

Bug Fixes
---------

* 500 http error for server internal auth errors (`#794`_, `62977ba`_)

* _deprecated wasn't resetting the warning filters correctly (`#247`_, `d92440f`_)

* A broken test and make others more robust (`#249`_, `6ede794`_)

* Accept all local files uri formats (`#545`_, `7254be5`_)

* Adapt to shapely v2.0 (`#580`_, `b8db03b`_)

* Adapts json data handling to flask 2.1.0 update (`#430`_, `9b4fd08`_)

* Add a next_page_url to QueryStringSearch, used in search_iter_page if available (`#190`_,
  `ab1c105`_)

* Add count bool parameter to query methods (`057c1e6`_)

* Add max_items_per_page for some providers (`#273`_, `a769ab6`_)

* Add missing module copyright and docstring (`5bcc431`_)

* Add missing stac properties + fix typo (`#947`_, `6823a97`_)

* Add timeout for download stream requests (`#394`_, `589ca10`_)

* Add warning for the total number of results returned by theia (`f2b3d07`_)

* Add warning when searching with non preferred provider (`#260`_, `84aac94`_)

* Align sensorType to opensearch-eo (`#528`_, `b66ad3b`_)

* Allow str type for resolution param (`#1102`_, `7d87255`_)

* Alternative http assets infos fetch (`#373`_, `c6fc141`_)

* Asset out of SAFE pattern wont break AwsDownload (`#609`_, `eec4adf`_)

* Astraea_eod product-type specific metadata-mapping (`#980`_, `85498a9`_)

* Auth errors messages more explicit (`378694c`_)

* Authenticate only when performing search (`#802`_, `dea2243`_)

* Auto extract if extract is not set (`#249`_, `6ede794`_)

* Aws auth and download (`2df5db5`_)

* Aws bucket extraction (`#524`_, `418da7c`_)

* Aws safe product destination path (`#228`_, `dac0046`_)

* Aws_eos geom search (`aac44a6`_)

* Aws_eos metadata re-mapping (`790e9f5`_)

* Aws_s3_sentinel2_l1c replaced with aws_eos (`cea9a93`_)

* AwsDownload SAFE build fix and more tests (`#609`_, `eec4adf`_)

* Bad providers handling when searching by id (`#805`_, `2af2d90`_)

* Better download wait time precision (`#621`_, `8558510`_)

* Better wrong or missing credentials handling (`23af1f0`_)

* Broken pip search (`bfe347d`_)

* Broken stac aws download conf (`#475`_, `54a5182`_)

* Cast loaded env vars type using config type-hints (`#987`_, `270f673`_)

* Catch product.location resolve errors during download (`#1118`_, `bd79ff7`_)

* CdsApi default dates and refactor (`#672`_, `52cacf3`_)

* Cdsapi logging (`#513`_, `158fac8`_)

* CdsApi logging handler (`#522`_, `0244dae`_)

* Changed country key in locations conf template (`6576287`_)

* Check usgs available downloadSystem in download_options (`#612`_, `4a0d689`_)

* CI failure following deps upgrade (`#280`_, `88c016d`_)

* Clear plugin context before performing search by id (`#693`_, `324bc80`_)

* Clear search context after each search() call (`#433`_, `3c7424c`_)

* Cli download_all register plugin, fixes #134 (`6e6aed8`_)

* Cli list product_types (`d2a7386`_)

* Cli serve-rest settings import (`25d029a`_)

* CLI update for geom search, fixes eodag/eodag#17 (`7708015`_)

* CLMS search by id on wekeo (`#1100`_, `5b9caa5`_)

* Cloud cover disabled for radar product types and onda queryable params (`#636`_, `9ea3f35`_)

* Common queryables (`#977`_, `bf9b8e9`_)

* Completed progress_callback with unknown total (`#1072`_, `db83859`_)

* Conf updatable from non-queryable params to queryable (`#288`_, `4aa610a`_)

* Conf update with external plugin, fixes GH-184 (`#189`_, `fc2bd76`_)

* Continue if error on gh actions tests publish (`#558`_, `643bcd9`_)

* Convert_to_bounds for multipolygons (`#1503`_, `1aa6a98`_)

* Cop_marine - handling of ids with points (`#1364`_, `441cefa`_)

* Correct external stac collection id reference (`#1171`_, `76fadda`_)

* Correctly replace the default location file path (`#192`_, `af9afc8`_)

* Cors issue with docker-compose (`#188`_, `11a6c14`_)

* Creodias & cop_dataspace search result count (`#929`_, `c89cf52`_)

* Creodias and cop_dataspace metadata_mapping (`#915`_, `f0257df`_)

* Creodias and cop_dataspace quicklook (`#957`_, `300a2f8`_)

* Creodias API update (`#623`_, `86a0cf1`_)

* Creodias archive_depth and e2e complete test (`#410`_, `47c0e33`_)

* Creodias max_items_per_page (`#649`_, `6a62711`_)

* Dates considered as utc to create a timestamp for sobloo (`5b06ca3`_)

* Dedl mapping for CORINE collection (`#1661`_, `4c61b54`_)

* Default dates on wekeo (`#840`_, `6a93f02`_)

* Deprecate load_static_items (`#225`_, `0632e41`_)

* Deprecation warnings in tests and py27 compatibility (`034819a`_)

* Disable cloudCover for RADAR product types (`#389`_, `a3dc5d5`_)

* Disable discover_product_types for StaticStacSearch (`#590`_, `870580e`_)

* Discover product types for new default providers (`#493`_, `6ff8e5f`_)

* Discover_product_types auth (`#486`_, `f4b5f52`_)

* Discovery_config in metadata_mapping (`#625`_, `139d22a`_)

* Do not _search_by_id if id is None, as expected by the CLI (`#190`_, `ab1c105`_)

* Do not build search plugins when updating product types list (`#500`_, `b8128f1`_)

* Do not prepare search_all twice (`#330`_, `2f6ebe8`_)

* Do not try to import rasterio, fixes GH-150 (`6db9e71`_)

* Do not use ipywidgets for the Notebookwidgets representation (`#223`_, `7054aa3`_)

* Docker image (`#1972`_, `fa3fe3f`_)

* Docker user home dir (`#764`_, `d24850a`_)

* Dockerfile update for stac-browser v2.0 (`#314`_, `30306e5`_)

* Don't propagate kwargs used for guessing a product type (`#248`_, `f344ddd`_)

* Download error after zip delete, fixes #142 (`39308ae`_)

* Download of single asset with aws download and ignore assets not working (`#991`_, `80394d2`_)

* Download progress_callback, fixes GH-157 (`ce84b33`_)

* Download_all doesn't empty the passed list of products (`#253`_, `dad8bb0`_)

* Drop support for python3.6 (`#505`_, `e68536c`_)

* Dynamic recent dates for onda end to end test (`ec4f4b1`_)

* E2e test mundi extent (`614075f`_)

* Earth Search uses next_page_url_tpl to get the next page in search_iter_page (`#274`_, `9096a12`_)

* EcmwfApi default dates and refactor (`#678`_, `873e45d`_)

* EFAS dates formatting on cop_cds (`#1178`_, `dbc1b57`_)

* Empty paths returned by HTTPDownload.download_all() (`6399631`_)

* Enable default search geometry usage in FilterLatestIntersect crunch (`#707`_, `47452e5`_)

* Enable eodag-cube assets import (`#1077`_, `a27c188`_)

* End-to-end tests, fixes #119, fixes #98 (`5beec33`_)

* Eodag-cube 0.2.0 required (`#338`_, `d3ada37`_)

* Eodag-cube does not yet allow to download a product subset, fixes GH-153 (`27b2db2`_)

* Eodag-server docker sigterm (`#702`_, `08a4fbc`_)

* Eumetsat_ds METOP search by id (`#1189`_, `56068d7`_)

* Ewkt extraction for creodias and cop_dataspace (`#868`_, `7e199dc`_)

* Exceptions handling update (`#829`_, `a721a4e`_)

* Existing tests (`#273`_, `a769ab6`_)

* Expose **version** in main __init__.py (`98dcc6b`_)

* Expose a timeout parameter in load_stac_items (`85be8a7`_)

* Extract USGS tarfiles (`#759`_, `9062756`_)

* Failing end-to-end sobloo tests (`#195`_, `78a18ae`_)

* Failing test due to the removal of locations from kwargs in _prepare_search (`#190`_, `ab1c105`_)

* Fetch only given provider if specified (`#557`_, `df9f01d`_)

* Fetch product types gh action failures (`#472`_, `66a9d2f`_)

* Fetch product types gh action when nothing to commit (`#472`_, `66a9d2f`_)

* Fixed flatten top dirs mechanism (`#576`_, `dd6069c`_)

* Flask 2.2.x as max version (`#722`_, `c7b8e24`_)

* Flatten_top_directories on single file (`#634`_, `8bffc9c`_)

* Forbidden and unauthorized errors in token auth (`#791`_, `caff0bc`_)

* Format warning by flake8 latest version (`7448cf8`_)

* Format_query_params in PostJsonSearch (`#1145`_, `9764ac8`_)

* Get all available metadata for onda products (`#440`_, `877366d`_)

* Get_quicklook method for onda provider (`#344`_, `b0253f3`_)

* Gitlab-ci docker img update (`425e44c`_)

* Gitlab-ci pypi publish (`8a891ef`_)

* Guess and set product_type when searching by id (`#320`_, `21b6708`_)

* Guess_product_type should return given productType if specified (`#694`_, `913b5d8`_)

* Handle creodias and cop_dataspace empty geometries (`#1186`_, `69b5443`_)

* Handle empty response from provider (`#1132`_, `22b7e1f`_)

* Handle local assets in HTTPDownload (`#561`_, `29c1474`_)

* Handle mundi missing storageStatus (`#743`_, `9d5caba`_)

* Homogenize inconsistent paths returned by download methods (`#244`_, `6ab4262`_)

* Id cast to str in progress_callback (`#490`_, `ff88331`_)

* Ignore and log misconfigured provider from user conf (`#296`_, `facf8bf`_)

* Ignore percent vars resolve errors in register_downloader (`#586`_, `c91cba7`_)

* Improve an error message in set_preferred_provider and black (`#190`_, `ab1c105`_)

* Improve stac collection links generation (`#1174`_, `f915932`_)

* Increase log level for search_all at each iteration (`#273`_, `a769ab6`_)

* Index rebuild on nfs, fixes GH-151 (`d893dec`_)

* ISO 8601 formatted datetimes accepted everywhere (`#257`_, `c564fdd`_)

* ISO8601 format accepted everywhere (`#257`_, `c564fdd`_)

* Items url through STAC search endpoint (`#698`_, `5ef8dac`_)

* JSONDecodeError during order process (`#620`_, `37eb4e5`_)

* Jsonpath issue causing missing productPath property (`#480`_, `3f39f6c`_)

* Keep ext_product_types.json in v4 (`#1888`_, `d4f8379`_)

* Keep order in unique items lists (`#1296`_, `db61d9c`_)

* Keyerror on search by id (`#290`_, `f488962`_)

* Labextension legacy rest compatibility (`49366bd`_)

* Landsat c1 no more available on usgs (`#601`_, `df7af23`_)

* Lansat-8 search for onda (`c068ff8`_)

* Lib and server mode queryables (`#974`_, `4061b78`_)

* Limit jsonpath-ng version (`#825`_, `18b22d5`_)

* List_product_types must not return GENERIC_PRODUCT_TYPE (`#261`_, `d18287d`_)

* Load user config file with settings of providers from ext plugin, fixes GH-234 (`#235`_,
  `96d85ab`_)

* Locations should not be part of the kwargs passed to query (`#186`_, `17a6cbb`_)

* Log warning when items_per_page > max_items_per_page (`#273`_, `a769ab6`_)

* Logout and in if usgs apikey expires (`#489`_, `0a782d7`_)

* Make map_product_type accept kwargs (`#629`_, `7960f93`_)

* Make setup_logging easier to import (`#221`_, `47dc78c`_)

* Metadata mapping update and uniformization, fixes GH-154 (`a958dae`_)

* Metadata-mapping with providers update (`#483`_, `9639b37`_)

* Metadata_mapping to_geo_interface changed to to_geojson (`#604`_, `6fee322`_)

* Meteoblue download format (`#647`_, `216edc2`_)

* Minimal pagination when searching by id (`#696`_, `d128d9c`_)

* Misconfigured provider skip (`#209`_, `cfc291f`_)

* Missing auth and remote location parsing in download_all, fixes #118 (`283b759`_)

* Missing auth in search results (`#793`_, `3c7b74b`_)

* Missing provider in stac downloadLink (`#774`_, `8561219`_)

* Missing search_plugin when searching by id (`#335`_, `304446b`_)

* Missing space needed in pytest cli call (`#598`_, `7d105d1`_)

* Missing tileIdentifier for creodias and cop_dataspace (`#1014`_, `f8cfc68`_)

* More explicit end-to-end tests error messages (`#398`_, `470aa49`_)

* More explicit message on misconfigured auth (`#293`_, `ed3026d`_)

* More explicit signature for setup_logging (`#200`_, `720588a`_)

* More info in the config template (`#249`_, `6ede794`_)

* More verbose build_index error (`9405571`_)

* More verbose keycloak auth plugin errors (`#771`_, `ff32294`_)

* Move DEFAULT_MISSION_START_DATE to utils (`#1111`_, `b71183e`_)

* Multipolygons geom search and stac-serve (`6881134`_)

* Nbsphinx broken with Jinja2 update (`#280`_, `88c016d`_)

* Need_auth and api plugin search (`#448`_, `cc1f51b`_)

* Negative coords in returned bbox geometry, fixes #143 (`208c114`_)

* New line at end of ext_product_types.json (`#472`_, `66a9d2f`_)

* New methods to get assets filename from header (`#542`_, `f73ba14`_)

* New search endoint aws_s3_sentinel2_l1c and RequestPayer option usage, fixes #131 (`c8f75c5`_)

* New test for readme/pypi syntax (`d8bb323`_)

* Not just expect a unix tmp directory (`#192`_, `af9afc8`_)

* Not-donwloaded products warning (`#635`_, `9aaf0cd`_)

* NotAvailableError using usgs api (`#393`_, `fc86004`_)

* Odata free text search operands filter (`#624`_, `ae475d6`_)

* Onda query quoting (`28073e8`_)

* Optimized jsonpath.parse using common_metadata_mapping_path (`#626`_, `dba5c61`_)

* Ordered keywords in discovered product types (`#597`_, `641ccfd`_)

* OrderLink in build_search plugins (`#1082`_, `1513d9c`_)

* OrderLink parsing using updated templates metadata-mapping (`#1091`_, `4286d13`_)

* Orjson requirement (`#1150`_, `a2c8b01`_)

* Out of safe format assets (`#609`_, `eec4adf`_)

* Paths when downloading and extracting again with archive depth (`#292`_, `df15f00`_)

* Peps storageStatus update (`#677`_, `16cdf28`_)

* Pin flask version to prevent doctest error (`#492`_, `3b9eb8c`_)

* Pin ipython version in docs for nbsphinx (`#582`_, `90eaaff`_)

* Pin markupsafe for doc build (`#399`_, `45a1f08`_)

* Pinned black version in pre-commit update (`#430`_, `9b4fd08`_)

* Plugin manager rebuild (`#919`_, `1d9f92c`_)

* Plugin.download returns a filesystem path, not a file URI (`#244`_, `6ab4262`_)

* PostJsonSearch request error and tests (`#610`_, `58b6093`_)

* Precommit fails with py36 (`c14d345`_)

* Prevent duplicated ODataV4Search custom args (`#652`_, `7a372eb`_)

* Prevent eol auto changes on windows causing docker crashes (`#324`_, `db3c4ec`_)

* Prevent NotebookWidgets.display_html in ipython shell (`#307`_, `e44c9e4`_)

* Prodcut types fetch update (`#1202`_, `9028c4b`_)

* Product-type specific metadata-mapping (`#830`_, `4650184`_)

* ProductionStatus renamed to storageStatus (`d11af66`_)

* ProductPath regex for earth_search (`#405`_, `8c3c1c1`_)

* Progress bar adjustable refresh (`#643`_, `3099b2a`_)

* Progress_bar max_size preset (`2a5d405`_)

* ProgressCallback smooth display and renamed input parameter (`#345`_, `e6b8a96`_)

* Providers and product-types conf update (`#1212`_, `e73c12e`_)

* Py27 encodeurl in querystring (`dc08dbd`_)

* Pystac v1.0 update (`#321`_, `37af691`_)

* Python-dateutil version for moto update, fixes #141 (`4b0b67d`_)

* Queryables fixes + small refactor (`#1050`_, `a8522fd`_)

* Re-login in UsgsApi plugin on api file error (`#1046`_, `2ef1ad1`_)

* Read outputs_extension from download plugin conf (`#604`_, `6fee322`_)

* Readme syntax (`8570750`_)

* Readthedocs git fetch unshallow (`#777`_, `ce9b54a`_)

* Recreate whoosh index when unsupported pickle protocol (`#258`_, `5eb6bb0`_)

* Reload plugins after providers settings update from user conf (`#306`_, `139f5c6`_)

* Remove dependency to unidecode, fixes GH-158 (`99cb67b`_)

* Remove inappropriate archive (`#1448`_, `d4fffce`_)

* Remove location param from query after usage (`8e6a79a`_)

* Remove metadata_mapping from CdsApi queryables (`#1048`_, `ee6306b`_)

* Remove module from logging and shorten loggers names (`#885`_, `93e61ca`_)

* Remove mundi provider (`#890`_, `c580617`_)

* Remove out-of-date wekeo driver (`#295`_, `45b4ca5`_)

* Remove product_type custom arg from QueryStringSearch.query (`#589`_, `acfbc8e`_)

* Remove python3.5 support (`f67c365`_)

* Remove rpc server (`#1011`_, `ce74f22`_)

* Remove step parameter in CAMS_EAC4 configuration (`#749`_, `c38d36e`_)

* Remove StopIteration usage following PEP-479 (`#337`_, `00bf073`_)

* Remove unavailable sobloo provider (`#607`_, `b5486f7`_)

* Removed deprecated server context extension (`#891`_, `b6dd367`_)

* Removed stac eo:bands for zipped products (`#341`_, `ee9af26`_)

* Removed traceback from geom intersection warning, fixes #114 (`d669625`_)

* Removes creodias discover_product_types (`#1112`_, `81732a8`_)

* Rename GRANULE first folder during SAFE build (`#434`_, `c28ab8f`_)

* Rename sort_by_extent to group_by_extent (`b7fe6b1`_)

* Renamed AwsDownload.get_bucket_name_and_prefix to get_product_bucket_name_and_prefix (`#609`_,
  `eec4adf`_)

* Renamed shapely exceptions (`#824`_, `886e046`_)

* Replace deprecated unittest assertEquals and assertDictContainsSubset (`#248`_, `f344ddd`_)

* Replace product_type_fetch_url with collection_fetch_url (`#1995`_, `4559f41`_)

* Request error handling during search_all (`#554`_, `2ddca49`_)

* Request-ftp requirement (`#781`_, `fa617ce`_)

* Requests intersphinx url (`#460`_, `909354f`_)

* Response with 4xx or 5xx is false (`#1078`_, `d513572`_)

* Rest search without stac formatting (`#526`_, `59ac844`_)

* Rest server import error, fixes #132 (`b80ea0f`_)

* Restore creodias product types discovery (`#639`_, `5de90ce`_)

* Return as many products as found by whoosh (`#246`_, `4f7edc8`_)

* Return empty list when no results entry in a JSON response, fixes GH-155 (`7c7f00c`_)

* Return extracted path after download (`7714bea`_)

* Return only user requested item if id is present (`#856`_, `5165658`_)

* S2_MSI_L2A removed for peps (`#969`_, `9b95224`_)

* Same name locations geom union instead of intersect (`fdf2b08`_)

* Sanitize downloaded assets paths (`#745`_, `50d6e60`_)

* Sara provider conf (`#828`_, `c8ef1b9`_)

* Search errors handling (`#660`_, `d378061`_)

* Search fallback error logging (`#1101`_, `9d04c9b`_)

* Search fallback with raise_errors and empty results (`#807`_, `78179d5`_)

* Search preferred provider and wekeo job error handling (`#790`_, `2eb52b8`_)

* Search using product_type_def_params and product_type (`4bcbe55`_)

* SensorType missing when serving STAC items for discovered product types (`#699`_, `e564348`_)

* Sentinel-3 products not available on peps any more (`#304`_, `e1c6173`_)

* Server-mode download for ext api providers (`#751`_, `3e1ccd4`_)

* Server-mode imports handling in cli (`#1113`_, `c9a324b`_)

* Server-mode search param formatting and error message (`#1103`_, `0dc0ba0`_)

* Set creodias search timeout to 20s (`#894`_, `19d7d6b`_)

* Set owslib version to 0.18.0 (py27 support dropped) (`ee83a74`_)

* Set responses max version lt 0.24.0 (`#913`_, `430592a`_)

* Shapely parseException warning, fixes #123 (`623b32a`_)

* Shapely transform inverted xy and warning (`#667`_, `e8c5a47`_)

* Shared rest functions without server extra (`#1115`_, `ad46243`_)

* Simplified mundi auth using HTTPHeaderAuth (`#804`_, `ee112d3`_)

* Simplify S2_MSI_L1C internal usage with peps (`#630`_, `05e94a5`_)

* Single product type discovery (`#1190`_, `8360a41`_)

* Skip badly configured providers in user conf, see #129 (`aa88fa6`_)

* Skip commit summary when not needed in fetch product types ci (`#473`_, `fa1e8c0`_)

* Skip pagination starts from 1 for mundi, not 0 (`a043e2a`_)

* Sobloo and creodias quicklook (`53cb3bb`_)

* Sort query dict items in BuildPostSearchResult (`#604`_, `6fee322`_)

* Sorted keys in gh action fetch product types diff (`#1205`_, `298f941`_)

* Stac 1.0.0 update (`#347`_, `1cd1b46`_)

* Stac api 1.0.0-beta.1 update (`82f2753`_)

* Stac items links (`64557a9`_)

* Stac provider dates format (`cebac98`_)

* Stac server catalogs cloud-cover filtering (`#705`_, `257eda4`_)

* Stac server catalogs dates filtering (`#706`_, `6ff2907`_)

* StacSearch default assets (`#935`_, `9c1a67c`_)

* Stop iteration if the next page returns the same first product (`#190`_, `ab1c105`_)

* Store & check product types index version (`69779cb`_)

* Support non UTC datetime (`#257`_, `c564fdd`_)

* Temporally remove callback to download methods (`#371`_, `1891f4b`_)

* Temporarily add py dep for pytest-html (`#541`_, `3cdbd4c`_)

* Temporarily set pytest-html max version (`#540`_, `79f40a3`_)

* Tests can run in parallel mode with tox, fixes GH-103 (`b487473`_)

* Theia-landsat provider moved to theia, fixes #95 (`22e74b8`_)

* Timeout set for all requests methods (`#495`_, `f0d13e7`_)

* Tqdm_notebook warning, fixes #117 (`8b118ee`_)

* Two error messages (`ff65795`_)

* Type hints related fixes and refactoring (`#1052`_, `d1df25e`_)

* TypeError on unexpected geometry type (`e356ed0`_)

* Unified ProgressCallback usage (`#276`_, `3ce721d`_)

* Unparsed base_uri in properties, fixes #122 (`1e0d894`_)

* Unwanted percent-encoded keys with mundi S2_MSI_L2A (`#350`_, `d4bd54e`_)

* Unwanted string in logging time (`#444`_, `06dd23d`_)

* Updatable metadata-mapping for stac providers (`b826f21`_)

* Update auth plugins docs and error handling (`#588`_, `106a9e0`_)

* Update black and adapts json data handling to flask 2.1.0 (`#430`_, `9b4fd08`_)

* Update creodias auth to Creodias-new (`#763`_, `bd59008`_)

* Update external product types for unknown provider (`#682`_, `3769147`_)

* Update external product types reference (`#1620`_, `0c9b55f`_)

* Update external product types reference (`#1610`_, `651f94f`_)

* Update external product types reference (`#1603`_, `6af7ce4`_)

* Update external product types reference (`#1599`_, `548fded`_)

* Update external product types reference (`#1567`_, `cacdee3`_)

* Update external product types reference (`#1565`_, `0293c5f`_)

* Update external product types reference (`#1557`_, `67f653d`_)

* Update external product types reference (`#1553`_, `4d6f726`_)

* Update external product types reference (`#1548`_, `0715f05`_)

* Update external product types reference (`#1539`_, `2a8e683`_)

* Update external product types reference (`#1525`_, `b7cc06e`_)

* Update external product types reference (`#1510`_, `c5805cf`_)

* Update external product types reference (`#1494`_, `0ff477d`_)

* Update external product types reference (`#1493`_, `b7ae557`_)

* Update external product types reference (`#1487`_, `7341337`_)

* Update external product types reference (`#1484`_, `045a849`_)

* Update external product types reference (`#1478`_, `689471c`_)

* Update external product types reference (`#1460`_, `4233b05`_)

* Update external product types reference (`#1459`_, `6564ce6`_)

* Update external product types reference (`#1453`_, `7924f7f`_)

* Update external product types reference (`#1424`_, `2fc3f27`_)

* Update external product types reference (`#1416`_, `77cd724`_)

* Update external product types reference (`#1408`_, `70e156b`_)

* Update external product types reference (`#1406`_, `ae88aa9`_)

* Update external product types reference (`#1404`_, `eeb8d3b`_)

* Update external product types reference (`#1401`_, `7ee6c7f`_)

* Update external product types reference (`#1391`_, `175e167`_)

* Update external product types reference (`#1387`_, `2473ac1`_)

* Update external product types reference (`#1384`_, `9a31d66`_)

* Update external product types reference (`#1381`_, `9fe7fb2`_)

* Update external product types reference (`#1378`_, `3a2babe`_)

* Update external product types reference (`#1375`_, `1888f5f`_)

* Update external product types reference (`#1373`_, `b471693`_)

* Update external product types reference (`#1369`_, `3ebb060`_)

* Update external product types reference (`#1366`_, `127e035`_)

* Update external product types reference (`#1362`_, `1737390`_)

* Update external product types reference (`#1360`_, `127b346`_)

* Update external product types reference (`#1359`_, `e482098`_)

* Update external product types reference (`#1356`_, `c4393b5`_)

* Update external product types reference (`#1342`_, `4785e8a`_)

* Update external product types reference (`#1334`_, `216612f`_)

* Update external product types reference (`#1322`_, `c42cf9c`_)

* Update external product types reference (`#1316`_, `0deebef`_)

* Update external product types reference (`#1290`_, `30c3c4a`_)

* Update external product types reference (`#1251`_, `cf2f643`_)

* Update external product types reference (`#1246`_, `568ae07`_)

* Update external product types reference (`#1244`_, `0afcc97`_)

* Update external product types reference (`#1234`_, `b3af807`_)

* Update external product types reference (`#1229`_, `8f633df`_)

* Update external product types reference (`#1223`_, `0d454f9`_)

* Update external product types reference (`#1210`_, `e577b27`_)

* Update external product types reference (`#1208`_, `e76f4a8`_)

* Update external product types reference (`#1207`_, `3efcf4c`_)

* Update external product types reference (`#1206`_, `8cf240e`_)

* Update external product types reference (`#1204`_, `fb729b1`_)

* Update external product types reference (`#1203`_, `8868ee5`_)

* Update external product types reference (`#1165`_, `06c4678`_)

* Update external product types reference (`#1160`_, `0a6208a`_)

* Update external product types reference (`#1153`_, `df8c944`_)

* Update external product types reference (`#1151`_, `f343411`_)

* Update external product types reference (`#1146`_, `eb9a6f0`_)

* Update external product types reference (`#1140`_, `3b8ca8d`_)

* Update external product types reference (`#1137`_, `a943c6c`_)

* Update external product types reference (`#1136`_, `975c7cd`_)

* Update external product types reference (`#1114`_, `b2c6a50`_)

* Update external product types reference (`#1110`_, `6606607`_)

* Update external product types reference (`#1107`_, `ed3ab95`_)

* Update external product types reference (`#1093`_, `baf2298`_)

* Update external product types reference (`#1086`_, `8090f54`_)

* Update external product types reference (`#1028`_, `6e25b8a`_)

* Update external product types reference (`#1027`_, `2ed579c`_)

* Update external product types reference (`#1025`_, `3323b91`_)

* Update external product types reference (`#1019`_, `6a6344c`_)

* Update external product types reference (`#1013`_, `44d725e`_)

* Update external product types reference (`#1009`_, `f18edab`_)

* Update external product types reference (`#877`_, `3cb6ca9`_)

* Update external product types reference (`#838`_, `cb0217b`_)

* Update external product types reference (`#818`_, `e100b96`_)

* Update external product types reference (`#788`_, `9acf017`_)

* Update external product types reference (`#775`_, `e40b40d`_)

* Update external product types reference (`#762`_, `6034cd1`_)

* Update external product types reference (`#738`_, `d9708f9`_)

* Update external product types reference (`#737`_, `fdde58e`_)

* Update external product types reference (`#731`_, `2ff150a`_)

* Update external product types reference (`#729`_, `9d0e561`_)

* Update external product types reference (`#720`_, `072a0f2`_)

* Update external product types reference (`#712`_, `36fd6ae`_)

* Update external product types reference (`#703`_, `cbce353`_)

* Update external product types reference (`#691`_, `f271cb3`_)

* Update external product types reference (`#644`_, `cdaac24`_)

* Update external product types reference (`#640`_, `6176b8e`_)

* Update external product types reference (`#638`_, `bc21b08`_)

* Update external product types reference (`#599`_, `0e11b56`_)

* Update external product types reference (`#595`_, `ca5c824`_)

* Update external product types reference (`#593`_, `77cf3d7`_)

* Update external product types reference (`#481`_, `918f2d1`_)

* Update external product types reference (`#471`_, `a003087`_)

* Update flask version limit (`#496`_, `f52c964`_)

* Update nbconvert (`#497`_, `04b9584`_)

* Update NOTICE files (`#1016`_, `622012a`_)

* Update package build & check (`#431`_, `4ca485c`_)

* Update provider with new plugin entry (`#484`_, `f6f97fe`_)

* Update read_local_json to catch OSErrors (`#572`_, `dacb233`_)

* Update server body model to search by ids (`#822`_, `d0869f9`_)

* Update STAC browser catalogUrl param name (`#704`_, `c9bba53`_)

* Update templates detection in metadata-mapping (`#1139`_, `8fe2f86`_)

* Update tests, code, ci to remove warnings (`#668`_, `93e33ee`_)

* Update usgs to enable search_all (`#340`_, `bbf8587`_)

* Update UsgsApi plugin (`#508`_, `1339844`_)

* Update_providers_config with existing provider (`8f74bea`_)

* Updated creodias auth settings (`#514`_, `eb054a4`_)

* Urllib errors catch during search/discover (`#688`_, `07a2b79`_)

* Urllib HTTP errors handle (`e22bc33`_)

* Usage of NamedTemporaryFile on Windows (`#192`_, `af9afc8`_)

* Use earth search v1 endpoint (`#754`_, `acf207e`_)

* Use id instead of title in item id metadata (`#1193`_, `5f1b707`_)

* Use jsonpath-ng instead of jsonpath-rw and pyjq (`1d00fe3`_)

* Use mock in stac server search tests (`#464`_, `7209dda`_)

* Use PR in github action to update external product types reference (`#470`_, `f2c495d`_)

* Use pystac to open STAC static catalogs (`431c47c`_)

* Use refresh token to get access token in keycloak auth (`#921`_, `67e0943`_)

* Usgs plugin uses m2m api (`#209`_, `cfc291f`_)

* Usgs plugin using m2m api (`#209`_, `cfc291f`_)

* USGS plugin, fixes #73 (`f02ecbd`_)

* Usgs product summary pattern update (`5cf3cc6`_)

* UsgsApi inheritance for download_all (`#379`_, `6e6e689`_)

* Various issues with the crunchers (`7bc6947`_)

* Version guess from gh actions (`#431`_, `4ca485c`_)

* Warning if keycloak auth error while discovering product types (`#555`_, `b4c8b9f`_)

* Warning message if an unknow provider is found in user conf, fixes #129 (`df6b4fe`_)

* Wekeo pagination (`#1098`_, `3506dfb`_)

* Wekeo2 wekeo-broker api (`#1010`_, `7bcdbc5`_)

* Whoosh fields update (`4a15d7f`_)

* Whoosh search returns all the matching elements (`#201`_, `0c16038`_)

* Wrong location set in the http plugin (`#244`_, `6ab4262`_)

* Wrong mutually exclusive option in the search command (`#173`_, `7e879d2`_)

* Wrong pagination entry in stac_provider.yml (`#190`_, `ab1c105`_)

* **build**: Do not cache apt update in server dockerfile (`#1430`_, `b871978`_)

* **build**: Update shapely to fix issues with numpy 2.1 (`#1303`_, `f373d7b`_)

* **cli**: Handle import error of eodag.rest module (`#1415`_, `d1e649e`_)

* **cop_marine**: Search_by_id for products without date in id (`#1471`_, `c08c053`_)

* **core**: Add Collection property for server extended metadata (`#1947`_, `e9ffb17`_)

* **core**: Advanced assets harmonisation using properties (`#2003`_, `49e8f9f`_)

* **core**: Always validate PluginConfig before loading (`#1690`_, `59ac437`_)

* **core**: Asset name harmonization with query-string (`#1983`_, `a93c2c7`_)

* **core**: Better compare matching_url with orderLink when OFFLINE (`#1332`_, `d24377f`_)

* **core**: Check if platform is str in sentinel drivers (`#2051`_, `d88f651`_)

* **core**: Do not download again unextracted products (`#1717`_, `29642e8`_)

* **core**: Do not retry skipped products during download_all (`#1465`_, `938c23e`_)

* **core**: Do not use git lfs (`#1333`_, `ea72351`_)

* **core**: Download asset with special chars (`#1585`_, `f8f92d5`_)

* **core**: Download authentication without downloadLink (`#1329`_, `8174a1e`_)

* **core**: Enable count with search iterator (`#1700`_, `bbcc7ba`_)

* **core**: Ensure datetime format compliance with STAC specification (`#1573`_, `7e10e3a`_)

* **core**: Guess_product_type using alias (`#1800`_, `99e6ab8`_)

* **core**: Handle exceptions occuring on failed index write (`#1428`_, `076a0f8`_)

* **core**: Handling of collections with aliases (`#1935`_, `274280a`_)

* **core**: Jsonpath-ng 1.8.0 Index indices (`#2059`_, `07ed6b0`_)

* **core**: List queryables for custom collections (`#2023`_, `d548ac0`_)

* **core**: Logging issue on entrypoint loading error (`#1728`_, `6f8e6ad`_)

* **core**: Metadata mapping for date parameter (`#1480`_, `8e47f11`_)

* **core**: Missing _search_by_id warning (`#1294`_, `3316c4f`_)

* **core**: Missing queryables from metadata-mapping (`#1614`_, `9789c0c`_)

* **core**: Polling times and typing update (`#1440`_, `3c2fcc7`_)

* **core**: Provider queryables metadata (`#1613`_, `f1b066a`_)

* **core**: Queryables mismatch when list of possible values contains a single value (`#1666`_,
  `538331d`_)

* **core**: Remove quotes around arrays in query param (`#1657`_, `b717e45`_)

* **core**: Rename old record file (`#1396`_, `a5e1620`_)

* **core**: Reset errors between SearchResult instances (`#1607`_, `48b0779`_)

* **core**: Skip None EOProduct.properties (`#1892`_, `41c2fc4`_)

* **core**: Skip provider empty conf on init (`#1687`_, `0a4104e`_)

* **core**: Sort queryables and ecmwf alias support (`#1894`_, `090c0bd`_)

* **core**: Ssl_verify setting for get_quicklook (`#1490`_, `b247f5c`_)

* **core**: TypedDict from typing_extensions required by pydantic (`#1986`_, `6ada805`_)

* **core**: Update pattern of data roles in GenericDriver (`#1815`_, `c75351d`_)

* **core**: Wrong credentials sharing (`#1970`_, `6ad08cb`_)

* **crunch**: Filter_latest_intersect used geometry (`#2030`_, `780eabf`_)

* **crunch**: Skip missing key in filter_property (`#1466`_, `17c23a4`_)

* **doc**: Doc update for provider priorities and params_mapping (`0bfa61d`_)

* **doc**: New badges in readme and CS logo (`7795cf1`_)

* **EcmwfSearch**: Map geometry metadata (`#1555`_, `ddde27a`_)

* **geodes**: Added relativeOrbitNumber property (`#1499`_, `4d03a1a`_)

* **geodes**: Unquote searched numerical values (`#1507`_, `d50b378`_)

* **oidc**: Do not fail when trying to authenticate an already authenticated user (`#1524`_,
  `baeafb4`_)

* **openid_connect**: Compare only offset-aware datetimes (`#1418`_, `f3556af`_)

* **plugins**: Adapt queryables additional_properties to providers config (`#1646`_, `cc6ecc9`_)

* **plugins**: Add alias to properties in cop_marine and EcmwfSearch plugins (`#1649`_, `ae93d5a`_)

* **plugins**: Add datetime for ecmwf search (`#1572`_, `b785e7c`_)

* **plugins**: Add ssl_verify where necessary and remove where unnecessary (`#1289`_, `0af86ad`_)

* **plugins**: Add temporal resolution to ecmwf properties (`#1899`_, `219e669`_)

* **plugins**: Auth only when needed during http download (`#1370`_, `6b6d64c`_)

* **plugins**: AWS rio_env s3_endpoint (`#1504`_, `e2846dd`_)

* **plugins**: Aws streamed downloads (`#1975`_, `652c927`_)

* **plugins**: Aws_session_token support in aws_auth (`#1267`_, `47ed8bb`_)

* **plugins**: AwsAuth without credentials (`#1865`_, `ab04612`_)

* **plugins**: AwsDownload with asset and ignore_assets (`#1571`_, `44ca6ff`_)

* **plugins**: Better error handling for cop_marine (`#1336`_, `72b14f0`_)

* **plugins**: Build_search_result end_date preprocessing (`#1304`_, `672fded`_)

* **plugins**: Check expiration time in token auth (`#1590`_, `15dbcb1`_)

* **plugins**: Cop_marine search by id (`#1923`_, `0d42f00`_)

* **plugins**: CopMarine dates check (`#1224`_, `87f69d3`_)

* **plugins**: Creodias_s3 search and download when no asset (`#1425`_, `aa3bb3c`_)

* **plugins**: Dates formatting and missing param in ECMWFSearch queryables (`#1956`_, `0fed963`_)

* **plugins**: Delete download link when order not finish (`#1952`_, `f020e24`_)

* **plugins**: Distinct headers for token retrieve and authentication (`#1451`_, `0f20c0a`_)

* **plugins**: Ecmwf geometries support (`#1924`_, `e996be9`_)

* **plugins**: EcmwfSearch orderable products search (`#1656`_, `a399a5b`_)

* **plugins**: ECMWFSearch strip_quotes implementation for dicts (`#1483`_, `2dbab73`_)

* **plugins**: FileNotFoundError on usgs auth attempt failure (`#1550`_, `2efa9e9`_)

* **plugins**: Filter using matching_url in SASAuth (`#1802`_, `c4e649c`_)

* **plugins**: GenericAuth missing credentials handle (`#1678`_, `576a2ac`_)

* **plugins**: Handle disabled count on cop_marine (`#1955`_, `816cf99`_)

* **plugins**: Handle InvalidRequest in AwsDownload (`#1532`_, `7c47474`_)

* **plugins**: Http asset HEAD check and ssl_verify (`#1266`_, `feef2bf`_)

* **plugins**: HTTPDownload conflicting files (`#1479`_, `f069ccb`_)

* **plugins**: Lru caching when fetching constraints with ECMWF (`#1698`_, `e23f47e`_)

* **plugins**: Metadata_mapping_from_product in search config (`#1737`_, `cdfe518`_)

* **plugins**: Missing datetime properties in ECMWFSearch result (`#1648`_, `9ac8d6a`_)

* **plugins**: Missing products conf in api plugin download (`#1241`_, `8bb11c4`_)

* **plugins**: Oidc_config_url usage and expired token fix (`#1346`_, `5c96977`_)

* **plugins**: Onda and no matching settings auth plugins (`#1340`_, `55bea37`_)

* **plugins**: Openid_connect requests error handling (#1320) (`#1663`_, `9926083`_)

* **plugins**: Order retry (`#1676`_, `3602426`_)

* **plugins**: Pagination is not globally mandatory (`#1240`_, `cda35ec`_)

* **plugins**: Product types discovery disabled by default on StaticStacSearch (`#1259`_,
  `1e42221`_)

* **plugins**: Qssearch without productType (`#1295`_, `f274d4a`_)

* **plugins**: Raise error if no data available on AwsDownload (`#1257`_, `dc24261`_)

* **plugins**: Raise error on failed empty stream_zip (`#1475`_, `f82f016`_)

* **plugins**: Raise error when http download order fails (`#1338`_, `86baf25`_)

* **plugins**: Raise errors when metadata discovery is not allowed (`#1534`_, `855ffa3`_)

* **plugins**: Remove default HTTPDownload zip extension (`#1400`_, `07a38ac`_)

* **plugins**: Remove default queryables form value (`#1473`_, `45c1aa7`_)

* **plugins**: Send client_id/client_secret with refresh_token in TokenAuth (`#1597`_, `9b626a9`_)

* **plugins**: Skip product types discovery on parsing errors (`#1300`_, `1948645`_)

* **plugins**: Small bugs in ecmwf queryables (`#1509`_, `e71ca9c`_)

* **plugins**: STAC providers datetime queryables handling (`#1625`_, `9417fd9`_)

* **plugins**: StaticStacSearch text opener (`#1643`_, `71a51f1`_)

* **plugins**: Stored oidc token conflicts (`#1232`_, `4ff098f`_)

* **plugins**: Uncomplete search validation for cop_ads and wekeo_ecmwf (`#1951`_, `3cc1d7c`_)

* **plugins**: Urlopen timeout handling (`#1547`_, `643cb3c`_)

* **plugins**: Validation error if 400 error during order (`#1390`_, `a0da7e4`_)

* **product-types**: Default license from proprietary to other (`#1492`_, `35949ce`_)

* **provider**: Use sobloo official api endpoint, fixes #115 (`782d34c`_)

* **provider**: Wekeo_ecmwf default dates (`#1288`_, `f4b7a67`_)

* **providers**: Added month/year mapping and default values for CMIP6_CLIMATE_PROJECT (`#1872`_,
  `dcdca60`_)

* **providers**: Allow search by id for CLMS_CORINE with wekeo_main (`#1746`_, `bfe5e71`_)

* **providers**: Area metadata mapping for CAMS_EU_AIR_QUALITY_FORECAST (`#1225`_, `8539f18`_)

* **providers**: CLMS_CORINE metadata mapping for wekeo (`#1846`_, `55b1ffe`_)

* **providers**: Cop_ads and wekeo_ecmwf metadata mapping (`#1389`_, `277b63b`_)

* **providers**: Cop_ewds metadata mapping (`#1629`_, `30b5554`_)

* **providers**: Creodias and cop_dataspace products title mapping (`#1635`_, `850cb50`_)

* **providers**: Creodias processing:version as str (`#2015`_, `3f8c56a`_)

* **providers**: Default search timeout to 20s (`#1505`_, `52a69f6`_)

* **providers**: Default values and dates for GLOFAS and EFAS product types (`#1467`_, `419956b`_)

* **providers**: Default values for some ECMWF collections (`#1575`_, `dc22c2e`_)

* **providers**: Earth_search S2_MSI_L2A_COG assets href (`#1866`_, `f14ef6b`_)

* **providers**: FIRE_HISTORICAL on wekeo_ecmwf (`#1392`_, `3f0f2cd`_)

* **providers**: Fix syntax error (`#1860`_, `d207f27`_)

* **providers**: Geodes API update (`#1581`_, `dfb7a0f`_)

* **providers**: Geodes conf fixes (`#1363`_, `10923f0`_)

* **providers**: Geodes datetime search (`#1592`_, `87ade04`_)

* **providers**: Geodes id property (`#1441`_, `132ff00`_)

* **providers**: Geodes max_items_per_page down to 80 (`#1938`_, `abf8c71`_)

* **providers**: Geodes metadata mapping (`#1468`_, `67039bc`_)

* **providers**: Geodes tileIdentifier (`#1457`_, `6229ca6`_)

* **providers**: Handle cop_marine in situ historical data (`#1301`_, `b3c0263`_)

* **providers**: Harmonize orbitDirection properties (`#1836`_, `b428d61`_)

* **providers**: Harmonize orbitDirection properties to lowercase (`#1830`_, `57fecd0`_)

* **providers**: Harmonize polarizationChannels property (`#1831`_, `b85ef0f`_)

* **providers**: Instrument format for STAC providers (`#1803`_, `e1a56fd`_)

* **providers**: Metadata mapping for EEA_DAILY_VI with wekeo_main (`#1464`_, `b21735a`_)

* **providers**: Missing orderable metadata mapping for some dedl product-types (`#1358`_,
  `90da4f0`_)

* **providers**: PlatformSerialIdentifier mapping for creodias/cop_dataspace (`#1848`_, `f890fbf`_)

* **providers**: PolarizationChannels mapping for STAC providers (`#1870`_, `819ecb2`_)

* **providers**: Product types discovered properties format (`#1783`_, `7824f6a`_)

* **providers**: Queryables fixes for some product-types (`#1462`_, `6d51c12`_)

* **providers**: Recognize geodes auth errors during download (`#1562`_, `d325727`_)

* **providers**: Remove astraea_eod provider (`#1383`_, `d2fc110`_)

* **providers**: Remove cacheable param for wekeo order (`#1239`_, `d29137d`_)

* **providers**: Remove deprecated product type (S2_MSI_L2AP) (`#1764`_, `7b1fb89`_)

* **providers**: Remove eumetsat_ds duplicate product types (`#1514`_, `e3be09a`_)

* **providers**: Remove no-more-available theia provider (`#1736`_, `e81013b`_)

* **providers**: Remove onda provider (`#1564`_, `a9234e4`_)

* **providers**: Remove two_passes_id_search config param (`#1298`_, `27f41ae`_)

* **providers**: Remove unnecessary metadata mappings for eumtesat_ds (`#1502`_, `8facb6d`_)

* **providers**: Rename EO:CLMS:DAT:CORINE to EO:EEA:DAT:CORINE (`#1576`_, `2d3f6da`_)

* **providers**: Renamed THEIA collections on geodes (`#1974`_, `39d0962`_)

* **providers**: Restore ssl verify for geodes (`#1780`_, `8b771f8`_)

* **providers**: S2_MSI_L1C search-by-id for earth_search (`#1053`_, `05f1142`_)

* **providers**: S2_MSI_L2A_COG moved to earth_search (`#1841`_, `786c663`_)

* **providers**: Sanitize eumetsat_ds titles (`#1582`_, `28c0bd0`_)

* **providers**: Search parameters parsing on hydroweb_next (`#1981`_, `ee21c4f`_)

* **providers**: Small errors in wekeo metadata mappings (`#1335`_, `7252ad5`_)

* **providers**: Ssl verify for fedeo_ceda (`#1801`_, `45b891a`_)

* **providers**: Typo in geodes_s3 user conf template (`#1536`_, `697b5c8`_)

* **providers**: Typos in dedl provider config (`#1308`_, `cecc9d8`_)

* **providers**: Update default version for CAMS_GLOBAL_EMISSIONS (`#1738`_, `81e4b90`_)

* **providers**: Update wekeo config for CLMS global collections (`#1985`_, `8762d3a`_)

* **providers**: Update wekeo config for COP-DEM produc types (`#1516`_, `d38035f`_)

* **providers**: Usage of hydrological_year in wekeo_ecmwf (`#1313`_, `6088572`_)

* **providers**: Usgs search by id (`#1262`_, `7f1b989`_)

* **providers**: Wekeo_main metadata mapping (`#1549`_, `0a66ed9`_)

* **providers**: Wekeo_main orderable products download (`#1670`_, `d573846`_)

* **queryables**: Improve date parameter parsing (`#1702`_, `9563d4b`_)

* **queryables**: Missing search plugin auth (`#1194`_, `72ca3d7`_)

* **queryables**: Remove optional typing for extension fields (`#2058`_, `da1039b`_)

* **server**: Add datetime in collections cache hash (`#1256`_, `2e12639`_)

* **server**: Add default datetime in dedt_lumi generated items (`#1472`_, `20c5cbf`_)

* **server**: Add provider in self link of item (`#1090`_, `2c0e690`_)

* **server**: Append external collections metadata to product_types config (`#1197`_, `203665d`_)

* **server**: Avoid multiplication of providers (`#1187`_, `8f0eacf`_)

* **server**: CdsApi download using _dc_qs parameter (`#958`_, `1af3d19`_)

* **server**: Common queryables for given provider (`#978`_, `149b4e5`_)

* **server**: Correct links in stac model (`#813`_, `3371426`_)

* **server**: Correct STAC collection generation (`#1278`_, `2a318e7`_)

* **server**: Delete file after download without streaming (`#992`_, `819247c`_)

* **server**: Empty instruments mapping (`#1763`_, `11f2318`_)

* **server**: Geodes property parsing (`#1477`_, `270e752`_)

* **server**: Get proxy info in next POST search URL (`#1106`_, `0196e96`_)

* **server**: Handle DownloadError and RequestError in server mode (`#806`_, `3e9ec56`_)

* **server**: Invalid characters in download urls (`#1276`_, `0e511e7`_)

* **server**: Landing page and collections metadata update (`#1221`_, `bc932d6`_)

* **server**: List providers in stac calalogs (`#884`_, `e98e0a9`_)

* **server**: Load json string intersects param as dict (`#821`_, `5b98144`_)

* **server**: Load processing level as string in external stac collection (`#1429`_, `90f0545`_)

* **server**: Merge providers by group & use groups in item links (`#1192`_, `ea12faa`_)

* **server**: Merge providers from external STAC collection (`#1176`_, `2c5a0e0`_)

* **server**: Missing intersects parameter in request body model (`#797`_, `1a627c7`_)

* **server**: Multithreaded requests (`#843`_, `5e389e4`_)

* **server**: Next page bbox is a list (`#1095`_, `e6743bb`_)

* **server**: NoneType error in download with api plugin (`#1087`_, `44172e0`_)

* **server**: Opened time intervals (`#837`_, `fefce06`_)

* **server**: Properly display next page object (`#895`_, `17244d7`_)

* **server**: Provider setting in server mode (`#808`_, `9bebfed`_)

* **server**: Queryable issues and parameters prefixes (`#1318`_, `cbe3238`_)

* **server**: Raise error if search fallback fails (`#1001`_, `db70682`_)

* **server**: Raise_errors disabled for server search fallback (`#812`_, `0b62dab`_)

* **server**: Remove catalogs (`#1306`_, `1d3070f`_)

* **server**: Remove duplicate host (`#1794`_, `fa22145`_)

* **server**: Replace 400 with 404 when collection or item not found (`#1182`_, `c5534d1`_)

* **server**: Send search_stac_items in its own threadpool (`#1323`_, `eb54b16`_)

* **server**: Single asset download with ignore_assets plugin setting (`#1199`_, `fe356ec`_)

* **server**: Stac ext collection keywords mapping (`#1180`_, `4358ae6`_)

* **server**: Type missing on some queryables (`#1083`_, `0440f20`_)

* **server**: Use only one of bbox and intersects on search (`#796`_, `4b1397b`_)

* **utils**: Avoid repeated SSL context creation (`#1758`_, `f93645e`_)

* **utils**: Include response text in RequestError (`#1341`_, `9b6f422`_)

* **wekeo**: Correct order link for GRIDDED_GLACIERS_MASS_CHANGE (`#1258`_, `050c371`_)

* **wekeo**: Yml anchor issue in provider config (`#1315`_, `4b35e1d`_)

* **wekeo-ecmwf**: Correct queryables (`#1427`_, `7658679`_)

Build System
------------

* Add docker image (`#1971`_, `0c5ed7c`_)

* Add missing cryptography requirement (`#1419`_, `fe753c4`_)

* Add missing requirements (`#1020`_, `29b824e`_)

* Add python3.13 and drop python3.8 support (`#1344`_, `fdd3dce`_)

* Add python3.14 support (`#1973`_, `07f484b`_)

* Bump alpine version on Dockerfile to prevent certificate error on geodes (`#2004`_, `9cf737b`_)

* Bump release (`#1508`_, `cfc4bca`_)

* Bump version (`054f4a8`_)

* Bump version (`#480`_, `3f39f6c`_)

* Bump version (`#475`_, `54a5182`_)

* Correct PYTHONPATH (`#976`_, `3a90ea3`_)

* Do not install usgs from git repo (`#1569`_, `13d3a73`_)

* Downgrade owslib with py310 (`#469`_, `1c7edf6`_)

* Downgrade owslib with py310 (`#469`_, `e161f5d`_)

* Fixed package build warnings (`#2033`_, `ce877a6`_)

* Freeze click version to prevent test fail (`4776cf9`_)

* Install boto3 by default (`#1219`_, `ccf150d`_)

* Orjson pinned for windows py312 (`#1079`_, `930ada1`_)

* Packaging update following PEP517 (`#435`_, `e470a6e`_)

* Pin pydantic < 2.12.0 to prevent sphinx failures (`#1873`_, `1b17b4a`_)

* Prevent pydantic v2.10.0 usage (`#1411`_, `1b3f312`_)

* Refactor and new optional dependencies (`#1108`_, `3ebcffd`_)

* Remove dependencies max versions (`#1519`_, `74490a2`_)

* Remove owslib version upper limit (`#1021`_, `ebfd3ec`_)

* Setup.cfg to pyproject.toml (`#2037`_, `5cfd0ac`_)

* Setuptools_scm max version for py36 (`#477`_, `f2d9979`_)

* Specify shapely min version (`#1155`_, `af5e548`_)

* Tests speedup using uv and tox-uv (`#1347`_, `7bf602f`_)

* Update usgs to 0.3.6 (`#1688`_, `e63cfb1`_)

* Usgs last version from git repo (`#1552`_, `2bc623f`_)

* Uvicorn extras fix (`#1152`_, `50a451f`_)

* **deps**: Bump actions/download-artifact from 3 to 4 (`#1310`_, `6c46430`_)

* **deps**: Update upload-artifact action v4 (`#1314`_, `eb0e34e`_)

* **docs**: Pin sphinxcontrib dependencies (`#988`_, `fe2a514`_)

* **docs**: Use sphinx 8 (`#2006`_, `811c176`_)

Chores
------

* Allow pydantic >= 2.12.0 by buiding docs with python3.13 (`#1966`_, `a8261af`_)

* Bump version (`#339`_, `1e049ee`_)

* Bump version (`#331`_, `067928e`_)

* Bump version (`#318`_, `8c5a658`_)

* Bump version (`#308`_, `362055e`_)

* Bump version (`#302`_, `f32b807`_)

* Bump version (`277b1e1`_)

* Bump version (`0852432`_)

* Bump version (`bd351ec`_)

* Bump version (`c667e72`_)

* Bump version (`9680cf3`_)

* CI with GitHub actions (`#159`_, `541794b`_)

* Citation.cff file (`#2038`_, `17ca92f`_)

* Deprecate unused code (`#1788`_, `2658e69`_)

* Ensure locations dir exists during init (`#1958`_, `df263c2`_)

* Gitlab ci configuration, fixes eodag/eodag#22 (`8c8bf95`_)

* Labextension conf in gitignore (`#1984`_, `b28d179`_)

* Nbsphinx version (`d2817ce`_)

* Pytest cfg to pyproject.toml (`#2043`_, `8664eb2`_)

* Python versions update (`741a340`_)

* Remove remaining server-mode related code (`#1963`_, `8131264`_)

* Removed fixed dependencies, fixes GH-82 (`ded0bfe`_)

* Removed xarray pkg version upper bound (`52e8363`_)

* Tooling update (`fc07f66`_)

* Tox fix for pypi (`#181`_, `c043500`_)

* Tox fix for pypi (#181) (`#182`_, `044fd8b`_)

* Update assets rendering depth (`#2016`_, `c060011`_)

* Update external product types reference (`#1880`_, `d67aaaf`_)

* Update external product types reference (`#1879`_, `89fa278`_)

* Update external product types reference (`#1874`_, `c7c150b`_)

* Update external product types reference (`#1855`_, `ec37bc9`_)

* Update external product types reference (`#1847`_, `a1f8cef`_)

* Update external product types reference (`#1818`_, `596b6bc`_)

* Update external product types reference (`#1816`_, `4d65d33`_)

* Update external product types reference (`#1804`_, `d2435ae`_)

* Update external product types reference (`#1799`_, `5aff668`_)

* Update external product types reference (`#1790`_, `5504ad5`_)

* Update external product types reference (`#1786`_, `9596c5b`_)

* Update external product types reference (`#1784`_, `4156fda`_)

* Update external product types reference (`#1782`_, `5220b60`_)

* Update external product types reference (`#1768`_, `247beb9`_)

* Update external product types reference (`#1744`_, `be7d098`_)

* Update external product types reference (`#1735`_, `9c6b891`_)

* Update external product types reference (`#1733`_, `9a838c1`_)

* Update external product types reference (`#1712`_, `f10136e`_)

* Update external product types reference (`#1694`_, `a28a40b`_)

* Update external product types reference (`#1691`_, `e817031`_)

* Update external product types reference (`#1686`_, `9c076ef`_)

* Update external product types reference (`#1674`_, `dfdfc7a`_)

* Update external product types reference (`#1669`_, `fec1838`_)

* Update external product types reference (`#1660`_, `82d55c0`_)

* Update external product types reference (`#1641`_, `2546986`_)

* Update external product types reference (`#1639`_, `abeb932`_)

* Update external product types reference (`#1634`_, `aa764c0`_)

* Update external product types reference (`#1628`_, `bad38f8`_)

* Update tox (`#160`_, `857eeb7`_)

* V4 ext collections (`#1878`_, `43ab2c0`_)

* **cli,docs**: Deprecate STAC REST API server (`#1837`_, `083989e`_)

* **deploy**: Remove deprecated common values (`154ea6d`_)

Code Style
----------

* Lighter crunchers logging (`3696fc8`_)

Continuous Integration
----------------------

* Action-semantic-pull-request (`#1570`_, `80cf170`_)

* Automatic changelog update (`#1601`_, `0625802`_)

* Automatic deployment (`#1655`_, `4fbdf8b`_)

* Better external collections summary in auto-update PR (`#1907`_, `43d9fb4`_)

* Cov reports only for PR (`#416`_, `059bc07`_)

* Coverage reports in gh actions (`#411`_, `4e739f8`_)

* Coverage to distinct pr comments (`#723`_, `f66ed1e`_)

* Fetch collections PR fix and refactor (`#1917`_, `0b88c50`_)

* Fetch wekeo product types (`#1377`_, `2043582`_)

* Fetch-product-types diff formatting (`#1351`_, `348e066`_)

* Fixed changelog generation (`#1630`_, `3bd7a5c`_)

* Github actions coverage report update (`#1024`_, `3f08774`_)

* Github actions updates (`#1249`_, `e0ce87b`_)

* Gitleaks in pre-commit (`#1982`_, `e740d97`_)

* Latest pandoc version in gh actions (`#744`_, `274b6b9`_)

* Limit fetch product types action PR body length (`#727`_, `bbd367a`_)

* Mypy in linting github action (`#1326`_, `3061402`_)

* Nose replaced with pytest and published test reports (`#406`_, `6ca3d50`_)

* Params_mapping_to_csv in docs test env (`#299`_, `fdc853e`_)

* Pre-commit replaced with faster prek (`#1914`_, `eb5dd5f`_)

* Pre-commit repos update (`#535`_, `380ce3f`_)

* Pre-commit update (`#579`_, `dc9f2c9`_)

* Pypi skip existing (`707dd1b`_)

* Pypi unskip existing (`1405661`_)

* Remove tests from coverage (`#717`_, `e0108b2`_)

* Run tests for v4 branch and associated PRs (`#1868`_, `a944aab`_)

* Token usage for coverage report publishing (`#1633`_, `6a7e0d4`_)

* Update changelog generation (`#1627`_, `20e0ef7`_)

* Upgrade gh-actions (`#670`_, `14ece44`_)

* Use flake8-eradicate and remove commented out code (`#832`_, `d824947`_)

* Use personal access token for deploy github action (`#1693`_, `ff777d7`_)

Documentation
-------------

* Add doi and zenodo badge (`#2040`_, `727fb09`_)

* Add eodag.utils.DownloadedCallback to api reference (`#121`_, `5400db4`_)

* Add missing url in sara provider configuration (`#1062`_, `b2c1467`_)

* Add wekeo_cmems provider in index and plugins documentation pages (`#1081`_, `e0774f9`_)

* Adding product types (`#1434`_, `2b94fd0`_)

* Aws_eos logo added (`#1773`_, `af6d959`_)

* Better crunch documentation (`#2046`_, `e119d93`_)

* Changelog typo (`#553`_, `bb6dca4`_)

* Changelog update (`#1254`_, `f457527`_)

* Cleanup and update of docstrings (`#355`_, `70aa455`_)

* Clearer info about default filename and output folder (`#254`_, `3c7598b`_)

* Cli and stac support update (`#1707`_, `c50aae1`_)

* Conda optional deps (`#1343`_, `7adc615`_)

* Configuration environment variables defaults (`#1681`_, `6e8eb6b`_)

* Contact email update (`#695`_, `e7873c0`_)

* Copernicus dem tutorial (`07aa48a`_)

* Copyright date fix (`#436`_, `f6d0ded`_)

* Corrected typo in the "Serialize/Deserialize" page of the documentation (`#920`_, `9a16a50`_)

* Credentials setting using environment variables better doc (`#641`_, `92392d0`_)

* Csgroup logos updated (`#374`_, `da6df3f`_)

* Dead-links and out-of-date param fix (`#1692`_, `445a20e`_)

* Default links to readthedocs latest version (`#287`_, `f96a93c`_)

* Developer documentation update (`#1327`_, `0d7ff3c`_)

* Display star number instead of watch number (`#175`_, `d278e12`_)

* Document constants in API ref (`#2044`_, `8f46614`_)

* Document delete_archive configuration (`#358`_, `3963758`_)

* Documentation overhaul (`#1823`_, `df67693`_)

* Documentation overhaul (`#233`_, `bab1b7e`_)

* Documentation update before v2.3.0b1 release (`#301`_, `62c75fe`_)

* Documentation update for 2.2.0 (`#211`_, `88fd434`_)

* Download methods (`#1282`_, `1e7247f`_)

* Eodag-cube api ref (`#1511`_, `f5b4015`_)

* Eodag-cube augment_from_xarray method (`#1989`_, `1fa56a3`_)

* Extend documentation for guess_product_type and other minor updates (`#756`_, `9826723`_)

* Fix broken link in documentation (`#388`_, `74aaad6`_)

* Fix cli examples and typos in contribute page (`#562`_, `3c4ca8a`_)

* Fix intersphinx_mapping links (`#282`_, `a9c30da`_)

* Fix list_product_types output (`#284`_, `6d29809`_)

* Fix shapefiles deadlink in sentinel-1 ship detection tutorial (`#451`_, `ff9fcee`_)

* Fix typehint of kwargs according to PEP484 (`#438`_, `95c7e31`_)

* Fixed and scrollable sidebar (`#196`_, `0adf3de`_)

* Fixed binder tutos links (`#1651`_, `5ec4421`_)

* Fixed rtype for guess_product_type (`#543`_, `837c127`_)

* Fixes params tables glitch (`#527`_, `81a4337`_)

* Fixes tutos auxdata reference (`072b93e`_)

* Import_stac_items documentation update (`#1709`_, `7a04158`_)

* Link to labextension in readme and side-projects (`#352`_, `6d44c2a`_)

* Make meteoblue product types visible (`#642`_, `6f52040`_)

* Make product types catalog more visible (`#603`_, `c2531ce`_)

* Menu items sort (`16619f2`_)

* Metadata mapping documentation (`#419`_, `2b11eee`_)

* Metadata mapping update (`#367`_, `18d93f6`_)

* Meteoblue provider (`#604`_, `6fee322`_)

* Mock search plugin section (`#1242`_, `e21c5d7`_)

* More logging when searching by id (`#336`_, `d2b436a`_)

* Move queryables doc to a new notebook (`#1447`_, `0d90d9e`_)

* Pin sphinx-book-theme version (`#665`_, `1bbfaab`_)

* Plugins and utils documention update (`#1297`_, `cdee784`_)

* Prevent newline between README badges (`#1109`_, `e619c88`_)

* Providers description update (`#714`_, `035f5a7`_)

* Providers.yml comments for sticky scroll (`#1059`_, `b49dfce`_)

* Queryables guide update (`#2005`_, `c3429d8`_)

* README update (`ee240fa`_)

* Readme update (`ab57fc9`_)

* Readme update (`f3d5535`_)

* Readme, badges and classifiers update (`#224`_, `8c318a5`_)

* Ref to dockerhub eodag-server (`#715`_, `1596872`_)

* References to eodag-sentinelsat (`1a38d08`_)

* Remove beta from ads and cds links (`#1541`_, `3a9ac6e`_)

* Remove current module from summarized items (`#1264`_, `f7efdd0`_)

* Remove onda logo (`#1566`_, `cd50894`_)

* Remove unneeded code and files (`211bdfd`_)

* Reorder sections in ecmwf tuto (`#511`_, `2cba529`_)

* Request an access to M2M API for usgs (`#269`_, `7da1505`_)

* Restored readme logo (`#1057`_, `1a23ff3`_)

* Rtd copyright 2024 (`#1121`_, `5f88b80`_)

* Sara provider documentation (`#602`_, `d238c08`_)

* Search dates documentation (`#1063`_, `a65bae4`_)

* Stac client tuto (`5e6764e`_)

* Swagger stac api doc (`e095901`_)

* Titles fixes in Breaking Changes (`#1498`_, `908c372`_)

* Typo in geodes register link (`#1500`_, `687d3f4`_)

* Typos (`#510`_, `482eae3`_)

* Update CS GROUP name (`#1122`_, `bc1953a`_)

* Update doc and tutos following API simplifications (`#420`_, `ace638f`_)

* Update documentation and community templates (`#198`_, `2140d9d`_)

* Update layout (`faa2a50`_)

* Update notice (`#724`_, `c328060`_)

* Update openapi static spec (`#846`_, `ec1d847`_)

* Update overview graph (`#893`_, `b2e448f`_)

* Update ProgressCallback documentation (`#276`_, `3ce721d`_)

* Update readthedocs img (`#675`_, `14c9504`_)

* Update setup_logging in tutorials (`#276`_, `3ce721d`_)

* Update sphinx theme and remove jquery (`13c177b`_)

* Update stac browser screenshot (`#710`_, `3018325`_)

* Update tutorials using eodag-cube (`#1436`_, `8331bd1`_)

* Updated contribution guidelines link in PR template (`#1667`_, `e5cd082`_)

* Updated description, overview and ecosystem (`#1734`_, `ea929e4`_)

* Updated wekeo tutorial (`#1367`_, `024a916`_)

* User friendly parameters mapping documentation (`#299`_, `fdc853e`_)

* Usgs registration update (`#1551`_, `53a53c8`_)

* V2.0 documentation update (`3a645b6`_)

* V3 breaking changes (`#1281`_, `fe3bf6d`_)

* Yaml settings quoting (`#1022`_, `49209ff`_)

* **tuto**: Add tutorial for CCI data through fedeo_ceda (`#1832`_, `01b130a`_)

Features
--------

* Add --all option to the search command to search for all the products (`#204`_, `49b15cc`_)

* Add a locations dict parameter to search (`616d1a9`_)

* Add a mechanism to get the next page in a search (`#190`_, `ab1c105`_)

* Add a warning when box or bbox are used instead of geom in a search (`#190`_, `ab1c105`_)

* Add an internal decorator to deprecate objects (`#225`_, `0632e41`_)

* Add callback to download method (`#121`_, `6ca2b90`_)

* Add callback to download methods (#121)(#357) (`6ca2b90`_)

* Add callback to download_all method (`#121`_, `5400db4`_)

* Add callback to download_all method (`#121`_, `6ca2b90`_)

* Add callback to download_all method (#121)(#381) (`5400db4`_)

* Add cop(ads, cds) product types (`#898`_, `0dcc36d`_)

* Add cop_ads and cop_cds providers with CdsApi plugin (`95f6c32`_)

* Add COP_DEM product types in creodias_s3 (`#1002`_, `9138237`_)

* Add cop_marine provider (`#1131`_, `19e0d05`_)

* Add count to _do_search and _do_search tests (`#190`_, `ab1c105`_)

* Add docker-compose for STAC server and browser (`#183`_, `7f1f3e1`_)

* Add filter_online to SearchResult (`#458`_, `835eab7`_)

* Add METOP product types for eumetsat_ds (`#1143`_, `3543a40`_)

* Add more convert methods to SearchResult (`#450`_, `be026c2`_)

* Add new product types (`#1164`_, `b507413`_)

* Add new provider dynamically (`b912305`_)

* Add Planetary Computer as a new provider (`#659`_, `372afbe`_)

* Add provider dedl (`#750`_, `2fc91a9`_)

* Add provider eumetsat_ds (`#1060`_, `05697ac`_)

* Add providers metadata to items endpoint (`#879`_, `7f520bc`_)

* Add quicklook & thumbnail to stac properties (`0f3b23e`_)

* Add refresh token to ``OIDCAuthorizationCodeFlowAuth`` plugin (`#1138`_, `8822525`_)

* Add search_all to EODataAccessGateway (`#190`_, `ab1c105`_)

* Add search_iter_page to iterate over the pages of a product search (`#190`_, `ab1c105`_)

* Add sorting feature in library mode (`#943`_, `dd9a2ef`_)

* Add static type information (`#863`_, `094cdb9`_)

* Add strict product types mode (`#1677`_, `5077fa5`_)

* Add support for py310 (`#407`_, `2d8cec2`_)

* Add support for py311 (`#552`_, `3465afe`_)

* Add timeout error (`#982`_, `1a0e007`_)

* Add to query the parameters set in the provider product type definition (`ed3daa0`_)

* Add two new methods to search for products, search_iter_page and search_all (`#190`_, `ab1c105`_)

* Add two utilities to convert paths to uri (`#244`_, `6ab4262`_)

* Added awsProductId property for usgs_satapi_aws (`#377`_, `ba7f655`_)

* Added SARA as a provider and respective S3 product definitions. (`#578`_, `4cd2070`_)

* Added support for py38 (`fe0d8da`_)

* Adjust timeout to match the provider's one (`#1163`_, `80f9403`_)

* Advanced tuto notebook, fixes #130 (`22f02d8`_)

* Allow empty geometry for stac providers (`#485`_, `fc01129`_)

* Allow headers and url formatting in TokenAuth (`#447`_, `99db80a`_)

* Allow local constraints files (`#1105`_, `59ccd8b`_)

* Allow no auth for download requests (`#1196`_, `d8aefa9`_)

* Allow to dynamically set download options, fixes GH-145 GH-112 (`1ad5afe`_)

* Assets support for HTTPDownload (`02f9d9f`_)

* Astraea_eod as new STAC provider (`1a0ff44`_)

* Attach the crunchers directly to SearchResult (#206) (`#359`_, `91e1a90`_)

* Auth on private stac search (`#443`_, `69baba5`_)

* Auto load ext plugins providers config, fixes GH-172 (`#176`_, `21a2dae`_)

* Automatic deletion of downloaded product zip after extraction (`#358`_, `3963758`_)

* Automatic deletion of downloaded product zip after extraction (#144) (`#358`_, `3963758`_)

* AwsDownload streaming (`#997`_, `72e7a48`_)

* Better generated stac catalogs title & desc (`#710`_, `3018325`_)

* Better logs when a product is ordered (`#449`_, `2a18716`_)

* Cached jsonpath.parse (`#502`_, `ac4edeb`_)

* CBERS-4 for aws_eos (`baa5f84`_)

* Check manisfest.safe for SAFE build (`#218`_, `fec965f`_)

* Configurable assets filtering (`#1033`_, `d4d6bdf`_)

* Configurable download timeout (`#1124`_, `a29e7a7`_)

* Configurable eodag logging in docker stac-server (`#323`_, `4a3e67a`_)

* Configurable requests ssl_verify (`#1045`_, `fe76492`_)

* COP-DEM through creodias (`#882`_, `176ac95`_)

* Creodias metadata mapping update (`#294`_, `1275815`_)

* Customize requests headers with EODAG version as user agent (`#656`_, `0a3d308`_)

* Customized and faster deepcopy (`#664`_, `d071212`_)

* Dedt_lumi provider (`#1119`_, `9729aa4`_)

* Default user_conf usage in cli mode (`2ec4edb`_)

* Discovered product types keywords (`#592`_, `92565f6`_)

* Distinct sentinel non-safe product types (`#228`_, `dac0046`_)

* Do not run flasgger automatically (`#529`_, `2086412`_)

* Download assets subset (`#932`_, `4f74c83`_)

* Earth_search as new provider (`4f64016`_)

* Enable kwargs when searching by id (`#329`_, `53c1c5e`_)

* EODAG_PROVIDERS_CFG_FILE env var (`#836`_, `ec4c868`_)

* EOProduct defaultGeometry property (`#653`_, `a10c807`_)

* EOProduct drivers definition update (`#316`_, `7f7a236`_)

* Expose aws env settings in AwsDownload (`#319`_, `389bae3`_)

* Expose raise_errors in _do_search and docstring (`#190`_, `ab1c105`_)

* Extend freetext search to all filters (`#1070`_, `ac53539`_)

* External enhanced product types metadata (`#1008`_, `be8f361`_)

* External product types conf on gh pages (`#491`_, `a65a6bc`_)

* Extract archives to temporary directory (`#358`_, `3963758`_)

* Fallback mechanism for search (`df440aa`_)

* Fetch ext product types before searching unkown product type (`#559`_, `68f98df`_)

* Fetch product types optimization (`#683`_, `e6c220c`_)

* Flask to FastAPI (`#701`_, `4c373fd`_)

* Generate record hash from product_type + id (`#1023`_, `c8189af`_)

* GENERIC_PRODUCT_TYPE usage for unknown product types fixes (`73a0364`_)

* Get queryables for wekeo with a constraints file (`#1104`_, `3bcdd79`_)

* Get_data, drivers and rpc server moved to eodag-cube (`de3f873`_)

* Get_logging_verbose function added (`#283`_, `d175b32`_)

* Guess eoproduct.product_type from properties (`#380`_, `df05c35`_)

* Handle EWKT geometry format (`#619`_, `2c26978`_)

* Handle integers as shapefile attributes (`#1280`_, `73d8f11`_)

* Helm chart (`#739`_, `92a537f`_)

* Http asset size from get method (`#566`_, `ce6d103`_)

* Http download through cdsapi (`#946`_, `4fa1b42`_)

* HTTPDownload.orderDownload and HTTPDownload.orderDownloadStatus methods (`#604`_, `6fee322`_)

* HTTPHeaderAuth accepts headers def in credentials (`#1215`_, `3309501`_)

* Hydroweb_next as new provider (`#711`_, `ba515f3`_)

* Implement new core method get_queryables (`#917`_, `aa09d73`_)

* Intersects option for filteroverlap (`7166a42`_)

* Keep origin assets in the stac server response (`#681`_, `2441b63`_)

* Keywords usage in product_types configuration (`#372`_, `2841f58`_)

* Lansat-8, MODIS, NAIP for aws_eos (`154fe2e`_)

* List provider-specific queryables (`#911`_, `40fe987`_)

* List providers supporting a given product_type (`31ca3eb`_)

* Load static features as SearchResult, fixes eodag/eodag#3 (`21ca0e5`_)

* Load static stac catalogs, fixes eodag/eodag#24 (`747b966`_)

* Log Retry-After info returned by provider, fixes #37 (`10c7b12`_)

* Match intersection of the datetime interval on search (`#1158`_, `0454652`_)

* Metadata auto discovery, replaces custom param (`9445964`_)

* Mix count and search requests when possible (`#632`_, `69d24e8`_)

* Mundi georss geometries handling (`#654`_, `0194b16`_)

* Mundi OFFLINE products order mechanism (`#645`_, `cc33191`_)

* Mutable progress bar (`#276`_, `3ce721d`_)

* New AwsAuth plugin enables no-sign-request and profiles (`b665dd4`_)

* New BuildPostSearchResult plugin (`#604`_, `6fee322`_)

* New CLI quicklooks flag for download command (`#279`_, `f7f12d8`_)

* New crunches FilterDate, FilterDate and updated FilterOverlap, fixes GH-137 (`e63d06d`_)

* New ecmwf provider and api plugin (`#452`_, `862ad15`_)

* New HttpQueryStringAuth plugin (`#604`_, `6fee322`_)

* New meteoblue provider (`#604`_, `6fee322`_)

* New method deserialize_and_register, fixes eodag/eodag#23 GH-140 (`a66523f`_)

* New notebook extra dependency (`#317`_, `6e82bad`_)

* New pagination key next_page_url_key_path (`#199`_, `4f1604e`_)

* New PostJsonSearch plugin, aws_eos provider + S2_MSI_L1C to SAFE (`539c605`_)

* New provider cop_dataspace (`#658`_, `e925418`_)

* New provider earth_search_cog for S2_MSI_L2A_COG (`#228`_, `dac0046`_)

* New provider earth_search_gcs (`#462`_, `9e6e51d`_)

* New provider for creodias s3 (`#986`_, `dda681a`_)

* New provider usgs_satapi_aws (`c9fd10d`_)

* New S3RestDownload plugin for mundi, fixes #127 (`863b372`_)

* New StaticStacSearch plugin (`d1b8f36`_)

* New theia product types for S2, SPOT, VENUS, OSO (`bb9ee42`_)

* No fixed provider for stac server (`05b24fc`_)

* Not-available products download management, fixes #125 (`05e2202`_)

* Optimize onda search and update discover_metadata mechanism (`#616`_, `70586e9`_)

* Peps queryable params update (`fd00cae`_)

* Per provider search timetout (`#841`_, `c63e4c7`_)

* POST reqs in StacSearch (`#363`_, `97f2357`_)

* Product type alias (`#905`_, `b61e2a0`_)

* Product types discovery (`#467`_, `e12c166`_)

* Product types update (`6bdc5bb`_)

* ProductionStatus standardization over providers (`63eea5a`_)

* Provider groups (`#1071`_, `7523dcf`_)

* Prune providers without credentials needing auth for search (`#442`_, `92a1fe2`_)

* Python 3.12 update (`#892`_, `4c340b0`_)

* Remove cloudcover restriction in product types discovery (`#530`_, `b94e3e1`_)

* Removed Python 3.7 support (`#903`_, `790df60`_)

* Requester_pays, base_uri, and and ignore_assets AwsDownload options (`#456`_, `414f84e`_)

* Restore pruned providers when configuration is updated (`#844`_, `cd527f1`_)

* Resume interrupted assets download using HTTPDownload (`#1017`_, `b800cac`_)

* Return all available providers for collection (`#835`_, `a2506e6`_)

* Rewrote progress callback mechanism (`#276`_, `3ce721d`_)

* Rewrote ProgressCallback interfaces and mechanism (`#276`_, `3ce721d`_)

* Roll back creodias to opensearch plugin (`#866`_, `6bdb107`_)

* S1_SAR_GRD and S2_MSI_L2A for aws_eos to SAFE format (`a0ba8d4`_)

* S1_SAR_GRD SAFE build for astraea_eod (`#218`_, `fec965f`_)

* S2_MSI_L1C S2_MSI_L2A SAFE build for astraea_eod (`#218`_, `fec965f`_)

* S2_MSI_L1C S2_MSI_L2A SAFE build for earth_sarch (`#218`_, `fec965f`_)

* S2_MSI_L2A for aws_eos search by id (specific_qssearch feature) (`662eaf1`_)

* S2_MSI_L2A support for peps, fixes #124 (`18ab40f`_)

* S3_OLCI_L2LFR support for mundi, see #124 (`a5c6389`_)

* SAFE build for STAC AWS providers (`#218`_, `fec965f`_)

* Search by geometry instead of bbox, fixes #49 (`8f2750e`_)

* Search by tile using tileIdentifier (`#713`_, `98eae2e`_)

* Sentinel non-safe product types (`#228`_, `dac0046`_)

* Sentinel5p and other product types updates for creodias mundi and onda (`#657`_, `e54ba86`_)

* Server search by ids (`#776`_, `fdd86a0`_)

* Server-mode parallel requests (`#741`_, `791fb4d`_)

* Server-mode streamed downloads (`#742`_, `6cc222a`_)

* Setting conf_dir with an environment variable and fallback directory (`#927`_, `a2466ae`_)

* Setuptools_scm usage (`#431`_, `4ca485c`_)

* Simplify odata metadata mapping using pre-mapping (`#622`_, `0cacf05`_)

* Stac api query fragment usage (`#367`_, `18d93f6`_)

* Stac collections filterables (`97b9b6a`_)

* Stac compliant rest api (`29e4d99`_)

* Stac custom search (`eb73623`_)

* Stac server criteria mapping from 'stac_provider.yml' (`#417`_, `51a489a`_)

* STAC server handling STAC Query fragment requests using client mapping criterias (`#417`_,
  `51a489a`_)

* Standardize output tree (`#746`_, `fbf81ca`_)

* Support opened time intervals for STAC providers (`#1144`_, `be370c7`_)

* Support regex query from locations file (`351e378`_)

* Thread id and server requests in debug logs (`#842`_, `2ff5763`_)

* Tqdm.auto usage (`#276`_, `3ce721d`_)

* Update wekeo sentinel product types (`#902`_, `9e881ac`_)

* Use ``downloadLink`` if exists for STAC providers (`#757`_, `73b17aa`_)

* Use constraints for queryables (`#981`_, `fbfc7d0`_)

* Use locations conf template by default, fixes eodag/eodag#6 (`115e53c`_)

* Use OData API for creodias & cop_dataspace (`#1149`_, `bb95da0`_)

* Use product_type_config as default product properties (`5a175cb`_)

* Wekeo driver update and new product types (`#798`_, `db336eb`_)

* Wekeo provider (`#772`_, `cd7ad76`_)

* Wekeo updated to hda-broker 2.0 (`#1034`_, `8132c6c`_)

* **AwsDownload**: Zip partial download from s3 (`#1561`_, `c59e264`_)

* **cli**: Commands chaining (`#1714`_, `754772b`_)

* **cli**: Download output directory (`#1716`_, `036b86b`_)

* **cli**: Download STAC items from their urls (`#1705`_, `5d598a9`_)

* **cli**: Search and directly download results (`#1706`_, `e1db471`_)

* **cop_dataspace**: Adds S1_SAR_GRD_COG and new odata query parameters (`#1277`_, `97b7b6f`_)

* **cop_ds**: Swap search plugin to opensearch (`#883`_, `42de3d8`_)

* **core**: Add env variable to whitelist providers (`#1672`_, `b93c4c8`_)

* **core**: Add EODAG_PRODUCT_TYPES_CFG_FILE env var (`#1559`_, `fd5ac0e`_)

* **core**: Add to_lower and to_upper parameters mapping (`#1410`_, `fb599d4`_)

* **core**: Add_provider method (`#1260`_, `513bfe0`_)

* **core**: Assets title normalized to key name (`#1826`_, `3662954`_)

* **core**: Collections representation classes (`#1731`_, `4b57160`_)

* **core**: Datetime filters in guess_product_types (`#1222`_, `1e37edc`_)

* **core**: Import stac items as SearchResult (`#1703`_, `1d49715`_)

* **core**: Improve search and authentication errors format (`#1237`_, `9a7b44c`_)

* **core**: Merge queryables by provider priority (`#1431`_, `2c7e575`_)

* **core**: Providers representation classes (`#1902`_, `fa5f42b`_)

* **core**: Queryables mechanism and ecmwf plugins updates (`#1397`_, `d709297`_)

* **core**: Search optional count and return only SearchResult (`#1200`_, `9c0d7e7`_)

* **core**: Search pagination using next_page (`#1745`_, `9abe670`_)

* **core**: Search validation (`#1877`_, `a157358`_)

* **core**: SearchResult HTML representation (`#1243`_, `ddb3c6f`_)

* **core**: Shared and multiple auth per provider (`#1292`_, `d148e50`_)

* **core**: Sorted discovered product types (`#1250`_, `641dfdf`_)

* **core**: STAC formatted properties (`#1730`_, `743d7b5`_)

* **core**: STAC formatted serialization (`#1940`_, `cdb3a17`_)

* **dedt_lumi**: Add parameter levelist & default time to 0000 (`#1126`_, `b54f8d5`_)

* **dedt_lumi**: Authenticate with destine credentials (`#1127`_, `52a4bfa`_)

* **eumetsat_ds**: New MTG product types (`#1513`_, `a3e2572`_)

* **plugins**: Add queryables to cop_marine (`#1638`_, `bcc793e`_)

* **plugins**: Auth token expiration margin (`#1665`_, `ef5fc18`_)

* **plugins**: Concurrent reqs for wekeo_cmems product-types fetch (`#1374`_, `7aa0309`_)

* **plugins**: Do not guess keys from href when inappropriate (`#1584`_, `beb6c1f`_)

* **plugins**: EcmwfSearch search-by-id (`#1580`_, `f296c52`_)

* **plugins**: Flatten_top_dirs true by default (`#1220`_, `888e7c4`_)

* **plugins**: New search config for assets mapping (`#1711`_, `1281268`_)

* **plugins**: Order and poll without downloading (`#1437`_, `7e502af`_)

* **plugins**: Possibility to create presigned urls (`#1845`_, `d002c38`_)

* **plugins**: Use original copernicus provider to list queryables of wekeo_ecmwf (`#1897`_,
  `0929a7c`_)

* **providers**: Add 2 new MSG collections to provider ``eumetsat_ds`` (`#1742`_, `801c52c`_)

* **providers**: Add CMIP6_CLIMATE_PROJECTIONS product type on cop_cds (`#1827`_, `308e0a9`_)

* **providers**: Add collections to eumetsat_ds (`#1979`_, `7d72d64`_)

* **providers**: Add DEDT Marenostrum provider (`#1869`_, `650d21b`_)

* **providers**: Add DT_CLIMATE_ADAPTATION collection (`#1908`_, `cd84b88`_)

* **providers**: Add GRIDDED_GLACIERS_MASS_CHANGE on provider cop_cds (`#1255`_, `a456422`_)

* **providers**: Add METOP_HIRSL1 and SATELLITE_FIRE_BURNED_AREA datasets (`#1227`_, `03306fa`_)

* **providers**: Add MSG product types (`#1348`_, `f65e582`_)

* **providers**: Add new eurostat product types to dedl (`#1662`_, `b7192b1`_)

* **providers**: Add product types to dedl provider (`#1515`_, `d549c5a`_)

* **providers**: Available product types update for creodias, cop_dataspace and wekeo_main
  (`#1817`_, `04b0b55`_)

* **providers**: Cop_ewds as new provider (`#1331`_, `28d9ae7`_)

* **providers**: Dedt_lumi search by geometry (`#1710`_, `efccdd0`_)

* **providers**: Geodes as new provider (`#1357`_, `ad57a81`_)

* **providers**: Geodes_s3 as new provider (`#1506`_, `23e1e54`_)

* **providers**: New mtg datasets in eumetsat_ds (`#1455`_, `6dc0509`_)

* **providers**: New provider fedeo_ceda (`#1778`_, `4d9f091`_)

* **providers**: Send query and filter parameters as is for STAC providers (`#1828`_, `3b04096`_)

* **providers**: Wekeo split to wekeo_main and wekeo_ecmwf (`#1214`_, `e864f53`_)

* **queryables**: Keep required even with default values (`#1521`_, `248990a`_)

* **server**: Add bbox queryables (`#1185`_, `17e68c2`_)

* **server**: Add blacklist config for assets alt URLs (`#1213`_, `53e2756`_)

* **server**: Add dedicated liveness endpoint (`#1353`_, `94d16b5`_)

* **server**: Add queryables endpoints (`#795`_, `03c72bc`_)

* **server**: Added bbox filter support for collections search (`#1671`_, `5717f0d`_)

* **server**: Caching LRU (`#1073`_, `60338b6`_)

* **server**: Enable HEAD requests (`#1120`_, `8dde659`_)

* **server**: Order and storage extensions usage (`#1117`_, `ff84295`_)

* **server**: Stac alternate assets (`#961`_, `dd8d653`_)

* **utils**: Update mimetypes definition (`#1445`_, `c44a5b8`_)

Performance Improvements
------------------------

* Download products and assets in parallel (`#1890`_, `b0b3799`_)

* **creodias**: Use zipper URL to avoid unecessary redirect (`#819`_, `812bc56`_)

* **plugins**: Optimize AwsDownload streaming (`#1740`_, `48f0e4c`_)

Refactoring
-----------

* Add _prepare_search method that is used by search internally (`#190`_, `ab1c105`_)

* Add eodag.crunch to import filters in eodag.plugins.crunch.filter_xxx (`#356`_, `16a7f51`_)

* Add EOProduct and SearchResult to main namespace (`#356`_, `16a7f51`_)

* Add some type hint (`#880`_, `a6be03b`_)

* Api base plugin inherits from Search and Download (`#1051`_, `2937f61`_)

* Aws auth typing and generic types (`#1486`_, `7bfe7fb`_)

* Black formatting (`#430`_, `9b4fd08`_)

* Black reformat and copyright date update (`91f2d1f`_)

* Boto3 ServiceResource type check (`#1949`_, `90fafbe`_)

* Cli.py collision name on eodag (`#1993`_, `6d6f34f`_)

* Constraints fetch using fetch_json method (`#1157`_, `1294ddd`_)

* Deprecate oauth plugin (`#1821`_, `1bdf8a9`_)

* Directly import urllib.parse methods (`#1761`_, `e4aca26`_)

* Download prepare & finalize to base plugin (`ada6797`_)

* Download retry decorator and tests (`#506`_, `b57fc76`_)

* EOProduct, SearchResult, and crunches easier to import (`#356`_, `16a7f51`_)

* Get_rio_env to AwsAuth (`#1838`_, `0ae4c17`_)

* Jsonpath obj creation factorized (`49e924d`_)

* Metadata parsing (`#669`_, `bf33e4c`_)

* Metadata.mapping format_query_params update (`#1142`_, `e47bd3e`_)

* Move CdsApi to BuildSearchResult and HTTPDownload (`#1029`_, `b3e40f6`_)

* Move dates utils functions to eodag.utils.dates (`#1844`_, `d2cd928`_)

* Output_dir and output_extension parameters (`#1279`_, `8586d37`_)

* PreparedSearch and RawSearchResult usage (`#1191`_, `2c37db3`_)

* Py35 compatibility, docstrings (`953acd7`_)

* Queryables type to Annotated (`#1005`_, `748e34e`_)

* Remove deprecated code (`#1781`_, `09e14fe`_)

* Remove deprecated converters and plugins (`#1789`_, `edff5fe`_)

* Remove deprecated OAuth (`#1839`_, `3b749e2`_)

* Remove deprecated server-mode (`#1840`_, `266471b`_)

* Remove not needed anymore requests-ftp (`#1085`_, `32b26dc`_)

* Remove object inheritance (`#881`_, `6e3277a`_)

* Remove unused code, templates and description.md (`#544`_, `cd3b08a`_)

* Removed py27 compatibility code (`a3c8e2b`_)

* Rename airbus tests to sobloo (`#195`_, `78a18ae`_)

* Replace deprecated methods and fix warnings (`#2032`_, `e84f17b`_)

* Replace fiona by pyshp (`1a9d488`_)

* Search all and crunch for _search_by_id (`#1099`_, `aba8f47`_)

* Some search methods moved to base plugin (`#878`_, `177d771`_)

* STAC API 1.0.0-beta.3 to 1.0.0-rc.3 (`#697`_, `9bbad5b`_)

* STAC server install in dockerfile (`#700`_, `1fb0807`_)

* TokenAuth credentials check (`#1141`_, `dda2150`_)

* Type hints fixes (`#1253`_, `1c91533`_)

* Type hints fixes (`#983`_, `0f094d5`_)

* Type hints fixes and mypy in tox (`#1269`_, `6055d7b`_)

* Typing fixes following mypy 1.14.0 (`#1458`_, `7a51598`_)

* Typing fixes following mypy 1.16.0 (`#1673`_, `ece52c0`_)

* Update ext product types list (`#690`_, `36870f9`_)

* Updated STAC extensions schemas versions (`#2017`_, `5bc3f68`_)

* Use wkt format for geometry in providers config (`#899`_, `f323366`_)

* Use zipstream-ng instead of stream-zip (`#1805`_, `182cdc0`_)

* Utils methods (`c38ef08`_)

* **collections**: Add processor for Sentinel and MAJA collections (`#1999`_, `f9a51f0`_)

* **collections**: CLMS and MetOp updates (`#1906`_, `9ebb872`_)

* **config/productTypes**: Ignore unindexed fields (`#996`_, `8bffd13`_)

* **core**: Authentication for get_quicklook (`#1608`_, `40915e0`_)

* **core**: Disable search pagination when less items got than expected (`#1920`_, `dfa18e7`_)

* **core**: Drivers from eodag-cube to core (`#1488`_, `59bf497`_)

* **core**: Git lfs and constraints update for DT datasets (`#1263`_, `073a910`_)

* **core**: Register downloader using manager from search to EOProduct (`#1699`_, `fd0c149`_)

* **core**: Remove deprecatred legacy driver and get_data doc (`#1891`_, `2500af7`_)

* **core**: Rename some parameters and methods to snake_case (`#1271`_, `3e5834f`_)

* **core**: Replace pkg_resources.resource_filename and version using importlib (`#1540`_,
  `c9be6ab`_)

* **core**: Shorter fetched product types logs (`#1379`_, `4e7645e`_)

* **core**: Use collection alias in EOProduct (`#1968`_, `b242061`_)

* **core**: Use importlib.metadata instead of the deprecated pkg_resources (`#1631`_, `3675690`_)

* **core**: Whole world as default product geometry and shapely stubs (`#1915`_, `99df712`_)

* **core**: Whoosh removal (`#1741`_, `31f3c8a`_)

* **docs**: Sphinx-autodoc-typehints usage (`#1066`_, `c54f68b`_)

* **ecmwf**: Simplify ECMWFSearch configuration (`#1433`_, `df3c233`_)

* **plugins**: Dedt_lumi not-available data error message (`#1770`_, `bf8cbe1`_)

* **plugins**: Deprecate CreodiasS3Download (`#1884`_, `5f6966b`_)

* **plugins**: Move aws authentication methods to AwsAuth plugin (`#1769`_, `1c072f8`_)

* **plugins**: Optional base_uri (`#1230`_, `5a72caa`_)

* **plugins**: Remove deprecated CreodiasS3Download (`#1886`_, `ea0a817`_)

* **plugins**: Rename PostJsonSearchWithStacQueryables to WekeoSearch (`#1842`_, `4bfbd6d`_)

* **product-types**: S1C and S2C as available platformSerialIdentifier (`#1850`_, `7c532f4`_)

* **provider**: New cds api (`#1284`_, `948b82b`_)

* **providers**: Next_page_token_key added to confs (`#1921`_, `2bb99ba`_)

* **providers**: Queryables form_url for dedt_lumi and dedt_mn5 (`#2018`_, `42f77a3`_)

* **providers**: Use hda v2 endpoint in dedl (`#2041`_, `5a72707`_)

* **providers**: Use s3 alternate assets in usgs_satapi_aws (`#1851`_, `27b1ab2`_)

* **server**: Get STAC collection by id (`#867`_, `f4eec1f`_)

* **server**: Logs format (`#1238`_, `c8733ce`_)

Testing
-------

* ``OIDCAuthorizationCodeFlowAuth`` plugin (`#1135`_, `919f46d`_)

* Add more tests to improve coverage (`#1791`_, `f7519f8`_)

* Add test for automatic deletion of downloaded product zip after extraction (`#358`_, `3963758`_)

* Add test_stac_utils, improve coverage of eodag.rest.utils (`#417`_, `51a489a`_)

* Add tests for download_all callback (`#121`_, `5400db4`_)

* Add tests for the callbacks of the methods download and download_all (`#121`_, `6ca2b90`_)

* Add utilities to EODagTestCase and refactor TestEOProduct (`5400db4`_)

* Add utilities to EODagTestCase and refactor TestEOProduct (`6ca2b90`_)

* Add windows support (`#192`_, `af9afc8`_)

* Advanced stac server tests (`#708`_, `919dd3c`_)

* All product_types list instead of random (`#1003`_, `c159fd0`_)

* Cli verbose level fix in tests (`#401`_, `d9f16f4`_)

* Cli version (`#525`_, `df0c9b5`_)

* Click 7.0 vs 7.1 compatibility (`14500e9`_)

* Creodias and onda in end-to-end tests (`0c8d6c8`_)

* Download plugins (`#494`_, `07abe78`_)

* E2e test minor changes (`766faaa`_)

* E2e tests for offline peps & aws_eos (`4e1923b`_)

* End-to-end and core tests updates (`#646`_, `7f1f490`_)

* End-to-end dates update (`2ceef7c`_)

* End-to-end dates update (`5ac08ec`_)

* End-to-end tests fixes (`#1997`_, `2a238ed`_)

* End-to-end tests update (`#523`_, `58335e7`_)

* EODataAccessGateway handling and unittest usage (`#2042`_, `c630b30`_)

* FieldInfo repr with pydantic >= 2.7.0 (`#1097`_, `c99e3be`_)

* Fix after automatic deletion of the archives was added (`#358`_, `3963758`_)

* Fix CdsApi test following provider api update (`#679`_, `34c41ac`_)

* Fix end-to-end tests (`#1236`_, `90aa258`_)

* Fix env var loading in test_http_server (`#962`_, `5ebb90b`_)

* Fixed test for ecmwf dates (`#1588`_, `b6ca196`_)

* Fixes root link in stac static resources (`#219`_, `c83d889`_)

* Force deps upgrade on install in tox (`#1368`_, `e20c12b`_)

* Headers as requests CaseInsensitiveDict (`#2054`_, `708fd41`_)

* Hydroweb_next public product-type usage (`#926`_, `09a9b79`_)

* Improve cli test coverage (`#539`_, `d2f4b61`_)

* Improve core test coverage (`#549`_, `fc15d0f`_)

* Less restrictive comparison in download retry tests (`#517`_, `e4d8775`_)

* Metadata mapping conversions (`#367`_, `18d93f6`_)

* Meteoblue end-to-end test (`#604`_, `6fee322`_)

* More AwsDownload tests (`#609`_, `eec4adf`_)

* More stac features (`dacce19`_)

* Mundi in end-to-end tests (`1a8ac9c`_)

* Optimizes and fixes tests (`#631`_, `6b7ca26`_)

* OrderDownload and orderDownloadStatus (`#604`_, `6fee322`_)

* Prevent failing actions for windows py3.9.8 (`#361`_, `2b33dfc`_)

* Product_type fixes (`e6e6931`_)

* Progress_callback unit tests (`#285`_, `3945ddd`_)

* Read_local_json raises STACOpenerError (`#574`_, `73e95cb`_)

* Renamed old formatted record file (`#1403`_, `279dad6`_)

* Reset logger after tests (`#936`_, `c7d09b5`_)

* Rewritten test_eoproduct_register_downloader_resolve_ignored (`#666`_, `c6c9d06`_)

* Safe build tests (`#218`_, `fec965f`_)

* Sara provider end-to-end test (`#602`_, `d238c08`_)

* Search by geometry (`b69375c`_)

* Stac features (`a47806e`_)

* Stac static catalog (`c925f7a`_)

* System agnostic fixes (`#934`_, `1631c88`_)

* Tests added to common methods (`86c7977`_)

* Update click>=8.2.0 exit status code (`#1650`_, `51a5f36`_)

* Update dates for sobloo end-to-end test (`#366`_, `2838ac4`_)

* Update SUPPORTED_PRODUCT_TYPES (`0f70077`_)

* Update test_end_to_end_complete_peps (`#872`_, `32c2654`_)

* Update test_search_by_tile (`#925`_, `4d2b7e3`_)

* Use responses instead of custom download mock (`#2062`_, `8af8318`_)

* Use tempdir for serialization, fixes #100 (`d6f3f48`_)

* Use tmp eodag conf dir (`#415`_, `db5bd23`_)

.. _#1001: https://github.com/vprivat-ads/eodag/pull/1001
.. _#1002: https://github.com/vprivat-ads/eodag/pull/1002
.. _#1003: https://github.com/vprivat-ads/eodag/pull/1003
.. _#1005: https://github.com/vprivat-ads/eodag/pull/1005
.. _#1008: https://github.com/vprivat-ads/eodag/pull/1008
.. _#1009: https://github.com/vprivat-ads/eodag/pull/1009
.. _#1010: https://github.com/vprivat-ads/eodag/pull/1010
.. _#1011: https://github.com/vprivat-ads/eodag/pull/1011
.. _#1013: https://github.com/vprivat-ads/eodag/pull/1013
.. _#1014: https://github.com/vprivat-ads/eodag/pull/1014
.. _#1016: https://github.com/vprivat-ads/eodag/pull/1016
.. _#1017: https://github.com/vprivat-ads/eodag/pull/1017
.. _#1019: https://github.com/vprivat-ads/eodag/pull/1019
.. _#1020: https://github.com/vprivat-ads/eodag/pull/1020
.. _#1021: https://github.com/vprivat-ads/eodag/pull/1021
.. _#1022: https://github.com/vprivat-ads/eodag/pull/1022
.. _#1023: https://github.com/vprivat-ads/eodag/pull/1023
.. _#1024: https://github.com/vprivat-ads/eodag/pull/1024
.. _#1025: https://github.com/vprivat-ads/eodag/pull/1025
.. _#1027: https://github.com/vprivat-ads/eodag/pull/1027
.. _#1028: https://github.com/vprivat-ads/eodag/pull/1028
.. _#1029: https://github.com/vprivat-ads/eodag/pull/1029
.. _#1033: https://github.com/vprivat-ads/eodag/pull/1033
.. _#1034: https://github.com/vprivat-ads/eodag/pull/1034
.. _#1045: https://github.com/vprivat-ads/eodag/pull/1045
.. _#1046: https://github.com/vprivat-ads/eodag/pull/1046
.. _#1048: https://github.com/vprivat-ads/eodag/pull/1048
.. _#1050: https://github.com/vprivat-ads/eodag/pull/1050
.. _#1051: https://github.com/vprivat-ads/eodag/pull/1051
.. _#1052: https://github.com/vprivat-ads/eodag/pull/1052
.. _#1053: https://github.com/vprivat-ads/eodag/pull/1053
.. _#1057: https://github.com/vprivat-ads/eodag/pull/1057
.. _#1059: https://github.com/vprivat-ads/eodag/pull/1059
.. _#1060: https://github.com/vprivat-ads/eodag/pull/1060
.. _#1062: https://github.com/vprivat-ads/eodag/pull/1062
.. _#1063: https://github.com/vprivat-ads/eodag/pull/1063
.. _#1066: https://github.com/vprivat-ads/eodag/pull/1066
.. _#1070: https://github.com/vprivat-ads/eodag/pull/1070
.. _#1071: https://github.com/vprivat-ads/eodag/pull/1071
.. _#1072: https://github.com/vprivat-ads/eodag/pull/1072
.. _#1073: https://github.com/vprivat-ads/eodag/pull/1073
.. _#1077: https://github.com/vprivat-ads/eodag/pull/1077
.. _#1078: https://github.com/vprivat-ads/eodag/pull/1078
.. _#1079: https://github.com/vprivat-ads/eodag/pull/1079
.. _#1081: https://github.com/vprivat-ads/eodag/pull/1081
.. _#1082: https://github.com/vprivat-ads/eodag/pull/1082
.. _#1083: https://github.com/vprivat-ads/eodag/pull/1083
.. _#1085: https://github.com/vprivat-ads/eodag/pull/1085
.. _#1086: https://github.com/vprivat-ads/eodag/pull/1086
.. _#1087: https://github.com/vprivat-ads/eodag/pull/1087
.. _#1090: https://github.com/vprivat-ads/eodag/pull/1090
.. _#1091: https://github.com/vprivat-ads/eodag/pull/1091
.. _#1093: https://github.com/vprivat-ads/eodag/pull/1093
.. _#1095: https://github.com/vprivat-ads/eodag/pull/1095
.. _#1097: https://github.com/vprivat-ads/eodag/pull/1097
.. _#1098: https://github.com/vprivat-ads/eodag/pull/1098
.. _#1099: https://github.com/vprivat-ads/eodag/pull/1099
.. _#1100: https://github.com/vprivat-ads/eodag/pull/1100
.. _#1101: https://github.com/vprivat-ads/eodag/pull/1101
.. _#1102: https://github.com/vprivat-ads/eodag/pull/1102
.. _#1103: https://github.com/vprivat-ads/eodag/pull/1103
.. _#1104: https://github.com/vprivat-ads/eodag/pull/1104
.. _#1105: https://github.com/vprivat-ads/eodag/pull/1105
.. _#1106: https://github.com/vprivat-ads/eodag/pull/1106
.. _#1107: https://github.com/vprivat-ads/eodag/pull/1107
.. _#1108: https://github.com/vprivat-ads/eodag/pull/1108
.. _#1109: https://github.com/vprivat-ads/eodag/pull/1109
.. _#1110: https://github.com/vprivat-ads/eodag/pull/1110
.. _#1111: https://github.com/vprivat-ads/eodag/pull/1111
.. _#1112: https://github.com/vprivat-ads/eodag/pull/1112
.. _#1113: https://github.com/vprivat-ads/eodag/pull/1113
.. _#1114: https://github.com/vprivat-ads/eodag/pull/1114
.. _#1115: https://github.com/vprivat-ads/eodag/pull/1115
.. _#1117: https://github.com/vprivat-ads/eodag/pull/1117
.. _#1118: https://github.com/vprivat-ads/eodag/pull/1118
.. _#1119: https://github.com/vprivat-ads/eodag/pull/1119
.. _#1120: https://github.com/vprivat-ads/eodag/pull/1120
.. _#1121: https://github.com/vprivat-ads/eodag/pull/1121
.. _#1122: https://github.com/vprivat-ads/eodag/pull/1122
.. _#1124: https://github.com/vprivat-ads/eodag/pull/1124
.. _#1126: https://github.com/vprivat-ads/eodag/pull/1126
.. _#1127: https://github.com/vprivat-ads/eodag/pull/1127
.. _#1131: https://github.com/vprivat-ads/eodag/pull/1131
.. _#1132: https://github.com/vprivat-ads/eodag/pull/1132
.. _#1135: https://github.com/vprivat-ads/eodag/pull/1135
.. _#1136: https://github.com/vprivat-ads/eodag/pull/1136
.. _#1137: https://github.com/vprivat-ads/eodag/pull/1137
.. _#1138: https://github.com/vprivat-ads/eodag/pull/1138
.. _#1139: https://github.com/vprivat-ads/eodag/pull/1139
.. _#1140: https://github.com/vprivat-ads/eodag/pull/1140
.. _#1141: https://github.com/vprivat-ads/eodag/pull/1141
.. _#1142: https://github.com/vprivat-ads/eodag/pull/1142
.. _#1143: https://github.com/vprivat-ads/eodag/pull/1143
.. _#1144: https://github.com/vprivat-ads/eodag/pull/1144
.. _#1145: https://github.com/vprivat-ads/eodag/pull/1145
.. _#1146: https://github.com/vprivat-ads/eodag/pull/1146
.. _#1149: https://github.com/vprivat-ads/eodag/pull/1149
.. _#1150: https://github.com/vprivat-ads/eodag/pull/1150
.. _#1151: https://github.com/vprivat-ads/eodag/pull/1151
.. _#1152: https://github.com/vprivat-ads/eodag/pull/1152
.. _#1153: https://github.com/vprivat-ads/eodag/pull/1153
.. _#1155: https://github.com/vprivat-ads/eodag/pull/1155
.. _#1157: https://github.com/vprivat-ads/eodag/pull/1157
.. _#1158: https://github.com/vprivat-ads/eodag/pull/1158
.. _#1160: https://github.com/vprivat-ads/eodag/pull/1160
.. _#1163: https://github.com/vprivat-ads/eodag/pull/1163
.. _#1164: https://github.com/vprivat-ads/eodag/pull/1164
.. _#1165: https://github.com/vprivat-ads/eodag/pull/1165
.. _#1171: https://github.com/vprivat-ads/eodag/pull/1171
.. _#1174: https://github.com/vprivat-ads/eodag/pull/1174
.. _#1176: https://github.com/vprivat-ads/eodag/pull/1176
.. _#1178: https://github.com/vprivat-ads/eodag/pull/1178
.. _#1180: https://github.com/vprivat-ads/eodag/pull/1180
.. _#1182: https://github.com/vprivat-ads/eodag/pull/1182
.. _#1185: https://github.com/vprivat-ads/eodag/pull/1185
.. _#1186: https://github.com/vprivat-ads/eodag/pull/1186
.. _#1187: https://github.com/vprivat-ads/eodag/pull/1187
.. _#1189: https://github.com/vprivat-ads/eodag/pull/1189
.. _#1190: https://github.com/vprivat-ads/eodag/pull/1190
.. _#1191: https://github.com/vprivat-ads/eodag/pull/1191
.. _#1192: https://github.com/vprivat-ads/eodag/pull/1192
.. _#1193: https://github.com/vprivat-ads/eodag/pull/1193
.. _#1194: https://github.com/vprivat-ads/eodag/pull/1194
.. _#1196: https://github.com/vprivat-ads/eodag/pull/1196
.. _#1197: https://github.com/vprivat-ads/eodag/pull/1197
.. _#1199: https://github.com/vprivat-ads/eodag/pull/1199
.. _#1200: https://github.com/vprivat-ads/eodag/pull/1200
.. _#1202: https://github.com/vprivat-ads/eodag/pull/1202
.. _#1203: https://github.com/vprivat-ads/eodag/pull/1203
.. _#1204: https://github.com/vprivat-ads/eodag/pull/1204
.. _#1205: https://github.com/vprivat-ads/eodag/pull/1205
.. _#1206: https://github.com/vprivat-ads/eodag/pull/1206
.. _#1207: https://github.com/vprivat-ads/eodag/pull/1207
.. _#1208: https://github.com/vprivat-ads/eodag/pull/1208
.. _#1210: https://github.com/vprivat-ads/eodag/pull/1210
.. _#1212: https://github.com/vprivat-ads/eodag/pull/1212
.. _#1213: https://github.com/vprivat-ads/eodag/pull/1213
.. _#1214: https://github.com/vprivat-ads/eodag/pull/1214
.. _#1215: https://github.com/vprivat-ads/eodag/pull/1215
.. _#1219: https://github.com/vprivat-ads/eodag/pull/1219
.. _#121: https://github.com/vprivat-ads/eodag/pull/121
.. _#1220: https://github.com/vprivat-ads/eodag/pull/1220
.. _#1221: https://github.com/vprivat-ads/eodag/pull/1221
.. _#1222: https://github.com/vprivat-ads/eodag/pull/1222
.. _#1223: https://github.com/vprivat-ads/eodag/pull/1223
.. _#1224: https://github.com/vprivat-ads/eodag/pull/1224
.. _#1225: https://github.com/vprivat-ads/eodag/pull/1225
.. _#1227: https://github.com/vprivat-ads/eodag/pull/1227
.. _#1229: https://github.com/vprivat-ads/eodag/pull/1229
.. _#1230: https://github.com/vprivat-ads/eodag/pull/1230
.. _#1232: https://github.com/vprivat-ads/eodag/pull/1232
.. _#1234: https://github.com/vprivat-ads/eodag/pull/1234
.. _#1236: https://github.com/vprivat-ads/eodag/pull/1236
.. _#1237: https://github.com/vprivat-ads/eodag/pull/1237
.. _#1238: https://github.com/vprivat-ads/eodag/pull/1238
.. _#1239: https://github.com/vprivat-ads/eodag/pull/1239
.. _#1240: https://github.com/vprivat-ads/eodag/pull/1240
.. _#1241: https://github.com/vprivat-ads/eodag/pull/1241
.. _#1242: https://github.com/vprivat-ads/eodag/pull/1242
.. _#1243: https://github.com/vprivat-ads/eodag/pull/1243
.. _#1244: https://github.com/vprivat-ads/eodag/pull/1244
.. _#1246: https://github.com/vprivat-ads/eodag/pull/1246
.. _#1249: https://github.com/vprivat-ads/eodag/pull/1249
.. _#1250: https://github.com/vprivat-ads/eodag/pull/1250
.. _#1251: https://github.com/vprivat-ads/eodag/pull/1251
.. _#1253: https://github.com/vprivat-ads/eodag/pull/1253
.. _#1254: https://github.com/vprivat-ads/eodag/pull/1254
.. _#1255: https://github.com/vprivat-ads/eodag/pull/1255
.. _#1256: https://github.com/vprivat-ads/eodag/pull/1256
.. _#1257: https://github.com/vprivat-ads/eodag/pull/1257
.. _#1258: https://github.com/vprivat-ads/eodag/pull/1258
.. _#1259: https://github.com/vprivat-ads/eodag/pull/1259
.. _#1260: https://github.com/vprivat-ads/eodag/pull/1260
.. _#1262: https://github.com/vprivat-ads/eodag/pull/1262
.. _#1263: https://github.com/vprivat-ads/eodag/pull/1263
.. _#1264: https://github.com/vprivat-ads/eodag/pull/1264
.. _#1266: https://github.com/vprivat-ads/eodag/pull/1266
.. _#1267: https://github.com/vprivat-ads/eodag/pull/1267
.. _#1269: https://github.com/vprivat-ads/eodag/pull/1269
.. _#1271: https://github.com/vprivat-ads/eodag/pull/1271
.. _#1276: https://github.com/vprivat-ads/eodag/pull/1276
.. _#1277: https://github.com/vprivat-ads/eodag/pull/1277
.. _#1278: https://github.com/vprivat-ads/eodag/pull/1278
.. _#1279: https://github.com/vprivat-ads/eodag/pull/1279
.. _#1280: https://github.com/vprivat-ads/eodag/pull/1280
.. _#1281: https://github.com/vprivat-ads/eodag/pull/1281
.. _#1282: https://github.com/vprivat-ads/eodag/pull/1282
.. _#1284: https://github.com/vprivat-ads/eodag/pull/1284
.. _#1288: https://github.com/vprivat-ads/eodag/pull/1288
.. _#1289: https://github.com/vprivat-ads/eodag/pull/1289
.. _#1290: https://github.com/vprivat-ads/eodag/pull/1290
.. _#1292: https://github.com/vprivat-ads/eodag/pull/1292
.. _#1294: https://github.com/vprivat-ads/eodag/pull/1294
.. _#1295: https://github.com/vprivat-ads/eodag/pull/1295
.. _#1296: https://github.com/vprivat-ads/eodag/pull/1296
.. _#1297: https://github.com/vprivat-ads/eodag/pull/1297
.. _#1298: https://github.com/vprivat-ads/eodag/pull/1298
.. _#1300: https://github.com/vprivat-ads/eodag/pull/1300
.. _#1301: https://github.com/vprivat-ads/eodag/pull/1301
.. _#1303: https://github.com/vprivat-ads/eodag/pull/1303
.. _#1304: https://github.com/vprivat-ads/eodag/pull/1304
.. _#1306: https://github.com/vprivat-ads/eodag/pull/1306
.. _#1308: https://github.com/vprivat-ads/eodag/pull/1308
.. _#1310: https://github.com/vprivat-ads/eodag/pull/1310
.. _#1313: https://github.com/vprivat-ads/eodag/pull/1313
.. _#1314: https://github.com/vprivat-ads/eodag/pull/1314
.. _#1315: https://github.com/vprivat-ads/eodag/pull/1315
.. _#1316: https://github.com/vprivat-ads/eodag/pull/1316
.. _#1318: https://github.com/vprivat-ads/eodag/pull/1318
.. _#1322: https://github.com/vprivat-ads/eodag/pull/1322
.. _#1323: https://github.com/vprivat-ads/eodag/pull/1323
.. _#1326: https://github.com/vprivat-ads/eodag/pull/1326
.. _#1327: https://github.com/vprivat-ads/eodag/pull/1327
.. _#1329: https://github.com/vprivat-ads/eodag/pull/1329
.. _#1331: https://github.com/vprivat-ads/eodag/pull/1331
.. _#1332: https://github.com/vprivat-ads/eodag/pull/1332
.. _#1333: https://github.com/vprivat-ads/eodag/pull/1333
.. _#1334: https://github.com/vprivat-ads/eodag/pull/1334
.. _#1335: https://github.com/vprivat-ads/eodag/pull/1335
.. _#1336: https://github.com/vprivat-ads/eodag/pull/1336
.. _#1338: https://github.com/vprivat-ads/eodag/pull/1338
.. _#1340: https://github.com/vprivat-ads/eodag/pull/1340
.. _#1341: https://github.com/vprivat-ads/eodag/pull/1341
.. _#1342: https://github.com/vprivat-ads/eodag/pull/1342
.. _#1343: https://github.com/vprivat-ads/eodag/pull/1343
.. _#1344: https://github.com/vprivat-ads/eodag/pull/1344
.. _#1346: https://github.com/vprivat-ads/eodag/pull/1346
.. _#1347: https://github.com/vprivat-ads/eodag/pull/1347
.. _#1348: https://github.com/vprivat-ads/eodag/pull/1348
.. _#1351: https://github.com/vprivat-ads/eodag/pull/1351
.. _#1353: https://github.com/vprivat-ads/eodag/pull/1353
.. _#1356: https://github.com/vprivat-ads/eodag/pull/1356
.. _#1357: https://github.com/vprivat-ads/eodag/pull/1357
.. _#1358: https://github.com/vprivat-ads/eodag/pull/1358
.. _#1359: https://github.com/vprivat-ads/eodag/pull/1359
.. _#1360: https://github.com/vprivat-ads/eodag/pull/1360
.. _#1362: https://github.com/vprivat-ads/eodag/pull/1362
.. _#1363: https://github.com/vprivat-ads/eodag/pull/1363
.. _#1364: https://github.com/vprivat-ads/eodag/pull/1364
.. _#1366: https://github.com/vprivat-ads/eodag/pull/1366
.. _#1367: https://github.com/vprivat-ads/eodag/pull/1367
.. _#1368: https://github.com/vprivat-ads/eodag/pull/1368
.. _#1369: https://github.com/vprivat-ads/eodag/pull/1369
.. _#1370: https://github.com/vprivat-ads/eodag/pull/1370
.. _#1373: https://github.com/vprivat-ads/eodag/pull/1373
.. _#1374: https://github.com/vprivat-ads/eodag/pull/1374
.. _#1375: https://github.com/vprivat-ads/eodag/pull/1375
.. _#1377: https://github.com/vprivat-ads/eodag/pull/1377
.. _#1378: https://github.com/vprivat-ads/eodag/pull/1378
.. _#1379: https://github.com/vprivat-ads/eodag/pull/1379
.. _#1381: https://github.com/vprivat-ads/eodag/pull/1381
.. _#1383: https://github.com/vprivat-ads/eodag/pull/1383
.. _#1384: https://github.com/vprivat-ads/eodag/pull/1384
.. _#1387: https://github.com/vprivat-ads/eodag/pull/1387
.. _#1389: https://github.com/vprivat-ads/eodag/pull/1389
.. _#1390: https://github.com/vprivat-ads/eodag/pull/1390
.. _#1391: https://github.com/vprivat-ads/eodag/pull/1391
.. _#1392: https://github.com/vprivat-ads/eodag/pull/1392
.. _#1396: https://github.com/vprivat-ads/eodag/pull/1396
.. _#1397: https://github.com/vprivat-ads/eodag/pull/1397
.. _#1400: https://github.com/vprivat-ads/eodag/pull/1400
.. _#1401: https://github.com/vprivat-ads/eodag/pull/1401
.. _#1403: https://github.com/vprivat-ads/eodag/pull/1403
.. _#1404: https://github.com/vprivat-ads/eodag/pull/1404
.. _#1406: https://github.com/vprivat-ads/eodag/pull/1406
.. _#1408: https://github.com/vprivat-ads/eodag/pull/1408
.. _#1410: https://github.com/vprivat-ads/eodag/pull/1410
.. _#1411: https://github.com/vprivat-ads/eodag/pull/1411
.. _#1415: https://github.com/vprivat-ads/eodag/pull/1415
.. _#1416: https://github.com/vprivat-ads/eodag/pull/1416
.. _#1418: https://github.com/vprivat-ads/eodag/pull/1418
.. _#1419: https://github.com/vprivat-ads/eodag/pull/1419
.. _#1424: https://github.com/vprivat-ads/eodag/pull/1424
.. _#1425: https://github.com/vprivat-ads/eodag/pull/1425
.. _#1427: https://github.com/vprivat-ads/eodag/pull/1427
.. _#1428: https://github.com/vprivat-ads/eodag/pull/1428
.. _#1429: https://github.com/vprivat-ads/eodag/pull/1429
.. _#1430: https://github.com/vprivat-ads/eodag/pull/1430
.. _#1431: https://github.com/vprivat-ads/eodag/pull/1431
.. _#1433: https://github.com/vprivat-ads/eodag/pull/1433
.. _#1434: https://github.com/vprivat-ads/eodag/pull/1434
.. _#1436: https://github.com/vprivat-ads/eodag/pull/1436
.. _#1437: https://github.com/vprivat-ads/eodag/pull/1437
.. _#1440: https://github.com/vprivat-ads/eodag/pull/1440
.. _#1441: https://github.com/vprivat-ads/eodag/pull/1441
.. _#1445: https://github.com/vprivat-ads/eodag/pull/1445
.. _#1447: https://github.com/vprivat-ads/eodag/pull/1447
.. _#1448: https://github.com/vprivat-ads/eodag/pull/1448
.. _#1451: https://github.com/vprivat-ads/eodag/pull/1451
.. _#1453: https://github.com/vprivat-ads/eodag/pull/1453
.. _#1455: https://github.com/vprivat-ads/eodag/pull/1455
.. _#1457: https://github.com/vprivat-ads/eodag/pull/1457
.. _#1458: https://github.com/vprivat-ads/eodag/pull/1458
.. _#1459: https://github.com/vprivat-ads/eodag/pull/1459
.. _#1460: https://github.com/vprivat-ads/eodag/pull/1460
.. _#1462: https://github.com/vprivat-ads/eodag/pull/1462
.. _#1464: https://github.com/vprivat-ads/eodag/pull/1464
.. _#1465: https://github.com/vprivat-ads/eodag/pull/1465
.. _#1466: https://github.com/vprivat-ads/eodag/pull/1466
.. _#1467: https://github.com/vprivat-ads/eodag/pull/1467
.. _#1468: https://github.com/vprivat-ads/eodag/pull/1468
.. _#1471: https://github.com/vprivat-ads/eodag/pull/1471
.. _#1472: https://github.com/vprivat-ads/eodag/pull/1472
.. _#1473: https://github.com/vprivat-ads/eodag/pull/1473
.. _#1475: https://github.com/vprivat-ads/eodag/pull/1475
.. _#1477: https://github.com/vprivat-ads/eodag/pull/1477
.. _#1478: https://github.com/vprivat-ads/eodag/pull/1478
.. _#1479: https://github.com/vprivat-ads/eodag/pull/1479
.. _#1480: https://github.com/vprivat-ads/eodag/pull/1480
.. _#1483: https://github.com/vprivat-ads/eodag/pull/1483
.. _#1484: https://github.com/vprivat-ads/eodag/pull/1484
.. _#1486: https://github.com/vprivat-ads/eodag/pull/1486
.. _#1487: https://github.com/vprivat-ads/eodag/pull/1487
.. _#1488: https://github.com/vprivat-ads/eodag/pull/1488
.. _#1490: https://github.com/vprivat-ads/eodag/pull/1490
.. _#1492: https://github.com/vprivat-ads/eodag/pull/1492
.. _#1493: https://github.com/vprivat-ads/eodag/pull/1493
.. _#1494: https://github.com/vprivat-ads/eodag/pull/1494
.. _#1498: https://github.com/vprivat-ads/eodag/pull/1498
.. _#1499: https://github.com/vprivat-ads/eodag/pull/1499
.. _#1500: https://github.com/vprivat-ads/eodag/pull/1500
.. _#1502: https://github.com/vprivat-ads/eodag/pull/1502
.. _#1503: https://github.com/vprivat-ads/eodag/pull/1503
.. _#1504: https://github.com/vprivat-ads/eodag/pull/1504
.. _#1505: https://github.com/vprivat-ads/eodag/pull/1505
.. _#1506: https://github.com/vprivat-ads/eodag/pull/1506
.. _#1507: https://github.com/vprivat-ads/eodag/pull/1507
.. _#1508: https://github.com/vprivat-ads/eodag/pull/1508
.. _#1509: https://github.com/vprivat-ads/eodag/pull/1509
.. _#1510: https://github.com/vprivat-ads/eodag/pull/1510
.. _#1511: https://github.com/vprivat-ads/eodag/pull/1511
.. _#1513: https://github.com/vprivat-ads/eodag/pull/1513
.. _#1514: https://github.com/vprivat-ads/eodag/pull/1514
.. _#1515: https://github.com/vprivat-ads/eodag/pull/1515
.. _#1516: https://github.com/vprivat-ads/eodag/pull/1516
.. _#1519: https://github.com/vprivat-ads/eodag/pull/1519
.. _#1521: https://github.com/vprivat-ads/eodag/pull/1521
.. _#1524: https://github.com/vprivat-ads/eodag/pull/1524
.. _#1525: https://github.com/vprivat-ads/eodag/pull/1525
.. _#1532: https://github.com/vprivat-ads/eodag/pull/1532
.. _#1534: https://github.com/vprivat-ads/eodag/pull/1534
.. _#1536: https://github.com/vprivat-ads/eodag/pull/1536
.. _#1539: https://github.com/vprivat-ads/eodag/pull/1539
.. _#1540: https://github.com/vprivat-ads/eodag/pull/1540
.. _#1541: https://github.com/vprivat-ads/eodag/pull/1541
.. _#1547: https://github.com/vprivat-ads/eodag/pull/1547
.. _#1548: https://github.com/vprivat-ads/eodag/pull/1548
.. _#1549: https://github.com/vprivat-ads/eodag/pull/1549
.. _#1550: https://github.com/vprivat-ads/eodag/pull/1550
.. _#1551: https://github.com/vprivat-ads/eodag/pull/1551
.. _#1552: https://github.com/vprivat-ads/eodag/pull/1552
.. _#1553: https://github.com/vprivat-ads/eodag/pull/1553
.. _#1555: https://github.com/vprivat-ads/eodag/pull/1555
.. _#1557: https://github.com/vprivat-ads/eodag/pull/1557
.. _#1559: https://github.com/vprivat-ads/eodag/pull/1559
.. _#1561: https://github.com/vprivat-ads/eodag/pull/1561
.. _#1562: https://github.com/vprivat-ads/eodag/pull/1562
.. _#1564: https://github.com/vprivat-ads/eodag/pull/1564
.. _#1565: https://github.com/vprivat-ads/eodag/pull/1565
.. _#1566: https://github.com/vprivat-ads/eodag/pull/1566
.. _#1567: https://github.com/vprivat-ads/eodag/pull/1567
.. _#1569: https://github.com/vprivat-ads/eodag/pull/1569
.. _#1570: https://github.com/vprivat-ads/eodag/pull/1570
.. _#1571: https://github.com/vprivat-ads/eodag/pull/1571
.. _#1572: https://github.com/vprivat-ads/eodag/pull/1572
.. _#1573: https://github.com/vprivat-ads/eodag/pull/1573
.. _#1575: https://github.com/vprivat-ads/eodag/pull/1575
.. _#1576: https://github.com/vprivat-ads/eodag/pull/1576
.. _#1580: https://github.com/vprivat-ads/eodag/pull/1580
.. _#1581: https://github.com/vprivat-ads/eodag/pull/1581
.. _#1582: https://github.com/vprivat-ads/eodag/pull/1582
.. _#1584: https://github.com/vprivat-ads/eodag/pull/1584
.. _#1585: https://github.com/vprivat-ads/eodag/pull/1585
.. _#1588: https://github.com/vprivat-ads/eodag/pull/1588
.. _#1590: https://github.com/vprivat-ads/eodag/pull/1590
.. _#1592: https://github.com/vprivat-ads/eodag/pull/1592
.. _#1597: https://github.com/vprivat-ads/eodag/pull/1597
.. _#1599: https://github.com/vprivat-ads/eodag/pull/1599
.. _#159: https://github.com/vprivat-ads/eodag/pull/159
.. _#1601: https://github.com/vprivat-ads/eodag/pull/1601
.. _#1603: https://github.com/vprivat-ads/eodag/pull/1603
.. _#1607: https://github.com/vprivat-ads/eodag/pull/1607
.. _#1608: https://github.com/vprivat-ads/eodag/pull/1608
.. _#160: https://github.com/vprivat-ads/eodag/pull/160
.. _#1610: https://github.com/vprivat-ads/eodag/pull/1610
.. _#1613: https://github.com/vprivat-ads/eodag/pull/1613
.. _#1614: https://github.com/vprivat-ads/eodag/pull/1614
.. _#1620: https://github.com/vprivat-ads/eodag/pull/1620
.. _#1625: https://github.com/vprivat-ads/eodag/pull/1625
.. _#1627: https://github.com/vprivat-ads/eodag/pull/1627
.. _#1628: https://github.com/vprivat-ads/eodag/pull/1628
.. _#1629: https://github.com/vprivat-ads/eodag/pull/1629
.. _#1630: https://github.com/vprivat-ads/eodag/pull/1630
.. _#1631: https://github.com/vprivat-ads/eodag/pull/1631
.. _#1633: https://github.com/vprivat-ads/eodag/pull/1633
.. _#1634: https://github.com/vprivat-ads/eodag/pull/1634
.. _#1635: https://github.com/vprivat-ads/eodag/pull/1635
.. _#1638: https://github.com/vprivat-ads/eodag/pull/1638
.. _#1639: https://github.com/vprivat-ads/eodag/pull/1639
.. _#1641: https://github.com/vprivat-ads/eodag/pull/1641
.. _#1643: https://github.com/vprivat-ads/eodag/pull/1643
.. _#1646: https://github.com/vprivat-ads/eodag/pull/1646
.. _#1648: https://github.com/vprivat-ads/eodag/pull/1648
.. _#1649: https://github.com/vprivat-ads/eodag/pull/1649
.. _#1650: https://github.com/vprivat-ads/eodag/pull/1650
.. _#1651: https://github.com/vprivat-ads/eodag/pull/1651
.. _#1655: https://github.com/vprivat-ads/eodag/pull/1655
.. _#1656: https://github.com/vprivat-ads/eodag/pull/1656
.. _#1657: https://github.com/vprivat-ads/eodag/pull/1657
.. _#1660: https://github.com/vprivat-ads/eodag/pull/1660
.. _#1661: https://github.com/vprivat-ads/eodag/pull/1661
.. _#1662: https://github.com/vprivat-ads/eodag/pull/1662
.. _#1663: https://github.com/vprivat-ads/eodag/pull/1663
.. _#1665: https://github.com/vprivat-ads/eodag/pull/1665
.. _#1666: https://github.com/vprivat-ads/eodag/pull/1666
.. _#1667: https://github.com/vprivat-ads/eodag/pull/1667
.. _#1669: https://github.com/vprivat-ads/eodag/pull/1669
.. _#1670: https://github.com/vprivat-ads/eodag/pull/1670
.. _#1671: https://github.com/vprivat-ads/eodag/pull/1671
.. _#1672: https://github.com/vprivat-ads/eodag/pull/1672
.. _#1673: https://github.com/vprivat-ads/eodag/pull/1673
.. _#1674: https://github.com/vprivat-ads/eodag/pull/1674
.. _#1676: https://github.com/vprivat-ads/eodag/pull/1676
.. _#1677: https://github.com/vprivat-ads/eodag/pull/1677
.. _#1678: https://github.com/vprivat-ads/eodag/pull/1678
.. _#1681: https://github.com/vprivat-ads/eodag/pull/1681
.. _#1686: https://github.com/vprivat-ads/eodag/pull/1686
.. _#1687: https://github.com/vprivat-ads/eodag/pull/1687
.. _#1688: https://github.com/vprivat-ads/eodag/pull/1688
.. _#1690: https://github.com/vprivat-ads/eodag/pull/1690
.. _#1691: https://github.com/vprivat-ads/eodag/pull/1691
.. _#1692: https://github.com/vprivat-ads/eodag/pull/1692
.. _#1693: https://github.com/vprivat-ads/eodag/pull/1693
.. _#1694: https://github.com/vprivat-ads/eodag/pull/1694
.. _#1698: https://github.com/vprivat-ads/eodag/pull/1698
.. _#1699: https://github.com/vprivat-ads/eodag/pull/1699
.. _#1700: https://github.com/vprivat-ads/eodag/pull/1700
.. _#1702: https://github.com/vprivat-ads/eodag/pull/1702
.. _#1703: https://github.com/vprivat-ads/eodag/pull/1703
.. _#1705: https://github.com/vprivat-ads/eodag/pull/1705
.. _#1706: https://github.com/vprivat-ads/eodag/pull/1706
.. _#1707: https://github.com/vprivat-ads/eodag/pull/1707
.. _#1709: https://github.com/vprivat-ads/eodag/pull/1709
.. _#1710: https://github.com/vprivat-ads/eodag/pull/1710
.. _#1711: https://github.com/vprivat-ads/eodag/pull/1711
.. _#1712: https://github.com/vprivat-ads/eodag/pull/1712
.. _#1714: https://github.com/vprivat-ads/eodag/pull/1714
.. _#1716: https://github.com/vprivat-ads/eodag/pull/1716
.. _#1717: https://github.com/vprivat-ads/eodag/pull/1717
.. _#1728: https://github.com/vprivat-ads/eodag/pull/1728
.. _#1730: https://github.com/vprivat-ads/eodag/pull/1730
.. _#1731: https://github.com/vprivat-ads/eodag/pull/1731
.. _#1733: https://github.com/vprivat-ads/eodag/pull/1733
.. _#1734: https://github.com/vprivat-ads/eodag/pull/1734
.. _#1735: https://github.com/vprivat-ads/eodag/pull/1735
.. _#1736: https://github.com/vprivat-ads/eodag/pull/1736
.. _#1737: https://github.com/vprivat-ads/eodag/pull/1737
.. _#1738: https://github.com/vprivat-ads/eodag/pull/1738
.. _#173: https://github.com/vprivat-ads/eodag/pull/173
.. _#1740: https://github.com/vprivat-ads/eodag/pull/1740
.. _#1741: https://github.com/vprivat-ads/eodag/pull/1741
.. _#1742: https://github.com/vprivat-ads/eodag/pull/1742
.. _#1744: https://github.com/vprivat-ads/eodag/pull/1744
.. _#1745: https://github.com/vprivat-ads/eodag/pull/1745
.. _#1746: https://github.com/vprivat-ads/eodag/pull/1746
.. _#1758: https://github.com/vprivat-ads/eodag/pull/1758
.. _#175: https://github.com/vprivat-ads/eodag/pull/175
.. _#1761: https://github.com/vprivat-ads/eodag/pull/1761
.. _#1763: https://github.com/vprivat-ads/eodag/pull/1763
.. _#1764: https://github.com/vprivat-ads/eodag/pull/1764
.. _#1768: https://github.com/vprivat-ads/eodag/pull/1768
.. _#1769: https://github.com/vprivat-ads/eodag/pull/1769
.. _#176: https://github.com/vprivat-ads/eodag/pull/176
.. _#1770: https://github.com/vprivat-ads/eodag/pull/1770
.. _#1773: https://github.com/vprivat-ads/eodag/pull/1773
.. _#1778: https://github.com/vprivat-ads/eodag/pull/1778
.. _#1780: https://github.com/vprivat-ads/eodag/pull/1780
.. _#1781: https://github.com/vprivat-ads/eodag/pull/1781
.. _#1782: https://github.com/vprivat-ads/eodag/pull/1782
.. _#1783: https://github.com/vprivat-ads/eodag/pull/1783
.. _#1784: https://github.com/vprivat-ads/eodag/pull/1784
.. _#1786: https://github.com/vprivat-ads/eodag/pull/1786
.. _#1788: https://github.com/vprivat-ads/eodag/pull/1788
.. _#1789: https://github.com/vprivat-ads/eodag/pull/1789
.. _#1790: https://github.com/vprivat-ads/eodag/pull/1790
.. _#1791: https://github.com/vprivat-ads/eodag/pull/1791
.. _#1794: https://github.com/vprivat-ads/eodag/pull/1794
.. _#1799: https://github.com/vprivat-ads/eodag/pull/1799
.. _#1800: https://github.com/vprivat-ads/eodag/pull/1800
.. _#1801: https://github.com/vprivat-ads/eodag/pull/1801
.. _#1802: https://github.com/vprivat-ads/eodag/pull/1802
.. _#1803: https://github.com/vprivat-ads/eodag/pull/1803
.. _#1804: https://github.com/vprivat-ads/eodag/pull/1804
.. _#1805: https://github.com/vprivat-ads/eodag/pull/1805
.. _#1815: https://github.com/vprivat-ads/eodag/pull/1815
.. _#1816: https://github.com/vprivat-ads/eodag/pull/1816
.. _#1817: https://github.com/vprivat-ads/eodag/pull/1817
.. _#1818: https://github.com/vprivat-ads/eodag/pull/1818
.. _#181: https://github.com/vprivat-ads/eodag/pull/181
.. _#1821: https://github.com/vprivat-ads/eodag/pull/1821
.. _#1823: https://github.com/vprivat-ads/eodag/pull/1823
.. _#1826: https://github.com/vprivat-ads/eodag/pull/1826
.. _#1827: https://github.com/vprivat-ads/eodag/pull/1827
.. _#1828: https://github.com/vprivat-ads/eodag/pull/1828
.. _#182: https://github.com/vprivat-ads/eodag/pull/182
.. _#1830: https://github.com/vprivat-ads/eodag/pull/1830
.. _#1831: https://github.com/vprivat-ads/eodag/pull/1831
.. _#1832: https://github.com/vprivat-ads/eodag/pull/1832
.. _#1836: https://github.com/vprivat-ads/eodag/pull/1836
.. _#1837: https://github.com/vprivat-ads/eodag/pull/1837
.. _#1838: https://github.com/vprivat-ads/eodag/pull/1838
.. _#1839: https://github.com/vprivat-ads/eodag/pull/1839
.. _#183: https://github.com/vprivat-ads/eodag/pull/183
.. _#1840: https://github.com/vprivat-ads/eodag/pull/1840
.. _#1841: https://github.com/vprivat-ads/eodag/pull/1841
.. _#1842: https://github.com/vprivat-ads/eodag/pull/1842
.. _#1844: https://github.com/vprivat-ads/eodag/pull/1844
.. _#1845: https://github.com/vprivat-ads/eodag/pull/1845
.. _#1846: https://github.com/vprivat-ads/eodag/pull/1846
.. _#1847: https://github.com/vprivat-ads/eodag/pull/1847
.. _#1848: https://github.com/vprivat-ads/eodag/pull/1848
.. _#1850: https://github.com/vprivat-ads/eodag/pull/1850
.. _#1851: https://github.com/vprivat-ads/eodag/pull/1851
.. _#1855: https://github.com/vprivat-ads/eodag/pull/1855
.. _#1860: https://github.com/vprivat-ads/eodag/pull/1860
.. _#1865: https://github.com/vprivat-ads/eodag/pull/1865
.. _#1866: https://github.com/vprivat-ads/eodag/pull/1866
.. _#1868: https://github.com/vprivat-ads/eodag/pull/1868
.. _#1869: https://github.com/vprivat-ads/eodag/pull/1869
.. _#186: https://github.com/vprivat-ads/eodag/pull/186
.. _#1870: https://github.com/vprivat-ads/eodag/pull/1870
.. _#1872: https://github.com/vprivat-ads/eodag/pull/1872
.. _#1873: https://github.com/vprivat-ads/eodag/pull/1873
.. _#1874: https://github.com/vprivat-ads/eodag/pull/1874
.. _#1877: https://github.com/vprivat-ads/eodag/pull/1877
.. _#1878: https://github.com/vprivat-ads/eodag/pull/1878
.. _#1879: https://github.com/vprivat-ads/eodag/pull/1879
.. _#1880: https://github.com/vprivat-ads/eodag/pull/1880
.. _#1884: https://github.com/vprivat-ads/eodag/pull/1884
.. _#1886: https://github.com/vprivat-ads/eodag/pull/1886
.. _#1888: https://github.com/vprivat-ads/eodag/pull/1888
.. _#188: https://github.com/vprivat-ads/eodag/pull/188
.. _#1890: https://github.com/vprivat-ads/eodag/pull/1890
.. _#1891: https://github.com/vprivat-ads/eodag/pull/1891
.. _#1892: https://github.com/vprivat-ads/eodag/pull/1892
.. _#1894: https://github.com/vprivat-ads/eodag/pull/1894
.. _#1897: https://github.com/vprivat-ads/eodag/pull/1897
.. _#1899: https://github.com/vprivat-ads/eodag/pull/1899
.. _#189: https://github.com/vprivat-ads/eodag/pull/189
.. _#1902: https://github.com/vprivat-ads/eodag/pull/1902
.. _#1906: https://github.com/vprivat-ads/eodag/pull/1906
.. _#1907: https://github.com/vprivat-ads/eodag/pull/1907
.. _#1908: https://github.com/vprivat-ads/eodag/pull/1908
.. _#190: https://github.com/vprivat-ads/eodag/pull/190
.. _#1914: https://github.com/vprivat-ads/eodag/pull/1914
.. _#1915: https://github.com/vprivat-ads/eodag/pull/1915
.. _#1917: https://github.com/vprivat-ads/eodag/pull/1917
.. _#1920: https://github.com/vprivat-ads/eodag/pull/1920
.. _#1921: https://github.com/vprivat-ads/eodag/pull/1921
.. _#1923: https://github.com/vprivat-ads/eodag/pull/1923
.. _#1924: https://github.com/vprivat-ads/eodag/pull/1924
.. _#192: https://github.com/vprivat-ads/eodag/pull/192
.. _#1935: https://github.com/vprivat-ads/eodag/pull/1935
.. _#1938: https://github.com/vprivat-ads/eodag/pull/1938
.. _#1940: https://github.com/vprivat-ads/eodag/pull/1940
.. _#1947: https://github.com/vprivat-ads/eodag/pull/1947
.. _#1949: https://github.com/vprivat-ads/eodag/pull/1949
.. _#1951: https://github.com/vprivat-ads/eodag/pull/1951
.. _#1952: https://github.com/vprivat-ads/eodag/pull/1952
.. _#1955: https://github.com/vprivat-ads/eodag/pull/1955
.. _#1956: https://github.com/vprivat-ads/eodag/pull/1956
.. _#1958: https://github.com/vprivat-ads/eodag/pull/1958
.. _#195: https://github.com/vprivat-ads/eodag/pull/195
.. _#1963: https://github.com/vprivat-ads/eodag/pull/1963
.. _#1966: https://github.com/vprivat-ads/eodag/pull/1966
.. _#1968: https://github.com/vprivat-ads/eodag/pull/1968
.. _#196: https://github.com/vprivat-ads/eodag/pull/196
.. _#1970: https://github.com/vprivat-ads/eodag/pull/1970
.. _#1971: https://github.com/vprivat-ads/eodag/pull/1971
.. _#1972: https://github.com/vprivat-ads/eodag/pull/1972
.. _#1973: https://github.com/vprivat-ads/eodag/pull/1973
.. _#1974: https://github.com/vprivat-ads/eodag/pull/1974
.. _#1975: https://github.com/vprivat-ads/eodag/pull/1975
.. _#1979: https://github.com/vprivat-ads/eodag/pull/1979
.. _#1981: https://github.com/vprivat-ads/eodag/pull/1981
.. _#1982: https://github.com/vprivat-ads/eodag/pull/1982
.. _#1983: https://github.com/vprivat-ads/eodag/pull/1983
.. _#1984: https://github.com/vprivat-ads/eodag/pull/1984
.. _#1985: https://github.com/vprivat-ads/eodag/pull/1985
.. _#1986: https://github.com/vprivat-ads/eodag/pull/1986
.. _#1989: https://github.com/vprivat-ads/eodag/pull/1989
.. _#198: https://github.com/vprivat-ads/eodag/pull/198
.. _#1993: https://github.com/vprivat-ads/eodag/pull/1993
.. _#1995: https://github.com/vprivat-ads/eodag/pull/1995
.. _#1997: https://github.com/vprivat-ads/eodag/pull/1997
.. _#1999: https://github.com/vprivat-ads/eodag/pull/1999
.. _#199: https://github.com/vprivat-ads/eodag/pull/199
.. _#2003: https://github.com/vprivat-ads/eodag/pull/2003
.. _#2004: https://github.com/vprivat-ads/eodag/pull/2004
.. _#2005: https://github.com/vprivat-ads/eodag/pull/2005
.. _#2006: https://github.com/vprivat-ads/eodag/pull/2006
.. _#200: https://github.com/vprivat-ads/eodag/pull/200
.. _#2015: https://github.com/vprivat-ads/eodag/pull/2015
.. _#2016: https://github.com/vprivat-ads/eodag/pull/2016
.. _#2017: https://github.com/vprivat-ads/eodag/pull/2017
.. _#2018: https://github.com/vprivat-ads/eodag/pull/2018
.. _#201: https://github.com/vprivat-ads/eodag/pull/201
.. _#2023: https://github.com/vprivat-ads/eodag/pull/2023
.. _#2030: https://github.com/vprivat-ads/eodag/pull/2030
.. _#2032: https://github.com/vprivat-ads/eodag/pull/2032
.. _#2033: https://github.com/vprivat-ads/eodag/pull/2033
.. _#2037: https://github.com/vprivat-ads/eodag/pull/2037
.. _#2038: https://github.com/vprivat-ads/eodag/pull/2038
.. _#2040: https://github.com/vprivat-ads/eodag/pull/2040
.. _#2041: https://github.com/vprivat-ads/eodag/pull/2041
.. _#2042: https://github.com/vprivat-ads/eodag/pull/2042
.. _#2043: https://github.com/vprivat-ads/eodag/pull/2043
.. _#2044: https://github.com/vprivat-ads/eodag/pull/2044
.. _#2046: https://github.com/vprivat-ads/eodag/pull/2046
.. _#204: https://github.com/vprivat-ads/eodag/pull/204
.. _#2051: https://github.com/vprivat-ads/eodag/pull/2051
.. _#2054: https://github.com/vprivat-ads/eodag/pull/2054
.. _#2058: https://github.com/vprivat-ads/eodag/pull/2058
.. _#2059: https://github.com/vprivat-ads/eodag/pull/2059
.. _#2062: https://github.com/vprivat-ads/eodag/pull/2062
.. _#209: https://github.com/vprivat-ads/eodag/pull/209
.. _#211: https://github.com/vprivat-ads/eodag/pull/211
.. _#218: https://github.com/vprivat-ads/eodag/pull/218
.. _#219: https://github.com/vprivat-ads/eodag/pull/219
.. _#221: https://github.com/vprivat-ads/eodag/pull/221
.. _#223: https://github.com/vprivat-ads/eodag/pull/223
.. _#224: https://github.com/vprivat-ads/eodag/pull/224
.. _#225: https://github.com/vprivat-ads/eodag/pull/225
.. _#228: https://github.com/vprivat-ads/eodag/pull/228
.. _#233: https://github.com/vprivat-ads/eodag/pull/233
.. _#235: https://github.com/vprivat-ads/eodag/pull/235
.. _#244: https://github.com/vprivat-ads/eodag/pull/244
.. _#246: https://github.com/vprivat-ads/eodag/pull/246
.. _#247: https://github.com/vprivat-ads/eodag/pull/247
.. _#248: https://github.com/vprivat-ads/eodag/pull/248
.. _#249: https://github.com/vprivat-ads/eodag/pull/249
.. _#253: https://github.com/vprivat-ads/eodag/pull/253
.. _#254: https://github.com/vprivat-ads/eodag/pull/254
.. _#257: https://github.com/vprivat-ads/eodag/pull/257
.. _#258: https://github.com/vprivat-ads/eodag/pull/258
.. _#260: https://github.com/vprivat-ads/eodag/pull/260
.. _#261: https://github.com/vprivat-ads/eodag/pull/261
.. _#269: https://github.com/vprivat-ads/eodag/pull/269
.. _#273: https://github.com/vprivat-ads/eodag/pull/273
.. _#274: https://github.com/vprivat-ads/eodag/pull/274
.. _#276: https://github.com/vprivat-ads/eodag/pull/276
.. _#279: https://github.com/vprivat-ads/eodag/pull/279
.. _#280: https://github.com/vprivat-ads/eodag/pull/280
.. _#282: https://github.com/vprivat-ads/eodag/pull/282
.. _#283: https://github.com/vprivat-ads/eodag/pull/283
.. _#284: https://github.com/vprivat-ads/eodag/pull/284
.. _#285: https://github.com/vprivat-ads/eodag/pull/285
.. _#287: https://github.com/vprivat-ads/eodag/pull/287
.. _#288: https://github.com/vprivat-ads/eodag/pull/288
.. _#290: https://github.com/vprivat-ads/eodag/pull/290
.. _#292: https://github.com/vprivat-ads/eodag/pull/292
.. _#293: https://github.com/vprivat-ads/eodag/pull/293
.. _#294: https://github.com/vprivat-ads/eodag/pull/294
.. _#295: https://github.com/vprivat-ads/eodag/pull/295
.. _#296: https://github.com/vprivat-ads/eodag/pull/296
.. _#299: https://github.com/vprivat-ads/eodag/pull/299
.. _#301: https://github.com/vprivat-ads/eodag/pull/301
.. _#302: https://github.com/vprivat-ads/eodag/pull/302
.. _#304: https://github.com/vprivat-ads/eodag/pull/304
.. _#306: https://github.com/vprivat-ads/eodag/pull/306
.. _#307: https://github.com/vprivat-ads/eodag/pull/307
.. _#308: https://github.com/vprivat-ads/eodag/pull/308
.. _#314: https://github.com/vprivat-ads/eodag/pull/314
.. _#316: https://github.com/vprivat-ads/eodag/pull/316
.. _#317: https://github.com/vprivat-ads/eodag/pull/317
.. _#318: https://github.com/vprivat-ads/eodag/pull/318
.. _#319: https://github.com/vprivat-ads/eodag/pull/319
.. _#320: https://github.com/vprivat-ads/eodag/pull/320
.. _#321: https://github.com/vprivat-ads/eodag/pull/321
.. _#323: https://github.com/vprivat-ads/eodag/pull/323
.. _#324: https://github.com/vprivat-ads/eodag/pull/324
.. _#329: https://github.com/vprivat-ads/eodag/pull/329
.. _#330: https://github.com/vprivat-ads/eodag/pull/330
.. _#331: https://github.com/vprivat-ads/eodag/pull/331
.. _#335: https://github.com/vprivat-ads/eodag/pull/335
.. _#336: https://github.com/vprivat-ads/eodag/pull/336
.. _#337: https://github.com/vprivat-ads/eodag/pull/337
.. _#338: https://github.com/vprivat-ads/eodag/pull/338
.. _#339: https://github.com/vprivat-ads/eodag/pull/339
.. _#340: https://github.com/vprivat-ads/eodag/pull/340
.. _#341: https://github.com/vprivat-ads/eodag/pull/341
.. _#344: https://github.com/vprivat-ads/eodag/pull/344
.. _#345: https://github.com/vprivat-ads/eodag/pull/345
.. _#347: https://github.com/vprivat-ads/eodag/pull/347
.. _#350: https://github.com/vprivat-ads/eodag/pull/350
.. _#352: https://github.com/vprivat-ads/eodag/pull/352
.. _#355: https://github.com/vprivat-ads/eodag/pull/355
.. _#356: https://github.com/vprivat-ads/eodag/pull/356
.. _#358: https://github.com/vprivat-ads/eodag/pull/358
.. _#359: https://github.com/vprivat-ads/eodag/pull/359
.. _#361: https://github.com/vprivat-ads/eodag/pull/361
.. _#363: https://github.com/vprivat-ads/eodag/pull/363
.. _#366: https://github.com/vprivat-ads/eodag/pull/366
.. _#367: https://github.com/vprivat-ads/eodag/pull/367
.. _#371: https://github.com/vprivat-ads/eodag/pull/371
.. _#372: https://github.com/vprivat-ads/eodag/pull/372
.. _#373: https://github.com/vprivat-ads/eodag/pull/373
.. _#374: https://github.com/vprivat-ads/eodag/pull/374
.. _#377: https://github.com/vprivat-ads/eodag/pull/377
.. _#379: https://github.com/vprivat-ads/eodag/pull/379
.. _#380: https://github.com/vprivat-ads/eodag/pull/380
.. _#388: https://github.com/vprivat-ads/eodag/pull/388
.. _#389: https://github.com/vprivat-ads/eodag/pull/389
.. _#393: https://github.com/vprivat-ads/eodag/pull/393
.. _#394: https://github.com/vprivat-ads/eodag/pull/394
.. _#398: https://github.com/vprivat-ads/eodag/pull/398
.. _#399: https://github.com/vprivat-ads/eodag/pull/399
.. _#401: https://github.com/vprivat-ads/eodag/pull/401
.. _#405: https://github.com/vprivat-ads/eodag/pull/405
.. _#406: https://github.com/vprivat-ads/eodag/pull/406
.. _#407: https://github.com/vprivat-ads/eodag/pull/407
.. _#410: https://github.com/vprivat-ads/eodag/pull/410
.. _#411: https://github.com/vprivat-ads/eodag/pull/411
.. _#415: https://github.com/vprivat-ads/eodag/pull/415
.. _#416: https://github.com/vprivat-ads/eodag/pull/416
.. _#417: https://github.com/vprivat-ads/eodag/pull/417
.. _#419: https://github.com/vprivat-ads/eodag/pull/419
.. _#420: https://github.com/vprivat-ads/eodag/pull/420
.. _#430: https://github.com/vprivat-ads/eodag/pull/430
.. _#431: https://github.com/vprivat-ads/eodag/pull/431
.. _#433: https://github.com/vprivat-ads/eodag/pull/433
.. _#434: https://github.com/vprivat-ads/eodag/pull/434
.. _#435: https://github.com/vprivat-ads/eodag/pull/435
.. _#436: https://github.com/vprivat-ads/eodag/pull/436
.. _#438: https://github.com/vprivat-ads/eodag/pull/438
.. _#440: https://github.com/vprivat-ads/eodag/pull/440
.. _#442: https://github.com/vprivat-ads/eodag/pull/442
.. _#443: https://github.com/vprivat-ads/eodag/pull/443
.. _#444: https://github.com/vprivat-ads/eodag/pull/444
.. _#447: https://github.com/vprivat-ads/eodag/pull/447
.. _#448: https://github.com/vprivat-ads/eodag/pull/448
.. _#449: https://github.com/vprivat-ads/eodag/pull/449
.. _#450: https://github.com/vprivat-ads/eodag/pull/450
.. _#451: https://github.com/vprivat-ads/eodag/pull/451
.. _#452: https://github.com/vprivat-ads/eodag/pull/452
.. _#456: https://github.com/vprivat-ads/eodag/pull/456
.. _#458: https://github.com/vprivat-ads/eodag/pull/458
.. _#460: https://github.com/vprivat-ads/eodag/pull/460
.. _#462: https://github.com/vprivat-ads/eodag/pull/462
.. _#464: https://github.com/vprivat-ads/eodag/pull/464
.. _#467: https://github.com/vprivat-ads/eodag/pull/467
.. _#469: https://github.com/vprivat-ads/eodag/pull/469
.. _#470: https://github.com/vprivat-ads/eodag/pull/470
.. _#471: https://github.com/vprivat-ads/eodag/pull/471
.. _#472: https://github.com/vprivat-ads/eodag/pull/472
.. _#473: https://github.com/vprivat-ads/eodag/pull/473
.. _#475: https://github.com/vprivat-ads/eodag/pull/475
.. _#477: https://github.com/vprivat-ads/eodag/pull/477
.. _#480: https://github.com/vprivat-ads/eodag/pull/480
.. _#481: https://github.com/vprivat-ads/eodag/pull/481
.. _#483: https://github.com/vprivat-ads/eodag/pull/483
.. _#484: https://github.com/vprivat-ads/eodag/pull/484
.. _#485: https://github.com/vprivat-ads/eodag/pull/485
.. _#486: https://github.com/vprivat-ads/eodag/pull/486
.. _#489: https://github.com/vprivat-ads/eodag/pull/489
.. _#490: https://github.com/vprivat-ads/eodag/pull/490
.. _#491: https://github.com/vprivat-ads/eodag/pull/491
.. _#492: https://github.com/vprivat-ads/eodag/pull/492
.. _#493: https://github.com/vprivat-ads/eodag/pull/493
.. _#494: https://github.com/vprivat-ads/eodag/pull/494
.. _#495: https://github.com/vprivat-ads/eodag/pull/495
.. _#496: https://github.com/vprivat-ads/eodag/pull/496
.. _#497: https://github.com/vprivat-ads/eodag/pull/497
.. _#500: https://github.com/vprivat-ads/eodag/pull/500
.. _#502: https://github.com/vprivat-ads/eodag/pull/502
.. _#505: https://github.com/vprivat-ads/eodag/pull/505
.. _#506: https://github.com/vprivat-ads/eodag/pull/506
.. _#508: https://github.com/vprivat-ads/eodag/pull/508
.. _#510: https://github.com/vprivat-ads/eodag/pull/510
.. _#511: https://github.com/vprivat-ads/eodag/pull/511
.. _#513: https://github.com/vprivat-ads/eodag/pull/513
.. _#514: https://github.com/vprivat-ads/eodag/pull/514
.. _#517: https://github.com/vprivat-ads/eodag/pull/517
.. _#522: https://github.com/vprivat-ads/eodag/pull/522
.. _#523: https://github.com/vprivat-ads/eodag/pull/523
.. _#524: https://github.com/vprivat-ads/eodag/pull/524
.. _#525: https://github.com/vprivat-ads/eodag/pull/525
.. _#526: https://github.com/vprivat-ads/eodag/pull/526
.. _#527: https://github.com/vprivat-ads/eodag/pull/527
.. _#528: https://github.com/vprivat-ads/eodag/pull/528
.. _#529: https://github.com/vprivat-ads/eodag/pull/529
.. _#530: https://github.com/vprivat-ads/eodag/pull/530
.. _#535: https://github.com/vprivat-ads/eodag/pull/535
.. _#539: https://github.com/vprivat-ads/eodag/pull/539
.. _#540: https://github.com/vprivat-ads/eodag/pull/540
.. _#541: https://github.com/vprivat-ads/eodag/pull/541
.. _#542: https://github.com/vprivat-ads/eodag/pull/542
.. _#543: https://github.com/vprivat-ads/eodag/pull/543
.. _#544: https://github.com/vprivat-ads/eodag/pull/544
.. _#545: https://github.com/vprivat-ads/eodag/pull/545
.. _#549: https://github.com/vprivat-ads/eodag/pull/549
.. _#552: https://github.com/vprivat-ads/eodag/pull/552
.. _#553: https://github.com/vprivat-ads/eodag/pull/553
.. _#554: https://github.com/vprivat-ads/eodag/pull/554
.. _#555: https://github.com/vprivat-ads/eodag/pull/555
.. _#557: https://github.com/vprivat-ads/eodag/pull/557
.. _#558: https://github.com/vprivat-ads/eodag/pull/558
.. _#559: https://github.com/vprivat-ads/eodag/pull/559
.. _#561: https://github.com/vprivat-ads/eodag/pull/561
.. _#562: https://github.com/vprivat-ads/eodag/pull/562
.. _#566: https://github.com/vprivat-ads/eodag/pull/566
.. _#572: https://github.com/vprivat-ads/eodag/pull/572
.. _#574: https://github.com/vprivat-ads/eodag/pull/574
.. _#576: https://github.com/vprivat-ads/eodag/pull/576
.. _#578: https://github.com/vprivat-ads/eodag/pull/578
.. _#579: https://github.com/vprivat-ads/eodag/pull/579
.. _#580: https://github.com/vprivat-ads/eodag/pull/580
.. _#582: https://github.com/vprivat-ads/eodag/pull/582
.. _#586: https://github.com/vprivat-ads/eodag/pull/586
.. _#588: https://github.com/vprivat-ads/eodag/pull/588
.. _#589: https://github.com/vprivat-ads/eodag/pull/589
.. _#590: https://github.com/vprivat-ads/eodag/pull/590
.. _#592: https://github.com/vprivat-ads/eodag/pull/592
.. _#593: https://github.com/vprivat-ads/eodag/pull/593
.. _#595: https://github.com/vprivat-ads/eodag/pull/595
.. _#597: https://github.com/vprivat-ads/eodag/pull/597
.. _#598: https://github.com/vprivat-ads/eodag/pull/598
.. _#599: https://github.com/vprivat-ads/eodag/pull/599
.. _#601: https://github.com/vprivat-ads/eodag/pull/601
.. _#602: https://github.com/vprivat-ads/eodag/pull/602
.. _#603: https://github.com/vprivat-ads/eodag/pull/603
.. _#604: https://github.com/vprivat-ads/eodag/pull/604
.. _#607: https://github.com/vprivat-ads/eodag/pull/607
.. _#609: https://github.com/vprivat-ads/eodag/pull/609
.. _#610: https://github.com/vprivat-ads/eodag/pull/610
.. _#612: https://github.com/vprivat-ads/eodag/pull/612
.. _#616: https://github.com/vprivat-ads/eodag/pull/616
.. _#619: https://github.com/vprivat-ads/eodag/pull/619
.. _#620: https://github.com/vprivat-ads/eodag/pull/620
.. _#621: https://github.com/vprivat-ads/eodag/pull/621
.. _#622: https://github.com/vprivat-ads/eodag/pull/622
.. _#623: https://github.com/vprivat-ads/eodag/pull/623
.. _#624: https://github.com/vprivat-ads/eodag/pull/624
.. _#625: https://github.com/vprivat-ads/eodag/pull/625
.. _#626: https://github.com/vprivat-ads/eodag/pull/626
.. _#629: https://github.com/vprivat-ads/eodag/pull/629
.. _#630: https://github.com/vprivat-ads/eodag/pull/630
.. _#631: https://github.com/vprivat-ads/eodag/pull/631
.. _#632: https://github.com/vprivat-ads/eodag/pull/632
.. _#634: https://github.com/vprivat-ads/eodag/pull/634
.. _#635: https://github.com/vprivat-ads/eodag/pull/635
.. _#636: https://github.com/vprivat-ads/eodag/pull/636
.. _#638: https://github.com/vprivat-ads/eodag/pull/638
.. _#639: https://github.com/vprivat-ads/eodag/pull/639
.. _#640: https://github.com/vprivat-ads/eodag/pull/640
.. _#641: https://github.com/vprivat-ads/eodag/pull/641
.. _#642: https://github.com/vprivat-ads/eodag/pull/642
.. _#643: https://github.com/vprivat-ads/eodag/pull/643
.. _#644: https://github.com/vprivat-ads/eodag/pull/644
.. _#645: https://github.com/vprivat-ads/eodag/pull/645
.. _#646: https://github.com/vprivat-ads/eodag/pull/646
.. _#647: https://github.com/vprivat-ads/eodag/pull/647
.. _#649: https://github.com/vprivat-ads/eodag/pull/649
.. _#652: https://github.com/vprivat-ads/eodag/pull/652
.. _#653: https://github.com/vprivat-ads/eodag/pull/653
.. _#654: https://github.com/vprivat-ads/eodag/pull/654
.. _#656: https://github.com/vprivat-ads/eodag/pull/656
.. _#657: https://github.com/vprivat-ads/eodag/pull/657
.. _#658: https://github.com/vprivat-ads/eodag/pull/658
.. _#659: https://github.com/vprivat-ads/eodag/pull/659
.. _#660: https://github.com/vprivat-ads/eodag/pull/660
.. _#664: https://github.com/vprivat-ads/eodag/pull/664
.. _#665: https://github.com/vprivat-ads/eodag/pull/665
.. _#666: https://github.com/vprivat-ads/eodag/pull/666
.. _#667: https://github.com/vprivat-ads/eodag/pull/667
.. _#668: https://github.com/vprivat-ads/eodag/pull/668
.. _#669: https://github.com/vprivat-ads/eodag/pull/669
.. _#670: https://github.com/vprivat-ads/eodag/pull/670
.. _#672: https://github.com/vprivat-ads/eodag/pull/672
.. _#675: https://github.com/vprivat-ads/eodag/pull/675
.. _#677: https://github.com/vprivat-ads/eodag/pull/677
.. _#678: https://github.com/vprivat-ads/eodag/pull/678
.. _#679: https://github.com/vprivat-ads/eodag/pull/679
.. _#681: https://github.com/vprivat-ads/eodag/pull/681
.. _#682: https://github.com/vprivat-ads/eodag/pull/682
.. _#683: https://github.com/vprivat-ads/eodag/pull/683
.. _#688: https://github.com/vprivat-ads/eodag/pull/688
.. _#690: https://github.com/vprivat-ads/eodag/pull/690
.. _#691: https://github.com/vprivat-ads/eodag/pull/691
.. _#693: https://github.com/vprivat-ads/eodag/pull/693
.. _#694: https://github.com/vprivat-ads/eodag/pull/694
.. _#695: https://github.com/vprivat-ads/eodag/pull/695
.. _#696: https://github.com/vprivat-ads/eodag/pull/696
.. _#697: https://github.com/vprivat-ads/eodag/pull/697
.. _#698: https://github.com/vprivat-ads/eodag/pull/698
.. _#699: https://github.com/vprivat-ads/eodag/pull/699
.. _#700: https://github.com/vprivat-ads/eodag/pull/700
.. _#701: https://github.com/vprivat-ads/eodag/pull/701
.. _#702: https://github.com/vprivat-ads/eodag/pull/702
.. _#703: https://github.com/vprivat-ads/eodag/pull/703
.. _#704: https://github.com/vprivat-ads/eodag/pull/704
.. _#705: https://github.com/vprivat-ads/eodag/pull/705
.. _#706: https://github.com/vprivat-ads/eodag/pull/706
.. _#707: https://github.com/vprivat-ads/eodag/pull/707
.. _#708: https://github.com/vprivat-ads/eodag/pull/708
.. _#710: https://github.com/vprivat-ads/eodag/pull/710
.. _#711: https://github.com/vprivat-ads/eodag/pull/711
.. _#712: https://github.com/vprivat-ads/eodag/pull/712
.. _#713: https://github.com/vprivat-ads/eodag/pull/713
.. _#714: https://github.com/vprivat-ads/eodag/pull/714
.. _#715: https://github.com/vprivat-ads/eodag/pull/715
.. _#717: https://github.com/vprivat-ads/eodag/pull/717
.. _#720: https://github.com/vprivat-ads/eodag/pull/720
.. _#722: https://github.com/vprivat-ads/eodag/pull/722
.. _#723: https://github.com/vprivat-ads/eodag/pull/723
.. _#724: https://github.com/vprivat-ads/eodag/pull/724
.. _#727: https://github.com/vprivat-ads/eodag/pull/727
.. _#729: https://github.com/vprivat-ads/eodag/pull/729
.. _#731: https://github.com/vprivat-ads/eodag/pull/731
.. _#737: https://github.com/vprivat-ads/eodag/pull/737
.. _#738: https://github.com/vprivat-ads/eodag/pull/738
.. _#739: https://github.com/vprivat-ads/eodag/pull/739
.. _#741: https://github.com/vprivat-ads/eodag/pull/741
.. _#742: https://github.com/vprivat-ads/eodag/pull/742
.. _#743: https://github.com/vprivat-ads/eodag/pull/743
.. _#744: https://github.com/vprivat-ads/eodag/pull/744
.. _#745: https://github.com/vprivat-ads/eodag/pull/745
.. _#746: https://github.com/vprivat-ads/eodag/pull/746
.. _#749: https://github.com/vprivat-ads/eodag/pull/749
.. _#750: https://github.com/vprivat-ads/eodag/pull/750
.. _#751: https://github.com/vprivat-ads/eodag/pull/751
.. _#754: https://github.com/vprivat-ads/eodag/pull/754
.. _#756: https://github.com/vprivat-ads/eodag/pull/756
.. _#757: https://github.com/vprivat-ads/eodag/pull/757
.. _#759: https://github.com/vprivat-ads/eodag/pull/759
.. _#762: https://github.com/vprivat-ads/eodag/pull/762
.. _#763: https://github.com/vprivat-ads/eodag/pull/763
.. _#764: https://github.com/vprivat-ads/eodag/pull/764
.. _#771: https://github.com/vprivat-ads/eodag/pull/771
.. _#772: https://github.com/vprivat-ads/eodag/pull/772
.. _#774: https://github.com/vprivat-ads/eodag/pull/774
.. _#775: https://github.com/vprivat-ads/eodag/pull/775
.. _#776: https://github.com/vprivat-ads/eodag/pull/776
.. _#777: https://github.com/vprivat-ads/eodag/pull/777
.. _#781: https://github.com/vprivat-ads/eodag/pull/781
.. _#788: https://github.com/vprivat-ads/eodag/pull/788
.. _#790: https://github.com/vprivat-ads/eodag/pull/790
.. _#791: https://github.com/vprivat-ads/eodag/pull/791
.. _#793: https://github.com/vprivat-ads/eodag/pull/793
.. _#794: https://github.com/vprivat-ads/eodag/pull/794
.. _#795: https://github.com/vprivat-ads/eodag/pull/795
.. _#796: https://github.com/vprivat-ads/eodag/pull/796
.. _#797: https://github.com/vprivat-ads/eodag/pull/797
.. _#798: https://github.com/vprivat-ads/eodag/pull/798
.. _#802: https://github.com/vprivat-ads/eodag/pull/802
.. _#804: https://github.com/vprivat-ads/eodag/pull/804
.. _#805: https://github.com/vprivat-ads/eodag/pull/805
.. _#806: https://github.com/vprivat-ads/eodag/pull/806
.. _#807: https://github.com/vprivat-ads/eodag/pull/807
.. _#808: https://github.com/vprivat-ads/eodag/pull/808
.. _#812: https://github.com/vprivat-ads/eodag/pull/812
.. _#813: https://github.com/vprivat-ads/eodag/pull/813
.. _#818: https://github.com/vprivat-ads/eodag/pull/818
.. _#819: https://github.com/vprivat-ads/eodag/pull/819
.. _#821: https://github.com/vprivat-ads/eodag/pull/821
.. _#822: https://github.com/vprivat-ads/eodag/pull/822
.. _#824: https://github.com/vprivat-ads/eodag/pull/824
.. _#825: https://github.com/vprivat-ads/eodag/pull/825
.. _#828: https://github.com/vprivat-ads/eodag/pull/828
.. _#829: https://github.com/vprivat-ads/eodag/pull/829
.. _#830: https://github.com/vprivat-ads/eodag/pull/830
.. _#832: https://github.com/vprivat-ads/eodag/pull/832
.. _#835: https://github.com/vprivat-ads/eodag/pull/835
.. _#836: https://github.com/vprivat-ads/eodag/pull/836
.. _#837: https://github.com/vprivat-ads/eodag/pull/837
.. _#838: https://github.com/vprivat-ads/eodag/pull/838
.. _#840: https://github.com/vprivat-ads/eodag/pull/840
.. _#841: https://github.com/vprivat-ads/eodag/pull/841
.. _#842: https://github.com/vprivat-ads/eodag/pull/842
.. _#843: https://github.com/vprivat-ads/eodag/pull/843
.. _#844: https://github.com/vprivat-ads/eodag/pull/844
.. _#846: https://github.com/vprivat-ads/eodag/pull/846
.. _#856: https://github.com/vprivat-ads/eodag/pull/856
.. _#863: https://github.com/vprivat-ads/eodag/pull/863
.. _#866: https://github.com/vprivat-ads/eodag/pull/866
.. _#867: https://github.com/vprivat-ads/eodag/pull/867
.. _#868: https://github.com/vprivat-ads/eodag/pull/868
.. _#872: https://github.com/vprivat-ads/eodag/pull/872
.. _#877: https://github.com/vprivat-ads/eodag/pull/877
.. _#878: https://github.com/vprivat-ads/eodag/pull/878
.. _#879: https://github.com/vprivat-ads/eodag/pull/879
.. _#880: https://github.com/vprivat-ads/eodag/pull/880
.. _#881: https://github.com/vprivat-ads/eodag/pull/881
.. _#882: https://github.com/vprivat-ads/eodag/pull/882
.. _#883: https://github.com/vprivat-ads/eodag/pull/883
.. _#884: https://github.com/vprivat-ads/eodag/pull/884
.. _#885: https://github.com/vprivat-ads/eodag/pull/885
.. _#890: https://github.com/vprivat-ads/eodag/pull/890
.. _#891: https://github.com/vprivat-ads/eodag/pull/891
.. _#892: https://github.com/vprivat-ads/eodag/pull/892
.. _#893: https://github.com/vprivat-ads/eodag/pull/893
.. _#894: https://github.com/vprivat-ads/eodag/pull/894
.. _#895: https://github.com/vprivat-ads/eodag/pull/895
.. _#898: https://github.com/vprivat-ads/eodag/pull/898
.. _#899: https://github.com/vprivat-ads/eodag/pull/899
.. _#902: https://github.com/vprivat-ads/eodag/pull/902
.. _#903: https://github.com/vprivat-ads/eodag/pull/903
.. _#905: https://github.com/vprivat-ads/eodag/pull/905
.. _#911: https://github.com/vprivat-ads/eodag/pull/911
.. _#913: https://github.com/vprivat-ads/eodag/pull/913
.. _#915: https://github.com/vprivat-ads/eodag/pull/915
.. _#917: https://github.com/vprivat-ads/eodag/pull/917
.. _#919: https://github.com/vprivat-ads/eodag/pull/919
.. _#920: https://github.com/vprivat-ads/eodag/pull/920
.. _#921: https://github.com/vprivat-ads/eodag/pull/921
.. _#925: https://github.com/vprivat-ads/eodag/pull/925
.. _#926: https://github.com/vprivat-ads/eodag/pull/926
.. _#927: https://github.com/vprivat-ads/eodag/pull/927
.. _#929: https://github.com/vprivat-ads/eodag/pull/929
.. _#932: https://github.com/vprivat-ads/eodag/pull/932
.. _#934: https://github.com/vprivat-ads/eodag/pull/934
.. _#935: https://github.com/vprivat-ads/eodag/pull/935
.. _#936: https://github.com/vprivat-ads/eodag/pull/936
.. _#943: https://github.com/vprivat-ads/eodag/pull/943
.. _#946: https://github.com/vprivat-ads/eodag/pull/946
.. _#947: https://github.com/vprivat-ads/eodag/pull/947
.. _#957: https://github.com/vprivat-ads/eodag/pull/957
.. _#958: https://github.com/vprivat-ads/eodag/pull/958
.. _#961: https://github.com/vprivat-ads/eodag/pull/961
.. _#962: https://github.com/vprivat-ads/eodag/pull/962
.. _#969: https://github.com/vprivat-ads/eodag/pull/969
.. _#974: https://github.com/vprivat-ads/eodag/pull/974
.. _#976: https://github.com/vprivat-ads/eodag/pull/976
.. _#977: https://github.com/vprivat-ads/eodag/pull/977
.. _#978: https://github.com/vprivat-ads/eodag/pull/978
.. _#980: https://github.com/vprivat-ads/eodag/pull/980
.. _#981: https://github.com/vprivat-ads/eodag/pull/981
.. _#982: https://github.com/vprivat-ads/eodag/pull/982
.. _#983: https://github.com/vprivat-ads/eodag/pull/983
.. _#986: https://github.com/vprivat-ads/eodag/pull/986
.. _#987: https://github.com/vprivat-ads/eodag/pull/987
.. _#988: https://github.com/vprivat-ads/eodag/pull/988
.. _#991: https://github.com/vprivat-ads/eodag/pull/991
.. _#992: https://github.com/vprivat-ads/eodag/pull/992
.. _#996: https://github.com/vprivat-ads/eodag/pull/996
.. _#997: https://github.com/vprivat-ads/eodag/pull/997
.. _00bf073: https://github.com/vprivat-ads/eodag/commit/00bf073000fbc7bcc1d349ad8217e9ea3bac2eab
.. _0194b16: https://github.com/vprivat-ads/eodag/commit/0194b162c83a93a6c214c29186f478e0eaaa8104
.. _0196e96: https://github.com/vprivat-ads/eodag/commit/0196e96e4a8463d8692c4aabbf80752adc152409
.. _01b130a: https://github.com/vprivat-ads/eodag/commit/01b130a02a9c16fc3c76ee180bf56d1356380f82
.. _0244dae: https://github.com/vprivat-ads/eodag/commit/0244dae9d572a63c5fca50e91b24d2a975c63819
.. _024a916: https://github.com/vprivat-ads/eodag/commit/024a9169e163861e027f1cf2b4c7e6434c97c56e
.. _0293c5f: https://github.com/vprivat-ads/eodag/commit/0293c5f1ccdf93786db37f6b9932fe7d74db6cbf
.. _02f9d9f: https://github.com/vprivat-ads/eodag/commit/02f9d9f25c23d4ba55b0ac03a5e4380a6f5b5ffe
.. _03306fa: https://github.com/vprivat-ads/eodag/commit/03306fa3a4485c9bb05108a9210de226d1abf8f2
.. _034819a: https://github.com/vprivat-ads/eodag/commit/034819a4a0cf43ac641854d14287ffc954f30622
.. _035f5a7: https://github.com/vprivat-ads/eodag/commit/035f5a74fb3c2a21f0f5372209162936a13a5c24
.. _036b86b: https://github.com/vprivat-ads/eodag/commit/036b86bbefeed905c9962a7a4bf7bca8258246fb
.. _03c72bc: https://github.com/vprivat-ads/eodag/commit/03c72bcf1612639f8383dee32f3405d2042fd4af
.. _0440f20: https://github.com/vprivat-ads/eodag/commit/0440f2082cd74f5a21822455580cd2a81415d665
.. _044fd8b: https://github.com/vprivat-ads/eodag/commit/044fd8b904f84c579e1ac84fe8c5aac6a9b9591e
.. _0454652: https://github.com/vprivat-ads/eodag/commit/04546522890d49f922f2870d4811a1cd18dd5eea
.. _045a849: https://github.com/vprivat-ads/eodag/commit/045a8492cb8f24aaa39eb9c68def97833e2efd35
.. _04b0b55: https://github.com/vprivat-ads/eodag/commit/04b0b5536b370a92843886ebf5135fac37172c18
.. _04b9584: https://github.com/vprivat-ads/eodag/commit/04b9584dfeb820d87f5fef1215a02c5f24446f65
.. _050c371: https://github.com/vprivat-ads/eodag/commit/050c3711d1a8f6584f098335f1b9a60ef34759d6
.. _054f4a8: https://github.com/vprivat-ads/eodag/commit/054f4a85669ecb16b42432876865a6f7a83244ff
.. _05697ac: https://github.com/vprivat-ads/eodag/commit/05697ac048f76b1a66b42951dfd61bcc7cd76581
.. _057c1e6: https://github.com/vprivat-ads/eodag/commit/057c1e69872214c5150d64055180c6e691acdf1f
.. _059bc07: https://github.com/vprivat-ads/eodag/commit/059bc078285edd7a8d41bc7e37212a8b18ef4186
.. _05b24fc: https://github.com/vprivat-ads/eodag/commit/05b24fc692cc5b55400ed8339b638b1eafe4d0e9
.. _05e2202: https://github.com/vprivat-ads/eodag/commit/05e2202b6c3d9426d2d19a2e002460de83f38ae9
.. _05e94a5: https://github.com/vprivat-ads/eodag/commit/05e94a5c534fb4195021f27ad0842046a64d3a33
.. _05f1142: https://github.com/vprivat-ads/eodag/commit/05f114281a3b7b2f56da5b1bc8a5f918e2ed23bd
.. _0625802: https://github.com/vprivat-ads/eodag/commit/0625802e62f5be02560f6b015c65d0643e7cb720
.. _0632e41: https://github.com/vprivat-ads/eodag/commit/0632e4147f26119bea43e0672f6d06e75d216a20
.. _067928e: https://github.com/vprivat-ads/eodag/commit/067928e97f70af2523bcd35df829eaf3465d5043
.. _06c4678: https://github.com/vprivat-ads/eodag/commit/06c4678d1cf18bb16c7d61b21c0255542acf6f33
.. _06dd23d: https://github.com/vprivat-ads/eodag/commit/06dd23d5d2ebb020032972ed77617403de75e31b
.. _0715f05: https://github.com/vprivat-ads/eodag/commit/0715f05176a56cd754170c4471970830b5b31472
.. _072a0f2: https://github.com/vprivat-ads/eodag/commit/072a0f210413b0a4b3c5689762fee498afedab86
.. _072b93e: https://github.com/vprivat-ads/eodag/commit/072b93e48d71a153a22f537f8b60daaea1d49c7a
.. _073a910: https://github.com/vprivat-ads/eodag/commit/073a9103cb50954a8f4c9d4eb4e17390e466256b
.. _076a0f8: https://github.com/vprivat-ads/eodag/commit/076a0f8efe1a1406817bdaa1ffcb446cfded9d56
.. _07a2b79: https://github.com/vprivat-ads/eodag/commit/07a2b79c88fad604d464db9d989abef248484f5a
.. _07a38ac: https://github.com/vprivat-ads/eodag/commit/07a38ace5ee8fd6c759e9325a475ec54ac92e113
.. _07aa48a: https://github.com/vprivat-ads/eodag/commit/07aa48a4eb4b9025df8b47136a6210e49aaa913a
.. _07abe78: https://github.com/vprivat-ads/eodag/commit/07abe78d376a55fa3365b4ed46c7da89448a38ca
.. _07ed6b0: https://github.com/vprivat-ads/eodag/commit/07ed6b06f5953c772c69960e69971badf72974bc
.. _07f484b: https://github.com/vprivat-ads/eodag/commit/07f484bf5799866d75ca8afb6f84765820485c3f
.. _083989e: https://github.com/vprivat-ads/eodag/commit/083989e0d1be8878fa1da2c984c6025bc4a564f0
.. _0852432: https://github.com/vprivat-ads/eodag/commit/08524322b0e2b9feef3ea6a252b29dfb31073766
.. _08a4fbc: https://github.com/vprivat-ads/eodag/commit/08a4fbc858a4deaa69431e923ab7b7355153e582
.. _090c0bd: https://github.com/vprivat-ads/eodag/commit/090c0bdee39041eb9b572112602be9477771a5fe
.. _0929a7c: https://github.com/vprivat-ads/eodag/commit/0929a7c7f883a5c5efcb87b903e2752a6efd789b
.. _094cdb9: https://github.com/vprivat-ads/eodag/commit/094cdb97592302305b00be370b6db88b3c9d9e5e
.. _09a9b79: https://github.com/vprivat-ads/eodag/commit/09a9b79e8b9c9ccb412cb75e6d66de2e39892a05
.. _09e14fe: https://github.com/vprivat-ads/eodag/commit/09e14fe91054bd3a67b572da47f283ea34309b9f
.. _0a3d308: https://github.com/vprivat-ads/eodag/commit/0a3d308f6204f87413d34838ac73dd2dab07ef02
.. _0a4104e: https://github.com/vprivat-ads/eodag/commit/0a4104e0518abc70e2133ca98472eea87d673a1c
.. _0a6208a: https://github.com/vprivat-ads/eodag/commit/0a6208a6e306461fca3f66c1653a41ffda54dfb6
.. _0a66ed9: https://github.com/vprivat-ads/eodag/commit/0a66ed938e37f141b25ed5c3ad9e44ef8ec05fa1
.. _0a782d7: https://github.com/vprivat-ads/eodag/commit/0a782d7f476a993170f7d60c006be09b4cfa2b47
.. _0adf3de: https://github.com/vprivat-ads/eodag/commit/0adf3de6d3792755c2498f51b3b9ce29a3f6038f
.. _0ae4c17: https://github.com/vprivat-ads/eodag/commit/0ae4c170fee95cfb2263c4f1b90a3219d502e819
.. _0af86ad: https://github.com/vprivat-ads/eodag/commit/0af86add7bae03489cff4a14a60d885c1b8aa4ec
.. _0afcc97: https://github.com/vprivat-ads/eodag/commit/0afcc97f30661217d96b4aae4a35ccb2bc63b6cf
.. _0b62dab: https://github.com/vprivat-ads/eodag/commit/0b62dab313803c1655bae1d7afbb5dd5672c240c
.. _0b88c50: https://github.com/vprivat-ads/eodag/commit/0b88c5041ec4d838cad64dbf864185b72325c791
.. _0bfa61d: https://github.com/vprivat-ads/eodag/commit/0bfa61dbe39a0ad7717b820a4fa5a1f8efcf43f9
.. _0c16038: https://github.com/vprivat-ads/eodag/commit/0c1603874f11495dfa9a2340e699059a4f24212a
.. _0c5ed7c: https://github.com/vprivat-ads/eodag/commit/0c5ed7c26200579f951596342dfddf3d214cbb55
.. _0c8d6c8: https://github.com/vprivat-ads/eodag/commit/0c8d6c8a1f4426d441d3ed7d33b61889219ce1ac
.. _0c9b55f: https://github.com/vprivat-ads/eodag/commit/0c9b55fb1685f51e72a8c35d60b6e6c02ddd5365
.. _0cacf05: https://github.com/vprivat-ads/eodag/commit/0cacf05d65f2afb1663cf0919aa2384ef5a5399e
.. _0d42f00: https://github.com/vprivat-ads/eodag/commit/0d42f00e9c237188c0ffc7de8aad3b5a0a37a6ae
.. _0d454f9: https://github.com/vprivat-ads/eodag/commit/0d454f9718b5449b9693c184517728c0dd070083
.. _0d7ff3c: https://github.com/vprivat-ads/eodag/commit/0d7ff3cf9fb348fd2c6d7cc40d9307791fb3325d
.. _0d90d9e: https://github.com/vprivat-ads/eodag/commit/0d90d9e40345cfaaf6733f0215b7e1d873e2be12
.. _0dc0ba0: https://github.com/vprivat-ads/eodag/commit/0dc0ba05eb4db2b5298e8de50d702e33ceae4aee
.. _0dcc36d: https://github.com/vprivat-ads/eodag/commit/0dcc36d255600669d69fd757f7af6d20e5a4faf1
.. _0deebef: https://github.com/vprivat-ads/eodag/commit/0deebefa2631c0649e990e813b67e54150637eda
.. _0e11b56: https://github.com/vprivat-ads/eodag/commit/0e11b5665e2a8f9a2d06c66e8e791d04b6134331
.. _0e511e7: https://github.com/vprivat-ads/eodag/commit/0e511e763f3fda98c0aea4b64f3091582e572d18
.. _0f094d5: https://github.com/vprivat-ads/eodag/commit/0f094d51424e293557348c3740db8da6f3ab54d4
.. _0f20c0a: https://github.com/vprivat-ads/eodag/commit/0f20c0a7b85b165c31eeb4ab558ddfff8b479f94
.. _0f3b23e: https://github.com/vprivat-ads/eodag/commit/0f3b23e30e2160f1a551ba8ef8c1d7f353b577b3
.. _0f70077: https://github.com/vprivat-ads/eodag/commit/0f700776ba303783ecf9eb3df24f73777698615a
.. _0fed963: https://github.com/vprivat-ads/eodag/commit/0fed9630f1965e804bad4364e5a920bec8414e62
.. _0ff477d: https://github.com/vprivat-ads/eodag/commit/0ff477d7a685896fa9d5dc2280fe925b1c269cf5
.. _106a9e0: https://github.com/vprivat-ads/eodag/commit/106a9e0940f4c19133db6293d7a74d2360f5d7f9
.. _10923f0: https://github.com/vprivat-ads/eodag/commit/10923f000ede40a4bd826c2df71007a7b7d273ac
.. _10c7b12: https://github.com/vprivat-ads/eodag/commit/10c7b129002d5e7a8a5d8ff3df4cd6886c8fde9b
.. _115e53c: https://github.com/vprivat-ads/eodag/commit/115e53c387d4514004a18f92552d94e640cfb3eb
.. _11a6c14: https://github.com/vprivat-ads/eodag/commit/11a6c14378b0f02b8708b38ce7bc68a984beb4ce
.. _11f2318: https://github.com/vprivat-ads/eodag/commit/11f2318a150982504226378110b853ca4aa644ce
.. _1275815: https://github.com/vprivat-ads/eodag/commit/1275815cb54449ff7f6cf671199ace2820c174e6
.. _127b346: https://github.com/vprivat-ads/eodag/commit/127b346ee024c7e23884f5887a8c9d9e1b41b0c9
.. _127e035: https://github.com/vprivat-ads/eodag/commit/127e035620f1c2f97c6f7d0d7d7d7dd973ab9340
.. _1281268: https://github.com/vprivat-ads/eodag/commit/1281268507c3a7338be9954b403a20d5156bc527
.. _1294ddd: https://github.com/vprivat-ads/eodag/commit/1294dddaecebf87312e368e1111f21aee6b016ac
.. _132ff00: https://github.com/vprivat-ads/eodag/commit/132ff0000d874992fab84de4abeb602f254d7264
.. _1339844: https://github.com/vprivat-ads/eodag/commit/1339844dd6fe8f882dcb90242b9736094e3830fc
.. _139d22a: https://github.com/vprivat-ads/eodag/commit/139d22a7b141131418504ea91d50c308498a8f5c
.. _139f5c6: https://github.com/vprivat-ads/eodag/commit/139f5c620c09c309e5e260f635b76ae2f3ff7873
.. _13c177b: https://github.com/vprivat-ads/eodag/commit/13c177bb5d2caaf7e88f0d01d06d541a61237749
.. _13d3a73: https://github.com/vprivat-ads/eodag/commit/13d3a7323616b0007108bd3b865e4a220f8880bc
.. _1405661: https://github.com/vprivat-ads/eodag/commit/1405661aa2daca57f98399cc3b1c763b418e9429
.. _14500e9: https://github.com/vprivat-ads/eodag/commit/14500e9e5f8844fcf2efbc4ce2fbfc5ef338f5d8
.. _149b4e5: https://github.com/vprivat-ads/eodag/commit/149b4e5b1ec8a70b54d07c4edef1d8e151d24508
.. _14c9504: https://github.com/vprivat-ads/eodag/commit/14c9504aaae0a64444e084c82e9640dad6ca4709
.. _14ece44: https://github.com/vprivat-ads/eodag/commit/14ece4499ce50e2edd366de18d9b49a1e23f7486
.. _1513d9c: https://github.com/vprivat-ads/eodag/commit/1513d9c623210aac53b65cfef9f8024117d0bdf7
.. _154ea6d: https://github.com/vprivat-ads/eodag/commit/154ea6d035572e64c3a434bb41c095c9b4cc76b2
.. _154fe2e: https://github.com/vprivat-ads/eodag/commit/154fe2e0825a8cb2889717662d007ffc6490a084
.. _158fac8: https://github.com/vprivat-ads/eodag/commit/158fac82232af978700e8f829bd5b7e227774a4c
.. _1596872: https://github.com/vprivat-ads/eodag/commit/1596872284f30017553110d9fd43de9995ae2760
.. _15dbcb1: https://github.com/vprivat-ads/eodag/commit/15dbcb17b14becdce57087fdba5b60adeb4a7551
.. _1631c88: https://github.com/vprivat-ads/eodag/commit/1631c888351605a5fbbc4a60334aada0b8462b6c
.. _16619f2: https://github.com/vprivat-ads/eodag/commit/16619f23e16bcc72fad0ba5cbd7d0999c90ceb3b
.. _16a7f51: https://github.com/vprivat-ads/eodag/commit/16a7f51110a7bf82f6986008634125e6ea9dd1a5
.. _16cdf28: https://github.com/vprivat-ads/eodag/commit/16cdf28dd29f038e15fc97e91b1ccde0fe5f1354
.. _17244d7: https://github.com/vprivat-ads/eodag/commit/17244d76f607dd2cf6ba2079e37241dbfeb819c4
.. _1737390: https://github.com/vprivat-ads/eodag/commit/1737390b3b9df60321e50cf4f4a9b46ca8f31506
.. _175e167: https://github.com/vprivat-ads/eodag/commit/175e167d429556d9a5914312d6ae54336bb8a2ae
.. _176ac95: https://github.com/vprivat-ads/eodag/commit/176ac95fce669078c0ba5e6b1035fec619280598
.. _177d771: https://github.com/vprivat-ads/eodag/commit/177d77120e1c5bda5c84af638bdaa49a07edf5f4
.. _17a6cbb: https://github.com/vprivat-ads/eodag/commit/17a6cbbaa0bff042eace060a4e6d269a2a9b1efd
.. _17c23a4: https://github.com/vprivat-ads/eodag/commit/17c23a44f72429c0ec931db16eeaf10cc916bf3d
.. _17ca92f: https://github.com/vprivat-ads/eodag/commit/17ca92f79dc2f580c05b25b947d87ea16563b7cc
.. _17e68c2: https://github.com/vprivat-ads/eodag/commit/17e68c2a45700ff8ab1d3de156d629dbf9a080a5
.. _182cdc0: https://github.com/vprivat-ads/eodag/commit/182cdc0eb82e7e4ca9e073b12edf6c3e51952d39
.. _1888f5f: https://github.com/vprivat-ads/eodag/commit/1888f5fc9f75301a836e1a8c15a29bea7bef167a
.. _1891f4b: https://github.com/vprivat-ads/eodag/commit/1891f4b3ff7554ebe04c7ee9fa2a5af5de407753
.. _18ab40f: https://github.com/vprivat-ads/eodag/commit/18ab40f929d71709733bbaf603b7665352c88952
.. _18b22d5: https://github.com/vprivat-ads/eodag/commit/18b22d5677bd39c14ed22369d4956df69b5281dc
.. _18d93f6: https://github.com/vprivat-ads/eodag/commit/18d93f6fffef5f84d5fdec8d4342d6f98c8290fe
.. _1948645: https://github.com/vprivat-ads/eodag/commit/19486454af9784ea80313d7ace6357601a47ddee
.. _19d7d6b: https://github.com/vprivat-ads/eodag/commit/19d7d6b21f378d8eb4566e4887bbf21b6fca0538
.. _19e0d05: https://github.com/vprivat-ads/eodag/commit/19e0d05fea41921d431b3a46eed83b875c8ac6e3
.. _1a0e007: https://github.com/vprivat-ads/eodag/commit/1a0e007d5364fd65c246e95ab7d9d591d69bde3e
.. _1a0ff44: https://github.com/vprivat-ads/eodag/commit/1a0ff440607dc92e519e6ba43d9c868679c720b3
.. _1a23ff3: https://github.com/vprivat-ads/eodag/commit/1a23ff314acaee053c6454e36c8a7d6a8466ba36
.. _1a38d08: https://github.com/vprivat-ads/eodag/commit/1a38d085d1839a4c46b6a66bde32ced31d7ce60f
.. _1a627c7: https://github.com/vprivat-ads/eodag/commit/1a627c704f3e984d1a3f94b78cbccab91b83cd85
.. _1a8ac9c: https://github.com/vprivat-ads/eodag/commit/1a8ac9cf8fd0c4528ed311924eea2e4fb39a0098
.. _1a9d488: https://github.com/vprivat-ads/eodag/commit/1a9d4887a081cf43d2c0e309ffdc6ef843f2c64d
.. _1aa6a98: https://github.com/vprivat-ads/eodag/commit/1aa6a98648c12e27bfb1bea936c03e855a7db0b2
.. _1ad5afe: https://github.com/vprivat-ads/eodag/commit/1ad5afead302158d87a243396ff7bd96451eb995
.. _1af3d19: https://github.com/vprivat-ads/eodag/commit/1af3d19486b88be5758ffc7277ccf4237fc1acae
.. _1b17b4a: https://github.com/vprivat-ads/eodag/commit/1b17b4af5f898ed608dd132e49477d28466f9451
.. _1b3f312: https://github.com/vprivat-ads/eodag/commit/1b3f312c386356431f705a9fac56b1581ef4aada
.. _1bbfaab: https://github.com/vprivat-ads/eodag/commit/1bbfaab095a0e0bf4b5b68f9130fa57d37614f0f
.. _1bdf8a9: https://github.com/vprivat-ads/eodag/commit/1bdf8a9544717533f6ea85c7fc86f27b226a8f0f
.. _1c072f8: https://github.com/vprivat-ads/eodag/commit/1c072f8f857f24e08642c1cb6ddaff51fe26e52d
.. _1c7edf6: https://github.com/vprivat-ads/eodag/commit/1c7edf6d8ab8506d2ad186ac51e3bce62515aa74
.. _1c91533: https://github.com/vprivat-ads/eodag/commit/1c915335fcf7a9070c2991f230309f454d74f1bf
.. _1cd1b46: https://github.com/vprivat-ads/eodag/commit/1cd1b4671c4691e6d4e783933d377aca29fe3f2c
.. _1d00fe3: https://github.com/vprivat-ads/eodag/commit/1d00fe3cca8f8c0d908739c3f5b1e543d1785d7d
.. _1d3070f: https://github.com/vprivat-ads/eodag/commit/1d3070f0aca2f34e091d46195694175889ee0e78
.. _1d49715: https://github.com/vprivat-ads/eodag/commit/1d4971560e9b789dfe96ca09b2fcd5d88cb4e30a
.. _1d9f92c: https://github.com/vprivat-ads/eodag/commit/1d9f92c563508322dd3b943845f8530087753cfa
.. _1e049ee: https://github.com/vprivat-ads/eodag/commit/1e049ee4c4a23e656de8794b46ff11f58a36242a
.. _1e0d894: https://github.com/vprivat-ads/eodag/commit/1e0d894920e8bb553d6370c64c6fa180cf94fc27
.. _1e37edc: https://github.com/vprivat-ads/eodag/commit/1e37edccf2c266768884076d0178dc0d71c7434d
.. _1e42221: https://github.com/vprivat-ads/eodag/commit/1e422214aa717c3a050d255c3dd81f4871480522
.. _1e7247f: https://github.com/vprivat-ads/eodag/commit/1e7247fb749ce0b69fb5ee59591b4b24b2d72140
.. _1fa56a3: https://github.com/vprivat-ads/eodag/commit/1fa56a3fb66de0035db14cd82b30e86d82f495a9
.. _1fb0807: https://github.com/vprivat-ads/eodag/commit/1fb08074c6fc68a389142655065b5a9850b67cf1
.. _203665d: https://github.com/vprivat-ads/eodag/commit/203665ddf68268b299782a98d75db15d747558dc
.. _2043582: https://github.com/vprivat-ads/eodag/commit/2043582f60cfe67462323eed374a0965cd5f1911
.. _2086412: https://github.com/vprivat-ads/eodag/commit/2086412c7056207c6f082431883f4227a749aa67
.. _208c114: https://github.com/vprivat-ads/eodag/commit/208c114843d9c1422eb26acc0abf27d99ff945e7
.. _20c5cbf: https://github.com/vprivat-ads/eodag/commit/20c5cbfe64076e8e92c5f71536a777ebea8a1568
.. _20e0ef7: https://github.com/vprivat-ads/eodag/commit/20e0ef7d066b278ad2f068e1f65998c5549fdaf0
.. _211bdfd: https://github.com/vprivat-ads/eodag/commit/211bdfdd48ac3bd8e9607c98b3d582aa39636be0
.. _2140d9d: https://github.com/vprivat-ads/eodag/commit/2140d9dce4808d6d5f1ecc70439c0cd11fcd1a60
.. _216612f: https://github.com/vprivat-ads/eodag/commit/216612f52440a273cf4fb9f9e7bb893c85e5d2bf
.. _216edc2: https://github.com/vprivat-ads/eodag/commit/216edc2a7e22676ecfcbc77b71795fc319cb3dc4
.. _219e669: https://github.com/vprivat-ads/eodag/commit/219e669fa6e8bbbfa96357b21b964dd53c445233
.. _21a2dae: https://github.com/vprivat-ads/eodag/commit/21a2dae43674fa1d751e21d20068bd6973684fa9
.. _21b6708: https://github.com/vprivat-ads/eodag/commit/21b67083ba26357877083d4d1dd330c33c42697b
.. _21ca0e5: https://github.com/vprivat-ads/eodag/commit/21ca0e5281f01a6330d72c50356fe099fe2facb7
.. _22b7e1f: https://github.com/vprivat-ads/eodag/commit/22b7e1f72147f8aa14f9193a9819d49be30eb535
.. _22e74b8: https://github.com/vprivat-ads/eodag/commit/22e74b88142eb7fc85ae0b9e40e10eef2171d649
.. _22f02d8: https://github.com/vprivat-ads/eodag/commit/22f02d89ed490ed91add246755a5548faf41bc57
.. _23af1f0: https://github.com/vprivat-ads/eodag/commit/23af1f0e8f4247e5ad3a1b88f0440685180f40fe
.. _23e1e54: https://github.com/vprivat-ads/eodag/commit/23e1e54cbd42af5c72a2e96ab2e5a8cfa2f65388
.. _2441b63: https://github.com/vprivat-ads/eodag/commit/2441b6392135501c0f215d031b94c5537b5d4e05
.. _2473ac1: https://github.com/vprivat-ads/eodag/commit/2473ac169a3d05f04f83d4f227c2fb63689ae2d6
.. _247beb9: https://github.com/vprivat-ads/eodag/commit/247beb9f64e59b33bddc63c0f29a86e68bc24985
.. _248990a: https://github.com/vprivat-ads/eodag/commit/248990abf57214a70e853006b784934e7f2f7037
.. _2500af7: https://github.com/vprivat-ads/eodag/commit/2500af7753cbbc1cfe6d315ea3247aebf6299859
.. _2546986: https://github.com/vprivat-ads/eodag/commit/2546986ae6d53627854acae0576609805141030a
.. _257eda4: https://github.com/vprivat-ads/eodag/commit/257eda49272de8919f938083a81add9a34ef15c6
.. _25d029a: https://github.com/vprivat-ads/eodag/commit/25d029aad616213e10feec63e25dfdc2dc564275
.. _2658e69: https://github.com/vprivat-ads/eodag/commit/2658e6983f64581f2364647993c4c0e6bc7bc841
.. _266471b: https://github.com/vprivat-ads/eodag/commit/266471b676289ad532818986843478cac5765337
.. _270e752: https://github.com/vprivat-ads/eodag/commit/270e75200d3dea75e28f84005bd2bcdafe8ba6b2
.. _270f673: https://github.com/vprivat-ads/eodag/commit/270f673d0a33cb3012ed1f61e02a0e444892299d
.. _274280a: https://github.com/vprivat-ads/eodag/commit/274280ae3b5df1fe7eac792d57192e633879dbcd
.. _274b6b9: https://github.com/vprivat-ads/eodag/commit/274b6b9083d946bd98709ec44aa3409078bfe284
.. _277b1e1: https://github.com/vprivat-ads/eodag/commit/277b1e1d4aefdcf06652e592ff7d82992b9647c8
.. _277b63b: https://github.com/vprivat-ads/eodag/commit/277b63b7b9e69104e92ae0cc4bf7b055d5d4b642
.. _279dad6: https://github.com/vprivat-ads/eodag/commit/279dad6968c9925bb03592eae00358eacb7a7193
.. _27b1ab2: https://github.com/vprivat-ads/eodag/commit/27b1ab2174e9855323db26975ab347699f5d60cd
.. _27b2db2: https://github.com/vprivat-ads/eodag/commit/27b2db249b9e66ce41e86f8e03ebb9e8ff27630d
.. _27f41ae: https://github.com/vprivat-ads/eodag/commit/27f41aed5ecb3499649aed1f3b4211ae1bee7a1b
.. _28073e8: https://github.com/vprivat-ads/eodag/commit/28073e8808184f9a9241a032d73607fb79977201
.. _2838ac4: https://github.com/vprivat-ads/eodag/commit/2838ac480451cc2210ba91312b9b7351ee2fbb7c
.. _283b759: https://github.com/vprivat-ads/eodag/commit/283b75903ce67203fcf59fab36887d71fda4939d
.. _2841f58: https://github.com/vprivat-ads/eodag/commit/2841f58862cca114d497ef8fa64a3c6b23ed5c84
.. _28c0bd0: https://github.com/vprivat-ads/eodag/commit/28c0bd0b3fc8cdf96ff5c199773f00658c2c8bfb
.. _28d9ae7: https://github.com/vprivat-ads/eodag/commit/28d9ae7aa9f69a290f92de86814b9ac39be0fe49
.. _2937f61: https://github.com/vprivat-ads/eodag/commit/2937f61124df06991f869a16798a0659c86cf705
.. _29642e8: https://github.com/vprivat-ads/eodag/commit/29642e87614b44ec3b544732ef6496ae8bf73087
.. _298f941: https://github.com/vprivat-ads/eodag/commit/298f941abfb9bc89f7636884039c034c5465f316
.. _29b824e: https://github.com/vprivat-ads/eodag/commit/29b824ea55145a2974747525156b26aa7e47fa0a
.. _29c1474: https://github.com/vprivat-ads/eodag/commit/29c1474e5016cd8158c890ec5210af2062c73a49
.. _29e4d99: https://github.com/vprivat-ads/eodag/commit/29e4d992b7b838033651297dc0e483df221da5f9
.. _2a18716: https://github.com/vprivat-ads/eodag/commit/2a18716339ef7ec5f8b3f3fe001e13aac1d35394
.. _2a238ed: https://github.com/vprivat-ads/eodag/commit/2a238edb621ce17eb99ae98fe28ad3fa56793ade
.. _2a318e7: https://github.com/vprivat-ads/eodag/commit/2a318e7ca5c696296a0ab9b68a5343a28ed10f77
.. _2a5d405: https://github.com/vprivat-ads/eodag/commit/2a5d4052c360be9b7109ca570209c46f533b58c5
.. _2a8e683: https://github.com/vprivat-ads/eodag/commit/2a8e683aedde62a610a499f04fed101bdae230e0
.. _2af2d90: https://github.com/vprivat-ads/eodag/commit/2af2d90a17d990a6fb3dbd79d679720df7742c56
.. _2b11eee: https://github.com/vprivat-ads/eodag/commit/2b11eee3de71cae9f49e910f8b3a3c1d43ffaf08
.. _2b33dfc: https://github.com/vprivat-ads/eodag/commit/2b33dfc605c411169002ab3c5d637c3b5b247c07
.. _2b94fd0: https://github.com/vprivat-ads/eodag/commit/2b94fd045ca720efc7fd0f8d54817f231b4972a7
.. _2bb99ba: https://github.com/vprivat-ads/eodag/commit/2bb99babf59ec2b7cf60a05148f20217ba6bfac9
.. _2bc623f: https://github.com/vprivat-ads/eodag/commit/2bc623f65dd4b2d07a687c40b7d8843a1678b51f
.. _2c0e690: https://github.com/vprivat-ads/eodag/commit/2c0e69045f7edeee7a63f29eff9601a19933707c
.. _2c26978: https://github.com/vprivat-ads/eodag/commit/2c269784bc329e88dc4e3477b12fc4eadc475831
.. _2c37db3: https://github.com/vprivat-ads/eodag/commit/2c37db30b5cd2e908bf3231f589debac7def11be
.. _2c5a0e0: https://github.com/vprivat-ads/eodag/commit/2c5a0e07593f15a264e8658e3bd91e4768f3865e
.. _2c7e575: https://github.com/vprivat-ads/eodag/commit/2c7e575421a815121f97332a273177e6ec124444
.. _2cba529: https://github.com/vprivat-ads/eodag/commit/2cba529db09de3aa96db757e1afddd1a1c483ebb
.. _2ceef7c: https://github.com/vprivat-ads/eodag/commit/2ceef7c14d699c4f9d919147410324ad0d2a4e10
.. _2d3f6da: https://github.com/vprivat-ads/eodag/commit/2d3f6dac273cb70f55dfa9eb3c898266a4c93552
.. _2d8cec2: https://github.com/vprivat-ads/eodag/commit/2d8cec2f6c3a1d7d23c6df6709cb0e3f18780548
.. _2dbab73: https://github.com/vprivat-ads/eodag/commit/2dbab735019e3b56278caa2abc84baacd3523e71
.. _2ddca49: https://github.com/vprivat-ads/eodag/commit/2ddca49329c26796957ec7a957e1fde15ab6e174
.. _2df5db5: https://github.com/vprivat-ads/eodag/commit/2df5db5e33ec42dd09c66a5a50ef1692866a7532
.. _2e12639: https://github.com/vprivat-ads/eodag/commit/2e126398a399e83542ad3a557f5aba43da4681eb
.. _2eb52b8: https://github.com/vprivat-ads/eodag/commit/2eb52b8300e3859712c74412a97d15181865ce97
.. _2ec4edb: https://github.com/vprivat-ads/eodag/commit/2ec4edb0bf37f2030b349e7fe82fe51e8faa0a53
.. _2ed579c: https://github.com/vprivat-ads/eodag/commit/2ed579c55521978ff07e8e9fefed095b24101d1f
.. _2ef1ad1: https://github.com/vprivat-ads/eodag/commit/2ef1ad1bbf78482abf284c3dc90449fc43afca41
.. _2efa9e9: https://github.com/vprivat-ads/eodag/commit/2efa9e903023db01ce0176fe1328e9fd4116482c
.. _2f6ebe8: https://github.com/vprivat-ads/eodag/commit/2f6ebe8be618de9538288f2ce17fe6c7f85c0c8b
.. _2fc3f27: https://github.com/vprivat-ads/eodag/commit/2fc3f278ee6f4843f8aea66122f96bd8ccd97fba
.. _2fc91a9: https://github.com/vprivat-ads/eodag/commit/2fc91a9fde63fc221fb23ddceb58aeaac170ecab
.. _2ff150a: https://github.com/vprivat-ads/eodag/commit/2ff150a4e8274569d0baa0780ed6a6a750e64e35
.. _2ff5763: https://github.com/vprivat-ads/eodag/commit/2ff576397ad2ca5d8a839e6a0d478689ecea6b72
.. _300a2f8: https://github.com/vprivat-ads/eodag/commit/300a2f8c3f5a5b80064b31865c8929c6d4604e48
.. _3018325: https://github.com/vprivat-ads/eodag/commit/3018325990359f1f8092f434d36d138eb3f787da
.. _30306e5: https://github.com/vprivat-ads/eodag/commit/30306e52f403e7471b37ed22e9c606c718f40f5f
.. _304446b: https://github.com/vprivat-ads/eodag/commit/304446bccecc4c41f07e0f329df699dbbd8ee49a
.. _3061402: https://github.com/vprivat-ads/eodag/commit/3061402971d6faf72978d390707cc247d22bcee8
.. _308e0a9: https://github.com/vprivat-ads/eodag/commit/308e0a9884d4b2e3435922c89a23cc0aab1edab9
.. _3099b2a: https://github.com/vprivat-ads/eodag/commit/3099b2a897480236598cf6fc36b4c1518fc04160
.. _30b5554: https://github.com/vprivat-ads/eodag/commit/30b5554d96c58a0aca53849bd38db80902823bdf
.. _30c3c4a: https://github.com/vprivat-ads/eodag/commit/30c3c4a6eb7cffc18586984e3ed3dbc33deb3fc7
.. _31ca3eb: https://github.com/vprivat-ads/eodag/commit/31ca3eb878b7585310898d409f7293391b8196dc
.. _31f3c8a: https://github.com/vprivat-ads/eodag/commit/31f3c8a50b251cc2ad2d567fb6f1eb62937b5d43
.. _324bc80: https://github.com/vprivat-ads/eodag/commit/324bc80ddcbd1e4450f49dc93585deec41aac702
.. _32b26dc: https://github.com/vprivat-ads/eodag/commit/32b26dc2fd84e68157ed50c261463390a514a44e
.. _32c2654: https://github.com/vprivat-ads/eodag/commit/32c2654aab6a70776703437eb8e8729d78fc18d7
.. _3309501: https://github.com/vprivat-ads/eodag/commit/3309501ac8391d09a4151dff4113dccaa6fa5d36
.. _3316c4f: https://github.com/vprivat-ads/eodag/commit/3316c4fcff8790e27316112a25ebabf2a5f88021
.. _3323b91: https://github.com/vprivat-ads/eodag/commit/3323b919ac264ea3c070bcb6ff9ceab719560ed2
.. _3371426: https://github.com/vprivat-ads/eodag/commit/3371426f4f814d78817771feea718c91c09764a5
.. _3465afe: https://github.com/vprivat-ads/eodag/commit/3465afe00a492e73bfd517f19c409ba21196f85f
.. _348e066: https://github.com/vprivat-ads/eodag/commit/348e066156d7078c7da5c36c9829f7885c8ef34f
.. _34c41ac: https://github.com/vprivat-ads/eodag/commit/34c41ac9396dab0bce9b76f1f9244ed67d726701
.. _3506dfb: https://github.com/vprivat-ads/eodag/commit/3506dfbdfa6520c18d9a94fdcd361cf77b59a97c
.. _351e378: https://github.com/vprivat-ads/eodag/commit/351e37851a4891942305ca32210f8c41c043bc41
.. _3543a40: https://github.com/vprivat-ads/eodag/commit/3543a40873c344242aec3cc9b719b9f1bf033462
.. _35949ce: https://github.com/vprivat-ads/eodag/commit/35949cefd3a871297fd85ae8de64448ed0949cc6
.. _3602426: https://github.com/vprivat-ads/eodag/commit/360242653ddc2a5c8587b37b3d91800459f4c243
.. _362055e: https://github.com/vprivat-ads/eodag/commit/362055e3ec7e651eaa2358dbac083a476ede7a43
.. _3662954: https://github.com/vprivat-ads/eodag/commit/3662954cf31dd91dc79d740686e6557c9cbf7954
.. _3675690: https://github.com/vprivat-ads/eodag/commit/3675690e04813de6b9402f0028277c091d0e51b0
.. _36870f9: https://github.com/vprivat-ads/eodag/commit/36870f9f3b613bf35ef5ce9c12350a0820a68433
.. _3696fc8: https://github.com/vprivat-ads/eodag/commit/3696fc842f925303dc6947c61aafea15dda1460e
.. _36fd6ae: https://github.com/vprivat-ads/eodag/commit/36fd6aed8eda0964ccc6dc48d560d5f686d5bd5f
.. _372afbe: https://github.com/vprivat-ads/eodag/commit/372afbec3333e5538d9ac91cba2491d087b69a64
.. _3769147: https://github.com/vprivat-ads/eodag/commit/37691478ab3e818695f84fb484d91ee85a77fa8f
.. _378694c: https://github.com/vprivat-ads/eodag/commit/378694cd2c084cb748ddb99d8b36c48add119232
.. _37af691: https://github.com/vprivat-ads/eodag/commit/37af69194d80522884cb5108ca85487b40255b03
.. _37eb4e5: https://github.com/vprivat-ads/eodag/commit/37eb4e53a97ceecb5189d87f14556c1bac4b2aab
.. _380ce3f: https://github.com/vprivat-ads/eodag/commit/380ce3fc5fc744c250952e81ccc58688faaffd15
.. _389bae3: https://github.com/vprivat-ads/eodag/commit/389bae3a525001d7817471b686f0b49a1ef8bafc
.. _39308ae: https://github.com/vprivat-ads/eodag/commit/39308ae78fae7bf96c30552cf12543bd9f0b6009
.. _3945ddd: https://github.com/vprivat-ads/eodag/commit/3945ddd15a94266dfe79a0c89ed16d09fec179b7
.. _3963758: https://github.com/vprivat-ads/eodag/commit/3963758fc5fda86da4799a26eb64fbc610c444da
.. _39d0962: https://github.com/vprivat-ads/eodag/commit/39d096283e504c2c43eaadc039250a295edd6ac9
.. _3a2babe: https://github.com/vprivat-ads/eodag/commit/3a2babe5453fbbc41c5625e31d9628fd9275577f
.. _3a645b6: https://github.com/vprivat-ads/eodag/commit/3a645b694364307a92745193109a6ab76cde2744
.. _3a90ea3: https://github.com/vprivat-ads/eodag/commit/3a90ea384a07297d4889ccbf6187a15ba88e19d4
.. _3a9ac6e: https://github.com/vprivat-ads/eodag/commit/3a9ac6e4666257b643e9bd544c8b4ec8d1fa7b5f
.. _3b04096: https://github.com/vprivat-ads/eodag/commit/3b04096ac6255f89c8eb8bb363a2b38ece1b02af
.. _3b749e2: https://github.com/vprivat-ads/eodag/commit/3b749e2b64f4c828f9562de7211df19ae7967736
.. _3b8ca8d: https://github.com/vprivat-ads/eodag/commit/3b8ca8d191dc98479dd2be3a9e53ec79d6c0be32
.. _3b9eb8c: https://github.com/vprivat-ads/eodag/commit/3b9eb8cfec74a0ca054480c806263c2e3e9433ca
.. _3bcdd79: https://github.com/vprivat-ads/eodag/commit/3bcdd7933cf1d42b4616c9c71aba65c564448018
.. _3bd7a5c: https://github.com/vprivat-ads/eodag/commit/3bd7a5c486f28c104964d7ca11c222a5a4d9132f
.. _3c2fcc7: https://github.com/vprivat-ads/eodag/commit/3c2fcc704ba577725af86335fe0bbf5b15ac9739
.. _3c4ca8a: https://github.com/vprivat-ads/eodag/commit/3c4ca8af92d257921500fb5e920a53aae947b398
.. _3c7424c: https://github.com/vprivat-ads/eodag/commit/3c7424c81cf70e4f430305a63cb0e22096c7b9cd
.. _3c7598b: https://github.com/vprivat-ads/eodag/commit/3c7598b22ba9e3de1c6ed901455b42b65179e5d9
.. _3c7b74b: https://github.com/vprivat-ads/eodag/commit/3c7b74bbc2efc05d7cb77e37df64cd0c8e1f3d44
.. _3cb6ca9: https://github.com/vprivat-ads/eodag/commit/3cb6ca9f12bae3cbf2013dc2f1cb60399ada0eb9
.. _3cc1d7c: https://github.com/vprivat-ads/eodag/commit/3cc1d7c85e140f03358990b3652d8c56d19e0321
.. _3cdbd4c: https://github.com/vprivat-ads/eodag/commit/3cdbd4c6ea77a25f85c6fac3314a22bf1c5a2cd1
.. _3ce721d: https://github.com/vprivat-ads/eodag/commit/3ce721d84aae3c0d090173669419c5c6448dca4c
.. _3e1ccd4: https://github.com/vprivat-ads/eodag/commit/3e1ccd42570453d1e8bea9c26c74ee767ded3d57
.. _3e5834f: https://github.com/vprivat-ads/eodag/commit/3e5834f1995ba7129aaad3c3742e38bbde2b927c
.. _3e9ec56: https://github.com/vprivat-ads/eodag/commit/3e9ec56d1e0e83bc1bd00244f1ad9af7be3c44af
.. _3ebb060: https://github.com/vprivat-ads/eodag/commit/3ebb060803399ff75fcd0dd0223039a5d2f46c06
.. _3ebcffd: https://github.com/vprivat-ads/eodag/commit/3ebcffd20dddb912d095e954a31efee7ca7931e9
.. _3efcf4c: https://github.com/vprivat-ads/eodag/commit/3efcf4ca6238c96788d130ddf2faed840158063a
.. _3f08774: https://github.com/vprivat-ads/eodag/commit/3f08774f80bc49f3dc50457a3ba0ffeb90c3be75
.. _3f0f2cd: https://github.com/vprivat-ads/eodag/commit/3f0f2cd2d54301b004fc8958cd369d93941d4c2a
.. _3f39f6c: https://github.com/vprivat-ads/eodag/commit/3f39f6cf0565cf11b13d0fa293e0a10d7d9ef8f9
.. _3f8c56a: https://github.com/vprivat-ads/eodag/commit/3f8c56a170d750295e0a708cd91b627d15a2408a
.. _4061b78: https://github.com/vprivat-ads/eodag/commit/4061b78f61f798a123dd4efc79fa5ba3718a71e3
.. _40915e0: https://github.com/vprivat-ads/eodag/commit/40915e031b4b5db2eda508fb71e5058d2a256bff
.. _40fe987: https://github.com/vprivat-ads/eodag/commit/40fe987ec3a0644e660653a7a330dbaefca9d610
.. _414f84e: https://github.com/vprivat-ads/eodag/commit/414f84eb1308688503053f47dde9c64f55d7c16f
.. _4156fda: https://github.com/vprivat-ads/eodag/commit/4156fdac38c8510115019fa0515646cfc3974c44
.. _418da7c: https://github.com/vprivat-ads/eodag/commit/418da7cc9fa0d19aaaf4b9a3b3a56db404e61bf7
.. _419956b: https://github.com/vprivat-ads/eodag/commit/419956b422a96a3aa4f92962aa19143f46ac61e6
.. _41c2fc4: https://github.com/vprivat-ads/eodag/commit/41c2fc4735df6b4498a5333dc13007ece279afce
.. _4233b05: https://github.com/vprivat-ads/eodag/commit/4233b05b1f9ed5de5c4d0bb8d9ea4610f711c3b9
.. _425e44c: https://github.com/vprivat-ads/eodag/commit/425e44c08aca1ebca8d5e4d342c40e90c3f6f7b2
.. _4286d13: https://github.com/vprivat-ads/eodag/commit/4286d132c8500c968a82445c2e3509216c4a1e65
.. _42de3d8: https://github.com/vprivat-ads/eodag/commit/42de3d8038269acbe282a2d9b2c93cd7e5ae316a
.. _42f77a3: https://github.com/vprivat-ads/eodag/commit/42f77a3ad154408150fa3ff48f1e18944752607d
.. _430592a: https://github.com/vprivat-ads/eodag/commit/430592a941773e6886a72d9bfcd7d7e2d72be8b9
.. _431c47c: https://github.com/vprivat-ads/eodag/commit/431c47c78e631508409120e8b13484721641c30f
.. _4358ae6: https://github.com/vprivat-ads/eodag/commit/4358ae622fce7b33bad5b6746290d6866cf3e4c1
.. _43ab2c0: https://github.com/vprivat-ads/eodag/commit/43ab2c0ff070ea049d77db82e5048c83a869ce6e
.. _43d9fb4: https://github.com/vprivat-ads/eodag/commit/43d9fb442a8f33ab94873be251b230d1838d01c8
.. _44172e0: https://github.com/vprivat-ads/eodag/commit/44172e0d23c14cad53c4b8a038d99ea827646f96
.. _441cefa: https://github.com/vprivat-ads/eodag/commit/441cefac33c8d93ee4ae8d596732fe24618faaf8
.. _445a20e: https://github.com/vprivat-ads/eodag/commit/445a20e060730642e703615c73225c0df3cc84d0
.. _44ca6ff: https://github.com/vprivat-ads/eodag/commit/44ca6ff43264827e50356414fb130f2fec8d8e57
.. _44d725e: https://github.com/vprivat-ads/eodag/commit/44d725e9923549c1af8c57527fdb3372abe91aa0
.. _4559f41: https://github.com/vprivat-ads/eodag/commit/4559f4198654338e99736046ed424612d50106be
.. _45a1f08: https://github.com/vprivat-ads/eodag/commit/45a1f086e8ca083a378c951ecaf5513072891565
.. _45b4ca5: https://github.com/vprivat-ads/eodag/commit/45b4ca50c6cf866286530ccd712634d4a166ddee
.. _45b891a: https://github.com/vprivat-ads/eodag/commit/45b891a6a527e0143eb23cfa1a9576cd74a56758
.. _45c1aa7: https://github.com/vprivat-ads/eodag/commit/45c1aa778974a915660cbed3233529e854edb94e
.. _4650184: https://github.com/vprivat-ads/eodag/commit/4650184637feaaee7e39f8d84da954789b26f7c3
.. _470aa49: https://github.com/vprivat-ads/eodag/commit/470aa492fa79d8d89f84a1277d783c38dd5d04aa
.. _47452e5: https://github.com/vprivat-ads/eodag/commit/47452e54c00659a4992df9bd1368cfbd21e1ccaf
.. _4776cf9: https://github.com/vprivat-ads/eodag/commit/4776cf9bec1e7550a0cae4a2e0606135f6851115
.. _4785e8a: https://github.com/vprivat-ads/eodag/commit/4785e8a128a70d3f07bd57ed6333a66db10a91a4
.. _47c0e33: https://github.com/vprivat-ads/eodag/commit/47c0e33bd503c04b0bbf9e2a8e54b8337248e04a
.. _47dc78c: https://github.com/vprivat-ads/eodag/commit/47dc78cc31f2a462199f32112a2dfb7ef3e6f13a
.. _47ed8bb: https://github.com/vprivat-ads/eodag/commit/47ed8bbd74c757d3d498b49132dc2d32f8ac6b38
.. _482eae3: https://github.com/vprivat-ads/eodag/commit/482eae366a3992845b97939a3d2e0d828a1f3392
.. _48b0779: https://github.com/vprivat-ads/eodag/commit/48b07797b3a17c26e33f6f8ee2f51488a0829162
.. _48f0e4c: https://github.com/vprivat-ads/eodag/commit/48f0e4c8c82e80841b7b64bec60a251661a13d12
.. _49209ff: https://github.com/vprivat-ads/eodag/commit/49209ff081784ca7d31121899ce1eb8eda7d294c
.. _49366bd: https://github.com/vprivat-ads/eodag/commit/49366bd6b7509466114cfec804003f6fe726bb85
.. _49b15cc: https://github.com/vprivat-ads/eodag/commit/49b15ccd7aa5b83f19fb98b8b4a0dae279c2c18c
.. _49e8f9f: https://github.com/vprivat-ads/eodag/commit/49e8f9f70755edf8d32652e95306fca16f02171c
.. _49e924d: https://github.com/vprivat-ads/eodag/commit/49e924d5831f6d4a42df754a9ed0326da72076a6
.. _4a0d689: https://github.com/vprivat-ads/eodag/commit/4a0d68987de913040e0ba16f9fe1d00cd10fe6e5
.. _4a15d7f: https://github.com/vprivat-ads/eodag/commit/4a15d7f894a379d48639876796ee159cac4c3986
.. _4a3e67a: https://github.com/vprivat-ads/eodag/commit/4a3e67acdf85f12d65ca0ba3d1f083d3888a2053
.. _4aa610a: https://github.com/vprivat-ads/eodag/commit/4aa610a0d84fe3fb2dcd8691e5b8cead9de65d54
.. _4b0b67d: https://github.com/vprivat-ads/eodag/commit/4b0b67d79c0e5f48f4a8419ef24176b1d126891b
.. _4b1397b: https://github.com/vprivat-ads/eodag/commit/4b1397bfdc79b0b9be0be3fc825df40949f4acae
.. _4b35e1d: https://github.com/vprivat-ads/eodag/commit/4b35e1d8eeeae5a2cc291f46aa0fbf02b98b972e
.. _4b57160: https://github.com/vprivat-ads/eodag/commit/4b571601b8a872265adc14c7fdb0be8e8566aa4c
.. _4bcbe55: https://github.com/vprivat-ads/eodag/commit/4bcbe5592f8426e3936fefec7d81c4db4ebcd0b7
.. _4bfbd6d: https://github.com/vprivat-ads/eodag/commit/4bfbd6dfc11a08744935f8fdd4e3d9c321252d26
.. _4c340b0: https://github.com/vprivat-ads/eodag/commit/4c340b09b0702ad90bb9110fc4cdf74c58a01f9c
.. _4c373fd: https://github.com/vprivat-ads/eodag/commit/4c373fd081a54f93b1bcda3d669f19aaf1a05c7d
.. _4c61b54: https://github.com/vprivat-ads/eodag/commit/4c61b540ee46a8ae70932d64e9d373653763eb16
.. _4ca485c: https://github.com/vprivat-ads/eodag/commit/4ca485c12f465348c4a08c082de86b162ee23144
.. _4cd2070: https://github.com/vprivat-ads/eodag/commit/4cd207078be7f97b1377677d242f9ff8a83164fc
.. _4d03a1a: https://github.com/vprivat-ads/eodag/commit/4d03a1a1be55d04c9ef9e769e64348ba1726a574
.. _4d2b7e3: https://github.com/vprivat-ads/eodag/commit/4d2b7e3a63b49603d8cc1d0dda4d9be012d5d2e8
.. _4d65d33: https://github.com/vprivat-ads/eodag/commit/4d65d33a86b46f3fb9743906c7f21d1359d05b98
.. _4d6f726: https://github.com/vprivat-ads/eodag/commit/4d6f726aa9a9e0d492eccdf7d88f498404c2c021
.. _4d9f091: https://github.com/vprivat-ads/eodag/commit/4d9f09110c0fcc745d910b9c02e155aa1952b048
.. _4e1923b: https://github.com/vprivat-ads/eodag/commit/4e1923be4e03a14d7acbd1b3baec21a85ece9969
.. _4e739f8: https://github.com/vprivat-ads/eodag/commit/4e739f869a8d73c2e0ae5898ebc2ac27e66edfcc
.. _4e7645e: https://github.com/vprivat-ads/eodag/commit/4e7645e0888b396e551885a0d62eef08e2afb684
.. _4f1604e: https://github.com/vprivat-ads/eodag/commit/4f1604ee1167fdef1ee7395af6781e2f1df14577
.. _4f64016: https://github.com/vprivat-ads/eodag/commit/4f6401661a6724c9c95a3538f7043a90a1e586be
.. _4f74c83: https://github.com/vprivat-ads/eodag/commit/4f74c83f7d7c7a50a84f31dd51c015725331c018
.. _4f7edc8: https://github.com/vprivat-ads/eodag/commit/4f7edc812255f2698d5fe03cd6514d74fdc16f82
.. _4fa1b42: https://github.com/vprivat-ads/eodag/commit/4fa1b4237c6d540444135c94ae17af776a64ce47
.. _4fbdf8b: https://github.com/vprivat-ads/eodag/commit/4fbdf8ba4d2cece05bede65e18438ecdc8029a69
.. _4ff098f: https://github.com/vprivat-ads/eodag/commit/4ff098fa3b9204809744e50bbba86cbaa08ae092
.. _5077fa5: https://github.com/vprivat-ads/eodag/commit/5077fa591496811fb100c1e6b6a3e452cbdbe2a5
.. _50a451f: https://github.com/vprivat-ads/eodag/commit/50a451fabfbd6529acd3b95cd1a8230ac1ada904
.. _50d6e60: https://github.com/vprivat-ads/eodag/commit/50d6e60396cff60f6373ab64af5a0229a77e6906
.. _513bfe0: https://github.com/vprivat-ads/eodag/commit/513bfe0fd417f6ea7fd33e68562048722696b7a0
.. _5165658: https://github.com/vprivat-ads/eodag/commit/5165658467e52e2c1d7f5573ef3b1db466a2591b
.. _51a489a: https://github.com/vprivat-ads/eodag/commit/51a489a728b581fbee5e1f26173cf813285c2460
.. _51a5f36: https://github.com/vprivat-ads/eodag/commit/51a5f3667b2cc0b706a7278494ee4e8bf1260210
.. _5220b60: https://github.com/vprivat-ads/eodag/commit/5220b6086411b5d9296a2083a5aca6e876b774dc
.. _52a4bfa: https://github.com/vprivat-ads/eodag/commit/52a4bfa70b06771c61f9b9bb40fa408401d18079
.. _52a69f6: https://github.com/vprivat-ads/eodag/commit/52a69f6026f6faf6dde82f06033f93658306e80e
.. _52cacf3: https://github.com/vprivat-ads/eodag/commit/52cacf3b91425510b02ccdd661e480a378d3fa18
.. _52e8363: https://github.com/vprivat-ads/eodag/commit/52e8363b9474081310f65b51aa94366bc0ace6f8
.. _538331d: https://github.com/vprivat-ads/eodag/commit/538331d30085a814307173913ff831ca5a3397af
.. _539c605: https://github.com/vprivat-ads/eodag/commit/539c605e683b35b7e4e7142487162b33a05b22c1
.. _53a53c8: https://github.com/vprivat-ads/eodag/commit/53a53c8c2dce182fb00e9780a3e0e2ccea30b0a6
.. _53c1c5e: https://github.com/vprivat-ads/eodag/commit/53c1c5e4e42c309e5f6da92d39107ebf8784e5d3
.. _53cb3bb: https://github.com/vprivat-ads/eodag/commit/53cb3bbc7818812e49ea7f010ea1c749aaac0d99
.. _53e2756: https://github.com/vprivat-ads/eodag/commit/53e2756c611262eff1f703874b83ca25478bb18f
.. _5400db4: https://github.com/vprivat-ads/eodag/commit/5400db484dc95b5e42e96ee05578a8fa261e86d0
.. _541794b: https://github.com/vprivat-ads/eodag/commit/541794bb1ca3d4f31b7df75d9c6ee62b0535dbb5
.. _548fded: https://github.com/vprivat-ads/eodag/commit/548fdedc7a30d488302a685c4c8361ba29c2068f
.. _54a5182: https://github.com/vprivat-ads/eodag/commit/54a51822ae350e54d2b7d353db377b6ff2886518
.. _5504ad5: https://github.com/vprivat-ads/eodag/commit/5504ad57fcb97e731b8c9880382db913bd45b4a4
.. _55b1ffe: https://github.com/vprivat-ads/eodag/commit/55b1ffeae8b2ef03e5ecac35838675f9328cde90
.. _55bea37: https://github.com/vprivat-ads/eodag/commit/55bea37d849167757a794cd0423f1217f694f399
.. _56068d7: https://github.com/vprivat-ads/eodag/commit/56068d75c3c6c58e140e1b174fe8311863c7987c
.. _568ae07: https://github.com/vprivat-ads/eodag/commit/568ae07bfa176f1e68b59c1775f2fb3e39df93b9
.. _5717f0d: https://github.com/vprivat-ads/eodag/commit/5717f0deddbf022f2c6d5207ade77de6afb0f9d5
.. _576a2ac: https://github.com/vprivat-ads/eodag/commit/576a2ac95044d10367e91e5ef843fb33a921f5f5
.. _57fecd0: https://github.com/vprivat-ads/eodag/commit/57fecd07d32830ad12be3fb8074d5124c5797dc5
.. _58335e7: https://github.com/vprivat-ads/eodag/commit/58335e728fff5b98bd85b96fead271429773a593
.. _589ca10: https://github.com/vprivat-ads/eodag/commit/589ca1062877b48239c2df93844e497b25119fe1
.. _58b6093: https://github.com/vprivat-ads/eodag/commit/58b6093b2522e036f5c617bd3cbd29fd4e4c6b7c
.. _596b6bc: https://github.com/vprivat-ads/eodag/commit/596b6bc501595953d0f81126f04c18ce0f0a3852
.. _59ac437: https://github.com/vprivat-ads/eodag/commit/59ac437de01a8996d247b1f8239f332ed5dc5456
.. _59ac844: https://github.com/vprivat-ads/eodag/commit/59ac8445bcfbbe54b83ca3c7fabaa6169db0998d
.. _59bf497: https://github.com/vprivat-ads/eodag/commit/59bf4970f38590e1a3c1a55b46cb9d757e3a2145
.. _59ccd8b: https://github.com/vprivat-ads/eodag/commit/59ccd8b563ce9914488ab0d5f52965fd09692cde
.. _5a175cb: https://github.com/vprivat-ads/eodag/commit/5a175cb4a82207b90e6194cc4e9fda6056d8cbdf
.. _5a72707: https://github.com/vprivat-ads/eodag/commit/5a72707f169643e1008b1f9f01670df4976a35dc
.. _5a72caa: https://github.com/vprivat-ads/eodag/commit/5a72caa3d422fd39ea68696df4055c004fa22a2e
.. _5ac08ec: https://github.com/vprivat-ads/eodag/commit/5ac08ec040fe64d716cf12f8093f717e9161e08a
.. _5aff668: https://github.com/vprivat-ads/eodag/commit/5aff6689a9ef91bda7e40c00cb167d4a9b082098
.. _5b06ca3: https://github.com/vprivat-ads/eodag/commit/5b06ca3e23d741a446a798958fff3d8a2d36347b
.. _5b98144: https://github.com/vprivat-ads/eodag/commit/5b981447e127f35b3014aad073e9126b15c39ed0
.. _5b9caa5: https://github.com/vprivat-ads/eodag/commit/5b9caa5bf8c0dec8c22756fcd6a8662506cb84f6
.. _5bc3f68: https://github.com/vprivat-ads/eodag/commit/5bc3f68961eae2f5878f07182a0cb6624563793c
.. _5bcc431: https://github.com/vprivat-ads/eodag/commit/5bcc431f4e0a39a23a3f2c0e6bcb7efb693ec4e7
.. _5beec33: https://github.com/vprivat-ads/eodag/commit/5beec33b6475bc90770cb43ca7d754ccd9453da9
.. _5c96977: https://github.com/vprivat-ads/eodag/commit/5c96977764972e0aa22075b897043cfbb3a5d07e
.. _5cf3cc6: https://github.com/vprivat-ads/eodag/commit/5cf3cc6c42de4f08c14c2f66e31781250e129813
.. _5cfd0ac: https://github.com/vprivat-ads/eodag/commit/5cfd0ac3b9c8435b921fb46bd43ae8f3b226c07f
.. _5d598a9: https://github.com/vprivat-ads/eodag/commit/5d598a9934d36390e7b6f1ef2d746f9a9030198d
.. _5de90ce: https://github.com/vprivat-ads/eodag/commit/5de90ce432c272f2b9dbe358a0e187c5b9fe0bad
.. _5e389e4: https://github.com/vprivat-ads/eodag/commit/5e389e4e26d9e8058fd3919170908514233db7fd
.. _5e6764e: https://github.com/vprivat-ads/eodag/commit/5e6764ed1250c943e4b8d3aa0215c70b33b9effd
.. _5eb6bb0: https://github.com/vprivat-ads/eodag/commit/5eb6bb0a257b5d5ac4bd6623d873d62d0c4b09e7
.. _5ebb90b: https://github.com/vprivat-ads/eodag/commit/5ebb90b62ce36838b7fb5a0bcd02abdba14e80d8
.. _5ec4421: https://github.com/vprivat-ads/eodag/commit/5ec4421cf3c653e35005e4489a09cb2f22e44a9f
.. _5ef8dac: https://github.com/vprivat-ads/eodag/commit/5ef8dac76e5187e80747c778b919eb8280a369e0
.. _5f1b707: https://github.com/vprivat-ads/eodag/commit/5f1b7070fea53513309d4719326b29428527f7d3
.. _5f6966b: https://github.com/vprivat-ads/eodag/commit/5f6966bc52db1e19ad3f959bab41aca25804c3e5
.. _5f88b80: https://github.com/vprivat-ads/eodag/commit/5f88b808f37197d871943c431c2d7ed3cd6b5181
.. _60338b6: https://github.com/vprivat-ads/eodag/commit/60338b6dd766c79d82c569170359210cbcad4cc4
.. _6034cd1: https://github.com/vprivat-ads/eodag/commit/6034cd1a2a595d294474c97301bd0dd598da79be
.. _6055d7b: https://github.com/vprivat-ads/eodag/commit/6055d7b2246f46f6f7122bb1dc8c08cc6119bc4f
.. _6088572: https://github.com/vprivat-ads/eodag/commit/6088572458c7fbcd315483187d35df231361cfd7
.. _614075f: https://github.com/vprivat-ads/eodag/commit/614075f279cebe61c79aca7355f2653efeafda94
.. _616d1a9: https://github.com/vprivat-ads/eodag/commit/616d1a960324313c18309d905c4465ece3f9b90b
.. _6176b8e: https://github.com/vprivat-ads/eodag/commit/6176b8e7e6cd67680d03d99b3483de9f66c34dbd
.. _622012a: https://github.com/vprivat-ads/eodag/commit/622012a17ceba532d6205f1056e97e5037beda09
.. _6229ca6: https://github.com/vprivat-ads/eodag/commit/6229ca6c7e716be5b48c26df9504bb0ca7adaea5
.. _623b32a: https://github.com/vprivat-ads/eodag/commit/623b32a3e769bf5db4a89657d85a05b50a7f18de
.. _62977ba: https://github.com/vprivat-ads/eodag/commit/62977ba5d86c30d9ced37adf2b3205da26e29614
.. _62c75fe: https://github.com/vprivat-ads/eodag/commit/62c75feb7f2ae44e50eaecaa6b4e04936a4451fa
.. _6399631: https://github.com/vprivat-ads/eodag/commit/63996319f57d9eb6d73e01908f29b3e6a1740724
.. _63eea5a: https://github.com/vprivat-ads/eodag/commit/63eea5a4a885f9f7449dbba8e5114ac5b640b2ec
.. _641ccfd: https://github.com/vprivat-ads/eodag/commit/641ccfdec5141c4cf4379476bb9c6061ed9a6d06
.. _641dfdf: https://github.com/vprivat-ads/eodag/commit/641dfdf3f755b5be6e01e78e3c594cadf5687070
.. _643bcd9: https://github.com/vprivat-ads/eodag/commit/643bcd9812ce99171aaa895a2e29af68bc0c164f
.. _643cb3c: https://github.com/vprivat-ads/eodag/commit/643cb3c0e6228ebf83ba01bf38a80b05162a7ab4
.. _64557a9: https://github.com/vprivat-ads/eodag/commit/64557a95b8ded531f5d151dd4ea57b9647b74c3f
.. _650d21b: https://github.com/vprivat-ads/eodag/commit/650d21b84e3c929eee7c1b100e6ee7ecfd0a70b8
.. _651f94f: https://github.com/vprivat-ads/eodag/commit/651f94f25be528d0d202a52414eb9aac0efcb957
.. _652c927: https://github.com/vprivat-ads/eodag/commit/652c9278c04c962a7661cfbd2dcdd332a6e77e46
.. _6564ce6: https://github.com/vprivat-ads/eodag/commit/6564ce68dd39f24a6b2db62b6b50cd24cb72552c
.. _6576287: https://github.com/vprivat-ads/eodag/commit/657628718e509b88d39e0222869de23cacc8f9ab
.. _6606607: https://github.com/vprivat-ads/eodag/commit/66066070f68e7a558ec34ac4ba46d64c7376ff31
.. _662eaf1: https://github.com/vprivat-ads/eodag/commit/662eaf1fcf007ecc1136ac122b4457af90c57f3d
.. _66a9d2f: https://github.com/vprivat-ads/eodag/commit/66a9d2fc0ae0c94e498a8d9f14a7a54268c1c3d2
.. _67039bc: https://github.com/vprivat-ads/eodag/commit/67039bca881c54649e628f466157579bdc47de79
.. _672fded: https://github.com/vprivat-ads/eodag/commit/672fdede8451931769333423f67d1183b86062ca
.. _67e0943: https://github.com/vprivat-ads/eodag/commit/67e0943793dd20c2c6c6271b9e1d8168fdc42ed3
.. _67f653d: https://github.com/vprivat-ads/eodag/commit/67f653deb272109dae563f5cc513ca696561bf2c
.. _6823a97: https://github.com/vprivat-ads/eodag/commit/6823a976319611d99d7358236f63266573c28aca
.. _687d3f4: https://github.com/vprivat-ads/eodag/commit/687d3f435a152eb54019d04cbc985439649f6b04
.. _6881134: https://github.com/vprivat-ads/eodag/commit/6881134cfe797e191ad1c67f56653c547756a965
.. _689471c: https://github.com/vprivat-ads/eodag/commit/689471c44a19be2bc495cde09c45038e36d06fe2
.. _68f98df: https://github.com/vprivat-ads/eodag/commit/68f98df4f1adcf2a4c28ff8ccfd8a9da5e419fd5
.. _69779cb: https://github.com/vprivat-ads/eodag/commit/69779cb8ae70c4acf46493cd031565f55a31b1e6
.. _697b5c8: https://github.com/vprivat-ads/eodag/commit/697b5c851f7f15ccb48c9e749061314118f26e3b
.. _69b5443: https://github.com/vprivat-ads/eodag/commit/69b5443866b16d29c5e511f3cd430adfdb7364bd
.. _69baba5: https://github.com/vprivat-ads/eodag/commit/69baba503b6ab715e3967beb1f068a17756c74b3
.. _69d24e8: https://github.com/vprivat-ads/eodag/commit/69d24e856d04abbf44a81786b67cc26e98d43ee5
.. _6a62711: https://github.com/vprivat-ads/eodag/commit/6a62711aece1672564b9357cc74734b793944e4e
.. _6a6344c: https://github.com/vprivat-ads/eodag/commit/6a6344c5b8c49ad623a42a60eabea23e61efd898
.. _6a7e0d4: https://github.com/vprivat-ads/eodag/commit/6a7e0d43883d862b06269dee4bff940b5112e018
.. _6a93f02: https://github.com/vprivat-ads/eodag/commit/6a93f02d44346c89e047e9b399904139922b879f
.. _6ab4262: https://github.com/vprivat-ads/eodag/commit/6ab4262a133f051f6699881fb9352237e16cbcc8
.. _6ad08cb: https://github.com/vprivat-ads/eodag/commit/6ad08cb4d7771c574401eafa41c37f4a5d898223
.. _6ada805: https://github.com/vprivat-ads/eodag/commit/6ada805f9d3db4b225a9c94c91fb296780e7b20d
.. _6af7ce4: https://github.com/vprivat-ads/eodag/commit/6af7ce499d00c32af3754ce30ebcb8fc392638a9
.. _6b6d64c: https://github.com/vprivat-ads/eodag/commit/6b6d64cdab94495eec0d72e4af8adb955b841d8a
.. _6b7ca26: https://github.com/vprivat-ads/eodag/commit/6b7ca26d5291602ce5b92beb148b359d6a1f5d05
.. _6bdb107: https://github.com/vprivat-ads/eodag/commit/6bdb107f5704df1fd868038d58617c8ac1d10779
.. _6bdc5bb: https://github.com/vprivat-ads/eodag/commit/6bdc5bb25635739c60b747ff42dc993d596778b0
.. _6c46430: https://github.com/vprivat-ads/eodag/commit/6c46430c96ee052554e092e0b0ee19afc3a2009e
.. _6ca2b90: https://github.com/vprivat-ads/eodag/commit/6ca2b90f1997aa10e66ddee2b1e33a385014bf7f
.. _6ca3d50: https://github.com/vprivat-ads/eodag/commit/6ca3d507cb64e3456f21a77981a0eebc62342f92
.. _6cc222a: https://github.com/vprivat-ads/eodag/commit/6cc222a7e8e3bdba17c928380c99de1da795660b
.. _6d29809: https://github.com/vprivat-ads/eodag/commit/6d29809a0dcec97df12ef8644646a3364a9c0a99
.. _6d44c2a: https://github.com/vprivat-ads/eodag/commit/6d44c2ae897d94d92b7d8e6d8ac425910cf0af7e
.. _6d51c12: https://github.com/vprivat-ads/eodag/commit/6d51c12ba6f6e9166833f8dfc85f9e1612b60ec3
.. _6d6f34f: https://github.com/vprivat-ads/eodag/commit/6d6f34fb247e9f51ed3576026ff3a90764023c38
.. _6db9e71: https://github.com/vprivat-ads/eodag/commit/6db9e711581ffd06bb69592e65d6b4f8d19f8bb5
.. _6dc0509: https://github.com/vprivat-ads/eodag/commit/6dc050952154450cb0c121b7f8ce3fe731e12274
.. _6e25b8a: https://github.com/vprivat-ads/eodag/commit/6e25b8ac1fe3e9b997dff9e6c1ada5854b57adf1
.. _6e3277a: https://github.com/vprivat-ads/eodag/commit/6e3277a4c53a8bdd53c4e5f4ede4e4ee48ee0e8c
.. _6e6aed8: https://github.com/vprivat-ads/eodag/commit/6e6aed84ac3ea8cd5c2f5860db5b851f4b8b79d2
.. _6e6e689: https://github.com/vprivat-ads/eodag/commit/6e6e6890a52ac8ad4d0f989f41a726b35d9cf5d8
.. _6e82bad: https://github.com/vprivat-ads/eodag/commit/6e82bad4a484d4c4bbbbb4f98faad64a06b24518
.. _6e8eb6b: https://github.com/vprivat-ads/eodag/commit/6e8eb6b94eaad6294fea45d764a0e7c18a4e6823
.. _6ede794: https://github.com/vprivat-ads/eodag/commit/6ede794e68cb3ae069ef90ea42192e9957dcce2f
.. _6f52040: https://github.com/vprivat-ads/eodag/commit/6f52040628c8627d2c1e1dc62080a2ac474884cd
.. _6f8e6ad: https://github.com/vprivat-ads/eodag/commit/6f8e6ad683f786286cfb36e8e22c17cfb2daf125
.. _6fee322: https://github.com/vprivat-ads/eodag/commit/6fee322d19ecc2805f7ab44139b3c555b8cad40f
.. _6ff2907: https://github.com/vprivat-ads/eodag/commit/6ff2907f7f0774237e550f587ad2b430389e69d3
.. _6ff8e5f: https://github.com/vprivat-ads/eodag/commit/6ff8e5f2d5828076f186d61b77ee393c70f9ee21
.. _7054aa3: https://github.com/vprivat-ads/eodag/commit/7054aa316e91b5841902e8afd67e28209a85b716
.. _70586e9: https://github.com/vprivat-ads/eodag/commit/70586e9482a65e6469c993e5bd1cc70f78f8f022
.. _707dd1b: https://github.com/vprivat-ads/eodag/commit/707dd1b8aa05dc673c1e0f2e9343cfe64c562a79
.. _708fd41: https://github.com/vprivat-ads/eodag/commit/708fd419b938897250ecf97ad15380c05bc830e1
.. _70aa455: https://github.com/vprivat-ads/eodag/commit/70aa45515b7b7c11326419abcf616979e7b6e024
.. _70e156b: https://github.com/vprivat-ads/eodag/commit/70e156b8959adf170833b01e06a91ab9d6e29c6c
.. _7166a42: https://github.com/vprivat-ads/eodag/commit/7166a42da9c5e337cc73d6b195d50f3220b0e607
.. _71a51f1: https://github.com/vprivat-ads/eodag/commit/71a51f16ea370f542af3142fee25ec90c2a75ae3
.. _720588a: https://github.com/vprivat-ads/eodag/commit/720588ae14b19f555c80b89019722a45770aff1d
.. _7209dda: https://github.com/vprivat-ads/eodag/commit/7209dda749c97fca63a9f97743edeeca45f1b885
.. _7252ad5: https://github.com/vprivat-ads/eodag/commit/7252ad5e7759d518a78e79a6d894446a9dc4ddd2
.. _7254be5: https://github.com/vprivat-ads/eodag/commit/7254be5e09df6acb74be637236087f4bbf72b8de
.. _727fb09: https://github.com/vprivat-ads/eodag/commit/727fb09e87432157ba876f484c27cd9c0c0e01f3
.. _72b14f0: https://github.com/vprivat-ads/eodag/commit/72b14f05974d12b754e03f700854e5292634f3a7
.. _72ca3d7: https://github.com/vprivat-ads/eodag/commit/72ca3d7dd63b4db66dd513f0479dc50b58708511
.. _72e7a48: https://github.com/vprivat-ads/eodag/commit/72e7a48eba23f7debb89903f31d67555b53fcbce
.. _7341337: https://github.com/vprivat-ads/eodag/commit/7341337b76ef9023d370dd191c7ee2a638552c88
.. _73a0364: https://github.com/vprivat-ads/eodag/commit/73a03646ea3ad2019cb180ff1da6368e649388d7
.. _73b17aa: https://github.com/vprivat-ads/eodag/commit/73b17aadf7eb92a2b156216aa6f84b9e4d186c31
.. _73d8f11: https://github.com/vprivat-ads/eodag/commit/73d8f11b9a74d7929a0df9d0aa68658ff61d8de4
.. _73e95cb: https://github.com/vprivat-ads/eodag/commit/73e95cb6407329faf860cb775e1dd61838e6a2c4
.. _741a340: https://github.com/vprivat-ads/eodag/commit/741a34068d0a91f4bbac46d863623c91d65ff5b9
.. _743d7b5: https://github.com/vprivat-ads/eodag/commit/743d7b5d25d50425de4c7f1c62c0922d7453afe2
.. _7448cf8: https://github.com/vprivat-ads/eodag/commit/7448cf8e41a83e56197ca1fef913d3dd2defb90d
.. _74490a2: https://github.com/vprivat-ads/eodag/commit/74490a2bf3baa8c6be94964e60f6d4323d5bc596
.. _747b966: https://github.com/vprivat-ads/eodag/commit/747b966b60d3382fcd3aaf39481ebaa5983c4cf3
.. _748e34e: https://github.com/vprivat-ads/eodag/commit/748e34e7b6fbce812d50a581aaad24a96c70bb65
.. _74aaad6: https://github.com/vprivat-ads/eodag/commit/74aaad6bca89d8d1e60c109886b9c151e8b739ab
.. _7523dcf: https://github.com/vprivat-ads/eodag/commit/7523dcf3ad98066fd4328c23cf674331be32b1f7
.. _754772b: https://github.com/vprivat-ads/eodag/commit/754772b9e71700fb752cb632dfb66ef13cd2c743
.. _7658679: https://github.com/vprivat-ads/eodag/commit/7658679d2494edc42f83facb23ee4c3f1d1c7df6
.. _766faaa: https://github.com/vprivat-ads/eodag/commit/766faaadc60499dc0e8de89bb0b1316e0d3d235b
.. _76fadda: https://github.com/vprivat-ads/eodag/commit/76fadda0844db2eb407632a375d93e9b9a7eec46
.. _7708015: https://github.com/vprivat-ads/eodag/commit/77080155d2e0089816e89e9b777dc38fd7d3d61d
.. _7714bea: https://github.com/vprivat-ads/eodag/commit/7714bea1c1bf4a80f9607256881cbccf9a997c16
.. _7795cf1: https://github.com/vprivat-ads/eodag/commit/7795cf1ddd8657ab61e33af849a25f71787bf0dc
.. _77cd724: https://github.com/vprivat-ads/eodag/commit/77cd7240aecb8829e8867302392ee5faebd3372d
.. _77cf3d7: https://github.com/vprivat-ads/eodag/commit/77cf3d7338d90a4034a769766ce1cc85045264be
.. _780eabf: https://github.com/vprivat-ads/eodag/commit/780eabf7e600c87b8e29e5ef0be68a8fe896abed
.. _78179d5: https://github.com/vprivat-ads/eodag/commit/78179d54d5f53e99d49cade6738b7a4b7568e09d
.. _7824f6a: https://github.com/vprivat-ads/eodag/commit/7824f6a1a3d3aa881532c5904f58acb73ebdca5f
.. _782d34c: https://github.com/vprivat-ads/eodag/commit/782d34c9511720b08662f6003a19e8d094d4e7bb
.. _786c663: https://github.com/vprivat-ads/eodag/commit/786c663414f42297e7ceeace2646446872160941
.. _78a18ae: https://github.com/vprivat-ads/eodag/commit/78a18ae74e06d27793430f69a7b6c2968563befa
.. _790df60: https://github.com/vprivat-ads/eodag/commit/790df608a1a1aa1dbe87198d883602ecf82176e0
.. _790e9f5: https://github.com/vprivat-ads/eodag/commit/790e9f56e2aeb9b2805f522057cb4da4d84aa8e4
.. _791fb4d: https://github.com/vprivat-ads/eodag/commit/791fb4d6a95cc2145d56ceac7c59ecaec08c3fec
.. _7924f7f: https://github.com/vprivat-ads/eodag/commit/7924f7f9bef81a15aff3de6c78c2b93fe96228a7
.. _7960f93: https://github.com/vprivat-ads/eodag/commit/7960f93232a5917b2a097b492fe9937f80f81fe2
.. _79f40a3: https://github.com/vprivat-ads/eodag/commit/79f40a3daa8d0ad860101e068fa201851db4dbad
.. _7a04158: https://github.com/vprivat-ads/eodag/commit/7a041583695f71811baf56e5616415df60750814
.. _7a372eb: https://github.com/vprivat-ads/eodag/commit/7a372ebeb4e378a171ffbb12d6748604cbff3ebe
.. _7a51598: https://github.com/vprivat-ads/eodag/commit/7a515985291fbafbbcdabc3babfe90e1f828568c
.. _7aa0309: https://github.com/vprivat-ads/eodag/commit/7aa0309d3ef356abaf51ca3335ceb489a8ea9e43
.. _7adc615: https://github.com/vprivat-ads/eodag/commit/7adc6156451eba3e14c0a1fab7c3e7679ef45683
.. _7b1fb89: https://github.com/vprivat-ads/eodag/commit/7b1fb89208537a360471a218d13b2f9865f282c4
.. _7bc6947: https://github.com/vprivat-ads/eodag/commit/7bc694749053bae7a060f7ff04832702aea84199
.. _7bcdbc5: https://github.com/vprivat-ads/eodag/commit/7bcdbc50cadba60507a6fbe805d8d6843e50075a
.. _7bf602f: https://github.com/vprivat-ads/eodag/commit/7bf602fc9c3cc9badf2862ad1237c1daef2c754e
.. _7bfe7fb: https://github.com/vprivat-ads/eodag/commit/7bfe7fbaac144b8e63e2b20657026ee1c86e245d
.. _7c47474: https://github.com/vprivat-ads/eodag/commit/7c47474d7932f0c824ab3b3dae94f4a041368adf
.. _7c532f4: https://github.com/vprivat-ads/eodag/commit/7c532f47fb3b17b4a39d379301134ac75f55253d
.. _7c7f00c: https://github.com/vprivat-ads/eodag/commit/7c7f00c30d4a0afd377e52666b7e454d357c0d21
.. _7d105d1: https://github.com/vprivat-ads/eodag/commit/7d105d12a32d659557c20d763e6ba189c66ab1f8
.. _7d72d64: https://github.com/vprivat-ads/eodag/commit/7d72d649ae12c020052c600062585384ca0a9111
.. _7d87255: https://github.com/vprivat-ads/eodag/commit/7d87255f833df7cafc30ce5f223ef39c1960542c
.. _7da1505: https://github.com/vprivat-ads/eodag/commit/7da1505fa2936c10deee4350019633959a96d8a5
.. _7e10e3a: https://github.com/vprivat-ads/eodag/commit/7e10e3aeb27220fd023f1cb00198ed2304ea3486
.. _7e199dc: https://github.com/vprivat-ads/eodag/commit/7e199dc56bbe18440fd16f3e9ff8428650572540
.. _7e502af: https://github.com/vprivat-ads/eodag/commit/7e502af83d68b83045a59358dc48200af9ad21ab
.. _7e879d2: https://github.com/vprivat-ads/eodag/commit/7e879d265c568c7642b0bc5cfe162885bd8aa3ed
.. _7ee6c7f: https://github.com/vprivat-ads/eodag/commit/7ee6c7f853e6789fa6addeccbef9016d96c4799a
.. _7f1b989: https://github.com/vprivat-ads/eodag/commit/7f1b989f75fcaebc9db3a218ed28696959b33ee1
.. _7f1f3e1: https://github.com/vprivat-ads/eodag/commit/7f1f3e10deb70213006f83fb0508fce6d72b5fc0
.. _7f1f490: https://github.com/vprivat-ads/eodag/commit/7f1f49051e247a0f3e2d2c05ee6040b489aec363
.. _7f520bc: https://github.com/vprivat-ads/eodag/commit/7f520bcc8d8005184e5f785a714ac4dee7388ea2
.. _7f7a236: https://github.com/vprivat-ads/eodag/commit/7f7a2368b38f4b13d3d81a44e088a5cd82b54435
.. _801c52c: https://github.com/vprivat-ads/eodag/commit/801c52c38124e6dfff1a5fdedeb0cbd269fc2478
.. _80394d2: https://github.com/vprivat-ads/eodag/commit/80394d20c0a68eb8ca6a59b373ce126081442356
.. _8090f54: https://github.com/vprivat-ads/eodag/commit/8090f547134c55e26528a3756491c3d4af5e9cc4
.. _80cf170: https://github.com/vprivat-ads/eodag/commit/80cf1708389849b26abc45d932276a59c6faacf4
.. _80f9403: https://github.com/vprivat-ads/eodag/commit/80f9403cf52c7446dd495539d551060fe54c92fc
.. _811c176: https://github.com/vprivat-ads/eodag/commit/811c17621af246ff82670c02bb924899d887a6b3
.. _812bc56: https://github.com/vprivat-ads/eodag/commit/812bc56b1cc74b3f2edf13efd665a5582d8a7f0c
.. _8131264: https://github.com/vprivat-ads/eodag/commit/8131264627b6143609868b9d3ebdcbf5b330eccd
.. _8132c6c: https://github.com/vprivat-ads/eodag/commit/8132c6c1f26b777e49c828ea803cee746d0eb102
.. _816cf99: https://github.com/vprivat-ads/eodag/commit/816cf99a08227201ca40df959a736128840b1947
.. _81732a8: https://github.com/vprivat-ads/eodag/commit/81732a834f414ad73c6b5654ec0226a14a9d4220
.. _8174a1e: https://github.com/vprivat-ads/eodag/commit/8174a1ea8079ae0aec604a9517342fce7055595a
.. _819247c: https://github.com/vprivat-ads/eodag/commit/819247c9c57389db3b51d3d402b09edc5938ad53
.. _819ecb2: https://github.com/vprivat-ads/eodag/commit/819ecb2127d7728236e32aadb1e605017c98cec6
.. _81a4337: https://github.com/vprivat-ads/eodag/commit/81a4337b77d1bcc2fdbcbf7002e224bdcc9ae761
.. _81e4b90: https://github.com/vprivat-ads/eodag/commit/81e4b903c5474894e87e6dcb9366fdfbb152398b
.. _82d55c0: https://github.com/vprivat-ads/eodag/commit/82d55c0d896627c4abdc0ad6d195fd40f178eb8e
.. _82f2753: https://github.com/vprivat-ads/eodag/commit/82f27537b0e87d7c6fae7df8f77736706c581ea1
.. _8331bd1: https://github.com/vprivat-ads/eodag/commit/8331bd19a9311a81c18547ace32dd4a0bbc43846
.. _835eab7: https://github.com/vprivat-ads/eodag/commit/835eab785d40ee21fdfa8af383d3c788aaa7dee9
.. _8360a41: https://github.com/vprivat-ads/eodag/commit/8360a418c93b787ce399932df8f4979626962765
.. _837c127: https://github.com/vprivat-ads/eodag/commit/837c127b5068fd87a99b875206b95d44e48fdb50
.. _84aac94: https://github.com/vprivat-ads/eodag/commit/84aac9405cd346a366e7499d043e1e6959a66f30
.. _850cb50: https://github.com/vprivat-ads/eodag/commit/850cb5010058887277e19e59b2b7b3311fddd2a4
.. _8539f18: https://github.com/vprivat-ads/eodag/commit/8539f18cb1314d9b4e4ec56b3e83ac6a08e46488
.. _85498a9: https://github.com/vprivat-ads/eodag/commit/85498a93c3a0aa5e4e27fb135685000254ec65aa
.. _8558510: https://github.com/vprivat-ads/eodag/commit/855851045a7280efb55d411d478b382ca774d1e6
.. _855ffa3: https://github.com/vprivat-ads/eodag/commit/855ffa39fa9b914eb39cc20d6e5c2cbbc1b2097a
.. _8561219: https://github.com/vprivat-ads/eodag/commit/856121900f6d973eca9d2ad3c0de61bbd706ae2c
.. _8570750: https://github.com/vprivat-ads/eodag/commit/857075060fe5137cbe8a90647cdd9e143307aac3
.. _857eeb7: https://github.com/vprivat-ads/eodag/commit/857eeb73333698ec4f2e1f71fbbb7f4b59fa7b7a
.. _8586d37: https://github.com/vprivat-ads/eodag/commit/8586d37ef28c031f80fe4665782da8aa08f96e00
.. _85be8a7: https://github.com/vprivat-ads/eodag/commit/85be8a721aa2479811a5dc0bc62cf42b5e836bbe
.. _862ad15: https://github.com/vprivat-ads/eodag/commit/862ad152b83c9989b34f1381c76a450b110eed3a
.. _863b372: https://github.com/vprivat-ads/eodag/commit/863b3725fa3021b3ab2bc66644a2994639692de4
.. _8664eb2: https://github.com/vprivat-ads/eodag/commit/8664eb2b4047fc3950675b5765264086901cb7ec
.. _86a0cf1: https://github.com/vprivat-ads/eodag/commit/86a0cf1dedc84147ee772169af92993c8e4f9fe3
.. _86baf25: https://github.com/vprivat-ads/eodag/commit/86baf25476cfd86fffb9d820ce48cbb7221c1315
.. _86c7977: https://github.com/vprivat-ads/eodag/commit/86c797763aa180f422da55c3f7bf508759043db9
.. _870580e: https://github.com/vprivat-ads/eodag/commit/870580e4565e533838a1b3c1b2acd2edd335de11
.. _873e45d: https://github.com/vprivat-ads/eodag/commit/873e45dd75eb3b229ab51b2b3c80ffe6e8c10fd9
.. _8762d3a: https://github.com/vprivat-ads/eodag/commit/8762d3a610d7a29df5dcbb99e41973b05aa38c72
.. _877366d: https://github.com/vprivat-ads/eodag/commit/877366d620216caa2557de6a217f4c606277b5e4
.. _87ade04: https://github.com/vprivat-ads/eodag/commit/87ade04922356eb78cf1798a8fb81bcea8057595
.. _87f69d3: https://github.com/vprivat-ads/eodag/commit/87f69d309a7445b558e01ff49d6e21bd801e7f43
.. _8822525: https://github.com/vprivat-ads/eodag/commit/88225254349299bfa4773c9083424e0b6df0ea34
.. _8868ee5: https://github.com/vprivat-ads/eodag/commit/8868ee57deb90c0b72ebd021c6033b2dbd28a193
.. _886e046: https://github.com/vprivat-ads/eodag/commit/886e04651619965b9869e56cc90d2acc9b5ba389
.. _888e7c4: https://github.com/vprivat-ads/eodag/commit/888e7c49620a92e848cb4b4e32dc39a3db6be108
.. _88c016d: https://github.com/vprivat-ads/eodag/commit/88c016d24a702581af416fc23a995c10a65174d2
.. _88fd434: https://github.com/vprivat-ads/eodag/commit/88fd434ec96bf56620bf133915c3d2e5dcafb23d
.. _89fa278: https://github.com/vprivat-ads/eodag/commit/89fa278117354d2877a4bb3f7f61da5a99178e5c
.. _8a891ef: https://github.com/vprivat-ads/eodag/commit/8a891ef2ec144e9ced5f28134320b1e9affde560
.. _8af8318: https://github.com/vprivat-ads/eodag/commit/8af8318e183e21bf2cbd04e0a334373de63d50fa
.. _8b118ee: https://github.com/vprivat-ads/eodag/commit/8b118eea3dcfaf194d2e649730596e01e183c1eb
.. _8b771f8: https://github.com/vprivat-ads/eodag/commit/8b771f801ef19e81297fc9fe273921702797dffc
.. _8bb11c4: https://github.com/vprivat-ads/eodag/commit/8bb11c4173c5585d52779b1a0c2c91051d9de639
.. _8bffc9c: https://github.com/vprivat-ads/eodag/commit/8bffc9caffbc900116956cbd4dc484ab691efab2
.. _8bffd13: https://github.com/vprivat-ads/eodag/commit/8bffd130baaeadb0dc87704c9a8e97806306affd
.. _8c318a5: https://github.com/vprivat-ads/eodag/commit/8c318a5c52bac8471362ff04b6c10f6de5e6a7b4
.. _8c3c1c1: https://github.com/vprivat-ads/eodag/commit/8c3c1c1e526f81f71a3ee01b10a9eb7f81ea3647
.. _8c5a658: https://github.com/vprivat-ads/eodag/commit/8c5a6589657dbf86d1c61631bb9e3dd7eff9c995
.. _8c8bf95: https://github.com/vprivat-ads/eodag/commit/8c8bf95a220736f7b795284f4be246615851c131
.. _8cf240e: https://github.com/vprivat-ads/eodag/commit/8cf240ecadc7632de5eadc7f19524856db8105f0
.. _8dde659: https://github.com/vprivat-ads/eodag/commit/8dde65983b16cc4d3cb4865c805d647e2728831b
.. _8e47f11: https://github.com/vprivat-ads/eodag/commit/8e47f11656a7d5e7e3dcc5e94f05ac31b457a71d
.. _8e6a79a: https://github.com/vprivat-ads/eodag/commit/8e6a79afacb39230738d23ff1143e951fe3029ed
.. _8f0eacf: https://github.com/vprivat-ads/eodag/commit/8f0eacf8ae6df513396cf033a93450316c778629
.. _8f2750e: https://github.com/vprivat-ads/eodag/commit/8f2750e07681f6522b9b5c5f6e5e272dde79683e
.. _8f46614: https://github.com/vprivat-ads/eodag/commit/8f46614b355e6f3bea81463767de99e212cc8b86
.. _8f633df: https://github.com/vprivat-ads/eodag/commit/8f633dff0d05f12579c9f7f1df5ddb6919bd656a
.. _8f74bea: https://github.com/vprivat-ads/eodag/commit/8f74bea8a26d0d16b302fca50ee912801caaeadd
.. _8facb6d: https://github.com/vprivat-ads/eodag/commit/8facb6d9a76c234233bfeee802d2316873f8f965
.. _8fe2f86: https://github.com/vprivat-ads/eodag/commit/8fe2f86f7bed28802c50eaa49499a66bbf86812a
.. _9028c4b: https://github.com/vprivat-ads/eodag/commit/9028c4b52c09810b7b74d1a62873734abd071af3
.. _9062756: https://github.com/vprivat-ads/eodag/commit/90627560ce0c66f7ad5d38fc4c3960c76e1f8932
.. _908c372: https://github.com/vprivat-ads/eodag/commit/908c3724092331611479f660b844093b50d7f67f
.. _909354f: https://github.com/vprivat-ads/eodag/commit/909354f089a3e08e810a194a10ce54858b26e6f6
.. _9096a12: https://github.com/vprivat-ads/eodag/commit/9096a12402068ac711b825956166a3de1051823f
.. _90aa258: https://github.com/vprivat-ads/eodag/commit/90aa258ed9c1caf5d6fce3ec79f6dcfce8ed50ae
.. _90da4f0: https://github.com/vprivat-ads/eodag/commit/90da4f09fa98a43419b50ddcf19f3155b2c849e8
.. _90eaaff: https://github.com/vprivat-ads/eodag/commit/90eaaff6516332521e96aaf5cb55a22f792d6385
.. _90f0545: https://github.com/vprivat-ads/eodag/commit/90f0545a6d40e2682818d5d2e59b2d7fb42bf11e
.. _90fafbe: https://github.com/vprivat-ads/eodag/commit/90fafbe3501569ab394b14b6df14ff69f38c35f8
.. _9138237: https://github.com/vprivat-ads/eodag/commit/9138237cbe1d01fb50d1ffc46741c21391851060
.. _913b5d8: https://github.com/vprivat-ads/eodag/commit/913b5d8caa24d1dcd76616cedcfd8cb867b549cc
.. _918f2d1: https://github.com/vprivat-ads/eodag/commit/918f2d1602cf5e0e351d155997ff24f7a3cd243e
.. _919dd3c: https://github.com/vprivat-ads/eodag/commit/919dd3c0755460597ab51a5af89715376d246917
.. _919f46d: https://github.com/vprivat-ads/eodag/commit/919f46df4527efe6963d5cc4c33e8971a65249b9
.. _91e1a90: https://github.com/vprivat-ads/eodag/commit/91e1a90b827defeee2fc20b9da4a8e1890ba013e
.. _91f2d1f: https://github.com/vprivat-ads/eodag/commit/91f2d1f684e068bd264d3e677b3c45ecb4898750
.. _92392d0: https://github.com/vprivat-ads/eodag/commit/92392d0f68278088a396341faf15224a5865987a
.. _92565f6: https://github.com/vprivat-ads/eodag/commit/92565f6327a5c696d73f9713ce609082e3ef3c1b
.. _92a1fe2: https://github.com/vprivat-ads/eodag/commit/92a1fe2131597b3b5c2d35d39272ec25baab8783
.. _92a537f: https://github.com/vprivat-ads/eodag/commit/92a537f7811a06f336712de6b8c07a9b80cf6de6
.. _930ada1: https://github.com/vprivat-ads/eodag/commit/930ada121a2e24ec90fbca7c4b099e024ad2b681
.. _938c23e: https://github.com/vprivat-ads/eodag/commit/938c23ee366ea4363873ab9be107744a24a6bd25
.. _93e33ee: https://github.com/vprivat-ads/eodag/commit/93e33eeeaac63f40b3aa8255f54b483c2fcc9264
.. _93e61ca: https://github.com/vprivat-ads/eodag/commit/93e61ca2f4d53f7da9d26cab44e9710092bf1dea
.. _9405571: https://github.com/vprivat-ads/eodag/commit/9405571bdc8b43bb9a98de86478270c5f5ee93f4
.. _9417fd9: https://github.com/vprivat-ads/eodag/commit/9417fd90049ccfb8ee30f6eef7e497da2c1bea60
.. _9445964: https://github.com/vprivat-ads/eodag/commit/9445964a8680c19237729b709b2a53d8602d2b74
.. _948b82b: https://github.com/vprivat-ads/eodag/commit/948b82b4fd1df9fc3078c99c1b04c34c3290fc65
.. _94d16b5: https://github.com/vprivat-ads/eodag/commit/94d16b5d197cfa8d5a958eb8e0436f9180bf16f8
.. _953acd7: https://github.com/vprivat-ads/eodag/commit/953acd7a49cd181bad9fcfffafd70bb1ed0e9c55
.. _9563d4b: https://github.com/vprivat-ads/eodag/commit/9563d4bccaea5a87805fff77863d14cb4b422fb7
.. _9596c5b: https://github.com/vprivat-ads/eodag/commit/9596c5bcdbbd90b5e0e3f291f1e19233a782fac3
.. _95c7e31: https://github.com/vprivat-ads/eodag/commit/95c7e31da01dc695c7abd014c135359653f684c2
.. _95f6c32: https://github.com/vprivat-ads/eodag/commit/95f6c321aceea84292827bafc5b3f865bd818573
.. _9639b37: https://github.com/vprivat-ads/eodag/commit/9639b374e85513056237adaa925f104f38677820
.. _9680cf3: https://github.com/vprivat-ads/eodag/commit/9680cf3ab6e856f9ec01f78eb3bf8b2b7ce61086
.. _96d85ab: https://github.com/vprivat-ads/eodag/commit/96d85ab3eb0b76bde134db6563a0505de6bbc467
.. _9729aa4: https://github.com/vprivat-ads/eodag/commit/9729aa4e5a52c1d692527fcac61d0ac7934bd481
.. _975c7cd: https://github.com/vprivat-ads/eodag/commit/975c7cddbe15dddfa4f06341252af1d4b63bd251
.. _9764ac8: https://github.com/vprivat-ads/eodag/commit/9764ac8d83ed81bd47d53df59a6dc3893ff55ec2
.. _9789c0c: https://github.com/vprivat-ads/eodag/commit/9789c0c4a52aa180422e1f0a0c2b8d86c373a0ee
.. _97b7b6f: https://github.com/vprivat-ads/eodag/commit/97b7b6f881714b4c40029a174c2539085cd50868
.. _97b9b6a: https://github.com/vprivat-ads/eodag/commit/97b9b6a7f4df6a7db419a3e3c8a39c165f1bfc6d
.. _97f2357: https://github.com/vprivat-ads/eodag/commit/97f23579c8d6f63ec209f5a1660f1133d483d2fb
.. _9826723: https://github.com/vprivat-ads/eodag/commit/982672369be388eea21234a593b99983ff6a3b75
.. _98dcc6b: https://github.com/vprivat-ads/eodag/commit/98dcc6b651d0a7f3d1b465480e461ec7b2d9a460
.. _98eae2e: https://github.com/vprivat-ads/eodag/commit/98eae2ee770a1356ff7da39a3012aa7d2599f119
.. _9926083: https://github.com/vprivat-ads/eodag/commit/99260837837c3b5f2eeac8b95dc2b2feae7a0390
.. _99cb67b: https://github.com/vprivat-ads/eodag/commit/99cb67b58c62e60c67dd557afb17a7d71f1e38a1
.. _99db80a: https://github.com/vprivat-ads/eodag/commit/99db80a896fa443dcff89602ff84d2b5c78507ad
.. _99df712: https://github.com/vprivat-ads/eodag/commit/99df71295a9a4c9f03bcb05cec814c4f50e43fb2
.. _99e6ab8: https://github.com/vprivat-ads/eodag/commit/99e6ab8fda3847bd8478bc8cc40688923ed13b49
.. _9a16a50: https://github.com/vprivat-ads/eodag/commit/9a16a500177d10d53ab60d7a3affda860ce3e2a8
.. _9a31d66: https://github.com/vprivat-ads/eodag/commit/9a31d66f2d7d17068c545cf104c9ab7194b3ce5e
.. _9a7b44c: https://github.com/vprivat-ads/eodag/commit/9a7b44c12a3e12c998a8fbc60a765e8ee6b474f5
.. _9a838c1: https://github.com/vprivat-ads/eodag/commit/9a838c180bda36181a305aed43d122102087825c
.. _9aaf0cd: https://github.com/vprivat-ads/eodag/commit/9aaf0cde61eba89c60209b7f29765f75bf72b9b9
.. _9abe670: https://github.com/vprivat-ads/eodag/commit/9abe670945a70878ed7de5c53c46e5d5776e96c1
.. _9ac8d6a: https://github.com/vprivat-ads/eodag/commit/9ac8d6a3f06ad1112c6dd3aeccb2f63eaa49c3c0
.. _9acf017: https://github.com/vprivat-ads/eodag/commit/9acf017451f71c5488011f3add086a9936cfffc8
.. _9b4fd08: https://github.com/vprivat-ads/eodag/commit/9b4fd08d2cd7f8431e2e67d9f514b67e86450817
.. _9b626a9: https://github.com/vprivat-ads/eodag/commit/9b626a91c7563d505632c830a98d18993ec95199
.. _9b6f422: https://github.com/vprivat-ads/eodag/commit/9b6f4221139e79878b4cd212f3d0d937cf26cdae
.. _9b95224: https://github.com/vprivat-ads/eodag/commit/9b952243e3164f430e9799d082d18e049d54b6cb
.. _9bbad5b: https://github.com/vprivat-ads/eodag/commit/9bbad5b0702da67fbad0c58d7153e7720a849d11
.. _9bebfed: https://github.com/vprivat-ads/eodag/commit/9bebfedfa9a98e72efabfe420b7035e90e7fd640
.. _9c076ef: https://github.com/vprivat-ads/eodag/commit/9c076efb561e31099276aa954ec02b2cc7c47568
.. _9c0d7e7: https://github.com/vprivat-ads/eodag/commit/9c0d7e7b2f2c3bcbeac6f6b710e3efd03ed78379
.. _9c1a67c: https://github.com/vprivat-ads/eodag/commit/9c1a67c1cce787536771dc3c063e41d1c749c9f9
.. _9c6b891: https://github.com/vprivat-ads/eodag/commit/9c6b8919d5e6dd7efaead4455a89447bec86fda6
.. _9cf737b: https://github.com/vprivat-ads/eodag/commit/9cf737b2a5637a85f9da974c42e2494582b97c5f
.. _9d04c9b: https://github.com/vprivat-ads/eodag/commit/9d04c9bd9757f469db0f010b457c5a90ef31ccae
.. _9d0e561: https://github.com/vprivat-ads/eodag/commit/9d0e5617200c2035563c25a793caa8355b89e4ba
.. _9d5caba: https://github.com/vprivat-ads/eodag/commit/9d5caba74657b84a471b7e0392617c370c5f0ed1
.. _9e6e51d: https://github.com/vprivat-ads/eodag/commit/9e6e51dd3a6cacf02ac232860cb40a8059ab39c4
.. _9e881ac: https://github.com/vprivat-ads/eodag/commit/9e881acd332eeb36257ae1746bb0d925517c7d3a
.. _9ea3f35: https://github.com/vprivat-ads/eodag/commit/9ea3f35a9a1a2bd1e3de38585c01bfa727065dc4
.. _9ebb872: https://github.com/vprivat-ads/eodag/commit/9ebb87297d464d06430dd5271c20b44e0df9b14c
.. _9fe7fb2: https://github.com/vprivat-ads/eodag/commit/9fe7fb25ca8afe79095633d66b8d7320c2efe383
.. _a003087: https://github.com/vprivat-ads/eodag/commit/a00308772c359998bff5fa04549a4f14bdd0026e
.. _a043e2a: https://github.com/vprivat-ads/eodag/commit/a043e2acbfc2872ef8381adadc498ba3bee320fc
.. _a0ba8d4: https://github.com/vprivat-ads/eodag/commit/a0ba8d4255d7a0c872b8f2cff832ebcc59c5acf0
.. _a0da7e4: https://github.com/vprivat-ads/eodag/commit/a0da7e412a1f7946f56190153624b7516403835d
.. _a10c807: https://github.com/vprivat-ads/eodag/commit/a10c807e255da89c0138368a2d1592d204f9a7f4
.. _a157358: https://github.com/vprivat-ads/eodag/commit/a157358fa85e88b09ded3f05e02f463c05bd8cbd
.. _a1f8cef: https://github.com/vprivat-ads/eodag/commit/a1f8cef80b983b9e7c56660249ac53067ff6617c
.. _a2466ae: https://github.com/vprivat-ads/eodag/commit/a2466ae68ecd0d5772e4f4ae9a60c5ee944c1971
.. _a2506e6: https://github.com/vprivat-ads/eodag/commit/a2506e6f92bccd0a6730480ebac98ca9257a5322
.. _a27c188: https://github.com/vprivat-ads/eodag/commit/a27c188c33be6115caac3237f4e699afc60943c1
.. _a28a40b: https://github.com/vprivat-ads/eodag/commit/a28a40bc7ebc24735f71d61fb6296420198f0a4e
.. _a29e7a7: https://github.com/vprivat-ads/eodag/commit/a29e7a744de8085868192952e675aa685a87b1d3
.. _a2c8b01: https://github.com/vprivat-ads/eodag/commit/a2c8b01656f373a05eedfafdcabe01fd68b3a21f
.. _a399a5b: https://github.com/vprivat-ads/eodag/commit/a399a5b1d5457cdfcab355f8e2b4c440982ba65f
.. _a3c8e2b: https://github.com/vprivat-ads/eodag/commit/a3c8e2b0c35491c3e399656391ea05deaa9fee52
.. _a3dc5d5: https://github.com/vprivat-ads/eodag/commit/a3dc5d53178cc613295b34bfb6e2ce98a6c9fed2
.. _a3e2572: https://github.com/vprivat-ads/eodag/commit/a3e25729a80e044f0745f537a8e07716a7a25a81
.. _a456422: https://github.com/vprivat-ads/eodag/commit/a456422efb7f912bfc50c1c1e62342eca95b3edb
.. _a47806e: https://github.com/vprivat-ads/eodag/commit/a47806ed24bb4bee18d53559e6582d2bd89a8a28
.. _a5c6389: https://github.com/vprivat-ads/eodag/commit/a5c6389823101998a01071abe6c35f27dfc1cb3c
.. _a5e1620: https://github.com/vprivat-ads/eodag/commit/a5e16201b59b6234bdce58353dd8b85ca00f6c65
.. _a65a6bc: https://github.com/vprivat-ads/eodag/commit/a65a6bcafd45896a278ddbb48c766dbc73f77eb8
.. _a65bae4: https://github.com/vprivat-ads/eodag/commit/a65bae4fed6a92e5fd729db863fc97386977c501
.. _a66523f: https://github.com/vprivat-ads/eodag/commit/a66523fc019f861927667702ee2142e088ffdb4f
.. _a6be03b: https://github.com/vprivat-ads/eodag/commit/a6be03b6f51ce35987b926bf4f721e68a1e27538
.. _a721a4e: https://github.com/vprivat-ads/eodag/commit/a721a4e9d3461ef431805489394c0ebf164ab6f8
.. _a769ab6: https://github.com/vprivat-ads/eodag/commit/a769ab66c8890633645e702dcdce4491c92a6cc6
.. _a8261af: https://github.com/vprivat-ads/eodag/commit/a8261afb2bb2129a152f6a498843bd015883f038
.. _a8522fd: https://github.com/vprivat-ads/eodag/commit/a8522fd96835becbcf2eecba4cbb5aaac492301e
.. _a9234e4: https://github.com/vprivat-ads/eodag/commit/a9234e4f72df7d8ab064a32e1db5376c0c45801b
.. _a93c2c7: https://github.com/vprivat-ads/eodag/commit/a93c2c7ec99d5923aa550bf4a2eb76a7c9ac7e3b
.. _a943c6c: https://github.com/vprivat-ads/eodag/commit/a943c6c099e488a926c2cc2e305f8b53299bb180
.. _a944aab: https://github.com/vprivat-ads/eodag/commit/a944aab4675310576ba64d8bc0f634ceb95c3f4b
.. _a958dae: https://github.com/vprivat-ads/eodag/commit/a958dae2af30d999ea225d1232e386806657ab27
.. _a9c30da: https://github.com/vprivat-ads/eodag/commit/a9c30da9978d69ef55b384c7b401195df0cf5afd
.. _aa09d73: https://github.com/vprivat-ads/eodag/commit/aa09d7315921b1ad74353f7d444f4c8d535c9d6d
.. _aa3bb3c: https://github.com/vprivat-ads/eodag/commit/aa3bb3c47a6517fc056fe1c09de26de7b62973b7
.. _aa764c0: https://github.com/vprivat-ads/eodag/commit/aa764c0b1f8bf52657186bc824a5d68c10ae091c
.. _aa88fa6: https://github.com/vprivat-ads/eodag/commit/aa88fa6a5062bd2851fcf9829911a549e217bd0b
.. _aac44a6: https://github.com/vprivat-ads/eodag/commit/aac44a61ad42133c1e32224e0699dc6eb32e5ff3
.. _ab04612: https://github.com/vprivat-ads/eodag/commit/ab046125d1241adc164e8ffdec430b5d77d8193b
.. _ab1c105: https://github.com/vprivat-ads/eodag/commit/ab1c1054e802d7a25980c331eb19a1c48f1ffc53
.. _ab57fc9: https://github.com/vprivat-ads/eodag/commit/ab57fc9c5c14b57d513271ad89955afe0235083d
.. _aba8f47: https://github.com/vprivat-ads/eodag/commit/aba8f47051d292cfd77ae42fcab7d204e9c2dabc
.. _abeb932: https://github.com/vprivat-ads/eodag/commit/abeb9323fcae0eb85f033adcdae895b3ec300b5b
.. _abf8c71: https://github.com/vprivat-ads/eodag/commit/abf8c71bdbb7b3bcc27371b85f47261c489e3650
.. _ac4edeb: https://github.com/vprivat-ads/eodag/commit/ac4edebf1b9c3bc699522bd890870557938a7a1b
.. _ac53539: https://github.com/vprivat-ads/eodag/commit/ac53539c4aed0c580fb80e0d2c2036af60e1aeca
.. _ace638f: https://github.com/vprivat-ads/eodag/commit/ace638ff0a6ae55aa77788a62c0b95b777e124ea
.. _acf207e: https://github.com/vprivat-ads/eodag/commit/acf207e2af4706e7c4f6e2e7dc5eac40b8c4a796
.. _acfbc8e: https://github.com/vprivat-ads/eodag/commit/acfbc8e39a2a13a1f632c9e0c9e0b874d781f6af
.. _ad46243: https://github.com/vprivat-ads/eodag/commit/ad46243a9591d2d27ea9f3c681d80bbac53e55ed
.. _ad57a81: https://github.com/vprivat-ads/eodag/commit/ad57a811eaa87e34143a8fda7bcc8d8afd5563ed
.. _ada6797: https://github.com/vprivat-ads/eodag/commit/ada67975003874095543df3da570984d26ba1b7b
.. _ae475d6: https://github.com/vprivat-ads/eodag/commit/ae475d6b12305d81a6dda8cdb1031be5c1c4bd21
.. _ae88aa9: https://github.com/vprivat-ads/eodag/commit/ae88aa951a5cd4840d8a735a20181c3bf64ffdde
.. _ae93d5a: https://github.com/vprivat-ads/eodag/commit/ae93d5a6c58476dad2461d9dde663aa31356dff9
.. _af5e548: https://github.com/vprivat-ads/eodag/commit/af5e54849215055791f184d3b211bf464f6ec132
.. _af6d959: https://github.com/vprivat-ads/eodag/commit/af6d959fec6fa009677ac429c70bb3004b066671
.. _af9afc8: https://github.com/vprivat-ads/eodag/commit/af9afc8f4e21f6af129c10a1763fb560ac0dfbe2
.. _b0253f3: https://github.com/vprivat-ads/eodag/commit/b0253f32b4def3f53421936de9b1bd0abe800489
.. _b0b3799: https://github.com/vprivat-ads/eodag/commit/b0b37992c9d49d7e5743f2a638f84f47f1de440e
.. _b21735a: https://github.com/vprivat-ads/eodag/commit/b21735af3aeaa616c3396a0f9ee177a807319e82
.. _b242061: https://github.com/vprivat-ads/eodag/commit/b242061f4f7d73cc4d1681f891d1aeb0663a6504
.. _b247f5c: https://github.com/vprivat-ads/eodag/commit/b247f5c9f1a0573cce408c48ff07b9fd50916671
.. _b28d179: https://github.com/vprivat-ads/eodag/commit/b28d179ded2588e0f44b131bfa959c7482139ff5
.. _b2c1467: https://github.com/vprivat-ads/eodag/commit/b2c1467fa2b84dfa7c617a6726b3e3c61d479593
.. _b2c6a50: https://github.com/vprivat-ads/eodag/commit/b2c6a50cde181ad0a642340baebe9fbf14a6c60b
.. _b2e448f: https://github.com/vprivat-ads/eodag/commit/b2e448f617651aff2014db0cf37385414e91d55a
.. _b3af807: https://github.com/vprivat-ads/eodag/commit/b3af807a732ae753d049d41f8181af0b32bbfe03
.. _b3c0263: https://github.com/vprivat-ads/eodag/commit/b3c0263863e976639e0355395f5e132836c625f1
.. _b3e40f6: https://github.com/vprivat-ads/eodag/commit/b3e40f6dccf92562902a067593ac8996f8f3e618
.. _b428d61: https://github.com/vprivat-ads/eodag/commit/b428d61405e2a24a59756016bade3788841c89dd
.. _b471693: https://github.com/vprivat-ads/eodag/commit/b471693a08c7ed3c7c2c12449a8d29bc09352ba6
.. _b487473: https://github.com/vprivat-ads/eodag/commit/b4874734c0ac5a8ff2d643d7bee680d2addfa6c3
.. _b49dfce: https://github.com/vprivat-ads/eodag/commit/b49dfceb9eaffdbb14bfea9c00929ed5ea71cccd
.. _b4c8b9f: https://github.com/vprivat-ads/eodag/commit/b4c8b9f7d1082bbd30e7870ef0a5288a135d8e38
.. _b507413: https://github.com/vprivat-ads/eodag/commit/b507413aa272f36a724fe1d09a4b54ae495bdeb0
.. _b5486f7: https://github.com/vprivat-ads/eodag/commit/b5486f719e4169bca5ce7701ed9b22c9dd0b44d9
.. _b54f8d5: https://github.com/vprivat-ads/eodag/commit/b54f8d566be4747c411f6683c9d27b4a4368eae6
.. _b57fc76: https://github.com/vprivat-ads/eodag/commit/b57fc768c1a08e1e255b8fa44b3785255bc8ca23
.. _b61e2a0: https://github.com/vprivat-ads/eodag/commit/b61e2a032fd9a66cced767223761dd0f432f9bd5
.. _b665dd4: https://github.com/vprivat-ads/eodag/commit/b665dd4c448d773b243c2ded09efdd5d0bda1248
.. _b66ad3b: https://github.com/vprivat-ads/eodag/commit/b66ad3bfbfca5c51cf3462f6ca2250c10be7dafe
.. _b69375c: https://github.com/vprivat-ads/eodag/commit/b69375cd03463e28087303230fdc3e9857d5e0e1
.. _b6ca196: https://github.com/vprivat-ads/eodag/commit/b6ca1968d60d6123e818f1eec06fc1fa386e465a
.. _b6dd367: https://github.com/vprivat-ads/eodag/commit/b6dd367341798de4202147376887c394c2794207
.. _b71183e: https://github.com/vprivat-ads/eodag/commit/b71183ebcf57a751a8081a1445e84a19fad29f43
.. _b717e45: https://github.com/vprivat-ads/eodag/commit/b717e456fb23e59e9dfb6a99b5e30b697be73232
.. _b7192b1: https://github.com/vprivat-ads/eodag/commit/b7192b14840d27a3558f4dc5dff0b99ea6c0d833
.. _b785e7c: https://github.com/vprivat-ads/eodag/commit/b785e7c15c8dc60efbe0f38ac4d6487d8917b1aa
.. _b7ae557: https://github.com/vprivat-ads/eodag/commit/b7ae55777753554516c0bf42422db3274bbd5eb1
.. _b7cc06e: https://github.com/vprivat-ads/eodag/commit/b7cc06e19025e5bbf14e28a0975f1749e21e9be3
.. _b7fe6b1: https://github.com/vprivat-ads/eodag/commit/b7fe6b152341fdecbbf3b4c3d4c21b09393822a8
.. _b800cac: https://github.com/vprivat-ads/eodag/commit/b800cacb931478fa73798d3bf88553c4de655296
.. _b80ea0f: https://github.com/vprivat-ads/eodag/commit/b80ea0f05cb45afc45b71a62b0f39e7a585e86c6
.. _b8128f1: https://github.com/vprivat-ads/eodag/commit/b8128f1348eaea9a48bf8c99ad18b8dd5a5c2a6a
.. _b826f21: https://github.com/vprivat-ads/eodag/commit/b826f21453e086ab90dbcbb1e06dcbaa5cf9d6cc
.. _b85ef0f: https://github.com/vprivat-ads/eodag/commit/b85ef0f360e805a61c2a7e9826a3cd7df4183315
.. _b871978: https://github.com/vprivat-ads/eodag/commit/b871978c5374fe3d1d3372cf4a0dbbaf4be6d099
.. _b8db03b: https://github.com/vprivat-ads/eodag/commit/b8db03b263c8523bb9d100c95d924202851794a4
.. _b912305: https://github.com/vprivat-ads/eodag/commit/b912305ee2bd1995c8cad9c79a2846344f1d5a25
.. _b93c4c8: https://github.com/vprivat-ads/eodag/commit/b93c4c88f323af0eecb0950c90c6862ca9a7c3f4
.. _b94e3e1: https://github.com/vprivat-ads/eodag/commit/b94e3e18768d308acb6c229c27f6a9c7a3fab268
.. _ba515f3: https://github.com/vprivat-ads/eodag/commit/ba515f30b6ee97ad8471b1edf2f5af5b70fe1c39
.. _ba7f655: https://github.com/vprivat-ads/eodag/commit/ba7f6555ce49c2cef428ec24c959da71e8e6e603
.. _baa5f84: https://github.com/vprivat-ads/eodag/commit/baa5f84dece41575d9f94a112f34ad354a290a55
.. _bab1b7e: https://github.com/vprivat-ads/eodag/commit/bab1b7e9c81e096d62ef6b5a2a736445c3b546d7
.. _bad38f8: https://github.com/vprivat-ads/eodag/commit/bad38f877e6b9f3cc76a1fc9f0ec37e15dc3bd2f
.. _baeafb4: https://github.com/vprivat-ads/eodag/commit/baeafb4d331f782dcbfd8e16cd6ec7242f6e687f
.. _baf2298: https://github.com/vprivat-ads/eodag/commit/baf2298a7c7ef7b4f423cef48df01901db1b8d35
.. _bb6dca4: https://github.com/vprivat-ads/eodag/commit/bb6dca41fd5f6d20afbfba67c0a0aa2187ce37af
.. _bb95da0: https://github.com/vprivat-ads/eodag/commit/bb95da00eb6f1b62920ff6d41c54fee5e0d46370
.. _bb9ee42: https://github.com/vprivat-ads/eodag/commit/bb9ee4253dfa9d735c38e102b091aa83cf903b90
.. _bbcc7ba: https://github.com/vprivat-ads/eodag/commit/bbcc7ba311fcf25a0231203035166276e704ec8e
.. _bbd367a: https://github.com/vprivat-ads/eodag/commit/bbd367a473c015928db5344b1df70ae1cbb56863
.. _bbf8587: https://github.com/vprivat-ads/eodag/commit/bbf8587043eb0a419242234dfd15486e435a510e
.. _bc1953a: https://github.com/vprivat-ads/eodag/commit/bc1953ab88bee1cff638872ead8239a4ac4433f2
.. _bc21b08: https://github.com/vprivat-ads/eodag/commit/bc21b08fc27d34935134b66e6d056dfe2d6de00a
.. _bc932d6: https://github.com/vprivat-ads/eodag/commit/bc932d60f2b0fc4df4c4e4dc0b1bb390427c5be2
.. _bcc793e: https://github.com/vprivat-ads/eodag/commit/bcc793e83ae6c7fec3e282046e4516510e9015fb
.. _bd351ec: https://github.com/vprivat-ads/eodag/commit/bd351ec791b91862944e1eeff9f89483cb85ce86
.. _bd59008: https://github.com/vprivat-ads/eodag/commit/bd59008d0bf2ec8ffe9c8daf3b882587c8775ba3
.. _bd79ff7: https://github.com/vprivat-ads/eodag/commit/bd79ff731b9abf637af37aa488e527f44f4e5821
.. _be026c2: https://github.com/vprivat-ads/eodag/commit/be026c211b2ef28ceb8b13437a8eceaf4245689b
.. _be370c7: https://github.com/vprivat-ads/eodag/commit/be370c745bc736536b076e37baad43e906cf49c4
.. _be7d098: https://github.com/vprivat-ads/eodag/commit/be7d098548f26ca2f351b88cba1799faa99d1c94
.. _be8f361: https://github.com/vprivat-ads/eodag/commit/be8f361153d017dd06e048dfc63fcfce278319c6
.. _beb6c1f: https://github.com/vprivat-ads/eodag/commit/beb6c1f7095b7f1401e3c7964b0d8e5964cf9cc4
.. _bf33e4c: https://github.com/vprivat-ads/eodag/commit/bf33e4c5105bbd28c7221094ea9c039820ab3afe
.. _bf8cbe1: https://github.com/vprivat-ads/eodag/commit/bf8cbe1bd1ade032a1a7abdc17f3785a11fca5d9
.. _bf9b8e9: https://github.com/vprivat-ads/eodag/commit/bf9b8e948f0912aa9aaea3f1317041736ebd5fa6
.. _bfe347d: https://github.com/vprivat-ads/eodag/commit/bfe347db7216ece9df232d70e11babc17b2c1a04
.. _bfe5e71: https://github.com/vprivat-ads/eodag/commit/bfe5e712087804d31fe7f057e5efbd1d2863fb36
.. _c043500: https://github.com/vprivat-ads/eodag/commit/c043500cd6aa80303c2d961e08f3e6769d8eba3b
.. _c060011: https://github.com/vprivat-ads/eodag/commit/c06001160e00c8f4aa19811f5e7ec3bd85eaeb89
.. _c068ff8: https://github.com/vprivat-ads/eodag/commit/c068ff83569388eda41d1d22cf79daa1fdaf4192
.. _c08c053: https://github.com/vprivat-ads/eodag/commit/c08c0537a5ed873439db25f6fb50b52d9b4c552c
.. _c14d345: https://github.com/vprivat-ads/eodag/commit/c14d345e320f5f6cfa19c62583461fc2e971a1a2
.. _c159fd0: https://github.com/vprivat-ads/eodag/commit/c159fd00c246f021e28d5f9d9f0230ea6a55e7af
.. _c2531ce: https://github.com/vprivat-ads/eodag/commit/c2531ce9744824324d6d03fa7e8ea9ea9ee00e58
.. _c28ab8f: https://github.com/vprivat-ads/eodag/commit/c28ab8fc4b997873fbbd3095a33d9fe7f5427b84
.. _c328060: https://github.com/vprivat-ads/eodag/commit/c328060affc212afe4a9e66f80f04854d4ec774d
.. _c3429d8: https://github.com/vprivat-ads/eodag/commit/c3429d897e59bd8491a524d06b8c706d247a35ec
.. _c38d36e: https://github.com/vprivat-ads/eodag/commit/c38d36ec0be2c490d04060030c10726ecf327972
.. _c38ef08: https://github.com/vprivat-ads/eodag/commit/c38ef0817f259a80417cc3d22c19621db11e2344
.. _c42cf9c: https://github.com/vprivat-ads/eodag/commit/c42cf9c9ddeeeb8fb10757c04823f527406e9862
.. _c4393b5: https://github.com/vprivat-ads/eodag/commit/c4393b56ac5f8ad6101367ed67a969ff39a1edc1
.. _c44a5b8: https://github.com/vprivat-ads/eodag/commit/c44a5b8efc1a45c376155c4289cc6f47360ea088
.. _c4e649c: https://github.com/vprivat-ads/eodag/commit/c4e649cdadda539be517797d2668638c19b486c8
.. _c50aae1: https://github.com/vprivat-ads/eodag/commit/c50aae12b344d81f66fc20a9a930b7718e0b12b7
.. _c54f68b: https://github.com/vprivat-ads/eodag/commit/c54f68b9935c005b58396cea85999e7bb0676c35
.. _c5534d1: https://github.com/vprivat-ads/eodag/commit/c5534d170ac87c064c4616331457f1003523d887
.. _c564fdd: https://github.com/vprivat-ads/eodag/commit/c564fdd2b5a4f968bf2f58c916cf094bcf378008
.. _c5805cf: https://github.com/vprivat-ads/eodag/commit/c5805cffe3798db35c78bb2e6b4478d057fca11c
.. _c580617: https://github.com/vprivat-ads/eodag/commit/c5806179578bf4887ace271b5b284788e364b917
.. _c59e264: https://github.com/vprivat-ads/eodag/commit/c59e2649a3c5f18d4debd034b4c7d11947acd6e6
.. _c630b30: https://github.com/vprivat-ads/eodag/commit/c630b30b4ceedd773843927f1e729f5a8716641a
.. _c63e4c7: https://github.com/vprivat-ads/eodag/commit/c63e4c70e854dfcca8eef3ebc4b7a924ec73eeeb
.. _c667e72: https://github.com/vprivat-ads/eodag/commit/c667e72bcff1fd6357894ae6f27dbb4c5e1c3d2b
.. _c6c9d06: https://github.com/vprivat-ads/eodag/commit/c6c9d06772e6ade9c8acf049b09945a37737dc39
.. _c6fc141: https://github.com/vprivat-ads/eodag/commit/c6fc141ff43b2183690d433e8dff89d27c65ad80
.. _c75351d: https://github.com/vprivat-ads/eodag/commit/c75351d9b74ffa1cab3746a04637eb0de1a9f642
.. _c7b8e24: https://github.com/vprivat-ads/eodag/commit/c7b8e24d8970ac2889732304968df9e1e214f69b
.. _c7c150b: https://github.com/vprivat-ads/eodag/commit/c7c150baa10cd88bbc4effeebc6abb0ef2da685e
.. _c7d09b5: https://github.com/vprivat-ads/eodag/commit/c7d09b5943b8919db7f268623cf73ef23e35e4e7
.. _c8189af: https://github.com/vprivat-ads/eodag/commit/c8189af1c9f9f68ed793d9eadfba62028ae6d8d1
.. _c83d889: https://github.com/vprivat-ads/eodag/commit/c83d889286c67678bc556043e11e19f34da10b99
.. _c8733ce: https://github.com/vprivat-ads/eodag/commit/c8733ce3c026417eaa318a498c752381053a1fd7
.. _c89cf52: https://github.com/vprivat-ads/eodag/commit/c89cf52893de68b3fd7912858dd02a76fe6a0ea3
.. _c8ef1b9: https://github.com/vprivat-ads/eodag/commit/c8ef1b9536a4ac91479dc0d9e6cdf04da6f533f0
.. _c8f75c5: https://github.com/vprivat-ads/eodag/commit/c8f75c530602e6a4bf4a7872e22bbb6ea3b6e8fa
.. _c91cba7: https://github.com/vprivat-ads/eodag/commit/c91cba779c1913985640b99e2c019c9c000bb4a0
.. _c925f7a: https://github.com/vprivat-ads/eodag/commit/c925f7aac756a06bd9ead5892e2bf2d0cd8b632d
.. _c99e3be: https://github.com/vprivat-ads/eodag/commit/c99e3bec15a3a8964dd39d5e6152a49d8152515e
.. _c9a324b: https://github.com/vprivat-ads/eodag/commit/c9a324ba000655bd69b64ea1cf8db91f20a6e015
.. _c9bba53: https://github.com/vprivat-ads/eodag/commit/c9bba53129226aef77466f1e34457eb4cd1046cc
.. _c9be6ab: https://github.com/vprivat-ads/eodag/commit/c9be6ab0460b88e30c166eb7e5b9b01cf34762fd
.. _c9fd10d: https://github.com/vprivat-ads/eodag/commit/c9fd10d0fc241193ae65f2f608b31bd581922876
.. _ca5c824: https://github.com/vprivat-ads/eodag/commit/ca5c82413691626093080f0cb47d9c19172b7b93
.. _cacdee3: https://github.com/vprivat-ads/eodag/commit/cacdee35f9cb42166168a2e5af91997bac072d07
.. _caff0bc: https://github.com/vprivat-ads/eodag/commit/caff0bc12f7fa4af8238030af43700b5bd6d8c0e
.. _cb0217b: https://github.com/vprivat-ads/eodag/commit/cb0217b5772a44fd7ffb384f0eda96fbd48e9bea
.. _cbce353: https://github.com/vprivat-ads/eodag/commit/cbce3538e142a6d6526478befd9700a2016351b9
.. _cbe3238: https://github.com/vprivat-ads/eodag/commit/cbe32384ccfcfafbee0e4e2a988408feac3bd832
.. _cc1f51b: https://github.com/vprivat-ads/eodag/commit/cc1f51b2da7eafd3fa077fc21914081bcd227b4a
.. _cc33191: https://github.com/vprivat-ads/eodag/commit/cc331917e9b54bfebbc6918e4e4a2d9458200d66
.. _cc6ecc9: https://github.com/vprivat-ads/eodag/commit/cc6ecc9979bfee420ff75cd919c3f90ae73689bb
.. _ccf150d: https://github.com/vprivat-ads/eodag/commit/ccf150d08cdc882d8ae02e66b003d9c23e790aeb
.. _cd3b08a: https://github.com/vprivat-ads/eodag/commit/cd3b08af8d67795eb582c0076ba169f163925c35
.. _cd50894: https://github.com/vprivat-ads/eodag/commit/cd50894671f098b90dd056f27b368003ea56e5e4
.. _cd527f1: https://github.com/vprivat-ads/eodag/commit/cd527f1cad5855fa3f44ac1ebe8a2b909b40dfc2
.. _cd7ad76: https://github.com/vprivat-ads/eodag/commit/cd7ad766bf286e64dac10b3ac154f4a583961f01
.. _cd84b88: https://github.com/vprivat-ads/eodag/commit/cd84b88ff1bcb765f0b7ecd4d67fea1b06bc403e
.. _cda35ec: https://github.com/vprivat-ads/eodag/commit/cda35ecda90edb10fe82e50633f2a8886b1528d1
.. _cdaac24: https://github.com/vprivat-ads/eodag/commit/cdaac241ecb7a08c46cda6f6c8eba845e5842064
.. _cdb3a17: https://github.com/vprivat-ads/eodag/commit/cdb3a17047462037ea98eb31b0481e82dd62a438
.. _cdee784: https://github.com/vprivat-ads/eodag/commit/cdee784fa2d227c8e908610422140188df4ed142
.. _cdfe518: https://github.com/vprivat-ads/eodag/commit/cdfe518f2b392b700994f93d2c2d6cafdb46b81d
.. _ce6d103: https://github.com/vprivat-ads/eodag/commit/ce6d103450676c5d1a736500cdb803e1aa5c47f5
.. _ce74f22: https://github.com/vprivat-ads/eodag/commit/ce74f222f6d9f646f9d35321072db2b18d7ea24f
.. _ce84b33: https://github.com/vprivat-ads/eodag/commit/ce84b330b88552a36c351928d053c4aa6ed6824e
.. _ce877a6: https://github.com/vprivat-ads/eodag/commit/ce877a6049b5da10cd650940d5eaf4366332e9b9
.. _ce9b54a: https://github.com/vprivat-ads/eodag/commit/ce9b54a672a7055432b2c2905da86e1f49647c35
.. _cea9a93: https://github.com/vprivat-ads/eodag/commit/cea9a937476321d9dd944e8ea08495fa8e616854
.. _cebac98: https://github.com/vprivat-ads/eodag/commit/cebac98290221b1edca0b314b70f587e1b6aa55d
.. _cecc9d8: https://github.com/vprivat-ads/eodag/commit/cecc9d81cc260b46bd88d2ba0e18497c9f62e9f4
.. _cf2f643: https://github.com/vprivat-ads/eodag/commit/cf2f643b18d6cff0d2472e7436bb5d92536b75b0
.. _cfc291f: https://github.com/vprivat-ads/eodag/commit/cfc291ff30ab84fcf4f11798dc012437b6154d1c
.. _cfc4bca: https://github.com/vprivat-ads/eodag/commit/cfc4bca17c330be3f91f96b67bf867e37c402272
.. _d002c38: https://github.com/vprivat-ads/eodag/commit/d002c38126f566f52903fb0e5012a22e771c3200
.. _d071212: https://github.com/vprivat-ads/eodag/commit/d0712120014ee1a20eed0f0b4d772ac344f2e308
.. _d0869f9: https://github.com/vprivat-ads/eodag/commit/d0869f9105cb2051a8976245f1896f4b919c40b0
.. _d11af66: https://github.com/vprivat-ads/eodag/commit/d11af6601cf25f195c247eb28162c7904fde8656
.. _d128d9c: https://github.com/vprivat-ads/eodag/commit/d128d9c1ee839d08fcdd12e0e3685b3bb6aa462e
.. _d148e50: https://github.com/vprivat-ads/eodag/commit/d148e50926ad4c29a2a338a74e1751ef21d8b5f1
.. _d175b32: https://github.com/vprivat-ads/eodag/commit/d175b32dc96732d754bcb09f3f2f2a78011f1af3
.. _d18287d: https://github.com/vprivat-ads/eodag/commit/d18287d37a7deb98457d7068402218983150c7f8
.. _d1b8f36: https://github.com/vprivat-ads/eodag/commit/d1b8f36f9b357308373095d8848f3a68fe090c65
.. _d1df25e: https://github.com/vprivat-ads/eodag/commit/d1df25ec4c7b97eb4b4543c6e8f919121919967c
.. _d1e649e: https://github.com/vprivat-ads/eodag/commit/d1e649e084f784600c2fceb09a684576206615c5
.. _d207f27: https://github.com/vprivat-ads/eodag/commit/d207f2701b472b8c6c75da5c63f0621736dedd8a
.. _d238c08: https://github.com/vprivat-ads/eodag/commit/d238c0853d29b5c2cc3a594f60a6e6e6ce6ad3ea
.. _d2435ae: https://github.com/vprivat-ads/eodag/commit/d2435ae1fd1677f7b82962c6a47b724f7bb92cc5
.. _d24377f: https://github.com/vprivat-ads/eodag/commit/d24377f36b8defd8e2ef78dd42ee8c451464e9c3
.. _d24850a: https://github.com/vprivat-ads/eodag/commit/d24850aee464afd938875be5d316955035ddb8e1
.. _d278e12: https://github.com/vprivat-ads/eodag/commit/d278e12087d8e7aae17e9ba46c798e1bd8f5b4cd
.. _d2817ce: https://github.com/vprivat-ads/eodag/commit/d2817ce1603a1b17855d0a284d8a29f0adb79e5b
.. _d29137d: https://github.com/vprivat-ads/eodag/commit/d29137de503d099615839d79c34799b7290284e7
.. _d2a7386: https://github.com/vprivat-ads/eodag/commit/d2a738611ea795d0a3f3a38f825bfed1252a9ded
.. _d2b436a: https://github.com/vprivat-ads/eodag/commit/d2b436a45aff991233f68e60dc1f02d6286f0cc3
.. _d2cd928: https://github.com/vprivat-ads/eodag/commit/d2cd928e9e887e88db639e3ebb02d4e006c0f653
.. _d2f4b61: https://github.com/vprivat-ads/eodag/commit/d2f4b61ed8b7e76455f68b54e93a38fb9220356f
.. _d2fc110: https://github.com/vprivat-ads/eodag/commit/d2fc1100c700fe1819e7cb2190ca4b3cf16dd1fa
.. _d325727: https://github.com/vprivat-ads/eodag/commit/d325727bf6728d117876684104ba60a4d0fc3cc2
.. _d378061: https://github.com/vprivat-ads/eodag/commit/d3780617dcd1fbcb80d0c3e32b537f893a98ac48
.. _d38035f: https://github.com/vprivat-ads/eodag/commit/d38035f63dc9a57136a5f4f295f77af0870914d2
.. _d3ada37: https://github.com/vprivat-ads/eodag/commit/d3ada3735d2afd76ec44d4dd70cf93db59b6ed0f
.. _d4bd54e: https://github.com/vprivat-ads/eodag/commit/d4bd54e656d6f356961230f9b383e5c85bf92b80
.. _d4d6bdf: https://github.com/vprivat-ads/eodag/commit/d4d6bdf136a0d5a8e0cc0e8e03ddbb0b6a6e494d
.. _d4f8379: https://github.com/vprivat-ads/eodag/commit/d4f8379b90c02346506bdb53ded4c06ef128df31
.. _d4fffce: https://github.com/vprivat-ads/eodag/commit/d4fffce9823ec078c557a222aaf9407ba7406bad
.. _d50b378: https://github.com/vprivat-ads/eodag/commit/d50b378f8de6ad328cdfae694ba76a9dfbdb3d09
.. _d513572: https://github.com/vprivat-ads/eodag/commit/d513572bafbdd45344b8b24c69acc8940e2175ef
.. _d548ac0: https://github.com/vprivat-ads/eodag/commit/d548ac088f8f74891890775a8b9bb03d71eab5e4
.. _d549c5a: https://github.com/vprivat-ads/eodag/commit/d549c5ace03685f6528fbe69a34f845842ecae98
.. _d573846: https://github.com/vprivat-ads/eodag/commit/d5738465930e08b24d562af3b7bc040464ff970a
.. _d669625: https://github.com/vprivat-ads/eodag/commit/d669625d572f4759b23f1dcd88cf9cc0e07f5c74
.. _d67aaaf: https://github.com/vprivat-ads/eodag/commit/d67aaafbfa4b36721df758029becdfd066e6c3e3
.. _d6f3f48: https://github.com/vprivat-ads/eodag/commit/d6f3f48707f630f098f566801e8b941065a5dc25
.. _d709297: https://github.com/vprivat-ads/eodag/commit/d709297eaff2aa642d454d871cac54c65bc70c2f
.. _d824947: https://github.com/vprivat-ads/eodag/commit/d824947150f3920f4ac88b10edd179990cb5f9fa
.. _d88f651: https://github.com/vprivat-ads/eodag/commit/d88f6510dc952f64262552207ee23f83212d60c9
.. _d893dec: https://github.com/vprivat-ads/eodag/commit/d893dec5e2e76a3d4b502680e48ff2386edf5474
.. _d8aefa9: https://github.com/vprivat-ads/eodag/commit/d8aefa9f27238618b16bb65965c3dd794b0d1123
.. _d8bb323: https://github.com/vprivat-ads/eodag/commit/d8bb323df1f543da09045780ab98d9231ed68246
.. _d92440f: https://github.com/vprivat-ads/eodag/commit/d92440f97e458e7d75b673b5495ff88ff5072f57
.. _d9708f9: https://github.com/vprivat-ads/eodag/commit/d9708f98c5a99e3ece37b24b556b0848463d2fe8
.. _d9f16f4: https://github.com/vprivat-ads/eodag/commit/d9f16f411fdf5eb6ad752f984782dd06ed882dc8
.. _da1039b: https://github.com/vprivat-ads/eodag/commit/da1039b2c61e4c3c489ef44fd8aa4e9c611f5118
.. _da6df3f: https://github.com/vprivat-ads/eodag/commit/da6df3fbc13912fb44e6cff3a3d1a74ac794bbec
.. _dac0046: https://github.com/vprivat-ads/eodag/commit/dac0046937df69c25978146637baf7d230519778
.. _dacb233: https://github.com/vprivat-ads/eodag/commit/dacb2333dbfbaa5bd582674e829171847963b09e
.. _dacce19: https://github.com/vprivat-ads/eodag/commit/dacce191cd15c0a188339d875e7aff2e5ef7e2b9
.. _dad8bb0: https://github.com/vprivat-ads/eodag/commit/dad8bb09fa9fdeafce7d4a103d284dfc6dd1bbf9
.. _db336eb: https://github.com/vprivat-ads/eodag/commit/db336ebe9e3359bc3549e546948ef59c54b632ae
.. _db3c4ec: https://github.com/vprivat-ads/eodag/commit/db3c4ec1720875f3396c4a847aad3afdd3369ec0
.. _db5bd23: https://github.com/vprivat-ads/eodag/commit/db5bd23326ff640b5305c591a9ccbd1e77e21a54
.. _db61d9c: https://github.com/vprivat-ads/eodag/commit/db61d9c2640bb8a3195d671b742214f4c3e02d33
.. _db70682: https://github.com/vprivat-ads/eodag/commit/db706825954deecc7f9936946bbcdccfc27159c4
.. _db83859: https://github.com/vprivat-ads/eodag/commit/db83859f9565ff101ead03fde8b85995fc3d8af8
.. _dba5c61: https://github.com/vprivat-ads/eodag/commit/dba5c617ada35a3f9b7fa6ecf08bc2dc4547884c
.. _dbc1b57: https://github.com/vprivat-ads/eodag/commit/dbc1b577d0d1a213879a6064f010ae42863dc84e
.. _dc08dbd: https://github.com/vprivat-ads/eodag/commit/dc08dbda4dcb2af872095aecc0e9064d3a59a595
.. _dc22c2e: https://github.com/vprivat-ads/eodag/commit/dc22c2e449b648b628d1dbbde3fc290be4f0b4a2
.. _dc24261: https://github.com/vprivat-ads/eodag/commit/dc24261ac6accfbd60b38de0825262c250a29a65
.. _dc9f2c9: https://github.com/vprivat-ads/eodag/commit/dc9f2c95cf67b368bff8e5a977620e96010e2f26
.. _dcdca60: https://github.com/vprivat-ads/eodag/commit/dcdca6012736f751418725312da736f61767ec36
.. _dd6069c: https://github.com/vprivat-ads/eodag/commit/dd6069c4789bcd14b8cbabee043a986f08ac2363
.. _dd8d653: https://github.com/vprivat-ads/eodag/commit/dd8d6530485fbeebe49dc0644de79ab36c475a1f
.. _dd9a2ef: https://github.com/vprivat-ads/eodag/commit/dd9a2ef78e042e131af8dc731024b618752a52ad
.. _dda2150: https://github.com/vprivat-ads/eodag/commit/dda21504db894b1e95acfb88f67033f22a322892
.. _dda681a: https://github.com/vprivat-ads/eodag/commit/dda681ae148c4fb555ab80d7ec2689dbbc8c2937
.. _ddb3c6f: https://github.com/vprivat-ads/eodag/commit/ddb3c6fa1e19c2aee7abbb998c44ed0542d7f627
.. _ddde27a: https://github.com/vprivat-ads/eodag/commit/ddde27a3313855d7e1afa391b6aef4b84a846bb6
.. _de3f873: https://github.com/vprivat-ads/eodag/commit/de3f873581b2b570b5d7b7a162b5c1491ad1db9d
.. _dea2243: https://github.com/vprivat-ads/eodag/commit/dea22430d8a055dd40484318e1c2743c1cdfffd0
.. _ded0bfe: https://github.com/vprivat-ads/eodag/commit/ded0bfe5da11e7ff4c2288abf7a9d93cc34f28c9
.. _df05c35: https://github.com/vprivat-ads/eodag/commit/df05c353836883546e47db4057123ac501e003c6
.. _df0c9b5: https://github.com/vprivat-ads/eodag/commit/df0c9b5a3dd65b9cc2c56b88071d6b13b07fe606
.. _df15f00: https://github.com/vprivat-ads/eodag/commit/df15f005a1767d69701c2f655e57c82bcd2ceed3
.. _df263c2: https://github.com/vprivat-ads/eodag/commit/df263c28042cc0aa4cdfeb88c24004aea9955cd5
.. _df3c233: https://github.com/vprivat-ads/eodag/commit/df3c233cc42832e75432d5d517944cea030f72e7
.. _df440aa: https://github.com/vprivat-ads/eodag/commit/df440aa6b35236a357ab0bbfd5d93fa94cefd3a8
.. _df67693: https://github.com/vprivat-ads/eodag/commit/df67693099f72cbaf42e008f8b5b9c5af062e573
.. _df6b4fe: https://github.com/vprivat-ads/eodag/commit/df6b4fee645c2d44507246f564cf980c63fef045
.. _df7af23: https://github.com/vprivat-ads/eodag/commit/df7af23aaa92449bc6319bf66d0c24884dd0e1e7
.. _df8c944: https://github.com/vprivat-ads/eodag/commit/df8c94465cf7ca2d1852842dc707dbacaa075e56
.. _df9f01d: https://github.com/vprivat-ads/eodag/commit/df9f01d871bb398367a103021f82c587e95ad219
.. _dfa18e7: https://github.com/vprivat-ads/eodag/commit/dfa18e7212094204000da269d039f05906dcb294
.. _dfb7a0f: https://github.com/vprivat-ads/eodag/commit/dfb7a0fb36d3e8225757248616f4399835c837df
.. _dfdfc7a: https://github.com/vprivat-ads/eodag/commit/dfdfc7aed8b5be3c2c5c3c413dfc2b909b3b2bcb
.. _e0108b2: https://github.com/vprivat-ads/eodag/commit/e0108b26f7ab8b2b5ddf810ed47838ea6d14c1b8
.. _e0774f9: https://github.com/vprivat-ads/eodag/commit/e0774f992e77774625df910fc3f8ba549fb85b96
.. _e095901: https://github.com/vprivat-ads/eodag/commit/e095901e956f1d9be431b198fd327674255741d2
.. _e0ce87b: https://github.com/vprivat-ads/eodag/commit/e0ce87bb6dae07730d169b7f53568e8bd912a8d4
.. _e100b96: https://github.com/vprivat-ads/eodag/commit/e100b96b75ee661ba6fce0555ee052b455b28705
.. _e119d93: https://github.com/vprivat-ads/eodag/commit/e119d936a4e7cf77d79ae19b49da9b6362a44510
.. _e12c166: https://github.com/vprivat-ads/eodag/commit/e12c166ecde9346dac9677ad6799c85b013c3586
.. _e161f5d: https://github.com/vprivat-ads/eodag/commit/e161f5dd5dab137f26c38baf6838c5657837ab53
.. _e1a56fd: https://github.com/vprivat-ads/eodag/commit/e1a56fd0670d0aa4ee27cd5cc8a67b5fbea20be9
.. _e1c6173: https://github.com/vprivat-ads/eodag/commit/e1c6173efc70ef9fa404eb5ab12dc644d2140410
.. _e1db471: https://github.com/vprivat-ads/eodag/commit/e1db47199d47c4988eaece7628005727dba2985f
.. _e20c12b: https://github.com/vprivat-ads/eodag/commit/e20c12b42f491f562056ab8884d1ffb8f18dd8af
.. _e21c5d7: https://github.com/vprivat-ads/eodag/commit/e21c5d75ae068e4ce1985be8561b4450b11871bf
.. _e22bc33: https://github.com/vprivat-ads/eodag/commit/e22bc33f3364bb6c4f9bfd1bb392557259063cfd
.. _e23f47e: https://github.com/vprivat-ads/eodag/commit/e23f47ee97a50c0ba1d573801a17177c88f06eae
.. _e2846dd: https://github.com/vprivat-ads/eodag/commit/e2846ddd130ffd5ddb8bd1b0b5a45bc71d92c2cb
.. _e356ed0: https://github.com/vprivat-ads/eodag/commit/e356ed05eba7a616f69cc71d469dad67fc5d9304
.. _e3be09a: https://github.com/vprivat-ads/eodag/commit/e3be09aaa2817e902a81a0accde424b04c3b7d9d
.. _e40b40d: https://github.com/vprivat-ads/eodag/commit/e40b40d910c60e7445fc2e043f21abaa12b45bca
.. _e44c9e4: https://github.com/vprivat-ads/eodag/commit/e44c9e4a29fd837fa80e4f680c83eb26ae77d7ba
.. _e470a6e: https://github.com/vprivat-ads/eodag/commit/e470a6ecbf0876d6fd2089724ccd096b579e1cef
.. _e47bd3e: https://github.com/vprivat-ads/eodag/commit/e47bd3e7c29bf1df787fe82d811e49e2eac16458
.. _e482098: https://github.com/vprivat-ads/eodag/commit/e482098bc146f610604fcf6e112cbe4cf6a79c0f
.. _e4aca26: https://github.com/vprivat-ads/eodag/commit/e4aca2672b156a6eb338e9e9a8277bc2895aa457
.. _e4d8775: https://github.com/vprivat-ads/eodag/commit/e4d87758af5d0e850f33a76b424f6dc507783097
.. _e54ba86: https://github.com/vprivat-ads/eodag/commit/e54ba8620457d4995589c4b4995b08d0cbfaaff3
.. _e564348: https://github.com/vprivat-ads/eodag/commit/e5643482cce0f5e4f71685e9bf15b07827c1cfd4
.. _e577b27: https://github.com/vprivat-ads/eodag/commit/e577b2754e9a4fde81d29fe84c4e9b1c8f97f585
.. _e5cd082: https://github.com/vprivat-ads/eodag/commit/e5cd082aa81eedb62cd48b7974362c99a6899d9c
.. _e619c88: https://github.com/vprivat-ads/eodag/commit/e619c88de826047b8f46f4485ca5537a58e60678
.. _e63cfb1: https://github.com/vprivat-ads/eodag/commit/e63cfb19ca64a2ed65f500ae9678e117a2ea4cf8
.. _e63d06d: https://github.com/vprivat-ads/eodag/commit/e63d06d69e66ecdb6a0d15ec90de84ed4cb65469
.. _e6743bb: https://github.com/vprivat-ads/eodag/commit/e6743bb5eea1936fb7e1fa7a53a4a62948952baa
.. _e68536c: https://github.com/vprivat-ads/eodag/commit/e68536c3469ab6181e96e3e8c095b1bf75b1deca
.. _e6b8a96: https://github.com/vprivat-ads/eodag/commit/e6b8a963b764895045e9832751036ce08af0cc86
.. _e6c220c: https://github.com/vprivat-ads/eodag/commit/e6c220cbafe1b7bd46453bfb6f485e6946d38dae
.. _e6e6931: https://github.com/vprivat-ads/eodag/commit/e6e6931f4cbd85f86fdc1f57fdfb8caa4241d952
.. _e71ca9c: https://github.com/vprivat-ads/eodag/commit/e71ca9cfe531b396ad042c9050f043ea84ba8e7a
.. _e73c12e: https://github.com/vprivat-ads/eodag/commit/e73c12e906318c95d0b7e912ce82f44c90091128
.. _e740d97: https://github.com/vprivat-ads/eodag/commit/e740d97a1d2940d5c8f2b26393f535c3a9fdbc78
.. _e76f4a8: https://github.com/vprivat-ads/eodag/commit/e76f4a823aa6607fbb4541fee78bf57138d1e504
.. _e7873c0: https://github.com/vprivat-ads/eodag/commit/e7873c05a43589f7c65a5fff115a1b74b1a8ee75
.. _e81013b: https://github.com/vprivat-ads/eodag/commit/e81013b262342a0621e2018a7d917145faaa2cc7
.. _e817031: https://github.com/vprivat-ads/eodag/commit/e81703104ea118a4a37ddc6d0dd177b3ae3ffdac
.. _e84f17b: https://github.com/vprivat-ads/eodag/commit/e84f17b7e7a3144c8f858f2e9320a4aa25e4530d
.. _e864f53: https://github.com/vprivat-ads/eodag/commit/e864f5313b7da2b6e8964b58d2df455c55e47250
.. _e8c5a47: https://github.com/vprivat-ads/eodag/commit/e8c5a47408a256139b6e864a2779a8b10947fa17
.. _e925418: https://github.com/vprivat-ads/eodag/commit/e925418af0787c29957a92aaaf4eabdd511545a6
.. _e98e0a9: https://github.com/vprivat-ads/eodag/commit/e98e0a9028f5edb3b771c000e70e346f17a9208c
.. _e996be9: https://github.com/vprivat-ads/eodag/commit/e996be9ae1d7d94703452df736aed6ec8115a1f5
.. _e9ffb17: https://github.com/vprivat-ads/eodag/commit/e9ffb178ceda82c7d9f4b6f87e2eadfff6b1078e
.. _ea0a817: https://github.com/vprivat-ads/eodag/commit/ea0a817674470685d4d5d83461c55e7ba0c52f79
.. _ea12faa: https://github.com/vprivat-ads/eodag/commit/ea12faadae5d7e02977fe3824c7c405f8ecb23ab
.. _ea72351: https://github.com/vprivat-ads/eodag/commit/ea723511ee51834d8578f1c9d52b33fa86f31efc
.. _ea929e4: https://github.com/vprivat-ads/eodag/commit/ea929e4339e976752bc61d1d305ad36ff1b78172
.. _eb054a4: https://github.com/vprivat-ads/eodag/commit/eb054a46f117e0971f772337bd70e5b5823a53d2
.. _eb0e34e: https://github.com/vprivat-ads/eodag/commit/eb0e34ec14a7a77b653d23a63626fb900dfcb071
.. _eb54b16: https://github.com/vprivat-ads/eodag/commit/eb54b1684a02c2e15f65b92729c5505decd7da98
.. _eb5dd5f: https://github.com/vprivat-ads/eodag/commit/eb5dd5fb85ae17f02ac3abf8d96ff72b84358fea
.. _eb73623: https://github.com/vprivat-ads/eodag/commit/eb73623a3713432f93dd17daee90a4aa58df1ce6
.. _eb9a6f0: https://github.com/vprivat-ads/eodag/commit/eb9a6f04359c64d28255a81775b42713b4abfad7
.. _ebfd3ec: https://github.com/vprivat-ads/eodag/commit/ebfd3ec21d0b1737b3537c3a3a0a67d627149256
.. _ec1d847: https://github.com/vprivat-ads/eodag/commit/ec1d847a11367a16d87d240e0e6fdeb65b1c6a74
.. _ec37bc9: https://github.com/vprivat-ads/eodag/commit/ec37bc900f43bd6fe0ea9a3c0dd01e9807b52d4a
.. _ec4c868: https://github.com/vprivat-ads/eodag/commit/ec4c868fc2bc885301dbd94a62805119f3cca9f3
.. _ec4f4b1: https://github.com/vprivat-ads/eodag/commit/ec4f4b1b883d0f65b27ecc1f1e723f6774da330c
.. _ece52c0: https://github.com/vprivat-ads/eodag/commit/ece52c07685e5df21cfda0b6ddc6a7416194406c
.. _ed3026d: https://github.com/vprivat-ads/eodag/commit/ed3026d5ab322d0097a77598e0ae2fb455030488
.. _ed3ab95: https://github.com/vprivat-ads/eodag/commit/ed3ab95dbdc27acd42bd6af65d7ca7eba0de5acd
.. _ed3daa0: https://github.com/vprivat-ads/eodag/commit/ed3daa03579f1aa53c983e6810389fea0f233d44
.. _edff5fe: https://github.com/vprivat-ads/eodag/commit/edff5fe12aedf860d1d30392a7775f3d23e648db
.. _ee112d3: https://github.com/vprivat-ads/eodag/commit/ee112d3035bcc70855a6efa115dac8cb1763e538
.. _ee21c4f: https://github.com/vprivat-ads/eodag/commit/ee21c4fa134591f31e2b38c7db129287807688ac
.. _ee240fa: https://github.com/vprivat-ads/eodag/commit/ee240fa3f09a90461fa445167b75c82cc456b9bb
.. _ee6306b: https://github.com/vprivat-ads/eodag/commit/ee6306b13f9a8a930e7ebb6b35af59f6799f2472
.. _ee83a74: https://github.com/vprivat-ads/eodag/commit/ee83a7458d275fa395dc3e59ee4f405899457d70
.. _ee9af26: https://github.com/vprivat-ads/eodag/commit/ee9af265d6a5799ed0da917dc312316d46df8ff1
.. _eeb8d3b: https://github.com/vprivat-ads/eodag/commit/eeb8d3b01c42fbd4d97aef28d3410e257378281a
.. _eec4adf: https://github.com/vprivat-ads/eodag/commit/eec4adfd9d49038c15e3e9dbbad56b49b6167b24
.. _ef5fc18: https://github.com/vprivat-ads/eodag/commit/ef5fc188e515759c9227584b25805db75f537833
.. _efccdd0: https://github.com/vprivat-ads/eodag/commit/efccdd00fbd0880344fe294dba0f4790468fd9bc
.. _f020e24: https://github.com/vprivat-ads/eodag/commit/f020e240e0012863920e86ae670bc036b858c741
.. _f0257df: https://github.com/vprivat-ads/eodag/commit/f0257dff077709f00696fef4d90ae91585a11787
.. _f02ecbd: https://github.com/vprivat-ads/eodag/commit/f02ecbd4fa40d8bbbe2ca8c42511ec32d8cf4083
.. _f069ccb: https://github.com/vprivat-ads/eodag/commit/f069ccbb64c53ef594047cde5e5e52a236595813
.. _f0d13e7: https://github.com/vprivat-ads/eodag/commit/f0d13e76f1c335433b98731409fbe42c8252df4e
.. _f10136e: https://github.com/vprivat-ads/eodag/commit/f10136e67f700ad9881e5fea3e3d2db597293ac9
.. _f14ef6b: https://github.com/vprivat-ads/eodag/commit/f14ef6b1b11428f68bc1ff47e1b3081819e03d9a
.. _f18edab: https://github.com/vprivat-ads/eodag/commit/f18edab149dc8868d7ebff5131397d09e225776d
.. _f1b066a: https://github.com/vprivat-ads/eodag/commit/f1b066a8feffef3d1c20147776128793177fcfeb
.. _f271cb3: https://github.com/vprivat-ads/eodag/commit/f271cb39985f26f74f6e54cb63176e943edb2bf0
.. _f274d4a: https://github.com/vprivat-ads/eodag/commit/f274d4adb60d5337e1dfd1b62dfe6d18c6ad61db
.. _f296c52: https://github.com/vprivat-ads/eodag/commit/f296c526a803607e23c477a9da679b5f27e142dc
.. _f2b3d07: https://github.com/vprivat-ads/eodag/commit/f2b3d076b022d8dc7b9f7a21498297c665f5a05f
.. _f2c495d: https://github.com/vprivat-ads/eodag/commit/f2c495d1ce6346d2d4a31e40203a5c6e57b96344
.. _f2d9979: https://github.com/vprivat-ads/eodag/commit/f2d9979b5391b95322622f5fe28de2f963a8200b
.. _f323366: https://github.com/vprivat-ads/eodag/commit/f323366a3594cfbe97a671ec17535d6dff1b1cea
.. _f32b807: https://github.com/vprivat-ads/eodag/commit/f32b8071ac367db96ff8f9f8709f0771f9d898f2
.. _f343411: https://github.com/vprivat-ads/eodag/commit/f34341140fcd82e81176fe5eb92d760031e65c44
.. _f344ddd: https://github.com/vprivat-ads/eodag/commit/f344dddf8cb9f0d512dd13984ebcaf16178485fe
.. _f3556af: https://github.com/vprivat-ads/eodag/commit/f3556af4a41b40a850cd938e0f9f4a635f6f8b16
.. _f373d7b: https://github.com/vprivat-ads/eodag/commit/f373d7b08c77b78293737ff742499bc91b123826
.. _f3d5535: https://github.com/vprivat-ads/eodag/commit/f3d5535a06fefdde2f79da3ecaaf59323d076a20
.. _f457527: https://github.com/vprivat-ads/eodag/commit/f4575270895d897b44b1ccc399884476dc754cd5
.. _f488962: https://github.com/vprivat-ads/eodag/commit/f48896229a00acaca2738ad175aac14dce60e42e
.. _f4b5f52: https://github.com/vprivat-ads/eodag/commit/f4b5f523553f67b1c2aeec03017fd462693164f9
.. _f4b7a67: https://github.com/vprivat-ads/eodag/commit/f4b7a67ad974b122ddc89ea6ff315248c9468169
.. _f4eec1f: https://github.com/vprivat-ads/eodag/commit/f4eec1fd64dbdb6de55462439f924a60d1623a4f
.. _f52c964: https://github.com/vprivat-ads/eodag/commit/f52c964ce52a5655f08616011d509b78d2b7c79c
.. _f5b4015: https://github.com/vprivat-ads/eodag/commit/f5b4015e976685972c823c4d992ab685b39d9b3a
.. _f65e582: https://github.com/vprivat-ads/eodag/commit/f65e5823801754cc64d460d612e407e732fb74eb
.. _f66ed1e: https://github.com/vprivat-ads/eodag/commit/f66ed1ea46ae46391447f08c341a89adbd11517f
.. _f67c365: https://github.com/vprivat-ads/eodag/commit/f67c365a4534b51ddbf9290767112bcd09bff89e
.. _f6d0ded: https://github.com/vprivat-ads/eodag/commit/f6d0deded4e490655dc612e30f80a2cd84f6f1f5
.. _f6f97fe: https://github.com/vprivat-ads/eodag/commit/f6f97fe82cb3d9c7fbf24396be22596ae87267d0
.. _f73ba14: https://github.com/vprivat-ads/eodag/commit/f73ba149625ed274fcb55ad5ab05b1f6ac4601e7
.. _f7519f8: https://github.com/vprivat-ads/eodag/commit/f7519f847af0253046d1329dead9d5a12b527923
.. _f7efdd0: https://github.com/vprivat-ads/eodag/commit/f7efdd09236091864c16b46822730cf1b97317c9
.. _f7f12d8: https://github.com/vprivat-ads/eodag/commit/f7f12d8170425f057c55efbddf5447daa6a83c23
.. _f82f016: https://github.com/vprivat-ads/eodag/commit/f82f016bac64911445b3beaa95f7fac7c47509bf
.. _f890fbf: https://github.com/vprivat-ads/eodag/commit/f890fbfe85c514e5f6794ff7db875bfbf5798b98
.. _f8cfc68: https://github.com/vprivat-ads/eodag/commit/f8cfc68a5d966eb1ce5a11cd1b58c354aad3205d
.. _f8f92d5: https://github.com/vprivat-ads/eodag/commit/f8f92d568f990c74f3f299ca172ca417af0856bb
.. _f915932: https://github.com/vprivat-ads/eodag/commit/f915932e6341de392a2d701d33ee4ec798beca5b
.. _f93645e: https://github.com/vprivat-ads/eodag/commit/f93645ed4f09194d6c7f12a3c65b2ab3a8f9ad5a
.. _f96a93c: https://github.com/vprivat-ads/eodag/commit/f96a93c1ec617b044ff3887ec50cae344e5aeab1
.. _f9a51f0: https://github.com/vprivat-ads/eodag/commit/f9a51f0347a2fc629915964e050bbf6a3befa02d
.. _fa1e8c0: https://github.com/vprivat-ads/eodag/commit/fa1e8c001a23dd4a42005c87e31f75da5d886d74
.. _fa22145: https://github.com/vprivat-ads/eodag/commit/fa22145056b62c8d399f254a3945e0c718834851
.. _fa3fe3f: https://github.com/vprivat-ads/eodag/commit/fa3fe3faeef275be4596f6435e5348ab3b9e833f
.. _fa5f42b: https://github.com/vprivat-ads/eodag/commit/fa5f42b5ec0cbe172e4dd73db6906f9f7b583793
.. _fa617ce: https://github.com/vprivat-ads/eodag/commit/fa617ce0d31fed9941fb178cfeb1e30ed2a16cd8
.. _faa2a50: https://github.com/vprivat-ads/eodag/commit/faa2a50269f2bbec7d62e113e49b08d1e588b831
.. _facf8bf: https://github.com/vprivat-ads/eodag/commit/facf8bf029fb74a84236b40b86c33a1265f35621
.. _fb599d4: https://github.com/vprivat-ads/eodag/commit/fb599d4d1385c7fdcea1c5d3f4457c6437208160
.. _fb729b1: https://github.com/vprivat-ads/eodag/commit/fb729b1b95b16b90ccd58a7bc3fb19480620b996
.. _fbf81ca: https://github.com/vprivat-ads/eodag/commit/fbf81ca8ae4eb064f31c88da19dd1a7b0100a281
.. _fbfc7d0: https://github.com/vprivat-ads/eodag/commit/fbfc7d09b96fcd1137525225b788a6903ee2d1eb
.. _fc01129: https://github.com/vprivat-ads/eodag/commit/fc01129a1a1ddcdbd9640d411d68f810419fc030
.. _fc07f66: https://github.com/vprivat-ads/eodag/commit/fc07f66ed0a968382f3b110d620e262551d97c5b
.. _fc15d0f: https://github.com/vprivat-ads/eodag/commit/fc15d0fb47eec7b17d6ac0b33713b28f3e261f80
.. _fc2bd76: https://github.com/vprivat-ads/eodag/commit/fc2bd76ae3cc775ed9068461c4cbc1892ce3fe28
.. _fc86004: https://github.com/vprivat-ads/eodag/commit/fc86004695bdfe03d6add6b5ff1b66d390b2a084
.. _fd00cae: https://github.com/vprivat-ads/eodag/commit/fd00cae7f0e7bf3013a8d7cf2c7fa725d9bb7363
.. _fd0c149: https://github.com/vprivat-ads/eodag/commit/fd0c149277735a3ecdc11588e8ac8e166b591ae8
.. _fd5ac0e: https://github.com/vprivat-ads/eodag/commit/fd5ac0e7a63c1bb2eaa7b3ae6ee69f2760f758aa
.. _fdc853e: https://github.com/vprivat-ads/eodag/commit/fdc853ee28ea3b9eba27e290ebf9fabde210c715
.. _fdd3dce: https://github.com/vprivat-ads/eodag/commit/fdd3dce8d74e91218d1392bc8bb4298d1e7ca5c8
.. _fdd86a0: https://github.com/vprivat-ads/eodag/commit/fdd86a08c40704a96ef8bbfc973078135af61db5
.. _fdde58e: https://github.com/vprivat-ads/eodag/commit/fdde58ebfc91c1c09d68ff51bbc09b8fb78649b2
.. _fdf2b08: https://github.com/vprivat-ads/eodag/commit/fdf2b08fc4d2cde352c1a1fa701c62fff82dc4d7
.. _fe0d8da: https://github.com/vprivat-ads/eodag/commit/fe0d8da7e266338d140d18f9032c61efef033a66
.. _fe2a514: https://github.com/vprivat-ads/eodag/commit/fe2a51497fa806f856e9bbb4e3911e7c78dad17e
.. _fe356ec: https://github.com/vprivat-ads/eodag/commit/fe356ec1df6c10d17051873a55b13df42a4d9d1e
.. _fe3bf6d: https://github.com/vprivat-ads/eodag/commit/fe3bf6de4a01330315b2f0a65ab1df9f971ab68f
.. _fe753c4: https://github.com/vprivat-ads/eodag/commit/fe753c4a303db775e10121f8944cd1658b4b768b
.. _fe76492: https://github.com/vprivat-ads/eodag/commit/fe76492b7d336271d78b0a980792638580257e7f
.. _fec1838: https://github.com/vprivat-ads/eodag/commit/fec1838bb0bbab76e194304899e82668fb9296eb
.. _fec965f: https://github.com/vprivat-ads/eodag/commit/fec965f791a74dbf658e0833e1507b7ac950d09d
.. _feef2bf: https://github.com/vprivat-ads/eodag/commit/feef2bfdab8d86b94645ce87de8de6c961982460
.. _fefce06: https://github.com/vprivat-ads/eodag/commit/fefce060c85b3831232e3111b6a16f34ac474b36
.. _ff32294: https://github.com/vprivat-ads/eodag/commit/ff32294cd9cb36985a461dccd8484a585a784788
.. _ff65795: https://github.com/vprivat-ads/eodag/commit/ff657954650d274b920283980c0dd8bd656cdd2a
.. _ff777d7: https://github.com/vprivat-ads/eodag/commit/ff777d7a1e33f612c5227dba4fecfcec55ff18fc
.. _ff84295: https://github.com/vprivat-ads/eodag/commit/ff84295c8d80a8f711b0f518726df19cb24ff701
.. _ff88331: https://github.com/vprivat-ads/eodag/commit/ff88331f734ec6b3a28ebe7c5a8eacda61187f2a
.. _ff9fcee: https://github.com/vprivat-ads/eodag/commit/ff9fceef56fe7e840b257c257b58707ed441429b


v4.0.0b1 (2026-02-03)
=====================

Features
--------

* **core**: STAC formatted serialization (`#1940`_, `cdb3a17`_)

* **providers**: Add collections to eumetsat_ds (`#1979`_, `7d72d64`_)

Bug Fixes
---------

* **core**: Add Collection property for server extended metadata (`#1947`_, `e9ffb17`_)

* **core**: Asset name harmonization with query-string (`#1983`_, `a93c2c7`_)

* **core**: TypedDict from typing_extensions required by pydantic (`#1986`_, `6ada805`_)

* **core**: Wrong credentials sharing (`#1970`_, `6ad08cb`_)

* **plugins**: Aws streamed downloads (`#1975`_, `652c927`_)

* **plugins**: Dates formatting and missing param in ECMWFSearch queryables (`#1956`_, `0fed963`_)

* **plugins**: Delete download link when order not finish (`#1952`_, `f020e24`_)

* **plugins**: Handle disabled count on cop_marine (`#1955`_, `816cf99`_)

* **plugins**: Uncomplete search validation for cop_ads and wekeo_ecmwf (`#1951`_, `3cc1d7c`_)

* **providers**: Creodias processing:version as str (`#2015`_, `3f8c56a`_)

* **providers**: Renamed THEIA collections on geodes (`#1974`_, `39d0962`_)

* **providers**: Search parameters parsing on hydroweb_next (`#1981`_, `ee21c4f`_)

* **providers** Update wekeo_ecmwf collection_fetch_url (`#1995`_, `4559f41`_)

Build System
------------

* Add docker image (`#1971`_, `0c5ed7c`_)(`#1972`_, `fa3fe3f`_)

* Add python3.14 support (`#1973`_, `07f484b`_)

* **docs**: Use sphinx 8 (`#2006`_, `811c176`_)

Chores
------

* Allow pydantic >= 2.12.0 by buiding docs with python3.13 (`#1966`_, `a8261af`_)

* Labextension conf in gitignore (`#1984`_, `b28d179`_)

* Remove remaining server-mode related code (`#1963`_, `8131264`_)

* Update assets rendering depth (`#2016`_, `c060011`_)

Continuous Integration
----------------------

* Gitleaks in pre-commit (`#1982`_, `e740d97`_)

Documentation
-------------

* Eodag-cube augment_from_xarray method (`#1989`_, `1fa56a3`_)

* Queryables guide update (`#2005`_, `c3429d8`_)

Refactoring
-----------

* **cli** Cli.py collision name on eodag (`#1993`_, `6d6f34f`_)

* **collections**: Add processor for Sentinel and MAJA collections (`#1999`_, `f9a51f0`_)

* **core** Updated STAC extensions schemas versions (`#2017`_, `5bc3f68`_)

* **core**: Use collection alias in EOProduct (`#1968`_, `b242061`_)

Testing
-------

* End-to-end tests fixes (`#1997`_, `2a238ed`_)

.. _#1940: https://github.com/CS-SI/eodag/pull/1940
.. _#1947: https://github.com/CS-SI/eodag/pull/1947
.. _#1951: https://github.com/CS-SI/eodag/pull/1951
.. _#1952: https://github.com/CS-SI/eodag/pull/1952
.. _#1955: https://github.com/CS-SI/eodag/pull/1955
.. _#1956: https://github.com/CS-SI/eodag/pull/1956
.. _#1963: https://github.com/CS-SI/eodag/pull/1963
.. _#1966: https://github.com/CS-SI/eodag/pull/1966
.. _#1968: https://github.com/CS-SI/eodag/pull/1968
.. _#1970: https://github.com/CS-SI/eodag/pull/1970
.. _#1971: https://github.com/CS-SI/eodag/pull/1971
.. _#1972: https://github.com/CS-SI/eodag/pull/1972
.. _#1973: https://github.com/CS-SI/eodag/pull/1973
.. _#1974: https://github.com/CS-SI/eodag/pull/1974
.. _#1975: https://github.com/CS-SI/eodag/pull/1975
.. _#1979: https://github.com/CS-SI/eodag/pull/1979
.. _#1981: https://github.com/CS-SI/eodag/pull/1981
.. _#1982: https://github.com/CS-SI/eodag/pull/1982
.. _#1983: https://github.com/CS-SI/eodag/pull/1983
.. _#1984: https://github.com/CS-SI/eodag/pull/1984
.. _#1986: https://github.com/CS-SI/eodag/pull/1986
.. _#1989: https://github.com/CS-SI/eodag/pull/1989
.. _#1993: https://github.com/CS-SI/eodag/pull/1993
.. _#1995: https://github.com/CS-SI/eodag/pull/1995
.. _#1997: https://github.com/CS-SI/eodag/pull/1997
.. _#1999: https://github.com/CS-SI/eodag/pull/1999
.. _#2005: https://github.com/CS-SI/eodag/pull/2005
.. _#2006: https://github.com/CS-SI/eodag/pull/2006
.. _#2015: https://github.com/CS-SI/eodag/pull/2015
.. _#2016: https://github.com/CS-SI/eodag/pull/2016
.. _#2017: https://github.com/CS-SI/eodag/pull/2017
.. _07f484b: https://github.com/CS-SI/eodag/commit/07f484bf5799866d75ca8afb6f84765820485c3f
.. _0c5ed7c: https://github.com/CS-SI/eodag/commit/0c5ed7c26200579f951596342dfddf3d214cbb55
.. _0fed963: https://github.com/CS-SI/eodag/commit/0fed9630f1965e804bad4364e5a920bec8414e62
.. _1fa56a3: https://github.com/CS-SI/eodag/commit/1fa56a3fb66de0035db14cd82b30e86d82f495a9
.. _2a238ed: https://github.com/CS-SI/eodag/commit/2a238edb621ce17eb99ae98fe28ad3fa56793ade
.. _39d0962: https://github.com/CS-SI/eodag/commit/39d096283e504c2c43eaadc039250a295edd6ac9
.. _3cc1d7c: https://github.com/CS-SI/eodag/commit/3cc1d7c85e140f03358990b3652d8c56d19e0321
.. _3f8c56a: https://github.com/CS-SI/eodag/commit/3f8c56a170d750295e0a708cd91b627d15a2408a
.. _4559f41: https://github.com/CS-SI/eodag/commit/4559f4198654338e99736046ed424612d50106be
.. _5bc3f68: https://github.com/CS-SI/eodag/commit/5bc3f68961eae2f5878f07182a0cb6624563793c
.. _652c927: https://github.com/CS-SI/eodag/commit/652c9278c04c962a7661cfbd2dcdd332a6e77e46
.. _6ad08cb: https://github.com/CS-SI/eodag/commit/6ad08cb4d7771c574401eafa41c37f4a5d898223
.. _6ada805: https://github.com/CS-SI/eodag/commit/6ada805f9d3db4b225a9c94c91fb296780e7b20d
.. _6d6f34f: https://github.com/CS-SI/eodag/commit/6d6f34fb247e9f51ed3576026ff3a90764023c38
.. _7d72d64: https://github.com/CS-SI/eodag/commit/7d72d649ae12c020052c600062585384ca0a9111
.. _811c176: https://github.com/CS-SI/eodag/commit/811c17621af246ff82670c02bb924899d887a6b3
.. _8131264: https://github.com/CS-SI/eodag/commit/8131264627b6143609868b9d3ebdcbf5b330eccd
.. _816cf99: https://github.com/CS-SI/eodag/commit/816cf99a08227201ca40df959a736128840b1947
.. _a8261af: https://github.com/CS-SI/eodag/commit/a8261afb2bb2129a152f6a498843bd015883f038
.. _a93c2c7: https://github.com/CS-SI/eodag/commit/a93c2c7ec99d5923aa550bf4a2eb76a7c9ac7e3b
.. _b242061: https://github.com/CS-SI/eodag/commit/b242061f4f7d73cc4d1681f891d1aeb0663a6504
.. _b28d179: https://github.com/CS-SI/eodag/commit/b28d179ded2588e0f44b131bfa959c7482139ff5
.. _c060011: https://github.com/CS-SI/eodag/commit/c06001160e00c8f4aa19811f5e7ec3bd85eaeb89
.. _c3429d8: https://github.com/CS-SI/eodag/commit/c3429d897e59bd8491a524d06b8c706d247a35ec
.. _cdb3a17: https://github.com/CS-SI/eodag/commit/cdb3a17047462037ea98eb31b0481e82dd62a438
.. _e740d97: https://github.com/CS-SI/eodag/commit/e740d97a1d2940d5c8f2b26393f535c3a9fdbc78
.. _e9ffb17: https://github.com/CS-SI/eodag/commit/e9ffb178ceda82c7d9f4b6f87e2eadfff6b1078e
.. _ee21c4f: https://github.com/CS-SI/eodag/commit/ee21c4fa134591f31e2b38c7db129287807688ac
.. _f020e24: https://github.com/CS-SI/eodag/commit/f020e240e0012863920e86ae670bc036b858c741
.. _f9a51f0: https://github.com/CS-SI/eodag/commit/f9a51f0347a2fc629915964e050bbf6a3befa02d
.. _fa3fe3f: https://github.com/CS-SI/eodag/commit/fa3fe3faeef275be4596f6435e5348ab3b9e833f


v4.0.0a5 (2025-12-04)
=====================

Chores
------

* Ensure locations dir exists during init (`#1958`_, `df263c2`_)

Performance Improvements
------------------------

* Download products and assets in parallel (`#1890`_, `b0b3799`_)

Refactoring
-----------

* Boto3 ServiceResource type check (`#1949`_, `90fafbe`_)

.. _#1890: https://github.com/CS-SI/eodag/pull/1890
.. _#1949: https://github.com/CS-SI/eodag/pull/1949
.. _#1958: https://github.com/CS-SI/eodag/pull/1958
.. _90fafbe: https://github.com/CS-SI/eodag/commit/90fafbe3501569ab394b14b6df14ff69f38c35f8
.. _b0b3799: https://github.com/CS-SI/eodag/commit/b0b37992c9d49d7e5743f2a638f84f47f1de440e
.. _df263c2: https://github.com/CS-SI/eodag/commit/df263c28042cc0aa4cdfeb88c24004aea9955cd5

v4.0.0a4 (2025-11-28)
=====================

Features
--------

* **core**: Providers representation classes (`#1902`_, `fa5f42b`_)

.. _#1902: https://github.com/CS-SI/eodag/pull/1902
.. _fa5f42b: https://github.com/CS-SI/eodag/commit/fa5f42b5ec0cbe172e4dd73db6906f9f7b583793


v4.0.0a3 (2025-11-27)
=====================

Bug Fixes
---------

* **core**: Handling of collections with aliases (`#1935`_, `274280a`_)

* **providers**: Geodes max_items_per_page down to 80 (`#1938`_, `abf8c71`_)

.. _#1935: https://github.com/CS-SI/eodag/pull/1935
.. _#1938: https://github.com/CS-SI/eodag/pull/1938

.. _274280a: https://github.com/CS-SI/eodag/commit/274280ae3b5df1fe7eac792d57192e633879dbcd
.. _abf8c71: https://github.com/CS-SI/eodag/commit/abf8c71bdbb7b3bcc27371b85f47261c489e3650

v4.0.0a2 (2025-11-19)
=====================

Features
--------

* **core**: Collections representation classes (`#1731`_, `4b57160`_)

* **core**: Search pagination using next_page (`#1745`_, `9abe670`_)

* **plugins**: Use original copernicus provider to list queryables of wekeo_ecmwf (`#1897`_,
  `0929a7c`_)

* **providers**: Add DEDT Marenostrum provider (`#1869`_, `650d21b`_)

* **providers**: Add DT_CLIMATE_ADAPTATION collection (`#1908`_, `cd84b88`_)

Bug Fixes
---------

* **core**: Skip None EOProduct.properties (`#1892`_, `41c2fc4`_)

* **core**: Sort queryables and ecmwf alias support (`#1894`_, `090c0bd`_)

* **plugins**: Add temporal resolution to ecmwf properties (`#1899`_, `219e669`_)

* **plugins**: Cop_marine search by id (`#1923`_, `0d42f00`_)

* **plugins**: Ecmwf geometries support (`#1924`_, `e996be9`_)

Continuous Integration
----------------------

* Better external collections summary in auto-update PR (`#1907`_, `43d9fb4`_)

* Fetch collections PR fix and refactor (`#1917`_, `0b88c50`_)

* Pre-commit replaced with faster prek (`#1914`_, `eb5dd5f`_)

Refactoring
-----------

* **collections**: CLMS and MetOp updates (`#1906`_, `9ebb872`_)

* **core**: Disable search pagination when less items got than expected (`#1920`_, `dfa18e7`_)

* **core**: Remove deprecatred legacy driver and get_data doc (`#1891`_, `2500af7`_)

* **core**: Whole world as default product geometry and shapely stubs (`#1915`_, `99df712`_)

* **providers**: Next_page_token_key added to confs (`#1921`_, `2bb99ba`_)

.. _#1730: https://github.com/CS-SI/eodag/pull/1730
.. _#1731: https://github.com/CS-SI/eodag/pull/1731
.. _#1745: https://github.com/CS-SI/eodag/pull/1745
.. _#1789: https://github.com/CS-SI/eodag/pull/1789
.. _#1839: https://github.com/CS-SI/eodag/pull/1839
.. _#1840: https://github.com/CS-SI/eodag/pull/1840
.. _#1868: https://github.com/CS-SI/eodag/pull/1868
.. _#1869: https://github.com/CS-SI/eodag/pull/1869
.. _#1877: https://github.com/CS-SI/eodag/pull/1877
.. _#1880: https://github.com/CS-SI/eodag/pull/1880
.. _#1886: https://github.com/CS-SI/eodag/pull/1886
.. _#1888: https://github.com/CS-SI/eodag/pull/1888
.. _#1891: https://github.com/CS-SI/eodag/pull/1891
.. _#1892: https://github.com/CS-SI/eodag/pull/1892
.. _#1894: https://github.com/CS-SI/eodag/pull/1894
.. _#1897: https://github.com/CS-SI/eodag/pull/1897
.. _#1899: https://github.com/CS-SI/eodag/pull/1899
.. _#1906: https://github.com/CS-SI/eodag/pull/1906
.. _#1907: https://github.com/CS-SI/eodag/pull/1907
.. _#1908: https://github.com/CS-SI/eodag/pull/1908
.. _#1914: https://github.com/CS-SI/eodag/pull/1914
.. _#1915: https://github.com/CS-SI/eodag/pull/1915
.. _#1917: https://github.com/CS-SI/eodag/pull/1917
.. _#1919: https://github.com/CS-SI/eodag/pull/1919
.. _#1920: https://github.com/CS-SI/eodag/pull/1920
.. _#1921: https://github.com/CS-SI/eodag/pull/1921
.. _#1923: https://github.com/CS-SI/eodag/pull/1923
.. _#1924: https://github.com/CS-SI/eodag/pull/1924
.. _090c0bd: https://github.com/CS-SI/eodag/commit/090c0bdee39041eb9b572112602be9477771a5fe
.. _0929a7c: https://github.com/CS-SI/eodag/commit/0929a7c7f883a5c5efcb87b903e2752a6efd789b
.. _0b88c50: https://github.com/CS-SI/eodag/commit/0b88c5041ec4d838cad64dbf864185b72325c791
.. _0d42f00: https://github.com/CS-SI/eodag/commit/0d42f00e9c237188c0ffc7de8aad3b5a0a37a6ae
.. _219e669: https://github.com/CS-SI/eodag/commit/219e669fa6e8bbbfa96357b21b964dd53c445233
.. _2500af7: https://github.com/CS-SI/eodag/commit/2500af7753cbbc1cfe6d315ea3247aebf6299859
.. _2bb99ba: https://github.com/CS-SI/eodag/commit/2bb99babf59ec2b7cf60a05148f20217ba6bfac9
.. _41c2fc4: https://github.com/CS-SI/eodag/commit/41c2fc4735df6b4498a5333dc13007ece279afce
.. _43d9fb4: https://github.com/CS-SI/eodag/commit/43d9fb442a8f33ab94873be251b230d1838d01c8
.. _4b57160: https://github.com/CS-SI/eodag/commit/4b571601b8a872265adc14c7fdb0be8e8566aa4c
.. _650d21b: https://github.com/CS-SI/eodag/commit/650d21b84e3c929eee7c1b100e6ee7ecfd0a70b8
.. _99df712: https://github.com/CS-SI/eodag/commit/99df71295a9a4c9f03bcb05cec814c4f50e43fb2
.. _9abe670: https://github.com/CS-SI/eodag/commit/9abe670945a70878ed7de5c53c46e5d5776e96c1
.. _9ebb872: https://github.com/CS-SI/eodag/commit/9ebb87297d464d06430dd5271c20b44e0df9b14c
.. _cd84b88: https://github.com/CS-SI/eodag/commit/cd84b88ff1bcb765f0b7ecd4d67fea1b06bc403e
.. _d4f8379: https://github.com/CS-SI/eodag/commit/d4f8379b90c02346506bdb53ded4c06ef128df31
.. _dfa18e7: https://github.com/CS-SI/eodag/commit/dfa18e7212094204000da269d039f05906dcb294
.. _e996be9: https://github.com/CS-SI/eodag/commit/e996be9ae1d7d94703452df736aed6ec8115a1f5
.. _eb5dd5f: https://github.com/CS-SI/eodag/commit/eb5dd5fb85ae17f02ac3abf8d96ff72b84358fea



v4.0.0a1 (2025-10-20)
=====================

Features
--------

* **core: STAC formatted properties** (`#1730`_, `743d7b5`_)

* **core**: Search validation (`#1877`_, `a157358`_)

Bug Fixes
---------

* Keep ext_product_types.json in v4 (`#1888`_, `d4f8379`_)

Continuous Integration
----------------------

* Run tests for v4 branch and associated PRs (`#1868`_, `a944aab`_)

Refactoring
-----------

* Remove deprecated code (`#1781`_, `09e14fe`_)

* Remove deprecated converters and plugins (`#1789`_, `edff5fe`_)

* Remove deprecated server-mode (`#1840`_, `266471b`_)

* **plugins**: Remove deprecated OAuth (`#1839`_, `3b749e2`_)

* **plugins**: Remove deprecated CreodiasS3Download (`#1886`_, `ea0a817`_)

.. _#1730: https://github.com/CS-SI/eodag/pull/1730
.. _#1781: https://github.com/CS-SI/eodag/pull/1781
.. _#1789: https://github.com/CS-SI/eodag/pull/1789
.. _#1839: https://github.com/CS-SI/eodag/pull/1839
.. _#1840: https://github.com/CS-SI/eodag/pull/1840
.. _#1868: https://github.com/CS-SI/eodag/pull/1868
.. _#1877: https://github.com/CS-SI/eodag/pull/1877
.. _#1886: https://github.com/CS-SI/eodag/pull/1886
.. _#1888: https://github.com/CS-SI/eodag/pull/1888
.. _09e14fe: https://github.com/CS-SI/eodag/commit/09e14fe91054bd3a67b572da47f283ea34309b9f
.. _266471b: https://github.com/CS-SI/eodag/commit/266471b676289ad532818986843478cac5765337
.. _3b749e2: https://github.com/CS-SI/eodag/commit/3b749e2b64f4c828f9562de7211df19ae7967736
.. _743d7b5: https://github.com/CS-SI/eodag/commit/743d7b5d25d50425de4c7f1c62c0922d7453afe2
.. _a157358: https://github.com/CS-SI/eodag/commit/a157358fa85e88b09ded3f05e02f463c05bd8cbd
.. _a944aab: https://github.com/CS-SI/eodag/commit/a944aab4675310576ba64d8bc0f634ceb95c3f4b
.. _d4f8379: https://github.com/CS-SI/eodag/commit/d4f8379b90c02346506bdb53ded4c06ef128df31
.. _ea0a817: https://github.com/CS-SI/eodag/commit/ea0a817674470685d4d5d83461c55e7ba0c52f79
.. _edff5fe: https://github.com/CS-SI/eodag/commit/edff5fe12aedf860d1d30392a7775f3d23e648db


v3.10.0 (2025-10-20)
====================

Features
--------

* **plugins**: Possibility to create presigned urls (`#1845`_, `d002c38`_)

Bug Fixes
---------

* **providers**: Added month/year mapping and default values for CMIP6_CLIMATE_PROJECT (`#1872`_,
  `dcdca60`_)

Build System
------------

* Pin pydantic < 2.12.0 to prevent sphinx failures (`#1873`_, `1b17b4a`_)

Refactoring
-----------

* **plugins**: Deprecate CreodiasS3Download (`#1884`_, `5f6966b`_)

.. _#1845: https://github.com/CS-SI/eodag/pull/1845
.. _#1872: https://github.com/CS-SI/eodag/pull/1872
.. _#1873: https://github.com/CS-SI/eodag/pull/1873
.. _#1884: https://github.com/CS-SI/eodag/pull/1884
.. _1b17b4a: https://github.com/CS-SI/eodag/commit/1b17b4af5f898ed608dd132e49477d28466f9451
.. _5f6966b: https://github.com/CS-SI/eodag/commit/5f6966bc52db1e19ad3f959bab41aca25804c3e5
.. _d002c38: https://github.com/CS-SI/eodag/commit/d002c38126f566f52903fb0e5012a22e771c3200
.. _dcdca60: https://github.com/CS-SI/eodag/commit/dcdca6012736f751418725312da736f61767ec36


v3.9.1 (2025-10-07)
===================

Bug Fixes
---------

* **plugins**: AwsAuth without credentials (`#1865`_, `ab04612`_)

* **providers**: Earth_search S2_MSI_L2A_COG assets href (`#1866`_, `f14ef6b`_)

* **providers**: Fix syntax error (`#1860`_, `d207f27`_)

* **providers**: PolarizationChannels mapping for STAC providers (`#1870`_, `819ecb2`_)

.. _#1860: https://github.com/CS-SI/eodag/pull/1860
.. _#1865: https://github.com/CS-SI/eodag/pull/1865
.. _#1866: https://github.com/CS-SI/eodag/pull/1866
.. _#1870: https://github.com/CS-SI/eodag/pull/1870
.. _819ecb2: https://github.com/CS-SI/eodag/commit/819ecb2127d7728236e32aadb1e605017c98cec6
.. _ab04612: https://github.com/CS-SI/eodag/commit/ab046125d1241adc164e8ffdec430b5d77d8193b
.. _d207f27: https://github.com/CS-SI/eodag/commit/d207f2701b472b8c6c75da5c63f0621736dedd8a
.. _f14ef6b: https://github.com/CS-SI/eodag/commit/f14ef6b1b11428f68bc1ff47e1b3081819e03d9a


v3.9.0 (2025-09-26)
===================

Features
--------

* **core**: Assets title normalized to key name (`#1826`_, `3662954`_)

* **providers**: Add CMIP6_CLIMATE_PROJECTIONS product type on cop_cds (`#1827`_, `308e0a9`_)

* **providers**: Available product types update for creodias, cop_dataspace and wekeo_main
  (`#1817`_, `04b0b55`_)

* **providers**: Send query and filter parameters as is for STAC providers (`#1828`_, `3b04096`_)

Bug Fixes
---------

* **core**: Update pattern of data roles in GenericDriver (`#1815`_, `c75351d`_)

* **providers**: CLMS_CORINE metadata mapping for wekeo (`#1846`_, `55b1ffe`_)

* **providers**: Harmonize orbitDirection properties (`#1836`_, `b428d61`_, `#1830`_, `57fecd0`_)

* **providers**: Harmonize polarizationChannels property (`#1831`_, `b85ef0f`_)

* **providers**: PlatformSerialIdentifier mapping for creodias/cop_dataspace (`#1848`_, `f890fbf`_)

* **providers**: S2_MSI_L2A_COG moved to earth_search (`#1841`_, `786c663`_)

Chores
------

* **cli,docs**: Deprecate STAC REST API server (`#1837`_, `083989e`_)

Documentation
-------------

* Documentation overhaul (`#1823`_, `df67693`_)

* Add tutorial for CCI data through fedeo_ceda (`#1832`_, `01b130a`_)

Refactoring
-----------

* **core**: Move dates utils functions to eodag.utils.dates (`#1844`_, `d2cd928`_)

* **core**: Use zipstream-ng instead of stream-zip (`#1805`_, `182cdc0`_)

* **plugins**: Dedt_lumi not-available data error message (`#1770`_, `bf8cbe1`_)

* **plugins**: Deprecate oauth plugin (`#1821`_, `1bdf8a9`_)

* **plugins**: Get_rio_env to AwsAuth (`#1838`_, `0ae4c17`_)

* **plugins**: Move aws authentication methods to AwsAuth plugin (`#1769`_, `1c072f8`_)

* **plugins**: Rename PostJsonSearchWithStacQueryables to WekeoSearch (`#1842`_, `4bfbd6d`_)

* **product-types**: S1C and S2C as available platformSerialIdentifier (`#1850`_, `7c532f4`_)

* **providers**: Use s3 alternate assets in usgs_satapi_aws (`#1851`_, `27b1ab2`_)

Testing
-------

* Add more tests to improve coverage (`#1791`_, `f7519f8`_)

.. _#1769: https://github.com/CS-SI/eodag/pull/1769
.. _#1770: https://github.com/CS-SI/eodag/pull/1770
.. _#1791: https://github.com/CS-SI/eodag/pull/1791
.. _#1805: https://github.com/CS-SI/eodag/pull/1805
.. _#1815: https://github.com/CS-SI/eodag/pull/1815
.. _#1817: https://github.com/CS-SI/eodag/pull/1817
.. _#1821: https://github.com/CS-SI/eodag/pull/1821
.. _#1823: https://github.com/CS-SI/eodag/pull/1823
.. _#1826: https://github.com/CS-SI/eodag/pull/1826
.. _#1827: https://github.com/CS-SI/eodag/pull/1827
.. _#1828: https://github.com/CS-SI/eodag/pull/1828
.. _#1830: https://github.com/CS-SI/eodag/pull/1830
.. _#1831: https://github.com/CS-SI/eodag/pull/1831
.. _#1832: https://github.com/CS-SI/eodag/pull/1832
.. _#1836: https://github.com/CS-SI/eodag/pull/1836
.. _#1837: https://github.com/CS-SI/eodag/pull/1837
.. _#1838: https://github.com/CS-SI/eodag/pull/1838
.. _#1841: https://github.com/CS-SI/eodag/pull/1841
.. _#1842: https://github.com/CS-SI/eodag/pull/1842
.. _#1844: https://github.com/CS-SI/eodag/pull/1844
.. _#1846: https://github.com/CS-SI/eodag/pull/1846
.. _#1848: https://github.com/CS-SI/eodag/pull/1848
.. _#1850: https://github.com/CS-SI/eodag/pull/1850
.. _#1851: https://github.com/CS-SI/eodag/pull/1851
.. _01b130a: https://github.com/CS-SI/eodag/commit/01b130a02a9c16fc3c76ee180bf56d1356380f82
.. _04b0b55: https://github.com/CS-SI/eodag/commit/04b0b5536b370a92843886ebf5135fac37172c18
.. _083989e: https://github.com/CS-SI/eodag/commit/083989e0d1be8878fa1da2c984c6025bc4a564f0
.. _0ae4c17: https://github.com/CS-SI/eodag/commit/0ae4c170fee95cfb2263c4f1b90a3219d502e819
.. _182cdc0: https://github.com/CS-SI/eodag/commit/182cdc0eb82e7e4ca9e073b12edf6c3e51952d39
.. _1bdf8a9: https://github.com/CS-SI/eodag/commit/1bdf8a9544717533f6ea85c7fc86f27b226a8f0f
.. _1c072f8: https://github.com/CS-SI/eodag/commit/1c072f8f857f24e08642c1cb6ddaff51fe26e52d
.. _27b1ab2: https://github.com/CS-SI/eodag/commit/27b1ab2174e9855323db26975ab347699f5d60cd
.. _308e0a9: https://github.com/CS-SI/eodag/commit/308e0a9884d4b2e3435922c89a23cc0aab1edab9
.. _3662954: https://github.com/CS-SI/eodag/commit/3662954cf31dd91dc79d740686e6557c9cbf7954
.. _3b04096: https://github.com/CS-SI/eodag/commit/3b04096ac6255f89c8eb8bb363a2b38ece1b02af
.. _4bfbd6d: https://github.com/CS-SI/eodag/commit/4bfbd6dfc11a08744935f8fdd4e3d9c321252d26
.. _55b1ffe: https://github.com/CS-SI/eodag/commit/55b1ffeae8b2ef03e5ecac35838675f9328cde90
.. _57fecd0: https://github.com/CS-SI/eodag/commit/57fecd07d32830ad12be3fb8074d5124c5797dc5
.. _786c663: https://github.com/CS-SI/eodag/commit/786c663414f42297e7ceeace2646446872160941
.. _7c532f4: https://github.com/CS-SI/eodag/commit/7c532f47fb3b17b4a39d379301134ac75f55253d
.. _b428d61: https://github.com/CS-SI/eodag/commit/b428d61405e2a24a59756016bade3788841c89dd
.. _b85ef0f: https://github.com/CS-SI/eodag/commit/b85ef0f360e805a61c2a7e9826a3cd7df4183315
.. _bf8cbe1: https://github.com/CS-SI/eodag/commit/bf8cbe1bd1ade032a1a7abdc17f3785a11fca5d9
.. _c75351d: https://github.com/CS-SI/eodag/commit/c75351d9b74ffa1cab3746a04637eb0de1a9f642
.. _d2cd928: https://github.com/CS-SI/eodag/commit/d2cd928e9e887e88db639e3ebb02d4e006c0f653
.. _df67693: https://github.com/CS-SI/eodag/commit/df67693099f72cbaf42e008f8b5b9c5af062e573
.. _f7519f8: https://github.com/CS-SI/eodag/commit/f7519f847af0253046d1329dead9d5a12b527923
.. _f890fbf: https://github.com/CS-SI/eodag/commit/f890fbfe85c514e5f6794ff7db875bfbf5798b98


v3.8.1 (2025-09-02)
===================

Bug Fixes
---------

* **core**: Guess_product_type using alias (`#1800`_, `99e6ab8`_)

* **plugins**: Filter using matching_url in SASAuth (`#1802`_, `c4e649c`_)

* **providers**: Instrument format for STAC providers (`#1803`_, `e1a56fd`_)

* **providers**: Ssl verify for fedeo_ceda (`#1801`_, `45b891a`_)

.. _#1800: https://github.com/CS-SI/eodag/pull/1800
.. _#1801: https://github.com/CS-SI/eodag/pull/1801
.. _#1802: https://github.com/CS-SI/eodag/pull/1802
.. _#1803: https://github.com/CS-SI/eodag/pull/1803
.. _45b891a: https://github.com/CS-SI/eodag/commit/45b891a6a527e0143eb23cfa1a9576cd74a56758
.. _99e6ab8: https://github.com/CS-SI/eodag/commit/99e6ab8fda3847bd8478bc8cc40688923ed13b49
.. _c4e649c: https://github.com/CS-SI/eodag/commit/c4e649cdadda539be517797d2668638c19b486c8
.. _e1a56fd: https://github.com/CS-SI/eodag/commit/e1a56fd0670d0aa4ee27cd5cc8a67b5fbea20be9


v3.8.0 (2025-08-27)
===================

Features
--------

* **providers**: New provider fedeo_ceda (`#1778`_, `4d9f091`_)

Bug Fixes
---------

* **providers**: Product types discovered properties format (`#1783`_, `7824f6a`_)

* **providers**: Remove deprecated product type (S2_MSI_L2AP) (`#1764`_, `7b1fb89`_)

* **providers**: Restore ssl verify for geodes (`#1780`_, `8b771f8`_)

* **server**: Remove duplicate host (`#1794`_, `fa22145`_)

Chores
------

* Deprecate unused code (`#1788`_, `2658e69`_)

Documentation
-------------

* Aws_eos logo added (`#1773`_, `af6d959`_)

Refactoring
-----------

* **core**: Whoosh removal (`#1741`_, `31f3c8a`_)

.. _#1741: https://github.com/CS-SI/eodag/pull/1741
.. _#1764: https://github.com/CS-SI/eodag/pull/1764
.. _#1773: https://github.com/CS-SI/eodag/pull/1773
.. _#1778: https://github.com/CS-SI/eodag/pull/1778
.. _#1780: https://github.com/CS-SI/eodag/pull/1780
.. _#1783: https://github.com/CS-SI/eodag/pull/1783
.. _#1788: https://github.com/CS-SI/eodag/pull/1788
.. _#1794: https://github.com/CS-SI/eodag/pull/1794
.. _2658e69: https://github.com/CS-SI/eodag/commit/2658e6983f64581f2364647993c4c0e6bc7bc841
.. _31f3c8a: https://github.com/CS-SI/eodag/commit/31f3c8a50b251cc2ad2d567fb6f1eb62937b5d43
.. _4d9f091: https://github.com/CS-SI/eodag/commit/4d9f09110c0fcc745d910b9c02e155aa1952b048
.. _7824f6a: https://github.com/CS-SI/eodag/commit/7824f6a1a3d3aa881532c5904f58acb73ebdca5f
.. _7b1fb89: https://github.com/CS-SI/eodag/commit/7b1fb89208537a360471a218d13b2f9865f282c4
.. _8b771f8: https://github.com/CS-SI/eodag/commit/8b771f801ef19e81297fc9fe273921702797dffc
.. _af6d959: https://github.com/CS-SI/eodag/commit/af6d959fec6fa009677ac429c70bb3004b066671
.. _fa22145: https://github.com/CS-SI/eodag/commit/fa22145056b62c8d399f254a3945e0c718834851


v3.7.0 (2025-07-31)
===================

Features
--------

* **plugins**: New search config for assets mapping (`#1711`_, `1281268`_)

* **providers**: Add 2 new MSG collections to provider ``eumetsat_ds`` (`#1742`_, `801c52c`_)

* **providers**: dedt_lumi search by geometry (`#1710`_, `efccdd0`_)

Bug Fixes
---------

* **core**: Logging issue on entrypoint loading error (`#1728`_, `6f8e6ad`_)

* **plugins**: metadata_mapping_from_product in search config (`#1737`_, `cdfe518`_)

* **providers**: Allow search by id for CLMS_CORINE with wekeo_main (`#1746`_, `bfe5e71`_)

* **providers**: Remove no-more-available theia provider (`#1736`_, `e81013b`_)

* **providers**: Update default version for CAMS_GLOBAL_EMISSIONS (`#1738`_, `81e4b90`_)

* **server**: Empty instruments mapping (`#1763`_, `11f2318`_)

* **utils**: Avoid repeated SSL context creation (`#1758`_, `f93645e`_)

Documentation
-------------

* Updated description, overview and ecosystem (`#1734`_, `ea929e4`_)

Performance Improvements
------------------------

* **plugins**: Optimize AwsDownload streaming (`#1740`_, `48f0e4c`_)

Refactoring
-----------

* Directly import urllib.parse methods (`#1761`_, `e4aca26`_)

.. _#1710: https://github.com/CS-SI/eodag/pull/1710
.. _#1711: https://github.com/CS-SI/eodag/pull/1711
.. _#1728: https://github.com/CS-SI/eodag/pull/1728
.. _#1734: https://github.com/CS-SI/eodag/pull/1734
.. _#1736: https://github.com/CS-SI/eodag/pull/1736
.. _#1737: https://github.com/CS-SI/eodag/pull/1737
.. _#1738: https://github.com/CS-SI/eodag/pull/1738
.. _#1740: https://github.com/CS-SI/eodag/pull/1740
.. _#1742: https://github.com/CS-SI/eodag/pull/1742
.. _#1746: https://github.com/CS-SI/eodag/pull/1746
.. _#1758: https://github.com/CS-SI/eodag/pull/1758
.. _#1761: https://github.com/CS-SI/eodag/pull/1761
.. _#1763: https://github.com/CS-SI/eodag/pull/1763
.. _11f2318: https://github.com/CS-SI/eodag/commit/11f2318a150982504226378110b853ca4aa644ce
.. _1281268: https://github.com/CS-SI/eodag/commit/1281268507c3a7338be9954b403a20d5156bc527
.. _48f0e4c: https://github.com/CS-SI/eodag/commit/48f0e4c8c82e80841b7b64bec60a251661a13d12
.. _6f8e6ad: https://github.com/CS-SI/eodag/commit/6f8e6ad683f786286cfb36e8e22c17cfb2daf125
.. _801c52c: https://github.com/CS-SI/eodag/commit/801c52c38124e6dfff1a5fdedeb0cbd269fc2478
.. _81e4b90: https://github.com/CS-SI/eodag/commit/81e4b903c5474894e87e6dcb9366fdfbb152398b
.. _bfe5e71: https://github.com/CS-SI/eodag/commit/bfe5e712087804d31fe7f057e5efbd1d2863fb36
.. _cdfe518: https://github.com/CS-SI/eodag/commit/cdfe518f2b392b700994f93d2c2d6cafdb46b81d
.. _e4aca26: https://github.com/CS-SI/eodag/commit/e4aca2672b156a6eb338e9e9a8277bc2895aa457
.. _e81013b: https://github.com/CS-SI/eodag/commit/e81013b262342a0621e2018a7d917145faaa2cc7
.. _ea929e4: https://github.com/CS-SI/eodag/commit/ea929e4339e976752bc61d1d305ad36ff1b78172
.. _efccdd0: https://github.com/CS-SI/eodag/commit/efccdd00fbd0880344fe294dba0f4790468fd9bc
.. _f93645e: https://github.com/CS-SI/eodag/commit/f93645ed4f09194d6c7f12a3c65b2ab3a8f9ad5a


v3.6.0 (2025-07-01)
===================

Features
--------

* **cli**: Commands chaining (`#1714`_, `754772b`_)

* **cli**: Download output directory (`#1716`_, `036b86b`_)

* **cli**: Download STAC items from their urls (`#1705`_, `5d598a9`_)

* **core**: Import stac items as SearchResult (`#1703`_, `1d49715`_)

* **providers**: Add new eurostat product types to dedl (`#1662`_, `b7192b1`_)

Bug Fixes
---------

* **core**: Do not download again unextracted products (`#1717`_, `29642e8`_)

* **queryables**: Improve date parameter parsing (`#1702`_, `9563d4b`_)

Documentation
-------------

* Cli and stac support update (`#1707`_, `c50aae1`_)

* Import_stac_items documentation update (`#1709`_, `7a04158`_)

.. _#1662: https://github.com/CS-SI/eodag/pull/1662
.. _#1702: https://github.com/CS-SI/eodag/pull/1702
.. _#1703: https://github.com/CS-SI/eodag/pull/1703
.. _#1705: https://github.com/CS-SI/eodag/pull/1705
.. _#1706: https://github.com/CS-SI/eodag/pull/1706
.. _#1707: https://github.com/CS-SI/eodag/pull/1707
.. _#1709: https://github.com/CS-SI/eodag/pull/1709
.. _#1714: https://github.com/CS-SI/eodag/pull/1714
.. _#1716: https://github.com/CS-SI/eodag/pull/1716
.. _#1717: https://github.com/CS-SI/eodag/pull/1717
.. _036b86b: https://github.com/CS-SI/eodag/commit/036b86bbefeed905c9962a7a4bf7bca8258246fb
.. _1d49715: https://github.com/CS-SI/eodag/commit/1d4971560e9b789dfe96ca09b2fcd5d88cb4e30a
.. _29642e8: https://github.com/CS-SI/eodag/commit/29642e87614b44ec3b544732ef6496ae8bf73087
.. _5d598a9: https://github.com/CS-SI/eodag/commit/5d598a9934d36390e7b6f1ef2d746f9a9030198d
.. _754772b: https://github.com/CS-SI/eodag/commit/754772b9e71700fb752cb632dfb66ef13cd2c743
.. _7a04158: https://github.com/CS-SI/eodag/commit/7a041583695f71811baf56e5616415df60750814
.. _9563d4b: https://github.com/CS-SI/eodag/commit/9563d4bccaea5a87805fff77863d14cb4b422fb7
.. _b7192b1: https://github.com/CS-SI/eodag/commit/b7192b14840d27a3558f4dc5dff0b99ea6c0d833
.. _c50aae1: https://github.com/CS-SI/eodag/commit/c50aae12b344d81f66fc20a9a930b7718e0b12b7
.. _e1db471: https://github.com/CS-SI/eodag/commit/e1db47199d47c4988eaece7628005727dba2985f


v3.5.1 (2025-06-23)
===================

Bug Fixes
---------

* **core**: Enable count with search iterator (`#1700`_, `bbcc7ba`_)

* **plugins**: Lru caching when fetching constraints with ECMWF (`#1698`_, `e23f47e`_)

Refactoring
-----------

* **core**: Register downloader using manager from search to EOProduct (`#1699`_, `fd0c149`_)

.. _#1698: https://github.com/CS-SI/eodag/pull/1698
.. _#1699: https://github.com/CS-SI/eodag/pull/1699
.. _#1700: https://github.com/CS-SI/eodag/pull/1700
.. _bbcc7ba: https://github.com/CS-SI/eodag/commit/bbcc7ba311fcf25a0231203035166276e704ec8e
.. _e23f47e: https://github.com/CS-SI/eodag/commit/e23f47ee97a50c0ba1d573801a17177c88f06eae
.. _fd0c149: https://github.com/CS-SI/eodag/commit/fd0c149277735a3ecdc11588e8ac8e166b591ae8


v3.5.0 (2025-06-20)
===================

Features
--------

* **core**: Add env variable to whitelist providers (`#1672`_, `b93c4c8`_)

* **core**: Add strict product types mode (`#1677`_, `5077fa5`_)

* **plugins**: Auth token expiration margin (`#1665`_, `ef5fc18`_)

* **server**: Added bbox filter support for collections search (`#1671`_, `5717f0d`_)

Bug Fixes
---------

* **core**: Always validate PluginConfig before loading (`#1690`_, `59ac437`_)

* **core**: Skip provider empty conf on init (`#1687`_, `0a4104e`_)

* **plugins**: Raise errors when metadata discovery is not allowed (`#1534`_, `855ffa3`_)

Build System
------------

* Update usgs to 0.3.6 (`#1688`_, `e63cfb1`_)

Continuous Integration
----------------------

* Use personal access token for deploy github action (`#1693`_, `ff777d7`_)

Documentation
-------------

* Dead-links and out-of-date param fix (`#1692`_, `445a20e`_)

.. _#1534: https://github.com/CS-SI/eodag/pull/1534
.. _#1665: https://github.com/CS-SI/eodag/pull/1665
.. _#1671: https://github.com/CS-SI/eodag/pull/1671
.. _#1672: https://github.com/CS-SI/eodag/pull/1672
.. _#1677: https://github.com/CS-SI/eodag/pull/1677
.. _#1687: https://github.com/CS-SI/eodag/pull/1687
.. _#1688: https://github.com/CS-SI/eodag/pull/1688
.. _#1690: https://github.com/CS-SI/eodag/pull/1690
.. _#1692: https://github.com/CS-SI/eodag/pull/1692
.. _#1693: https://github.com/CS-SI/eodag/pull/1693
.. _0a4104e: https://github.com/CS-SI/eodag/commit/0a4104e0518abc70e2133ca98472eea87d673a1c
.. _445a20e: https://github.com/CS-SI/eodag/commit/445a20e060730642e703615c73225c0df3cc84d0
.. _5077fa5: https://github.com/CS-SI/eodag/commit/5077fa591496811fb100c1e6b6a3e452cbdbe2a5
.. _5717f0d: https://github.com/CS-SI/eodag/commit/5717f0deddbf022f2c6d5207ade77de6afb0f9d5
.. _59ac437: https://github.com/CS-SI/eodag/commit/59ac437de01a8996d247b1f8239f332ed5dc5456
.. _855ffa3: https://github.com/CS-SI/eodag/commit/855ffa39fa9b914eb39cc20d6e5c2cbbc1b2097a
.. _b93c4c8: https://github.com/CS-SI/eodag/commit/b93c4c88f323af0eecb0950c90c6862ca9a7c3f4
.. _e63cfb1: https://github.com/CS-SI/eodag/commit/e63cfb19ca64a2ed65f500ae9678e117a2ea4cf8
.. _ef5fc18: https://github.com/CS-SI/eodag/commit/ef5fc188e515759c9227584b25805db75f537833
.. _ff777d7: https://github.com/CS-SI/eodag/commit/ff777d7a1e33f612c5227dba4fecfcec55ff18fc


v3.4.3 (2025-06-12)
===================

Bug Fixes
---------

* **core**: Queryables mismatch when list of possible values contains a single value (`#1666`_,
  `538331d`_)

* **plugins**: GenericAuth missing credentials handle (`#1678`_, `576a2ac`_)

* **plugins**: Openid_connect requests error handling (#1320) (`#1663`_, `9926083`_)

* **plugins**: Order retry (`#1676`_, `3602426`_)

* **providers**: Dedl mapping for CORINE collection (`#1661`_, `4c61b54`_)

* **providers**: Wekeo_main orderable products download (`#1670`_, `d573846`_)

Chores
------

* **deploy**: Remove deprecated common values (`154ea6d`_)

Documentation
-------------

* Configuration environment variables defaults (`#1681`_, `6e8eb6b`_)

* Updated contribution guidelines link in PR template (`#1667`_, `e5cd082`_)

Refactoring
-----------

* Typing fixes following mypy 1.16.0 (`#1673`_, `ece52c0`_)

.. _#1661: https://github.com/CS-SI/eodag/pull/1661
.. _#1663: https://github.com/CS-SI/eodag/pull/1663
.. _#1666: https://github.com/CS-SI/eodag/pull/1666
.. _#1667: https://github.com/CS-SI/eodag/pull/1667
.. _#1670: https://github.com/CS-SI/eodag/pull/1670
.. _#1673: https://github.com/CS-SI/eodag/pull/1673
.. _#1676: https://github.com/CS-SI/eodag/pull/1676
.. _#1678: https://github.com/CS-SI/eodag/pull/1678
.. _#1681: https://github.com/CS-SI/eodag/pull/1681
.. _154ea6d: https://github.com/CS-SI/eodag/commit/154ea6d035572e64c3a434bb41c095c9b4cc76b2
.. _3602426: https://github.com/CS-SI/eodag/commit/360242653ddc2a5c8587b37b3d91800459f4c243
.. _4c61b54: https://github.com/CS-SI/eodag/commit/4c61b540ee46a8ae70932d64e9d373653763eb16
.. _538331d: https://github.com/CS-SI/eodag/commit/538331d30085a814307173913ff831ca5a3397af
.. _576a2ac: https://github.com/CS-SI/eodag/commit/576a2ac95044d10367e91e5ef843fb33a921f5f5
.. _6e8eb6b: https://github.com/CS-SI/eodag/commit/6e8eb6b94eaad6294fea45d764a0e7c18a4e6823
.. _9926083: https://github.com/CS-SI/eodag/commit/99260837837c3b5f2eeac8b95dc2b2feae7a0390
.. _d573846: https://github.com/CS-SI/eodag/commit/d5738465930e08b24d562af3b7bc040464ff970a
.. _e5cd082: https://github.com/CS-SI/eodag/commit/e5cd082aa81eedb62cd48b7974362c99a6899d9c
.. _ece52c0: https://github.com/CS-SI/eodag/commit/ece52c07685e5df21cfda0b6ddc6a7416194406c


v3.4.2 (2025-05-15)
===================

Bug Fixes
---------

* **core**: Remove quotes around arrays in query param (`#1657`_, `b717e45`_)

* **plugins**: Adapt queryables additional_properties to providers config (`#1646`_, `cc6ecc9`_)

* **plugins**: Add alias to properties in cop_marine and EcmwfSearch plugins (`#1649`_, `ae93d5a`_)

* **plugins**: Ecmwfsearch orderable products search (`#1656`_, `a399a5b`_)

Continuous Integration
----------------------

* Automatic deployment (`#1655`_, `4fbdf8b`_)

.. _#1646: https://github.com/CS-SI/eodag/pull/1646
.. _#1649: https://github.com/CS-SI/eodag/pull/1649
.. _#1655: https://github.com/CS-SI/eodag/pull/1655
.. _#1656: https://github.com/CS-SI/eodag/pull/1656
.. _#1657: https://github.com/CS-SI/eodag/pull/1657
.. _4fbdf8b: https://github.com/CS-SI/eodag/commit/4fbdf8ba4d2cece05bede65e18438ecdc8029a69
.. _a399a5b: https://github.com/CS-SI/eodag/commit/a399a5b1d5457cdfcab355f8e2b4c440982ba65f
.. _ae93d5a: https://github.com/CS-SI/eodag/commit/ae93d5a6c58476dad2461d9dde663aa31356dff9
.. _b717e45: https://github.com/CS-SI/eodag/commit/b717e456fb23e59e9dfb6a99b5e30b697be73232
.. _cc6ecc9: https://github.com/CS-SI/eodag/commit/cc6ecc9979bfee420ff75cd919c3f90ae73689bb


v3.4.1 (2025-05-12)
===================

Features
--------

* **plugins**: Add queryables to cop_marine (`#1638`_, `bcc793e`_)

Bug Fixes
---------

* **plugins**: Missing datetime properties in ECMWFSearch result (`#1648`_, `9ac8d6a`_)

* **plugins**: Staticstacsearch text opener (`#1643`_, `71a51f1`_)

Documentation
-------------

* Fixed binder tutos links (`#1651`_, `5ec4421`_)

Testing
-------

* Update click>=8.2.0 exit status code (`#1650`_, `51a5f36`_)

.. _#1643: https://github.com/CS-SI/eodag/pull/1643
.. _#1648: https://github.com/CS-SI/eodag/pull/1648
.. _#1650: https://github.com/CS-SI/eodag/pull/1650
.. _#1651: https://github.com/CS-SI/eodag/pull/1651
.. _51a5f36: https://github.com/CS-SI/eodag/commit/51a5f3667b2cc0b706a7278494ee4e8bf1260210
.. _5ec4421: https://github.com/CS-SI/eodag/commit/5ec4421cf3c653e35005e4489a09cb2f22e44a9f
.. _71a51f1: https://github.com/CS-SI/eodag/commit/71a51f16ea370f542af3142fee25ec90c2a75ae3
.. _9ac8d6a: https://github.com/CS-SI/eodag/commit/9ac8d6a3f06ad1112c6dd3aeccb2f63eaa49c3c0


v3.4.0 (2025-04-30)
===================

Bug Fixes
---------

* **plugins**: Stac providers datetime queryables handling (`#1625`_, `9417fd9`_)

* **providers**: cop_ewds metadata mapping (`#1629`_, `30b5554`_)

Refactoring
-----------

* **core**: Use importlib.metadata instead of the deprecated pkg_resources (`#1631`_, `3675690`_, thanks `@avalentino <https://github.com/avalentino>`_)

.. _#1625: https://github.com/CS-SI/eodag/pull/1625
.. _#1629: https://github.com/CS-SI/eodag/pull/1629
.. _#1631: https://github.com/CS-SI/eodag/pull/1631
.. _#1638: https://github.com/CS-SI/eodag/pull/1638
.. _30b5554: https://github.com/CS-SI/eodag/commit/30b5554d96c58a0aca53849bd38db80902823bdf
.. _3675690: https://github.com/CS-SI/eodag/commit/3675690e04813de6b9402f0028277c091d0e51b0
.. _9417fd9: https://github.com/CS-SI/eodag/commit/9417fd90049ccfb8ee30f6eef7e497da2c1bea60
.. _bcc793e: https://github.com/CS-SI/eodag/commit/bcc793e83ae6c7fec3e282046e4516510e9015fb


v3.3.2 (2025-04-24)
===================

Bug Fixes
---------

* **providers**: Creodias and cop_dataspace products title mapping (`#1635`_, `850cb50`_)

Continuous Integration
----------------------

* Fixed changelog generation (`#1630`_, `3bd7a5c`_)

* Token usage for coverage report publishing (`#1633`_, `6a7e0d4`_)

* Update changelog generation (`#1627`_, `20e0ef7`_)

Refactoring
-----------

* **core**: Authentication for get_quicklook (`#1608`_, `40915e0`_)

.. _#1608: https://github.com/CS-SI/eodag/pull/1608
.. _#1627: https://github.com/CS-SI/eodag/pull/1627
.. _#1630: https://github.com/CS-SI/eodag/pull/1630
.. _#1633: https://github.com/CS-SI/eodag/pull/1633
.. _#1635: https://github.com/CS-SI/eodag/pull/1635
.. _20e0ef7: https://github.com/CS-SI/eodag/commit/20e0ef7d066b278ad2f068e1f65998c5549fdaf0
.. _3bd7a5c: https://github.com/CS-SI/eodag/commit/3bd7a5c486f28c104964d7ca11c222a5a4d9132f
.. _40915e0: https://github.com/CS-SI/eodag/commit/40915e031b4b5db2eda508fb71e5058d2a256bff
.. _6a7e0d4: https://github.com/CS-SI/eodag/commit/6a7e0d43883d862b06269dee4bff940b5112e018
.. _850cb50: https://github.com/CS-SI/eodag/commit/850cb5010058887277e19e59b2b7b3311fddd2a4


v3.3.1 (2025-04-17)
===================

Bug Fixes
---------

* **core**: Missing queryables from metadata-mapping (`#1614`_, `9789c0c`_)

* **core**: Provider queryables metadata (`#1613`_, `f1b066a`_)

* **core**: Reset errors between SearchResult instances (`#1607`_, `48b0779`_)

* **plugins**: Send client_id/client_secret with refresh_token in TokenAuth (`#1597`_, `9b626a9`_, thanks
  `@jgaucher-cs <https://github.com/jgaucher-cs>`_)

.. _#1597: https://github.com/CS-SI/eodag/pull/1597
.. _#1607: https://github.com/CS-SI/eodag/pull/1607
.. _#1613: https://github.com/CS-SI/eodag/pull/1613
.. _#1614: https://github.com/CS-SI/eodag/pull/1614
.. _48b0779: https://github.com/CS-SI/eodag/commit/48b07797b3a17c26e33f6f8ee2f51488a0829162
.. _9789c0c: https://github.com/CS-SI/eodag/commit/9789c0c4a52aa180422e1f0a0c2b8d86c373a0ee
.. _9b626a9: https://github.com/CS-SI/eodag/commit/9b626a91c7563d505632c830a98d18993ec95199
.. _f1b066a: https://github.com/CS-SI/eodag/commit/f1b066a8feffef3d1c20147776128793177fcfeb


v3.3.0 (2025-04-10)
===================


Features
--------

* **plugins**: :class:`~eodag.plugins.search.build_search_result.ECMWFSearch` search-by-id (`#1580`_, `f296c52`_)

Bug Fixes
---------

* **core**: Ensure datetime format compliance with STAC specification (`#1573`_, `7e10e3a`_)

* **plugins**: Add datetime for ecmwf search (`#1572`_, `b785e7c`_)

* **plugins**: Check expiration time in token auth (`#1590`_, `15dbcb1`_)

* **providers**: ``geodes`` datetime search (`#1592`_, `87ade04`_)

* **providers**: Rename ``EO:CLMS:DAT:CORINE`` to ``EO:EEA:DAT:CORINE`` (`#1576`_, `2d3f6da`_)

Continuous Integration
----------------------

* Automatic changelog update (`#1601`_, `0625802`_)

Testing
-------

* Fixed test for ecmwf dates (`#1588`_, `b6ca196`_)

.. _#1572: https://github.com/CS-SI/eodag/pull/1572
.. _#1573: https://github.com/CS-SI/eodag/pull/1573
.. _#1576: https://github.com/CS-SI/eodag/pull/1576
.. _#1580: https://github.com/CS-SI/eodag/pull/1580
.. _#1588: https://github.com/CS-SI/eodag/pull/1588
.. _#1590: https://github.com/CS-SI/eodag/pull/1590
.. _#1592: https://github.com/CS-SI/eodag/pull/1592
.. _#1599: https://github.com/CS-SI/eodag/pull/1599
.. _#1601: https://github.com/CS-SI/eodag/pull/1601
.. _#1603: https://github.com/CS-SI/eodag/pull/1603
.. _0625802: https://github.com/CS-SI/eodag/commit/0625802e62f5be02560f6b015c65d0643e7cb720
.. _15dbcb1: https://github.com/CS-SI/eodag/commit/15dbcb17b14becdce57087fdba5b60adeb4a7551
.. _2d3f6da: https://github.com/CS-SI/eodag/commit/2d3f6dac273cb70f55dfa9eb3c898266a4c93552
.. _548fded: https://github.com/CS-SI/eodag/commit/548fdedc7a30d488302a685c4c8361ba29c2068f
.. _6af7ce4: https://github.com/CS-SI/eodag/commit/6af7ce499d00c32af3754ce30ebcb8fc392638a9
.. _7e10e3a: https://github.com/CS-SI/eodag/commit/7e10e3aeb27220fd023f1cb00198ed2304ea3486
.. _87ade04: https://github.com/CS-SI/eodag/commit/87ade04922356eb78cf1798a8fb81bcea8057595
.. _b6ca196: https://github.com/CS-SI/eodag/commit/b6ca1968d60d6123e818f1eec06fc1fa386e465a
.. _b785e7c: https://github.com/CS-SI/eodag/commit/b785e7c15c8dc60efbe0f38ac4d6487d8917b1aa
.. _f296c52: https://github.com/CS-SI/eodag/commit/f296c526a803607e23c477a9da679b5f27e142dc


v3.2.0 (2025-04-01)
===================

Core features and fixes
-----------------------

* Fixes download of assets having keys with special characters (:pull:`1585`)

Providers and product types updates
-----------------------------------

* ``geodes`` API update (:pull:`1581`)
* Sanitize ``eumetsat_ds`` products title (:pull:`1582`)
* Updated default values for some ECMWF collections (:pull:`1575`)

Plugins new features and fixes
------------------------------

* Do not guess assets keys from their URL when inappropriate (:pull:`1584`)

Miscellaneous
-------------

* Various minor fixes and improvements (:pull:`1570`)(:pull:`1571`)
* External product types reference updates (:pull:`1567`)

v3.1.0 (2025-03-19)
===================

|:loudspeaker:| Major changes since last stable (`v3.0.1 <changelog.rst#v3-0-1-2024-11-06>`_)
---------------------------------------------------------------------------------------------

Core features and fixes
^^^^^^^^^^^^^^^^^^^^^^^

* [v3.1.0b2] Assets keys uniformization using drivers (:pull:`1488`)
* [v3.1.0b1] Updated `queryables <https://eodag.readthedocs.io/en/latest/notebooks/api_user_guide/4_queryables.html>`_
  mechanism and ecmwf-like plugins (:pull:`1397`)(:pull:`1427`)(:pull:`1462`)
* **[v3.1.0]** Customizable providers configuration file through ``EODAG_PRODUCT_TYPES_CFG_FILE`` environment
  variable (:pull:`1559`)
* [v3.1.0b1] Order and download polling times update (:pull:`1440`)

Providers and product types updates
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* **[v3.1.0]** Removed ``onda`` provider (:pull:`1564`)
* [v3.1.0b2] default search timeout to 20s (:pull:`1505`)

Plugins new features and fixes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* **[v3.1.0]** :class:`~eodag.plugins.search.build_search_result.ECMWFSearch`: simplified configuration (:pull:`1433`),
  fixed queryables issues (:pull:`1509`), mapped geometry metadata (:pull:`1555`)
* [v3.1.0b1] Removed default :class:`~eodag.plugins.download.http.HTTPDownload` zip extension (:pull:`1400`)
* [v3.1.0b1] Order and poll without downloading (:pull:`1437`)

Remaining changes since `v3.1.0b2 <changelog.rst#v3-1-0b2-2025-02-03>`_
-----------------------------------------------------------------------

Core features and fixes
^^^^^^^^^^^^^^^^^^^^^^^

* Keep queryables `required` attribute even with default values (:pull:`1521`)

Providers and product types updates
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* ``geodes``: recognize auth errors during download (:pull:`1562`), typo in ``geodes_s3`` user conf template
  (:pull:`1536`)
* ``wekeo_main`` metadata mapping update (:pull:`1549`) and COP-DEM product types update (:pull:`1516`)
* ``eumetsat_ds``: new MTG product types (:pull:`1513`), metadata mapping fix (:pull:`1502`), remove duplicate product
  types (:pull:`1514`)
* Add product types to ``dedl`` provider (:pull:`1515`)

Plugins new features and fixes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* :class:`~eodag.plugins.download.aws.AwsDownload`: zip partial download (:pull:`1561`), `InvalidRequest` handle
  (:pull:`1532`)
* Already authenticated user fix on openid authentication plugins (:pull:`1524`)
* Fixes missing file error on ``usgs`` authentication during attempts (:pull:`1550`)

Miscellaneous
^^^^^^^^^^^^^

* **[build]** remove dependencies max versions (:pull:`1519`)
* **[docs]** ``eodag-cube`` `Python API documentation
  <https://eodag.readthedocs.io/en/latest/notebooks/api_user_guide/8_post_process.html#Data-access-with-eodag-cube>`_
  (:pull:`1511`), ``usgs`` registration update (:pull:`1551`)
* Various minor fixes and improvements (:pull:`1502`)(:pull:`1540`)(:pull:`1541`)(:pull:`1547`)(:pull:`1552`)
  (:pull:`1566`)(:pull:`1568`)
* External product types reference updates (:pull:`1510`)(:pull:`1525`)(:pull:`1539`)(:pull:`1548`)(:pull:`1553`)
  (:pull:`1557`)(:pull:`1565`)

v3.1.0b2 (2025-02-03)
=====================

Core features and fixes
-----------------------

* Assets keys uniformization using drivers (:pull:`1488`)
* ``ssl_verify`` setting for ``get_quicklook`` (:pull:`1490`, thanks `@tromain <https://github.com/tromain>`_)
* Queryables merged by provider priority (:pull:`1431`)

Providers and product types updates
-----------------------------------

* ``geodes_s3`` as new provider (:pull:`1506`)
* default search timeout to 20s (:pull:`1505`)
* ``geodes`` ``relativeOrbitNumber`` property (:pull:`1499`) and numerical queryables fix (:pull:`1507`)

Miscellaneous
-------------

* **[docs]** Updated tutorials using ``eodag-cube`` (:pull:`1436`) and minor fixes (:pull:`1498`)(:pull:`1500`)
* **[style]** Typing update for generics (:pull:`1486`)
* Various minor fixes and improvements (:pull:`1471`)(:pull:`1472`)(:pull:`1473`)(:pull:`1475`)(:pull:`1477`)
  (:pull:`1479`)(:pull:`1480`)(:pull:`1483`)(:pull:`1492`)(:pull:`1503`)(:pull:`1504`)
* External product types reference updates (:pull:`1460`)(:pull:`1478`)(:pull:`1484`)(:pull:`1487`)(:pull:`1493`)
  (:pull:`1494`)

v3.1.0b1 (2025-01-13)
=====================

Core features and fixes
-----------------------

* Updated `queryables <https://eodag.readthedocs.io/en/latest/notebooks/api_user_guide/4_queryables.html>`_ mechanism
  and ecmwf-like plugins (:pull:`1397`)(:pull:`1427`)(:pull:`1462`)
* Order and download polling times update (:pull:`1440`)
* Do not retry downloading skipped products during download_all (:pull:`1465`)
* Renamed record files that were using previous mechanism (:pull:`1396`, thanks `@gasparakos\
  <https://github.com/gasparakos>`_)
* New ``to_lower()`` and ``to_upper()`` `parameters mapping\
  <https://eodag.readthedocs.io/en/latest/params_mapping.html#formatters>`_ methods (:pull:`1410`, thanks
  `@jgaucher-cs <https://github.com/jgaucher-cs>`_)

Providers and product types updates
-----------------------------------

* ``geodes`` updated ``id`` (:pull:`1441`) and ``tileIdentifier`` parameters (:pull:`1457`), and metadata mapping fix
  (:pull:`1468`)
* New MTG product types for ``eumetsat_ds`` (:pull:`1455`)
* ``FIRE_HISTORICAL`` on ``wekeo_ecmwf`` (:pull:`1392`)
* Various product types metadata-mapping and default values updates: for ``cop_ads`` and ``wekeo_ecmwf`` (:pull:`1389`),
  GLOFAS and EFAS product types (:pull:`1467`), ``EEA_DAILY_VI`` on ``wekeo_main`` (:pull:`1464`)

Plugins new features and fixes
------------------------------

* Removed default :class:`~eodag.plugins.download.http.HTTPDownload` zip extension (:pull:`1400`)
* Order and poll without downloading (:pull:`1437`)
* :class:`~eodag.plugins.authentication.token.TokenAuth` distinct headers for token retrieve and authentication
  (:pull:`1451`, thanks `@jgaucher-cs <https://github.com/jgaucher-cs>`_)
* Compare only offset-aware datetimes on openid authentication plugins (:pull:`1418`)
* Fixed ``creodias_s3`` search and download when no asset is available (:pull:`1425`)

Server mode
-----------

* Dedicated liveness endpoint added (:pull:`1353`)
* Processing level parsing fix in external STAC collections (:pull:`1429`)

Miscellaneous
-------------
* **[docs]** `Queryables <https://eodag.readthedocs.io/en/latest/notebooks/api_user_guide/4_queryables.html>`_
  documentation in a dedicated section (:pull:`1447`)
* Various minor fixes and improvements (:pull:`1390`)(:pull:`1403`)(:pull:`1411`)(:pull:`1415`)(:pull:`1419`)
  (:pull:`1428`)(:pull:`1430`)(:pull:`1434`)(:pull:`1445`)(:pull:`1448`)(:pull:`1458`)(:pull:`1466`)
* External product types reference updates (:pull:`1387`)(:pull:`1391`)(:pull:`1401`)(:pull:`1404`)(:pull:`1406`)
  (:pull:`1408`)(:pull:`1416`)(:pull:`1424`)(:pull:`1453`)(:pull:`1459`)

v3.0.1 (2024-11-06)
===================

Providers and product types updates
-----------------------------------

* ``geodes`` as new provider (:pull:`1357`)(:pull:`1363`)
* ``cop_ewds`` as new provider (:pull:`1331`)
* Removed ``astraea_eod`` provider (:pull:`1383`)
* Fixed ``S2_MSI_L1C`` search-by-id for ``earth_search`` (:pull:`1053`)
* MSG product types added (:pull:`1348`)
* Fixed order for some ``dedl`` product-types (:pull:`1358`)

Plugins new features and fixes
------------------------------

* Authenticate only when needed in :class:`~eodag.plugins.download.http.HTTPDownload` (:pull:`1370`)
* Various fixes for ``cop_marine`` (:pull:`1336`)(:pull:`1364`)
* OpenID token expiration fix and ``oidc_config_url`` usage (:pull:`1346`)
* Concurrent requests for ``wekeo_cmems`` product-types fetch (:pull:`1374`)
* Error is raised when :class:`~eodag.plugins.download.http.HTTPDownload` order fails (:pull:`1338`)

Miscellaneous
-------------
* **[build]** Add ``python3.13`` and drop ``python3.8`` support (:pull:`1344`)
* **[docs]** `Plugins <https://eodag.readthedocs.io/en/latest/plugins.html>`_ and `utils\
  <https://eodag.readthedocs.io/en/latest/api_reference/utils.html>`_ documention update (:pull:`1297`)
* **[docs]**  `conda optional dependencies\
  <https://eodag.readthedocs.io/en/latest/getting_started_guide/install.html#conda>`_  handling (:pull:`1343`)
* **[docs]**  Fixed ``auxdata`` reference in tutorials (:pull:`1372`, thanks `@emmanuel-ferdman\
  <https://github.com/emmanuel-ferdman>`_)
* **[ci]** Tests speedup using ``uv`` and ``tox-uv`` (:pull:`1347`)
* **[ci]** ``wekeo`` product types included in external product types reference (:pull:`1377`)
* Various minor fixes and improvements (:pull:`1298`)(:pull:`1335`)(:pull:`1340`)(:pull:`1341`)(:pull:`1351`)
  (:pull:`1367`)(:pull:`1365`)(:pull:`1368`)(:pull:`1379`)
* External product types reference updates (:pull:`1342`)(:pull:`1356`)(:pull:`1359`)(:pull:`1360`)(:pull:`1362`)
  (:pull:`1366`)(:pull:`1369`)(:pull:`1373`)(:pull:`1375`)(:pull:`1378`)(:pull:`1381`)(:pull:`1384`)

v3.0.0 (2024-10-10)
===================

|:warning:| Breaking changes since last stable (`v2.12.1 <changelog.rst#v2-12-1-2024-03-05>`_)
----------------------------------------------------------------------------------------------

* [v3.0.0b1] `search() <https://eodag.readthedocs.io/en/latest/notebooks/api_user_guide/3_search.html#search()>`_ method
  now returns only a :class:`~eodag.api.search_result.SearchResult` instead of a 2 values tuple (:pull:`1200`). It can
  optionally store the estimated total number of products in ``SearchResult.number_matched`` if the method is called
  with ``count=True`` (``False`` by  default).
* [v3.0.0b1] Packaging refactoring and new `optional dependencies
  <https://eodag.readthedocs.io/en/latest/getting_started_guide/install.html#optional-dependencies>`_ (:pull:`1108`)
  (:pull:`1219`). EODAG default installs with a minimal set of dependencies.
  New sets of extra requirements are: ``eodag[all]``, ``eodag[all-providers]``, ``eodag[ecmwf]``, ``eodag[usgs]``,
  ``eodag[csw]``, ``eodag[server]``. Previous existing sets of extra requirements are also kept:
  ``eodag[notebook]``, ``eodag[tutorials]``, ``eodag[dev]``, ``eodag[docs]``.
* [v3.0.0b3] :meth:`~eodag.api.core.EODataAccessGateway.download` / :class:`~eodag.types.download_args.DownloadConf`
  parameters ``outputs_prefix`` and ``outputs_extension`` renamed to ``output_dir`` and ``output_extension``
  (:pull:`1279`)

|:loudspeaker:| Major changes since last stable (`v2.12.1 <changelog.rst#v2-12-1-2024-03-05>`_)
-----------------------------------------------------------------------------------------------

Core features and fixes
^^^^^^^^^^^^^^^^^^^^^^^

* **[v3.0.0]** Sharable and multiple authentication plugins per provider (:pull:`1292`)(:pull:`1329`)(:pull:`1332`)
* [v3.0.0b3] New :meth:`~eodag.api.core.EODataAccessGateway.add_provider` method (:pull:`1260`)
* [v3.0.0b2] New :class:`~eodag.api.search_result.SearchResult` HTML representation for notebooks (:pull:`1243`)
* [v3.0.0b1] Search results sort feature (:pull:`943`)
* [v3.0.0b1] Providers groups (:pull:`1071`)
* [v3.0.0b1] Configurable download timeout (:pull:`1124`)

Providers and product types updates
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* **[v3.0.0]** Updated ``cop_ads`` and ``cop_cds`` to new cds api (:pull:`1284`)
* **[v3.0.0]** ``wekeo`` split into ``wekeo_main`` and ``wekeo_ecmwf`` providers (:pull:`1214`)
* [v3.0.0b1] `dedl <https://hda.data.destination-earth.eu/ui>`_ as new provider (:pull:`750`)
* [v3.0.0b1] `dedt_lumi <https://polytope.lumi.apps.dte.destination-earth.eu/openapi>`_ as new provider (:pull:`1119`)
  (:pull:`1126`), with authentication using destine credentials (:pull:`1127`)
* [v3.0.0b1] `cop_marine <https://marine.copernicus.eu/>`_ as new provider (:pull:`1131`)(:pull:`1224`)
* [v3.0.0b1] `eumetsat_ds <https://data.eumetsat.int/>`_ as new provider (:pull:`1060`), including `METOP` product types
  (:pull:`1143`)(:pull:`1189`)
* [v3.0.0b1] `OData` API usage for ``creodias`` & ``cop_dataspace`` (:pull:`1149`)

Plugins new features and fixes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* [v3.0.0b1] Standardized download output tree (:pull:`746`)
* [v3.0.0b1] ``flatten_top_dirs`` download plugins option set to true by default (:pull:`1220`)
* [v3.0.0b1] ``base_uri`` download plugins setting is not systematically mandatory any more (:pull:`1230`)
* [v3.0.0b1] Allow no auth for :class:`~eodag.plugins.download.http.HTTPDownload` download requests (:pull:`1196`)

Server mode
^^^^^^^^^^^

* [v3.0.0b1] Server-mode rework and cql2 support (:pull:`966`)
* [v3.0.0b1] Offline products order handling (:pull:`918`)
* **[v3.0.0]** Browsable catalogs removed (:pull:`1306`)

Miscellaneous
^^^^^^^^^^^^^

* **[v3.0.0b1 to v3.0.0][style]** type hints fixes and ``mypy`` in ``tox`` (:pull:`1052`)(:pull:`1253`)(:pull:`1269`)
  (:pull:`1326`)
* **[v3.0.0][docs]** Developer documentation update (:pull:`1327`)

Remaining changes since `v3.0.0b3 <changelog.rst#v3-0-0b3-2024-08-01>`_
-----------------------------------------------------------------------

Core features and fixes
^^^^^^^^^^^^^^^^^^^^^^^

* Improve search and authentication errors format (:pull:`1237`)

Providers and product types updates
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* Handle ``cop_marine`` in-situ historical data (:pull:`1301`)
* Fixes for ``wekeo``: ``GRIDDED_GLACIERS_MASS_CHANGE`` order link (:pull:`1258`), yaml issue in provider config
  (:pull:`1315`)
* Fixes for ``wekeo_ecmwf``: ``hydrological_year`` usage (:pull:`1313`), fixed default dates (:pull:`1288`)

Plugins new features and fixes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* Raise an error if no data available on :class:`~eodag.plugins.download.aws.AwsDownload` (:pull:`1257`)

Server mode
^^^^^^^^^^^

* Fixed *queryables* issues and parameters prefixes (:pull:`1318`)
* Send ``search_stac_items()`` in its own threadpool (:pull:`1323`)
* Fixed STAC collections metadata (:pull:`1278`)
* Updated logs format (:pull:`1238`)

Miscellaneous
^^^^^^^^^^^^^

* **[ci]** ``mypy`` in linting github action (:pull:`1326`), actions updates (:pull:`1310`)(:pull:`1314`)
* Various minor fixes and improvements (:pull:`1256`)(:pull:`1263`)(:pull:`1276`)(:pull:`1289`)(:pull:`1294`)
  (:pull:`1295`)(:pull:`1296`)(:pull:`1300`)(:pull:`1303`)(:pull:`1304`)(:pull:`1308`)(:pull:`1333`)
* External product types reference updates (:pull:`1290`)(:pull:`1316`)(:pull:`1322`)(:pull:`1334`)

v3.0.0b3 (2024-08-01)
=====================

|:warning:| Breaking changes
----------------------------

* :meth:`~eodag.api.core.EODataAccessGateway.download` / :class:`~eodag.types.download_args.DownloadConf` parameters
  ``outputs_prefix`` and ``outputs_extension`` renamed to ``output_dir`` and ``output_extension`` (:pull:`1279`)

Core features and fixes
-----------------------

* New :meth:`~eodag.api.core.EODataAccessGateway.add_provider` method (:pull:`1260`)
* Handle integers as ``locations`` shapefile attributes (:pull:`1280`)
* Renames some parameters and methods to snake_case (:pull:`1271`)
* Sorted discovered product types (:pull:`1250`)

Providers and product types updates
-----------------------------------

* Fixes ``usgs`` search by id (:pull:`1262`)
* Adds ``S1_SAR_GRD_COG`` and new odata query parameters for ``cop_dataspace`` (:pull:`1277`, thanks
  `@ninsbl <https://github.com/ninsbl>`_)
* Adds ``GRIDDED_GLACIERS_MASS_CHANGE`` on provider ``cop_cds`` (:pull:`1255`)
* Removes ``cacheable`` parameter for ``wekeo`` order requests (:pull:`1239`)

Plugins new features and fixes
------------------------------

* ``aws_session_token`` support in :class:`~eodag.plugins.authentication.aws_auth.AwsAuth` (:pull:`1267`)
* :class:`~eodag.plugins.download.http.HTTPDownload` asset ``HEAD`` check and ``ssl_verify`` (:pull:`1266`)
* Product types discovery disabled by default on :class:`~eodag.plugins.search.static_stac_search.StaticStacSearch`
  (:pull:`1259`)

Miscellaneous
-------------

* **[style]** type hints fixes and ``mypy`` in ``tox`` (:pull:`1253`)(:pull:`1269`)
* **[docs]** v3 breaking changes (:pull:`1281`), :meth:`~eodag.api.core.EODataAccessGateway.download` kwargs
  (:pull:`1282`), autosummary fixes (:pull:`1264`) and changelog update (:pull:`1254`)
* **[ci]** Github actions updates (:pull:`1249`)
* **[test]** Fixed end-to-end tests (:pull:`1236`)
* External product types reference updates (:pull:`1244`)(:pull:`1246`)(:pull:`1251`)

v3.0.0b2 (2024-06-29)
=====================

Core features and fixes
-----------------------

* New :class:`~eodag.api.search_result.SearchResult` HTML representation for notebooks (:pull:`1243`)

Plugins new features and fixes
------------------------------

* Fixed missing ``products`` configuration in ``Api`` plugin download (:pull:`1241`)
* Fixed ``pagination`` configuration to be not allways mandatory (:pull:`1240`)

Miscellaneous
-------------

* **[docs]** Custom mock search plugin example (:pull:`1242`)
* External product types reference updates (:pull:`1234`)

v3.0.0b1 (2024-06-24)
=====================

|:warning:| Breaking changes
----------------------------

* `search() <https://eodag.readthedocs.io/en/latest/notebooks/api_user_guide/3_search.html#search()>`_ method now
  returns only a :class:`~eodag.api.search_result.SearchResult` instead of a 2 values tuple (:pull:`1200`). It can
  optionally store the estimated total number of products in ``SearchResult.number_matched`` if the method is called
  with ``count=True`` (``False`` by  default).
* Packaging refactoring and new `optional dependencies
  <https://eodag.readthedocs.io/en/latest/getting_started_guide/install.html#optional-dependencies>`_ (:pull:`1108`)
  (:pull:`1219`). EODAG default installs with a minimal set of dependencies.
  New sets of extra requirements are: ``eodag[all]``, ``eodag[all-providers]``, ``eodag[ecmwf]``, ``eodag[usgs]``,
  ``eodag[csw]``, ``eodag[server]``. Previous existing sets of extra requirements are also kept:
  ``eodag[notebook]``, ``eodag[tutorials]``, ``eodag[dev]``, ``eodag[docs]``.

Core features and fixes
-----------------------

* Search results sort feature (:pull:`943`)
* Providers groups (:pull:`1071`)
* Configurable download timeout (:pull:`1124`)
* `Search by id <https://eodag.readthedocs.io/en/stable/notebooks/api_user_guide/3_search.html#id-and-provider>`_ now
  uses :meth:`~eodag.api.core.EODataAccessGateway.search_all` and
  `crunch <https://eodag.readthedocs.io/en/stable/notebooks/api_user_guide/6_crunch.html#Filter-by-property>`_
  (:pull:`1099`).
* Free text search available for all fields when `guessing a product type
  <https://eodag.readthedocs.io/en/stable/notebooks/api_user_guide/6_crunch.html#Filter-by-property>`_ (:pull:`1070`),
  mission dates filtering support (:pull:`1222`)
* Configurable requests ``ssl_verify`` (:pull:`1045`)
* Download record hash independent from provider (:pull:`1023`)
* Fixed and refactored `queryables` (:pull:`1050`)(:pull:`1097`)(:pull:`1102`)(:pull:`1157`), authentication fix
  (:pull:`1194`), support for local constraints files (:pull:`1105`)
* Fixed `metadata mapping` in templates detection (:pull:`1139`), ``format_query_params()`` fixes (:pull:`1145`) and
  refactor (:pull:`1142`). Configurable assets filtering (:pull:`1033`).

Providers and product types updates
-----------------------------------

* `dedl <https://hda.data.destination-earth.eu/ui>`_ as new provider (:pull:`750`)
* `dedt_lumi <https://polytope.lumi.apps.dte.destination-earth.eu/openapi>`_ as new provider (:pull:`1119`)
  (:pull:`1126`), with authentication using destine credentials (:pull:`1127`)
* `cop_marine <https://marine.copernicus.eu/>`_ as new provider (:pull:`1131`)(:pull:`1224`)
* `eumetsat_ds <https://data.eumetsat.int/>`_ as new provider (:pull:`1060`), including `METOP` product types
  (:pull:`1143`)(:pull:`1189`)
* `OData` API usage for ``creodias`` & ``cop_dataspace`` (:pull:`1149`), fixes for empty geometries (:pull:`1186`),
  search datetime intervals (:pull:`1158`), and removed `discover_product_types` (:pull:`1112`)
* ``cop_ads`` and ``cop_cds`` now use :class:`~eodag.plugins.search.build_search_result.BuildSearchResult` and
  :class:`~eodag.plugins.download.http.HTTPDownload` instead of move ``CdsApi`` (:pull:`1029`), `EFAS` dates formatting
  (:pull:`1178`), ``area`` metadata mapping fix (:pull:`1225`)
* ``wekeo`` now uses `hda-broker 2.0` API (:pull:`1034`), lists queryables (:pull:`1104`), has fixed pagination
  (:pull:`1098`) and CLMS search by id (:pull:`1100`)
* Adjusted timeouts (:pull:`1163`)
* Opened time intervals supported for STAC providers (:pull:`1144`)
* New product types (:pull:`1164`)(:pull:`1227`), providers and product types configuration update (:pull:`1212`)

Plugins new features and fixes
------------------------------

* Standardized download output tree (:pull:`746`)
* Refactored search plugins methods to use ``PreparedSearch`` and ``RawSearchResult`` new classes (:pull:`1191`)
* Refresh token for :class:`~eodag.plugins.authentication.openid_connect.OIDCAuthorizationCodeFlowAuth` plugin
  (:pull:`1138`), tests (:pull:`1135`), and fix (:pull:`1232`)
* :class:`~eodag.plugins.authentication.header.HTTPHeaderAuth` accepts headers definition in credentials (:pull:`1215`)
* ``flatten_top_dirs`` download plugins option set to true by default (:pull:`1220`)
* ``base_uri`` download plugins setting is not systematically mandatory any more (:pull:`1230`)
* Re-login in :class:`~eodag.plugins.apis.usgs.UsgsApi` plugin on api file error (:pull:`1046`)
* Allow no auth for :class:`~eodag.plugins.download.http.HTTPDownload` download requests (:pull:`1196`)
* Refactorization of ``Api`` base plugin that now inherits from ``Search`` and ``Download`` (:pull:`1051`)
* ``orderLink`` support in `build_search_result.*` plugins (:pull:`1082`), and parsing fix (:pull:`1091`)
* Fixed resume interrupted assets download using :class:`~eodag.plugins.download.http.HTTPDownload` (:pull:`1017`)

Server mode
-----------

* Server-mode rework and cql2 support (:pull:`966`)
* Offline products order handling (:pull:`918`)
* External enhanced product types metadata (:pull:`1008`)(:pull:`1171`)(:pull:`1176`)(:pull:`1180`)(:pull:`1197`)
* Collections search using updated :meth:`~eodag.api.core.EODataAccessGateway.guess_product_type` (:pull:`909`)
* Providers groups (:pull:`1192`), and fixes for listing (:pull:`1187`) and items self links (:pull:`1090`)
* ``HEAD`` requests enabled (:pull:`1120`)
* LRU caching (:pull:`1073`)
* Additional item properties (:pull:`1170`)
* ``order`` and ``storage`` extensions usage (:pull:`1117`)
* ``bbox`` in queryables (:pull:`1185`), fixed some types missing (:pull:`1083`)
* Blacklist configution for assets alternate URLs (:pull:`1213`)
* ``id`` vs ``title`` in item metadata fix (:pull:`1193`)
* Error handling fixes (:pull:`1078`)(:pull:`1103`)(:pull:`1182`)
* Other server-mode fixes  (:pull:`1065`)(:pull:`1087`)(:pull:`1094`)(:pull:`1095`)(:pull:`1096`)(:pull:`1106`)
  (:pull:`1113`)(:pull:`1115`)(:pull:`1156`)(:pull:`1174`)(:pull:`1210`)(:pull:`1221`)(:pull:`1223`)

Miscellaneous
-------------

* **[build]** Updated requirements for ``uvicorn`` (:pull:`1152`), ``shapely`` (:pull:`1155`), ``orjson`` (:pull:`1150`)
  (:pull:`1079`)
* **[build]** Remove ``requests-ftp`` (:pull:`1085`)
* **[style]** type hints related fixes and refactoring (:pull:`1052`)
* **[docs]** sphinx theme updated and removed jquery (:pull:`1054`), newlines between badges fixes (:pull:`1109`), and
  other documentation fixes and updates (:pull:`1057`)(:pull:`1059`)(:pull:`1062`)(:pull:`1063`)(:pull:`1081`)
  (:pull:`1121`)(:pull:`1122`)
* **[ci]** Fetch product types Github action updates (:pull:`1202`)(:pull:`1205`)
* Various minor fixes and improvements (:pull:`1072`)(:pull:`1077`)(:pull:`1101`)(:pull:`1111`)(:pull:`1118`)
  (:pull:`1132`)(:pull:`1141`)(:pull:`1190`)
* External product types reference updates (:pull:`1027`)(:pull:`1028`)(:pull:`1086`)(:pull:`1093`)(:pull:`1107`)
  (:pull:`1110`)(:pull:`1114`)(:pull:`1136`)(:pull:`1137`)(:pull:`1140`)(:pull:`1146`)(:pull:`1151`)(:pull:`1153`)
  (:pull:`1160`)(:pull:`1165`)(:pull:`1203`)(:pull:`1204`)(:pull:`1206`)(:pull:`1207`)(:pull:`1208`)(:pull:`1229`)

v2.12.1 (2024-03-05)
====================

* `CdsApi` queryables fix (:pull:`1048`)

v2.12.0 (2024-02-19)
====================

* Individual product asset download methods (:pull:`932`)
* New environment variable `EODAG_CFG_DIR` available for custom configuration directory (:pull:`927`)
* New `list_queryables <https://eodag.readthedocs.io/en/latest/notebooks/api_user_guide/3_search.html#Queryables>`_
  method, available through python API and server mode, and using product-types constraints if available (:pull:`911`)
  (:pull:`917`)(:pull:`974`)(:pull:`977`)(:pull:`978`)(:pull:`981`)(:pull:`1005`)
* Removes limited RPC server (:pull:`1011`)
* Product types aliases (:pull:`905`)
* New provider `creodias_s3` (:pull:`986`)(:pull:`1002`)
* `earth_search` endpoint updated from v0 to v1 (:pull:`754`)
* `wekeo` endpoint updated to *wekeo2 wekeo-broker API* (:pull:`1010`)
* New product types added for `cop_ads` and `cop_cds` (:pull:`898`)
* Adds missing `tileIdentifier` and `quicklook` for `creodias`, `creodias_s3` and `cop_dataspace` (:pull:`957`)
  (:pull:`1014`)
* HTTP download with `CdsApi` (:pull:`946`)
* Download streaming available for :class:`~eodag.plugins.download.aws.AwsDownload` plugin (:pull:`997`)
* Lists STAC alternate assets in server mode (:pull:`961`)
* `_dc_qs` used in server-mode to store `CdsApi` search criteria (:pull:`958`)(:pull:`1000`)
* New eodag exception :class:`~eodag.utils.exceptions.TimeOutError` (:pull:`982`)
* Cast loaded environment variables type using config type-hints (:pull:`987`)
* Type hints fixes (:pull:`880`)(:pull:`983`)
* Requirements updates (:pull:`1020`)(:pull:`1021`)
* Various server mode fixes (:pull:`891`)(:pull:`895`)(:pull:`947`)(:pull:`992`)(:pull:`1001`)
* Various minor fixes and improvements (:pull:`934`)(:pull:`935`)(:pull:`936`)(:pull:`962`)(:pull:`969`)(:pull:`976`)
  (:pull:`980`)(:pull:`988`)(:pull:`991`)(:pull:`996`)(:pull:`1003`)(:pull:`1009`)(:pull:`1013`)(:pull:`1016`)
  (:pull:`1019`)(:pull:`1022`)(:pull:`1024`)(:pull:`1025`)

v2.11.0 (2023-11-20)
====================

* Fallback mechanism for search (:pull:`753`)(:pull:`807`)
* `creodias` and `cop_dataspace` configuration update (from `OData` to `OpenSearch`) (:pull:`866`)(:pull:`883`)
  (:pull:`894`)(:pull:`915`)(:pull:`929`)
* Removes `mundi` provider (:pull:`890`)
* Copernicus DEM product types available through creodias (:pull:`882`)
* `wekeo` driver update and new product types (:pull:`798`)(:pull:`840`)(:pull:`856`)(:pull:`902`)
* Allows `provider` search parameter to directly search on it (:pull:`790`)
* Refresh token usage in `KeycloakOIDCPasswordAuth` (`creodias` and `cop_dataspace`) (:pull:`921`)
* Per-provider search timeout (:pull:`841`)
* New `EODAG_PROVIDERS_CFG_FILE` environment variable for custom provider configuration setting (:pull:`836`)
* Many server-mode updates and fixes: `queryables` endpoints (:pull:`795`), built-in Swagger doc update (:pull:`846`),
  exceptions handling (:pull:`794`)(:pull:`806`)(:pull:`812`)(:pull:`829`),
  provider setting (:pull:`808`) and returned information (:pull:`884`)(:pull:`879`), multithreaded requests (:pull:`843`),
  opened time intervals fixes (:pull:`837`), search-by-ids fix (:pull:`822`), intersects parameter fixes (:pull:`796`)
  (:pull:`797`)
* Adds support for Python 3.12 (:pull:`892`) and removes support for Python 3.7 (:pull:`903`)
* Fixes plugin manager rebuild (solves preferred provider issues) (:pull:`919`)
* Reformatted logs (:pull:`842`)(:pull:`885`)
* Adds static type information (:pull:`863`)
* Various minor fixes and improvements (:pull:`759`)(:pull:`788`)(:pull:`791`)(:pull:`793`)(:pull:`802`)(:pull:`804`)
  (:pull:`805`)(:pull:`813`)(:pull:`818`)(:pull:`819`)(:pull:`821`)(:pull:`824`)(:pull:`825`)(:pull:`828`)(:pull:`830`)
  (:pull:`832`)(:pull:`835`)(:pull:`838`)(:pull:`844`)(:pull:`867`)(:pull:`868`)(:pull:`872`)(:pull:`877`)(:pull:`878`)
  (:pull:`881`)(:pull:`893`)(:pull:`899`)(:pull:`913`)(:pull:`920`)(:pull:`925`)(:pull:`926`)

v2.11.0b1 (2023-07-28)
======================

* `wekeo <https://www.wekeo.eu>`_ as new provider (:pull:`772`)
* Server-mode Flask to FastAPI (:pull:`701`)
* Server-mode download streaming (:pull:`742`)
* Updated creodias authentication mechanism to Creodias-new (:pull:`763`)
* Helm Chart (:pull:`739`)
* Server-mode search by (multiples) id(s) (:pull:`776`)
* Fixed server-mode parallel requests (:pull:`741`)
* Keep origin assets in the stac server response (:pull:`681`)
* Enable single-link download for STAC providers (:pull:`757`)
* Fixes missing provider in STAC download link (:pull:`774`)
* Better documentation for `guess_product_type()\
  <https://eodag.readthedocs.io/en/latest/notebooks/api_user_guide/3_search.html#Guess-a-collection>`_ (:pull:`756`)
* Fixed issue with docker image user directory (:pull:`764`)
* Various minor fixes and improvements (:pull:`720`)(:pull:`717`)(:pull:`722`)(:pull:`723`)(:pull:`724`)(:pull:`727`)
  (:pull:`729`)(:pull:`731`)(:pull:`737`)(:pull:`738`)(:pull:`743`)(:pull:`744`)(:pull:`745`)(:pull:`749`)(:pull:`751`)
  (:pull:`762`)(:pull:`771`)(:pull:`775`)(:pull:`777`)

v2.10.0 (2023-04-18)
====================

* `hydroweb_next` (`hydroweb.next <https://hydroweb.next.theia-land.fr>`_), thematic hub for hydrology data access,
  as new provider (:pull:`711`)
* Search by tile standardized using ``tileIdentifier`` new query parameter and metadata (:pull:`713`)
* Server mode STAC API version updated to `1.0.0-rc.3` (:pull:`697`)
* Better catalogs title and description in server mode (:pull:`710`)
* Server mode advanced tests (:pull:`708`), and fixes for catalogs dates filtering (:pull:`706`), catalogs cloud-cover
  filtering (:pull:`705`), missing `sensorType` error for discovered product types (:pull:`699`), broken links through
  STAC search endpoint (:pull:`698`)
* Added links to `eodag-server <https://hub.docker.com/r/csspace/eodag-server>`_ image on Dockerhub (:pull:`715`)
* EODAG server installation update in docker image (:pull:`700`) and sigterm fix (:pull:`702`)
* STAC browser docker image update (:pull:`704`)
* Various minor fixes and improvements (:pull:`693`)(:pull:`694`)(:pull:`695`)(:pull:`696`)(:pull:`703`)(:pull:`707`)
  (:pull:`712`)(:pull:`714`)

v2.9.2 (2023-03-31)
===================

* `planetary_computer`, `Microsoft Planetary Computer <https://planetarycomputer.microsoft.com/>`_  as new provider
  (:pull:`659`)
* Fetch product types optimization (:pull:`683`)
* Fixes external product types update for unknown provider (:pull:`682`)
* Default dates and refactor for `CdsApi` and :class:`~eodag.plugins.apis.ecmwf.EcmwfApi` (:pull:`672`)(:pull:`678`)(:pull:`679`)
* `peps` `storageStatus` update (:pull:`677`)
* Customized and faster `deepcopy` (:pull:`664`)
* Various minor fixes and improvements (:pull:`665`)(:pull:`666`)(:pull:`667`)(:pull:`668`)(:pull:`669`)(:pull:`670`)
  (:pull:`675`)(:pull:`688`)(:pull:`690`)(:pull:`691`)

v2.9.1 (2023-02-27)
===================

* ``cop_dataspace``, `Copernicus Data Space <https://dataspace.copernicus.eu>`_  as new provider (:pull:`658`)
* EODAG specific `User-Agent` appended to requests headers (:pull:`656`)
* ``Sentinel-5P`` and other product types updates for ``creodias``, ``mundi`` and ``onda`` (:pull:`657`)
* Handle missing geometries through new ``defaultGeometry`` :class:`~eodag.api.product._product.EOProduct` property
  (:pull:`653`)
* ``mundi`` `GeoRSS` geometries handling (:pull:`654`)
* Fixes search errors handling (:pull:`660`)
* Various minor fixes and improvements (:pull:`649`)(:pull:`652`)

v2.9.0 (2023-02-16)
===================

* Optimizes search time mixing count and search requests when possible (:pull:`632`)
* Optimizes search time with rewritten ``JSONPath.parse`` usage now based on a
  `common_metadata_mapping_path` (:pull:`626`)
* ``creodias`` API update, from resto to OData (:pull:`623`)(:pull:`639`)
* Optimizes and updates ``onda`` search (:pull:`616`)(:pull:`636`)
* Fixes OFFLINE products order mechanism for ``mundi`` provider (:pull:`645`)
* Download progress bar adjustable refresh time (:pull:`643`)
* Simplify ``OData`` metadata mapping using pre-mapping (:pull:`622`)
* Fixes download error for single-asset products on STAC providers (:pull:`634`)
* Tests execution optimized (:pull:`631`)
* Various minor fixes and improvements (:pull:`612`)(:pull:`619`)(:pull:`620`)(:pull:`621`)(:pull:`624`)(:pull:`625`)
  (:pull:`629`)(:pull:`630`)(:pull:`635`)(:pull:`638`)(:pull:`640`)(:pull:`641`)(:pull:`642`)(:pull:`644`)(:pull:`646`)
  (:pull:`647`)

v2.8.0 (2023-01-17)
===================

* `meteoblue <https://content.meteoblue.com/en/business-solutions/weather-apis/dataset-api>`_ as new forecast provider,
  in the context of DOMINO-X (:pull:`604`)
* `SARA <https://copernicus.nci.org.au/sara.client>`_ (Sentinel Australasia Regional Access) as new provider
  (:pull:`578`, thanks `@catchSheep <https://github.com/catchSheep>`_)(:pull:`602`)
* Removes unavailable ```sobloo``` provider (:pull:`607`)
* Landsat collection-1 data no more available on `usgs` (:pull:`601`)
* `Product types catalog\
  <https://eodag.readthedocs.io/en/latest/getting_started_guide/collections.html#product-types-information-csv>`_
  more visible in documentation (:pull:`603`)
* Metadata mapping `to_geo_interface()` renamed to `to_geojson()`
  (`d7565a4 <https://github.com/CS-SI/eodag/pull/604/commits/d7565a4984d356aca20310a87c02692cb879427e>`_)
* Added support for `python3.11` (:pull:`552`)
* Improved http asset size discovery in :class:`~eodag.plugins.download.http.HTTPDownload` (:pull:`566`)
* Various minor fixes and improvements (:pull:`572`)(:pull:`574`)(:pull:`576`)(:pull:`579`)(:pull:`580`)(:pull:`582`)
  (:pull:`586`)(:pull:`588`)(:pull:`589`)(:pull:`590`)(:pull:`592`)(:pull:`593`)(:pull:`595`)(:pull:`597`)(:pull:`598`)
  (:pull:`599`)(:pull:`609`)(:pull:`610`)

v2.7.0 (2022-11-29)
===================

* Fetch external product types before searching for an unkown product type (:pull:`559`)
* Handle local assets in :class:`~eodag.plugins.download.http.HTTPDownload` plugin (:pull:`561`)
* Fetch external product types only for given provider if one is specified (:pull:`557`)
* Fixed request error handling during :meth:`~eodag.api.core.EODataAccessGateway.search_all` (:pull:`554`)
* Various minor fixes and improvements (:pull:`555`)(:pull:`558`)(:pull:`562`)

v2.6.2 (2022-11-15)
===================

* Added new methods to get assets filename from header (:pull:`542`)
* All local files URI formats are now supported (:pull:`545`)
* More tests (:pull:`539`)(:pull:`549`)
* Various minor fixes and improvements (:pull:`535`)(:pull:`540`)(:pull:`541`)(:pull:`543`)(:pull:`544`)(:pull:`553`)

v2.6.1 (2022-10-19)
===================

* Swagger UI now needs to be manually run when using python API (:pull:`529`)
* Removed `cloudCover` restriction in product types discovery (:pull:`530`)
* Some `sensorType` values changed in product types settings to align to `OpenSearch extension for Earth Observation\
  <http://docs.opengeospatial.org/is/13-026r9/13-026r9.html>`_ (:pull:`528`)
* Fixed CSS glitch in `online documentation parameters tables\
  <https://eodag.rtfd.io/en/stable/add_provider.html#parameters-mapping>`_ (:pull:`527`)
* Fixed S3 bucket extraction (:pull:`524`)
* Various minor fixes and improvements (:pull:`522`)(:pull:`523`)(:pull:`525`)(:pull:`526`)

v2.6.0 (2022-10-07)
===================

* New `product types automatic discovery\
  <https://eodag.rtfd.io/en/latest/notebooks/api_user_guide/1_providers_products_available.html#Collections-discovery>`_
  (:pull:`480`)(:pull:`467`)(:pull:`470`)(:pull:`471`)(:pull:`472`)(:pull:`473`)(:pull:`481`)(:pull:`486`)(:pull:`493`)
  (:pull:`491`)(:pull:`500`)
* New providers `cop_ads <https://ads.atmosphere.copernicus.eu>`_ and `cop_cds <https://cds.climate.copernicus.eu>`_
  for Copernicus Atmosphere and Climate Data Stores using `CdsApi` plugin, developed in
  the context of DOMINO-X (:pull:`504`)(:pull:`513`)
* :class:`~eodag.plugins.apis.usgs.UsgsApi` plugin fixed and updated (:pull:`489`)(:pull:`508`)
* Cache usage for ``jsonpath.parse()`` (:pull:`502`)
* Refactored download retry mechanism and more tests (:pull:`506`)
* Drop support of Python 3.6 (:pull:`505`)
* Various minor fixes and improvements (:pull:`469`)(:pull:`483`)(:pull:`484`)(:pull:`485`)(:pull:`490`)(:pull:`492`)
  (:pull:`494`)(:pull:`495`)(:pull:`496`)(:pull:`497`)(:pull:`510`)(:pull:`511`)(:pull:`514`)(:pull:`517`)

v2.5.2 (2022-07-05)
===================

* Fixes missing ``productPath`` property for some ``earth_search`` products (:pull:`480`)

v2.5.1 (2022-06-27)
===================

* Fixed broken :class:`~eodag.plugins.download.aws.AwsDownload` configuration for STAC providers (:pull:`475`)
* Set ``setuptools_scm`` max version for python3.6 (:pull:`477`)

v2.5.0 (2022-06-07)
===================

* `ecmwf <https://www.ecmwf.int/>`_ as new provider with new API plugin :class:`~eodag.plugins.apis.ecmwf.EcmwfApi`
  and `tutorial <https://eodag.readthedocs.io/en/latest/notebooks/tutos/tuto_ecmwf.html>`_, developed in the context
  of DOMINO-X (:pull:`452`)
* ``earth_search_gcs`` as new provider to download on
  `Google Cloud Storage public datasets <https://cloud.google.com/storage/docs/public-datasets>`_
  (:pull:`462`, thanks `@robert-werner <https://github.com/robert-werner>`_)
* STAC search on private servers needing authentication for earch (:pull:`443`)
* Do not list providers without credentials needing authentication for search (:pull:`442`)
* New packaging using `pyproject.toml` and `setup.cfg`, following `PEP 517 <https://peps.python.org/pep-0517/>`_
  recommendations and `setuptools build_meta <https://setuptools.pypa.io/en/latest/build_meta.html>`_ (:pull:`435`)
* `setuptools_scm` usage to have intermediate `dev` versions between releases (:pull:`431`)
* New options for :class:`~eodag.plugins.download.aws.AwsDownload` plugin: `requester_pays`, `base_uri`,
  and `ignore_assets` (:pull:`456`, thanks `@robert-werner <https://github.com/robert-werner>`_)
* :meth:`~eodag.api.search_result.SearchResult.filter_online` and additional convert methods added to
  :class:`~eodag.api.search_result.SearchResult` (:pull:`458`)(:pull:`450`)
* :class:`~eodag.plugins.authentication.token.TokenAuth` can now use headers and url formatting (:pull:`447`)
* All available metadata for `onda` provider is now retrieved (:pull:`440`)
* Various minor fixes and improvements (:pull:`430`)(:pull:`433`)(:pull:`434`)(:pull:`436`)(:pull:`438`)(:pull:`444`)
  (:pull:`448`)(:pull:`449`)(:pull:`451`)(:pull:`460`)(:pull:`464`)

v2.4.0 (2022-03-09)
===================

* STAC API POST requests and Query fragment handled in both
  :class:`~eodag.plugins.search.qssearch.StacSearch` client (:pull:`363`)(:pull:`367`) and server mode (:pull:`417`)
* Added ``downloaded_callback`` parameter to :meth:`~eodag.api.core.EODataAccessGateway.download_all` method
  allowing running a callback after each individual download (:pull:`381`)
* ``cloudCover`` parameter disabled for RADAR product types (:pull:`389`)
* Guess ``EOProduct.product_type`` from properties when missing (:pull:`380`)
* Keywords usage in product types configuration and guess mechanism (:pull:`372`)
* Automatic deletion of downloaded product zip after extraction (:pull:`358`)
* Crunchers are now directly attached to :class:`~eodag.api.search_result.SearchResult` (:pull:`359`)
* Import simplified for :class:`~eodag.api.product._product.EOProduct`, :class:`~eodag.api.search_result.SearchResult`,
  and `Crunchers <https://eodag.readthedocs.io/en/stable/plugins_reference/crunch.html>`_ (:pull:`356`)
* Added support for `python3.10` (:pull:`407`)
* Pytest usage instead of nosetest (:pull:`406`) and tests/coverage reports included in PR (:pull:`411`)(:pull:`416`)
* Various minor fixes and improvements (:pull:`355`)(:pull:`361`)(:pull:`366`)(:pull:`357`)(:pull:`371`)(:pull:`373`)
  (:pull:`374`)(:pull:`377`)(:pull:`379`)(:pull:`388`)(:pull:`394`)(:pull:`393`)(:pull:`405`)(:pull:`401`)(:pull:`398`)
  (:pull:`399`)(:pull:`419`)(:pull:`415`)(:pull:`410`)(:pull:`420`)

v2.3.4 (2021-10-08)
===================

* Link to the new eodag Jupyterlab extension: `eodag-labextension <https://github.com/CS-SI/eodag-labextension>`_
  (:pull:`352`)
* STAC client and server update to STAC 1.0.0 (:pull:`347`)
* Fixes :meth:`~eodag.api.product._product.EOProduct.get_quicklook` for onda provider
  (:pull:`344`, thanks `@drnextgis <https://github.com/drnextgis>`_)
* Fixed issue when downloading ``S2_MSI_L2A`` products from ``mundi`` (:pull:`350`)
* Various minor fixes and improvements (:pull:`340`)(:pull:`341`)(:pull:`345`)

v2.3.3 (2021-08-11)
===================

* Fixed issue when searching by id (:pull:`335`)
* Specified minimal `eodag-cube <https://github.com/CS-SI/eodag-cube>`_ version needed (:pull:`338`)
* Various minor fixes and improvements (:pull:`336`)(:pull:`337`)

v2.3.2 (2021-07-29)
===================

* Fixes duplicate logging in :meth:`~eodag.api.core.EODataAccessGateway.search_all` (:pull:`330`)
* Enable additional arguments like `productType` when searching by id (:pull:`329`)
* Prevent EOL auto changes on windows causing docker crashes (:pull:`324`)
* Configurable eodag logging in docker stac-server (:pull:`323`)
* Fixes missing `productType` in product properties when searching by id (:pull:`320`)
* Various minor fixes and improvements (:pull:`319`)(:pull:`321`)

v2.3.1 (2021-07-09)
===================

- Dockerfile update to be compatible with `stac-browser v2.0` (:pull:`314`)
- Adds new notebook extra dependency (:pull:`317`)
- EOProduct drivers definition update (:pull:`316`)

v2.3.0 (2021-06-24)
===================

- Removed Sentinel-3 products not available on peps any more (:pull:`304`, thanks `@tpfd <https://github.com/tpfd>`_)
- Prevent :meth:`~eodag.utils.notebook.NotebookWidgets.display_html` in ipython shell (:pull:`307`)
- Fixed plugins reload after having updated providers settings from user configuration (:pull:`306`)

v2.3.0b1 (2021-06-11)
=====================

- Re-structured and more complete documentation (:pull:`233`, and also :pull:`224`, :pull:`254`, :pull:`282`,
  :pull:`287`, :pull:`301`)
- Homogenized inconsistent paths returned by :meth:`~eodag.api.core.EODataAccessGateway.download` and
  :meth:`~eodag.api.core.EODataAccessGateway.download_all` methods (:pull:`244`)(:pull:`292`)
- Rewritten progress callback mechanism (:pull:`276`)(:pull:`285`)
- Sentinel products SAFE-format build for STAC AWS providers (:pull:`218`)
- New CLI optional `--quicklooks` flag in `eodag download` command (:pull:`279`,
  thanks `@ahuarte47 <https://github.com/ahuarte47>`_)
- New product types for Sentinel non-SAFE products (:pull:`228`)
- Creodias metadata mapping update (:pull:`294`)
- :meth:`~eodag.utils.logging.setup_logging` is now easier to import (:pull:`221`)
- :func:`~eodag.utils.logging.get_logging_verbose` function added (:pull:`283`)
- Documentation on how to request USGS M2M API access (:pull:`269`)
- User friendly parameters mapping documentation (:pull:`299`)
- Auto extract if extract is not set (:pull:`249`)
- Fixed how :meth:`~eodag.api.core.EODataAccessGateway.download_all` updates the passed list of products (:pull:`253`)
- Fixed user config file loading with settings of providers from ext plugin (:pull:`235`,
  thanks `@ahuarte47 <https://github.com/ahuarte47>`_)
- Improved and less strict handling of misconfigured user settings (:pull:`293`)(:pull:`296`)
- ISO 8601 formatted datetimes accepted by all providers (:pull:`257`)
- `GENERIC_PRODUCT_TYPE` not returned any more by :meth:`~eodag.api.core.EODataAccessGateway.list_product_types`
  (:pull:`261`)
- Warning displayed when searching with non preferred provider (:pull:`260`)
- Search kwargs used for guessing a product type not propagated any more (:pull:`248`)
- Deprecate :meth:`~eodag.api.core.EODataAccessGateway.load_stac_items`,
  :class:`~eodag.plugins.search.static_stac_search.StaticStacSearch` search plugin should be used instead (:pull:`225`)
- `ipywidgets` no more needed in :class:`~eodag.utils.notebook.NotebookWidgets` (:pull:`223`)
- Various minor fixes and improvements (:pull:`219`)(:pull:`246`)(:pull:`247`)(:pull:`258`)(:pull:`233`)(:pull:`273`)
  (:pull:`274`)(:pull:`280`)(:pull:`284`)(:pull:`288`)(:pull:`290`)(:pull:`295`)

v2.2.0 (2021-03-26)
===================

- New :meth:`~eodag.api.core.EODataAccessGateway.search_all` and
  :meth:`~eodag.api.core.EODataAccessGateway.search_iter_page` methods to simplify pagination handling (:pull:`190`)
- Docker-compose files for STAC API server with STAC-browser (:pull:`183`,
  thanks `@apparell <https://github.com/apparell>`_)
- Fixed USGS plugin which now uses M2M API (:pull:`209`)
- Windows support added in Continuous Integration (:pull:`192`)
- Fixes issue with automatically load configution from EODAG external plugins, fixes :issue:`184`
- More explicit signature for :meth:`~eodag.utils.logging.setup_logging`, fixes :issue:`197`
- Various minor fixes

v2.1.1 (2021-03-18)
===================

- Continuous Integration performed with GitHub actions
- Providers config automatically loaded from EODAG external plugins, fixes :issue:`172`
- Various minor fixes

v2.1.0 (2021-03-09)
===================

- `earth_search <https://www.element84.com/earth-search>`_ and
  `usgs_satapi_aws <https://landsatlook.usgs.gov/sat-api>`_ as new providers
- Updated :class:`~eodag.plugins.download.http.HTTPDownload` plugin, handling products with multiple assets
- New plugin :class:`~eodag.plugins.authentication.aws_auth.AwsAuth`, enables AWS authentication using no-sign-request,
  profile, ``~/.aws/*``
- New search plugin :class:`~eodag.plugins.search.static_stac_search.StaticStacSearch` and updated
  `STAC client tutorial <https://eodag.readthedocs.io/en/latest/notebooks/tutos/tuto_stac_client.html>`_
- New tutorial for `Copernicus DEM <https://eodag.readthedocs.io/en/latest/notebooks/tutos/tuto_cop_dem.html>`_
- Remove ``unidecode`` dependency
- Start/end dates passed to sobloo are now in UTC, and make it clear that search dates must be in UTC
- Locations must now be passed to :meth:`~eodag.api.core.EODataAccessGateway.search` method as a dictionary
- Metadata mapping update and uniformization, fixes :issue:`154`
- Raise a :class:`ValueError` when a location search doesn't match any record and add a new ``locations``
  parameter to :meth:`~eodag.api.core.EODataAccessGateway.search`.
- Drop support of Python 3.5

v2.0.1 (2021-02-05)
===================

- Fixes issue when rebuilding index on NFS, see :issue:`151`
- Tests can be run in parallel mode, fixes :issue:`103`

v2.0 (2021-01-28)
=================

- Add a new provider dynamically
- Allow to dynamically set download options, fixes :issue:`145` and :issue:`112`
- New tutorials for STAC and search by geometry, fixes :issue:`139`
- New crunches :class:`~eodag.plugins.crunch.filter_date.FilterDate`,
  :class:`~eodag.plugins.crunch.filter_property.FilterProperty` and updated
  :class:`~eodag.plugins.crunch.filter_overlap.FilterOverlap`, fixes :issue:`137`
- Use ``jsonpath-ng`` instead of ``jsonpath-rw`` and ``pyjq``, ``pyshp`` instead of ``fiona``
- Better wrong or missing credentials handling
- Add warning for the total number of results returned by theia
- Support regex query from locations configuration
- sort_by_extent renamed to group_by_extent
- Documentation and tutorials update
- Various minor fixes, code refactorization, and tests update

v2.0b2 (2020-12-18)
===================

- New method :meth:`~eodag.api.core.EODataAccessGateway.deserialize_and_register`, fixes :issue:`140`
- Load static stac catalogs as :class:`~eodag.api.search_result.SearchResult`
- Search on unknown product types using ``GENERIC_PRODUCT_TYPE``
- ``get_data``, drivers and rpc server moved to `eodag-cube <https://github.com/CS-SI/eodag-cube>`_
- Removed fixed dependencies, fixes :issue:`82`
- Use locations conf template by default

v2.0b1 (2020-11-17)
===================

- STAC API compliant REST server
- Common configuration for STAC providers
- astraea_eod as new STAC provider
- Search by geometry / bbox / location name, fixes :issue:`49`
- removed Python 2.7 support

v1.6.0 (2020-08-24)
===================

- Warning: last release including Python 2.7 support

v1.6.0rc2 (2020-08-11)
======================

- Queryable parameters configuration update for peps
- Fixed re-download error after original zip deletion, fixes :issue:`142`
- Fixed python-dateutil version conflict, fixes :issue:`141`
- Default user configuration file usage in CLI mode
- Fixed error when provider returns geometry as bbox with negative coords, fixes :issue:`143`

v1.6.0rc0 (2020-06-18)
======================

- Github set as default version control repository hosting service for source code and issues
- New provider for AWS: aws_eos (S2_MSI_L1C/L2A, S1_SAR_GRD, L8, CBERS-4, MODIS, NAIP), replaces aws_s3_sentinel2_l1c
- Build SAFE products for AWS Sentinel data
- New theia product types for S2, SPOT, VENUS, OSO
- New search plugin for POST requests (PostJsonSearch)
- Metadata auto discovery (for product properties and search parameter), replaces custom parameter
- Search configuration can be tweaked for each provider product type
- Fixed Lansat-8 search for onda, fixes :issue:`135`
- Advanced tutorial notebook, fixes :issue:`130`
- Various minor fixes, code refactorization, and tests update

v1.5.2 (2020-05-06)
===================

- Fix CLI download_all missing plugin configuration, fixes :issue:`134`

v1.5.1 (2020-04-08)
===================

- ``productionStatus`` parameter renamed to ``storageStatus``,
  see `Parameters Mapping documentation <https://eodag.readthedocs.io/en/latest/intro.html#parameters-mapping>`_

v1.5.0 (2020-04-08)
===================

- ``productionStatus`` parameter standardization over providers
- Not-available products download management, using ``wait``/``timeout``
  :meth:`~eodag.api.core.EODataAccessGateway.download`
  optional parameters, fixes :issue:`125`
- More explicit authentication errors messages
- Update search endoint for aws_s3_sentinel2_l1c and add RequestPayer option usage,
  fixes :issue:`131`

v1.4.2 (2020-03-04)
===================

- Skip badly configured providers in user configuration, see :issue:`129`

v1.4.1 (2020-02-25)
===================

- Warning message if an unknow provider is found in user configuration file,
  fixes :issue:`129`

v1.4.0 (2020-02-24)
===================

- Add to query the parameters set in the provider product type definition
- New :class:`~eodag.plugins.download.s3rest.S3RestDownload` plugin for mundi, fixes :issue:`127`
- S3_OLCI_L2LFR support for mundi, see :issue:`124`
- S2_MSI_L2A support for peps, see :issue:`124`
- Theia-landsat provider moved to theia, fixes :issue:`95`
- Fixed onda query quoting issues, fixes :issue:`128`
- Mundi, creodias and onda added to end-to-end tests
- Gdal install instructions and missing auxdata in ship_detection tutorial
- Sobloo and creodias quicklooks fix
- Eodag logo added and other minor changes to documentation

v1.3.6 (2020-01-24)
===================

- USGS plugin corrections, fixes :issue:`73`
- Fixed py27 encodeurl in querystring
- End-to-end tests update, fixes :issue:`119`
- Default eodag conf used in end-to-end tests, fixes :issue:`98`
- Fixed :meth:`~eodag.api.core.EODataAccessGateway.download_all` method :issue:`118`

v1.3.5 (2020-01-07)
===================

- Removed tqdm_notebook warning, fixes :issue:`117`
- Removed traceback from geom intersection warning, fixes :issue:`114`
- Documentation update for provider priorities and parametters mapping
- New test for readme/pypi syntax

v1.3.4 (2019-12-12)
===================

- Use sobloo official api endpoint, fixes :issue:`115`
- New badges in readme and CS logo
- Set owslib version to 0.18.0 (py27 support dropped)

v1.3.3 (2019-10-11)
===================

- Fixes product configuration for theia provider :issue:`113`

v1.3.2 (2019-09-27)
===================

- Fixes pagination configuration for sobloo provider :issue:`111`

v1.3.1 (2019-09-27)
===================

- Added calls graphs in documentation
- Tutorial notebooks fixes :issue:`109`,
  :issue:`110`
- Download unit display fix :issue:`108`
- Fix date format with sobloo provider :issue:`107`

v1.3.0 (2019-09-06)
===================

- Add parameters mapping in documentation
- Add new queryable parameters for sobloo :issue:`105`
- Fix custom search
- Fix sobloo cloudCoverage query :issue:`106`

v1.2.3 (2019-08-26)
===================

- Binder basic tuto Binder badge only

v1.2.2 (2019-08-23)
===================

- Binder basic tuto working

v1.2.1 (2019-08-23)
===================

- Add binder links

v1.2.0 (2019-08-22)
===================

- Add download_all support by plugins
- Fix GeoJSON rounding issue with new geojson lib

v1.1.3 (2019-08-05)
===================

- Tutorial fix

v1.1.2 (2019-08-05)
===================

- Fix dependency version issue (Jinja2)
- Tutorials fixes and enhancements

v1.1.1 (2019-07-26)
===================

- Updates documentation for custom field

v1.1.0 (2019-07-23)
===================

- Adds custom fields for query string search
- Adapts to new download interface for sobloo

v1.0.1 (2019-04-30)
===================

- Fixes :issue:`97`
- Fixes :issue:`96`

v1.0 (2019-04-26)
=================

- Adds product type search functionality
- Extends the list of search parameters with ``instrument``, ``platform``, ``platformSerialIdentifier``,
  ``processingLevel`` and ``sensorType``
- The cli arguments are now fully compliant with opensearch geo(bbox)/time extensions
- Adds functionality to search products by their ID
- Exposes search products by ID functionality on REST interface
- Exposes get quicklook functionality on REST interface
- Fixes a bug occuring when ``outputs_prefix`` config parameter is not set in user config

v0.7.2 (2019-03-26)
===================

- Fixes bug due to the new version of PyYaml
- Updates documentation and tutorial
- Automatically generates a user configuration file in ``~/.config/eodag/eodag.yml``. This path is overridable by the
  ``EODAG_CFG_FILE`` environment variable.


v0.7.1 (2019-03-01)
===================

- Creates a http rest server interface to eodag
- Switches separator of conversion functions in search parameters: the separator switches from "$" to "#"
- In the providers configuration file, an operator can now specify a conversion to be applied to metadata when
  extracting them from provider search response. See the providers.yml file (sobloo provider, specification of
  startTimeFromAscendingNode extraction) for an example usage of this feature
- The RestoSearch plugin is dismissed and merged with its parent to allow better generalization of the
  QueryStringSearch plugin.
- Simplifies the way eodag search for product types on the providers: the partial_support mechanism is removed
- The search interface is modified to return a 2-tuple, the first item being the result and the second the total
  number of items satisfying the request
- The EOProduct properties now excludes all metadata that were either not mapped or not available (mapped in the
  provider metadata_mapping but not present in the provider response). This lowers the size of the number of elements
  needed to be transferred as response to http requests for the embedded http server
- Two new cli args are added: --page and --items to precise which page is to be requested on the provider (default 1)
  and how many results to retrieve (default 20)


v0.7.0 (2018-12-04)
===================

- Creates Creodias, Mundi, Onda and Wekeo drivers
- Every provider configuration parameter is now overridable by the user configuration
- Provider configuration is now overridable by environment variables following the pattern:
  EODAG__<PROVIDER>__<CONFIG_PARAMETER> (special prefix + double underscore between configuration keys + configuration
  parameters uppercase with simple underscores preserved). There is no limit to the how fine the override can go
- New authentication plugins (keycloak with openid)


v0.6.3 (2018-09-24)
===================

- Silences rasterio's NotGeoreferencedWarning warning when sentinel2_l1c driver tries to determine the address of a
  requested band on the disk
- Changes the `DEFAULT_PROJ` constant in `eodag.utils` from a `pyproj.Proj` instance to `rasterio.crs.CRS` instance

v0.6.2 (2018-09-24)
===================

- Updates catalog url for airbus-ds provider
- Removes authentication for airbus-ds provider on catalog search

v0.6.1 (2018-09-19)
===================

- Enhance error message for missing credentials
- Enable EOProduct to remember its remote address for subsequent downloads

v0.6.0 (2018-08-09)
===================

- Add support of a new product type: PLD_BUNDLE provided by theia-landsat
- Create a new authentication plugin to perform headless OpenID connect authorisation
  code flow
- Refactor the class name of the core api (from SatImagesAPI to EODataAccessGateway)
- Set peps platform as the default provider
- Set product archive depth for peps provider to 2 (after extracting a product from peps,
  the product is nested one level inside a top level directory where it was extracted)

v0.5.0 (2018-08-02)
===================

- Make progress bar for download optional and customizable
- Fix bugs in FilterOverlap cruncher

v0.4.0 (2018-07-26)
===================

- Enable quicklook retrieval interface for EOProduct

v0.3.0 (2018-07-23)
===================

- Add docs for tutorials
- Configure project for CI/CD on Bitbucket pipelines


v0.2.0 (2018-07-17)
===================

- Prepare project for release as open source and publication on PyPI
- The get_data functionality now returns an xarray.DataArray instead of numpy.ndarray
- Sentinel 2 L1C product type driver for get_data functionality now supports products
  stored on Amazon S3
- Add tutorials


v0.1.0 (2018-06-20)
===================

- Handle different organisation of files in downloaded zip files
- Add HTTPHeaderAuth authentication plugin
- Map product metadata in providers configuration file through xpath and jsonpath
- Add an interface for sorting multiple SearchResult by geographic extent
- Index Dataset drivers (for the get_data functionality) by eodag product types
- Refactor plugin manager
- Enable SearchResult to provide a list-like interface
- Download is now resilient to download plugins failures
- Update EOProduct API
- Create ArlasSearch search plugin
- Some bug fixes


v0.0.1 (2018-06-15)
===================

- Starting to be stable for internal use
- Basic functionality implemented (search, download, crunch, get_data)
