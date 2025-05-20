# Function: <code>skb_pull_inline</code>

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
In net/core/skbuff.c (ffffffff81706a75)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff817401b8)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff8176cd85)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff817acf58)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff8179a205)
Location: include/linux/skbuff.h:1946
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff817dc5a8)
Location: include/linux/skbuff.h:1946
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff817b98a5)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff817fbc68)
Location: include/linux/skbuff.h:1985
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff818327d5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff81879628)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff8187cab5)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff818cb008)
Location: include/linux/skbuff.h:2083
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff8189d925)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff818f61b8)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff818e8905)
Location: include/linux/skbuff.h:2249
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff819557f9)
Location: include/linux/skbuff.h:2249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff81919d95)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff8198bc99)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff819f27b5)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/ethernet/eth.c (ffffffff81a63949)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff819f27a5)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/ethernet/eth.c (ffffffff81a6baa9)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff819d89d9)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/ethernet/eth.c (ffffffff81a54239)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff81a88969)
Location: include/linux/skbuff.h:2352
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/ethernet/eth.c (ffffffff81b0cf4b)
Location: include/linux/skbuff.h:2352
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff81bf4d7b)
Location: include/linux/skbuff.h:2718
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull_data
```
```
In net/ethernet/eth.c (ffffffff81c93881)
Location: include/linux/skbuff.h:2718
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff81da2dab)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull_data
```
```
In net/ethernet/eth.c (ffffffff81e4efb1)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff81e1188b)
Location: include/linux/skbuff.h:2658
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull_data
```
```
In net/ethernet/eth.c (ffffffff81eaa651)
Location: include/linux/skbuff.h:2658
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff81eceb2b)
Location: include/linux/skbuff.h:2665
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull_data
```
```
In net/ethernet/eth.c (ffffffff81f6d101)
Location: include/linux/skbuff.h:2665
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6ee0)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In net/core/skbuff.c (ffff800010bb2dfc)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffff800010c36d10)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In drivers/net/ethernet/freescale/fec_main.c (c0acbdb8)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In net/core/skbuff.c (c0cd10f0)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (c0d49670)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (c000000000c8b0a8)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (c000000000d2ed1c)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffe000744e78)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffe0007a86b4)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff818b9d95)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff8192bb09)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff81873ce5)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff818e58b9)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff8190ad95)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff8197cc99)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/skbuff.c (ffffffff8192be95)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
```
```
In net/ethernet/eth.c (ffffffff8199f209)
Location: include/linux/skbuff.h:2263
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
</details>
</li>
</ul>

## Differences
