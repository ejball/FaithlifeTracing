# ITraceProvider interface

[`ITraceProvider`](ITraceProvider.md) is implemented by an object that stores the current trace (for the active request, etc.) and can return it.

```csharp
public interface ITraceProvider
```

## Members

| name | description |
| --- | --- |
| [CurrentTrace](ITraceProvider/CurrentTrace.md) { get; } | The current trace. |

## Remarks

An [`ITrace`](ITrace.md) is an [`ITraceProvider`](ITraceProvider.md) that returns itself.

## See Also

* namespace [Faithlife.Tracing](../Faithlife.Tracing.md)
* [ITraceProvider.cs](https://github.com/Faithlife/FaithlifeTracing/tree/master/src/Faithlife.Tracing/Faithlife.Tracing/ITraceProvider.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Tracing.dll -->