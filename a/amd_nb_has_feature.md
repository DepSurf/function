# Function: <code>amd_nb_has_feature</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f635)
Location: arch/x86/include/asm/amd_nb.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/include/asm/amd_nb.h:74
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/amd_nb.h:74
Inline: True
```
```
In drivers/char/agp/amd64-agp.c (0)
Location: arch/x86/include/asm/amd_nb.h:74
Inline: True
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f435)
Location: arch/x86/include/asm/amd_nb.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: arch/x86/include/asm/amd_nb.h:82
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/amd_nb.h:82
Inline: True
```
```
In drivers/char/agp/amd64-agp.c (0)
Location: arch/x86/include/asm/amd_nb.h:82
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81065e50)
Location: arch/x86/kernel/amd_nb.c:69
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81065e50-ffffffff81065e6d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810651e0)
Location: arch/x86/kernel/amd_nb.c:69
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810651e0-ffffffff810651fd: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81069380)
Location: arch/x86/kernel/amd_nb.c:73
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81069380-ffffffff8106939d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff826e9530)
Location: arch/x86/kernel/amd_nb.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8106bfd0-ffffffff8106bfed: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828a00f6)
Location: arch/x86/kernel/amd_nb.c:99
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81071d60-ffffffff81071d7d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828b82ee)
Location: arch/x86/kernel/amd_nb.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810758a0-ffffffff810758bd: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828be7ec)
Location: arch/x86/kernel/amd_nb.c:106
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81076870-ffffffff8107688d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8107e5ad)
Location: arch/x86/kernel/amd_nb.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_cache_gart
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8107db10-ffffffff8107db2d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81bd7ff6)
Location: arch/x86/kernel/amd_nb.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_cache_gart
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8107d7f0-ffffffff8107d80d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff831daa18)
Location: arch/x86/kernel/amd_nb.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8107e920-ffffffff8107e93d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff832bdc52)
Location: arch/x86/kernel/amd_nb.c:122
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8108d5b0-ffffffff8108d5cd: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8346f65a)
Location: arch/x86/kernel/amd_nb.c:122
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8109e130-ffffffff8109e153: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff83e95ce2)
Location: arch/x86/kernel/amd_nb.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810b53c0-ffffffff810b53e3: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff836b9862)
Location: arch/x86/kernel/amd_nb.c:143
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810b8490-ffffffff810b84b3: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff838ea192)
Location: arch/x86/kernel/amd_nb.c:159
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810bf8d0-ffffffff810bf8f3: amd_nb_has_feature (STB_GLOBAL)
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
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828a97c2)
Location: arch/x86/kernel/amd_nb.c:106
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81075870-ffffffff8107588d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828a186e)
Location: arch/x86/kernel/amd_nb.c:106
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81065860-ffffffff8106587d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828bc6c1)
Location: arch/x86/kernel/amd_nb.c:106
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81075820-ffffffff8107583d: amd_nb_has_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool amd_nb_has_feature(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff828bf819)
Location: arch/x86/kernel/amd_nb.c:106
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81077880-ffffffff8107789d: amd_nb_has_feature (STB_GLOBAL)
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
