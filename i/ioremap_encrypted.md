# Function: <code>ioremap_encrypted</code>

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
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d0d0)
Location: arch/x86/mm/ioremap.c:366
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8107d0d0-ffffffff8107d0ec: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080820)
Location: arch/x86/mm/ioremap.c:386
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81080820-ffffffff8108083c: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81081a20)
Location: arch/x86/mm/ioremap.c:408
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81081a20-ffffffff81081a3c: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810889d0)
Location: arch/x86/mm/ioremap.c:408
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff810889d0-ffffffff810889ec: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088c10)
Location: arch/x86/mm/ioremap.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:sev_es_setup_ap_jump_table
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff81088c10-ffffffff81088c2c: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810898b0)
Location: arch/x86/mm/ioremap.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff810898b0-ffffffff810898cc: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81098d50)
Location: arch/x86/mm/ioremap.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff81098d50-ffffffff81098d6c: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810abb50)
Location: arch/x86/mm/ioremap.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff810abb50-ffffffff810abb7b: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c5590)
Location: arch/x86/mm/ioremap.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - drivers/iommu/amd/init.c:__copy_device_table
```
**Symbols:**

```
ffffffff810c5590-ffffffff810c55bb: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c8d20)
Location: arch/x86/mm/ioremap.c:427
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - drivers/iommu/amd/init.c:__copy_device_table
```
**Symbols:**

```
ffffffff810c8d20-ffffffff810c8d4b: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d1420)
Location: arch/x86/mm/ioremap.c:427
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - drivers/iommu/amd/init.c:__copy_device_table
```
**Symbols:**

```
ffffffff810d1420-ffffffff810d144b: ioremap_encrypted (STB_GLOBAL)
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
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080a20)
Location: arch/x86/mm/ioremap.c:408
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81080a20-ffffffff81080a3c: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f970)
Location: arch/x86/mm/ioremap.c:408
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8106f970-ffffffff8106f98c: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810809d0)
Location: arch/x86/mm/ioremap.c:408
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff810809d0-ffffffff810809ec: ioremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *ioremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082af0)
Location: arch/x86/mm/ioremap.c:408
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81082af0-ffffffff81082b0c: ioremap_encrypted (STB_GLOBAL)
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
