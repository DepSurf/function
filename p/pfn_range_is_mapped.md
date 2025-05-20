# Function: <code>pfn_range_is_mapped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81068a50)
Location: arch/x86/mm/init.c:380
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff81068a50-ffffffff81068a97: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81068740)
Location: arch/x86/mm/init.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff81068740-ffffffff81068787: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8106c3c0)
Location: arch/x86/mm/init.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff8106c3c0-ffffffff8106c407: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8106b7c0)
Location: arch/x86/mm/init.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff8106b7c0-ffffffff8106b80a: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81070050)
Location: arch/x86/mm/init.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff81070050-ffffffff8107009a: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81072eb0)
Location: arch/x86/mm/init.c:443
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff81072eb0-ffffffff81072efa: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81078f40)
Location: arch/x86/mm/init.c:449
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff81078f40-ffffffff81078f8a: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107cb40)
Location: arch/x86/mm/init.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff8107cb40-ffffffff8107cb87: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107dbf0)
Location: arch/x86/mm/init.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff8107dbf0-ffffffff8107dc37: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810842f0)
Location: arch/x86/mm/init.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_initrd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff810842f0-ffffffff81084337: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81085840)
Location: arch/x86/mm/init.c:486
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_initrd
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
**Symbols:**

```
ffffffff81085840-ffffffff81085887: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81086540)
Location: arch/x86/mm/init.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
**Symbols:**

```
ffffffff81086540-ffffffff81086587: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81095750)
Location: arch/x86/mm/init.c:493
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
**Symbols:**

```
ffffffff81095750-ffffffff810957f8: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810a7920)
Location: arch/x86/mm/init.c:502
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
**Symbols:**

```
ffffffff810a7920-ffffffff810a79d8: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c0d50)
Location: arch/x86/mm/init.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
**Symbols:**

```
ffffffff810c0d50-ffffffff810c0e08: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c4430)
Location: arch/x86/mm/init.c:528
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
**Symbols:**

```
ffffffff810c4430-ffffffff810c44e8: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810cc880)
Location: arch/x86/mm/init.c:518
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
**Symbols:**

```
ffffffff810cc880-ffffffff810cc938: pfn_range_is_mapped (STB_GLOBAL)
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
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107cbf0)
Location: arch/x86/mm/init.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff8107cbf0-ffffffff8107cc37: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8106c360)
Location: arch/x86/mm/init.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff8106c360-ffffffff8106c3a7: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107cba0)
Location: arch/x86/mm/init.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff8107cba0-ffffffff8107cbe7: pfn_range_is_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pfn_range_is_mapped(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107eca0)
Location: arch/x86/mm/init.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/platform/efi/efi.c:old_map_region
```
**Symbols:**

```
ffffffff8107eca0-ffffffff8107ece7: pfn_range_is_mapped (STB_GLOBAL)
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
