# Function: <code>totalram_pages_add</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812066e4)
Location: include/linux/mm.h:67
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff828be664)
Location: include/linux/mm.h:67
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/page_alloc.c (ffffffff8126c694)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff828d7833)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff8129bc02)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff8127b4a4)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff828dfca4)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812aba03)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff812ad63f)
Location: include/linux/mm.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff82cfd116)
Location: include/linux/mm.h:71
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812e0373)
Location: include/linux/mm.h:71
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff812b901f)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff82fe9b47)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812eb2f3)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff812be4ef)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff831f433d)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812c5f73)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff81300c40)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff832da75e)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff8130a973)
Location: include/linux/mm.h:76
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff813680f1)
Location: include/linux/mm.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff8348f875)
Location: include/linux/mm.h:69
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81373561)
Location: include/linux/mm.h:69
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff813e4141)
Location: include/linux/mm.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff83ec1f5a)
Location: include/linux/mm.h:70
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff813f0cd1)
Location: include/linux/mm.h:70
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff81418e91)
Location: include/linux/mm.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff836e75a3)
Location: include/linux/mm.h:72
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81424811)
Location: include/linux/mm.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff814459e1)
Location: include/linux/mm.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff83919da3)
Location: include/linux/mm.h:72
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81451641)
Location: include/linux/mm.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffff80001031397c)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffff800011458e2c)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffff80001034de98)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (c052e004)
Location: include/linux/mm.h:68
Inline: True
```
```
In mm/memblock.c (c1532db4)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/page_alloc.c (c0000000003eccb4)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
```
```
In mm/memblock.c (c000000001382758)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (c00000000042d3ac)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffe00021f6e6)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
```
```
In mm/memblock.c (ffffffe00001743c)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/page_alloc.c (ffffffff81273af4)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff828c8b58)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812a3fe3)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff81265a64)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff828c127d)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81295ab3)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff81271894)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff828db8d8)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812a1df3)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In mm/page_alloc.c (ffffffff812812f4)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
```
```
In mm/memblock.c (ffffffff828e0cf9)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812b1fb3)
Location: include/linux/mm.h:68
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
</details>
</li>
</ul>

## Differences
