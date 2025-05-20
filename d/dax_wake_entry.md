# Function: <code>dax_wake_entry</code>

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
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130bcd0)
Location: fs/dax.c:184
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff8130bcd0-ffffffff8130bd69: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813331f0)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff813331f0-ffffffff81333283: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81346da0)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81346da0-ffffffff81346e33: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138cb20)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff8138cb20-ffffffff8138cbb7: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139e2b0)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff8139e2b0-ffffffff8139e347: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, enum dax_wake_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a5370)
Location: fs/dax.c:195
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff813a5370-ffffffff813a5403: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, enum dax_wake_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f4de0)
Location: fs/dax.c:195
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff813f4de0-ffffffff813f4e73: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, enum dax_wake_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81468400)
Location: fs/dax.c:195
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff81468400-ffffffff814684a2: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, enum dax_wake_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f8e70)
Location: fs/dax.c:195
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff814f8e70-ffffffff814f8f12: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, enum dax_wake_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152f590)
Location: fs/dax.c:195
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff8152f590-ffffffff8152f632: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, enum dax_wake_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81564470)
Location: fs/dax.c:181
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffffffff81564470-ffffffff81564512: dax_wake_entry (STB_LOCAL)
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
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff800010407170)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
ffff800010407170-ffff80001040722c: dax_wake_entry (STB_LOCAL)
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
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000512470)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
```
**Symbols:**

```
c000000000512470-c000000000512560: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b20c2)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffe0002b20c2-ffffffe0002b214a: dax_wake_entry (STB_LOCAL)
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
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133f380)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8133f380-ffffffff8133f413: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81330040)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81330040-ffffffff813300d3: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133ce50)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8133ce50-ffffffff8133cee3: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dax_wake_entry(struct xa_state *xas, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813500e0)
Location: fs/dax.c:185
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff813500e0-ffffffff81350173: dax_wake_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum dax_wake_mode mode</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wake_all</code>
</li>
</ul>
</details>
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
