# Function: <code>__vma_address</code>

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
In mm/rmap.c (ffffffff811ca5cd)
Location: mm/rmap.c:572
Inline: True
Inline callers:
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
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
In mm/rmap.c (ffffffff811e6b71)
Location: mm/internal.h:319
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
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
In mm/page_vma_mapped.c (ffffffff811f6d7d)
Location: mm/internal.h:322
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f7f11)
Location: mm/internal.h:322
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
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
In mm/page_vma_mapped.c (ffffffff812021dc)
Location: mm/internal.h:336
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8120347b)
Location: mm/internal.h:336
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
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
In mm/page_vma_mapped.c (ffffffff8121addc)
Location: mm/internal.h:337
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121bfbb)
Location: mm/internal.h:337
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
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
In mm/page_vma_mapped.c (ffffffff8123cc2c)
Location: mm/internal.h:337
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123e0d6)
Location: mm/internal.h:337
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8128898f)
Location: mm/internal.h:337
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/page_vma_mapped.c (ffffffff812510fc)
Location: mm/internal.h:337
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81252669)
Location: mm/internal.h:337
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8129d68f)
Location: mm/internal.h:337
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/page_vma_mapped.c (ffffffff812633dc)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812647f6)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812b89c5)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/page_vma_mapped.c (ffffffff81271b8c)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81273066)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812ca8a5)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/page_vma_mapped.c (ffffffff812a21bc)
Location: mm/internal.h:386
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a4096)
Location: mm/internal.h:386
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81300695)
Location: mm/internal.h:386
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/page_vma_mapped.c (ffffffff812adaec)
Location: mm/internal.h:390
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812af966)
Location: mm/internal.h:390
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8130c842)
Location: mm/internal.h:390
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/page_vma_mapped.c (ffff80001030768c)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffff800010308db0)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (0)
Location: mm/internal.h:345
Inline: True
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
In mm/page_vma_mapped.c (c0524ef0)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (c0525908)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
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
In mm/page_vma_mapped.c (c0000000003d61a8)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003d804c)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (c00000000045e940)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/page_vma_mapped.c (ffffffe00021283e)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffe0002133e4)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
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
In mm/page_vma_mapped.c (ffffffff8126a1dc)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126b6b6)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812c2e85)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/page_vma_mapped.c (ffffffff8125c3cc)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125d956)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812b3f85)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/page_vma_mapped.c (ffffffff81267f7c)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81269456)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812c0c95)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/page_vma_mapped.c (ffffffff812778fc)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81278f86)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812d1755)
Location: mm/internal.h:345
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
</ul>

## Differences
