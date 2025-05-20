# Function: <code>xas_set_mark</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17080)
Location: lib/xarray.c:850
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_fcntl
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffffffff81a17080-ffffffff81a170dd: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a86d20)
Location: lib/xarray.c:869
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffffffff81a86d20-ffffffff81a86d6e: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abdf90)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffffffff81abdf90-ffffffff81abdfde: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815f9f90)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff815f9f90-ffffffff815f9fe1: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161e790)
Location: lib/xarray.c:873
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff8161e790-ffffffff8161e7e1: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816020d0)
Location: lib/xarray.c:873
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff816020d0-ffffffff81602120: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff816708d0)
Location: lib/xarray.c:873
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81cdfdb3-ffffffff81cdfe18: xas_set_mark.cold (STB_LOCAL)
ffffffff81670880-ffffffff816708f8: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff8178b462)
Location: lib/xarray.c:878
Inline: True
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81ea65bf-ffffffff81ea6624: xas_set_mark.cold (STB_LOCAL)
ffffffff8178b3f0-ffffffff8178b48a: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff82048d32)
Location: lib/xarray.c:878
Inline: True
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff820b7e45-ffffffff820b7eaa: xas_set_mark.cold (STB_LOCAL)
ffffffff82048cc0-ffffffff82048d5a: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff820c75c4)
Location: lib/xarray.c:876
Inline: True
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff821392b1-ffffffff821392fe: xas_set_mark.cold (STB_LOCAL)
ffffffff820c7550-ffffffff820c7601: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff821a1f44)
Location: lib/xarray.c:876
Inline: True
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff8221b056-ffffffff8221b0a3: xas_set_mark.cold (STB_LOCAL)
ffffffff821a1ed0-ffffffff821a1f81: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d991b0)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffff800010d991b0-ffff800010d99234: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e95bf8)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
c0e95bf8-c0e95c9c: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edee70)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
c000000000edee70-c000000000edef1c: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2214)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffffffe0008c2214-ffffffe0008c229a: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5cde0)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffffffff81a5cde0-ffffffff81a5ce2e: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19eb0)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffffffff81a19eb0-ffffffff81a19efe: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac91d0)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffffffff81ac91d0-ffffffff81ac921e: xas_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xas_set_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad56a0)
Location: lib/xarray.c:870
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_entry
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xas_init_marks
```
**Symbols:**

```
ffffffff81ad56a0-ffffffff81ad56ee: xas_set_mark (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
