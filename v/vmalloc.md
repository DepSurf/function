# Function: <code>vmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cf330)
Location: mm/vmalloc.c:1742
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/kexec_file.c:copy_file_from_fd
  - kernel/cgroup.c:pidlist_array_load
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/frame_vector.c:frame_vector_create
  - fs/file.c:alloc_fdmem
  - fs/seq_file.c:seq_buf_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/jbd2/journal.c:jbd2_alloc
  - ipc/util.c:ipc_alloc
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/selinux/selinuxfs.c:sel_write_load
  - security/apparmor/lib.c:__aa_kvmalloc
  - crypto/lzo.c:lzo_init
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/iov_iter.c:get_pages_array
  - lib/rhashtable.c:bucket_table_alloc
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/generic.c:agp_alloc_page_array
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff811cf330-ffffffff811cf386: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec6f0)
Location: mm/vmalloc.c:1763
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/frame_vector.c:frame_vector_create
  - fs/seq_file.c:seq_buf_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - ipc/util.c:ipc_alloc
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/selinux/selinuxfs.c:sel_write_load
  - security/apparmor/lib.c:__aa_kvmalloc
  - crypto/lzo.c:lzo_init
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/iov_iter.c:get_pages_array
  - lib/rhashtable.c:bucket_table_alloc
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/generic.c:agp_alloc_page_array
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff811ec6f0-ffffffff811ec746: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd990)
Location: mm/vmalloc.c:1776
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/verifier.c:bpf_check
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/seq_file.c:seq_buf_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - ipc/util.c:ipc_alloc
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/selinux/selinuxfs.c:sel_write_load
  - security/apparmor/lib.c:__aa_kvmalloc
  - crypto/lzo.c:lzo_alloc_ctx
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/iov_iter.c:get_pages_array
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/generic.c:agp_alloc_page_array
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff811fd990-ffffffff811fd9e6: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81208430)
Location: mm/vmalloc.c:1846
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/verifier.c:bpf_check
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81208430-ffffffff81208470: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812214e0)
Location: mm/vmalloc.c:1838
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff812214e0-ffffffff81221527: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81243590)
Location: mm/vmalloc.c:1825
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81243590-ffffffff812435de: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257a80)
Location: mm/vmalloc.c:1831
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81257a80-ffffffff81257ace: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a840)
Location: mm/vmalloc.c:2582
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff8126a840-ffffffff8126a88e: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81279750)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81279750-ffffffff8127979e: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac6e0)
Location: mm/vmalloc.c:2619
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:start_bunzip
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_core.c:rproc_coredump
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff812ac6e0-ffffffff812ac703: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7c10)
Location: mm/vmalloc.c:2652
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/kernel_read_file.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:start_bunzip
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unzstd.c:decompress_single
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_do_vmap
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff812b7c10-ffffffff812b7c33: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bd170)
Location: mm/vmalloc.c:2999
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/kernel_read_file.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_read_state_kernel
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff812bd170-ffffffff812bd193: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff8e0)
Location: mm/vmalloc.c:3105
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/kernel_read_file.c:kernel_read_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_read_state_kernel
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff812ff8e0-ffffffff812ff903: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81367210)
Location: mm/vmalloc.c:3262
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/kernel_read_file.c:kernel_read_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_read_state_kernel
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff81367210-ffffffff81367242: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e3100)
Location: mm/vmalloc.c:3324
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/kernel_read_file.c:kernel_read_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_read_state_kernel
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff813e3100-ffffffff813e3132: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81417d60)
Location: mm/vmalloc.c:3417
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/module/decompress.c:module_zstd_decompress
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/kernel_read_file.c:kernel_read_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_read_state_kernel
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81417d60-ffffffff81417d92: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814448b0)
Location: mm/vmalloc.c:3417
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/kernel_read_file.c:kernel_read_file
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - fs/pstore/platform.c:pstore_register
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_read_state_kernel
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff814448b0-ffffffff814448e2: vmalloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff8000103109c8)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - arch/arm64/kernel/machine_kexec_file.c:load_other_segments
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffff8000103109c8-ffff800010310ac4: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c9fc)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
  - drivers/mtd/mtdblock.c:mtdblock_writesect
  - drivers/mtd/nand/raw/nand_bbt.c:nand_create_bbt
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
c052c9fc-c052ca70: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e1880)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan_init
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/integrity/ima/ima_kexec.c:ima_dump_measurement_list
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
c0000000003e1880-c0000000003e18e8: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000218690)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffe000218690-ffffffe0002186dc: vmalloc (STB_GLOBAL)
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
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271da0)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81271da0-ffffffff81271dee: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263f40)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/nvdimm/bus.c:__nd_ioctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff81263f40-ffffffff81263f8e: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126fb40)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff8126fb40-ffffffff8126fb8e: vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *vmalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f760)
Location: mm/vmalloc.c:2590
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - fs/exec.c:kernel_read_file
  - fs/configfs/file.c:configfs_write_bin_file
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lz4_wrapper.c:lz4_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/lzo_wrapper.c:lzo_init
  - fs/squashfs/zlib_wrapper.c:zlib_init
  - fs/squashfs/zstd_wrapper.c:zstd_init
  - security/selinux/selinuxfs.c:sel_write_load
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlz4.c:unlz4
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
**Symbols:**

```
ffffffff8127f760-ffffffff8127f7ae: vmalloc (STB_GLOBAL)
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
