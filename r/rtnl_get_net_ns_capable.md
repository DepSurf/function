# Function: <code>rtnl_get_net_ns_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818cb9a0)
Location: net/core/rtnetlink.c:1862
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff818cb9a0-ffffffff818cba0a: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81918d60)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff81918d60-ffffffff81918dce: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194b380)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff8194b380-ffffffff8194b3ee: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1afe0)
Location: net/core/rtnetlink.c:1950
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff81a1afe0-ffffffff81a1b064: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1b6d0)
Location: net/core/rtnetlink.c:1993
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff81a1b6d0-ffffffff81a1b75a: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a01810)
Location: net/core/rtnetlink.c:1996
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff81a01810-ffffffff81a0189a: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab3b00)
Location: net/core/rtnetlink.c:2005
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_valid_dump_ifaddr_req
```
**Symbols:**

```
ffffffff81ab3b00-ffffffff81ab3b8a: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2d8d0)
Location: net/core/rtnetlink.c:2051
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff81c2d8d0-ffffffff81c2d95a: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de0a70)
Location: net/core/rtnetlink.c:2091
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff81de0a70-ffffffff81de0afa: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e519b0)
Location: net/core/rtnetlink.c:2106
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff81e519b0-ffffffff81e51a3a: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f10480)
Location: net/core/rtnetlink.c:2138
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff81f10480-ffffffff81f1050a: rtnl_get_net_ns_capable (STB_GLOBAL)
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
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bec2e8)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffff800010bec2e8-ffff800010bec37c: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d04a2c)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
c0d04a2c-c0d04a9c: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccfcc0)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
c000000000ccfcc0-c000000000ccfda4: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076de62)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffe00076de62-ffffffe00076deec: rtnl_get_net_ns_capable (STB_GLOBAL)
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
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818eb350)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff818eb350-ffffffff818eb3be: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a5190)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff818a5190-ffffffff818a51fe: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193c380)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff8193c380-ffffffff8193c3ee: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct net *rtnl_get_net_ns_capable(struct sock *sk, int netnsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195dbf0)
Location: net/core/rtnetlink.c:1864
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff8195dbf0-ffffffff8195dc5e: rtnl_get_net_ns_capable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
