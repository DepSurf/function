# Function: <code>page_is_ram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086fd0)
Location: kernel/resource.c:489
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff81086fd0-ffffffff81086ff7: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089fe0)
Location: kernel/resource.c:515
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff81089fe0-ffffffff8108a007: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ef30)
Location: kernel/resource.c:515
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff8108ef30-ffffffff8108ef57: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108bef0)
Location: kernel/resource.c:515
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff8108bef0-ffffffff8108bf17: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092c30)
Location: kernel/resource.c:533
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff81092c30-ffffffff81092c57: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096650)
Location: kernel/resource.c:501
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff81096650-ffffffff81096677: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e960)
Location: kernel/resource.c:495
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff8109e960-ffffffff8109e987: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2fa0)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff810a2fa0-ffffffff810a2fc7: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a95e0)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810a95e0-ffffffff810a9607: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0c10)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810b0c10-ffffffff810b0c97: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac370)
Location: kernel/resource.c:517
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810ac370-ffffffff810ac3f7: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad1e0)
Location: kernel/resource.c:499
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810ad1e0-ffffffff810ad264: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bed50)
Location: kernel/resource.c:499
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810bed50-ffffffff810bedd4: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6410)
Location: kernel/resource.c:486
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810d6410-ffffffff810d64b1: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f5480)
Location: kernel/resource.c:486
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810f5480-ffffffff810f5521: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811018c0)
Location: kernel/resource.c:486
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel/pmc/core.c:get_primary_reg_base
```
**Symbols:**

```
ffffffff811018c0-ffffffff81101961: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110b010)
Location: kernel/resource.c:541
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff8110b010-ffffffff8110b0b1: page_is_ram (STB_WEAK)
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
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000101013e0)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - arch/arm64/mm/mmap.c:devmem_is_allowed
```
**Symbols:**

```
ffff8000101013e0-ffff800010101424: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035da20)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - arch/arm/mm/mmap.c:devmem_is_allowed
```
**Symbols:**

```
c035da20-c035da58: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000148b40)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pci_phys_mem_access_prot
  - arch/powerpc/mm/mem.c:devmem_is_allowed
  - arch/powerpc/mm/mem.c:phys_mem_access_prot
  - arch/powerpc/perf/callchain.c:read_user_stack_slow
```
**Symbols:**

```
c000000000148b40-c000000000148b8c: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8722)
Location: kernel/resource.c:510
Inline: False
```
**Symbols:**

```
ffffffe0000c8722-ffffffe0000c875e: page_is_ram (STB_WEAK)
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
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2f00)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810a2f00-ffffffff810a2f27: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810918e0)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810918e0-ffffffff81091907: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2eb0)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810a2eb0-ffffffff810a2ed7: page_is_ram (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int page_is_ram(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aaf50)
Location: kernel/resource.c:510
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810aaf50-ffffffff810aaf77: page_is_ram (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
