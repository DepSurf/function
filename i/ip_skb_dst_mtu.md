# Function: <code>ip_skb_dst_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175c71a)
Location: include/net/ip.h:320
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817c9511)
Location: include/net/ip.h:317
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817f94a1)
Location: include/net/ip.h:346
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
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
In net/ipv4/ip_output.c (ffffffff818198f1)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff81872559)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff81897f21)
Location: include/net/ip.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2f4f)
Location: include/net/ip.h:369
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff818ec1cd)
Location: include/net/ip.h:388
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8194985e)
Location: include/net/ip.h:388
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff8191936d)
Location: include/net/ip.h:412
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b51b)
Location: include/net/ip.h:412
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff8197b6e1)
Location: include/net/ip.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4a4b)
Location: include/net/ip.h:450
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff819b1dd2)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1ba6b)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff81a9c662)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f989)
Location: include/net/ip.h:451
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81aa64c2)
Location: include/net/ip.h:454
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e259)
Location: include/net/ip.h:454
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int ip_skb_dst_mtu(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a90a60)
Location: include/net/ip.h:455
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bc04)
Location: include/net/ip.h:455
Inline: True
```
**Symbols:**

```
ffffffff81a90a60-ffffffff81a90b2a: ip_skb_dst_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ip_skb_dst_mtu(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4bc2a)
Location: include/net/ip.h:469
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/net/ip.h:469
Inline: False
```
**Symbols:**

```
ffffffff81b4bbe0-ffffffff81b4bd26: ip_skb_dst_mtu (STB_LOCAL)
ffffffff81d3a0ee-ffffffff81d3a10e: ip_skb_dst_mtu.cold (STB_LOCAL)
ffffffff81be0010-ffffffff81be0174: ip_skb_dst_mtu (STB_LOCAL)
ffffffff81d3eef2-ffffffff81d3ef12: ip_skb_dst_mtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ip_skb_dst_mtu(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cd932a)
Location: include/net/ip.h:475
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77397)
Location: include/net/ip.h:475
Inline: True
```
**Symbols:**

```
ffffffff81cd92e0-ffffffff81cd9458: ip_skb_dst_mtu (STB_LOCAL)
ffffffff81f06870-ffffffff81f06890: ip_skb_dst_mtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ip_skb_dst_mtu(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e99a7a)
Location: include/net/ip.h:475
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43c27)
Location: include/net/ip.h:475
Inline: True
```
**Symbols:**

```
ffffffff81e99a30-ffffffff81e99ba8: ip_skb_dst_mtu (STB_LOCAL)
ffffffff820ae351-ffffffff820ae371: ip_skb_dst_mtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ip_skb_dst_mtu(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81ef83e7)
Location: include/net/ip.h:484
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3405)
Location: include/net/ip.h:484
Inline: True
```
**Symbols:**

```
ffffffff81ef83a0-ffffffff81ef8516: ip_skb_dst_mtu (STB_LOCAL)
ffffffff8212f878-ffffffff8212f891: ip_skb_dst_mtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ip_skb_dst_mtu(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fbc309)
Location: include/net/ip.h:494
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/net/ip.h:494
Inline: False
```
**Symbols:**

```
ffffffff81fbc2c0-ffffffff81fbc428: ip_skb_dst_mtu (STB_LOCAL)
ffffffff82211605-ffffffff8221161e: ip_skb_dst_mtu.cold (STB_LOCAL)
ffffffff820703f0-ffffffff8207058d: ip_skb_dst_mtu (STB_LOCAL)
ffffffff82215ea9-ffffffff82215ec6: ip_skb_dst_mtu.cold (STB_LOCAL)
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
In net/ipv4/ip_output.c (ffff800010c63adc)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7d04)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (c0d71fc4)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (c0de17e0)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (c000000000d65c48)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (c000000000df7d94)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffe0007ca3a2)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffe000828300)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff81951c42)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb0fb)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff8190b732)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977eeb)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff819bc412)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25b7b)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_output.c (ffffffff819c5d22)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a3101b)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
