# Function: <code>skb_set_inner_mac_header</code>

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
In net/ethernet/eth.c (ffffffff8173ffdc)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/udp_offload.c (ffffffff8178b8fb)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff817a4d05)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff817acd1c)
Location: include/linux/skbuff.h:2115
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff818129dc)
Location: include/linux/skbuff.h:2115
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff817dc36c)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81843edc)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff817fba5c)
Location: include/linux/skbuff.h:2171
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff8186575a)
Location: include/linux/skbuff.h:2171
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff8187940c)
Location: include/linux/skbuff.h:2258
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff818e58b0)
Location: include/linux/skbuff.h:2258
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff818cadec)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff8193c160)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff818f5ebc)
Location: include/linux/skbuff.h:2347
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff8196be70)
Location: include/linux/skbuff.h:2347
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff8195553c)
Location: include/linux/skbuff.h:2435
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff819d2bbc)
Location: include/linux/skbuff.h:2435
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff8198b9dc)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81a0972c)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff81a635dc)
Location: include/linux/skbuff.h:2472
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81af9e9c)
Location: include/linux/skbuff.h:2472
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff81a6b72c)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81b075f6)
Location: include/linux/skbuff.h:2493
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff81a53e5c)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81af2da4)
Location: include/linux/skbuff.h:2509
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff81b0cb6c)
Location: include/linux/skbuff.h:2538
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81bb32b4)
Location: include/linux/skbuff.h:2538
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff81c9355c)
Location: include/linux/skbuff.h:2906
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81d46ac0)
Location: include/linux/skbuff.h:2906
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff81e4ea4c)
Location: include/linux/skbuff.h:2798
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81f0fef0)
Location: include/linux/skbuff.h:2798
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff81eaa0ec)
Location: include/linux/skbuff.h:2852
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fbe0)
Location: include/linux/skbuff.h:2852
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff81f6cb9c)
Location: include/linux/skbuff.h:2859
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff82036310)
Location: include/linux/skbuff.h:2859
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffff800010c369c8)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffff800010cc2af0)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (c0d4933c)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (c0dce310)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (c000000000d2eb44)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (c000000000dde428)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffe0007a83d4)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffe000817f2e)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff8192b84c)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff819a94cc)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff818e55fc)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81962f8c)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff8197c9dc)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81a13d6c)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
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
In net/ethernet/eth.c (ffffffff8199ef2d)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_complete
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e760)
Location: include/linux/skbuff.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
```
</details>
</li>
</ul>

## Differences
