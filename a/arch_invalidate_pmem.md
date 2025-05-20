# Function: <code>arch_invalidate_pmem</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81625009)
Location: arch/x86/include/asm/pmem.h:116
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f3a0)
Location: arch/x86/mm/pageattr.c:153
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8106f3a0-ffffffff8106f3b0: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81074740)
Location: arch/x86/mm/pageattr.c:153
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81074740-ffffffff81074750: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810771b0)
Location: arch/x86/mm/pageattr.c:171
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff810771b0-ffffffff810771c0: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107d8d0)
Location: arch/x86/mm/pageattr.c:306
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8107d8d0-ffffffff8107d8e6: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810811d0)
Location: arch/x86/mm/pageattr.c:307
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff810811d0-ffffffff810811e6: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082270)
Location: arch/x86/mm/pageattr.c:307
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81082270-ffffffff810822a7: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bd30)
Location: arch/x86/mm/pat/set_memory.c:315
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8108bd30-ffffffff8108bd67: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bd50)
Location: arch/x86/mm/pat/set_memory.c:315
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8108bd50-ffffffff8108bd87: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c920)
Location: arch/x86/mm/pat/set_memory.c:323
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8108c920-ffffffff8108c957: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c180)
Location: arch/x86/mm/pat/set_memory.c:323
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8109c180-ffffffff8109c1b7: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810af910)
Location: arch/x86/mm/pat/set_memory.c:326
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff810af910-ffffffff810af953: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810c9f10)
Location: arch/x86/mm/pat/set_memory.c:344
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff810c9f10-ffffffff810c9f53: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd560)
Location: arch/x86/mm/pat/set_memory.c:345
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff810cd560-ffffffff810cd5a3: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5c40)
Location: arch/x86/mm/pat/set_memory.c:345
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff810d5c40-ffffffff810d5c83: arch_invalidate_pmem (STB_GLOBAL)
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
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/flush.c (ffff8000100adb70)
Location: arch/arm64/mm/flush.c:89
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffff8000100adb70-ffff8000100adba4: arch_invalidate_pmem (STB_GLOBAL)
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
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/lib/pmem.c (c0000000000a7df0)
Location: arch/powerpc/lib/pmem.c:22
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
c0000000000a7df0-c0000000000a7e58: arch_invalidate_pmem (STB_GLOBAL)
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
In drivers/nvdimm/claim.c (0)
Location: include/linux/libnvdimm.h:289
Inline: True
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
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081270)
Location: arch/x86/mm/pageattr.c:307
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81081270-ffffffff810812a7: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810701c0)
Location: arch/x86/mm/pageattr.c:307
Inline: False
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pmem.c:pmem_do_bvec
```
**Symbols:**

```
ffffffff810701c0-ffffffff810701f7: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081220)
Location: arch/x86/mm/pageattr.c:307
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81081220-ffffffff81081257: arch_invalidate_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_invalidate_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083340)
Location: arch/x86/mm/pageattr.c:307
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81083340-ffffffff81083377: arch_invalidate_pmem (STB_GLOBAL)
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
