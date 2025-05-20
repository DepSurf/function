# Function: <code>get_unlocked_entry</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130ca70)
Location: fs/dax.c:209
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8130ca70-ffffffff8130cb8d: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81334010)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81334010-ffffffff8133414e: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81347bc0)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81347bc0-ffffffff81347d02: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138d150)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8138d150-ffffffff8138d292: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139e8e0)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8139e8e0-ffffffff8139ea22: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a59d0)
Location: fs/dax.c:223
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff813a59d0-ffffffff813a5b12: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f5440)
Location: fs/dax.c:223
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff813f5440-ffffffff813f5582: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814682b0)
Location: fs/dax.c:223
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff814682b0-ffffffff814683f9: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f8700)
Location: fs/dax.c:223
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff814f8700-ffffffff814f8849: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152f360)
Location: fs/dax.c:223
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8152f360-ffffffff8152f4a1: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81564240)
Location: fs/dax.c:209
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81564240-ffffffff81564381: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff800010407f18)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffff800010407f18-ffff8000104080ac: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000513a90)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
c000000000513a90-c000000000513cc0: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b29ae)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffe0002b29ae-ffffffe0002b2b04: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813401a0)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff813401a0-ffffffff813402e2: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81330e30)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81330e30-ffffffff81330f6c: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133dc70)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8133dc70-ffffffff8133ddb2: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *get_unlocked_entry(struct xa_state *xas, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81350180)
Location: fs/dax.c:212
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81350180-ffffffff813502b8: get_unlocked_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
