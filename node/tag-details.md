<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `node`

-	[`node:0.10.43`](#node01043)
-	[`node:0.10`](#node010)
-	[`node:0.10.43-onbuild`](#node01043-onbuild)
-	[`node:0.10-onbuild`](#node010-onbuild)
-	[`node:0.10.43-slim`](#node01043-slim)
-	[`node:0.10-slim`](#node010-slim)
-	[`node:0.10.43-wheezy`](#node01043-wheezy)
-	[`node:0.10-wheezy`](#node010-wheezy)
-	[`node:0.12.12`](#node01212)
-	[`node:0.12`](#node012)
-	[`node:0`](#node0)
-	[`node:0.12.12-onbuild`](#node01212-onbuild)
-	[`node:0.12-onbuild`](#node012-onbuild)
-	[`node:0-onbuild`](#node0-onbuild)
-	[`node:0.12.12-slim`](#node01212-slim)
-	[`node:0.12-slim`](#node012-slim)
-	[`node:0-slim`](#node0-slim)
-	[`node:0.12.12-wheezy`](#node01212-wheezy)
-	[`node:0.12-wheezy`](#node012-wheezy)
-	[`node:0-wheezy`](#node0-wheezy)
-	[`node:4.4.0`](#node440)
-	[`node:4.4`](#node44)
-	[`node:4`](#node4)
-	[`node:argon`](#nodeargon)
-	[`node:4.4.0-onbuild`](#node440-onbuild)
-	[`node:4.4-onbuild`](#node44-onbuild)
-	[`node:4-onbuild`](#node4-onbuild)
-	[`node:argon-onbuild`](#nodeargon-onbuild)
-	[`node:4.4.0-slim`](#node440-slim)
-	[`node:4.4-slim`](#node44-slim)
-	[`node:4-slim`](#node4-slim)
-	[`node:argon-slim`](#nodeargon-slim)
-	[`node:4.4.0-wheezy`](#node440-wheezy)
-	[`node:4.4-wheezy`](#node44-wheezy)
-	[`node:4-wheezy`](#node4-wheezy)
-	[`node:argon-wheezy`](#nodeargon-wheezy)
-	[`node:5.9.0`](#node590)
-	[`node:5.9`](#node59)
-	[`node:5`](#node5)
-	[`node:latest`](#nodelatest)
-	[`node:5.9.0-onbuild`](#node590-onbuild)
-	[`node:5.9-onbuild`](#node59-onbuild)
-	[`node:5-onbuild`](#node5-onbuild)
-	[`node:onbuild`](#nodeonbuild)
-	[`node:5.9.0-slim`](#node590-slim)
-	[`node:5.9-slim`](#node59-slim)
-	[`node:5-slim`](#node5-slim)
-	[`node:slim`](#nodeslim)
-	[`node:5.9.0-wheezy`](#node590-wheezy)
-	[`node:5.9-wheezy`](#node59-wheezy)
-	[`node:5-wheezy`](#node5-wheezy)
-	[`node:wheezy`](#nodewheezy)

## `node:0.10.43`

```console
$ docker pull library/node@sha256:f4da40e9cbdb12ab417b7ebe3b8184d14c37d21d292dbe2f2372ca3b1ab19658
```

-	Total Virtual Size: 633.8 MB (633771514 bytes)
-	Total v2 Content-Length: 251.2 MB (251171755 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `6b1971eeab056993acd385e7faba8dbdcbc44759ee9e87d46b791a93c92c866e`

```dockerfile
ENV NODE_VERSION=0.10.43
```

-	Created: Fri, 04 Mar 2016 05:10:46 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `4a4e11d3921a488d39b46881d4e166886cadeb35a7c88f440f511377bfe433a1`

```dockerfile
ENV NPM_VERSION=2.14.1
```

-	Created: Fri, 04 Mar 2016 05:10:47 GMT
-	Parent Layer: `6b1971eeab056993acd385e7faba8dbdcbc44759ee9e87d46b791a93c92c866e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `7f757b79d67173165d993078c63b91e6817b1514eeb30f1fc0bb44b4a7d85309`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& npm install -g npm@"$NPM_VERSION" \
	&& npm cache clear
```

-	Created: Fri, 04 Mar 2016 05:10:56 GMT
-	Parent Layer: `4a4e11d3921a488d39b46881d4e166886cadeb35a7c88f440f511377bfe433a1`
-	Docker Version: 1.9.1
-	Virtual Size: 27.0 MB (27008399 bytes)
-	v2 Blob: `sha256:00f99891854edfdb68df77834ec2083b68f095b07cdf3de2370f79a12ec170ed`
-	v2 Content-Length: 10.1 MB (10145791 bytes)

#### `6316804d448d2580e08619ec43b14d4bba39c2c4878cfe6b9c850f7e6d701110`

```dockerfile
CMD ["node"]
```

-	Created: Fri, 04 Mar 2016 05:10:58 GMT
-	Parent Layer: `7f757b79d67173165d993078c63b91e6817b1514eeb30f1fc0bb44b4a7d85309`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.10`

```console
$ docker pull library/node@sha256:e2f4c8804db8d366b6846533d4321329e76962b8ded8fbe658fa5b17f2812e44
```

-	Total Virtual Size: 633.8 MB (633771514 bytes)
-	Total v2 Content-Length: 251.2 MB (251171755 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `6b1971eeab056993acd385e7faba8dbdcbc44759ee9e87d46b791a93c92c866e`

```dockerfile
ENV NODE_VERSION=0.10.43
```

-	Created: Fri, 04 Mar 2016 05:10:46 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `4a4e11d3921a488d39b46881d4e166886cadeb35a7c88f440f511377bfe433a1`

```dockerfile
ENV NPM_VERSION=2.14.1
```

-	Created: Fri, 04 Mar 2016 05:10:47 GMT
-	Parent Layer: `6b1971eeab056993acd385e7faba8dbdcbc44759ee9e87d46b791a93c92c866e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `7f757b79d67173165d993078c63b91e6817b1514eeb30f1fc0bb44b4a7d85309`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& npm install -g npm@"$NPM_VERSION" \
	&& npm cache clear
```

-	Created: Fri, 04 Mar 2016 05:10:56 GMT
-	Parent Layer: `4a4e11d3921a488d39b46881d4e166886cadeb35a7c88f440f511377bfe433a1`
-	Docker Version: 1.9.1
-	Virtual Size: 27.0 MB (27008399 bytes)
-	v2 Blob: `sha256:00f99891854edfdb68df77834ec2083b68f095b07cdf3de2370f79a12ec170ed`
-	v2 Content-Length: 10.1 MB (10145791 bytes)

#### `6316804d448d2580e08619ec43b14d4bba39c2c4878cfe6b9c850f7e6d701110`

```dockerfile
CMD ["node"]
```

-	Created: Fri, 04 Mar 2016 05:10:58 GMT
-	Parent Layer: `7f757b79d67173165d993078c63b91e6817b1514eeb30f1fc0bb44b4a7d85309`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.10.43-onbuild`

```console
$ docker pull library/node@sha256:e00322a9eeef6bf08baf7149314d59cdfc0b13566dc4eb57cb168aeca1850930
```

-	Total Virtual Size: 633.8 MB (633771514 bytes)
-	Total v2 Content-Length: 251.2 MB (251172041 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `6b1971eeab056993acd385e7faba8dbdcbc44759ee9e87d46b791a93c92c866e`

```dockerfile
ENV NODE_VERSION=0.10.43
```

-	Created: Fri, 04 Mar 2016 05:10:46 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `4a4e11d3921a488d39b46881d4e166886cadeb35a7c88f440f511377bfe433a1`

```dockerfile
ENV NPM_VERSION=2.14.1
```

-	Created: Fri, 04 Mar 2016 05:10:47 GMT
-	Parent Layer: `6b1971eeab056993acd385e7faba8dbdcbc44759ee9e87d46b791a93c92c866e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `7f757b79d67173165d993078c63b91e6817b1514eeb30f1fc0bb44b4a7d85309`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& npm install -g npm@"$NPM_VERSION" \
	&& npm cache clear
```

-	Created: Fri, 04 Mar 2016 05:10:56 GMT
-	Parent Layer: `4a4e11d3921a488d39b46881d4e166886cadeb35a7c88f440f511377bfe433a1`
-	Docker Version: 1.9.1
-	Virtual Size: 27.0 MB (27008399 bytes)
-	v2 Blob: `sha256:00f99891854edfdb68df77834ec2083b68f095b07cdf3de2370f79a12ec170ed`
-	v2 Content-Length: 10.1 MB (10145791 bytes)

#### `6316804d448d2580e08619ec43b14d4bba39c2c4878cfe6b9c850f7e6d701110`

```dockerfile
CMD ["node"]
```

-	Created: Fri, 04 Mar 2016 05:10:58 GMT
-	Parent Layer: `7f757b79d67173165d993078c63b91e6817b1514eeb30f1fc0bb44b4a7d85309`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `8b58fe1f10ebca75b2d5d82ab9e9f8933ef1cc1ce8b9200f0a6bcaf4cc5b35f4`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Fri, 04 Mar 2016 05:11:13 GMT
-	Parent Layer: `6316804d448d2580e08619ec43b14d4bba39c2c4878cfe6b9c850f7e6d701110`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:219826cae60bcdb6942eef6ac283a281b6d77bff683749c52961976c8c69cbed`
-	v2 Content-Length: 126.0 B

#### `dfee09cf6c48834e6d04f140c34d71dee41ddaa06509c471bc7c08bfe42411d5`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Fri, 04 Mar 2016 05:11:13 GMT
-	Parent Layer: `8b58fe1f10ebca75b2d5d82ab9e9f8933ef1cc1ce8b9200f0a6bcaf4cc5b35f4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `5746ff2b1c7cc4eca870d1a2a0ffb3437094847a081694e5bb9d133267398fa8`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Fri, 04 Mar 2016 05:11:14 GMT
-	Parent Layer: `dfee09cf6c48834e6d04f140c34d71dee41ddaa06509c471bc7c08bfe42411d5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `debc68600e1cda1bee92969b40a1f6f5ed26a254fdf0b6f627e4438b8346cb01`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Fri, 04 Mar 2016 05:11:15 GMT
-	Parent Layer: `5746ff2b1c7cc4eca870d1a2a0ffb3437094847a081694e5bb9d133267398fa8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9a9fe7898bb86b47c022cef084cd3822dbad0689178fd6bb7ab4470244687e09`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Fri, 04 Mar 2016 05:11:15 GMT
-	Parent Layer: `debc68600e1cda1bee92969b40a1f6f5ed26a254fdf0b6f627e4438b8346cb01`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `c6cd5903edb0b1b2c5fc22aed093b40b158b7fc8aa482891e02704394423ddd1`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Fri, 04 Mar 2016 05:11:16 GMT
-	Parent Layer: `9a9fe7898bb86b47c022cef084cd3822dbad0689178fd6bb7ab4470244687e09`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.10-onbuild`

```console
$ docker pull library/node@sha256:533bfd7be4140bfbf401f1d9a3f16583df4a8e7ad6c2a290e797b14b839fa7dd
```

-	Total Virtual Size: 633.8 MB (633771514 bytes)
-	Total v2 Content-Length: 251.2 MB (251172041 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `6b1971eeab056993acd385e7faba8dbdcbc44759ee9e87d46b791a93c92c866e`

```dockerfile
ENV NODE_VERSION=0.10.43
```

-	Created: Fri, 04 Mar 2016 05:10:46 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `4a4e11d3921a488d39b46881d4e166886cadeb35a7c88f440f511377bfe433a1`

```dockerfile
ENV NPM_VERSION=2.14.1
```

-	Created: Fri, 04 Mar 2016 05:10:47 GMT
-	Parent Layer: `6b1971eeab056993acd385e7faba8dbdcbc44759ee9e87d46b791a93c92c866e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `7f757b79d67173165d993078c63b91e6817b1514eeb30f1fc0bb44b4a7d85309`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& npm install -g npm@"$NPM_VERSION" \
	&& npm cache clear
```

-	Created: Fri, 04 Mar 2016 05:10:56 GMT
-	Parent Layer: `4a4e11d3921a488d39b46881d4e166886cadeb35a7c88f440f511377bfe433a1`
-	Docker Version: 1.9.1
-	Virtual Size: 27.0 MB (27008399 bytes)
-	v2 Blob: `sha256:00f99891854edfdb68df77834ec2083b68f095b07cdf3de2370f79a12ec170ed`
-	v2 Content-Length: 10.1 MB (10145791 bytes)

#### `6316804d448d2580e08619ec43b14d4bba39c2c4878cfe6b9c850f7e6d701110`

```dockerfile
CMD ["node"]
```

-	Created: Fri, 04 Mar 2016 05:10:58 GMT
-	Parent Layer: `7f757b79d67173165d993078c63b91e6817b1514eeb30f1fc0bb44b4a7d85309`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `8b58fe1f10ebca75b2d5d82ab9e9f8933ef1cc1ce8b9200f0a6bcaf4cc5b35f4`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Fri, 04 Mar 2016 05:11:13 GMT
-	Parent Layer: `6316804d448d2580e08619ec43b14d4bba39c2c4878cfe6b9c850f7e6d701110`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:219826cae60bcdb6942eef6ac283a281b6d77bff683749c52961976c8c69cbed`
-	v2 Content-Length: 126.0 B

#### `dfee09cf6c48834e6d04f140c34d71dee41ddaa06509c471bc7c08bfe42411d5`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Fri, 04 Mar 2016 05:11:13 GMT
-	Parent Layer: `8b58fe1f10ebca75b2d5d82ab9e9f8933ef1cc1ce8b9200f0a6bcaf4cc5b35f4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `5746ff2b1c7cc4eca870d1a2a0ffb3437094847a081694e5bb9d133267398fa8`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Fri, 04 Mar 2016 05:11:14 GMT
-	Parent Layer: `dfee09cf6c48834e6d04f140c34d71dee41ddaa06509c471bc7c08bfe42411d5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `debc68600e1cda1bee92969b40a1f6f5ed26a254fdf0b6f627e4438b8346cb01`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Fri, 04 Mar 2016 05:11:15 GMT
-	Parent Layer: `5746ff2b1c7cc4eca870d1a2a0ffb3437094847a081694e5bb9d133267398fa8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9a9fe7898bb86b47c022cef084cd3822dbad0689178fd6bb7ab4470244687e09`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Fri, 04 Mar 2016 05:11:15 GMT
-	Parent Layer: `debc68600e1cda1bee92969b40a1f6f5ed26a254fdf0b6f627e4438b8346cb01`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `c6cd5903edb0b1b2c5fc22aed093b40b158b7fc8aa482891e02704394423ddd1`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Fri, 04 Mar 2016 05:11:16 GMT
-	Parent Layer: `9a9fe7898bb86b47c022cef084cd3822dbad0689178fd6bb7ab4470244687e09`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.10.43-slim`

```console
$ docker pull library/node@sha256:e8f49f74dcc6f13ac29715e052ed593b3a58d13c1f14165666b0b4bc942f4cc6
```

-	Total Virtual Size: 157.9 MB (157876209 bytes)
-	Total v2 Content-Length: 64.0 MB (64018661 bytes)

### Layers (7)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:01:10 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:44dc6f2cf8e8e7ca81adf3ed6ab4c0eec204c4b4bfa35012c0d3a0af0f2a78b9`
-	v2 Content-Length: 26.9 KB (26933 bytes)

#### `2a1bfbf05e82e32cbcd8b38ee3e7f9009cb6ed0b02436dbbc9270139a3318ebd`

```dockerfile
ENV NODE_VERSION=0.10.43
```

-	Created: Fri, 04 Mar 2016 05:11:38 GMT
-	Parent Layer: `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `37e72cfd29dfee35dcedd18e938f77c4431259d3911eb97dd0c3201a6ad084af`

```dockerfile
ENV NPM_VERSION=2.14.1
```

-	Created: Fri, 04 Mar 2016 05:11:38 GMT
-	Parent Layer: `2a1bfbf05e82e32cbcd8b38ee3e7f9009cb6ed0b02436dbbc9270139a3318ebd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b88b12b140c7687ef3609c4464fe19566c6d2e419d2eb9dfbea9faaece5733ff`

```dockerfile
RUN buildDeps='curl ca-certificates xz-utils' \
	&& set -x \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends \
	&& rm -rf /var/lib/apt/lists/* \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& npm install -g npm@"$NPM_VERSION" \
	&& npm cache clear
```

-	Created: Fri, 04 Mar 2016 05:13:02 GMT
-	Parent Layer: `37e72cfd29dfee35dcedd18e938f77c4431259d3911eb97dd0c3201a6ad084af`
-	Docker Version: 1.9.1
-	Virtual Size: 32.7 MB (32713653 bytes)
-	v2 Blob: `sha256:339db5bde8bb4c553e5ea75600b9c673b19661ce89f2c1dae76aeb31d200e64a`
-	v2 Content-Length: 12.6 MB (12623885 bytes)

#### `5a97a31b1d69478b2fd6738acef0b417a6a4863697c68a94c8069dc7258746ce`

```dockerfile
CMD ["node"]
```

-	Created: Fri, 04 Mar 2016 05:13:04 GMT
-	Parent Layer: `b88b12b140c7687ef3609c4464fe19566c6d2e419d2eb9dfbea9faaece5733ff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.10-slim`

```console
$ docker pull library/node@sha256:f2686cf876f1fe94002b1706ae82a5a2b275673b84e0076b0da1159967a75d65
```

-	Total Virtual Size: 157.9 MB (157876209 bytes)
-	Total v2 Content-Length: 64.0 MB (64018661 bytes)

### Layers (7)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:01:10 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:44dc6f2cf8e8e7ca81adf3ed6ab4c0eec204c4b4bfa35012c0d3a0af0f2a78b9`
-	v2 Content-Length: 26.9 KB (26933 bytes)

#### `2a1bfbf05e82e32cbcd8b38ee3e7f9009cb6ed0b02436dbbc9270139a3318ebd`

```dockerfile
ENV NODE_VERSION=0.10.43
```

-	Created: Fri, 04 Mar 2016 05:11:38 GMT
-	Parent Layer: `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `37e72cfd29dfee35dcedd18e938f77c4431259d3911eb97dd0c3201a6ad084af`

```dockerfile
ENV NPM_VERSION=2.14.1
```

-	Created: Fri, 04 Mar 2016 05:11:38 GMT
-	Parent Layer: `2a1bfbf05e82e32cbcd8b38ee3e7f9009cb6ed0b02436dbbc9270139a3318ebd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b88b12b140c7687ef3609c4464fe19566c6d2e419d2eb9dfbea9faaece5733ff`

```dockerfile
RUN buildDeps='curl ca-certificates xz-utils' \
	&& set -x \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends \
	&& rm -rf /var/lib/apt/lists/* \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& npm install -g npm@"$NPM_VERSION" \
	&& npm cache clear
```

-	Created: Fri, 04 Mar 2016 05:13:02 GMT
-	Parent Layer: `37e72cfd29dfee35dcedd18e938f77c4431259d3911eb97dd0c3201a6ad084af`
-	Docker Version: 1.9.1
-	Virtual Size: 32.7 MB (32713653 bytes)
-	v2 Blob: `sha256:339db5bde8bb4c553e5ea75600b9c673b19661ce89f2c1dae76aeb31d200e64a`
-	v2 Content-Length: 12.6 MB (12623885 bytes)

#### `5a97a31b1d69478b2fd6738acef0b417a6a4863697c68a94c8069dc7258746ce`

```dockerfile
CMD ["node"]
```

-	Created: Fri, 04 Mar 2016 05:13:04 GMT
-	Parent Layer: `b88b12b140c7687ef3609c4464fe19566c6d2e419d2eb9dfbea9faaece5733ff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.10.43-wheezy`

```console
$ docker pull library/node@sha256:0cf828308370ec9e0ea185265bcbfd132148edad9bcbb5f233a575bfa8ed1edd
```

-	Total Virtual Size: 486.8 MB (486774891 bytes)
-	Total v2 Content-Length: 185.8 MB (185765497 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `05e0eb8f2b9cdc0020909ee2059551c75ed9c5af45129da0d0c0408d1fddeacf`

```dockerfile
ENV NODE_VERSION=0.10.43
```

-	Created: Fri, 04 Mar 2016 05:13:24 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2338f3eb9b1ac6c47f490c1b4cb30e6a4663d194b8b865eb4acc3a4304062b7c`

```dockerfile
ENV NPM_VERSION=2.14.1
```

-	Created: Fri, 04 Mar 2016 05:13:24 GMT
-	Parent Layer: `05e0eb8f2b9cdc0020909ee2059551c75ed9c5af45129da0d0c0408d1fddeacf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `a9a95e855052e904e86357b71aca627aeebfbc566e71e457e256c5c16caf5ecd`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& npm install -g npm@"$NPM_VERSION" \
	&& npm cache clear
```

-	Created: Fri, 04 Mar 2016 05:13:57 GMT
-	Parent Layer: `2338f3eb9b1ac6c47f490c1b4cb30e6a4663d194b8b865eb4acc3a4304062b7c`
-	Docker Version: 1.9.1
-	Virtual Size: 27.0 MB (27008399 bytes)
-	v2 Blob: `sha256:787214e9d895520c822bc6b186e87bf097701ba6153666b95fb6ff17e0523bcf`
-	v2 Content-Length: 10.1 MB (10145838 bytes)

#### `ae8939027ae7f2fed6460dda92ff135ecd033395465020fce1067afb9b85b951`

```dockerfile
CMD ["node"]
```

-	Created: Fri, 04 Mar 2016 05:13:59 GMT
-	Parent Layer: `a9a95e855052e904e86357b71aca627aeebfbc566e71e457e256c5c16caf5ecd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.10-wheezy`

```console
$ docker pull library/node@sha256:2b1a2d2196a764751b18ca794437dffc3e4286b476ccdb906ac7dd1a6a7ffcd1
```

-	Total Virtual Size: 486.8 MB (486774891 bytes)
-	Total v2 Content-Length: 185.8 MB (185765497 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `05e0eb8f2b9cdc0020909ee2059551c75ed9c5af45129da0d0c0408d1fddeacf`

```dockerfile
ENV NODE_VERSION=0.10.43
```

-	Created: Fri, 04 Mar 2016 05:13:24 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2338f3eb9b1ac6c47f490c1b4cb30e6a4663d194b8b865eb4acc3a4304062b7c`

```dockerfile
ENV NPM_VERSION=2.14.1
```

-	Created: Fri, 04 Mar 2016 05:13:24 GMT
-	Parent Layer: `05e0eb8f2b9cdc0020909ee2059551c75ed9c5af45129da0d0c0408d1fddeacf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `a9a95e855052e904e86357b71aca627aeebfbc566e71e457e256c5c16caf5ecd`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& npm install -g npm@"$NPM_VERSION" \
	&& npm cache clear
```

-	Created: Fri, 04 Mar 2016 05:13:57 GMT
-	Parent Layer: `2338f3eb9b1ac6c47f490c1b4cb30e6a4663d194b8b865eb4acc3a4304062b7c`
-	Docker Version: 1.9.1
-	Virtual Size: 27.0 MB (27008399 bytes)
-	v2 Blob: `sha256:787214e9d895520c822bc6b186e87bf097701ba6153666b95fb6ff17e0523bcf`
-	v2 Content-Length: 10.1 MB (10145838 bytes)

#### `ae8939027ae7f2fed6460dda92ff135ecd033395465020fce1067afb9b85b951`

```dockerfile
CMD ["node"]
```

-	Created: Fri, 04 Mar 2016 05:13:59 GMT
-	Parent Layer: `a9a95e855052e904e86357b71aca627aeebfbc566e71e457e256c5c16caf5ecd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.12.12`

```console
$ docker pull library/node@sha256:0925118d3d8ed5c4fff9d11e425bdbfcef725ff23d24ef3998c2ad9748470bdc
```

-	Total Virtual Size: 637.1 MB (637136604 bytes)
-	Total v2 Content-Length: 250.8 MB (250819668 bytes)

### Layers (9)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:24:29 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:24:34 GMT
-	Parent Layer: `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:823b37f4d4689f99dc849ad12320cf9718a36d7abcb133784bd00dd9dd43a76a`
-	v2 Content-Length: 9.8 MB (9793736 bytes)

#### `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:24:36 GMT
-	Parent Layer: `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.12`

```console
$ docker pull library/node@sha256:d83254c71fea63ddab39a77be7c56e428eee010b28ee1fc3fe775ed6e1f9ed9b
```

-	Total Virtual Size: 637.1 MB (637136604 bytes)
-	Total v2 Content-Length: 250.8 MB (250819668 bytes)

### Layers (9)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:24:29 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:24:34 GMT
-	Parent Layer: `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:823b37f4d4689f99dc849ad12320cf9718a36d7abcb133784bd00dd9dd43a76a`
-	v2 Content-Length: 9.8 MB (9793736 bytes)

#### `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:24:36 GMT
-	Parent Layer: `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0`

```console
$ docker pull library/node@sha256:6023a2e124b7bfd22d42942dbc5de2208663a53032a6c6444a499f5a33bc9e9f
```

-	Total Virtual Size: 637.1 MB (637136604 bytes)
-	Total v2 Content-Length: 250.8 MB (250819668 bytes)

### Layers (9)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:24:29 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:24:34 GMT
-	Parent Layer: `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:823b37f4d4689f99dc849ad12320cf9718a36d7abcb133784bd00dd9dd43a76a`
-	v2 Content-Length: 9.8 MB (9793736 bytes)

#### `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:24:36 GMT
-	Parent Layer: `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.12.12-onbuild`

```console
$ docker pull library/node@sha256:1eb6030983f893ed48a5f4482676c0dd76acbf0fac36fea2c9fa42df30baacde
```

-	Total Virtual Size: 637.1 MB (637136604 bytes)
-	Total v2 Content-Length: 250.8 MB (250819955 bytes)

### Layers (15)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:24:29 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:24:34 GMT
-	Parent Layer: `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:823b37f4d4689f99dc849ad12320cf9718a36d7abcb133784bd00dd9dd43a76a`
-	v2 Content-Length: 9.8 MB (9793736 bytes)

#### `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:24:36 GMT
-	Parent Layer: `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `4825ddba530b6a875e8102480833f3cbda03518f60dadb6cabe794c130c61fff`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:24:59 GMT
-	Parent Layer: `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f0563e6728180f55781fb4d9a5f8da4efa616661f2e12b4bb514db45662b7582`
-	v2 Content-Length: 127.0 B

#### `edaeb268222df5b8f1b66cfb70e7300f0cdbeba5e39c397a7a3adf2988325c7a`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:25:00 GMT
-	Parent Layer: `4825ddba530b6a875e8102480833f3cbda03518f60dadb6cabe794c130c61fff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `52d2bdee262dd3676cbc2025441da3c42aaae23e6ba1b5b5c61ec0145ef59f7a`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Wed, 09 Mar 2016 18:25:01 GMT
-	Parent Layer: `edaeb268222df5b8f1b66cfb70e7300f0cdbeba5e39c397a7a3adf2988325c7a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3820b37cc0f8b6dc989b71aabffe5f99d79e3b143296d144ce3f4214b6c0ab67`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Wed, 09 Mar 2016 18:25:01 GMT
-	Parent Layer: `52d2bdee262dd3676cbc2025441da3c42aaae23e6ba1b5b5c61ec0145ef59f7a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `160b664b4e7fd373d5e9cb5894ee04f1e25b712063286561a84fb24366349f29`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:25:02 GMT
-	Parent Layer: `3820b37cc0f8b6dc989b71aabffe5f99d79e3b143296d144ce3f4214b6c0ab67`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `98b184e185dc80195b8e44b091684e4b5e6893ec9fdc4814dbd86835c1d56ef5`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Wed, 09 Mar 2016 18:25:03 GMT
-	Parent Layer: `160b664b4e7fd373d5e9cb5894ee04f1e25b712063286561a84fb24366349f29`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.12-onbuild`

```console
$ docker pull library/node@sha256:1d3b32196070f3aed42bc093f5b9aec2c4bcb68c8a56ffd79c238353e3a34581
```

-	Total Virtual Size: 637.1 MB (637136604 bytes)
-	Total v2 Content-Length: 250.8 MB (250819955 bytes)

### Layers (15)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:24:29 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:24:34 GMT
-	Parent Layer: `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:823b37f4d4689f99dc849ad12320cf9718a36d7abcb133784bd00dd9dd43a76a`
-	v2 Content-Length: 9.8 MB (9793736 bytes)

#### `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:24:36 GMT
-	Parent Layer: `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `4825ddba530b6a875e8102480833f3cbda03518f60dadb6cabe794c130c61fff`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:24:59 GMT
-	Parent Layer: `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f0563e6728180f55781fb4d9a5f8da4efa616661f2e12b4bb514db45662b7582`
-	v2 Content-Length: 127.0 B

#### `edaeb268222df5b8f1b66cfb70e7300f0cdbeba5e39c397a7a3adf2988325c7a`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:25:00 GMT
-	Parent Layer: `4825ddba530b6a875e8102480833f3cbda03518f60dadb6cabe794c130c61fff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `52d2bdee262dd3676cbc2025441da3c42aaae23e6ba1b5b5c61ec0145ef59f7a`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Wed, 09 Mar 2016 18:25:01 GMT
-	Parent Layer: `edaeb268222df5b8f1b66cfb70e7300f0cdbeba5e39c397a7a3adf2988325c7a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3820b37cc0f8b6dc989b71aabffe5f99d79e3b143296d144ce3f4214b6c0ab67`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Wed, 09 Mar 2016 18:25:01 GMT
-	Parent Layer: `52d2bdee262dd3676cbc2025441da3c42aaae23e6ba1b5b5c61ec0145ef59f7a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `160b664b4e7fd373d5e9cb5894ee04f1e25b712063286561a84fb24366349f29`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:25:02 GMT
-	Parent Layer: `3820b37cc0f8b6dc989b71aabffe5f99d79e3b143296d144ce3f4214b6c0ab67`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `98b184e185dc80195b8e44b091684e4b5e6893ec9fdc4814dbd86835c1d56ef5`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Wed, 09 Mar 2016 18:25:03 GMT
-	Parent Layer: `160b664b4e7fd373d5e9cb5894ee04f1e25b712063286561a84fb24366349f29`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0-onbuild`

```console
$ docker pull library/node@sha256:fe8a13efe3c402f612d61a179a631ccbeb25b39452ddb3676ed27fee4d7030d8
```

-	Total Virtual Size: 637.1 MB (637136604 bytes)
-	Total v2 Content-Length: 250.8 MB (250819955 bytes)

### Layers (15)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:24:29 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:24:34 GMT
-	Parent Layer: `46c43f84243e5af84ba0f6cf73ac8b1d5bdf2f2856948c88225d938baa7a908f`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:823b37f4d4689f99dc849ad12320cf9718a36d7abcb133784bd00dd9dd43a76a`
-	v2 Content-Length: 9.8 MB (9793736 bytes)

#### `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:24:36 GMT
-	Parent Layer: `e676c568f1e32e2c46a7fe43a26c66be6712e919b8c9cb8d58bb3373466f4558`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `4825ddba530b6a875e8102480833f3cbda03518f60dadb6cabe794c130c61fff`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:24:59 GMT
-	Parent Layer: `d5eaa5b075296fd857de22d8fbafd7ef8db62fbc051aba4713e52846aa76de2e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:f0563e6728180f55781fb4d9a5f8da4efa616661f2e12b4bb514db45662b7582`
-	v2 Content-Length: 127.0 B

#### `edaeb268222df5b8f1b66cfb70e7300f0cdbeba5e39c397a7a3adf2988325c7a`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:25:00 GMT
-	Parent Layer: `4825ddba530b6a875e8102480833f3cbda03518f60dadb6cabe794c130c61fff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `52d2bdee262dd3676cbc2025441da3c42aaae23e6ba1b5b5c61ec0145ef59f7a`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Wed, 09 Mar 2016 18:25:01 GMT
-	Parent Layer: `edaeb268222df5b8f1b66cfb70e7300f0cdbeba5e39c397a7a3adf2988325c7a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3820b37cc0f8b6dc989b71aabffe5f99d79e3b143296d144ce3f4214b6c0ab67`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Wed, 09 Mar 2016 18:25:01 GMT
-	Parent Layer: `52d2bdee262dd3676cbc2025441da3c42aaae23e6ba1b5b5c61ec0145ef59f7a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `160b664b4e7fd373d5e9cb5894ee04f1e25b712063286561a84fb24366349f29`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:25:02 GMT
-	Parent Layer: `3820b37cc0f8b6dc989b71aabffe5f99d79e3b143296d144ce3f4214b6c0ab67`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `98b184e185dc80195b8e44b091684e4b5e6893ec9fdc4814dbd86835c1d56ef5`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Wed, 09 Mar 2016 18:25:03 GMT
-	Parent Layer: `160b664b4e7fd373d5e9cb5894ee04f1e25b712063286561a84fb24366349f29`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.12.12-slim`

```console
$ docker pull library/node@sha256:3a2cf5fee631b7c6a55595337c210d6d59a04af964c69e5a2dcf8ecd21c6771b
```

-	Total Virtual Size: 161.2 MB (161241299 bytes)
-	Total v2 Content-Length: 63.7 MB (63659091 bytes)

### Layers (6)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:01:10 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:44dc6f2cf8e8e7ca81adf3ed6ab4c0eec204c4b4bfa35012c0d3a0af0f2a78b9`
-	v2 Content-Length: 26.9 KB (26933 bytes)

#### `4f8e7718ea84d082b61f425ba2dfe47bc21cf93e59c47d5d9bb94f75b2510db5`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:25:40 GMT
-	Parent Layer: `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `708a1706ed826a7215c5a0bf1cd7e5fc0784aa4dac59387c82cb92788cc78c90`

```dockerfile
RUN buildDeps='curl ca-certificates xz-utils' \
	&& set -x \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends \
	&& rm -rf /var/lib/apt/lists/* \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& apt-get purge -y --auto-remove $buildDeps
```

-	Created: Wed, 09 Mar 2016 18:26:41 GMT
-	Parent Layer: `4f8e7718ea84d082b61f425ba2dfe47bc21cf93e59c47d5d9bb94f75b2510db5`
-	Docker Version: 1.9.1
-	Virtual Size: 36.1 MB (36078743 bytes)
-	v2 Blob: `sha256:992dbaa1666745fd8fdc075f7f4fd5a316831d76d2e476b880d99e53a483c97f`
-	v2 Content-Length: 12.3 MB (12264347 bytes)

#### `8a598342646f38124aa77b6ea52d27b7f31a0a68f400ac2649d77e577fd99972`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:26:42 GMT
-	Parent Layer: `708a1706ed826a7215c5a0bf1cd7e5fc0784aa4dac59387c82cb92788cc78c90`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.12-slim`

```console
$ docker pull library/node@sha256:14729d9109cbe34997f2decb1e9c9c939c5dbb6245a4cb2a6e877563755bc671
```

-	Total Virtual Size: 161.2 MB (161241299 bytes)
-	Total v2 Content-Length: 63.7 MB (63659091 bytes)

### Layers (6)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:01:10 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:44dc6f2cf8e8e7ca81adf3ed6ab4c0eec204c4b4bfa35012c0d3a0af0f2a78b9`
-	v2 Content-Length: 26.9 KB (26933 bytes)

#### `4f8e7718ea84d082b61f425ba2dfe47bc21cf93e59c47d5d9bb94f75b2510db5`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:25:40 GMT
-	Parent Layer: `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `708a1706ed826a7215c5a0bf1cd7e5fc0784aa4dac59387c82cb92788cc78c90`

```dockerfile
RUN buildDeps='curl ca-certificates xz-utils' \
	&& set -x \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends \
	&& rm -rf /var/lib/apt/lists/* \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& apt-get purge -y --auto-remove $buildDeps
```

-	Created: Wed, 09 Mar 2016 18:26:41 GMT
-	Parent Layer: `4f8e7718ea84d082b61f425ba2dfe47bc21cf93e59c47d5d9bb94f75b2510db5`
-	Docker Version: 1.9.1
-	Virtual Size: 36.1 MB (36078743 bytes)
-	v2 Blob: `sha256:992dbaa1666745fd8fdc075f7f4fd5a316831d76d2e476b880d99e53a483c97f`
-	v2 Content-Length: 12.3 MB (12264347 bytes)

#### `8a598342646f38124aa77b6ea52d27b7f31a0a68f400ac2649d77e577fd99972`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:26:42 GMT
-	Parent Layer: `708a1706ed826a7215c5a0bf1cd7e5fc0784aa4dac59387c82cb92788cc78c90`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0-slim`

```console
$ docker pull library/node@sha256:05319de2767357cd0d9a727ed979e0a4e25502ec85cc4f7f8544e2b0909f076e
```

-	Total Virtual Size: 161.2 MB (161241299 bytes)
-	Total v2 Content-Length: 63.7 MB (63659091 bytes)

### Layers (6)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:01:10 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:44dc6f2cf8e8e7ca81adf3ed6ab4c0eec204c4b4bfa35012c0d3a0af0f2a78b9`
-	v2 Content-Length: 26.9 KB (26933 bytes)

#### `4f8e7718ea84d082b61f425ba2dfe47bc21cf93e59c47d5d9bb94f75b2510db5`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:25:40 GMT
-	Parent Layer: `9a9fb96d30501dbf68907efc653635cd8e068b66fde1678cd6d06f6522b2e01b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `708a1706ed826a7215c5a0bf1cd7e5fc0784aa4dac59387c82cb92788cc78c90`

```dockerfile
RUN buildDeps='curl ca-certificates xz-utils' \
	&& set -x \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends \
	&& rm -rf /var/lib/apt/lists/* \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt \
	&& apt-get purge -y --auto-remove $buildDeps
```

-	Created: Wed, 09 Mar 2016 18:26:41 GMT
-	Parent Layer: `4f8e7718ea84d082b61f425ba2dfe47bc21cf93e59c47d5d9bb94f75b2510db5`
-	Docker Version: 1.9.1
-	Virtual Size: 36.1 MB (36078743 bytes)
-	v2 Blob: `sha256:992dbaa1666745fd8fdc075f7f4fd5a316831d76d2e476b880d99e53a483c97f`
-	v2 Content-Length: 12.3 MB (12264347 bytes)

#### `8a598342646f38124aa77b6ea52d27b7f31a0a68f400ac2649d77e577fd99972`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:26:42 GMT
-	Parent Layer: `708a1706ed826a7215c5a0bf1cd7e5fc0784aa4dac59387c82cb92788cc78c90`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.12.12-wheezy`

```console
$ docker pull library/node@sha256:400788a36db7375db8f5ec52b4d2eea3fb467c3b598425e18c6ae168820fe258
```

-	Total Virtual Size: 490.1 MB (490139981 bytes)
-	Total v2 Content-Length: 185.4 MB (185413344 bytes)

### Layers (9)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `37614c9ef04ad9faa0e0449594897e185c6616d2fb91bcc5bca5a2f05b4d21db`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:27:10 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1ee1d539928a4a2b31838f6e3f9cf700307ce4c2c17270aa0b4072be22d2fe2c`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:14 GMT
-	Parent Layer: `37614c9ef04ad9faa0e0449594897e185c6616d2fb91bcc5bca5a2f05b4d21db`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:4fa662cf1044c934195c081261dde3b81189928e4058290118b10c5306717aac`
-	v2 Content-Length: 9.8 MB (9793717 bytes)

#### `8644ab50d76d9b0f854a265561c3d7b2e752db1b97695d18d086f91549b63915`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:15 GMT
-	Parent Layer: `1ee1d539928a4a2b31838f6e3f9cf700307ce4c2c17270aa0b4072be22d2fe2c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0.12-wheezy`

```console
$ docker pull library/node@sha256:07dbb5c3dd5fc56c1a0133fbe7e79e948e709819dd4ee5f4909468cb7660f104
```

-	Total Virtual Size: 490.1 MB (490139981 bytes)
-	Total v2 Content-Length: 185.4 MB (185413344 bytes)

### Layers (9)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `37614c9ef04ad9faa0e0449594897e185c6616d2fb91bcc5bca5a2f05b4d21db`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:27:10 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1ee1d539928a4a2b31838f6e3f9cf700307ce4c2c17270aa0b4072be22d2fe2c`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:14 GMT
-	Parent Layer: `37614c9ef04ad9faa0e0449594897e185c6616d2fb91bcc5bca5a2f05b4d21db`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:4fa662cf1044c934195c081261dde3b81189928e4058290118b10c5306717aac`
-	v2 Content-Length: 9.8 MB (9793717 bytes)

#### `8644ab50d76d9b0f854a265561c3d7b2e752db1b97695d18d086f91549b63915`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:15 GMT
-	Parent Layer: `1ee1d539928a4a2b31838f6e3f9cf700307ce4c2c17270aa0b4072be22d2fe2c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:0-wheezy`

```console
$ docker pull library/node@sha256:120f6087f841f527794a1a1b0bb2cde64a46383e9ed509ad448f24920d7fce02
```

-	Total Virtual Size: 490.1 MB (490139981 bytes)
-	Total v2 Content-Length: 185.4 MB (185413344 bytes)

### Layers (9)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `37614c9ef04ad9faa0e0449594897e185c6616d2fb91bcc5bca5a2f05b4d21db`

```dockerfile
ENV NODE_VERSION=0.12.12
```

-	Created: Wed, 09 Mar 2016 18:27:10 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1ee1d539928a4a2b31838f6e3f9cf700307ce4c2c17270aa0b4072be22d2fe2c`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz" \
	&& curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc" \
	&& gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc \
	&& grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c - \
	&& tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1 \
	&& rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:14 GMT
-	Parent Layer: `37614c9ef04ad9faa0e0449594897e185c6616d2fb91bcc5bca5a2f05b4d21db`
-	Docker Version: 1.9.1
-	Virtual Size: 30.4 MB (30373489 bytes)
-	v2 Blob: `sha256:4fa662cf1044c934195c081261dde3b81189928e4058290118b10c5306717aac`
-	v2 Content-Length: 9.8 MB (9793717 bytes)

#### `8644ab50d76d9b0f854a265561c3d7b2e752db1b97695d18d086f91549b63915`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:15 GMT
-	Parent Layer: `1ee1d539928a4a2b31838f6e3f9cf700307ce4c2c17270aa0b4072be22d2fe2c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4.4.0`

```console
$ docker pull library/node@sha256:2297b34acf5a72009007a6a1d376d7ba341c8b232a0d602c09e1994efeef2e71
```

-	Total Virtual Size: 643.7 MB (643740900 bytes)
-	Total v2 Content-Length: 253.1 MB (253135613 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:27:46 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:50 GMT
-	Parent Layer: `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:9090a75fd680555138e8c744d8a828a142b6cfd5f90535aa0fd744d2dabbeb96`
-	v2 Content-Length: 12.1 MB (12109649 bytes)

#### `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:51 GMT
-	Parent Layer: `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4.4`

```console
$ docker pull library/node@sha256:61d611a80e3d577e015123b7d8baa284c2dbd81f48b78d2591499f0216d98514
```

-	Total Virtual Size: 643.7 MB (643740900 bytes)
-	Total v2 Content-Length: 253.1 MB (253135613 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:27:46 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:50 GMT
-	Parent Layer: `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:9090a75fd680555138e8c744d8a828a142b6cfd5f90535aa0fd744d2dabbeb96`
-	v2 Content-Length: 12.1 MB (12109649 bytes)

#### `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:51 GMT
-	Parent Layer: `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4`

```console
$ docker pull library/node@sha256:bae53154d40489982b1d82a1bc50959ccf7285a9179e8b7748ed84cc9ababae5
```

-	Total Virtual Size: 643.7 MB (643740900 bytes)
-	Total v2 Content-Length: 253.1 MB (253135613 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:27:46 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:50 GMT
-	Parent Layer: `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:9090a75fd680555138e8c744d8a828a142b6cfd5f90535aa0fd744d2dabbeb96`
-	v2 Content-Length: 12.1 MB (12109649 bytes)

#### `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:51 GMT
-	Parent Layer: `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:argon`

```console
$ docker pull library/node@sha256:03066a3e1b4d5bca929ca3cad9cb99e7e96e5335657d62f6a4f179354bcd81d4
```

-	Total Virtual Size: 643.7 MB (643740900 bytes)
-	Total v2 Content-Length: 253.1 MB (253135613 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:27:46 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:50 GMT
-	Parent Layer: `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:9090a75fd680555138e8c744d8a828a142b6cfd5f90535aa0fd744d2dabbeb96`
-	v2 Content-Length: 12.1 MB (12109649 bytes)

#### `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:51 GMT
-	Parent Layer: `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4.4.0-onbuild`

```console
$ docker pull library/node@sha256:a2d1f435c2e0fa6dcaf1f6204964318e8d915ee81953edd84d33a5f3e23b9130
```

-	Total Virtual Size: 643.7 MB (643740900 bytes)
-	Total v2 Content-Length: 253.1 MB (253135898 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:27:46 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:50 GMT
-	Parent Layer: `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:9090a75fd680555138e8c744d8a828a142b6cfd5f90535aa0fd744d2dabbeb96`
-	v2 Content-Length: 12.1 MB (12109649 bytes)

#### `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:51 GMT
-	Parent Layer: `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1d98d9262a674b70c9f2be62c0bd658d537e6db8d59ec5397a31c5a610e630e6`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:33 GMT
-	Parent Layer: `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:3fdf3c72965a8cae15051ec21ad16c912b1907696469bbbd9b7b79d98676da84`
-	v2 Content-Length: 125.0 B

#### `e4f0baa0c96e4a4d7e08636185b68faba5cbb2131de99f24b7b49d9f18cba95a`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:34 GMT
-	Parent Layer: `1d98d9262a674b70c9f2be62c0bd658d537e6db8d59ec5397a31c5a610e630e6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `87cc6ad1cf67fe94d6566832ca6643925c38c96f49de72057bcd571f41f715b5`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Wed, 09 Mar 2016 18:28:35 GMT
-	Parent Layer: `e4f0baa0c96e4a4d7e08636185b68faba5cbb2131de99f24b7b49d9f18cba95a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3b8f4a2fbaa6f6ff9f7518ba294b7f6252325a1beceab65bf5fff40876ac210b`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Wed, 09 Mar 2016 18:28:35 GMT
-	Parent Layer: `87cc6ad1cf67fe94d6566832ca6643925c38c96f49de72057bcd571f41f715b5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b5220f7ad6dc6eb4f47f8684cd8d9316264e15b5cdc5576129f27bb99b2f2fb7`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:36 GMT
-	Parent Layer: `3b8f4a2fbaa6f6ff9f7518ba294b7f6252325a1beceab65bf5fff40876ac210b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b2b7d6aa01b70d5378c5705f8aa28e4e22aa965350effbaf6adaa91594cc5377`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Wed, 09 Mar 2016 18:28:37 GMT
-	Parent Layer: `b5220f7ad6dc6eb4f47f8684cd8d9316264e15b5cdc5576129f27bb99b2f2fb7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4.4-onbuild`

```console
$ docker pull library/node@sha256:743e31d30d40be744bd115c44e2c22fea880102b2db9227865ed2e5d79fe11ba
```

-	Total Virtual Size: 643.7 MB (643740900 bytes)
-	Total v2 Content-Length: 253.1 MB (253135898 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:27:46 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:50 GMT
-	Parent Layer: `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:9090a75fd680555138e8c744d8a828a142b6cfd5f90535aa0fd744d2dabbeb96`
-	v2 Content-Length: 12.1 MB (12109649 bytes)

#### `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:51 GMT
-	Parent Layer: `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1d98d9262a674b70c9f2be62c0bd658d537e6db8d59ec5397a31c5a610e630e6`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:33 GMT
-	Parent Layer: `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:3fdf3c72965a8cae15051ec21ad16c912b1907696469bbbd9b7b79d98676da84`
-	v2 Content-Length: 125.0 B

#### `e4f0baa0c96e4a4d7e08636185b68faba5cbb2131de99f24b7b49d9f18cba95a`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:34 GMT
-	Parent Layer: `1d98d9262a674b70c9f2be62c0bd658d537e6db8d59ec5397a31c5a610e630e6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `87cc6ad1cf67fe94d6566832ca6643925c38c96f49de72057bcd571f41f715b5`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Wed, 09 Mar 2016 18:28:35 GMT
-	Parent Layer: `e4f0baa0c96e4a4d7e08636185b68faba5cbb2131de99f24b7b49d9f18cba95a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3b8f4a2fbaa6f6ff9f7518ba294b7f6252325a1beceab65bf5fff40876ac210b`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Wed, 09 Mar 2016 18:28:35 GMT
-	Parent Layer: `87cc6ad1cf67fe94d6566832ca6643925c38c96f49de72057bcd571f41f715b5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b5220f7ad6dc6eb4f47f8684cd8d9316264e15b5cdc5576129f27bb99b2f2fb7`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:36 GMT
-	Parent Layer: `3b8f4a2fbaa6f6ff9f7518ba294b7f6252325a1beceab65bf5fff40876ac210b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b2b7d6aa01b70d5378c5705f8aa28e4e22aa965350effbaf6adaa91594cc5377`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Wed, 09 Mar 2016 18:28:37 GMT
-	Parent Layer: `b5220f7ad6dc6eb4f47f8684cd8d9316264e15b5cdc5576129f27bb99b2f2fb7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4-onbuild`

```console
$ docker pull library/node@sha256:c196dc31d2af01c6caaca9e5fa4ef5ecf785aabe8720cd21b2d4579ae660e282
```

-	Total Virtual Size: 643.7 MB (643740900 bytes)
-	Total v2 Content-Length: 253.1 MB (253135898 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:27:46 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:50 GMT
-	Parent Layer: `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:9090a75fd680555138e8c744d8a828a142b6cfd5f90535aa0fd744d2dabbeb96`
-	v2 Content-Length: 12.1 MB (12109649 bytes)

#### `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:51 GMT
-	Parent Layer: `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1d98d9262a674b70c9f2be62c0bd658d537e6db8d59ec5397a31c5a610e630e6`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:33 GMT
-	Parent Layer: `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:3fdf3c72965a8cae15051ec21ad16c912b1907696469bbbd9b7b79d98676da84`
-	v2 Content-Length: 125.0 B

#### `e4f0baa0c96e4a4d7e08636185b68faba5cbb2131de99f24b7b49d9f18cba95a`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:34 GMT
-	Parent Layer: `1d98d9262a674b70c9f2be62c0bd658d537e6db8d59ec5397a31c5a610e630e6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `87cc6ad1cf67fe94d6566832ca6643925c38c96f49de72057bcd571f41f715b5`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Wed, 09 Mar 2016 18:28:35 GMT
-	Parent Layer: `e4f0baa0c96e4a4d7e08636185b68faba5cbb2131de99f24b7b49d9f18cba95a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3b8f4a2fbaa6f6ff9f7518ba294b7f6252325a1beceab65bf5fff40876ac210b`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Wed, 09 Mar 2016 18:28:35 GMT
-	Parent Layer: `87cc6ad1cf67fe94d6566832ca6643925c38c96f49de72057bcd571f41f715b5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b5220f7ad6dc6eb4f47f8684cd8d9316264e15b5cdc5576129f27bb99b2f2fb7`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:36 GMT
-	Parent Layer: `3b8f4a2fbaa6f6ff9f7518ba294b7f6252325a1beceab65bf5fff40876ac210b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b2b7d6aa01b70d5378c5705f8aa28e4e22aa965350effbaf6adaa91594cc5377`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Wed, 09 Mar 2016 18:28:37 GMT
-	Parent Layer: `b5220f7ad6dc6eb4f47f8684cd8d9316264e15b5cdc5576129f27bb99b2f2fb7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:argon-onbuild`

```console
$ docker pull library/node@sha256:c555c30c865a42476df39c69781e625ec96b7042888ea4c69000e6ba684ebcb0
```

-	Total Virtual Size: 643.7 MB (643740900 bytes)
-	Total v2 Content-Length: 253.1 MB (253135898 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:27:46 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:27:50 GMT
-	Parent Layer: `282afdbe62c40b39548e546522ca8cda84c91afe040f05d078e9e1831ccc63ea`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:9090a75fd680555138e8c744d8a828a142b6cfd5f90535aa0fd744d2dabbeb96`
-	v2 Content-Length: 12.1 MB (12109649 bytes)

#### `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:27:51 GMT
-	Parent Layer: `b943b76ba6be044eb1be2124a3a44eb262a94585b3e2f0cdc08ffa6ab5b284a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1d98d9262a674b70c9f2be62c0bd658d537e6db8d59ec5397a31c5a610e630e6`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:33 GMT
-	Parent Layer: `14c6b4a1f30b74471041b954258825f628fac116c301e83f9172cd1784fc26f3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:3fdf3c72965a8cae15051ec21ad16c912b1907696469bbbd9b7b79d98676da84`
-	v2 Content-Length: 125.0 B

#### `e4f0baa0c96e4a4d7e08636185b68faba5cbb2131de99f24b7b49d9f18cba95a`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:34 GMT
-	Parent Layer: `1d98d9262a674b70c9f2be62c0bd658d537e6db8d59ec5397a31c5a610e630e6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `87cc6ad1cf67fe94d6566832ca6643925c38c96f49de72057bcd571f41f715b5`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Wed, 09 Mar 2016 18:28:35 GMT
-	Parent Layer: `e4f0baa0c96e4a4d7e08636185b68faba5cbb2131de99f24b7b49d9f18cba95a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3b8f4a2fbaa6f6ff9f7518ba294b7f6252325a1beceab65bf5fff40876ac210b`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Wed, 09 Mar 2016 18:28:35 GMT
-	Parent Layer: `87cc6ad1cf67fe94d6566832ca6643925c38c96f49de72057bcd571f41f715b5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b5220f7ad6dc6eb4f47f8684cd8d9316264e15b5cdc5576129f27bb99b2f2fb7`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Mar 2016 18:28:36 GMT
-	Parent Layer: `3b8f4a2fbaa6f6ff9f7518ba294b7f6252325a1beceab65bf5fff40876ac210b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `b2b7d6aa01b70d5378c5705f8aa28e4e22aa965350effbaf6adaa91594cc5377`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Wed, 09 Mar 2016 18:28:37 GMT
-	Parent Layer: `b5220f7ad6dc6eb4f47f8684cd8d9316264e15b5cdc5576129f27bb99b2f2fb7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4.4.0-slim`

```console
$ docker pull library/node@sha256:4f842abcc6616a51a0fab02ecacbf2bccd7af2b89d862be01a1ffe9b51c0494c
```

-	Total Virtual Size: 206.8 MB (206799014 bytes)
-	Total v2 Content-Length: 82.1 MB (82117637 bytes)

### Layers (8)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:06:25 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b6c4c5059134a4e9f52b9512688dcdb3b8890b31d438b23c1b03e1d1cbc6303f`
-	v2 Content-Length: 26.9 KB (26938 bytes)

#### `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:06:26 GMT
-	Parent Layer: `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `581f2c8c7efae43189ffc83bdc8981875180996fa6626026cbe6110a210cfc79`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:29:33 GMT
-	Parent Layer: `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2bb617dbd3fc9ef69d5be3761401813cb7157cb07204cba56c0f2b00465f3dd6`

```dockerfile
RUN buildDeps='xz-utils'\
     && set -x\
     && apt-get update && apt-get install -y $buildDeps --no-install-recommends\
     && rm -rf /var/lib/apt/lists/*\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"\
     && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc\
     && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -\
     && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1\
     && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt\
     && apt-get purge -y --auto-remove $buildDeps
```

-	Created: Wed, 09 Mar 2016 18:30:20 GMT
-	Parent Layer: `581f2c8c7efae43189ffc83bdc8981875180996fa6626026cbe6110a210cfc79`
-	Docker Version: 1.9.1
-	Virtual Size: 37.3 MB (37321116 bytes)
-	v2 Blob: `sha256:0ee8917bdd4b58ad446d35ef8e560322ebe033c51ab1ecde27fd78bec1b8c5d2`
-	v2 Content-Length: 12.2 MB (12188758 bytes)

#### `b971ec07f168fa810dd9bcce4c70318609da5689f12f59ec7fadaf7152c82216`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:30:21 GMT
-	Parent Layer: `2bb617dbd3fc9ef69d5be3761401813cb7157cb07204cba56c0f2b00465f3dd6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4.4-slim`

```console
$ docker pull library/node@sha256:dbd418ea3a8f23320e18437d6ff7f4e48cc709104cb79840d1deea8ee592d5a5
```

-	Total Virtual Size: 206.8 MB (206799014 bytes)
-	Total v2 Content-Length: 82.1 MB (82117637 bytes)

### Layers (8)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:06:25 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b6c4c5059134a4e9f52b9512688dcdb3b8890b31d438b23c1b03e1d1cbc6303f`
-	v2 Content-Length: 26.9 KB (26938 bytes)

#### `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:06:26 GMT
-	Parent Layer: `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `581f2c8c7efae43189ffc83bdc8981875180996fa6626026cbe6110a210cfc79`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:29:33 GMT
-	Parent Layer: `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2bb617dbd3fc9ef69d5be3761401813cb7157cb07204cba56c0f2b00465f3dd6`

```dockerfile
RUN buildDeps='xz-utils'\
     && set -x\
     && apt-get update && apt-get install -y $buildDeps --no-install-recommends\
     && rm -rf /var/lib/apt/lists/*\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"\
     && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc\
     && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -\
     && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1\
     && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt\
     && apt-get purge -y --auto-remove $buildDeps
```

-	Created: Wed, 09 Mar 2016 18:30:20 GMT
-	Parent Layer: `581f2c8c7efae43189ffc83bdc8981875180996fa6626026cbe6110a210cfc79`
-	Docker Version: 1.9.1
-	Virtual Size: 37.3 MB (37321116 bytes)
-	v2 Blob: `sha256:0ee8917bdd4b58ad446d35ef8e560322ebe033c51ab1ecde27fd78bec1b8c5d2`
-	v2 Content-Length: 12.2 MB (12188758 bytes)

#### `b971ec07f168fa810dd9bcce4c70318609da5689f12f59ec7fadaf7152c82216`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:30:21 GMT
-	Parent Layer: `2bb617dbd3fc9ef69d5be3761401813cb7157cb07204cba56c0f2b00465f3dd6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4-slim`

```console
$ docker pull library/node@sha256:06443449e1b8ba26f868559bec6167cd66ecf858df82a39097321ba1b406016c
```

-	Total Virtual Size: 206.8 MB (206799014 bytes)
-	Total v2 Content-Length: 82.1 MB (82117637 bytes)

### Layers (8)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:06:25 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b6c4c5059134a4e9f52b9512688dcdb3b8890b31d438b23c1b03e1d1cbc6303f`
-	v2 Content-Length: 26.9 KB (26938 bytes)

#### `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:06:26 GMT
-	Parent Layer: `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `581f2c8c7efae43189ffc83bdc8981875180996fa6626026cbe6110a210cfc79`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:29:33 GMT
-	Parent Layer: `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2bb617dbd3fc9ef69d5be3761401813cb7157cb07204cba56c0f2b00465f3dd6`

```dockerfile
RUN buildDeps='xz-utils'\
     && set -x\
     && apt-get update && apt-get install -y $buildDeps --no-install-recommends\
     && rm -rf /var/lib/apt/lists/*\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"\
     && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc\
     && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -\
     && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1\
     && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt\
     && apt-get purge -y --auto-remove $buildDeps
```

-	Created: Wed, 09 Mar 2016 18:30:20 GMT
-	Parent Layer: `581f2c8c7efae43189ffc83bdc8981875180996fa6626026cbe6110a210cfc79`
-	Docker Version: 1.9.1
-	Virtual Size: 37.3 MB (37321116 bytes)
-	v2 Blob: `sha256:0ee8917bdd4b58ad446d35ef8e560322ebe033c51ab1ecde27fd78bec1b8c5d2`
-	v2 Content-Length: 12.2 MB (12188758 bytes)

#### `b971ec07f168fa810dd9bcce4c70318609da5689f12f59ec7fadaf7152c82216`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:30:21 GMT
-	Parent Layer: `2bb617dbd3fc9ef69d5be3761401813cb7157cb07204cba56c0f2b00465f3dd6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:argon-slim`

```console
$ docker pull library/node@sha256:b6729c81dd9a9f236f5af873353f707cb06921649a69a3bd8add1f19ed4e4e3f
```

-	Total Virtual Size: 206.8 MB (206799014 bytes)
-	Total v2 Content-Length: 82.1 MB (82117637 bytes)

### Layers (8)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:06:25 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b6c4c5059134a4e9f52b9512688dcdb3b8890b31d438b23c1b03e1d1cbc6303f`
-	v2 Content-Length: 26.9 KB (26938 bytes)

#### `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:06:26 GMT
-	Parent Layer: `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `581f2c8c7efae43189ffc83bdc8981875180996fa6626026cbe6110a210cfc79`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:29:33 GMT
-	Parent Layer: `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2bb617dbd3fc9ef69d5be3761401813cb7157cb07204cba56c0f2b00465f3dd6`

```dockerfile
RUN buildDeps='xz-utils'\
     && set -x\
     && apt-get update && apt-get install -y $buildDeps --no-install-recommends\
     && rm -rf /var/lib/apt/lists/*\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"\
     && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc\
     && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -\
     && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1\
     && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt\
     && apt-get purge -y --auto-remove $buildDeps
```

-	Created: Wed, 09 Mar 2016 18:30:20 GMT
-	Parent Layer: `581f2c8c7efae43189ffc83bdc8981875180996fa6626026cbe6110a210cfc79`
-	Docker Version: 1.9.1
-	Virtual Size: 37.3 MB (37321116 bytes)
-	v2 Blob: `sha256:0ee8917bdd4b58ad446d35ef8e560322ebe033c51ab1ecde27fd78bec1b8c5d2`
-	v2 Content-Length: 12.2 MB (12188758 bytes)

#### `b971ec07f168fa810dd9bcce4c70318609da5689f12f59ec7fadaf7152c82216`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:30:21 GMT
-	Parent Layer: `2bb617dbd3fc9ef69d5be3761401813cb7157cb07204cba56c0f2b00465f3dd6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4.4.0-wheezy`

```console
$ docker pull library/node@sha256:cc3dafcf9e3424f61323e3c97ae4861039bdac8c0ccd9ab1564341e78615e3a2
```

-	Total Virtual Size: 496.7 MB (496744277 bytes)
-	Total v2 Content-Length: 187.7 MB (187729306 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:07:33 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `cac0677faecdcfc8c604f062dcc6db0beae69d1d02842ff0eda2486876323dab`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:31:10 GMT
-	Parent Layer: `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `5d4f392ec011b7346bad283d8f0375395eea2e9e45ebdbe8ebd946e6b5133bd2`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:31:14 GMT
-	Parent Layer: `cac0677faecdcfc8c604f062dcc6db0beae69d1d02842ff0eda2486876323dab`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:fe63f9c8be8ffe2314915eb45ebf6dc314bd7ec71ee2a1ffe3ce3dfac34487b7`
-	v2 Content-Length: 12.1 MB (12109647 bytes)

#### `ea155cfdc00dace686a3341567411e589af2d54978c3e93c9a21b23a709a583c`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:31:16 GMT
-	Parent Layer: `5d4f392ec011b7346bad283d8f0375395eea2e9e45ebdbe8ebd946e6b5133bd2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4.4-wheezy`

```console
$ docker pull library/node@sha256:d492447dc1749f1d9b17666d7950abb965bbea18318eb410c56717254d1b649f
```

-	Total Virtual Size: 496.7 MB (496744277 bytes)
-	Total v2 Content-Length: 187.7 MB (187729306 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:07:33 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `cac0677faecdcfc8c604f062dcc6db0beae69d1d02842ff0eda2486876323dab`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:31:10 GMT
-	Parent Layer: `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `5d4f392ec011b7346bad283d8f0375395eea2e9e45ebdbe8ebd946e6b5133bd2`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:31:14 GMT
-	Parent Layer: `cac0677faecdcfc8c604f062dcc6db0beae69d1d02842ff0eda2486876323dab`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:fe63f9c8be8ffe2314915eb45ebf6dc314bd7ec71ee2a1ffe3ce3dfac34487b7`
-	v2 Content-Length: 12.1 MB (12109647 bytes)

#### `ea155cfdc00dace686a3341567411e589af2d54978c3e93c9a21b23a709a583c`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:31:16 GMT
-	Parent Layer: `5d4f392ec011b7346bad283d8f0375395eea2e9e45ebdbe8ebd946e6b5133bd2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:4-wheezy`

```console
$ docker pull library/node@sha256:23ea64611dfab44a887f21722e818e753c264f79c93d82de50b22abd28efbbda
```

-	Total Virtual Size: 496.7 MB (496744277 bytes)
-	Total v2 Content-Length: 187.7 MB (187729306 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:07:33 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `cac0677faecdcfc8c604f062dcc6db0beae69d1d02842ff0eda2486876323dab`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:31:10 GMT
-	Parent Layer: `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `5d4f392ec011b7346bad283d8f0375395eea2e9e45ebdbe8ebd946e6b5133bd2`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:31:14 GMT
-	Parent Layer: `cac0677faecdcfc8c604f062dcc6db0beae69d1d02842ff0eda2486876323dab`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:fe63f9c8be8ffe2314915eb45ebf6dc314bd7ec71ee2a1ffe3ce3dfac34487b7`
-	v2 Content-Length: 12.1 MB (12109647 bytes)

#### `ea155cfdc00dace686a3341567411e589af2d54978c3e93c9a21b23a709a583c`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:31:16 GMT
-	Parent Layer: `5d4f392ec011b7346bad283d8f0375395eea2e9e45ebdbe8ebd946e6b5133bd2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:argon-wheezy`

```console
$ docker pull library/node@sha256:06063638f32b4aadfd706a7d0f75fcff936f10531cb62a4d0ea051ee32956ef9
```

-	Total Virtual Size: 496.7 MB (496744277 bytes)
-	Total v2 Content-Length: 187.7 MB (187729306 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:07:33 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `cac0677faecdcfc8c604f062dcc6db0beae69d1d02842ff0eda2486876323dab`

```dockerfile
ENV NODE_VERSION=4.4.0
```

-	Created: Wed, 09 Mar 2016 18:31:10 GMT
-	Parent Layer: `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `5d4f392ec011b7346bad283d8f0375395eea2e9e45ebdbe8ebd946e6b5133bd2`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Wed, 09 Mar 2016 18:31:14 GMT
-	Parent Layer: `cac0677faecdcfc8c604f062dcc6db0beae69d1d02842ff0eda2486876323dab`
-	Docker Version: 1.9.1
-	Virtual Size: 37.0 MB (36977785 bytes)
-	v2 Blob: `sha256:fe63f9c8be8ffe2314915eb45ebf6dc314bd7ec71ee2a1ffe3ce3dfac34487b7`
-	v2 Content-Length: 12.1 MB (12109647 bytes)

#### `ea155cfdc00dace686a3341567411e589af2d54978c3e93c9a21b23a709a583c`

```dockerfile
CMD ["node"]
```

-	Created: Wed, 09 Mar 2016 18:31:16 GMT
-	Parent Layer: `5d4f392ec011b7346bad283d8f0375395eea2e9e45ebdbe8ebd946e6b5133bd2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5.9.0`

```console
$ docker pull library/node@sha256:d1f155d7be233334c1051f36e63c13fc3d273048571a4d9cbda57c206e52a7aa
```

-	Total Virtual Size: 644.3 MB (644302697 bytes)
-	Total v2 Content-Length: 253.3 MB (253278256 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:23:02 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:23:06 GMT
-	Parent Layer: `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:54995cb663907cc5e6006efd41789ef43ad6a508047da02b9deeeaa13652b571`
-	v2 Content-Length: 12.3 MB (12252292 bytes)

#### `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:23:08 GMT
-	Parent Layer: `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5.9`

```console
$ docker pull library/node@sha256:6b507d99975f68c365379d712bd72b361bd18c76c1e047357e9602bc5cca698b
```

-	Total Virtual Size: 644.3 MB (644302697 bytes)
-	Total v2 Content-Length: 253.3 MB (253278256 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:23:02 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:23:06 GMT
-	Parent Layer: `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:54995cb663907cc5e6006efd41789ef43ad6a508047da02b9deeeaa13652b571`
-	v2 Content-Length: 12.3 MB (12252292 bytes)

#### `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:23:08 GMT
-	Parent Layer: `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5`

```console
$ docker pull library/node@sha256:6b6874a9e0a24e46a22bb4cb660bb5ab981941dc29475847615f4d74999d4834
```

-	Total Virtual Size: 644.3 MB (644302697 bytes)
-	Total v2 Content-Length: 253.3 MB (253278256 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:23:02 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:23:06 GMT
-	Parent Layer: `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:54995cb663907cc5e6006efd41789ef43ad6a508047da02b9deeeaa13652b571`
-	v2 Content-Length: 12.3 MB (12252292 bytes)

#### `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:23:08 GMT
-	Parent Layer: `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:latest`

```console
$ docker pull library/node@sha256:47287141adcf84156b2b4344c8aa593bf2a6fe7eb68e3fd04df0da75aa667454
```

-	Total Virtual Size: 644.3 MB (644302697 bytes)
-	Total v2 Content-Length: 253.3 MB (253278256 bytes)

### Layers (10)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:23:02 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:23:06 GMT
-	Parent Layer: `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:54995cb663907cc5e6006efd41789ef43ad6a508047da02b9deeeaa13652b571`
-	v2 Content-Length: 12.3 MB (12252292 bytes)

#### `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:23:08 GMT
-	Parent Layer: `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5.9.0-onbuild`

```console
$ docker pull library/node@sha256:df81f615d88831472c4ca8a1b94273556a01c17e47c33ec217f40d673821d1c7
```

-	Total Virtual Size: 644.3 MB (644302697 bytes)
-	Total v2 Content-Length: 253.3 MB (253278543 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:23:02 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:23:06 GMT
-	Parent Layer: `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:54995cb663907cc5e6006efd41789ef43ad6a508047da02b9deeeaa13652b571`
-	v2 Content-Length: 12.3 MB (12252292 bytes)

#### `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:23:08 GMT
-	Parent Layer: `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2316535a26b7023e9d986c622aa5bcc94488234d25cfabafb8a09c5763644c8e`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:49 GMT
-	Parent Layer: `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:7b5ef9392be34fb110826334bc0f98a55fb769d3490afd2585d3d2aa195af6c7`
-	v2 Content-Length: 127.0 B

#### `f290091529fafbcfb8c413dc3818a1a32372c0fe60efde0f7ca6583626c4aaa1`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:50 GMT
-	Parent Layer: `2316535a26b7023e9d986c622aa5bcc94488234d25cfabafb8a09c5763644c8e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9ed8aa8980db0472db0c2406d34eb91e149c25fb8e2bb16a0ebc6e82bfa71439`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 17 Mar 2016 16:23:50 GMT
-	Parent Layer: `f290091529fafbcfb8c413dc3818a1a32372c0fe60efde0f7ca6583626c4aaa1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1b2f6e8fb8666ec513bc213094212673f0ca272f680fb29c103b39f66b6dc060`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 17 Mar 2016 16:23:51 GMT
-	Parent Layer: `9ed8aa8980db0472db0c2406d34eb91e149c25fb8e2bb16a0ebc6e82bfa71439`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `a375be29bb96e84296b8955006060b504877d3ff0bcb2919529de028e80467d6`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:51 GMT
-	Parent Layer: `1b2f6e8fb8666ec513bc213094212673f0ca272f680fb29c103b39f66b6dc060`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `232571f9e8ff5fbacc0fb057b2d1bc373ae618ce16949162805501c8edf5c0dd`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 17 Mar 2016 16:23:52 GMT
-	Parent Layer: `a375be29bb96e84296b8955006060b504877d3ff0bcb2919529de028e80467d6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5.9-onbuild`

```console
$ docker pull library/node@sha256:8f5ff8963e4788a97d2bb140b103d869d19832fca46f29ceeb5b59d65e06293d
```

-	Total Virtual Size: 644.3 MB (644302697 bytes)
-	Total v2 Content-Length: 253.3 MB (253278543 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:23:02 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:23:06 GMT
-	Parent Layer: `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:54995cb663907cc5e6006efd41789ef43ad6a508047da02b9deeeaa13652b571`
-	v2 Content-Length: 12.3 MB (12252292 bytes)

#### `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:23:08 GMT
-	Parent Layer: `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2316535a26b7023e9d986c622aa5bcc94488234d25cfabafb8a09c5763644c8e`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:49 GMT
-	Parent Layer: `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:7b5ef9392be34fb110826334bc0f98a55fb769d3490afd2585d3d2aa195af6c7`
-	v2 Content-Length: 127.0 B

#### `f290091529fafbcfb8c413dc3818a1a32372c0fe60efde0f7ca6583626c4aaa1`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:50 GMT
-	Parent Layer: `2316535a26b7023e9d986c622aa5bcc94488234d25cfabafb8a09c5763644c8e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9ed8aa8980db0472db0c2406d34eb91e149c25fb8e2bb16a0ebc6e82bfa71439`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 17 Mar 2016 16:23:50 GMT
-	Parent Layer: `f290091529fafbcfb8c413dc3818a1a32372c0fe60efde0f7ca6583626c4aaa1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1b2f6e8fb8666ec513bc213094212673f0ca272f680fb29c103b39f66b6dc060`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 17 Mar 2016 16:23:51 GMT
-	Parent Layer: `9ed8aa8980db0472db0c2406d34eb91e149c25fb8e2bb16a0ebc6e82bfa71439`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `a375be29bb96e84296b8955006060b504877d3ff0bcb2919529de028e80467d6`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:51 GMT
-	Parent Layer: `1b2f6e8fb8666ec513bc213094212673f0ca272f680fb29c103b39f66b6dc060`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `232571f9e8ff5fbacc0fb057b2d1bc373ae618ce16949162805501c8edf5c0dd`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 17 Mar 2016 16:23:52 GMT
-	Parent Layer: `a375be29bb96e84296b8955006060b504877d3ff0bcb2919529de028e80467d6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5-onbuild`

```console
$ docker pull library/node@sha256:f741a2798f8313d6bc5da4fa99356f3de772d3c6c19f62f8992adc6d0b3cf4d9
```

-	Total Virtual Size: 644.3 MB (644302697 bytes)
-	Total v2 Content-Length: 253.3 MB (253278543 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:23:02 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:23:06 GMT
-	Parent Layer: `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:54995cb663907cc5e6006efd41789ef43ad6a508047da02b9deeeaa13652b571`
-	v2 Content-Length: 12.3 MB (12252292 bytes)

#### `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:23:08 GMT
-	Parent Layer: `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2316535a26b7023e9d986c622aa5bcc94488234d25cfabafb8a09c5763644c8e`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:49 GMT
-	Parent Layer: `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:7b5ef9392be34fb110826334bc0f98a55fb769d3490afd2585d3d2aa195af6c7`
-	v2 Content-Length: 127.0 B

#### `f290091529fafbcfb8c413dc3818a1a32372c0fe60efde0f7ca6583626c4aaa1`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:50 GMT
-	Parent Layer: `2316535a26b7023e9d986c622aa5bcc94488234d25cfabafb8a09c5763644c8e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9ed8aa8980db0472db0c2406d34eb91e149c25fb8e2bb16a0ebc6e82bfa71439`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 17 Mar 2016 16:23:50 GMT
-	Parent Layer: `f290091529fafbcfb8c413dc3818a1a32372c0fe60efde0f7ca6583626c4aaa1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1b2f6e8fb8666ec513bc213094212673f0ca272f680fb29c103b39f66b6dc060`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 17 Mar 2016 16:23:51 GMT
-	Parent Layer: `9ed8aa8980db0472db0c2406d34eb91e149c25fb8e2bb16a0ebc6e82bfa71439`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `a375be29bb96e84296b8955006060b504877d3ff0bcb2919529de028e80467d6`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:51 GMT
-	Parent Layer: `1b2f6e8fb8666ec513bc213094212673f0ca272f680fb29c103b39f66b6dc060`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `232571f9e8ff5fbacc0fb057b2d1bc373ae618ce16949162805501c8edf5c0dd`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 17 Mar 2016 16:23:52 GMT
-	Parent Layer: `a375be29bb96e84296b8955006060b504877d3ff0bcb2919529de028e80467d6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:onbuild`

```console
$ docker pull library/node@sha256:1e2ed119ec585ab1f04740541a833790aadf6ddd3ec21eb419038bb643edbe12
```

-	Total Virtual Size: 644.3 MB (644302697 bytes)
-	Total v2 Content-Length: 253.3 MB (253278543 bytes)

### Layers (16)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:26 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122586932 bytes)
-	v2 Blob: `sha256:627b6479c8f7601589d5fc889d9aa0fc9121f26dfd1c5af64ba964f82d561d8b`
-	v2 Content-Length: 42.5 MB (42494879 bytes)

#### `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:01:16 GMT
-	Parent Layer: `5901462573ab9e62761caa412b98a6ea4c847f2d652e9a9be18befbc36986331`
-	Docker Version: 1.9.1
-	Virtual Size: 314.7 MB (314698285 bytes)
-	v2 Blob: `sha256:67c44324f4e30ead35c8a464eac3c0a3533d5f58ce2d64f1d89d07432f0073cd`
-	v2 Content-Length: 128.6 MB (128602210 bytes)

#### `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:00:21 GMT
-	Parent Layer: `c8bb6b7c8be6a598f8fca43966e84ece9e368b15b36b75f8a73e028ee4b9face`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b52090f6ca009920f912ca84362aa053fbc6b4841a66c1c416cdd3f523f5ff5d`
-	v2 Content-Length: 26.9 KB (26934 bytes)

#### `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:05:39 GMT
-	Parent Layer: `1a333ae26010565f616d1f77a0ac4c88c11bc677288db6d3eaf06e09eef7bb1e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:23:02 GMT
-	Parent Layer: `5daa010059a27a9b7258d8f9227f21947806fb274a9be94ea09e72dfec268fde`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:23:06 GMT
-	Parent Layer: `f0e8b4b23a1be2a30cd05b51439812bfafaf6e05115536873dc97ffefadde760`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:54995cb663907cc5e6006efd41789ef43ad6a508047da02b9deeeaa13652b571`
-	v2 Content-Length: 12.3 MB (12252292 bytes)

#### `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:23:08 GMT
-	Parent Layer: `372c4f2561194f2674a59a916547cb93bc1b9ba7ed8d00d4fa701f27d34042f7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `2316535a26b7023e9d986c622aa5bcc94488234d25cfabafb8a09c5763644c8e`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:49 GMT
-	Parent Layer: `f87e184044814c98ec48259f881fe1d7d110d8058e8bf43a1172fd40f1e876ff`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:7b5ef9392be34fb110826334bc0f98a55fb769d3490afd2585d3d2aa195af6c7`
-	v2 Content-Length: 127.0 B

#### `f290091529fafbcfb8c413dc3818a1a32372c0fe60efde0f7ca6583626c4aaa1`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:50 GMT
-	Parent Layer: `2316535a26b7023e9d986c622aa5bcc94488234d25cfabafb8a09c5763644c8e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `9ed8aa8980db0472db0c2406d34eb91e149c25fb8e2bb16a0ebc6e82bfa71439`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 17 Mar 2016 16:23:50 GMT
-	Parent Layer: `f290091529fafbcfb8c413dc3818a1a32372c0fe60efde0f7ca6583626c4aaa1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1b2f6e8fb8666ec513bc213094212673f0ca272f680fb29c103b39f66b6dc060`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 17 Mar 2016 16:23:51 GMT
-	Parent Layer: `9ed8aa8980db0472db0c2406d34eb91e149c25fb8e2bb16a0ebc6e82bfa71439`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `a375be29bb96e84296b8955006060b504877d3ff0bcb2919529de028e80467d6`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 17 Mar 2016 16:23:51 GMT
-	Parent Layer: `1b2f6e8fb8666ec513bc213094212673f0ca272f680fb29c103b39f66b6dc060`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `232571f9e8ff5fbacc0fb057b2d1bc373ae618ce16949162805501c8edf5c0dd`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 17 Mar 2016 16:23:52 GMT
-	Parent Layer: `a375be29bb96e84296b8955006060b504877d3ff0bcb2919529de028e80467d6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5.9.0-slim`

```console
$ docker pull library/node@sha256:413a7a52c3edd7150cd1c9f1faf7f61fd31baf4fa77ae5929c943f9e576fe5a1
```

-	Total Virtual Size: 207.4 MB (207360811 bytes)
-	Total v2 Content-Length: 82.3 MB (82260276 bytes)

### Layers (8)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:06:25 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b6c4c5059134a4e9f52b9512688dcdb3b8890b31d438b23c1b03e1d1cbc6303f`
-	v2 Content-Length: 26.9 KB (26938 bytes)

#### `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:06:26 GMT
-	Parent Layer: `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `99a469d47740c5d1b63677ad9b880325a6b0eb354a5c3f108fabcf82a169fa0a`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:24:48 GMT
-	Parent Layer: `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `069f924fa52b583ba694badc608c9e2e3fe6c600d42c99eaedab317ac1fd5ef8`

```dockerfile
RUN buildDeps='xz-utils'\
     && set -x\
     && apt-get update && apt-get install -y $buildDeps --no-install-recommends\
     && rm -rf /var/lib/apt/lists/*\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"\
     && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc\
     && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -\
     && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1\
     && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt\
     && apt-get purge -y --auto-remove $buildDeps
```

-	Created: Thu, 17 Mar 2016 16:25:35 GMT
-	Parent Layer: `99a469d47740c5d1b63677ad9b880325a6b0eb354a5c3f108fabcf82a169fa0a`
-	Docker Version: 1.9.1
-	Virtual Size: 37.9 MB (37882913 bytes)
-	v2 Blob: `sha256:e65b80560fd5252d993388a7879f92b63cd41b43906aaee4f35b54cfbff87270`
-	v2 Content-Length: 12.3 MB (12331397 bytes)

#### `94626086051a15269a5cccb21f82c9c171f24b590ef37b3296f318890e26b772`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:25:36 GMT
-	Parent Layer: `069f924fa52b583ba694badc608c9e2e3fe6c600d42c99eaedab317ac1fd5ef8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5.9-slim`

```console
$ docker pull library/node@sha256:b25be11d8bd1154d58fa9c1e52d4ac617f1f15a43de01dcaf99ea13a18335811
```

-	Total Virtual Size: 207.4 MB (207360811 bytes)
-	Total v2 Content-Length: 82.3 MB (82260276 bytes)

### Layers (8)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:06:25 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b6c4c5059134a4e9f52b9512688dcdb3b8890b31d438b23c1b03e1d1cbc6303f`
-	v2 Content-Length: 26.9 KB (26938 bytes)

#### `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:06:26 GMT
-	Parent Layer: `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `99a469d47740c5d1b63677ad9b880325a6b0eb354a5c3f108fabcf82a169fa0a`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:24:48 GMT
-	Parent Layer: `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `069f924fa52b583ba694badc608c9e2e3fe6c600d42c99eaedab317ac1fd5ef8`

```dockerfile
RUN buildDeps='xz-utils'\
     && set -x\
     && apt-get update && apt-get install -y $buildDeps --no-install-recommends\
     && rm -rf /var/lib/apt/lists/*\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"\
     && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc\
     && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -\
     && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1\
     && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt\
     && apt-get purge -y --auto-remove $buildDeps
```

-	Created: Thu, 17 Mar 2016 16:25:35 GMT
-	Parent Layer: `99a469d47740c5d1b63677ad9b880325a6b0eb354a5c3f108fabcf82a169fa0a`
-	Docker Version: 1.9.1
-	Virtual Size: 37.9 MB (37882913 bytes)
-	v2 Blob: `sha256:e65b80560fd5252d993388a7879f92b63cd41b43906aaee4f35b54cfbff87270`
-	v2 Content-Length: 12.3 MB (12331397 bytes)

#### `94626086051a15269a5cccb21f82c9c171f24b590ef37b3296f318890e26b772`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:25:36 GMT
-	Parent Layer: `069f924fa52b583ba694badc608c9e2e3fe6c600d42c99eaedab317ac1fd5ef8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5-slim`

```console
$ docker pull library/node@sha256:71bc7fdcc4e2fdd6de22390a006f55af0104d2b37fe91b2ce285e7a5fa3ac734
```

-	Total Virtual Size: 207.4 MB (207360811 bytes)
-	Total v2 Content-Length: 82.3 MB (82260276 bytes)

### Layers (8)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:06:25 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b6c4c5059134a4e9f52b9512688dcdb3b8890b31d438b23c1b03e1d1cbc6303f`
-	v2 Content-Length: 26.9 KB (26938 bytes)

#### `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:06:26 GMT
-	Parent Layer: `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `99a469d47740c5d1b63677ad9b880325a6b0eb354a5c3f108fabcf82a169fa0a`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:24:48 GMT
-	Parent Layer: `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `069f924fa52b583ba694badc608c9e2e3fe6c600d42c99eaedab317ac1fd5ef8`

```dockerfile
RUN buildDeps='xz-utils'\
     && set -x\
     && apt-get update && apt-get install -y $buildDeps --no-install-recommends\
     && rm -rf /var/lib/apt/lists/*\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"\
     && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc\
     && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -\
     && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1\
     && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt\
     && apt-get purge -y --auto-remove $buildDeps
```

-	Created: Thu, 17 Mar 2016 16:25:35 GMT
-	Parent Layer: `99a469d47740c5d1b63677ad9b880325a6b0eb354a5c3f108fabcf82a169fa0a`
-	Docker Version: 1.9.1
-	Virtual Size: 37.9 MB (37882913 bytes)
-	v2 Blob: `sha256:e65b80560fd5252d993388a7879f92b63cd41b43906aaee4f35b54cfbff87270`
-	v2 Content-Length: 12.3 MB (12331397 bytes)

#### `94626086051a15269a5cccb21f82c9c171f24b590ef37b3296f318890e26b772`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:25:36 GMT
-	Parent Layer: `069f924fa52b583ba694badc608c9e2e3fe6c600d42c99eaedab317ac1fd5ef8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:slim`

```console
$ docker pull library/node@sha256:765a93815b00ee6e6c5a2b061f43f101f99630db6bfd82555325c4c3a9de7ef3
```

-	Total Virtual Size: 207.4 MB (207360811 bytes)
-	Total v2 Content-Length: 82.3 MB (82260276 bytes)

### Layers (8)

#### `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`

```dockerfile
ADD file:b5391cb13172fb513dbfca0b8471ea02bffa913ffdab94ad864d892d129318c6 in /
```

-	Created: Tue, 01 Mar 2016 18:51:11 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125110803 bytes)
-	v2 Blob: `sha256:fdd5d7827f33ef075f45262a0f74ac96ec8a5e687faeb40135319764963dcb42`
-	v2 Content-Length: 51.4 MB (51367715 bytes)

#### `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:51:14 GMT
-	Parent Layer: `d8bd0657b25f17eef81a3d52b53da5bda4de0cf5cca3dcafec277634ae4b38fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:33 GMT
-	Parent Layer: `a582cd499e0ff0b0a2af94dbaef5f56fce1935b7c01429074c2d5abd1ea23d5a`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44315342 bytes)
-	v2 Blob: `sha256:0f35d0fe50cc8378069ab18a20a7aa65bda82e19b5caca53d21e3866d203aa07`
-	v2 Content-Length: 18.5 MB (18534098 bytes)

#### `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:06:25 GMT
-	Parent Layer: `3c3e582d88fad41cd2fc62d98ab54d4199030bff57b76a55c66b6946173909fa`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:b6c4c5059134a4e9f52b9512688dcdb3b8890b31d438b23c1b03e1d1cbc6303f`
-	v2 Content-Length: 26.9 KB (26938 bytes)

#### `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:06:26 GMT
-	Parent Layer: `e569cd081a6e285f4a1f90f513fc70dc9f1d7e5d3eb91ae4eac14fb100b59728`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `99a469d47740c5d1b63677ad9b880325a6b0eb354a5c3f108fabcf82a169fa0a`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:24:48 GMT
-	Parent Layer: `f1eef947ddacd23aefc079c83eec1f482d74eb262c4f9900f82fd32958c23af8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `069f924fa52b583ba694badc608c9e2e3fe6c600d42c99eaedab317ac1fd5ef8`

```dockerfile
RUN buildDeps='xz-utils'\
     && set -x\
     && apt-get update && apt-get install -y $buildDeps --no-install-recommends\
     && rm -rf /var/lib/apt/lists/*\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"\
     && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"\
     && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc\
     && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -\
     && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1\
     && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt\
     && apt-get purge -y --auto-remove $buildDeps
```

-	Created: Thu, 17 Mar 2016 16:25:35 GMT
-	Parent Layer: `99a469d47740c5d1b63677ad9b880325a6b0eb354a5c3f108fabcf82a169fa0a`
-	Docker Version: 1.9.1
-	Virtual Size: 37.9 MB (37882913 bytes)
-	v2 Blob: `sha256:e65b80560fd5252d993388a7879f92b63cd41b43906aaee4f35b54cfbff87270`
-	v2 Content-Length: 12.3 MB (12331397 bytes)

#### `94626086051a15269a5cccb21f82c9c171f24b590ef37b3296f318890e26b772`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:25:36 GMT
-	Parent Layer: `069f924fa52b583ba694badc608c9e2e3fe6c600d42c99eaedab317ac1fd5ef8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5.9.0-wheezy`

```console
$ docker pull library/node@sha256:1599e68b80a5377a4f441f1d3dbd0037dcee842efbedb43a553e2f51399b68d6
```

-	Total Virtual Size: 497.3 MB (497306074 bytes)
-	Total v2 Content-Length: 187.9 MB (187871950 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:07:33 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1184a715d033122986923020fbb1c116e0c84fde82ad573c1b7988a670d5187a`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:26:24 GMT
-	Parent Layer: `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `fde9f34af8c47d1a5826d8c8206877ef237fbf60d750074ebe247ef181a60529`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:26:31 GMT
-	Parent Layer: `1184a715d033122986923020fbb1c116e0c84fde82ad573c1b7988a670d5187a`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:c84126925987645dec4b8ff691abe79aad90116547a48216bfee1048824c6b50`
-	v2 Content-Length: 12.3 MB (12252291 bytes)

#### `3239586e6a4fd24ddb667b572249125091195e9da292396853a40572df3d88e3`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:26:33 GMT
-	Parent Layer: `fde9f34af8c47d1a5826d8c8206877ef237fbf60d750074ebe247ef181a60529`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5.9-wheezy`

```console
$ docker pull library/node@sha256:a95bb5b911127f8885aea7fbbb97c3fe573881684e7ed232baad89232bdaca12
```

-	Total Virtual Size: 497.3 MB (497306074 bytes)
-	Total v2 Content-Length: 187.9 MB (187871950 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:07:33 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1184a715d033122986923020fbb1c116e0c84fde82ad573c1b7988a670d5187a`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:26:24 GMT
-	Parent Layer: `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `fde9f34af8c47d1a5826d8c8206877ef237fbf60d750074ebe247ef181a60529`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:26:31 GMT
-	Parent Layer: `1184a715d033122986923020fbb1c116e0c84fde82ad573c1b7988a670d5187a`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:c84126925987645dec4b8ff691abe79aad90116547a48216bfee1048824c6b50`
-	v2 Content-Length: 12.3 MB (12252291 bytes)

#### `3239586e6a4fd24ddb667b572249125091195e9da292396853a40572df3d88e3`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:26:33 GMT
-	Parent Layer: `fde9f34af8c47d1a5826d8c8206877ef237fbf60d750074ebe247ef181a60529`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:5-wheezy`

```console
$ docker pull library/node@sha256:a2210f5f790333f463de2eedffb83208a865be6569a8f217a65fdce41534bba2
```

-	Total Virtual Size: 497.3 MB (497306074 bytes)
-	Total v2 Content-Length: 187.9 MB (187871950 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:07:33 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1184a715d033122986923020fbb1c116e0c84fde82ad573c1b7988a670d5187a`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:26:24 GMT
-	Parent Layer: `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `fde9f34af8c47d1a5826d8c8206877ef237fbf60d750074ebe247ef181a60529`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:26:31 GMT
-	Parent Layer: `1184a715d033122986923020fbb1c116e0c84fde82ad573c1b7988a670d5187a`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:c84126925987645dec4b8ff691abe79aad90116547a48216bfee1048824c6b50`
-	v2 Content-Length: 12.3 MB (12252291 bytes)

#### `3239586e6a4fd24ddb667b572249125091195e9da292396853a40572df3d88e3`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:26:33 GMT
-	Parent Layer: `fde9f34af8c47d1a5826d8c8206877ef237fbf60d750074ebe247ef181a60529`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

## `node:wheezy`

```console
$ docker pull library/node@sha256:dde5383e07beab256c41305552ca414039ab631bc046600d1bbf0cebf42c0b4a
```

-	Total Virtual Size: 497.3 MB (497306074 bytes)
-	Total v2 Content-Length: 187.9 MB (187871950 bytes)

### Layers (10)

#### `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`

```dockerfile
ADD file:73c2f06a3259420bc07e1b956b33721e4358cbd68533e021b6d888545859c5d5 in /
```

-	Created: Tue, 01 Mar 2016 18:52:03 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 84.9 MB (84906260 bytes)
-	v2 Blob: `sha256:4d690fa986553fb89f8ea3131e923ed9470d7a863add7991ea547805d5cab0d4`
-	v2 Content-Length: 37.2 MB (37190628 bytes)

#### `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 01 Mar 2016 18:52:06 GMT
-	Parent Layer: `002a4599f1ba54b8cd359ee3a01f936c16b7beeb0d38cbed43229cdbe93a25ea`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:56:55 GMT
-	Parent Layer: `43d31a5a4c8c063e9711cde1b0a9f7b1721ff133e72f61b50ed3b8128feb0ed5`
-	Docker Version: 1.9.1
-	Virtual Size: 14.2 MB (14187318 bytes)
-	v2 Blob: `sha256:5372f1e24e33826263d9fe6e8b732232aadd8d6e8051fbba0246af344dad40be`
-	v2 Content-Length: 6.7 MB (6729273 bytes)

#### `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 18:58:56 GMT
-	Parent Layer: `f32fbd7fff2e40cd21c82b726152f352021f16016aada2db6a77dda400045ada`
-	Docker Version: 1.9.1
-	Virtual Size: 110.0 MB (110026607 bytes)
-	v2 Blob: `sha256:e6e4db7c3583498ce25903846cc636d5adfc54e912c43d46e19556a0799371fa`
-	v2 Content-Length: 37.4 MB (37365585 bytes)

#### `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 01 Mar 2016 19:02:29 GMT
-	Parent Layer: `61be0c81cc289935f157f07b2efe5dfb0f722796aa7e0d65cfbe3202d4baa032`
-	Docker Version: 1.9.1
-	Virtual Size: 250.6 MB (250594554 bytes)
-	v2 Blob: `sha256:b20fa92dff5bddb9ac8b23bf2c44cbcb4546e6b8d9247963006d3245449eec74`
-	v2 Content-Length: 94.3 MB (94307104 bytes)

#### `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D\
     B9AE9905FFD7803F25714661B63B535A4C206CA9\
     C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key";   done
```

-	Created: Wed, 02 Mar 2016 11:02:29 GMT
-	Parent Layer: `e3b5d15a56b42d65657451f398151cc01f433d4e1769753789af97941fadcc1d`
-	Docker Version: 1.9.1
-	Virtual Size: 51.8 KB (51753 bytes)
-	v2 Blob: `sha256:a8741d87c480ef6191949f35c23d0429a6badeb6e57f79756c565445040bda57`
-	v2 Content-Length: 26.9 KB (26941 bytes)

#### `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Wed, 02 Mar 2016 11:07:33 GMT
-	Parent Layer: `0136f791aa4f6a5ba77d9cea75b84f39bdc6a9b1bc3a0e655b1313d7a3d70746`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `1184a715d033122986923020fbb1c116e0c84fde82ad573c1b7988a670d5187a`

```dockerfile
ENV NODE_VERSION=5.9.0
```

-	Created: Thu, 17 Mar 2016 16:26:24 GMT
-	Parent Layer: `99147447a0153801358fd76e279593ef644561a1377646e478a1499b4816783c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B

#### `fde9f34af8c47d1a5826d8c8206877ef237fbf60d750074ebe247ef181a60529`

```dockerfile
RUN curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz"   && curl -SLO "https://nodejs.org/dist/v$NODE_VERSION/SHASUMS256.txt.asc"   && gpg --batch --decrypt --output SHASUMS256.txt SHASUMS256.txt.asc   && grep " node-v$NODE_VERSION-linux-x64.tar.xz\$" SHASUMS256.txt | sha256sum -c -   && tar -xJf "node-v$NODE_VERSION-linux-x64.tar.xz" -C /usr/local --strip-components=1   && rm "node-v$NODE_VERSION-linux-x64.tar.xz" SHASUMS256.txt.asc SHASUMS256.txt
```

-	Created: Thu, 17 Mar 2016 16:26:31 GMT
-	Parent Layer: `1184a715d033122986923020fbb1c116e0c84fde82ad573c1b7988a670d5187a`
-	Docker Version: 1.9.1
-	Virtual Size: 37.5 MB (37539582 bytes)
-	v2 Blob: `sha256:c84126925987645dec4b8ff691abe79aad90116547a48216bfee1048824c6b50`
-	v2 Content-Length: 12.3 MB (12252291 bytes)

#### `3239586e6a4fd24ddb667b572249125091195e9da292396853a40572df3d88e3`

```dockerfile
CMD ["node"]
```

-	Created: Thu, 17 Mar 2016 16:26:33 GMT
-	Parent Layer: `fde9f34af8c47d1a5826d8c8206877ef237fbf60d750074ebe247ef181a60529`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
