# Function: <code>movable_node_is_enabled</code>

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
In mm/page_alloc.c (0)
Location: include/linux/memblock.h:167
Inline: True
```
```
In mm/memblock.c (ffffffff8181dd42)
Location: include/linux/memblock.h:167
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:__next_mem_range_rev
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
In mm/page_alloc.c (0)
Location: include/linux/memblock.h:176
Inline: True
```
```
In mm/memblock.c (ffffffff81898378)
Location: include/linux/memblock.h:176
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
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
In arch/x86/kernel/setup.c (0)
Location: include/linux/memblock.h:176
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/memblock.h:176
Inline: True
```
```
In mm/memblock.c (ffffffff818cca20)
Location: include/linux/memblock.h:176
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
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
In arch/x86/kernel/setup.c (0)
Location: include/linux/memory_hotplug.h:120
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/memory_hotplug.h:120
Inline: True
```
```
In mm/memblock.c (ffffffff81903ec1)
Location: include/linux/memory_hotplug.h:120
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/memory_hotplug.h:120
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
In arch/x86/kernel/setup.c (0)
Location: include/linux/memory_hotplug.h:121
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/memory_hotplug.h:121
Inline: True
```
```
In mm/memblock.c (ffffffff8198dec7)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
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
In arch/x86/kernel/setup.c (ffffffff826d9c98)
Location: include/linux/memory_hotplug.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff82701c2f)
Location: include/linux/memory_hotplug.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/memblock.c (ffffffff819ea7b4)
Location: include/linux/memory_hotplug.h:104
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
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
In arch/x86/kernel/setup.c (ffffffff82890086)
Location: include/linux/memory_hotplug.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff828b8728)
Location: include/linux/memory_hotplug.h:106
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81a25a17)
Location: include/linux/memory_hotplug.h:106
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
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
In arch/x86/kernel/setup.c (ffffffff828a7870)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff828d5835)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff812745a3)
Location: include/linux/memory_hotplug.h:121
Inline: True
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
In arch/x86/kernel/setup.c (ffffffff828aa8ab)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff828ddca9)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff812833b3)
Location: include/linux/memory_hotplug.h:121
Inline: True
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
In arch/x86/kernel/setup.c (ffffffff82ccfc70)
Location: include/linux/memory_hotplug.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff82cfaf83)
Location: include/linux/memory_hotplug.h:127
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff812b5406)
Location: include/linux/memory_hotplug.h:127
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
In arch/x86/kernel/setup.c (ffffffff82fbbaa1)
Location: include/linux/memory_hotplug.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff82fe7bf8)
Location: include/linux/memory_hotplug.h:140
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff812c04d6)
Location: include/linux/memory_hotplug.h:140
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
In arch/x86/kernel/setup.c (ffffffff831c61d1)
Location: include/linux/memory_hotplug.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff831f235a)
Location: include/linux/memory_hotplug.h:140
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff812c5c76)
Location: include/linux/memory_hotplug.h:140
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
In arch/x86/kernel/setup.c (ffffffff832a7068)
Location: include/linux/memory_hotplug.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff832d80f3)
Location: include/linux/memory_hotplug.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff8130a569)
Location: include/linux/memory_hotplug.h:136
Inline: True
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
In arch/x86/kernel/setup.c (ffffffff83456347)
Location: include/linux/memory_hotplug.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff8348d5ea)
Location: include/linux/memory_hotplug.h:189
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81373041)
Location: include/linux/memory_hotplug.h:189
Inline: True
Inline callers:
  - mm/memblock.c:should_skip_region
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
In arch/x86/kernel/setup.c (ffffffff83e7471a)
Location: include/linux/memory_hotplug.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff83ebf3eb)
Location: include/linux/memory_hotplug.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff813f07b1)
Location: include/linux/memory_hotplug.h:180
Inline: True
Inline callers:
  - mm/memblock.c:should_skip_region
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
In arch/x86/kernel/setup.c (ffffffff836961e7)
Location: include/linux/memory_hotplug.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/mm_init.c (ffffffff836e17bb)
Location: include/linux/memory_hotplug.h:180
Inline: True
Inline callers:
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81424341)
Location: include/linux/memory_hotplug.h:180
Inline: True
Inline callers:
  - mm/memblock.c:should_skip_region
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
In arch/x86/kernel/setup.c (ffffffff838c5e38)
Location: include/linux/memory_hotplug.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/mm_init.c (ffffffff839140bb)
Location: include/linux/memory_hotplug.h:198
Inline: True
Inline callers:
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81451161)
Location: include/linux/memory_hotplug.h:198
Inline: True
Inline callers:
  - mm/memblock.c:should_skip_region
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
In mm/page_alloc.c (ffff8000114569f8)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffff80001031b66c)
Location: include/linux/memory_hotplug.h:121
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memory_hotplug.h:282
Inline: True
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
In mm/page_alloc.c (c00000000137f8a4)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (c0000000003eef8c)
Location: include/linux/memory_hotplug.h:121
Inline: True
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
In mm/page_alloc.c (0)
Location: include/linux/memory_hotplug.h:282
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/memory_hotplug.h:282
Inline: True
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
In arch/x86/kernel/setup.c (ffffffff828988bb)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff828c6b5d)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff8127ba03)
Location: include/linux/memory_hotplug.h:121
Inline: True
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
In arch/x86/kernel/setup.c (ffffffff82890bcb)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff828bf282)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff8126d8e3)
Location: include/linux/memory_hotplug.h:121
Inline: True
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
In arch/x86/kernel/setup.c (ffffffff828ab8ab)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff828d98dd)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff812797a3)
Location: include/linux/memory_hotplug.h:121
Inline: True
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
In arch/x86/kernel/setup.c (ffffffff828ab8bb)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffffffff828decfe)
Location: include/linux/memory_hotplug.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81289393)
Location: include/linux/memory_hotplug.h:121
Inline: True
```
</details>
</li>
</ul>

## Differences
