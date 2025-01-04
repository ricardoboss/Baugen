# Baugen

A C# source generator that generates statically accessible build metadata.

## Usage

Install the package:

```shell
dotnet add package Baugen
```

## Build Metadata

The following properties are available:

- `BuildTimestampTicks`: a `long` representing the build timestamp in ticks
- `BuildTimestamp`: a `DateTimeOffset` representing the build timestamp

## License

[MIT](LICENSE.md)
