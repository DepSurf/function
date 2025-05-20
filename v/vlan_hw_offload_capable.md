# Function: <code>vlan_hw_offload_capable</code>

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
In net/core/dev.c (ffffffff8171c5b9)
Location: include/linux/if_vlan.h:274
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738afc)
Location: include/linux/if_vlan.h:274
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81784f30)
Location: include/linux/if_vlan.h:274
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817a4dd0)
Location: include/linux/if_vlan.h:274
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff817b2540)
Location: include/linux/if_vlan.h:292
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817d3840)
Location: include/linux/if_vlan.h:292
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff817cfd3c)
Location: include/linux/if_vlan.h:292
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817f2bf6)
Location: include/linux/if_vlan.h:292
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff8184968c)
Location: include/linux/if_vlan.h:292
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8186e1c0)
Location: include/linux/if_vlan.h:292
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff8189368f)
Location: include/linux/if_vlan.h:316
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818bf108)
Location: include/linux/if_vlan.h:316
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff818b40ac)
Location: include/linux/if_vlan.h:327
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818e7f35)
Location: include/linux/if_vlan.h:327
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff8190097f)
Location: include/linux/if_vlan.h:322
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81937898)
Location: include/linux/if_vlan.h:322
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81932caf)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8196a758)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81a049d5)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a3de58)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81a05755)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a40b78)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff819ee0e5)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a25838)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81a9f385)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81ada578)
Location: include/linux/if_vlan.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81c18edc)
Location: include/linux/if_vlan.h:318
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81c5bd6f)
Location: include/linux/if_vlan.h:318
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81dc9ead)
Location: include/linux/if_vlan.h:318
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e121d0)
Location: include/linux/if_vlan.h:318
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81e3aa39)
Location: include/linux/if_vlan.h:326
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e85a10)
Location: include/linux/if_vlan.h:326
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81ef8de9)
Location: include/linux/if_vlan.h:326
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81f47940)
Location: include/linux/if_vlan.h:326
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffff800010bd0cd0)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffff800010c10b10)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (c0ceb908)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c0d28a4c)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (c000000000caed44)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c000000000cfd700)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffe00075b340)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffe00078d252)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff818d2caf)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8190a728)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff8188cb3f)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818c4778)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81923caf)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8195b758)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff8194511f)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8197d978)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
</ul>

## Differences
