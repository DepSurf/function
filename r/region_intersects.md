# Function: <code>region_intersects</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81087000)
Location: kernel/resource.c:513
Inline: False
Direct callers:
  - kernel/memremap.c:memremap
```
**Symbols:**

```
ffffffff81087000-ffffffff81087127: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81088f00)
Location: kernel/resource.c:541
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:memremap
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81088f00-ffffffff81089015: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108de50)
Location: kernel/resource.c:541
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:memremap
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff8108de50-ffffffff8108df65: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ae80)
Location: kernel/resource.c:541
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:memremap
```
**Symbols:**

```
ffffffff8108ae80-ffffffff8108afc4: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091b60)
Location: kernel/resource.c:559
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:memremap
  - mm/hmm.c:hmm_devmem_add
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff81091b60-ffffffff81091ca4: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095610)
Location: kernel/resource.c:527
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - kernel/memremap.c:devm_memremap_pages
  - mm/hmm.c:hmm_devmem_add
  - mm/hmm.c:hmm_devmem_pages_create
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81095610-ffffffff81095759: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109d990)
Location: kernel/resource.c:521
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - kernel/memremap.c:devm_memremap_pages
  - mm/hmm.c:hmm_devmem_add
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff8109d990-ffffffff8109dad9: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1f50)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/resource.c:devm_request_free_mem_region
  - kernel/iomem.c:memremap
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff810a1f50-ffffffff810a2016: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8510)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff810a8510-ffffffff810a85d6: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0810)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/resource.c:__request_free_mem_region
  - kernel/iomem.c:memremap
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff810b0810-ffffffff810b08ce: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810abf30)
Location: kernel/resource.c:543
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/resource.c:__request_free_mem_region
  - kernel/iomem.c:memremap
  - mm/memremap.c:pagemap_range
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff810abf30-ffffffff810abfff: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810acf40)
Location: kernel/resource.c:553
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - mm/memremap.c:pagemap_range
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff810acf40-ffffffff810acf91: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810beab0)
Location: kernel/resource.c:553
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - mm/memremap.c:pagemap_range
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff810beab0-ffffffff810beb01: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5350)
Location: kernel/resource.c:540
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - kernel/iomem.c:memremap
  - mm/memremap.c:pagemap_range
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff810d5350-ffffffff810d53ae: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f4ba0)
Location: kernel/resource.c:541
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - kernel/iomem.c:memremap
  - mm/memremap.c:pagemap_range
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff810f4ba0-ffffffff810f4c08: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81100fd0)
Location: kernel/resource.c:541
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - kernel/iomem.c:memremap
  - mm/memremap.c:pagemap_range
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
```
**Symbols:**

```
ffffffff81100fd0-ffffffff81101038: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110a7e0)
Location: kernel/resource.c:596
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - kernel/iomem.c:memremap
  - mm/memremap.c:pagemap_range
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
```
**Symbols:**

```
ffffffff8110a7e0-ffffffff8110a848: region_intersects (STB_GLOBAL)
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000101002f0)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffff8000101002f0-ffff800010100454: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d36c)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
c035d36c-c035d4a8: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000146ea0)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
c000000000146ea0-c00000000014702c: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c7642)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffe0000c7642-ffffffe0000c771a: region_intersects (STB_GLOBAL)
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1e30)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff810a1e30-ffffffff810a1ef6: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81090810)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - mm/memremap.c:memremap_pages
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
```
**Symbols:**

```
ffffffff81090810-ffffffff810908d6: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1de0)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff810a1de0-ffffffff810a1ea6: region_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9e00)
Location: kernel/resource.c:536
Inline: False
Direct callers:
  - arch/x86/mm/init.c:devmem_is_allowed
  - kernel/iomem.c:memremap
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff810a9e00-ffffffff810a9ef4: region_intersects (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int desc</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
</ul>
</details>
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
