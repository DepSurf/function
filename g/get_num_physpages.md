# Function: <code>get_num_physpages</code>

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
In kernel/power/snapshot.c (ffffffff810d1eaf)
Location: include/linux/mm.h:1754
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_write_next
```
```
In mm/page_alloc.c (ffffffff81f86e42)
Location: include/linux/mm.h:1754
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff81fa47ce)
Location: include/linux/mm.h:1754
Inline: True
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
In kernel/power/snapshot.c (ffffffff810d7147)
Location: include/linux/mm.h:1870
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff81fb0ed6)
Location: include/linux/mm.h:1870
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff81fd0d4b)
Location: include/linux/mm.h:1870
Inline: True
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
In kernel/power/snapshot.c (ffffffff810ddcce)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff81fed776)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff8200e6c3)
Location: include/linux/mm.h:1846
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
In kernel/power/snapshot.c (ffffffff810dcdfb)
Location: include/linux/mm.h:1917
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff820cf3de)
Location: include/linux/mm.h:1917
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff820f0164)
Location: include/linux/mm.h:1917
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
In kernel/power/snapshot.c (ffffffff810e5026)
Location: include/linux/mm.h:2019
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff826d7dfe)
Location: include/linux/mm.h:2019
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff826f9959)
Location: include/linux/mm.h:2019
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
In kernel/power/snapshot.c (ffffffff810eccaf)
Location: include/linux/mm.h:2108
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff8270229f)
Location: include/linux/mm.h:2108
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff82723cff)
Location: include/linux/mm.h:2108
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff810f834f)
Location: include/linux/mm.h:2178
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff828b99be)
Location: include/linux/mm.h:2178
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff828dbee4)
Location: include/linux/mm.h:2178
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff81100911)
Location: include/linux/mm.h:2173
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff828d6aaa)
Location: include/linux/mm.h:2173
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff828f67dd)
Location: include/linux/mm.h:2173
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff8110cd71)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff828def3b)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff828ff834)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff81117ee3)
Location: include/linux/mm.h:2414
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff82cfc324)
Location: include/linux/mm.h:2414
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff82d16b6c)
Location: include/linux/mm.h:2414
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff81114323)
Location: include/linux/mm.h:2430
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff82fe8d3f)
Location: include/linux/mm.h:2430
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff830047df)
Location: include/linux/mm.h:2430
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff81114b66)
Location: include/linux/mm.h:2426
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff831f35b5)
Location: include/linux/mm.h:2426
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff8320f289)
Location: include/linux/mm.h:2426
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff81134cd3)
Location: include/linux/mm.h:2455
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff832d97e7)
Location: include/linux/mm.h:2455
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff832f81e1)
Location: include/linux/mm.h:2455
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff81156f70)
Location: include/linux/mm.h:2532
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff8348e78e)
Location: include/linux/mm.h:2532
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff834b0900)
Location: include/linux/mm.h:2532
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff81187cab)
Location: include/linux/mm.h:2696
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff83ec09c5)
Location: include/linux/mm.h:2696
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff83eea6b9)
Location: include/linux/mm.h:2696
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff81198e3b)
Location: include/linux/mm.h:3021
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/mm_init.c (ffffffff836e2fa8)
Location: include/linux/mm.h:3021
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
```
```
In drivers/xen/balloon.c (ffffffff837100aa)
Location: include/linux/mm.h:3021
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff811a7dc7)
Location: include/linux/mm.h:3147
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/mm_init.c (ffffffff83915838)
Location: include/linux/mm.h:3147
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
```
```
In drivers/xen/balloon.c (ffffffff83943a1f)
Location: include/linux/mm.h:3147
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In mm/page_alloc.c (ffff800011457d30)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffff800011491850)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (c03bf770)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (c1531ca8)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
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
In mm/page_alloc.c (c0000000013814a4)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
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
In mm/page_alloc.c (ffffffe00001670c)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
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
In kernel/power/snapshot.c (ffffffff81104f91)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff828c7def)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff828e707a)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff810f6231)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff828c0514)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
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
In kernel/power/snapshot.c (ffffffff81103241)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff828dab6f)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff828fab57)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
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
In kernel/power/snapshot.c (ffffffff8110e631)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/page_alloc.c (ffffffff828dff90)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
```
```
In drivers/xen/balloon.c (ffffffff82900888)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
</details>
</li>
</ul>

## Differences
