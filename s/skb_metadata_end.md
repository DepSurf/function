# Function: <code>skb_metadata_end</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184b863)
Location: include/linux/skbuff.h:3433
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff81895c5b)
Location: include/linux/skbuff.h:3443
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff818b7868)
Location: include/linux/skbuff.h:3522
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (ffffffff818eccf7)
Location: include/linux/skbuff.h:3631
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff819036de)
Location: include/linux/skbuff.h:3631
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (ffffffff8191ee17)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81936491)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (ffffffff819f0875)
Location: include/linux/skbuff.h:3724
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff81a00a8f)
Location: include/linux/skbuff.h:3724
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
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
In net/core/skbuff.c (ffffffff819f0035)
Location: include/linux/skbuff.h:3753
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff81a00e9f)
Location: include/linux/skbuff.h:3753
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
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
In net/core/skbuff.c (ffffffff819d7865)
Location: include/linux/skbuff.h:3817
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff819e7621)
Location: include/linux/skbuff.h:3817
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
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
In net/core/skbuff.c (ffffffff81a860a5)
Location: include/linux/skbuff.h:3854
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff81a9838d)
Location: include/linux/skbuff.h:3854
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
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
In net/core/skbuff.c (ffffffff81bf90a5)
Location: include/linux/skbuff.h:4273
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/gro.c (ffffffff81c53b6e)
Location: include/linux/skbuff.h:4273
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
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
In net/core/skbuff.c (ffffffff81daa685)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/gro.c (ffffffff81e092d3)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
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
In net/core/skbuff.c (ffffffff81e1b845)
Location: include/linux/skbuff.h:4201
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/gro.c (ffffffff81e7bb19)
Location: include/linux/skbuff.h:4201
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
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
In net/core/skbuff.c (ffffffff81ed8e05)
Location: include/linux/skbuff.h:4238
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/gro.c (ffffffff81f3be4b)
Location: include/linux/skbuff.h:4238
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
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
In net/core/skbuff.c (ffff800010bb9618)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffff800010bd4adc)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (c0cd60a8)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (c0cef074)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (c000000000c91bd8)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (c000000000cb3e40)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (ffffffe000748be6)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffe00075e896)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (ffffffff818bee17)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818d6461)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (ffffffff81878d57)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818902a1)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (ffffffff8190fe17)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81927491)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
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
In net/core/skbuff.c (ffffffff81930f47)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81948af9)
Location: include/linux/skbuff.h:3698
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
</ul>

## Differences
