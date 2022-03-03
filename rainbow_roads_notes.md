# Go Install

Installing Go from `apt` doesn't work because it's out of date. Install using [manual download](https://go.dev/doc/install).

# Rainbow Roads Install

```bash
go install github.com/NathanBaulch/rainbow-roads@latest
cd ~/go/bin
./rainbow-roads -arg value -arg value /path/to/gpx
```

*Note the lack of trailing slash on gpx path!*
