# Function: <code>lru_cache_enable</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c21ce)
Location: include/linux/swap.h:352
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81c2d6c1)
Location: include/linux/swap.h:352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/mempolicy.c (ffffffff812e3258)
Location: include/linux/swap.h:352
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff812f8bfb)
Location: include/linux/swap.h:352
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In mm/page_alloc.c (ffffffff81305b54)
Location: include/linux/swap.h:358
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81d4bf93)
Location: include/linux/swap.h:358
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/mempolicy.c (ffffffff8132a644)
Location: include/linux/swap.h:358
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8134325b)
Location: include/linux/swap.h:358
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In mm/page_alloc.c (ffffffff81371d99)
Location: include/linux/swap.h:393
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff81f1b9c3)
Location: include/linux/swap.h:393
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/mempolicy.c (ffffffff81399f87)
Location: include/linux/swap.h:393
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff813b5a88)
Location: include/linux/swap.h:393
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In mm/page_alloc.c (ffffffff813ef579)
Location: include/linux/swap.h:394
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff820c3953)
Location: include/linux/swap.h:394
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/mempolicy.c (ffffffff81419fb5)
Location: include/linux/swap.h:394
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff81435b88)
Location: include/linux/swap.h:394
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In mm/page_alloc.c (ffffffff814230e9)
Location: include/linux/swap.h:391
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82147735)
Location: include/linux/swap.h:391
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/mempolicy.c (ffffffff8144d33b)
Location: include/linux/swap.h:391
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8146b869)
Location: include/linux/swap.h:391
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In mm/page_alloc.c (ffffffff81450019)
Location: include/linux/swap.h:386
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82229f6d)
Location: include/linux/swap.h:386
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/mempolicy.c (ffffffff81486e10)
Location: include/linux/swap.h:386
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8149a844)
Location: include/linux/swap.h:386
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
