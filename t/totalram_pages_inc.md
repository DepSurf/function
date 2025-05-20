# Function: <code>totalram_pages_inc</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828be1fa)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (ffffffff828d73cd)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (ffffffff828df83e)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (ffffffff82cfcdfa)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe987d)
Location: include/linux/mm.h:66
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3f26)
Location: include/linux/mm.h:66
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832da26c)
Location: include/linux/mm.h:66
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348f2fc)
Location: include/linux/mm.h:59
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec17cf)
Location: include/linux/mm.h:60
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6fdf)
Location: include/linux/mm.h:62
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8391958f)
Location: include/linux/mm.h:62
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
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
In mm/memblock.c (ffff8000114588d4)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/page_alloc.c (c05345a4)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/page_alloc.c:free_highmem_page
```
```
In mm/memblock.c (c1532858)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (c000000001382130)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (ffffffe000016f58)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (ffffffff828c86f2)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (ffffffff828c0e17)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (ffffffff828db472)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
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
In mm/memblock.c (ffffffff828e0893)
Location: include/linux/mm.h:58
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
</details>
</li>
</ul>

## Differences
