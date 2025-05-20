# Function: <code>__memcpy_flushcache</code>

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
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c550)
Location: arch/x86/lib/usercopy_64.c:156
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff81a1c550-ffffffff81a1c6d2: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c200)
Location: arch/x86/lib/usercopy_64.c:137
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff81a8c200-ffffffff81a8c380: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ac34c0)
Location: arch/x86/lib/usercopy_64.c:137
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff81ac34c0-ffffffff81ac3640: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff815ffa40)
Location: arch/x86/lib/usercopy_64.c:138
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff815ffa40-ffffffff815ffb90: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81624980)
Location: arch/x86/lib/usercopy_64.c:117
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81624980-ffffffff81624ad0: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81608330)
Location: arch/x86/lib/usercopy_64.c:117
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81608330-ffffffff8160847f: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81676f70)
Location: arch/x86/lib/usercopy_64.c:117
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81676f70-ffffffff816770bf: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81791f60)
Location: arch/x86/lib/usercopy_64.c:115
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81791f60-ffffffff817920c7: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8204fd10)
Location: arch/x86/lib/usercopy_64.c:75
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff8204fd10-ffffffff8204fe77: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff820ce260)
Location: arch/x86/lib/usercopy_64.c:80
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff820ce260-ffffffff820ce3c7: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff821a8a70)
Location: arch/x86/lib/usercopy_64.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:arch_crash_handle_hotplug_event
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff821a8a70-ffffffff821a8bd7: __memcpy_flushcache (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a62310)
Location: arch/x86/lib/usercopy_64.c:137
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff81a62310-ffffffff81a62490: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f380)
Location: arch/x86/lib/usercopy_64.c:137
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pmem.c:write_pmem
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff81a1f380-ffffffff81a1f500: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ace700)
Location: arch/x86/lib/usercopy_64.c:137
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff81ace700-ffffffff81ace880: __memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81adac10)
Location: arch/x86/lib/usercopy_64.c:137
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff81adac10-ffffffff81adad90: __memcpy_flushcache (STB_GLOBAL)
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
