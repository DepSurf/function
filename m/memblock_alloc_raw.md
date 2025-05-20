# Function: <code>memblock_alloc_raw</code>

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
In mm/page_alloc.c (ffffffff828b9dd0)
Location: include/linux/memblock.h:349
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff828d6f23)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff828df394)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff82cfc73e)
Location: include/linux/memblock.h:380
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff82fe9159)
Location: include/linux/memblock.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff831f398b)
Location: include/linux/memblock.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff832d9c87)
Location: include/linux/memblock.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff8348ec61)
Location: include/linux/memblock.h:430
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff83ec0f7c)
Location: include/linux/memblock.h:430
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/mm_init.c (ffffffff836e2c1d)
Location: include/linux/memblock.h:429
Inline: True
Inline callers:
  - mm/mm_init.c:alloc_large_system_hash
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
In mm/mm_init.c (ffffffff83915513)
Location: include/linux/memblock.h:441
Inline: True
Inline callers:
  - mm/mm_init.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffff8000114581ac)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (c1532198)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In arch/powerpc/kernel/prom.c (c000000001349d60)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
```
```
In arch/powerpc/kernel/paca.c (c00000000134baa4)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - arch/powerpc/kernel/paca.c:allocate_paca_ptrs
```
```
In mm/page_alloc.c (c0000000013819c8)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffe000016a70)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff828c8248)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff828c096d)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff828dafc8)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
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
In mm/page_alloc.c (ffffffff828e03e9)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
</details>
</li>
</ul>

## Differences
