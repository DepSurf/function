# Function: <code>inet6_unregister_protosw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff817c3500)
Location: net/ipv6/af_inet6.c:629
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff817c3500-ffffffff817c3561: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff818305b0)
Location: net/ipv6/af_inet6.c:643
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff818305b0-ffffffff81830611: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81862030)
Location: net/ipv6/af_inet6.c:654
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81862030-ffffffff81862091: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff818863a0)
Location: net/ipv6/af_inet6.c:655
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff818863a0-ffffffff81886401: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff819075b0)
Location: net/ipv6/af_inet6.c:660
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff819075b0-ffffffff81907611: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:686
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff8195efbb-ffffffff8195efd0: inet6_unregister_protosw.cold.15 (STB_LOCAL)
ffffffff8195e170-ffffffff8195e1c3: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81993bab)
Location: net/ipv6/af_inet6.c:698
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81993bab-ffffffff81993bc0: inet6_unregister_protosw.cold.17 (STB_LOCAL)
ffffffff81992cd0-ffffffff81992d23: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff819ff661)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff819ff661-ffffffff819ff676: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff819fe760-ffffffff819fe7b3: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a36261)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81a36261-ffffffff81a36276: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff81a35350-ffffffff81a353a3: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b2b31a)
Location: net/ipv6/af_inet6.c:788
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81b2b31a-ffffffff81b2b32f: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff81b2ab60-ffffffff81b2abb6: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81c32b07)
Location: net/ipv6/af_inet6.c:785
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81c32b07-ffffffff81c32b1c: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff81b394f0-ffffffff81b39546: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81c24e17)
Location: net/ipv6/af_inet6.c:789
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81c24e17-ffffffff81c24e2c: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff81b271c0-ffffffff81b27216: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81d3f0b4)
Location: net/ipv6/af_inet6.c:791
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81d3f0b4-ffffffff81d3f0c9: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff81becbb0-ffffffff81becc06: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81f0b9f1)
Location: net/ipv6/af_inet6.c:802
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81f0b9f1-ffffffff81f0ba06: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff81d85070-ffffffff81d850d2: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81f522a0)
Location: net/ipv6/af_inet6.c:811
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81f522a0-ffffffff81f52320: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81fb1cb0)
Location: net/ipv6/af_inet6.c:799
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81fb1cb0-ffffffff81fb1d30: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff8207f3d0)
Location: net/ipv6/af_inet6.c:808
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff8207f3d0-ffffffff8207f450: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffff800010cf6330)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffff800010cf6330-ffff800010cf6418: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (c0dfc708)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
c0dfc708-c0dfc770: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (c000000000e1c280)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
c000000000e1c280-c000000000e1c32c: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffe000841750)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffe000841750-ffffffe0008417c4: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff819d58f1)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff819d58f1-ffffffff819d5906: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff819d49e0-ffffffff819d4a33: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff819926b1)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff819926b1-ffffffff819926c6: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff819917a0-ffffffff819917f3: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a40371)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81a40371-ffffffff81a40386: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff81a3f460-ffffffff81a3f4b3: inet6_unregister_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet6_unregister_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a4bf61)
Location: net/ipv6/af_inet6.c:724
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/raw.c:rawv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
```
**Symbols:**

```
ffffffff81a4bf61-ffffffff81a4bf76: inet6_unregister_protosw.cold (STB_LOCAL)
ffffffff81a4af60-ffffffff81a4afb3: inet6_unregister_protosw (STB_GLOBAL)
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
