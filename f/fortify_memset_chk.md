# Function: <code>fortify_memset_chk</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81067c07)
Location: include/linux/fortify-string.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/swap.c:__lru_add_drain_all
  - mm/percpu.c:pcpu_build_alloc_info
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - net/core/dev.c:flush_all_backlogs
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
In arch/x86/kernel/head64.c (ffffffff81077557)
Location: include/linux/fortify-string.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/swap.c:__lru_add_drain_all
  - mm/percpu.c:pcpu_build_alloc_info
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - net/core/dev.c:flush_all_backlogs
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
In init/initramfs.c (ffffffff83694823)
Location: include/linux/fortify-string.h:475
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
  - arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/kprobes.c:__get_insn_slot
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - mm/swap.c:__lru_add_drain_all
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/ext4/ioctl.c:ext4_ioctl_setlabel
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_kmalloc
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/md/dm-table.c:dm_table_create
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/skbuff.c:slab_build_skb
  - net/core/skbuff.c:slab_build_skb
  - net/core/dev.c:flush_all_backlogs
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/netlink/policy.c:add_policy
  - net/packet/af_packet.c:packet_mc_add
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
In init/initramfs.c (ffffffff838c4713)
Location: include/linux/fortify-string.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/workqueue.c:workqueue_unbound_cpus_setup
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/kprobes.c:__get_insn_slot
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - mm/swap.c:__lru_add_drain_all
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/ext4/ioctl.c:ext4_ioctl_setlabel
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/landlock/syscalls.c:__do_sys_landlock_create_ruleset
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_kmalloc
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_connector_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_private_obj_state
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
  - drivers/gpu/drm/drm_managed.c:drmm_kmalloc
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/md/dm-table.c:dm_table_create
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - net/core/skbuff.c:slab_build_skb
  - net/core/skbuff.c:slab_build_skb
  - net/core/dev.c:flush_all_backlogs
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/netlink/policy.c:add_policy
  - net/ipv4/tcp_sigpool.c:cpool_cleanup_work_cb
  - net/packet/af_packet.c:packet_mc_add
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
