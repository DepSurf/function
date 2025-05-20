# Function: <code>walk_iomem_res_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089da0)
Location: kernel/resource.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff81089da0-ffffffff81089e4c: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ecf0)
Location: kernel/resource.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff8108ecf0-ffffffff8108ed9c: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108bcb0)
Location: kernel/resource.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff8108bcb0-ffffffff8108bd5c: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092a30)
Location: kernel/resource.c:440
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81092a30-ffffffff81092a86: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095da0)
Location: kernel/resource.c:407
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff81095da0-ffffffff81095df6: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e0d0)
Location: kernel/resource.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff8109e0d0-ffffffff8109e0fa: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2630)
Location: kernel/resource.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff810a2630-ffffffff810a265a: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8c00)
Location: kernel/resource.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff810a8c00-ffffffff810a8c2a: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0b60)
Location: kernel/resource.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff810b0b60-ffffffff810b0c08: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac2c0)
Location: kernel/resource.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
  - drivers/nvdimm/e820.c:e820_pmem_probe
  - drivers/dax/hmem/device.c:hmem_init
```
**Symbols:**

```
ffffffff810ac2c0-ffffffff810ac368: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad130)
Location: kernel/resource.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
  - drivers/nvdimm/e820.c:e820_pmem_probe
  - drivers/dax/hmem/device.c:hmem_init
```
**Symbols:**

```
ffffffff810ad130-ffffffff810ad1d5: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810beca0)
Location: kernel/resource.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
  - drivers/nvdimm/e820.c:e820_pmem_probe
  - drivers/dax/hmem/device.c:hmem_init
```
**Symbols:**

```
ffffffff810beca0-ffffffff810bed45: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6340)
Location: kernel/resource.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - kernel/kexec_file.c:kexec_locate_mem_hole
  - drivers/nvdimm/e820.c:e820_pmem_probe
  - drivers/dax/hmem/device.c:hmem_init
```
**Symbols:**

```
ffffffff810d6340-ffffffff810d640a: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f4ea0)
Location: kernel/resource.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - kernel/kexec_file.c:kexec_locate_mem_hole
  - drivers/nvdimm/e820.c:e820_pmem_probe
  - drivers/dax/hmem/device.c:hmem_init
```
**Symbols:**

```
ffffffff810f4ea0-ffffffff810f4f6a: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811012d0)
Location: kernel/resource.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - kernel/kexec_file.c:kexec_locate_mem_hole
  - drivers/nvdimm/e820.c:e820_pmem_probe
  - drivers/dax/hmem/device.c:hmem_init
```
**Symbols:**

```
ffffffff811012d0-ffffffff8110139a: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110aa00)
Location: kernel/resource.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - kernel/kexec_file.c:kexec_locate_mem_hole
  - drivers/nvdimm/e820.c:e820_pmem_probe
  - drivers/dax/hmem/device.c:hmem_init
```
**Symbols:**

```
ffffffff8110aa00-ffffffff8110aaca: walk_iomem_res_desc (STB_GLOBAL)
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100940)
Location: kernel/resource.c:431
Inline: False
```
**Symbols:**

```
ffff800010100940-ffff8000101009a8: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d6d8)
Location: kernel/resource.c:431
Inline: False
```
**Symbols:**

```
c035d6d8-c035d724: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147a90)
Location: kernel/resource.c:431
Inline: False
```
**Symbols:**

```
c000000000147a90-c000000000147acc: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c7d30)
Location: kernel/resource.c:431
Inline: False
```
**Symbols:**

```
ffffffe0000c7d30-ffffffe0000c7d84: walk_iomem_res_desc (STB_GLOBAL)
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2520)
Location: kernel/resource.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff810a2520-ffffffff810a254a: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81090f00)
Location: kernel/resource.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff81090f00-ffffffff81090f2a: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a24d0)
Location: kernel/resource.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff810a24d0-ffffffff810a24fa: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa540)
Location: kernel/resource.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
**Symbols:**

```
ffffffff810aa540-ffffffff810aa56a: walk_iomem_res_desc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*func)(u64, u64, void *)</code> ➡️ <code>int (*func)(struct resource *, void *)</code>
</li>
</ul>
</details>
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
