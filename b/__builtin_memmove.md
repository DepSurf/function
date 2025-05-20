# Function: <code>__builtin_memmove</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/init.c:init_memory_mapping
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - arch/x86/platform/efi/early_printk.c:early_efi_scroll_up
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/ftrace.c:ftrace_free_init_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/bpf/core.c:bpf_patch_insn_single
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/md/md.c:md_ioctl
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/init.c:init_memory_mapping
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - arch/x86/platform/efi/early_printk.c:early_efi_scroll_up
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/bpf/core.c:bpf_patch_insn_single
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/md/md.c:md_ioctl
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/init.c:init_memory_mapping
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - arch/x86/platform/efi/early_printk.c:early_efi_scroll_up
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_patch_insn_single
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/md/md.c:md_ioctl
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/init.c:init_memory_mapping
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - arch/x86/platform/efi/early_printk.c:early_efi_scroll_up
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_patch_insn_single
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/md/md.c:md_ioctl
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:eval_replace
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:bpf_adj_linfo_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/bitmap.c:bitmap_cut
  - lib/lz4/lz4_compress.c:LZ4_saveDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/decompress_bunzip2.c:get_next_block
  - lib/kobject_uevent.c:zap_modalias_env
  - lib/vsprintf.c:widen_string
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/block/loop.c:loop_attr_backing_file_show
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:get_bitmap_file
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_vlan
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk.c:record_print_text
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:eval_replace
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:bpf_adj_linfo_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/bitmap.c:bitmap_cut
  - lib/lz4/lz4_compress.c:LZ4_saveDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/decompress_bunzip2.c:get_next_block
  - lib/kobject_uevent.c:zap_modalias_env
  - lib/vsprintf.c:widen_string
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/block/loop.c:loop_attr_backing_file_show
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:get_bitmap_file
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_vlan
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk.c:record_print_text
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:update_event_printk
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:bpf_adj_linfo_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - fs/io_uring.c:io_rsrc_file_put
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/bitmap.c:bitmap_cut
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/decompress_bunzip2.c:get_next_block
  - lib/kobject_uevent.c:zap_modalias_env
  - lib/vsprintf.c:widen_string
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_vlan
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk.c:record_print_text
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:update_event_printk
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:bpf_adj_linfo_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - fs/io_uring.c:io_rsrc_file_put
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/bitmap.c:bitmap_cut
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/decompress_bunzip2.c:get_next_block
  - lib/kobject_uevent.c:zap_modalias_env
  - lib/vsprintf.c:widen_string
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_vlan
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk.c:record_print_text
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:eval_replace
  - kernel/trace/trace_events_filter.c:filter_build_regex
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:bpf_adj_linfo_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - io_uring/io_uring.c:io_rsrc_file_put
  - lib/bitmap.c:bitmap_cut
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/zstd/compress/hist.c:HIST_count_parallel_wksp
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/xz/xz_dec_lzma2.c:dict_uncompressed
  - lib/xz/xz_dec_lzma2.c:dict_uncompressed
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/decompress_bunzip2.c:get_next_block
  - lib/kobject_uevent.c:zap_modalias_env
  - lib/vsprintf.c:move_right
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/block/loop.c:loop_attr_backing_file_show
  - drivers/net/slip/slhc.c:slhc_uncompress
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:get_bitmap_file
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/gro.c:gro_pull_from_frag0
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/mctp/device.c:mctp_rtm_deladdr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk.c:record_print_text
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:eval_replace
  - kernel/trace/trace_events_filter.c:filter_build_regex
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:bpf_adj_linfo_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/helpers.c:bpf_dynptr_write
  - kernel/bpf/helpers.c:bpf_dynptr_read
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/xattr.c:ext4_xattr_shift_entries
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - io_uring/rsrc.c:io_rsrc_file_put
  - lib/bitmap.c:bitmap_cut
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/zstd/compress/hist.c:HIST_count_parallel_wksp
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/xz/xz_dec_lzma2.c:dict_uncompressed
  - lib/xz/xz_dec_lzma2.c:dict_uncompressed
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_insert
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/block/loop.c:loop_attr_backing_file_show
  - drivers/net/slip/slhc.c:slhc_uncompress
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:get_bitmap_file
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/gro.c:gro_pull_from_frag0
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/mctp/device.c:mctp_rtm_deladdr
  - lib/decompress_bunzip2.c:get_next_block
  - lib/kobject_uevent.c:zap_modalias_env
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/vsprintf.c:move_right
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/cpu/mtrr/generic.c:add_map_entry_at
  - arch/x86/kernel/cpu/mtrr/generic.c:rm_map_entry_at
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/printk/printk.c:console_prepend_dropped
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk.c:record_print_text
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:eval_replace
  - kernel/trace/trace_events_filter.c:filter_build_regex
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:bpf_adj_linfo_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/helpers.c:bpf_dynptr_write
  - kernel/bpf/helpers.c:bpf_dynptr_read
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/xattr.c:ext4_xattr_shift_entries
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - lib/bitmap.c:bitmap_cut
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/zstd/compress/hist.c:HIST_count_parallel_wksp
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/xz/xz_dec_lzma2.c:dict_uncompressed
  - lib/xz/xz_dec_lzma2.c:dict_uncompressed
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_insert
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/block/loop.c:loop_attr_backing_file_show
  - drivers/net/slip/slhc.c:slhc_uncompress
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:get_bitmap_file
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/gro.c:gro_pull_from_frag0
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/mctp/device.c:mctp_rtm_deladdr
  - lib/decompress_bunzip2.c:get_next_block
  - lib/kobject_uevent.c:zap_modalias_env
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/vsprintf.c:move_right
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/cpu/mtrr/generic.c:add_map_entry_at
  - arch/x86/kernel/cpu/mtrr/generic.c:rm_map_entry_at
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/printk/printk.c:console_prepend_dropped
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk.c:record_print_text
  - kernel/crash_core.c:crash_exclude_mem_range
  - kernel/crash_core.c:crash_exclude_mem_range
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:eval_replace
  - kernel/trace/trace_events_filter.c:filter_build_regex
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:bpf_adj_linfo_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/helpers.c:bpf_dynptr_write
  - kernel/bpf/helpers.c:bpf_dynptr_read
  - kernel/bpf/mprog.c:bpf_mprog_entry_shrink
  - kernel/bpf/mprog.c:bpf_mprog_entry_shrink
  - kernel/bpf/mprog.c:bpf_mprog_entry_shrink
  - kernel/bpf/mprog.c:bpf_mprog_entry_shrink
  - kernel/bpf/mprog.c:bpf_mprog_entry_grow
  - kernel/bpf/mprog.c:bpf_mprog_entry_grow
  - kernel/bpf/mprog.c:bpf_mprog_entry_grow
  - kernel/bpf/mprog.c:bpf_mprog_entry_grow
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/xattr.c:ext4_xattr_shift_entries
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:_badblocks_set
  - block/badblocks.c:front_overwrite
  - block/badblocks.c:front_overwrite
  - block/badblocks.c:front_overwrite
  - block/badblocks.c:front_combine
  - lib/bitmap.c:bitmap_cut
  - lib/crypto/mpi/mpih-div.c:mpihelp_divrem
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withSmallPrefix
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_withPrefix64k
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_partial
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe
  - lib/zstd/compress/hist.c:HIST_count_parallel_wksp
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/xz/xz_dec_lzma2.c:dict_uncompressed
  - lib/xz/xz_dec_lzma2.c:dict_uncompressed
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_insert
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/block/loop.c:loop_attr_backing_file_show
  - drivers/gpu/drm/drm_edid.c:edid_filter_invalid_blocks
  - drivers/net/slip/slhc.c:slhc_uncompress
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:get_bitmap_file
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_push
  - net/core/gro.c:gro_pull_from_frag0
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/mctp/device.c:mctp_rtm_deladdr
  - lib/decompress_bunzip2.c:get_next_block
  - lib/kobject_uevent.c:zap_modalias_env
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/vsprintf.c:move_right
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/fdt.c:fdt_move
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_splice_
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_insert_block
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/reed_solomon/reed_solomon.c:decode_rs16
  - lib/reed_solomon/reed_solomon.c:decode_rs16
  - lib/reed_solomon/reed_solomon.c:decode_rs8
  - lib/reed_solomon/reed_solomon.c:decode_rs8
  - lib/reed_solomon/reed_solomon.c:encode_rs8
  - lib/reed_solomon/reed_solomon.c:encode_rs8
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_execSequenceLast7
  - lib/zstd/decompress.c:ZSTD_execSequenceLast7
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/mtd/parsers/cmdlinepart.c:parse_cmdline_partitions
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/fdt.c:fdt_move
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_splice_
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/powerpc/kernel/module_64.c:module_frob_arch_sections
  - arch/powerpc/xmon/xmon.c:cmds
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_vio.c:hvterm_raw_get_chars
  - drivers/tty/hvc/hvsi_lib.c:hvsilib_get_chars
  - drivers/tty/hvc/hvsi_lib.c:hvsi_get_packet
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/fdt.c:fdt_move
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_splice_
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:repair_env_string
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/pci-iommu_table.c:sort_iommu_table
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - kernel/range.c:add_range_with_merge
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/trace_events.c:trace_event_eval_update
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:verifier_remove_insns
  - mm/memblock.c:memblock_insert_region
  - mm/memblock.c:memblock_remove_region
  - mm/slub.c:process_slab
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/sysfs/file.c:sysfs_kf_read
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/badblocks.c:badblocks_set
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/lz4/lz4_decompress.c:LZ4_decompress_fast_extDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_forceExtDict
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_run
  - lib/xz/xz_dec_bcj.c:bcj_flush
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/hvc/hvc_console.c:hvc_push
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/firmware/efi/earlycon.c:efi_earlycon_scroll_up
  - drivers/ras/cec.c:cec_add_elem
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:validate_xmit_skb
  - net/core/filter.c:bpf_xdp_adjust_head
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_push
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_options.c:ip_options_undo
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/vsprintf.c:widen_string
```
</details>
</li>
</ul>

## Differences
