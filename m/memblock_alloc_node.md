# Function: <code>memblock_alloc_node</code>

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
In mm/sparse.c (ffffffff81a20f00)
Location: include/linux/memblock.h:396
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81a914c3)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81ac87f0)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81bc11f0)
Location: include/linux/memblock.h:403
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81c3a242)
Location: include/linux/memblock.h:436
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81c2dac2)
Location: include/linux/memblock.h:436
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81d4c3b7)
Location: include/linux/memblock.h:437
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81f1becf)
Location: include/linux/memblock.h:453
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff820c3e72)
Location: include/linux/memblock.h:453
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff82147c22)
Location: include/linux/memblock.h:452
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff8222a521)
Location: include/linux/memblock.h:464
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffff80001145a164)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_index_alloc
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
In mm/page_alloc.c (c0e989ec)
Location: include/linux/memblock.h:397
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
In arch/powerpc/platforms/powernv/setup.c (c00000000135ac18)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/setup.c:pnv_probe
```
```
In mm/sparse.c (c000000000417e0c)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffe0000182f0)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81a67660)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81a24120)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81ad3a70)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
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
In mm/sparse.c (ffffffff81adff63)
Location: include/linux/memblock.h:397
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
</details>
</li>
</ul>

## Differences
