# Function: <code>node_to_amd_nb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ee8c)
Location: arch/x86/include/asm/amd_nb.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810486b6)
Location: arch/x86/include/asm/amd_nb.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810630e5)
Location: arch/x86/include/asm/amd_nb.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810668e8)
Location: arch/x86/include/asm/amd_nb.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151f20c)
Location: arch/x86/include/asm/amd_nb.h:79
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ecb7)
Location: arch/x86/include/asm/amd_nb.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81048d12)
Location: arch/x86/include/asm/amd_nb.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81f9cbc0)
Location: arch/x86/include/asm/amd_nb.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81f9da98)
Location: arch/x86/include/asm/amd_nb.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81572da3)
Location: arch/x86/include/asm/amd_nb.h:87
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81fd8112)
Location: arch/x86/kernel/amd_nb.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff81065e70-ffffffff81065e9c: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff820b8f59)
Location: arch/x86/kernel/amd_nb.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff81065200-ffffffff8106522c: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff826bf7b6)
Location: arch/x86/kernel/amd_nb.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff810693a0-ffffffff810693cc: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff826e9586)
Location: arch/x86/kernel/amd_nb.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff8106bff0-ffffffff8106c01a: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828a014c)
Location: arch/x86/kernel/amd_nb.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff81071d80-ffffffff81071daa: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828b833f)
Location: arch/x86/kernel/amd_nb.c:106
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff810758c0-ffffffff810758ea: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828be83d)
Location: arch/x86/kernel/amd_nb.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff81076890-ffffffff810768ba: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff82ce2ba6)
Location: arch/x86/kernel/amd_nb.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_cache_gart
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff8107db30-ffffffff8107db5a: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff82fcfe43)
Location: arch/x86/kernel/amd_nb.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_cache_gart
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff8107d810-ffffffff8107d83a: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff831daa69)
Location: arch/x86/kernel/amd_nb.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff8107e940-ffffffff8107e96a: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff832bdca3)
Location: arch/x86/kernel/amd_nb.c:128
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff8108d5d0-ffffffff8108d5fa: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8346f6b6)
Location: arch/x86/kernel/amd_nb.c:128
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff8109e160-ffffffff8109e192: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff83e95daf)
Location: arch/x86/kernel/amd_nb.c:141
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff810b5400-ffffffff810b5432: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff836b992f)
Location: arch/x86/kernel/amd_nb.c:149
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff810b84d0-ffffffff810b8502: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff838ea25f)
Location: arch/x86/kernel/amd_nb.c:165
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff810bf910-ffffffff810bf942: node_to_amd_nb (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828a9813)
Location: arch/x86/kernel/amd_nb.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff81075890-ffffffff810758ba: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828a18bf)
Location: arch/x86/kernel/amd_nb.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff81065880-ffffffff810658aa: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828bc712)
Location: arch/x86/kernel/amd_nb.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff81075840-ffffffff8107586a: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct amd_northbridge *node_to_amd_nb(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828bf86a)
Location: arch/x86/kernel/amd_nb.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
**Symbols:**

```
ffffffff810778a0-ffffffff810778ca: node_to_amd_nb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
