# Function: <code>netdev_get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171beb0)
Location: net/core/dev.c:870
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8171beb0-ffffffff8171bf43: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81784740)
Location: net/core/dev.c:874
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81784740-ffffffff817847e2: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b1d30)
Location: net/core/dev.c:873
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff817b1d30-ffffffff817b1dd2: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cf3a0)
Location: net/core/dev.c:905
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ifname
```
**Symbols:**

```
ffffffff817cf3a0-ffffffff817cf446: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81848d10)
Location: net/core/dev.c:908
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ifname
```
**Symbols:**

```
ffffffff81848d10-ffffffff81848db6: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81892d70)
Location: net/core/dev.c:908
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81892d70-ffffffff81892e12: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b37f0)
Location: net/core/dev.c:910
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818b37f0-ffffffff818b3892: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81900080)
Location: net/core/dev.c:906
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81900080-ffffffff81900130: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819323a0)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff819323a0-ffffffff81932450: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a074b0)
Location: net/core/dev.c:1018
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a074b0-ffffffff81a0753f: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1021
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81c312c8-ffffffff81c312e0: netdev_get_name.cold (STB_LOCAL)
ffffffff81a08a60-ffffffff81a08b9a: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1069
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81c2358e-ffffffff81c235a6: netdev_get_name.cold (STB_LOCAL)
ffffffff819ef2b0-ffffffff819ef3ea: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:944
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81d3632c-ffffffff81d36344: netdev_get_name.cold (STB_LOCAL)
ffffffff81aa06d0-ffffffff81aa080a: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:891
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81f02b02-ffffffff81f02b1a: netdev_get_name.cold (STB_LOCAL)
ffffffff81c186e0-ffffffff81c18829: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc9640)
Location: net/core/dev.c:891
Inline: False
Direct callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81dc9640-ffffffff81dc979c: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e37ba0)
Location: net/core/dev.c:916
Inline: False
Direct callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81e37ba0-ffffffff81e37cf1: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef5bf0)
Location: net/core/dev.c:933
Inline: False
Direct callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81ef5bf0-ffffffff81ef5d4d: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0310)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffff800010bd0310-ffff800010bd03f0: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceae88)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
c0ceae88-c0ceaf40: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cae000)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
c000000000cae000-c000000000cae138: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075ab56)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffe00075ab56-ffffffe00075ac10: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d23a0)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818d23a0-ffffffff818d2450: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c230)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8188c230-ffffffff8188c2e0: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819233a0)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff819233a0-ffffffff81923450: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netdev_get_name(struct net *net, char *name, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819447d0)
Location: net/core/dev.c:824
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff819447d0-ffffffff81944861: netdev_get_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
