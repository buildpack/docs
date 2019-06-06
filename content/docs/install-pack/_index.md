+++
title="Installing `pack`"
weight=1
creatordisplayname="Andrew Meyer"
creatoremail="ameyer@pivotal.io"
lastmodifierdisplayname="Andrew Meyer"
lastmodifieremail="ameyer@pivotal.io"
+++

You can install the most recent version of `pack` (version **{{< latest >}}**) as an executable binary on the following operating systems:

* [macOS](#macos)
* [Linux](#linux)
* [Windows](#windows)

`pack` requires Docker to run

<a href="https://store.docker.com/search?type=edition&offering=community" class="download-button button icon-button bg-blue">Install Docker Community Edition</a>

## macOS

To install `pack` on macOS, the easiest way is to use Homebrew:

```bash
$ brew tap buildpack/tap
$ brew install pack
```

To install manually instead, fetch and unpack the tarball:

```bash
$ wget https://github.com/buildpack/pack/releases/download/v{{< latest >}}/pack-v{{< latest >}}-macos.tgz
$ tar xvf pack-v{{< latest >}}-macos.tgz
$ rm pack-v{{< latest >}}-macos.tgz
$ ./pack --help
```

From there, you can copy the executable to a directory like `/usr/local/bin` or add the current directory to your `PATH`.

## Linux

```bash
$ wget https://github.com/buildpack/pack/releases/download/v{{< latest >}}/pack-v{{< latest >}}-linux.tgz
$ tar xvf pack-v{{< latest >}}-linux.tgz
$ rm pack-v{{< latest >}}-linux.tgz
$ ./pack --help
```

From there, you can copy the executable to a directory like `/usr/local/bin` or add the current directory to your `PATH`.

## Windows

You can install the Windows executable for `pack` by downloading the Windows [ZIP file](https://github.com/buildpack/pack/releases/download/v{{< latest >}}/pack-v{{< latest >}}-windows.zip).

