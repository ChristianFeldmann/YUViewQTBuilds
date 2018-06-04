# YUViewQTBuilds
Qt builds that we use to compile YUView in the CI environements

For each of the supported platforms, we keep a different branch. This way, we can perform a shallow clone on each of the specific branches (git clone --depth 1 https://path/to/repo/foo.git -b bar).

The platforms we support are: Linux, Mac, Windows
