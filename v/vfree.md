# Function: <code>vfree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cee10)
Location: mm/vmalloc.c:1507
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_fini_cpu
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:module_memfree
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:SYSC_init_module
  - kernel/kexec_file.c:copy_file_from_fd
  - kernel/kexec_file.c:copy_file_from_fd
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:bpf_check
  - mm/util.c:kvfree
  - mm/percpu.c:pcpu_free_chunk
  - mm/percpu.c:pcpu_free_chunk
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:pcpu_create_chunk
  - mm/vmalloc.c:__vunmap
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/memory_hotplug.c:try_offline_node
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - ipc/util.c:ipc_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/firmware_class.c:release_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-ioctl.c:free_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:free_pg_vec
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff811cee10-ffffffff811cee7b: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ebfa0)
Location: mm/vmalloc.c:1528
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_fini_cpu
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - mm/util.c:kvfree
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/memory_hotplug.c:try_offline_node
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_class.c:release_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff811ebfa0-ffffffff811ec00b: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd1e0)
Location: mm/vmalloc.c:1545
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - mm/util.c:kvfree
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_class.c:release_firmware
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff811fd1e0-ffffffff811fd24b: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207ec0)
Location: mm/vmalloc.c:1597
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:fw_free_buf
  - drivers/base/firmware_class.c:fw_free_buf
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81207ec0-ffffffff81207f2a: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81220fa0)
Location: mm/vmalloc.c:1595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81220fa0-ffffffff81221008: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242e50)
Location: mm/vmalloc.c:1582
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81242e50-ffffffff81242eb8: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257530)
Location: mm/vmalloc.c:1586
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:free_equiv_cpu_table
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81257530-ffffffff812575c7: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812697d0)
Location: mm/vmalloc.c:2320
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:free_equiv_cpu_table
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff812697d0-ffffffff8126980f: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81278710)
Location: mm/vmalloc.c:2326
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:free_equiv_cpu_table
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81278710-ffffffff8127874f: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac0d0)
Location: mm/vmalloc.c:2373
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_purgatory_setup_kbuf
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812ac0d0-ffffffff812ac15c: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7580)
Location: mm/vmalloc.c:2355
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_purgatory_setup_kbuf
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/kernel_read_file.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unzstd.c:decompress_single
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_do_vmap
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812b7580-ffffffff812b75bf: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bce50)
Location: mm/vmalloc.c:2637
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/kernel_read_file.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/char/agp/backend.c:agp_remove_bridge
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812bce50-ffffffff812bce8f: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff5c0)
Location: mm/vmalloc.c:2690
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/kernel_read_file.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_release_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/char/agp/backend.c:agp_remove_bridge
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/nexthop.c:nh_notifier_info_fini
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812ff5c0-ffffffff812ff5ff: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81366700)
Location: mm/vmalloc.c:2734
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_free_guest_fpstate
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:fpstate_free
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:thread_stack_free_rcu
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/module/main.c:__do_sys_finit_module
  - kernel/module/main.c:__do_sys_init_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/kernel_read_file.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_release_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/char/agp/backend.c:agp_remove_bridge
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff81366700-ffffffff81366747: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e2340)
Location: mm/vmalloc.c:2796
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_free_guest_fpstate
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:fpstate_free
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:thread_stack_free_rcu
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/module/main.c:__do_sys_finit_module
  - kernel/module/main.c:__do_sys_init_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/kernel_read_file.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_release_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/char/agp/backend.c:agp_remove_bridge
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff813e2340-ffffffff813e2387: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2808
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_free_guest_fpstate
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/xstate.c:fpstate_free
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:thread_stack_free_rcu
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/module/main.c:init_module_from_file
  - kernel/module/main.c:__do_sys_init_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
  - kernel/module/decompress.c:module_zstd_decompress
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:delayed_vfree_work
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/kernel_read_file.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_release_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/char/agp/backend.c:agp_remove_bridge
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - net/xdp/xsk_queue.c:xskq_destroy
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff820e4408-ffffffff820e446c: vfree.cold (STB_LOCAL)
ffffffff81416f40-ffffffff81417204: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff8144430c)
Location: mm/vmalloc.c:2808
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:delayed_vfree_work
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_free_guest_fpstate
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/xstate.c:fpstate_free
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup
  - arch/x86/kernel/crash.c:arch_crash_handle_hotplug_event
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:prepare_elf_headers
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:thread_stack_free_rcu
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/module/main.c:init_module_from_file
  - kernel/module/main.c:__do_sys_init_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:module_memfree
  - kernel/module/main.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:delayed_vfree_work
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/kernel_read_file.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - fs/pstore/platform.c:pstore_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_release_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/ss/services.c:security_read_state_kernel
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_free_ctx
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/char/agp/backend.c:agp_remove_bridge
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_helper_fb_probe
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_fb_destroy
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - net/xdp/xsk_queue.c:xskq_destroy
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff814438a0-ffffffff81443b14: vfree.part.0 (STB_LOCAL)
ffffffff821c103c-ffffffff821c10a0: vfree.part.0.cold (STB_LOCAL)
ffffffff81443ca0-ffffffff81443cf7: vfree (STB_GLOBAL)
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
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030f070)
Location: mm/vmalloc.c:2326
Inline: True
Direct callers:
  - arch/arm64/kernel/machine_kexec_file.c:load_other_segments
  - arch/arm64/kernel/machine_kexec_file.c:load_other_segments
  - arch/arm64/kernel/machine_kexec_file.c:arch_kimage_file_post_load_cleanup
  - arch/arm64/kernel/sdei.c:_free_sdei_stack
  - arch/arm64/net/bpf_jit_comp.c:bpf_jit_free_exec
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/arm/arm.c:kvm_arch_free_vm
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffff80001030f070-ffff80001030f0c4: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a8bc)
Location: mm/vmalloc.c:2326
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__se_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/events/ring_buffer.c:rb_free_work
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/mtd/mtdblock.c:mtdblock_release
  - drivers/mtd/nand/raw/nand_bbt.c:nand_create_bbt
  - drivers/mtd/nand/raw/nand_bbt.c:nand_create_bbt
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - sound/core/pcm_memory.c:snd_pcm_lib_free_vmalloc_buffer
  - sound/core/pcm_memory.c:_snd_pcm_lib_alloc_vmalloc_buffer
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
c052a8bc-c052a92c: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e0090)
Location: mm/vmalloc.c:2326
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
  - arch/powerpc/platforms/powernv/opal-flash.c:image_data_write
  - arch/powerpc/platforms/powernv/opal-dump.c:dump_attr_read
  - arch/powerpc/platforms/powernv/opal-dump.c:dump_release
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_release_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_kexec.c:ima_dump_measurement_list
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/genalloc.c:gen_pool_destroy
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
c0000000003e0090-c0000000003e011c: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe00021783a)
Location: mm/vmalloc.c:2326
Inline: True
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffe00021783a-ffffffe000217890: vfree (STB_GLOBAL)
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
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270d60)
Location: mm/vmalloc.c:2326
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:free_equiv_cpu_table
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81270d60-ffffffff81270d9f: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81262cd0)
Location: mm/vmalloc.c:2326
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:free_equiv_cpu_table
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81262cd0-ffffffff81262d0f: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126eb00)
Location: mm/vmalloc.c:2326
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:free_equiv_cpu_table
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff8126eb00-ffffffff8126eb3f: vfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127e500)
Location: mm/vmalloc.c:2326
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:free_equiv_cpu_table
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_kernel_image_load
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/fork.c:free_vm_stack_cache
  - kernel/fork.c:free_vm_stack_cache
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_memfree
  - kernel/module.c:module_memfree
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/kexec_file.c:kimage_file_post_load_cleanup
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/util.c:kvfree
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/exec.c:kernel_read_file
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_free
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_free
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_free
  - fs/squashfs/zstd_wrapper.c:zstd_free
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/scompress.c:crypto_scomp_free_scratches
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:__deflate_exit
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_end
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/n_tty.c:n_tty_close
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/agp/backend.c:agp_backend_cleanup
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/devcoredump.c:devcd_freev
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_close
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/net-sysfs.c:rps_dev_flow_table_release
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff8127e500-ffffffff8127e526: vfree (STB_GLOBAL)
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
