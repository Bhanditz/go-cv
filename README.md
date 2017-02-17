# go-cv

Golang wrapper for https://github.com/ermig1979/Simd

## Installation

Install Simd

```
go get github.com/fwessels/go-cv
```

## Examples

Provide several extensive examples demonstrating the use of go-cv.

## Performance comparison

Show a performance comparison to OpenCV for various techniques.

```
benchmark                old ns/op     new ns/op     delta
benchmark                   old ns/op     new ns/op     delta
BenchmarkGaussian-8         3645335       1082332       -70.31%
BenchmarkGaussianRGB-8      10885144      3636472       -66.59%
BenchmarkBlur-8             5814178       1406019       -75.82%
BenchmarkBlurRGB-8          17284782      3479465       -79.87%
BenchmarkMedian3x3-8        2397787       1358023       -43.36%
BenchmarkMedian3x3RGB-8     5232342       4253066       -18.72%
BenchmarkMedian5x5-8        17180590      8482600       -50.63%
BenchmarkMedian5x5RGB-8     42957406      24858284      -42.13%
```
