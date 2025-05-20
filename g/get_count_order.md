# Function: <code>get_count_order</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f32b)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810405f1)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041f3b)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In kernel/trace/ftrace.c (ffffffff8114330b)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In drivers/dma/dmaengine.c (ffffffff814bdb15)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ae500)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_sg_alloc
  - drivers/scsi/scsi_lib.c:scsi_sg_free
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f152)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040440)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041f0f)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In kernel/trace/ftrace.c (ffffffff8114d53f)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff81461ddb)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff8150d7c5)
Location: include/linux/bitops.h:68
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103eb2f)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103fe80)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104195b)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In kernel/trace/ftrace.c (ffffffff8115747f)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff8148091b)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff815398f5)
Location: include/linux/bitops.h:184
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103cb02)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ddf1)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fb7d)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In kernel/trace/ftrace.c (ffffffff820c961d)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_init_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff81489adb)
Location: include/linux/bitops.h:184
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff8154d0b5)
Location: include/linux/bitops.h:184
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f6f3)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040951)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81042f09)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In kernel/trace/ftrace.c (ffffffff81167ad3)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff814c5c2b)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff815b0625)
Location: include/linux/bitops.h:186
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040bdc)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104222d)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81044d70)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81045f23)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In kernel/trace/ftrace.c (ffffffff811767d6)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff814f6b56)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff815e8a85)
Location: include/linux/bitops.h:186
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810421fb)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104384d)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81046780)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047947)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81048515)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In kernel/trace/ftrace.c (ffffffff8118441f)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff8150af96)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff816028d5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044777)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81045dad)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810491b3)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a6b0)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b2b5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104b83e)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In kernel/trace/ftrace.c (ffffffff811911a1)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff815396a6)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff816350f5)
Location: include/linux/bitops.h:167
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044ec7)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104650d)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049a83)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b055)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bcb2)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c1fe)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In kernel/trace/ftrace.c (ffffffff8119d1c1)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff8155a4c6)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff81656e05)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048ed9)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a4cd)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e206)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f486)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810502cb)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81050b1e)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In kernel/trace/ftrace.c (ffffffff811b3136)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:ftrace_allocate_pages
```
```
In lib/sg_pool.c (ffffffff815e3e86)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff81707185)
Location: include/linux/bitops.h:189
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048374)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104996d)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d736)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e763)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f655)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104fc7e)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In kernel/trace/ftrace.c (ffffffff811b0c8d)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:ftrace_allocate_pages
```
```
In lib/sg_pool.c (ffffffff816083b3)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff817245c5)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049b3d)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b0ed)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f1c6)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81050b69)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8105126b)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8105182e)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In lib/sg_pool.c (ffffffff815eb013)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff81705885)
Location: include/linux/bitops.h:192
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81051411)
Location: include/linux/bitops.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810521af)
Location: include/linux/bitops.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810572de)
Location: include/linux/bitops.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058ea0)
Location: include/linux/bitops.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8105973c)
Location: include/linux/bitops.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81059dbe)
Location: include/linux/bitops.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In lib/sg_pool.c (ffffffff816574a3)
Location: include/linux/bitops.h:193
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff81780dd5)
Location: include/linux/bitops.h:193
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105c9df)
Location: include/linux/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105dbff)
Location: include/linux/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063674)
Location: include/linux/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8106482f)
Location: include/linux/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065e03)
Location: include/linux/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81066594)
Location: include/linux/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In lib/sg_pool.c (ffffffff8176edcb)
Location: include/linux/bitops.h:159
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff818b7575)
Location: include/linux/bitops.h:159
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a9ff)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106c12f)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810726b7)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81073a9f)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107513f)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81075864)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In lib/sg_pool.c (ffffffff8189e71b)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff81a044a5)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c36f)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106dacf)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107429c)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107594f)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810772af)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff810779d4)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In lib/sg_pool.c (ffffffff818e0ceb)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d305)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810735bf)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074d3f)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107cd71)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e83a)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In lib/sg_pool.c (ffffffff819277d8)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff81a98fa5)
Location: include/linux/bitops.h:210
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/bitops.h:210
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001021605c)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffff800010667770)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff80001066d534)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (ffff80001066fbb4)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010672f24)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bb064)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010723fd8)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_free
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_alloc
```
```
In drivers/dma/dmaengine.c (ffff8000107fcd18)
Location: include/linux/bitops.h:174
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0454de8)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (c080ff38)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/irqchip/irq-gic-v2m.c (c0816510)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_unalloc_msi
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (c08182c4)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_free_msi
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081ab0c)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085bca4)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
```
In drivers/dma/dmaengine.c (c091e120)
Location: include/linux/bitops.h:174
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/sysdev/msi_bitmap.c (c0000000000b7be8)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_reserve_dt_hwirqs
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc_hwirqs
```
```
In kernel/trace/ftrace.c (c000000000297d38)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (c00000000081ccd4)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (c0000000008c8224)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000175c28)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffe000492da6)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffe000517564)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045047)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104668d)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049bf3)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b1c5)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104be22)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c36e)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In kernel/trace/ftrace.c (ffffffff811957e1)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff81552aa6)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff8161cca5)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034557)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103590d)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81038f34)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a63e)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103b00e)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b7bf)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In kernel/trace/ftrace.c (ffffffff811888f1)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff81542d86)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff81611395)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044e87)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810464cd)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049a33)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b005)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bc62)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c1ae)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In kernel/trace/ftrace.c (ffffffff811935b1)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff8154e7e6)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff8164ac45)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046287)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810478cd)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ae43)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c415)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104d072)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104d5be)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In kernel/trace/ftrace.c (ffffffff811a1181)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In lib/sg_pool.c (ffffffff81568636)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/dma/dmaengine.c (ffffffff816651e5)
Location: include/linux/bitops.h:174
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
</details>
</li>
</ul>

## Differences
