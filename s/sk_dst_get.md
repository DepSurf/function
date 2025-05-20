# Function: <code>sk_dst_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817007e0)
Location: include/net/sock.h:1717
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81756eb9)
Location: include/net/sock.h:1717
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8176004b)
Location: include/net/sock.h:1717
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817671ac)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff817c3159)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cc2de)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8179422c)
Location: include/net/sock.h:1740
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff817f18e1)
Location: include/net/sock.h:1740
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fbe47)
Location: include/net/sock.h:1740
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b25fe)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff818131a2)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181c1d9)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818416d2)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182a7be)
Location: include/net/sock.h:1759
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff818927e2)
Location: include/net/sock.h:1759
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189b12f)
Location: include/net/sock.h:1759
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0eea)
Location: include/net/sock.h:1759
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874915)
Location: include/net/sock.h:1770
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff818e67a2)
Location: include/net/sock.h:1770
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef668)
Location: include/net/sock.h:1770
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916a0f)
Location: include/net/sock.h:1770
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895315)
Location: include/net/sock.h:1855
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff819135f6)
Location: include/net/sock.h:1855
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191d228)
Location: include/net/sock.h:1855
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819451bf)
Location: include/net/sock.h:1855
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1c05)
Location: include/net/sock.h:1867
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81975c42)
Location: include/net/sock.h:1867
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197f3ec)
Location: include/net/sock.h:1867
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a979a)
Location: include/net/sock.h:1867
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81913dc5)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff819ac652)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b592c)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e045a)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3855)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81a96b3f)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9fedb)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acda8f)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e33a5)
Location: include/net/sock.h:1941
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81aa0c10)
Location: include/net/sock.h:1941
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa766)
Location: include/net/sock.h:1941
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9acf)
Location: include/net/sock.h:1941
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c93f5)
Location: include/net/sock.h:1958
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81a8bb40)
Location: include/net/sock.h:1958
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95d15)
Location: include/net/sock.h:1958
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4b1d)
Location: include/net/sock.h:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a78795)
Location: include/net/sock.h:1998
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81b46ad0)
Location: include/net/sock.h:1998
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51175)
Location: include/net/sock.h:1998
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b832cd)
Location: include/net/sock.h:1998
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bec163)
Location: include/net/sock.h:2119
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81cd3b69)
Location: include/net/sock.h:2119
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cddf18)
Location: include/net/sock.h:2119
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d138d1)
Location: include/net/sock.h:2119
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d98b43)
Location: include/net/sock.h:2156
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81e93d99)
Location: include/net/sock.h:2156
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea180e)
Location: include/net/sock.h:2156
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed9891)
Location: include/net/sock.h:2156
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e089b3)
Location: include/net/sock.h:2144
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81ef2549)
Location: include/net/sock.h:2144
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81f0064c)
Location: include/net/sock.h:2144
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38971)
Location: include/net/sock.h:2144
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5423)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81fb6664)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc4491)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffea51)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bac168)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffff800010c5c7e8)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffff800010c66858)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c940d0)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccab3c)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (c0d6be8c)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (c0d76364)
Location: include/net/sock.h:1877
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (c0da28ec)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7e718)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (c000000000d5ec1c)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (c000000000d6afe8)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (c000000000da4808)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073ca1e)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffe0007c5686)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd962)
Location: include/net/sock.h:1877
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f360e)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b3dc5)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff8194c4c2)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195579c)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819802ca)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186dd15)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81905fb2)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190f28c)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939d8a)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81904dc5)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff819b6c92)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819bff6c)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819eaa9a)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81925e85)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff819c0501)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c993c)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4967)
Location: include/net/sock.h:1877
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
</details>
</li>
</ul>

## Differences
