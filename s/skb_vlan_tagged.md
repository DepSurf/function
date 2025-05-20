# Function: <code>skb_vlan_tagged</code>

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
In net/core/dev.c (ffffffff8171c39b)
Location: include/linux/if_vlan.h:571
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/dev.c (ffffffff81784d09)
Location: include/linux/if_vlan.h:571
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
In net/core/dev.c (ffffffff817b233d)
Location: include/linux/if_vlan.h:571
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
In net/core/dev.c (ffffffff817cfb48)
Location: include/linux/if_vlan.h:571
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
In net/core/dev.c (ffffffff81849498)
Location: include/linux/if_vlan.h:571
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
In net/core/dev.c (ffffffff81893458)
Location: include/linux/if_vlan.h:650
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
In net/core/dev.c (ffffffff818b3e88)
Location: include/linux/if_vlan.h:685
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819006da)
Location: include/linux/if_vlan.h:680
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81932a0a)
Location: include/linux/if_vlan.h:669
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07aaf)
Location: include/linux/if_vlan.h:684
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff819f151c)
Location: include/linux/if_vlan.h:684
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81a090ca)
Location: include/linux/if_vlan.h:684
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff819d67ac)
Location: include/linux/if_vlan.h:684
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff819ef9db)
Location: include/linux/if_vlan.h:684
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
In net/core/skbuff.c (ffffffff81a86dfc)
Location: include/linux/if_vlan.h:684
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81aa0dfb)
Location: include/linux/if_vlan.h:684
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
In net/core/skbuff.c (ffffffff81bfc55c)
Location: include/linux/if_vlan.h:689
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81c18bf7)
Location: include/linux/if_vlan.h:689
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
In net/core/skbuff.c (ffffffff81dab44c)
Location: include/linux/if_vlan.h:686
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81dc9bc7)
Location: include/linux/if_vlan.h:686
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
In net/core/skbuff.c (ffffffff81e1af4c)
Location: include/linux/if_vlan.h:733
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81e3a737)
Location: include/linux/if_vlan.h:733
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
In net/core/skbuff.c (ffffffff81ed7f3c)
Location: include/linux/if_vlan.h:733
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81ef8acb)
Location: include/linux/if_vlan.h:733
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0a94)
Location: include/linux/if_vlan.h:669
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceb64c)
Location: include/linux/if_vlan.h:669
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caea1c)
Location: include/linux/if_vlan.h:669
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b164)
Location: include/linux/if_vlan.h:669
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d2a0a)
Location: include/linux/if_vlan.h:669
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c89a)
Location: include/linux/if_vlan.h:669
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81923a0a)
Location: include/linux/if_vlan.h:669
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81944e7a)
Location: include/linux/if_vlan.h:669
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
</ul>

## Differences
