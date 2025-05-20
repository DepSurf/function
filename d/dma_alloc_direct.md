# Function: <code>dma_alloc_direct</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137b0a)
Location: kernel/dma/mapping.c:128
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
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
In kernel/dma/mapping.c (ffffffff811393ba)
Location: kernel/dma/mapping.c:130
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
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
In kernel/dma/mapping.c (ffffffff8115c24a)
Location: kernel/dma/mapping.c:130
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
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
In kernel/dma/mapping.c (ffffffff81185f6b)
Location: kernel/dma/mapping.c:130
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
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
In kernel/dma/mapping.c (ffffffff811c19eb)
Location: kernel/dma/mapping.c:131
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
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
In kernel/dma/mapping.c (ffffffff811d446b)
Location: kernel/dma/mapping.c:135
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
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
In kernel/dma/mapping.c (ffffffff811e9309)
Location: kernel/dma/mapping.c:135
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_addressing_limited
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
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
