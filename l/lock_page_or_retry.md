# Function: <code>lock_page_or_retry</code>

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
In mm/filemap.c (ffffffff8118f80c)
Location: include/linux/pagemap.h:481
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/memory.c (ffffffff811bfa2d)
Location: include/linux/pagemap.h:481
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/dax.c (ffffffff8125dcc2)
Location: include/linux/pagemap.h:481
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
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
In mm/filemap.c (ffffffff811a360a)
Location: include/linux/pagemap.h:458
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/memory.c (ffffffff811d9bdd)
Location: include/linux/pagemap.h:458
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/filemap.c (ffffffff811b382e)
Location: include/linux/pagemap.h:477
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/memory.c (ffffffff811e970c)
Location: include/linux/pagemap.h:477
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/filemap.c (ffffffff811ba60b)
Location: include/linux/pagemap.h:493
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/memory.c (ffffffff811f4859)
Location: include/linux/pagemap.h:493
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/filemap.c (ffffffff811cde73)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/memory.c (ffffffff8120c633)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/filemap.c (ffffffff811ef9ae)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/memory.c (ffffffff8122d279)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/filemap.c (ffffffff81201c03)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/memory.c (ffffffff8124080f)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff81252ab0)
Location: include/linux/pagemap.h:493
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff81261010)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff81291492)
Location: include/linux/pagemap.h:544
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff8129be02)
Location: include/linux/pagemap.h:649
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff812a109d)
Location: include/linux/pagemap.h:665
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff812e2018)
Location: include/linux/pagemap.h:664
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
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
In mm/memory.c (ffffffff81343c84)
Location: include/linux/pagemap.h:1001
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f83b0)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (c051ab88)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (c0000000003c1718)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffe000208914)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff81259660)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff8124bad7)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff81257400)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
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
In mm/memory.c (ffffffff81266dee)
Location: include/linux/pagemap.h:503
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
</details>
</li>
</ul>

## Differences
