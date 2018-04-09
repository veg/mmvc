# mmvc

Multinomial mixture variant caller

## Dependencies

- julia v0.3.x
- [ArgParse](https://github.com/carlobaldassi/ArgParse.jl)
- [FastaIO](https://github.com/carlobaldassi/FastaIO.jl)
- [JSON](https://github.com/JuliaIO/JSON.jl)

## Test

```
julia mmvc.jl --chain-length 2000000 --json-report out.json --filter filter.msa testdata.fasta
```
