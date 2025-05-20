# Function: <code>folio_alloc_buffers</code>

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
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct buffer_head *folio_alloc_buffers(struct folio *folio, long unsigned int size, bool retry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:922
Inline: False
Direct callers:
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff820e8937-ffffffff820e896a: folio_alloc_buffers.cold (STB_LOCAL)
ffffffff81509cf0-ffffffff81509ea8: folio_alloc_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct buffer_head *folio_alloc_buffers(struct folio *folio, long unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:910
Inline: False
Direct callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff821c5736-ffffffff821c5770: folio_alloc_buffers.cold (STB_LOCAL)
ffffffff8153eb20-ffffffff8153ecd5: folio_alloc_buffers (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>bool retry</code>
</li>
</ul>
</details>
</li>
</ul>
