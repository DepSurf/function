# Function: <code>mem_cgroup_swappiness</code>

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
In mm/vmscan.c (ffffffff811a4a81)
Location: include/linux/swap.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:mem_cgroup_shrink_node_zone
```
```
In mm/memcontrol.c (ffffffff811f95b9)
Location: include/linux/swap.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In mm/vmscan.c (ffffffff811badb9)
Location: include/linux/swap.h:530
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/memcontrol.c (ffffffff81894b07)
Location: include/linux/swap.h:530
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In mm/vmscan.c (ffffffff811cb449)
Location: include/linux/swap.h:505
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/memcontrol.c (ffffffff818c9218)
Location: include/linux/swap.h:505
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_limit
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
In mm/vmscan.c (ffffffff811d4059)
Location: include/linux/swap.h:530
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/memcontrol.c (ffffffff819007aa)
Location: include/linux/swap.h:530
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_limit
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
In mm/vmscan.c (ffffffff811e95a9)
Location: include/linux/swap.h:646
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/memcontrol.c (ffffffff8198a7b7)
Location: include/linux/swap.h:646
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_limit
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
In mm/vmscan.c (ffffffff8120ab5d)
Location: include/linux/swap.h:620
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/memcontrol.c (ffffffff819e70b3)
Location: include/linux/swap.h:620
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff8121d85d)
Location: include/linux/swap.h:621
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/memcontrol.c (ffffffff81a22522)
Location: include/linux/swap.h:621
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff8122a636)
Location: include/linux/swap.h:627
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81a92557)
Location: include/linux/swap.h:627
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff81238476)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81ac9d07)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff8126418c)
Location: include/linux/swap.h:636
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81bc22be)
Location: include/linux/swap.h:636
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff8126eb6c)
Location: include/linux/swap.h:655
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81c3b3f5)
Location: include/linux/swap.h:655
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff81273c9b)
Location: include/linux/swap.h:680
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81c2dbb5)
Location: include/linux/swap.h:680
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff812b17c0)
Location: include/linux/swap.h:704
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81d4c4a5)
Location: include/linux/swap.h:704
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff8130c6c0)
Location: include/linux/swap.h:609
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81f1bfe8)
Location: include/linux/swap.h:609
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff8137f33c)
Location: include/linux/swap.h:619
Inline: True
Inline callers:
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff820c3f9b)
Location: include/linux/swap.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff813b2f5c)
Location: include/linux/swap.h:614
Inline: True
Inline callers:
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff82147d4b)
Location: include/linux/swap.h:614
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff813dc54c)
Location: include/linux/swap.h:610
Inline: True
Inline callers:
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff8222a67c)
Location: include/linux/swap.h:610
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffff8000102c9230)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffff800010d9d65c)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (c04f3160)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (c0e98dc8)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (c000000000385658)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (c00000000045bccc)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffe0001e86de)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffe0008c48ca)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff81230ac6)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81a68b77)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff81223b86)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81a25637)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff8122e866)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81ad4f87)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
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
In mm/vmscan.c (ffffffff8123dc76)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/memcontrol.c (ffffffff81ae1457)
Location: include/linux/swap.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
```
</details>
</li>
</ul>

## Differences
