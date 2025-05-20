# Function: <code>pcpu_chunk_nr_blocks</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff826d9aac)
Location: mm/percpu-internal.h:73
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121aeea)
Location: mm/percpu-internal.h:73
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_next_md_free_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122de9a)
Location: mm/percpu-internal.h:73
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8123dc3d)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8124c08d)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff81279565)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff81283da7)
Location: mm/percpu-internal.h:102
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff812893b0)
Location: mm/percpu-internal.h:102
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff812c8455)
Location: mm/percpu-internal.h:87
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff81325d93)
Location: mm/percpu-internal.h:87
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8139a8b3)
Location: mm/percpu-internal.h:87
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff813cd953)
Location: mm/percpu-internal.h:95
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff813f82c3)
Location: mm/percpu-internal.h:95
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffff8000102e2954)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (c0506c10)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (c0000000003a2a98)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffe0001f9540)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff812446dd)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff812376ad)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8124247d)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff81251c2d)
Location: mm/percpu-internal.h:80
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_next_md_free_region
```
</details>
</li>
</ul>

## Differences
