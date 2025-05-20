# Function: <code>tcp_v6_check</code>

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
In net/ipv6/tcp_ipv6.c (ffffffff817ef0b1)
Location: include/net/ip6_checksum.h:59
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81801276)
Location: include/net/ip6_checksum.h:59
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff8185d9b1)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872ab6)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff8188fa04)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a70d6)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff818b609c)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdb46)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81938e26)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952946)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81992710)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abf32)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff819c8e4d)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2b0f)
Location: include/net/ip6_checksum.h:58
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81a3780f)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a5184b)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81a6e339)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a8844b)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81b67fda)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b8391e)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81b7706a)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b92fde)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81b65b8a)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b82139)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81c2c5bb)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e1e9)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81dc9869)
Location: include/net/ip6_checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deea9f)
Location: include/net/ip6_checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81f9a7e9)
Location: include/net/ip6_checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2adf)
Location: include/net/ip6_checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81ffb349)
Location: include/net/ip6_checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023a6f)
Location: include/net/ip6_checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff820c8c29)
Location: include/net/ip6_checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2bcf)
Location: include/net/ip6_checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffff800010d37cb4)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d54fd8)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (c0e388f8)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (c0e55598)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (c000000000e691f4)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dce8)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffe0008740e2)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c84e)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81a0d9c9)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27adb)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff819ca789)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e489b)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81a78449)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9368b)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In net/ipv6/tcp_ipv6.c (ffffffff81a84bb9)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f7db)
Location: include/net/ip6_checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
</details>
</li>
</ul>

## Differences
