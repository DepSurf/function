# Function: <code>sev_active</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c6662)
Location: arch/x86/mm/mem_encrypt.c:410
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvm_memblock_free
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff810802b0-ffffffff810802c9: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826f002b)
Location: arch/x86/mm/mem_encrypt.c:344
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvm_memblock_free
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff81083780-ffffffff81083794: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6ce8)
Location: arch/x86/mm/mem_encrypt.c:344
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff8108a450-ffffffff8108a464: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8108e200)
Location: arch/x86/mm/mem_encrypt.c:349
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - fs/proc/vmcore.c:elfcorehdr_read
```
**Symbols:**

```
ffffffff8108e1e0-ffffffff8108e1f8: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8108ee60)
Location: arch/x86/mm/mem_encrypt.c:348
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff8108ee40-ffffffff8108ee58: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81095210)
Location: arch/x86/mm/mem_encrypt.c:348
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff810951f0-ffffffff81095208: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810944c0)
Location: arch/x86/mm/mem_encrypt.c:381
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sev_setup_arch
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff81094490-ffffffff8109449b: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81094e00)
Location: arch/x86/mm/mem_encrypt.c:375
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:arch_has_restricted_virtio_memory_access
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sev_setup_arch
  - arch/x86/mm/mem_encrypt.c:sme_early_init
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff81094df0-ffffffff81094dfb: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810a4d80)
Location: arch/x86/mm/mem_encrypt.c:376
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:arch_has_restricted_virtio_memory_access
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sev_setup_arch
  - arch/x86/mm/mem_encrypt.c:sme_early_init
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff810a4d70-ffffffff810a4d7b: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8108de20)
Location: arch/x86/mm/mem_encrypt.c:348
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff8108de00-ffffffff8108de18: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8107c930)
Location: arch/x86/mm/mem_encrypt.c:348
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff8107c910-ffffffff8107c928: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8108ddd0)
Location: arch/x86/mm/mem_encrypt.c:348
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff8108ddb0-ffffffff8108ddc8: sev_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool sev_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810901b0)
Location: arch/x86/mm/mem_encrypt.c:348
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_early_init
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff81090190-ffffffff810901a8: sev_active (STB_GLOBAL)
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
