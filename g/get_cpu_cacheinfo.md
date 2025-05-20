# Function: <code>get_cpu_cacheinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff8155248b)
Location: drivers/base/cacheinfo.c:37
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:cache_add_dev
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff81552560-ffffffff8155257c: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815a46f5)
Location: drivers/base/cacheinfo.c:37
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level
```
**Symbols:**

```
ffffffff815a4500-ffffffff815a451c: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815d2a2e)
Location: drivers/base/cacheinfo.c:40
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/intel_rdt.c:get_cache_id
```
**Symbols:**

```
ffffffff815d2ce0-ffffffff815d2cfc: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815e7595)
Location: drivers/base/cacheinfo.c:40
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/intel_rdt.c:get_cache_id
```
**Symbols:**

```
ffffffff815e7850-ffffffff815e786c: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff8164e965)
Location: drivers/base/cacheinfo.c:40
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/intel_rdt.c:get_cache_id
```
**Symbols:**

```
ffffffff8164ec00-ffffffff8164ec1c: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff8168a0b5)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/intel_rdt.c:get_cache_id
```
**Symbols:**

```
ffffffff8168a390-ffffffff8168a3ac: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816a95b5)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/resctrl/core.c:get_cache_id
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff816a9890-ffffffff816a98ac: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816e2bb5)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/resctrl/core.c:get_cache_id
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff816e2e90-ffffffff816e2eac: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81706d65)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/resctrl/core.c:get_cache_id
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81707040-ffffffff8170705c: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817c2025)
Location: drivers/base/cacheinfo.c:29
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
```
**Symbols:**

```
ffffffff817c1db0-ffffffff817c1dcc: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817d7245)
Location: drivers/base/cacheinfo.c:29
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
```
**Symbols:**

```
ffffffff817d6fd0-ffffffff817d6fec: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817babe5)
Location: drivers/base/cacheinfo.c:29
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff817baa20-ffffffff817baa3c: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81844b65)
Location: drivers/base/cacheinfo.c:29
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff818448d0-ffffffff81844916: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81988d85)
Location: drivers/base/cacheinfo.c:29
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81988aa0-ffffffff81988aee: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81af71b1)
Location: drivers/base/cacheinfo.c:31
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81af7720-ffffffff81af776e: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b462a2)
Location: drivers/base/cacheinfo.c:34
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:fetch_cache_info
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81b45a70-ffffffff81b45abe: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b9e4b5)
Location: drivers/base/cacheinfo.c:34
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:fetch_cache_info
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_hygon_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - mm/page_alloc.c:setup_pcp_cacheinfo
```
**Symbols:**

```
ffffffff81b9da60-ffffffff81b9daae: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffff8000108f4250)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/arm64/kernel/cacheinfo.c:_populate_cache_leaves
  - arch/arm64/kernel/cacheinfo.c:_init_cache_level
  - drivers/acpi/pptt.c:cache_setup_acpi
  - drivers/acpi/pptt.c:cache_setup_acpi
  - drivers/acpi/pptt.c:cache_setup_acpi
```
**Symbols:**

```
ffff8000108f4488-ffff8000108f44c8: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (c09e0850)
Location: drivers/base/cacheinfo.c:29
Inline: True
```
**Symbols:**

```
c09e09d4-c09e0a04: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (c00000000098e180)
Location: drivers/base/cacheinfo.c:29
Inline: True
```
**Symbols:**

```
c00000000098e4a0-c00000000098e4d0: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffe00058583e)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves
  - arch/riscv/kernel/cacheinfo.c:_init_cache_level
```
**Symbols:**

```
ffffffe000585a46-ffffffe000585a80: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816cc4b5)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/resctrl/core.c:get_cache_id
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff816cc790-ffffffff816cc7ac: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816a77e5)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/resctrl/core.c:get_cache_id
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff816a7ac0-ffffffff816a7adc: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816faa25)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/resctrl/core.c:get_cache_id
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff816fad00-ffffffff816fad1c: get_cpu_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cpu_cacheinfo *get_cpu_cacheinfo(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817152c5)
Location: drivers/base/cacheinfo.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/resctrl/core.c:get_cache_id
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff817155a0-ffffffff817155bc: get_cpu_cacheinfo (STB_GLOBAL)
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
