# Function: <code>ip_sk_use_pmtu</code>

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
In net/ipv4/ip_output.c (0)
Location: include/net/ip.h:296
Inline: True
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
In net/ipv4/ip_output.c (0)
Location: include/net/ip.h:293
Inline: True
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
In net/ipv4/ip_output.c (0)
Location: include/net/ip.h:322
Inline: True
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
In net/ipv4/ip_output.c (0)
Location: include/net/ip.h:334
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/net/ip.h:334
Inline: True
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
In net/ipv4/ip_output.c (0)
Location: include/net/ip.h:345
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/net/ip.h:345
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
In net/ipv4/ip_output.c (ffffffff818eb9c7)
Location: include/net/ip.h:364
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8194987c)
Location: include/net/ip.h:364
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
In net/ipv4/ip_output.c (ffffffff81919213)
Location: include/net/ip.h:388
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b539)
Location: include/net/ip.h:388
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
In net/ipv4/ip_output.c (ffffffff8197b547)
Location: include/net/ip.h:426
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4a69)
Location: include/net/ip.h:426
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
In net/ipv4/ip_output.c (ffffffff819b2430)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1ba89)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (ffffffff81a9ba80)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f9af)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (ffffffff81aa58e0)
Location: include/net/ip.h:424
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e27f)
Location: include/net/ip.h:424
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81a91020)
Location: include/net/ip.h:425
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bc2a)
Location: include/net/ip.h:425
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81b4bdb0)
Location: include/net/ip.h:425
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0054)
Location: include/net/ip.h:425
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
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
In net/ipv4/ip_output.c (ffffffff81cd94e0)
Location: include/net/ip.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/xfrm/xfrm_output.c (ffffffff81d773d3)
Location: include/net/ip.h:431
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81e99c40)
Location: include/net/ip.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43c63)
Location: include/net/ip.h:431
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81ef83de)
Location: include/net/ip.h:440
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3443)
Location: include/net/ip.h:440
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81fbc2fe)
Location: include/net/ip.h:449
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff82070431)
Location: include/net/ip.h:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
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
In net/ipv4/ip_output.c (ffff800010c61fb8)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7d28)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (c0d719e4)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (c0de1804)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (c000000000d665d4)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (c000000000df7dc4)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (ffffffe0007caa00)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082831c)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (ffffffff819522a0)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb119)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (ffffffff8190bd90)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977f09)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (ffffffff819bca70)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25b99)
Location: include/net/ip.h:427
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
In net/ipv4/ip_output.c (ffffffff819c6380)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a31039)
Location: include/net/ip.h:427
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
</details>
</li>
</ul>

## Differences
