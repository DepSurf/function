# Function: <code>__skb_incr_checksum_unnecessary</code>

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
In net/ipv4/tcp_offload.c (ffffffff81783b4c)
Location: include/linux/skbuff.h:3104
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178b7d9)
Location: include/linux/skbuff.h:3104
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a5051)
Location: include/linux/skbuff.h:3104
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818013d3)
Location: include/linux/skbuff.h:3104
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81801b48)
Location: include/linux/skbuff.h:3104
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff817f1160)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff817f8f54)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8181312c)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81866eae)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872c71)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff81821ef0)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829e24)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8184463c)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818995ae)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a7291)
Location: include/linux/skbuff.h:3363
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff81842b24)
Location: include/linux/skbuff.h:3431
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184b063)
Location: include/linux/skbuff.h:3431
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865eb5)
Location: include/linux/skbuff.h:3431
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818bf629)
Location: include/linux/skbuff.h:3431
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdca4)
Location: include/linux/skbuff.h:3431
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff818c2484)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818cacc3)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5fe7)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819426f9)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952aa4)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff819180cf)
Location: include/linux/skbuff.h:3625
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81920b8f)
Location: include/linux/skbuff.h:3625
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c885)
Location: include/linux/skbuff.h:3625
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8199b6a5)
Location: include/linux/skbuff.h:3625
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819ac050)
Location: include/linux/skbuff.h:3625
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff8194681c)
Location: include/linux/skbuff.h:3710
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194ff97)
Location: include/linux/skbuff.h:3710
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c569)
Location: include/linux/skbuff.h:3710
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d1e95)
Location: include/linux/skbuff.h:3710
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2c2d)
Location: include/linux/skbuff.h:3710
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff819aae7e)
Location: include/linux/skbuff.h:3819
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b4863)
Location: include/linux/skbuff.h:3819
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d32c1)
Location: include/linux/skbuff.h:3819
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a40e4e)
Location: include/linux/skbuff.h:3819
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a51984)
Location: include/linux/skbuff.h:3819
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff819e1b4e)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819eb593)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09e31)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a77ace)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a88584)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/filter.c (ffffffff81a2306a)
Location: include/linux/skbuff.h:3912
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf20c)
Location: include/linux/skbuff.h:3912
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad9213)
Location: include/linux/skbuff.h:3912
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa5b3)
Location: include/linux/skbuff.h:3912
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b71d28)
Location: include/linux/skbuff.h:3912
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83b78)
Location: include/linux/skbuff.h:3912
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/filter.c (ffffffff81a233ca)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb211)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5c2a)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07d61)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b80a74)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b93226)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/filter.c (ffffffff81a0a6ea)
Location: include/linux/skbuff.h:4005
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6268)
Location: include/linux/skbuff.h:4005
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0f1a)
Location: include/linux/skbuff.h:4005
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af356d)
Location: include/linux/skbuff.h:4005
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f67e)
Location: include/linux/skbuff.h:4005
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b822c5)
Location: include/linux/skbuff.h:4005
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/filter.c (ffffffff81abcbca)
Location: include/linux/skbuff.h:4042
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84a78)
Location: include/linux/skbuff.h:4042
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f937)
Location: include/linux/skbuff.h:4042
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3a7d)
Location: include/linux/skbuff.h:4042
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81c3773b)
Location: include/linux/skbuff.h:4042
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e375)
Location: include/linux/skbuff.h:4042
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/filter.c (ffffffff81c376ca)
Location: include/linux/skbuff.h:4461
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_offload.c (ffffffff81d152d2)
Location: include/linux/skbuff.h:4461
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d20c2a)
Location: include/linux/skbuff.h:4461
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d47298)
Location: include/linux/skbuff.h:4461
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5125)
Location: include/linux/skbuff.h:4461
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deec18)
Location: include/linux/skbuff.h:4461
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/filter.c (ffffffff81deaf2a)
Location: include/linux/skbuff.h:4357
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb4b2)
Location: include/linux/skbuff.h:4357
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7ea4)
Location: include/linux/skbuff.h:4357
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f102ad)
Location: include/linux/skbuff.h:4357
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6825)
Location: include/linux/skbuff.h:4357
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2c68)
Location: include/linux/skbuff.h:4357
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/filter.c (ffffffff81e5c72a)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a572)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f4772d)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6ff9d)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8200721b)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023bf7)
Location: include/linux/skbuff.h:4389
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/filter.c (ffffffff81f1bb1a)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_offload.c (ffffffff82000662)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d86d)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff820366cd)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff820d607b)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2d57)
Location: include/linux/skbuff.h:4429
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffff800010c95b58)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca0f08)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc3178)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffff800010d40f50)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d5512c)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (c0da4338)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad60c)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce9d0)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c0e43978)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (c0e556e0)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (c000000000da6ed0)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3df8)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde8d4)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c000000000e757b0)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8de80)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffe0007f4d44)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd564)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe00081858c)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffe00087c6fc)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c970)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff819819be)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198b403)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9bd1)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a1715e)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27c14)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff8193b47e)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81944ec3)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81963691)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d3f1e)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e49d4)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff819ec18e)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f5bd3)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a14471)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a81bde)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a937c4)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/ipv4/tcp_offload.c (ffffffff819f603e)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ffdd3)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ee73)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e4de)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f914)
Location: include/linux/skbuff.h:3886
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
</details>
</li>
</ul>

## Differences
