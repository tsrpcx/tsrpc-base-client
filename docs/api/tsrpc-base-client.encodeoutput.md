<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tsrpc-base-client](./tsrpc-base-client.md) &gt; [EncodeOutput](./tsrpc-base-client.encodeoutput.md)

## EncodeOutput type

<b>Signature:</b>

```typescript
export declare type EncodeOutput<T> = {
    isSucc: true;
    output: T;
    errMsg?: undefined;
} | {
    isSucc: false;
    errMsg: string;
    output?: undefined;
};
```