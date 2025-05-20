# Function: <code>NF_HOOK_COND</code>

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
In net/ipv4/ip_output.c (ffffffff8175e7fc)
Location: include/linux/netfilter.h:231
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b02f5)
Location: include/linux/netfilter.h:231
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff817c7c4f)
Location: include/linux/netfilter.h:231
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd3c5)
Location: include/linux/netfilter.h:231
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff817cace8)
Location: include/linux/netfilter.h:224
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d235)
Location: include/linux/netfilter.h:224
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81834d7f)
Location: include/linux/netfilter.h:224
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186ccf5)
Location: include/linux/netfilter.h:224
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff817fa95d)
Location: include/linux/netfilter.h:237
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184eafa)
Location: include/linux/netfilter.h:237
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff818668d4)
Location: include/linux/netfilter.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189faea)
Location: include/linux/netfilter.h:237
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff8181ad6c)
Location: include/linux/netfilter.h:228
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8187269a)
Location: include/linux/netfilter.h:228
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff8188aff5)
Location: include/linux/netfilter.h:228
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c60fa)
Location: include/linux/netfilter.h:228
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81899d4c)
Location: include/linux/netfilter.h:230
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f309a)
Location: include/linux/netfilter.h:230
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff8190c215)
Location: include/linux/netfilter.h:230
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff8194949a)
Location: include/linux/netfilter.h:230
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff818ee1ec)
Location: include/linux/netfilter.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff819499aa)
Location: include/linux/netfilter.h:267
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81963698)
Location: include/linux/netfilter.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a257a)
Location: include/linux/netfilter.h:267
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff8191b9b9)
Location: include/linux/netfilter.h:269
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b66a)
Location: include/linux/netfilter.h:269
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81998658)
Location: include/linux/netfilter.h:269
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d91ea)
Location: include/linux/netfilter.h:269
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff8197dc8f)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4b9b)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a0449a)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47a6b)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff819b462f)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bbbb)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b08a)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e61b)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81a9e732)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b0ca51)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b3064f)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b790bb)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81aa8672)
Location: include/linux/netfilter.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b1ad81)
Location: include/linux/netfilter.h:281
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f26f)
Location: include/linux/netfilter.h:281
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b8803b)
Location: include/linux/netfilter.h:281
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81a91d62)
Location: include/linux/netfilter.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b08a68)
Location: include/linux/netfilter.h:281
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c04f)
Location: include/linux/netfilter.h:281
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76d78)
Location: include/linux/netfilter.h:281
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81b4d172)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81bcb968)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81bf21df)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41828)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81cda90f)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81d6145b)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81d8ac1c)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81de002b)
Location: include/linux/netfilter.h:287
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81e9b10f)
Location: include/linux/netfilter.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f2bd7b)
Location: include/linux/netfilter.h:282
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81f58bec)
Location: include/linux/netfilter.h:282
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb236b)
Location: include/linux/netfilter.h:282
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81ef9b2f)
Location: include/linux/netfilter.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f8ba1b)
Location: include/linux/netfilter.h:283
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81fb88bc)
Location: include/linux/netfilter.h:283
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff82012a7b)
Location: include/linux/netfilter.h:283
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81fbda5b)
Location: include/linux/netfilter.h:294
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8205331b)
Location: include/linux/netfilter.h:294
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff82085e9c)
Location: include/linux/netfilter.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1bdb)
Location: include/linux/netfilter.h:294
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffff800010c64d7c)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7e80)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffff800010cfc1a8)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffff800010d49ad0)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (c0d749e4)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (c0de1958)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (c0e0350c)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (c0e4add0)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (c000000000d690dc)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (c000000000df7f64)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (c000000000e23be0)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (c000000000e7f244)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffe0007cc6a2)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffe000828442)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffe000846aac)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882e8a)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff8195449f)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb24b)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff819da71a)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1dcab)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff8190df8f)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197803b)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff819974da)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819daa6b)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff819bec6f)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25ccb)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a4519a)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a8872b)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff819c85ce)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a3116c)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a50e58)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a9537c)
Location: include/linux/netfilter.h:285
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
</details>
</li>
</ul>

## Differences
