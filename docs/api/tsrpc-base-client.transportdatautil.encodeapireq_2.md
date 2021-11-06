<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tsrpc-base-client](./tsrpc-base-client.md) &gt; [TransportDataUtil](./tsrpc-base-client.transportdatautil.md) &gt; [encodeApiReq](./tsrpc-base-client.transportdatautil.encodeapireq_2.md)

## TransportDataUtil.encodeApiReq() method

<b>Signature:</b>

```typescript
static encodeApiReq(tsbuffer: TSBuffer, service: ApiService, req: any, type: 'text' | 'buffer', sn?: number): EncodeOutputBuf | EncodeOutputText;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  tsbuffer | TSBuffer |  |
|  service | [ApiService](./tsrpc-base-client.apiservice.md) |  |
|  req | any |  |
|  type | 'text' \| 'buffer' |  |
|  sn | number |  |

<b>Returns:</b>

[EncodeOutputBuf](./tsrpc-base-client.encodeoutputbuf.md) \| [EncodeOutputText](./tsrpc-base-client.encodeoutputtext.md)
