# Results

```sh
goos: windows
goarch: amd64
pkg: github.com/gominima/benchmarks
cpu: Intel(R) Core(TM) i5-9300H CPU @ 2.40GHz
BenchmarkMinimaStatic-8             7962            151200 ns/op           48230 B/op       1093 allocs/op
BenchmarkMinimaGitHubAPI-8           642           1318892 ns/op          598181 B/op      10389 allocs/op
BenchmarkMinimaGplusAPI-8          49812             28091 ns/op           11967 B/op        201 allocs/op
BenchmarkMinimaParseAPI-8          50712             29137 ns/op           14203 B/op        212 allocs/op
PASS
ok      github.com/gominima/benchmarks  11.668s