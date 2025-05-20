# Function: <code>xas_pause</code>

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
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a16bc0)
Location: lib/xarray.c:944
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffff81a16bc0-ffffffff81a16c2b: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a86750)
Location: lib/xarray.c:963
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffff81a86750-ffffffff81a867bb: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abd9d0)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffff81abd9d0-ffffffff81abda44: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815f9a90)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffff815f9a90-ffffffff815f9b07: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161e150)
Location: lib/xarray.c:1114
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
**Symbols:**

```
ffffffff8161e150-ffffffff8161e1c7: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81601aa0)
Location: lib/xarray.c:1115
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:mapping_seek_hole_data
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
**Symbols:**

```
ffffffff81601aa0-ffffffff81601b17: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1115
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:mapping_seek_hole_data
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
**Symbols:**

```
ffffffff81cdfbc5-ffffffff81cdfbe3: xas_pause.cold (STB_LOCAL)
ffffffff8166fa30-ffffffff8166faee: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1122
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:mapping_seek_hole_data
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
**Symbols:**

```
ffffffff81ea6397-ffffffff81ea63b5: xas_pause.cold (STB_LOCAL)
ffffffff81789f20-ffffffff8178a001: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1122
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:mapping_seek_hole_data
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
**Symbols:**

```
ffffffff820b7c1d-ffffffff820b7c3b: xas_pause.cold (STB_LOCAL)
ffffffff82047340-ffffffff82047421: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:mapping_seek_hole_data
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:shmem_swapin_range
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
**Symbols:**

```
ffffffff8213908e-ffffffff821390ac: xas_pause.cold (STB_LOCAL)
ffffffff820c59d0-ffffffff820c5ab1: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:mapping_seek_hole_data
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:shmem_swapin_range
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
**Symbols:**

```
ffffffff8221ae33-ffffffff8221ae51: xas_pause.cold (STB_LOCAL)
ffffffff821a0350-ffffffff821a0431: xas_pause (STB_GLOBAL)
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
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d98cb8)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffff800010d98cb8-ffff800010d98d3c: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e9576c)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
c0e9576c-c0e957d4: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ede4a0)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
c000000000ede4a0-c000000000ede58c: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c19de)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffe0008c19de-ffffffe0008c1a3c: xas_pause (STB_GLOBAL)
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
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5c820)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffff81a5c820-ffffffff81a5c894: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19900)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffff81a19900-ffffffff81a19974: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac8c10)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffff81ac8c10-ffffffff81ac8c84: xas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xas_pause(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad50f0)
Location: lib/xarray.c:964
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
**Symbols:**

```
ffffffff81ad50f0-ffffffff81ad5164: xas_pause (STB_GLOBAL)
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
