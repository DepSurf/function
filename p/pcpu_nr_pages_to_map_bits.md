# Function: <code>pcpu_nr_pages_to_map_bits</code>

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
In mm/percpu.c (ffffffff811f92d0)
Location: mm/percpu-internal.h:85
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff8121aea0)
Location: mm/percpu-internal.h:85
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff8122de50)
Location: mm/percpu-internal.h:85
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff8123dbf3)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff8124c043)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff81279523)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff81283d63)
Location: mm/percpu-internal.h:114
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff81289366)
Location: mm/percpu-internal.h:114
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff812c8411)
Location: mm/percpu-internal.h:99
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff81325d4f)
Location: mm/percpu-internal.h:99
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff8139a86f)
Location: mm/percpu-internal.h:99
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff813cd90f)
Location: mm/percpu-internal.h:107
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff813fb8fb)
Location: mm/percpu-internal.h:107
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_size
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffff8000102e2918)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (c0506bdc)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (c0000000003a2a58)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffe0001f9506)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff81244693)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff81237663)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff81242433)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
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
In mm/percpu.c (ffffffff81251be3)
Location: mm/percpu-internal.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_init_md_blocks
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
</details>
</li>
</ul>

## Differences
