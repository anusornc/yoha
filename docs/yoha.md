<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@handtracking.io/yoha](./yoha.md)

## yoha package

Yoha hand tracking library for precision interactions.

## Functions

|  Function | Description |
|  --- | --- |
|  [ApplyPaddingToCoordinates(padding, coords)](./yoha.applypaddingtocoordinates.md) | Starting from the borders, removes a percentage of the analyzed track source. |
|  [CreateMaxFpsMaxResStream()](./yoha.createmaxfpsmaxresstream.md) | Creates a MediaStream with maximum fps and given the max fps the highest available resolution. |
|  [CreateVideoElementFromStream(stream)](./yoha.createvideoelementfromstream.md) | Creates a <code>&lt;video&gt;</code> element for the given stream. |
|  [DownloadYohaModelFiles(boxUrl, lanUrl, progressCb)](./yoha.downloadyohamodelfiles.md) | Downloads a list of TFJS models. |
|  [MirrorCoordinatesHorizontally(coords)](./yoha.mirrorcoordinateshorizontally.md) | Mirrors result coordinates along the y axis i.e. <code>[x, y]</code> becomes <code>[1 - x, y]</code>. |
|  [StartWebGlEngine(config, trackSource, yohaModel, resCb)](./yoha.startwebglengine.md) | Starts an analysis loop on a track source (e.g. a <code>&lt;video&gt;</code> element) using the TFJS WebGl backend. |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [IEngineConfig](./yoha.iengineconfig.md) | Engine configuration. |
|  [IMediaStreamResult](./yoha.imediastreamresult.md) | Result of trying to obtain a MediaStream. |
|  [IPoseProbabilities](./yoha.iposeprobabilities.md) | The detected hand poses. |
|  [IStopEngineCb](./yoha.istopenginecb.md) | A callback that when invoked stops the engine. |
|  [ITfjsModelFiles](./yoha.itfjsmodelfiles.md) | Collection of files belonging to a TFJS model. |
|  [ITrackResult](./yoha.itrackresult.md) | Hand tracking results. |
|  [IYohaModelFiles](./yoha.iyohamodelfiles.md) | The two models required for running the Yoha engine. |

## Variables

|  Variable | Description |
|  --- | --- |
|  [MediaStreamErrorEnum](./yoha.mediastreamerrorenum.md) | Possible error types that can occur when calling navigator.mediaDevices.getUserMedia. |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [IModelDownloadProgressCb](./yoha.imodeldownloadprogresscb.md) | Callback that periodically informs about download progress. |
|  [ITrackResultCb](./yoha.itrackresultcb.md) | Result callback. |
|  [ITrackSource](./yoha.itracksource.md) | The element to be used as source for the handtracking. Usually this is a <code>&lt;video&gt;</code> element. |
|  [ObjValues](./yoha.objvalues.md) | A small helper that is used to build a type consisting of all values of an object literal.<br/> |

