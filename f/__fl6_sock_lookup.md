# Function: <code>__fl6_sock_lookup</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f890)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a3f890-ffffffff81a3f939: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a76500)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a76500-ffffffff81a765a9: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6fd80)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81b6fd80-ffffffff81b6fe3b: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7e890)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81b7e890-ffffffff81b7e94b: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d490)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81b6d490-ffffffff81b6d54b: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (0)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81d410d1-ffffffff81d410f1: __fl6_sock_lookup.cold (STB_LOCAL)
ffffffff81c35f50-ffffffff81c36028: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (0)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81f0da1d-ffffffff81f0da3d: __fl6_sock_lookup.cold (STB_LOCAL)
ffffffff81dd39e0-ffffffff81dd3ab9: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (0)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff820b4e4d-ffffffff820b4e6d: __fl6_sock_lookup.cold (STB_LOCAL)
ffffffff81fa4fe0-ffffffff81fa50b9: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (0)
Location: net/ipv6/ip6_flowlabel.c:262
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff82135d8d-ffffffff82135da6: __fl6_sock_lookup.cold (STB_LOCAL)
ffffffff820057f0-ffffffff820058a2: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (0)
Location: net/ipv6/ip6_flowlabel.c:262
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff822179c2-ffffffff822179db: __fl6_sock_lookup.cold (STB_LOCAL)
ffffffff820d4600-ffffffff820d46b2: __fl6_sock_lookup (STB_GLOBAL)
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
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffff800010d3eb70)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffff800010d3eb70-ffff800010d3ec84: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (c0e42424)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
c0e42424-c0e42518: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (c000000000e72e90)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
c000000000e72e90-c000000000e72fc0: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffe00087ab8c)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffe00087ab8c-ffffffe00087ac5a: __fl6_sock_lookup (STB_GLOBAL)
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
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15b90)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a15b90-ffffffff81a15c39: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2950)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff819d2950-ffffffff819d29f9: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a80610)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a80610-ffffffff81a806b9: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ip6_flowlabel *__fl6_sock_lookup(struct sock *sk, __be32 label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8ced0)
Location: net/ipv6/ip6_flowlabel.c:259
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a8ced0-ffffffff81a8cf79: __fl6_sock_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
