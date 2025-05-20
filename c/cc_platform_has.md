# Function: <code>cc_platform_has</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cc_platform_has(enum cc_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cc_platform.c (ffffffff810941d0)
Location: arch/x86/kernel/cc_platform.c:62
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
```
**Symbols:**

```
ffffffff810941d0-ffffffff8109421b: cc_platform_has (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cc_platform_has(enum cc_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81002920)
Location: arch/x86/coco/core.c:84
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:snp_init_platform_device
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - arch/x86/lib/iomem.c:memset_io
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/init.c:amd_iommu_detect
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff81002920-ffffffff81002a31: cc_platform_has (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cc_platform_has(enum cc_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81003250)
Location: arch/x86/coco/core.c:84
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:snp_init_platform_device
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - arch/x86/lib/iomem.c:memset_io
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/init.c:amd_iommu_detect
  - drivers/iommu/amd/init.c:__copy_device_table
```
**Symbols:**

```
ffffffff81003250-ffffffff81003361: cc_platform_has (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cc_platform_has(enum cc_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff82139600)
Location: arch/x86/coco/core.c:100
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:snp_init_platform_device
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu
  - arch/x86/kernel/sev.c:snp_accept_memory
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_prepare
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - kernel/cpu.c:cpu_down_maps_locked
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - arch/x86/lib/iomem.c:memset_io
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/init.c:amd_iommu_detect
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
**Symbols:**

```
ffffffff82139600-ffffffff82139638: cc_platform_has (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cc_platform_has(enum cc_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff8221b3a0)
Location: arch/x86/coco/core.c:100
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:snp_init_platform_device
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu
  - arch/x86/kernel/sev.c:snp_accept_memory
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_setup_arch
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_prepare
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/platform/efi/efi_64.c:efi_update_mem_attr
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - kernel/cpu.c:cpu_down_maps_locked
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - arch/x86/lib/iomem.c:memset_io
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/init.c:amd_iommu_detect
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
**Symbols:**

```
ffffffff8221b3a0-ffffffff8221b3d8: cc_platform_has (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
