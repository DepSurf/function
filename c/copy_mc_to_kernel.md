# Function: <code>copy_mc_to_kernel</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int copy_mc_to_kernel(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff816216d0)
Location: arch/x86/lib/copy_mc.c:62
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff816216d0-ffffffff816216fc: copy_mc_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int copy_mc_to_kernel(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff81604fd0)
Location: arch/x86/lib/copy_mc.c:62
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81604fd0-ffffffff81604ffc: copy_mc_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int copy_mc_to_kernel(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff816738c0)
Location: arch/x86/lib/copy_mc.c:62
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff816738c0-ffffffff816738e9: copy_mc_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int copy_mc_to_kernel(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff8178de60)
Location: arch/x86/lib/copy_mc.c:62
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8178de60-ffffffff8178dea7: copy_mc_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int copy_mc_to_kernel(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff8204b660)
Location: arch/x86/lib/copy_mc.c:62
Inline: False
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - fs/dax.c:dax_file_unshare
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8204b660-ffffffff8204b6a7: copy_mc_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int copy_mc_to_kernel(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff820c9f40)
Location: arch/x86/lib/copy_mc.c:62
Inline: False
Direct callers:
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_subpage
  - mm/memory.c:__wp_page_copy_user
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff820c9f40-ffffffff820c9f87: copy_mc_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int copy_mc_to_kernel(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff821a48c0)
Location: arch/x86/lib/copy_mc.c:62
Inline: False
Direct callers:
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_subpage
  - mm/memory.c:__wp_page_copy_user
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - fs/coredump.c:dump_user_range
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff821a48c0-ffffffff821a4907: copy_mc_to_kernel (STB_GLOBAL)
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
