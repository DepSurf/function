# Function: <code>vzalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cf390)
Location: mm/vmalloc.c:1759
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/bpf/arraymap.c:array_map_alloc
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - security/apparmor/lib.c:__aa_kvmalloc
  - block/partitions/check.c:check_partition
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff811cf390-ffffffff811cf3e6: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec750)
Location: mm/vmalloc.c:1780
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - security/apparmor/lib.c:__aa_kvmalloc
  - block/partitions/check.c:check_partition
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff811ec750-ffffffff811ec7a6: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd9f0)
Location: mm/vmalloc.c:1793
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_check
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - security/apparmor/lib.c:__aa_kvmalloc
  - block/partitions/check.c:check_partition
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff811fd9f0-ffffffff811fda46: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812085f0)
Location: mm/vmalloc.c:1863
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:SyS_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - block/partitions/check.c:check_partition
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff812085f0-ffffffff81208630: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812216d0)
Location: mm/vmalloc.c:1855
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:SYSC_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - block/partitions/check.c:check_partition
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff812216d0-ffffffff81221717: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812435e0)
Location: mm/vmalloc.c:1842
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff812435e0-ffffffff8124362e: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257c90)
Location: mm/vmalloc.c:1848
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81257c90-ffffffff81257cde: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126aa20)
Location: mm/vmalloc.c:2602
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8126aa20-ffffffff8126aa6e: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81279930)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81279930-ffffffff8127997e: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac710)
Location: mm/vmalloc.c:2639
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
  - kernel/kexec_file.c:kexec_purgatory_setup_kbuf
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/md/dm-table.c:setup_indexes
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff812ac710-ffffffff812ac733: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7c40)
Location: mm/vmalloc.c:2672
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
  - kernel/kexec_file.c:kexec_purgatory_setup_kbuf
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/md/dm-table.c:setup_indexes
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff812b7c40-ffffffff812b7c63: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bd1a0)
Location: mm/vmalloc.c:3036
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/relay.c:relay_create_buf
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff812bd1a0-ffffffff812bd1c3: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff910)
Location: mm/vmalloc.c:3142
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/relay.c:relay_create_buf
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff812ff910-ffffffff812ff933: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81367250)
Location: mm/vmalloc.c:3302
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/relay.c:relay_alloc_buf
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff81367250-ffffffff81367282: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e3150)
Location: mm/vmalloc.c:3364
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_vzalloc_stats_array
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff813e3150-ffffffff813e3182: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81417db0)
Location: mm/vmalloc.c:3457
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff81417db0-ffffffff81417de2: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81444900)
Location: mm/vmalloc.c:3457
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:prepare_elf_headers
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/profile.c:profile_init
  - kernel/crash_core.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_alloc_ctx
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/core.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
  - drivers/char/agp/backend.c:agp_backend_initialize
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_helper_fb_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff81444900-ffffffff81444932: vzalloc (STB_GLOBAL)
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
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff8000103103c0)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - virt/kvm/arm/arm.c:kvm_arch_alloc_vm
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/soc/fsl/qbman/qman.c:qman_alloc_fq_table
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffff8000103103c0-ffff8000103104bc: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c6dc)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - kernel/profile.c:profile_init
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c052c6dc-c052c750: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e15e0)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
  - arch/powerpc/platforms/powernv/opal-flash.c:image_data_write
  - arch/powerpc/platforms/powernv/opal-dump.c:dump_attr_read
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c0000000003e15e0-c0000000003e1648: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002186dc)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - kernel/profile.c:profile_init
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffe0002186dc-ffffffe000218728: vzalloc (STB_GLOBAL)
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
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271f80)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81271f80-ffffffff81271fce: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263d10)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81263d10-ffffffff81263d5e: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126fd20)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8126fd20-ffffffff8126fd6e: vzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *vzalloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f530)
Location: mm/vmalloc.c:2610
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - kernel/profile.c:profile_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - crypto/deflate.c:deflate_decomp_init
  - crypto/deflate.c:deflate_comp_init
  - block/partitions/check.c:check_partition
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/ipv4/fib_trie.c:tnode_new
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8127f530-ffffffff8127f57e: vzalloc (STB_GLOBAL)
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
