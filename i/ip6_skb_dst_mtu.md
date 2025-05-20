# Function: <code>ip6_skb_dst_mtu</code>

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
In net/ipv6/ip6_output.c (ffffffff817c71b5)
Location: include/net/ip6_route.h:178
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd0f0)
Location: include/net/ip6_route.h:178
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv6/ip6_output.c (ffffffff81834295)
Location: include/net/ip6_route.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186ca20)
Location: include/net/ip6_route.h:198
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv6/ip6_output.c (ffffffff81865cf5)
Location: include/net/ip6_route.h:203
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f810)
Location: include/net/ip6_route.h:203
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ip6_skb_dst_mtu(struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8188a517)
Location: include/net/ip6_route.h:204
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5f82)
Location: include/net/ip6_route.h:204
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff818c5c60-ffffffff818c5cc0: ip6_skb_dst_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ip6_skb_dst_mtu(struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8190b717)
Location: include/net/ip6_route.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff8194931c)
Location: include/net/ip6_route.h:221
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81948fd0-ffffffff81949037: ip6_skb_dst_mtu (STB_LOCAL)
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
In net/ipv6/ip6_output.c (ffffffff81962b42)
Location: include/net/ip6_route.h:243
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a2234)
Location: include/net/ip6_route.h:243
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (ffffffff81997b37)
Location: include/net/ip6_route.h:243
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8e91)
Location: include/net/ip6_route.h:243
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (ffffffff81a03c2e)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47703)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (ffffffff81a3a80c)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e283)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/xfrm/xfrm_output.c (ffffffff81b1f04d)
Location: include/net/ip6_route.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2fdea)
Location: include/net/ip6_route.h:265
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78f99)
Location: include/net/ip6_route.h:265
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/xfrm/xfrm_output.c (ffffffff81b2d90d)
Location: include/net/ip6_route.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e88a)
Location: include/net/ip6_route.h:265
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87f19)
Location: include/net/ip6_route.h:265
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/xfrm/xfrm_output.c (ffffffff81b1b970)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b62e)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76b89)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/xfrm/xfrm_output.c (ffffffff81be01fc)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1737)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c415eb)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/xfrm/xfrm_output.c (ffffffff81d7710e)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a0cf)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfe07)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/xfrm/xfrm_output.c (ffffffff81f4398e)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81f5805f)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb2127)
Location: include/net/ip6_route.h:266
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/xfrm/xfrm_output.c (ffffffff81fa3168)
Location: include/net/ip6_route.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7c3c)
Location: include/net/ip6_route.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff82012834)
Location: include/net/ip6_route.h:262
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/xfrm/xfrm_output.c (ffffffff820707e8)
Location: include/net/ip6_route.h:261
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff8208527c)
Location: include/net/ip6_route.h:261
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e199f)
Location: include/net/ip6_route.h:261
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv6/ip6_output.c (ffff800010cfb894)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffff800010d496ac)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (c0e02788)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (c0e4aa7c)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (c000000000e22f8c)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ed40)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (ffffffe000846236)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882b26)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (ffffffff819d9e9c)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d913)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (ffffffff81996c5c)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da6d3)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (ffffffff81a4491c)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a88393)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/ip6_output.c (ffffffff81a505dc)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a94fe3)
Location: include/net/ip6_route.h:263
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
