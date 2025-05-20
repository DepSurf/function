# Function: <code>memcpy_flushcache</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff818fd5c0)
Location: arch/x86/lib/usercopy_64.c:136
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff818fd5c0-ffffffff818fd747: memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819850b0)
Location: arch/x86/lib/usercopy_64.c:136
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
**Symbols:**

```
ffffffff819850b0-ffffffff81985237: memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memcpy_flushcache(void *_dst, const void *_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819e15a0)
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
ffffffff819e15a0-ffffffff819e1722: memcpy_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814ddecd)
Location: arch/x86/include/asm/string_64.h:135
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff81700fed)
Location: arch/x86/include/asm/string_64.h:135
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c8aa)
Location: arch/x86/include/asm/string_64.h:135
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150922a)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff8173ae84)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c4e0)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81527b8a)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff8175eb54)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ac37a0)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158a74c)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In arch/x86/lib/usercopy_64.c (ffffffff815ffca0)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff8181e532)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a7400)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81624b90)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff8182d483)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ae98c)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81608540)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff81810757)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81617363)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81677180)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff8189ad87)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e3e24)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In arch/x86/lib/usercopy_64.c (ffffffff817921b7)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff819e4477)
Location: arch/x86/include/asm/string_64.h:88
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d4d65)
Location: arch/x86/include/asm/string_64.h:110
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff81b601b7)
Location: arch/x86/include/asm/string_64.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8204ff87)
Location: arch/x86/include/asm/string_64.h:110
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81813279)
Location: arch/x86/include/asm/string_64.h:80
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff81bb3750)
Location: arch/x86/include/asm/string_64.h:80
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b81f1)
Location: arch/x86/include/asm/string_64.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:arch_crash_handle_hotplug_event
```
```
In lib/iov_iter.c (ffffffff8185660b)
Location: arch/x86/include/asm/string_64.h:80
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff81c07ca0)
Location: arch/x86/include/asm/string_64.h:80
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
void memcpy_flushcache(void *dst, const void *src, size_t cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/lib/uaccess_flushcache.c (ffff800010d83538)
Location: arch/arm64/lib/uaccess_flushcache.c:10
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - arch/arm64/lib/uaccess_flushcache.c:memcpy_page_flushcache
```
**Symbols:**

```
ffff800010d83538-ffff800010d83588: memcpy_flushcache (STB_GLOBAL)
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
void *memcpy_flushcache(void *dest, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/lib/pmem.c (c0000000000a7e60)
Location: arch/powerpc/lib/pmem.c:43
Inline: False
Direct callers:
  - arch/powerpc/lib/pmem.c:memcpy_page_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
c0000000000a7e60-c0000000000a7f00: memcpy_flushcache (STB_GLOBAL)
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
In drivers/nvdimm/claim.c (ffffffe0005cde60)
Location: include/linux/string.h:172
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8152016a)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff81713244)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a625f0)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151045a)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/acpi/nfit/core.c (ffffffff815f4aca)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io
```
```
In drivers/nvdimm/claim.c (ffffffff816e6cc4)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pmem.c (ffffffff816eadcb)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:write_pmem
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f660)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c1fa)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff81752014)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ace9e0)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81535a4a)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
```
In drivers/nvdimm/claim.c (ffffffff8176d494)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adaef7)
Location: arch/x86/include/asm/string_64.h:120
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
