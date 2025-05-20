# Function: <code>set_memory_decrypted</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077610)
Location: arch/x86/mm/pageattr.c:1836
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/mm/mem_encrypt.c:swiotlb_set_mem_attributes
  - arch/x86/mm/mem_encrypt.c:sev_alloc
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff81077610-ffffffff81077622: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a080)
Location: arch/x86/mm/pageattr.c:1887
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff8107a080-ffffffff8107a092: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080860)
Location: arch/x86/mm/pageattr.c:2071
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff81080860-ffffffff81080872: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084360)
Location: arch/x86/mm/pageattr.c:2082
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff81084360-ffffffff81084372: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810850a0)
Location: arch/x86/mm/pageattr.c:1988
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff810850a0-ffffffff810850b2: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ece0)
Location: arch/x86/mm/pat/set_memory.c:2024
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff8108ece0-ffffffff8108ecf2: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ead0)
Location: arch/x86/mm/pat/set_memory.c:2024
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff8108ead0-ffffffff8108eae2: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f690)
Location: arch/x86/mm/pat/set_memory.c:2032
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff8108f690-ffffffff8108f6a2: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f150)
Location: arch/x86/mm/pat/set_memory.c:2032
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff8109f150-ffffffff8109f162: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2ce0)
Location: arch/x86/mm/pat/set_memory.c:2089
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff810b2ce0-ffffffff810b2d51: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd6c0)
Location: arch/x86/mm/pat/set_memory.c:2193
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff810cd6c0-ffffffff810cd731: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d0c60)
Location: arch/x86/mm/pat/set_memory.c:2192
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff810d0c60-ffffffff810d0cac: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9340)
Location: arch/x86/mm/pat/set_memory.c:2196
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
**Symbols:**

```
ffffffff810d9340-ffffffff810d938c: set_memory_decrypted (STB_GLOBAL)
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
In kernel/dma/direct.c (0)
Location: include/linux/set_memory.h:48
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/set_memory.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/set_memory.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/svm.c (c0000000001038c0)
Location: arch/powerpc/platforms/pseries/svm.c:47
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
**Symbols:**

```
c0000000001038c0-c000000000103918: set_memory_decrypted (STB_GLOBAL)
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
In kernel/dma/direct.c (0)
Location: include/linux/set_memory.h:48
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/set_memory.h:48
Inline: True
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
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810840a0)
Location: arch/x86/mm/pageattr.c:1988
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff810840a0-ffffffff810840b2: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072cf0)
Location: arch/x86/mm/pageattr.c:1988
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff81072cf0-ffffffff81072d02: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084050)
Location: arch/x86/mm/pageattr.c:1988
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff81084050-ffffffff81084062: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086190)
Location: arch/x86/mm/pageattr.c:1988
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffff81086190-ffffffff810861a2: set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
