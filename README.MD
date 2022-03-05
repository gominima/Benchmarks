# Results

```sh
$ go test -bench=.
goos: windows
goarch: amd64
pkg: github.com/gominima/benchmarks/_example
cpu: Intel(R) Core(TM) i5-9300H CPU @ 2.40GHz
BenchmarkMinimaStatic-8            19346             54850 ns/op           23100 B/op        157 allocs/op
BenchmarkMinimaGitHubAPI-8          8593            106954 ns/op           82739 B/op        537 allocs/op
BenchmarkMinimaGplusAPI-8         229596              5702 ns/op            5641 B/op         35 allocs/op
BenchmarkMinimaParseAPI-8         104377             11102 ns/op            8838 B/op         58 allocs/op
PASS
ok      github.com/gominima/benchmarks/_example        8.480s
```
