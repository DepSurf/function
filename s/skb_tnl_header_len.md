# Function: <code>skb_tnl_header_len</code>

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
In net/core/skbuff.c (ffffffff8170aaf8)
Location: include/linux/skbuff.h:3456
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8178af94)
Location: include/linux/skbuff.h:3456
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff817a5248)
Location: include/linux/skbuff.h:3456
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81801726)
Location: include/linux/skbuff.h:3456
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff81772702)
Location: include/linux/skbuff.h:3667
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff817f8860)
Location: include/linux/skbuff.h:3667
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81812b82)
Location: include/linux/skbuff.h:3667
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81866aa7)
Location: include/linux/skbuff.h:3667
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff8179f7fc)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81829711)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8184407b)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff818991a7)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff817be85b)
Location: include/linux/skbuff.h:3783
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8184a726)
Location: include/linux/skbuff.h:3783
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818658f9)
Location: include/linux/skbuff.h:3783
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff818bf3cf)
Location: include/linux/skbuff.h:3783
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff81838132)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff818ca3a6)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818e5a3c)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff8194252b)
Location: include/linux/skbuff.h:3974
Inline: True
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
In net/core/skbuff.c (ffffffff818826bc)
Location: include/linux/skbuff.h:3984
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819206d6)
Location: include/linux/skbuff.h:3984
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8193c316)
Location: include/linux/skbuff.h:3984
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff8199b35d)
Location: include/linux/skbuff.h:3984
Inline: True
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
In net/core/skbuff.c (ffffffff818a316c)
Location: include/linux/skbuff.h:4147
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8194f50d)
Location: include/linux/skbuff.h:4147
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196c014)
Location: include/linux/skbuff.h:4147
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff819d1c91)
Location: include/linux/skbuff.h:4147
Inline: True
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
In net/core/skbuff.c (ffffffff818ede0a)
Location: include/linux/skbuff.h:4254
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819b3d43)
Location: include/linux/skbuff.h:4254
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819d2d5e)
Location: include/linux/skbuff.h:4254
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81a40a53)
Location: include/linux/skbuff.h:4254
Inline: True
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
In net/core/skbuff.c (ffffffff8191fefe)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819eaa73)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a098cf)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81a776d3)
Location: include/linux/skbuff.h:4338
Inline: True
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
In net/core/skbuff.c (ffffffff819f34f4)
Location: include/linux/skbuff.h:4378
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/ipv4/udp_offload.c (ffffffff81ad86b9)
Location: include/linux/skbuff.h:4378
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81afa03f)
Location: include/linux/skbuff.h:4378
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81b71a03)
Location: include/linux/skbuff.h:4378
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff819f3524)
Location: include/linux/skbuff.h:4407
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4bec)
Location: include/linux/skbuff.h:4407
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81b077b7)
Location: include/linux/skbuff.h:4407
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81b806a7)
Location: include/linux/skbuff.h:4407
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff819d977b)
Location: include/linux/skbuff.h:4471
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/ipv4/udp_offload.c (ffffffff81acfe09)
Location: include/linux/skbuff.h:4471
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81af2f7b)
Location: include/linux/skbuff.h:4471
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f2ca)
Location: include/linux/skbuff.h:4471
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff81a89730)
Location: include/linux/skbuff.h:4510
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e829)
Location: include/linux/skbuff.h:4510
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81bb348b)
Location: include/linux/skbuff.h:4510
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81c3738a)
Location: include/linux/skbuff.h:4510
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff81bfea87)
Location: include/linux/skbuff.h:4932
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/ipv4/udp_offload.c (ffffffff81d1ff87)
Location: include/linux/skbuff.h:4932
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81d46cba)
Location: include/linux/skbuff.h:4932
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81dd4f2d)
Location: include/linux/skbuff.h:4932
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff81dad4c3)
Location: include/linux/skbuff.h:4828
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7184)
Location: include/linux/skbuff.h:4828
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f1050a)
Location: include/linux/skbuff.h:4828
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6633)
Location: include/linux/skbuff.h:4828
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff81e1d3b8)
Location: include/net/gso.h:26
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/ipv4/udp_offload.c (ffffffff81f46a27)
Location: include/net/gso.h:26
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f701f4)
Location: include/net/gso.h:26
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff82006e7d)
Location: include/net/gso.h:26
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffffffff81edaaa4)
Location: include/net/gso.h:26
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
```
```
In net/ipv4/udp_offload.c (ffffffff8200cb67)
Location: include/net/gso.h:26
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff82036924)
Location: include/net/gso.h:26
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff820d5cdd)
Location: include/net/gso.h:26
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In net/core/skbuff.c (ffff800010bba98c)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffff800010cc2c50)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffff800010d40d38)
Location: include/linux/skbuff.h:4338
Inline: True
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
In net/core/skbuff.c (c0cd7118)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (c0dad8bc)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c0dce484)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (c0e43734)
Location: include/linux/skbuff.h:4338
Inline: True
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
In net/core/skbuff.c (c000000000c93648)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (c000000000db2ddc)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c000000000ddeaf4)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (c000000000e754b0)
Location: include/linux/skbuff.h:4338
Inline: True
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
In net/core/skbuff.c (ffffffe000749b62)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcc90)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffe000818062)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffe00087c52a)
Location: include/linux/skbuff.h:4338
Inline: True
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
In net/core/skbuff.c (ffffffff818bfefe)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8198a8e3)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819a966f)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81a16d63)
Location: include/linux/skbuff.h:4338
Inline: True
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
In net/core/skbuff.c (ffffffff81879e3e)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819443a3)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196312f)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff819d3b23)
Location: include/linux/skbuff.h:4338
Inline: True
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
In net/core/skbuff.c (ffffffff81910efe)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819f50b3)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a13f0f)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81a817e3)
Location: include/linux/skbuff.h:4338
Inline: True
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
In net/core/skbuff.c (ffffffff8193205e)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819ff2b8)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e8ff)
Location: include/linux/skbuff.h:4338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e0e3)
Location: include/linux/skbuff.h:4338
Inline: True
```
</details>
</li>
</ul>

## Differences
