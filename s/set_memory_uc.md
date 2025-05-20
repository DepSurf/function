# Function: <code>set_memory_uc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106ef70)
Location: arch/x86/mm/pageattr.c:1507
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff8106ef70-ffffffff8106f031: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106ed10)
Location: arch/x86/mm/pageattr.c:1515
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff8106ed10-ffffffff8106edd0: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072980)
Location: arch/x86/mm/pageattr.c:1515
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff81072980-ffffffff81072a40: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071f30)
Location: arch/x86/mm/pageattr.c:1561
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff81071f30-ffffffff81071ff1: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810777a0)
Location: arch/x86/mm/pageattr.c:1561
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810777a0-ffffffff81077861: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a1d0)
Location: arch/x86/mm/pageattr.c:1591
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff8107a1d0-ffffffff8107a291: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810809b0)
Location: arch/x86/mm/pageattr.c:1786
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810809b0-ffffffff81080a71: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810844b0)
Location: arch/x86/mm/pageattr.c:1797
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810844b0-ffffffff8108456c: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810851f0)
Location: arch/x86/mm/pageattr.c:1797
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810851f0-ffffffff810852ac: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ea70)
Location: arch/x86/mm/pat/set_memory.c:1833
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff8108ea70-ffffffff8108eb78: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e840)
Location: arch/x86/mm/pat/set_memory.c:1833
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff8108e840-ffffffff8108e948: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f400)
Location: arch/x86/mm/pat/set_memory.c:1841
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff8108f400-ffffffff8108f509: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109eeb0)
Location: arch/x86/mm/pat/set_memory.c:1841
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff8109eeb0-ffffffff8109efb9: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2950)
Location: arch/x86/mm/pat/set_memory.c:1833
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810b2950-ffffffff810b2a6e: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd2f0)
Location: arch/x86/mm/pat/set_memory.c:1929
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810cd2f0-ffffffff810cd40e: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d0920)
Location: arch/x86/mm/pat/set_memory.c:1930
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810d0920-ffffffff810d0a3e: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9000)
Location: arch/x86/mm/pat/set_memory.c:1934
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810d9000-ffffffff810d911e: set_memory_uc (STB_GLOBAL)
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
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810841f0)
Location: arch/x86/mm/pageattr.c:1797
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810841f0-ffffffff810842ac: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072e00)
Location: arch/x86/mm/pageattr.c:1797
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff81072e00-ffffffff81072ebc: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810841a0)
Location: arch/x86/mm/pageattr.c:1797
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810841a0-ffffffff8108425c: set_memory_uc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_uc(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810862e0)
Location: arch/x86/mm/pageattr.c:1797
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/platform/efi/efi.c:efi_memory_uc
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
**Symbols:**

```
ffffffff810862e0-ffffffff8108639c: set_memory_uc (STB_GLOBAL)
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
