
## Overview

| Image reference | `bogusrj/imagem-caotica:v1`        | `bogusrj/imagem-caotica:v3`        |
|-----------------|---------------------------|---------------------------|
| - digest        | `546951e93c0f` | `fc1422398012` |
| - vulnerabilities | <img alt="critical: 2" src="https://img.shields.io/badge/critical-2-8b1924"/> <img alt="high: 20" src="https://img.shields.io/badge/high-20-e25d68"/> <img alt="medium: 29" src="https://img.shields.io/badge/medium-29-fbb552"/> <img alt="low: 92" src="https://img.shields.io/badge/low-92-fce1a9"/> <img alt="unspecified: 6" src="https://img.shields.io/badge/unspecified-6-lightgrey"/> | <img alt="critical: 0" src="https://img.shields.io/badge/critical-0-lightgrey"/> <img alt="high: 2" src="https://img.shields.io/badge/high-2-e25d68"/> <img alt="medium: 3" src="https://img.shields.io/badge/medium-3-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/low-0-lightgrey"/> <img alt="unspecified: 1" src="https://img.shields.io/badge/unspecified-1-lightgrey"/> |
| - platform | linux/amd64 | linux/amd64 |
| - size | 451 MB | 61 MB (-390 MB) |
| - packages | 827 | 281 (-546) |
| **Base Image** | `node:18`<br/>also known as:<br/>• <code>18-bookworm</code><br/>• <code>hydrogen</code><br/>• <code>hydrogen-bookworm</code><br/>• <code>lts</code><br/>• <code>lts-bookworm</code> | `node:22-alpine3.18`<br/>also known as:<br/>• <code>22.2-alpine3.18</code><br/>• <code>22.2.0-alpine3.18</code><br/>• <code>alpine3.18</code><br/>• <code>current-alpine3.18</code> |
| - vulnerabilities | <img alt="critical: 3" src="https://img.shields.io/badge/critical-3-8b1924"/> <img alt="high: 22" src="https://img.shields.io/badge/high-22-e25d68"/> <img alt="medium: 28" src="https://img.shields.io/badge/medium-28-fbb552"/> <img alt="low: 93" src="https://img.shields.io/badge/low-93-fce1a9"/> <img alt="unspecified: 7" src="https://img.shields.io/badge/unspecified-7-lightgrey"/> | <img alt="critical: 0" src="https://img.shields.io/badge/critical-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/high-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/medium-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/low-0-lightgrey"/> <img alt="unspecified: 1" src="https://img.shields.io/badge/unspecified-1-lightgrey"/> |

<details><summary><strong>Environment Variables</strong> (1 changes)</summary>

> * `±` 1 changed
> * _2 unchanged_


```diff
-NODE_VERSION=18.16.0
+NODE_VERSION=22.2.0
 PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
 YARN_VERSION=1.22.19
```


</details>





<details><summary><strong>Packages and Vulnerabilities</strong> (734 package changes and 147 vulnerability changes)</summary>

> * :heavy_plus_sign: 49 packages added
> * :heavy_minus_sign: 589 packages removed
> * :infinity: 96 packages changed
> * 112 packages unchanged


> * :heavy_exclamation_mark: 2 vulnerabilities added
> * :heavy_check_mark: 145 vulnerabilities removed
<details><summary>Changes for packages of type <code>apk</code> (22 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v1</code></th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v3</code></th>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>alpine-baselayout</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.4.3-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>alpine-baselayout-data</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.4.3-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>alpine-keys</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.4-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>apk-tools</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.14.0-r2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>busybox</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.36.1-r5</code></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"></td>
		<td valign="top"><strong>Added vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2023--42366" src="https://img.shields.io/badge/CVE--2023--42366-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
	</tr><tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>busybox-binsh</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.36.1-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ca-certificates</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>20230506-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ca-certificates-bundle</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>20230506-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>gcc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>12.2.1_git20220924-r10</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libc-dev</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.7.2-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libc-utils</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.7.2-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libcrypto3</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.4-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libgcc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>12.2.1_git20220924-r10</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libssl3</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.4-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libstdc++</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>12.2.1_git20220924-r10</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>musl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2.4-r2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>musl-utils</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2.4-r2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>openssl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.4-r5</code></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <img alt="unspecified: 1" src="https://img.shields.io/badge/U-1-lightgrey"/></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"></td>
		<td valign="top"><strong>Added vulnerabilities (1):</strong><br/><ul><li><img alt="unspecified : CVE--2024--2511" src="https://img.shields.io/badge/CVE--2024--2511-lightgrey?label=unspecified%20&labelColor=lightgrey"/></li></ul></td>
	</tr><tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>pax-utils</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.3.7-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>scanelf</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.3.7-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ssl_client</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.36.1-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>zlib</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2.13-r1</code></td>
	</tr>
	
</table>
</details>
<details><summary>Changes for packages of type <code>deb</code> (545 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v1</code></th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v3</code></th>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>acl</strong></td>
		<td valign="top"><code>2.3.1-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>adduser</strong></td>
		<td valign="top"><code>3.134</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>aom</strong></td>
		<td valign="top"><code>3.6.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>apr</strong></td>
		<td valign="top"><code>1.7.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>apr-util</strong></td>
		<td valign="top"><code>1.6.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>apt</strong></td>
		<td valign="top"><code>2.6.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2011--3374" src="https://img.shields.io/badge/CVE--2011--3374-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>attr</strong></td>
		<td valign="top"><code>1:2.5.1-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>audit</strong></td>
		<td valign="top"><code>1:3.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>autoconf</strong></td>
		<td valign="top"><code>2.71-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>automake</strong></td>
		<td valign="top"><code>1:1.16.5-1.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>automake-1.16</strong></td>
		<td valign="top"><code>1:1.16.5-1.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>autotools-dev</strong></td>
		<td valign="top"><code>20220109.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>base-files</strong></td>
		<td valign="top"><code>12.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>base-passwd</strong></td>
		<td valign="top"><code>3.6.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>bash</strong></td>
		<td valign="top"><code>5.2.15-2+b2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>binutils</strong></td>
		<td valign="top"><code>2.40-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 7" src="https://img.shields.io/badge/L-7-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (7):</strong><br/><ul><li><img alt="low : CVE--2023--1972" src="https://img.shields.io/badge/CVE--2023--1972-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2021--32256" src="https://img.shields.io/badge/CVE--2021--32256-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--9996" src="https://img.shields.io/badge/CVE--2018--9996-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--20712" src="https://img.shields.io/badge/CVE--2018--20712-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--20673" src="https://img.shields.io/badge/CVE--2018--20673-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--18483" src="https://img.shields.io/badge/CVE--2018--18483-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2017--13716" src="https://img.shields.io/badge/CVE--2017--13716-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>binutils-common</strong></td>
		<td valign="top"><code>2.40-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>binutils-x86-64-linux-gnu</strong></td>
		<td valign="top"><code>2.40-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>brotli</strong></td>
		<td valign="top"><code>1.0.9-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>bsdutils</strong></td>
		<td valign="top"><code>1:2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>bzip2</strong></td>
		<td valign="top"><code>1.0.8-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ca-certificates</strong></td>
		<td valign="top"><code>20230311</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>cairo</strong></td>
		<td valign="top"><code>1.16.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>cdebconf</strong></td>
		<td valign="top"><code>0.270</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>comerr-dev</strong></td>
		<td valign="top"><code>2.1-1.47.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>coreutils</strong></td>
		<td valign="top"><code>9.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2017--18018" src="https://img.shields.io/badge/CVE--2017--18018-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>cpp</strong></td>
		<td valign="top"><code>4:12.2.0-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>cpp-12</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>curl</strong></td>
		<td valign="top"><code>7.88.1-10</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (5):</strong><br/><ul><li><img alt="medium : CVE--2023--46218" src="https://img.shields.io/badge/CVE--2023--46218-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="low : CVE--2023--38546" src="https://img.shields.io/badge/CVE--2023--38546-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--46219" src="https://img.shields.io/badge/CVE--2023--46219-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--38545" src="https://img.shields.io/badge/CVE--2023--38545-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--38039" src="https://img.shields.io/badge/CVE--2023--38039-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>cyrus-sasl2</strong></td>
		<td valign="top"><code>2.1.28+dfsg-10</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>dash</strong></td>
		<td valign="top"><code>0.5.12-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>dav1d</strong></td>
		<td valign="top"><code>1.0.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2024--1580" src="https://img.shields.io/badge/CVE--2024--1580-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>db-defaults</strong></td>
		<td valign="top"><code>5.3.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>db5.3</strong></td>
		<td valign="top"><code>5.3.28+dfsg2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>debconf</strong></td>
		<td valign="top"><code>1.5.82</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>debian-archive-keyring</strong></td>
		<td valign="top"><code>2023.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>debianutils</strong></td>
		<td valign="top"><code>5.7-0.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>default-libmysqlclient-dev</strong></td>
		<td valign="top"><code>1.1.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>diffutils</strong></td>
		<td valign="top"><code>1:3.8-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>dirmngr</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>djvulibre</strong></td>
		<td valign="top"><code>3.5.28-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>dpkg</strong></td>
		<td valign="top"><code>1.21.22</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>dpkg-dev</strong></td>
		<td valign="top"><code>1.21.22</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>e2fsprogs</strong></td>
		<td valign="top"><code>1.47.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>elfutils</strong></td>
		<td valign="top"><code>0.188-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2024--25260" src="https://img.shields.io/badge/CVE--2024--25260-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>expat</strong></td>
		<td valign="top"><code>2.5.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="low : CVE--2024--28757" src="https://img.shields.io/badge/CVE--2024--28757-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--52426" src="https://img.shields.io/badge/CVE--2023--52426-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fftw3</strong></td>
		<td valign="top"><code>3.3.10-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>file</strong></td>
		<td valign="top"><code>1:5.44-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>findutils</strong></td>
		<td valign="top"><code>4.9.0-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fontconfig</strong></td>
		<td valign="top"><code>2.14.1-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fontconfig-config</strong></td>
		<td valign="top"><code>2.14.1-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fonts-dejavu</strong></td>
		<td valign="top"><code>2.37-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fonts-dejavu-core</strong></td>
		<td valign="top"><code>2.37-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>freetype</strong></td>
		<td valign="top"><code>2.12.1+dfsg-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fribidi</strong></td>
		<td valign="top"><code>1.0.8-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>g++</strong></td>
		<td valign="top"><code>4:12.2.0-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>g++-12</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gcc</strong></td>
		<td valign="top"><code>4:12.2.0-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gcc-12</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2022--27943" src="https://img.shields.io/badge/CVE--2022--27943-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gcc-12-base</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gcc-defaults</strong></td>
		<td valign="top"><code>1.203</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gdbm</strong></td>
		<td valign="top"><code>1.23-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gdk-pixbuf</strong></td>
		<td valign="top"><code>2.42.10+dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gir1.2-freedesktop</strong></td>
		<td valign="top"><code>1.74.0-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gir1.2-gdkpixbuf-2.0</strong></td>
		<td valign="top"><code>2.42.10+dfsg-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gir1.2-glib-2.0</strong></td>
		<td valign="top"><code>1.74.0-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gir1.2-rsvg-2.0</strong></td>
		<td valign="top"><code>2.54.5+dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>git</strong></td>
		<td valign="top"><code>1:2.39.2-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 1" src="https://img.shields.io/badge/C-1-8b1924"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (7):</strong><br/><ul><li><img alt="critical : CVE--2024--32002" src="https://img.shields.io/badge/CVE--2024--32002-lightgrey?label=critical%20&labelColor=8b1924"/></li><li><img alt="high : CVE--2024--32004" src="https://img.shields.io/badge/CVE--2024--32004-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2024--32465" src="https://img.shields.io/badge/CVE--2024--32465-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="low : CVE--2024--32021" src="https://img.shields.io/badge/CVE--2024--32021-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2024--32020" src="https://img.shields.io/badge/CVE--2024--32020-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2022--24975" src="https://img.shields.io/badge/CVE--2022--24975-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--1000021" src="https://img.shields.io/badge/CVE--2018--1000021-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>git-man</strong></td>
		<td valign="top"><code>1:2.39.2-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>glib2.0</strong></td>
		<td valign="top"><code>2.74.6-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <img alt="unspecified: 1" src="https://img.shields.io/badge/U-1-lightgrey"/></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="low : CVE--2012--0039" src="https://img.shields.io/badge/CVE--2012--0039-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="unspecified : CVE--2024--34397" src="https://img.shields.io/badge/CVE--2024--34397-lightgrey?label=unspecified%20&labelColor=lightgrey"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>glibc</strong></td>
		<td valign="top"><code>2.36-9</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 3" src="https://img.shields.io/badge/H-3-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 5" src="https://img.shields.io/badge/L-5-fce1a9"/> <img alt="unspecified: 2" src="https://img.shields.io/badge/U-2-lightgrey"/></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (11):</strong><br/><ul><li><img alt="high : CVE--2024--33602" src="https://img.shields.io/badge/CVE--2024--33602-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2024--33601" src="https://img.shields.io/badge/CVE--2024--33601-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2024--2961" src="https://img.shields.io/badge/CVE--2024--2961-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="medium : CVE--2023--4806" src="https://img.shields.io/badge/CVE--2023--4806-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="low : CVE--2023--6780" src="https://img.shields.io/badge/CVE--2023--6780-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--6779" src="https://img.shields.io/badge/CVE--2023--6779-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--6246" src="https://img.shields.io/badge/CVE--2023--6246-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--4911" src="https://img.shields.io/badge/CVE--2023--4911-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--4527" src="https://img.shields.io/badge/CVE--2023--4527-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="unspecified : CVE--2024--33600" src="https://img.shields.io/badge/CVE--2024--33600-lightgrey?label=unspecified%20&labelColor=lightgrey"/></li><li><img alt="unspecified : CVE--2024--33599" src="https://img.shields.io/badge/CVE--2024--33599-lightgrey?label=unspecified%20&labelColor=lightgrey"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gmp</strong></td>
		<td valign="top"><code>2:6.2.1+dfsg1-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gnupg</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gnupg-l10n</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gnupg-utils</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gnupg2</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2022--3219" src="https://img.shields.io/badge/CVE--2022--3219-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gnutls28</strong></td>
		<td valign="top"><code>3.7.9-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (3):</strong><br/><ul><li><img alt="high : CVE--2024--0553" src="https://img.shields.io/badge/CVE--2024--0553-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="medium : CVE--2023--5981" src="https://img.shields.io/badge/CVE--2023--5981-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="low : CVE--2024--0567" src="https://img.shields.io/badge/CVE--2024--0567-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gobject-introspection</strong></td>
		<td valign="top"><code>1.74.0-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gpg</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gpg-agent</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gpg-wks-client</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gpg-wks-server</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gpgconf</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gpgsm</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gpgv</strong></td>
		<td valign="top"><code>2.2.40-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>graphite2</strong></td>
		<td valign="top"><code>1.3.14-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>grep</strong></td>
		<td valign="top"><code>3.8-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gzip</strong></td>
		<td valign="top"><code>1.12-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>harfbuzz</strong></td>
		<td valign="top"><code>6.0.0+dfsg-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>hicolor-icon-theme</strong></td>
		<td valign="top"><code>0.17-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>hostname</strong></td>
		<td valign="top"><code>3.23+nmu1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>icu</strong></td>
		<td valign="top"><code>72.1-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>icu-devtools</strong></td>
		<td valign="top"><code>72.1-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>imagemagick</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 3" src="https://img.shields.io/badge/M-3-fbb552"/> <img alt="low: 13" src="https://img.shields.io/badge/L-13-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (16):</strong><br/><ul><li><img alt="medium : CVE--2023--5341" src="https://img.shields.io/badge/CVE--2023--5341-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2023--34151" src="https://img.shields.io/badge/CVE--2023--34151-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2023--1289" src="https://img.shields.io/badge/CVE--2023--1289-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="low : CVE--2023--3428" src="https://img.shields.io/badge/CVE--2023--3428-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--34152" src="https://img.shields.io/badge/CVE--2023--34152-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--1906" src="https://img.shields.io/badge/CVE--2023--1906-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2022--1115" src="https://img.shields.io/badge/CVE--2022--1115-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2021--3610" src="https://img.shields.io/badge/CVE--2021--3610-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2021--20311" src="https://img.shields.io/badge/CVE--2021--20311-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--15607" src="https://img.shields.io/badge/CVE--2018--15607-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2017--7275" src="https://img.shields.io/badge/CVE--2017--7275-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2017--11755" src="https://img.shields.io/badge/CVE--2017--11755-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2017--11754" src="https://img.shields.io/badge/CVE--2017--11754-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--8678" src="https://img.shields.io/badge/CVE--2016--8678-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2008--3134" src="https://img.shields.io/badge/CVE--2008--3134-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2005--0406" src="https://img.shields.io/badge/CVE--2005--0406-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>imagemagick-6-common</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>imagemagick-6.q16</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>imath</strong></td>
		<td valign="top"><code>3.1.6-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>init-system-helpers</strong></td>
		<td valign="top"><code>1.65.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>isl</strong></td>
		<td valign="top"><code>0.25-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>jansson</strong></td>
		<td valign="top"><code>2.14-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2020--36325" src="https://img.shields.io/badge/CVE--2020--36325-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>jbigkit</strong></td>
		<td valign="top"><code>2.1-6.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2017--9937" src="https://img.shields.io/badge/CVE--2017--9937-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>keyutils</strong></td>
		<td valign="top"><code>1.6.3-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>krb5</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2023--36054" src="https://img.shields.io/badge/CVE--2023--36054-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>krb5-multidev</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>lcms2</strong></td>
		<td valign="top"><code>2.14-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>lerc</strong></td>
		<td valign="top"><code>4.0.0+ds-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libacl1</strong></td>
		<td valign="top"><code>2.3.1-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libaom3</strong></td>
		<td valign="top"><code>3.6.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libapr1</strong></td>
		<td valign="top"><code>1.7.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libaprutil1</strong></td>
		<td valign="top"><code>1.6.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libapt-pkg6.0</strong></td>
		<td valign="top"><code>2.6.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libasan8</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libassuan</strong></td>
		<td valign="top"><code>2.5.5-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libassuan0</strong></td>
		<td valign="top"><code>2.5.5-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libatomic1</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libattr1</strong></td>
		<td valign="top"><code>1:2.5.1-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libaudit-common</strong></td>
		<td valign="top"><code>1:3.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libaudit1</strong></td>
		<td valign="top"><code>1:3.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbinutils</strong></td>
		<td valign="top"><code>2.40-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libblkid-dev</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libblkid1</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbrotli-dev</strong></td>
		<td valign="top"><code>1.0.9-2+b6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbrotli1</strong></td>
		<td valign="top"><code>1.0.9-2+b6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbsd</strong></td>
		<td valign="top"><code>0.11.7-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbsd0</strong></td>
		<td valign="top"><code>0.11.7-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbz2-1.0</strong></td>
		<td valign="top"><code>1.0.8-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbz2-dev</strong></td>
		<td valign="top"><code>1.0.8-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libc-bin</strong></td>
		<td valign="top"><code>2.36-9</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libc-dev-bin</strong></td>
		<td valign="top"><code>2.36-9</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libc6</strong></td>
		<td valign="top"><code>2.36-9</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libc6-dev</strong></td>
		<td valign="top"><code>2.36-9</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcairo-gobject2</strong></td>
		<td valign="top"><code>1.16.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcairo-script-interpreter2</strong></td>
		<td valign="top"><code>1.16.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcairo2</strong></td>
		<td valign="top"><code>1.16.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcairo2-dev</strong></td>
		<td valign="top"><code>1.16.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcap-ng</strong></td>
		<td valign="top"><code>0.8.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcap-ng0</strong></td>
		<td valign="top"><code>0.8.3-1+b3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcap2</strong></td>
		<td valign="top"><code>1:2.66-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcbor</strong></td>
		<td valign="top"><code>0.8.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcbor0.8</strong></td>
		<td valign="top"><code>0.8.0-2+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcc1-0</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcom-err2</strong></td>
		<td valign="top"><code>1.47.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcrypt-dev</strong></td>
		<td valign="top"><code>1:4.4.33-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcrypt1</strong></td>
		<td valign="top"><code>1:4.4.33-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libctf-nobfd0</strong></td>
		<td valign="top"><code>2.40-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libctf0</strong></td>
		<td valign="top"><code>2.40-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcurl3-gnutls</strong></td>
		<td valign="top"><code>7.88.1-10</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcurl4</strong></td>
		<td valign="top"><code>7.88.1-10</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcurl4-openssl-dev</strong></td>
		<td valign="top"><code>7.88.1-10</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdatrie</strong></td>
		<td valign="top"><code>0.2.13-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdatrie1</strong></td>
		<td valign="top"><code>0.2.13-2+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdav1d6</strong></td>
		<td valign="top"><code>1.0.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdb-dev</strong></td>
		<td valign="top"><code>5.3.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdb5.3</strong></td>
		<td valign="top"><code>5.3.28+dfsg2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdb5.3-dev</strong></td>
		<td valign="top"><code>5.3.28+dfsg2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libde265</strong></td>
		<td valign="top"><code>1.0.11-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 5" src="https://img.shields.io/badge/H-5-e25d68"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (7):</strong><br/><ul><li><img alt="high : CVE--2023--49468" src="https://img.shields.io/badge/CVE--2023--49468-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2023--49467" src="https://img.shields.io/badge/CVE--2023--49467-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2023--49465" src="https://img.shields.io/badge/CVE--2023--49465-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2023--27103" src="https://img.shields.io/badge/CVE--2023--27103-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2023--43887" src="https://img.shields.io/badge/CVE--2023--43887-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="medium : CVE--2023--47471" src="https://img.shields.io/badge/CVE--2023--47471-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2023--27102" src="https://img.shields.io/badge/CVE--2023--27102-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libde265-0</strong></td>
		<td valign="top"><code>1.0.11-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdebconfclient0</strong></td>
		<td valign="top"><code>0.270</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdeflate</strong></td>
		<td valign="top"><code>1.14-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdeflate-dev</strong></td>
		<td valign="top"><code>1.14-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdeflate0</strong></td>
		<td valign="top"><code>1.14-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdjvulibre-dev</strong></td>
		<td valign="top"><code>3.5.28-2+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdjvulibre-text</strong></td>
		<td valign="top"><code>3.5.28-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdjvulibre21</strong></td>
		<td valign="top"><code>3.5.28-2+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdpkg-perl</strong></td>
		<td valign="top"><code>1.21.22</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libedit</strong></td>
		<td valign="top"><code>3.1-20221030-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libedit2</strong></td>
		<td valign="top"><code>3.1-20221030-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libelf1</strong></td>
		<td valign="top"><code>0.188-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liberror-perl</strong></td>
		<td valign="top"><code>0.17029-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libevent</strong></td>
		<td valign="top"><code>2.1.12-stable-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libevent-2.1-7</strong></td>
		<td valign="top"><code>2.1.12-stable-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libevent-core-2.1-7</strong></td>
		<td valign="top"><code>2.1.12-stable-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libevent-dev</strong></td>
		<td valign="top"><code>2.1.12-stable-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libevent-extra-2.1-7</strong></td>
		<td valign="top"><code>2.1.12-stable-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libevent-openssl-2.1-7</strong></td>
		<td valign="top"><code>2.1.12-stable-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libevent-pthreads-2.1-7</strong></td>
		<td valign="top"><code>2.1.12-stable-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libexif</strong></td>
		<td valign="top"><code>0.6.24-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libexif-dev</strong></td>
		<td valign="top"><code>0.6.24-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libexif12</strong></td>
		<td valign="top"><code>0.6.24-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libexpat1</strong></td>
		<td valign="top"><code>2.5.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libexpat1-dev</strong></td>
		<td valign="top"><code>2.5.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libext2fs2</strong></td>
		<td valign="top"><code>1.47.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libffi</strong></td>
		<td valign="top"><code>3.4.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libffi-dev</strong></td>
		<td valign="top"><code>3.4.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libffi8</strong></td>
		<td valign="top"><code>3.4.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfftw3-double3</strong></td>
		<td valign="top"><code>3.3.10-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfido2</strong></td>
		<td valign="top"><code>1.12.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfido2-1</strong></td>
		<td valign="top"><code>1.12.0-2+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfontconfig-dev</strong></td>
		<td valign="top"><code>2.14.1-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfontconfig1</strong></td>
		<td valign="top"><code>2.14.1-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfreetype-dev</strong></td>
		<td valign="top"><code>2.12.1+dfsg-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfreetype6</strong></td>
		<td valign="top"><code>2.12.1+dfsg-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfreetype6-dev</strong></td>
		<td valign="top"><code>2.12.1+dfsg-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfribidi0</strong></td>
		<td valign="top"><code>1.0.8-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgcc-12-dev</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgcc-s1</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgcrypt20</strong></td>
		<td valign="top"><code>1.10.1-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2018--6829" src="https://img.shields.io/badge/CVE--2018--6829-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdbm-compat4</strong></td>
		<td valign="top"><code>1.23-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdbm-dev</strong></td>
		<td valign="top"><code>1.23-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdbm6</strong></td>
		<td valign="top"><code>1.23-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdk-pixbuf-2.0-0</strong></td>
		<td valign="top"><code>2.42.10+dfsg-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdk-pixbuf-2.0-dev</strong></td>
		<td valign="top"><code>2.42.10+dfsg-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdk-pixbuf2.0-bin</strong></td>
		<td valign="top"><code>2.42.10+dfsg-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdk-pixbuf2.0-common</strong></td>
		<td valign="top"><code>2.42.10+dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgirepository-1.0-1</strong></td>
		<td valign="top"><code>1.74.0-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libglib2.0-0</strong></td>
		<td valign="top"><code>2.74.6-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libglib2.0-bin</strong></td>
		<td valign="top"><code>2.74.6-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libglib2.0-data</strong></td>
		<td valign="top"><code>2.74.6-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libglib2.0-dev</strong></td>
		<td valign="top"><code>2.74.6-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libglib2.0-dev-bin</strong></td>
		<td valign="top"><code>2.74.6-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgmp-dev</strong></td>
		<td valign="top"><code>2:6.2.1+dfsg1-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgmp10</strong></td>
		<td valign="top"><code>2:6.2.1+dfsg1-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgmpxx4ldbl</strong></td>
		<td valign="top"><code>2:6.2.1+dfsg1-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgnutls30</strong></td>
		<td valign="top"><code>3.7.9-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgomp1</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgpg-error</strong></td>
		<td valign="top"><code>1.46-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgpg-error0</strong></td>
		<td valign="top"><code>1.46-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgprofng0</strong></td>
		<td valign="top"><code>2.40-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgraphite2-3</strong></td>
		<td valign="top"><code>1.3.14-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgssapi-krb5-2</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgssrpc4</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libharfbuzz0b</strong></td>
		<td valign="top"><code>6.0.0+dfsg-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libheif</strong></td>
		<td valign="top"><code>1.15.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2024--25269" src="https://img.shields.io/badge/CVE--2024--25269-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libheif1</strong></td>
		<td valign="top"><code>1.15.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libhogweed6</strong></td>
		<td valign="top"><code>3.8.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libice</strong></td>
		<td valign="top"><code>2:1.0.10-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libice-dev</strong></td>
		<td valign="top"><code>2:1.0.10-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libice6</strong></td>
		<td valign="top"><code>2:1.0.10-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libicu-dev</strong></td>
		<td valign="top"><code>72.1-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libicu72</strong></td>
		<td valign="top"><code>72.1-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libidn2</strong></td>
		<td valign="top"><code>2.3.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libidn2-0</strong></td>
		<td valign="top"><code>2.3.3-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libimath-3-1-29</strong></td>
		<td valign="top"><code>3.1.6-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libimath-dev</strong></td>
		<td valign="top"><code>3.1.6-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libisl23</strong></td>
		<td valign="top"><code>0.25-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libitm1</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjansson4</strong></td>
		<td valign="top"><code>2.14-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjbig-dev</strong></td>
		<td valign="top"><code>2.1-6.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjbig0</strong></td>
		<td valign="top"><code>2.1-6.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjpeg-dev</strong></td>
		<td valign="top"><code>1:2.1.5-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjpeg-turbo</strong></td>
		<td valign="top"><code>1:2.1.5-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjpeg62-turbo</strong></td>
		<td valign="top"><code>1:2.1.5-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjpeg62-turbo-dev</strong></td>
		<td valign="top"><code>1:2.1.5-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libk5crypto3</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkadm5clnt-mit12</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkadm5srv-mit12</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkdb5-10</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkeyutils1</strong></td>
		<td valign="top"><code>1.6.3-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkrb5-3</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkrb5-dev</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkrb5support0</strong></td>
		<td valign="top"><code>1.20.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libksba</strong></td>
		<td valign="top"><code>1.6.3-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libksba8</strong></td>
		<td valign="top"><code>1.6.3-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblcms2-2</strong></td>
		<td valign="top"><code>2.14-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblcms2-dev</strong></td>
		<td valign="top"><code>2.14-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libldap-2.5-0</strong></td>
		<td valign="top"><code>2.5.13+dfsg-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblerc-dev</strong></td>
		<td valign="top"><code>4.0.0+ds-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblerc4</strong></td>
		<td valign="top"><code>4.0.0+ds-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblqr</strong></td>
		<td valign="top"><code>0.4.2-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblqr-1-0</strong></td>
		<td valign="top"><code>0.4.2-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblqr-1-0-dev</strong></td>
		<td valign="top"><code>0.4.2-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblsan0</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libltdl-dev</strong></td>
		<td valign="top"><code>2.4.7-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libltdl7</strong></td>
		<td valign="top"><code>2.4.7-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblz4-1</strong></td>
		<td valign="top"><code>1.9.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblzma-dev</strong></td>
		<td valign="top"><code>5.4.1-0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblzma5</strong></td>
		<td valign="top"><code>5.4.1-0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblzo2-2</strong></td>
		<td valign="top"><code>2.10-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagic-mgc</strong></td>
		<td valign="top"><code>1:5.44-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagic1</strong></td>
		<td valign="top"><code>1:5.44-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickcore-6-arch-config</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickcore-6-headers</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickcore-6.q16-6</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickcore-6.q16-6-extra</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickcore-6.q16-dev</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickcore-dev</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickwand-6-headers</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickwand-6.q16-6</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickwand-6.q16-dev</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmagickwand-dev</strong></td>
		<td valign="top"><code>8:6.9.11.60+dfsg-1.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmariadb-dev</strong></td>
		<td valign="top"><code>1:10.11.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmariadb-dev-compat</strong></td>
		<td valign="top"><code>1:10.11.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmariadb3</strong></td>
		<td valign="top"><code>1:10.11.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmaxminddb</strong></td>
		<td valign="top"><code>1.7.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmaxminddb-dev</strong></td>
		<td valign="top"><code>1.7.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmaxminddb0</strong></td>
		<td valign="top"><code>1.7.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmd</strong></td>
		<td valign="top"><code>1.0.4-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmd0</strong></td>
		<td valign="top"><code>1.0.4-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmount-dev</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmount1</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmpc3</strong></td>
		<td valign="top"><code>1.3.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmpfr6</strong></td>
		<td valign="top"><code>4.2.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libncurses-dev</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libncurses5-dev</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libncurses6</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libncursesw5-dev</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libncursesw6</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnettle8</strong></td>
		<td valign="top"><code>3.8.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnghttp2-14</strong></td>
		<td valign="top"><code>1.52.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnpth0</strong></td>
		<td valign="top"><code>1.6-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnsl</strong></td>
		<td valign="top"><code>1.3.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnsl-dev</strong></td>
		<td valign="top"><code>1.3.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnsl2</strong></td>
		<td valign="top"><code>1.3.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnuma1</strong></td>
		<td valign="top"><code>2.0.16-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libopenexr-3-1-30</strong></td>
		<td valign="top"><code>3.1.5-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libopenexr-dev</strong></td>
		<td valign="top"><code>3.1.5-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libopenjp2-7</strong></td>
		<td valign="top"><code>2.5.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libopenjp2-7-dev</strong></td>
		<td valign="top"><code>2.5.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libp11-kit0</strong></td>
		<td valign="top"><code>0.24.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpam-modules</strong></td>
		<td valign="top"><code>1.5.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpam-modules-bin</strong></td>
		<td valign="top"><code>1.5.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpam-runtime</strong></td>
		<td valign="top"><code>1.5.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpam0g</strong></td>
		<td valign="top"><code>1.5.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpango-1.0-0</strong></td>
		<td valign="top"><code>1.50.12+ds-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpangocairo-1.0-0</strong></td>
		<td valign="top"><code>1.50.12+ds-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpangoft2-1.0-0</strong></td>
		<td valign="top"><code>1.50.12+ds-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpcre2-16-0</strong></td>
		<td valign="top"><code>10.42-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpcre2-32-0</strong></td>
		<td valign="top"><code>10.42-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpcre2-8-0</strong></td>
		<td valign="top"><code>10.42-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpcre2-dev</strong></td>
		<td valign="top"><code>10.42-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpcre2-posix3</strong></td>
		<td valign="top"><code>10.42-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libperl5.36</strong></td>
		<td valign="top"><code>5.36.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpixman-1-0</strong></td>
		<td valign="top"><code>0.42.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpixman-1-dev</strong></td>
		<td valign="top"><code>0.42.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpkgconf3</strong></td>
		<td valign="top"><code>1.8.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpng-dev</strong></td>
		<td valign="top"><code>1.6.39-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpng1.6</strong></td>
		<td valign="top"><code>1.6.39-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2021--4214" src="https://img.shields.io/badge/CVE--2021--4214-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpng16-16</strong></td>
		<td valign="top"><code>1.6.39-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpq-dev</strong></td>
		<td valign="top"><code>15.3-0+deb12u1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpq5</strong></td>
		<td valign="top"><code>15.3-0+deb12u1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libproc2-0</strong></td>
		<td valign="top"><code>2:4.0.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpsl</strong></td>
		<td valign="top"><code>0.21.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpsl5</strong></td>
		<td valign="top"><code>0.21.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpthread-stubs</strong></td>
		<td valign="top"><code>0.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpthread-stubs0-dev</strong></td>
		<td valign="top"><code>0.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpython3-stdlib</strong></td>
		<td valign="top"><code>3.11.2-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpython3.11-minimal</strong></td>
		<td valign="top"><code>3.11.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpython3.11-stdlib</strong></td>
		<td valign="top"><code>3.11.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libquadmath0</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libreadline-dev</strong></td>
		<td valign="top"><code>8.2-1.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libreadline8</strong></td>
		<td valign="top"><code>8.2-1.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>librsvg</strong></td>
		<td valign="top"><code>2.54.5+dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2023--38633" src="https://img.shields.io/badge/CVE--2023--38633-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>librsvg2-2</strong></td>
		<td valign="top"><code>2.54.5+dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>librsvg2-common</strong></td>
		<td valign="top"><code>2.54.5+dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>librsvg2-dev</strong></td>
		<td valign="top"><code>2.54.5+dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>librtmp1</strong></td>
		<td valign="top"><code>2.4+20151223.gitfa8646d.1-2+b2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsasl2-2</strong></td>
		<td valign="top"><code>2.1.28+dfsg-10</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsasl2-modules-db</strong></td>
		<td valign="top"><code>2.1.28+dfsg-10</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libseccomp</strong></td>
		<td valign="top"><code>2.5.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libseccomp2</strong></td>
		<td valign="top"><code>2.5.4-1+b3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libselinux</strong></td>
		<td valign="top"><code>3.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libselinux1</strong></td>
		<td valign="top"><code>3.4-1+b6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libselinux1-dev</strong></td>
		<td valign="top"><code>3.4-1+b6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsemanage</strong></td>
		<td valign="top"><code>3.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsemanage-common</strong></td>
		<td valign="top"><code>3.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsemanage2</strong></td>
		<td valign="top"><code>3.4-1+b5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsepol</strong></td>
		<td valign="top"><code>3.4-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsepol-dev</strong></td>
		<td valign="top"><code>3.4-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsepol2</strong></td>
		<td valign="top"><code>3.4-2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libserf-1-1</strong></td>
		<td valign="top"><code>1.3.9-11</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsm</strong></td>
		<td valign="top"><code>2:1.2.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsm-dev</strong></td>
		<td valign="top"><code>2:1.2.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsm6</strong></td>
		<td valign="top"><code>2:1.2.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsmartcols1</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsqlite3-0</strong></td>
		<td valign="top"><code>3.40.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsqlite3-dev</strong></td>
		<td valign="top"><code>3.40.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libss2</strong></td>
		<td valign="top"><code>1.47.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libssh2</strong></td>
		<td valign="top"><code>1.10.0-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libssh2-1</strong></td>
		<td valign="top"><code>1.10.0-3+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libssl-dev</strong></td>
		<td valign="top"><code>3.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libssl3</strong></td>
		<td valign="top"><code>3.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libstdc++-12-dev</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libstdc++6</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsvn1</strong></td>
		<td valign="top"><code>1.14.2-4+b2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsystemd0</strong></td>
		<td valign="top"><code>252.6-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtasn1-6</strong></td>
		<td valign="top"><code>4.19.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libthai</strong></td>
		<td valign="top"><code>0.1.29-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libthai-data</strong></td>
		<td valign="top"><code>0.1.29-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libthai0</strong></td>
		<td valign="top"><code>0.1.29-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtiff-dev</strong></td>
		<td valign="top"><code>4.5.0-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtiff6</strong></td>
		<td valign="top"><code>4.5.0-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtiffxx6</strong></td>
		<td valign="top"><code>4.5.0-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtinfo6</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtirpc</strong></td>
		<td valign="top"><code>1.3.3+ds-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtirpc-common</strong></td>
		<td valign="top"><code>1.3.3+ds-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtirpc-dev</strong></td>
		<td valign="top"><code>1.3.3+ds-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtirpc3</strong></td>
		<td valign="top"><code>1.3.3+ds-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtool</strong></td>
		<td valign="top"><code>2.4.7-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtsan2</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libubsan1</strong></td>
		<td valign="top"><code>12.2.0-14</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libudev1</strong></td>
		<td valign="top"><code>252.6-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libunistring</strong></td>
		<td valign="top"><code>1.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libunistring2</strong></td>
		<td valign="top"><code>1.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libutf8proc2</strong></td>
		<td valign="top"><code>2.8.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libuuid1</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwebp</strong></td>
		<td valign="top"><code>1.2.4-0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2023--4863" src="https://img.shields.io/badge/CVE--2023--4863-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwebp-dev</strong></td>
		<td valign="top"><code>1.2.4-0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwebp7</strong></td>
		<td valign="top"><code>1.2.4-0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwebpdemux2</strong></td>
		<td valign="top"><code>1.2.4-0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwebpmux3</strong></td>
		<td valign="top"><code>1.2.4-0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwmf</strong></td>
		<td valign="top"><code>0.2.12-5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (4):</strong><br/><ul><li><img alt="medium : CVE--2009--3546" src="https://img.shields.io/badge/CVE--2009--3546-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2007--3996" src="https://img.shields.io/badge/CVE--2007--3996-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="low : CVE--2007--3477" src="https://img.shields.io/badge/CVE--2007--3477-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2007--3476" src="https://img.shields.io/badge/CVE--2007--3476-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwmf-0.2-7</strong></td>
		<td valign="top"><code>0.2.12-5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwmf-dev</strong></td>
		<td valign="top"><code>0.2.12-5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwmflite-0.2-7</strong></td>
		<td valign="top"><code>0.2.12-5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libx11</strong></td>
		<td valign="top"><code>2:1.8.4-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (4):</strong><br/><ul><li><img alt="high : CVE--2023--43787" src="https://img.shields.io/badge/CVE--2023--43787-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2023--3138" src="https://img.shields.io/badge/CVE--2023--3138-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="medium : CVE--2023--43786" src="https://img.shields.io/badge/CVE--2023--43786-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2023--43785" src="https://img.shields.io/badge/CVE--2023--43785-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libx11-6</strong></td>
		<td valign="top"><code>2:1.8.4-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libx11-data</strong></td>
		<td valign="top"><code>2:1.8.4-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libx11-dev</strong></td>
		<td valign="top"><code>2:1.8.4-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libx265-199</strong></td>
		<td valign="top"><code>3.5-2+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxau</strong></td>
		<td valign="top"><code>1:1.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxau-dev</strong></td>
		<td valign="top"><code>1:1.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxau6</strong></td>
		<td valign="top"><code>1:1.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcb</strong></td>
		<td valign="top"><code>1.15-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcb-render0</strong></td>
		<td valign="top"><code>1.15-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcb-render0-dev</strong></td>
		<td valign="top"><code>1.15-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcb-shm0</strong></td>
		<td valign="top"><code>1.15-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcb-shm0-dev</strong></td>
		<td valign="top"><code>1.15-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcb1</strong></td>
		<td valign="top"><code>1.15-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcb1-dev</strong></td>
		<td valign="top"><code>1.15-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcrypt</strong></td>
		<td valign="top"><code>1:4.4.33-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxdmcp</strong></td>
		<td valign="top"><code>1:1.1.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxdmcp-dev</strong></td>
		<td valign="top"><code>1:1.1.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxdmcp6</strong></td>
		<td valign="top"><code>1:1.1.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxext</strong></td>
		<td valign="top"><code>2:1.3.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxext-dev</strong></td>
		<td valign="top"><code>2:1.3.4-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxext6</strong></td>
		<td valign="top"><code>2:1.3.4-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxml2</strong></td>
		<td valign="top"><code>2.9.14+dfsg-1.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="high : CVE--2022--2309" src="https://img.shields.io/badge/CVE--2022--2309-lightgrey?label=high%20&labelColor=e25d68"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxml2-dev</strong></td>
		<td valign="top"><code>2.9.14+dfsg-1.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxrender</strong></td>
		<td valign="top"><code>1:0.9.10-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxrender-dev</strong></td>
		<td valign="top"><code>1:0.9.10-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxrender1</strong></td>
		<td valign="top"><code>1:0.9.10-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxslt</strong></td>
		<td valign="top"><code>1.1.35-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2015--9019" src="https://img.shields.io/badge/CVE--2015--9019-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxslt1-dev</strong></td>
		<td valign="top"><code>1.1.35-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxslt1.1</strong></td>
		<td valign="top"><code>1.1.35-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxt</strong></td>
		<td valign="top"><code>1:1.2.1-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxt-dev</strong></td>
		<td valign="top"><code>1:1.2.1-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxt6</strong></td>
		<td valign="top"><code>1:1.2.1-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxxhash0</strong></td>
		<td valign="top"><code>0.8.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libyaml</strong></td>
		<td valign="top"><code>0.2.5-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="high : CVE--2024--3205" src="https://img.shields.io/badge/CVE--2024--3205-lightgrey?label=high%20&labelColor=e25d68"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libyaml-0-2</strong></td>
		<td valign="top"><code>0.2.5-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libyaml-dev</strong></td>
		<td valign="top"><code>0.2.5-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libzstd</strong></td>
		<td valign="top"><code>1.5.4+dfsg2-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libzstd-dev</strong></td>
		<td valign="top"><code>1.5.4+dfsg2-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libzstd1</strong></td>
		<td valign="top"><code>1.5.4+dfsg2-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>linux</strong></td>
		<td valign="top"><code>6.1.27-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>linux-libc-dev</strong></td>
		<td valign="top"><code>6.1.27-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>login</strong></td>
		<td valign="top"><code>1:4.13+dfsg1-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>logsave</strong></td>
		<td valign="top"><code>1.47.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>lz4</strong></td>
		<td valign="top"><code>1.9.4-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>lzo2</strong></td>
		<td valign="top"><code>2.10-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>m4</strong></td>
		<td valign="top"><code>1.4.19-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="low : CVE--2008--1688" src="https://img.shields.io/badge/CVE--2008--1688-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2008--1687" src="https://img.shields.io/badge/CVE--2008--1687-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>make</strong></td>
		<td valign="top"><code>4.3-4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>make-dfsg</strong></td>
		<td valign="top"><code>4.3-4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mariadb</strong></td>
		<td valign="top"><code>1:10.11.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2023--22084" src="https://img.shields.io/badge/CVE--2023--22084-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mariadb-common</strong></td>
		<td valign="top"><code>1:10.11.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mawk</strong></td>
		<td valign="top"><code>1.3.4.20200120-3.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>media-types</strong></td>
		<td valign="top"><code>10.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mercurial</strong></td>
		<td valign="top"><code>6.3.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mercurial-common</strong></td>
		<td valign="top"><code>6.3.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mount</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mpclib3</strong></td>
		<td valign="top"><code>1.3.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mpfr4</strong></td>
		<td valign="top"><code>4.2.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mysql-common</strong></td>
		<td valign="top"><code>5.8+1.1.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mysql-defaults</strong></td>
		<td valign="top"><code>1.1.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ncurses</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ncurses-base</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ncurses-bin</strong></td>
		<td valign="top"><code>6.4-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>netbase</strong></td>
		<td valign="top"><code>6.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>nettle</strong></td>
		<td valign="top"><code>3.8.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>nghttp2</strong></td>
		<td valign="top"><code>1.52.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2023--44487" src="https://img.shields.io/badge/CVE--2023--44487-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>npth</strong></td>
		<td valign="top"><code>1.6-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>numactl</strong></td>
		<td valign="top"><code>2.0.16-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>openexr</strong></td>
		<td valign="top"><code>3.1.5-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2017--14988" src="https://img.shields.io/badge/CVE--2017--14988-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>openjpeg2</strong></td>
		<td valign="top"><code>2.5.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 13" src="https://img.shields.io/badge/L-13-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (13):</strong><br/><ul><li><img alt="low : CVE--2018--20846" src="https://img.shields.io/badge/CVE--2018--20846-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--16376" src="https://img.shields.io/badge/CVE--2018--16376-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--16375" src="https://img.shields.io/badge/CVE--2018--16375-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2017--17479" src="https://img.shields.io/badge/CVE--2017--17479-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--9581" src="https://img.shields.io/badge/CVE--2016--9581-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--9580" src="https://img.shields.io/badge/CVE--2016--9580-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--9117" src="https://img.shields.io/badge/CVE--2016--9117-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--9116" src="https://img.shields.io/badge/CVE--2016--9116-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--9115" src="https://img.shields.io/badge/CVE--2016--9115-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--9114" src="https://img.shields.io/badge/CVE--2016--9114-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--9113" src="https://img.shields.io/badge/CVE--2016--9113-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--10506" src="https://img.shields.io/badge/CVE--2016--10506-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2016--10505" src="https://img.shields.io/badge/CVE--2016--10505-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>openldap</strong></td>
		<td valign="top"><code>2.5.13+dfsg-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (4):</strong><br/><ul><li><img alt="low : CVE--2020--15719" src="https://img.shields.io/badge/CVE--2020--15719-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2017--17740" src="https://img.shields.io/badge/CVE--2017--17740-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2017--14159" src="https://img.shields.io/badge/CVE--2017--14159-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2015--3276" src="https://img.shields.io/badge/CVE--2015--3276-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>openssh</strong></td>
		<td valign="top"><code>1:9.2p1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 1" src="https://img.shields.io/badge/C-1-8b1924"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 3" src="https://img.shields.io/badge/L-3-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (5):</strong><br/><ul><li><img alt="critical : CVE--2023--38408" src="https://img.shields.io/badge/CVE--2023--38408-lightgrey?label=critical%20&labelColor=8b1924"/></li><li><img alt="medium : CVE--2023--51385" src="https://img.shields.io/badge/CVE--2023--51385-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="low : CVE--2023--51384" src="https://img.shields.io/badge/CVE--2023--51384-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--48795" src="https://img.shields.io/badge/CVE--2023--48795-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--28531" src="https://img.shields.io/badge/CVE--2023--28531-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>openssh-client</strong></td>
		<td valign="top"><code>1:9.2p1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>openssl</strong></td>
		<td valign="top"><code>3.0.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (4):</strong><br/><ul><li><img alt="medium : CVE--2023--3817" src="https://img.shields.io/badge/CVE--2023--3817-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2023--3446" src="https://img.shields.io/badge/CVE--2023--3446-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="low : CVE--2023--5363" src="https://img.shields.io/badge/CVE--2023--5363-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2023--2975" src="https://img.shields.io/badge/CVE--2023--2975-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>p11-kit</strong></td>
		<td valign="top"><code>0.24.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pam</strong></td>
		<td valign="top"><code>1.5.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pango1.0</strong></td>
		<td valign="top"><code>1.50.12+ds-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>passwd</strong></td>
		<td valign="top"><code>1:4.13+dfsg1-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>patch</strong></td>
		<td valign="top"><code>2.7.6-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (4):</strong><br/><ul><li><img alt="low : CVE--2021--45261" src="https://img.shields.io/badge/CVE--2021--45261-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--6952" src="https://img.shields.io/badge/CVE--2018--6952-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2018--6951" src="https://img.shields.io/badge/CVE--2018--6951-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2010--4651" src="https://img.shields.io/badge/CVE--2010--4651-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pcre2</strong></td>
		<td valign="top"><code>10.42-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>perl</strong></td>
		<td valign="top"><code>5.36.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2023--47038" src="https://img.shields.io/badge/CVE--2023--47038-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>perl-base</strong></td>
		<td valign="top"><code>5.36.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>perl-modules-5.36</strong></td>
		<td valign="top"><code>5.36.0-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pinentry</strong></td>
		<td valign="top"><code>1.2.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pinentry-curses</strong></td>
		<td valign="top"><code>1.2.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pixman</strong></td>
		<td valign="top"><code>0.42.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2023--37769" src="https://img.shields.io/badge/CVE--2023--37769-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pkg-config</strong></td>
		<td valign="top"><code>1.8.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pkgconf</strong></td>
		<td valign="top"><code>1.8.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>pkgconf-bin</strong></td>
		<td valign="top"><code>1.8.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>postgresql-15</strong></td>
		<td valign="top"><code>15.3-0+deb12u1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 3" src="https://img.shields.io/badge/H-3-e25d68"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (6):</strong><br/><ul><li><img alt="high : CVE--2023--5869" src="https://img.shields.io/badge/CVE--2023--5869-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2023--39417" src="https://img.shields.io/badge/CVE--2023--39417-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="high : CVE--2024--0985" src="https://img.shields.io/badge/CVE--2024--0985-lightgrey?label=high%20&labelColor=e25d68"/></li><li><img alt="medium : CVE--2023--5870" src="https://img.shields.io/badge/CVE--2023--5870-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2023--5868" src="https://img.shields.io/badge/CVE--2023--5868-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="low : CVE--2023--39418" src="https://img.shields.io/badge/CVE--2023--39418-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>procps</strong></td>
		<td valign="top"><code>2:4.0.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3</strong></td>
		<td valign="top"><code>3.11.2-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3-defaults</strong></td>
		<td valign="top"><code>3.11.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3-distutils</strong></td>
		<td valign="top"><code>3.11.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3-lib2to3</strong></td>
		<td valign="top"><code>3.11.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3-minimal</strong></td>
		<td valign="top"><code>3.11.2-1+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3-stdlib-extensions</strong></td>
		<td valign="top"><code>3.11.2-3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3.11</strong></td>
		<td valign="top"><code>3.11.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3.11-minimal</strong></td>
		<td valign="top"><code>3.11.2-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>readline</strong></td>
		<td valign="top"><code>8.2-1.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>readline-common</strong></td>
		<td valign="top"><code>8.2-1.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>rpcsvc-proto</strong></td>
		<td valign="top"><code>1.4.3-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>rtmpdump</strong></td>
		<td valign="top"><code>2.4+20151223.gitfa8646d.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>rust-sequoia-sq</strong></td>
		<td valign="top"><code>0.27.0-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sed</strong></td>
		<td valign="top"><code>4.9-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sensible-utils</strong></td>
		<td valign="top"><code>0.0.17+nmu1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>serf</strong></td>
		<td valign="top"><code>1.3.9-11</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>shadow</strong></td>
		<td valign="top"><code>1:4.13+dfsg1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="low : CVE--2019--19882" src="https://img.shields.io/badge/CVE--2019--19882-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="low : CVE--2007--5686" src="https://img.shields.io/badge/CVE--2007--5686-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>shared-mime-info</strong></td>
		<td valign="top"><code>2.2-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sq</strong></td>
		<td valign="top"><code>0.27.0-2+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sqlite3</strong></td>
		<td valign="top"><code>3.40.1-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2021--45346" src="https://img.shields.io/badge/CVE--2021--45346-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>subversion</strong></td>
		<td valign="top"><code>1.14.2-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>systemd</strong></td>
		<td valign="top"><code>252.6-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2023--7008" src="https://img.shields.io/badge/CVE--2023--7008-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sysvinit</strong></td>
		<td valign="top"><code>3.06-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sysvinit-utils</strong></td>
		<td valign="top"><code>3.06-4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>tar</strong></td>
		<td valign="top"><code>1.34+dfsg-1.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <img alt="unspecified: 1" src="https://img.shields.io/badge/U-1-lightgrey"/></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="low : CVE--2022--48303" src="https://img.shields.io/badge/CVE--2022--48303-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="unspecified : CVE--2023--39804" src="https://img.shields.io/badge/CVE--2023--39804-lightgrey?label=unspecified%20&labelColor=lightgrey"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>tiff</strong></td>
		<td valign="top"><code>4.5.0-6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 3" src="https://img.shields.io/badge/M-3-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (3):</strong><br/><ul><li><img alt="medium : CVE--2023--41175" src="https://img.shields.io/badge/CVE--2023--41175-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2023--40745" src="https://img.shields.io/badge/CVE--2023--40745-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2023--3576" src="https://img.shields.io/badge/CVE--2023--3576-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>tzdata</strong></td>
		<td valign="top"><code>2023c-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ucf</strong></td>
		<td valign="top"><code>3.0043+nmu1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>unzip</strong></td>
		<td valign="top"><code>6.0-28</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2021--4217" src="https://img.shields.io/badge/CVE--2021--4217-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>usr-is-merged</strong></td>
		<td valign="top"><code>35</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>usrmerge</strong></td>
		<td valign="top"><code>35</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>utf8proc</strong></td>
		<td valign="top"><code>2.8.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>util-linux</strong></td>
		<td valign="top"><code>2.38.1-5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <img alt="unspecified: 1" src="https://img.shields.io/badge/U-1-lightgrey"/></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="low : CVE--2022--0563" src="https://img.shields.io/badge/CVE--2022--0563-lightgrey?label=low%20&labelColor=fce1a9"/></li><li><img alt="unspecified : CVE--2024--28085" src="https://img.shields.io/badge/CVE--2024--28085-lightgrey?label=unspecified%20&labelColor=lightgrey"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>util-linux-extra</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>uuid-dev</strong></td>
		<td valign="top"><code>2.38.1-5+b1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>wget</strong></td>
		<td valign="top"><code>1.21.3-1+b2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>x11-common</strong></td>
		<td valign="top"><code>1:7.7+23</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>x11proto-core-dev</strong></td>
		<td valign="top"><code>2022.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>x11proto-dev</strong></td>
		<td valign="top"><code>2022.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>x265</strong></td>
		<td valign="top"><code>3.5-2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>xorg</strong></td>
		<td valign="top"><code>1:7.7+23</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>xorg-sgml-doctools</strong></td>
		<td valign="top"><code>1:1.11-1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>xorgproto</strong></td>
		<td valign="top"><code>2022.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>xtrans</strong></td>
		<td valign="top"><code>1.4.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>xtrans-dev</strong></td>
		<td valign="top"><code>1.4.0-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>xxhash</strong></td>
		<td valign="top"><code>0.8.1-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>xz-utils</strong></td>
		<td valign="top"><code>5.4.1-0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>zlib</strong></td>
		<td valign="top"><code>1:1.2.13.dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>zlib1g</strong></td>
		<td valign="top"><code>1:1.2.13.dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>zlib1g-dev</strong></td>
		<td valign="top"><code>1:1.2.13.dfsg-1</code></td>
		<td valign="top"></td>
	</tr>
	
</table>
</details>
<details><summary>Changes for packages of type <code>generic</code> (3 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v1</code></th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v3</code></th>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>bash</strong></td>
		<td valign="top"><code>5.2.15</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>openssl</strong></td>
		<td valign="top"><code>3.0.9</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python</strong></td>
		<td valign="top"><code>3.11.2</code></td>
		<td valign="top"></td>
	</tr>
	
</table>
</details>
<details><summary>Changes for packages of type <code>github</code> (1 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v1</code></th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v3</code></th>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>node</strong></td>
		<td valign="top"><code>18.16.0</code></td>
		<td valign="top"><code>22.2.0</code></td>
	</tr>
	
</table>
</details>
<details><summary>Changes for packages of type <code>npm</code> (162 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v1</code></th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v3</code></th>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>@colors/colors</strong></td>
		<td valign="top"><code>1.5.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>@gar/promisify</strong></td>
		<td valign="top"><code>1.1.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@isaacs/cliui</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@npmcli/agent</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.2.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/arborist</strong></td>
		<td valign="top"><code>6.2.3</code></td>
		<td valign="top"><code>7.5.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/config</strong></td>
		<td valign="top"><code>6.1.3</code></td>
		<td valign="top"><code>8.3.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>@npmcli/disparity-colors</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/git</strong></td>
		<td valign="top"><code>4.0.3</code></td>
		<td valign="top"><code>5.0.6</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/installed-package-contents</strong></td>
		<td valign="top"><code>2.0.1</code></td>
		<td valign="top"><code>2.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/map-workspaces</strong></td>
		<td valign="top"><code>3.0.2</code></td>
		<td valign="top"><code>3.0.6</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/metavuln-calculator</strong></td>
		<td valign="top"><code>5.0.0</code></td>
		<td valign="top"><code>7.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>@npmcli/move-file</strong></td>
		<td valign="top"><code>2.0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/package-json</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"><code>5.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/promise-spawn</strong></td>
		<td valign="top"><code>6.0.2</code></td>
		<td valign="top"><code>7.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/query</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"><code>3.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@npmcli/redact</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>@npmcli/run-script</strong></td>
		<td valign="top"><code>6.0.0</code></td>
		<td valign="top"><code>8.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@pkgjs/parseargs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.11.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@sigstore/bundle</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.3.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@sigstore/core</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@sigstore/protobuf-specs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.3.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@sigstore/sign</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.3.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@sigstore/tuf</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.3.2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@sigstore/verify</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>@tootallnate/once</strong></td>
		<td valign="top"><code>2.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@tufjs/canonical-json</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>@tufjs/models</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>abort-controller</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>agent-base</strong></td>
		<td valign="top"><code>6.0.2</code></td>
		<td valign="top"><code>7.1.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>agentkeepalive</strong></td>
		<td valign="top"><code>4.2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>ansi-regex</strong></td>
		<td valign="top"><code>5.0.1</code></td>
		<td valign="top"><code>6.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>ansi-styles</strong></td>
		<td valign="top"><code>4.3.0</code></td>
		<td valign="top"><code>6.2.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>are-we-there-yet</strong></td>
		<td valign="top"><code>4.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>base64-js</strong></td>
		<td valign="top"><code>1.5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>bin-links</strong></td>
		<td valign="top"><code>4.0.1</code></td>
		<td valign="top"><code>4.0.3</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>binary-extensions</strong></td>
		<td valign="top"><code>2.2.0</code></td>
		<td valign="top"><code>2.3.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>buffer</strong></td>
		<td valign="top"><code>6.0.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>builtins</strong></td>
		<td valign="top"><code>5.0.1</code></td>
		<td valign="top"><code>5.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>cacache</strong></td>
		<td valign="top"><code>17.0.4</code></td>
		<td valign="top"><code>18.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>chalk</strong></td>
		<td valign="top"><code>4.1.2</code></td>
		<td valign="top"><code>5.3.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>ci-info</strong></td>
		<td valign="top"><code>3.8.0</code></td>
		<td valign="top"><code>4.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>cidr-regex</strong></td>
		<td valign="top"><code>3.1.1</code></td>
		<td valign="top"><code>4.0.5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>cli-table3</strong></td>
		<td valign="top"><code>0.6.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>clone</strong></td>
		<td valign="top"><code>1.0.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>cmd-shim</strong></td>
		<td valign="top"><code>6.0.1</code></td>
		<td valign="top"><code>6.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>color-support</strong></td>
		<td valign="top"><code>1.1.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>columnify</strong></td>
		<td valign="top"><code>1.6.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>console-control-strings</strong></td>
		<td valign="top"><code>1.1.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>corepack</strong></td>
		<td valign="top"><code>0.17.0</code></td>
		<td valign="top"><code>0.28.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>cross-spawn</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>7.0.3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>defaults</strong></td>
		<td valign="top"><code>1.0.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>delegates</strong></td>
		<td valign="top"><code>1.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>diff</strong></td>
		<td valign="top"><code>5.1.0</code></td>
		<td valign="top"><code>5.2.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>eastasianwidth</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.2.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>emoji-regex</strong></td>
		<td valign="top"><code>8.0.0</code></td>
		<td valign="top"><code>9.2.2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>event-target-shim</strong></td>
		<td valign="top"><code>5.0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>events</strong></td>
		<td valign="top"><code>3.3.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>exponential-backoff</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>foreground-child</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>fs-minipass</strong></td>
		<td valign="top"><code>3.0.1</code></td>
		<td valign="top"><code>3.0.3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fs.realpath</strong></td>
		<td valign="top"><code>1.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>function-bind</strong></td>
		<td valign="top"><code>1.1.1</code></td>
		<td valign="top"><code>1.1.2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gauge</strong></td>
		<td valign="top"><code>5.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>glob</strong></td>
		<td valign="top"><code>8.1.0</code></td>
		<td valign="top"><code>10.3.12</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>graceful-fs</strong></td>
		<td valign="top"><code>4.2.10</code></td>
		<td valign="top"><code>4.2.11</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>has</strong></td>
		<td valign="top"><code>1.0.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>has-unicode</strong></td>
		<td valign="top"><code>2.0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>hasown</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>hosted-git-info</strong></td>
		<td valign="top"><code>6.1.1</code></td>
		<td valign="top"><code>7.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>http-proxy-agent</strong></td>
		<td valign="top"><code>5.0.0</code></td>
		<td valign="top"><code>7.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>https-proxy-agent</strong></td>
		<td valign="top"><code>5.0.1</code></td>
		<td valign="top"><code>7.0.4</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>humanize-ms</strong></td>
		<td valign="top"><code>1.2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ieee754</strong></td>
		<td valign="top"><code>1.2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>ignore-walk</strong></td>
		<td valign="top"><code>6.0.1</code></td>
		<td valign="top"><code>6.0.4</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>infer-owner</strong></td>
		<td valign="top"><code>1.0.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>inflight</strong></td>
		<td valign="top"><code>1.0.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>inherits</strong></td>
		<td valign="top"><code>2.0.4</code></td>
		<td valign="top"><code>2.0.3</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>ini</strong></td>
		<td valign="top"><code>3.0.1</code></td>
		<td valign="top"><code>4.1.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>init-package-json</strong></td>
		<td valign="top"><code>5.0.0</code></td>
		<td valign="top"><code>6.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ip</strong></td>
		<td valign="top"><code>2.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2023--42282" src="https://img.shields.io/badge/CVE--2023--42282-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ip-address</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>9.0.5</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>ip-regex</strong></td>
		<td valign="top"><code>4.3.0</code></td>
		<td valign="top"><code>5.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>is-cidr</strong></td>
		<td valign="top"><code>4.0.2</code></td>
		<td valign="top"><code>5.0.5</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>is-core-module</strong></td>
		<td valign="top"><code>2.11.0</code></td>
		<td valign="top"><code>2.13.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>isexe</strong></td>
		<td valign="top"><code>2.0.0</code></td>
		<td valign="top"><code>3.1.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>jackspeak</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.3.6</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>jsbn</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>json-parse-even-better-errors</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"><code>3.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>just-diff</strong></td>
		<td valign="top"><code>5.2.0</code></td>
		<td valign="top"><code>6.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmaccess</strong></td>
		<td valign="top"><code>7.0.2</code></td>
		<td valign="top"><code>8.0.5</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmdiff</strong></td>
		<td valign="top"><code>5.0.11</code></td>
		<td valign="top"><code>6.1.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmexec</strong></td>
		<td valign="top"><code>5.0.11</code></td>
		<td valign="top"><code>8.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmfund</strong></td>
		<td valign="top"><code>4.0.11</code></td>
		<td valign="top"><code>5.0.9</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmhook</strong></td>
		<td valign="top"><code>9.0.3</code></td>
		<td valign="top"><code>10.0.4</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmorg</strong></td>
		<td valign="top"><code>5.0.3</code></td>
		<td valign="top"><code>6.0.5</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmpack</strong></td>
		<td valign="top"><code>5.0.11</code></td>
		<td valign="top"><code>7.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmpublish</strong></td>
		<td valign="top"><code>7.1.0</code></td>
		<td valign="top"><code>9.0.7</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmsearch</strong></td>
		<td valign="top"><code>6.0.2</code></td>
		<td valign="top"><code>7.0.4</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmteam</strong></td>
		<td valign="top"><code>5.0.3</code></td>
		<td valign="top"><code>6.0.4</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>libnpmversion</strong></td>
		<td valign="top"><code>4.0.2</code></td>
		<td valign="top"><code>6.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>lru-cache</strong></td>
		<td valign="top"><code>7.16.2</code></td>
		<td valign="top"><code>6.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>make-fetch-happen</strong></td>
		<td valign="top"><code>11.0.3</code></td>
		<td valign="top"><code>13.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>minimatch</strong></td>
		<td valign="top"><code>6.2.0</code></td>
		<td valign="top"><code>9.0.4</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>minipass</strong></td>
		<td valign="top"><code>4.0.3</code></td>
		<td valign="top"><code>7.0.4</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>minipass-collect</strong></td>
		<td valign="top"><code>1.0.2</code></td>
		<td valign="top"><code>2.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>minipass-fetch</strong></td>
		<td valign="top"><code>3.0.1</code></td>
		<td valign="top"><code>3.0.4</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>node-gyp</strong></td>
		<td valign="top"><code>9.3.1</code></td>
		<td valign="top"><code>10.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>nopt</strong></td>
		<td valign="top"><code>7.0.0</code></td>
		<td valign="top"><code>7.2.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>normalize-package-data</strong></td>
		<td valign="top"><code>5.0.0</code></td>
		<td valign="top"><code>6.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm</strong></td>
		<td valign="top"><code>9.5.1</code></td>
		<td valign="top"><code>10.7.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm-audit-report</strong></td>
		<td valign="top"><code>4.0.0</code></td>
		<td valign="top"><code>5.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm-install-checks</strong></td>
		<td valign="top"><code>6.0.0</code></td>
		<td valign="top"><code>6.3.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm-normalize-package-bin</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"><code>3.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm-package-arg</strong></td>
		<td valign="top"><code>10.1.0</code></td>
		<td valign="top"><code>11.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm-packlist</strong></td>
		<td valign="top"><code>7.0.4</code></td>
		<td valign="top"><code>8.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm-pick-manifest</strong></td>
		<td valign="top"><code>8.0.1</code></td>
		<td valign="top"><code>9.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm-profile</strong></td>
		<td valign="top"><code>7.0.1</code></td>
		<td valign="top"><code>9.0.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>npm-registry-fetch</strong></td>
		<td valign="top"><code>14.0.3</code></td>
		<td valign="top"><code>17.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>npmlog</strong></td>
		<td valign="top"><code>7.0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>once</strong></td>
		<td valign="top"><code>1.4.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>pacote</strong></td>
		<td valign="top"><code>15.1.1</code></td>
		<td valign="top"><code>18.0.3</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>parse-conflict-json</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"><code>3.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>path-is-absolute</strong></td>
		<td valign="top"><code>1.0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>path-key</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>path-scurry</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.10.2</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>postcss-selector-parser</strong></td>
		<td valign="top"><code>6.0.11</code></td>
		<td valign="top"><code>6.0.16</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>proc-log</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"><code>4.2.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>process</strong></td>
		<td valign="top"><code>0.11.10</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>proggy</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>promise-call-limit</strong></td>
		<td valign="top"><code>1.0.1</code></td>
		<td valign="top"><code>3.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>promzard</strong></td>
		<td valign="top"><code>1.0.0</code></td>
		<td valign="top"><code>1.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>read</strong></td>
		<td valign="top"><code>2.0.0</code></td>
		<td valign="top"><code>3.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>read-package-json</strong></td>
		<td valign="top"><code>6.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>readable-stream</strong></td>
		<td valign="top"><code>4.3.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>rimraf</strong></td>
		<td valign="top"><code>3.0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>semver</strong></td>
		<td valign="top"><code>7.3.8</code></td>
		<td valign="top"><code>7.6.0</code></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2022--25883" src="https://img.shields.io/badge/CVE--2022--25883-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>set-blocking</strong></td>
		<td valign="top"><code>2.0.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>shebang-command</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>shebang-regex</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>signal-exit</strong></td>
		<td valign="top"><code>3.0.7</code></td>
		<td valign="top"><code>4.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>sigstore</strong></td>
		<td valign="top"><code>1.0.0</code></td>
		<td valign="top"><code>2.3.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>socks</strong></td>
		<td valign="top"><code>2.7.1</code></td>
		<td valign="top"><code>2.8.3</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>socks-proxy-agent</strong></td>
		<td valign="top"><code>7.0.0</code></td>
		<td valign="top"><code>8.0.3</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>spdx-correct</strong></td>
		<td valign="top"><code>3.1.1</code></td>
		<td valign="top"><code>3.2.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>spdx-exceptions</strong></td>
		<td valign="top"><code>2.3.0</code></td>
		<td valign="top"><code>2.5.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>spdx-expression-parse</strong></td>
		<td valign="top"><code>3.0.1</code></td>
		<td valign="top"><code>4.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>spdx-license-ids</strong></td>
		<td valign="top"><code>3.0.12</code></td>
		<td valign="top"><code>3.0.17</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>sprintf-js</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.1.3</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>ssri</strong></td>
		<td valign="top"><code>9.0.1</code></td>
		<td valign="top"><code>10.0.5</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>string-width</strong></td>
		<td valign="top"><code>4.2.3</code></td>
		<td valign="top"><code>5.1.2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>string_decoder</strong></td>
		<td valign="top"><code>1.1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>strip-ansi</strong></td>
		<td valign="top"><code>6.0.1</code></td>
		<td valign="top"><code>7.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>supports-color</strong></td>
		<td valign="top"><code>7.2.0</code></td>
		<td valign="top"><code>9.4.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>tar</strong></td>
		<td valign="top"><code>6.1.13</code></td>
		<td valign="top"><code>6.2.1</code></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2024--28863" src="https://img.shields.io/badge/CVE--2024--28863-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>tuf-js</strong></td>
		<td valign="top"><code>1.0.0</code></td>
		<td valign="top"><code>2.2.0</code></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>walk-up-path</strong></td>
		<td valign="top"><code>1.0.0</code></td>
		<td valign="top"><code>3.0.1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>wcwidth</strong></td>
		<td valign="top"><code>1.0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>which</strong></td>
		<td valign="top"><code>3.0.0</code></td>
		<td valign="top"><code>4.0.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>wide-align</strong></td>
		<td valign="top"><code>1.1.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>wrap-ansi</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.1.0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>wrappy</strong></td>
		<td valign="top"><code>1.0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:infinity:</td>
		<td valign="top"><strong>write-file-atomic</strong></td>
		<td valign="top"><code>5.0.0</code></td>
		<td valign="top"><code>5.0.1</code></td>
	</tr>
	
</table>
</details>
<details><summary>Changes for packages of type <code>pypi</code> (1 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v1</code></th>
		<th valign="top">Version<br/><code>bogusrj/imagem-caotica:v3</code></th>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mercurial</strong></td>
		<td valign="top"><code>6.3.2</code></td>
		<td valign="top"></td>
	</tr>
	
</table>
</details>
</details>

