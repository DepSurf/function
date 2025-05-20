# Function: <code>sk_nocaps_add</code>

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
In net/ipv4/tcp_output.c (ffffffff81776176)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c0d9)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff817c72af)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff817e30b1)
Location: include/net/sock.h:1756
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eaca8)
Location: include/net/sock.h:1756
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff8183438f)
Location: include/net/sock.h:1756
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff81813762)
Location: include/net/sock.h:1818
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b5f8)
Location: include/net/sock.h:1818
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81865def)
Location: include/net/sock.h:1818
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff818339d8)
Location: include/net/sock.h:1843
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183be84)
Location: include/net/sock.h:1843
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff8188a5c6)
Location: include/net/sock.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff818b2cd8)
Location: include/net/sock.h:1857
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b98f7)
Location: include/net/sock.h:1857
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff8190b770)
Location: include/net/sock.h:1857
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff81908192)
Location: include/net/sock.h:1868
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819101a4)
Location: include/net/sock.h:1868
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81962fb5)
Location: include/net/sock.h:1868
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff81936472)
Location: include/net/sock.h:1953
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e71b)
Location: include/net/sock.h:1953
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81997fa3)
Location: include/net/sock.h:1953
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff8199a835)
Location: include/net/sock.h:1965
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a2b69)
Location: include/net/sock.h:1965
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81a03f71)
Location: include/net/sock.h:1965
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff819d1274)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d974e)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81a3ab5a)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff81abe317)
Location: include/net/sock.h:2024
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac660e)
Location: include/net/sock.h:2024
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b30119)
Location: include/net/sock.h:2024
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff81ac9c04)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad394e)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ebb9)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff81ab4a8c)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe9e9)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b961)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff81b71a4a)
Location: include/net/sock.h:2100
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c527)
Location: include/net/sock.h:2100
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1a41)
Location: include/net/sock.h:2100
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/ipv4/tcp_output.c (ffff800010c83e70)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8cc6c)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffff800010cfbc34)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (c0d93108)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c0d9ce94)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (c0e02b0c)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (c000000000d8f884)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9bbd8)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (c000000000e23428)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffe0007e59ec)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ec13a)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffe0008465b0)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff819710e4)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819795be)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff819da1ea)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff8192abb4)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193307e)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81996faa)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff819db8b4)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e3d8e)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81a44c6a)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv4/tcp_output.c (ffffffff819e5534)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819edeae)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81a5092a)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
</details>
</li>
</ul>

## Differences
