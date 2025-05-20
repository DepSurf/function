# Function: <code>eth_p_mpls</code>

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
In net/core/dev.c (0)
Location: include/net/mpls.h:22
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
In net/core/dev.c (ffffffff81784d66)
Location: include/net/mpls.h:22
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/dev.c (ffffffff817b23b4)
Location: include/net/mpls.h:26
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cfbbf)
Location: include/net/mpls.h:26
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81849512)
Location: include/net/mpls.h:26
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818934d1)
Location: include/net/mpls.h:26
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b3eff)
Location: include/net/mpls.h:26
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff818ecb65)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81900757)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff8191ec85)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81932a87)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff819f1565)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81a0799e)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/dev.c:harmonize_features
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
In net/core/skbuff.c (ffffffff819f15c5)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81a09019)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/dev.c:harmonize_features
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
In net/core/skbuff.c (ffffffff819d6855)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff819efa30)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81a86ea5)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81aa0e50)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81bfc615)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81c18d08)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81dab515)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81dc9cd2)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81e1b015)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81e3a842)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81ed85d5)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81ef8b19)
Location: include/net/mpls.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffff800010bb9488)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffff800010bd0b08)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (c0cd5f28)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (c0ceb6e8)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (c000000000c91a30)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (c000000000caeab0)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffe0007489d4)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffe00075b1c2)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff818bec85)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff818d2a87)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81878bc5)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff8188c917)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff8190fc85)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81923a87)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81930db5)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81944ef7)
Location: include/net/mpls.h:18
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
</ul>

## Differences
