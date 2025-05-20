# Function: <code>fortify_memcpy_chk</code>

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
In arch/x86/kernel/head64.c (ffffffff81003472)
Location: include/linux/fortify-string.h:322
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/core.c:x86_pmu_add
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:emulate_umip_insn
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/printk/printk.c:record_print_text
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/module/sysfs.c:module_sect_read
  - kernel/profile.c:profile_init
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/user_namespace.c:map_write
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/btf.c:btf_bitfield_show
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/shmem.c:shmem_enabled_store
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/efivarfs/super.c:efivarfs_callback
  - security/keys/encrypted-keys/encrypted.c:__ekey_init
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/vfio/pci/vfio_pci_config.c:vfio_virt_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/message.c:usb_cache_string
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/input/mousedev.c:mousedev_read
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivars_sysfs_callback
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/filter.c:bpf_convert_filter
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/packet/af_packet.c:packet_mc_add
  - net/wireless/wext-core.c:wireless_send_event
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
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
In arch/x86/kernel/head64.c (ffffffff81003c72)
Location: include/linux/fortify-string.h:489
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/core.c:x86_pmu_add
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:emulate_umip_insn
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/printk/printk.c:record_print_text
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/module/sysfs.c:module_sect_read
  - kernel/profile.c:profile_init
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/user_namespace.c:insert_extent
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/btf.c:btf_bitfield_show
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - mm/shmem.c:shmem_enabled_store
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/efivarfs/super.c:efivarfs_callback
  - security/keys/encrypted-keys/encrypted.c:__ekey_init
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/message.c:usb_cache_string
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/input/mousedev.c:mousedev_read
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev_addr_lists.c:__hw_addr_create
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/filter.c:bpf_convert_filter
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/wireless/wext-core.c:wireless_send_event
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In init/main.c (ffffffff8100320b)
Location: include/linux/fortify-string.h:559
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/core.c:x86_pmu_add
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/ksysfs.c:boot_params_data_read
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_copy_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/mpparse.c:check_irq_src
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:emulate_umip_insn
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/energy_model.c:em_create_pd
  - kernel/printk/printk.c:console_prepend_dropped
  - kernel/printk/printk.c:record_print_text
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/module/decompress.c:module_extend_max_pages
  - kernel/module/sysfs.c:module_add_modinfo_attrs
  - kernel/module/sysfs.c:module_sect_read
  - kernel/profile.c:profile_init
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/user_namespace.c:insert_extent
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_bitfield_show
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - certs/blacklist.c:get_raw_hash
  - mm/shmem.c:shmem_enabled_store
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/madvise.c:anon_vma_name_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/aio.c:ioctx_add_table
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:verify_data_block
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/proc/proc_sysctl.c:new_links
  - fs/proc/proc_sysctl.c:new_dir
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_expand_inode_array
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
  - fs/ecryptfs/crypto.c:ecryptfs_copy_filename
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_send_miscdev
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/pstore/platform.c:decompress_record
  - fs/efivarfs/file.c:efivarfs_file_read
  - fs/efivarfs/super.c:efivarfs_callback
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - security/keys/encrypted-keys/encrypted.c:__ekey_init
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/tomoyo/audit.c:tomoyo_print_bprm
  - security/tomoyo/audit.c:tomoyo_print_bprm
  - security/tomoyo/audit.c:tomoyo_print_bprm
  - security/tomoyo/audit.c:tomoyo_print_bprm
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
  - security/integrity/ima/ima_template_lib.c:ima_write_template_field_data
  - crypto/akcipher.c:crypto_akcipher_sync_prep
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/sha3_generic.c:crypto_sha3_update
  - crypto/sha3_generic.c:crypto_sha3_update
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_generate_id
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_generate_id
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - block/blk-map.c:bio_alloc_map_data
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rw.c:io_req_map_rw
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_create
  - lib/crypto/blake2s.c:blake2s_update
  - lib/crypto/blake2s.c:blake2s_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xz/xz_dec_stream.c:fill_temp
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/nlattr.c:nla_strdup
  - lib/mpi/mpicoder.c:mpi_read_buffer
  - drivers/pci/pci.c:pci_store_saved_state
  - drivers/pci/pci.c:pci_store_saved_state
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/xenbus/xenbus_xs.c:split
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/message.c:usb_cache_string
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/input/mousedev.c:mousedev_read
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_hw_request
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - net/socket.c:kernel_connect
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/sysctl_net_core.c:dump_cpumask
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/filter.c:bpf_convert_filter
  - net/core/gro.c:skb_gro_receive
  - net/sched/sch_api.c:qdisc_get_stab
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/unix/af_unix.c:unix_create_addr
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_del
  - net/ipv6/calipso.c:calipso_opt_insert
  - net/ipv6/calipso.c:calipso_opt_insert
  - net/packet/af_packet.c:packet_mc_add
  - net/wireless/wext-core.c:wireless_send_event
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_query.c:dns_query
  - net/dns_resolver/dns_query.c:dns_query
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mctp/device.c:mctp_rtm_newaddr
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_mab_cp
  - lib/maple_tree.c:mas_mab_cp
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In init/main.c (ffffffff810037fb)
Location: include/linux/fortify-string.h:504
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/core.c:x86_pmu_add
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/ksysfs.c:boot_params_data_read
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_copy_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/mpparse.c:check_irq_src
  - arch/x86/kernel/apic/apic.c:smp_init_primary_thread_mask
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:emulate_umip_insn
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:numa_remove_memblk_from
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/energy_model.c:em_create_pd
  - kernel/printk/printk.c:console_prepend_dropped
  - kernel/printk/printk.c:record_print_text
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/module/decompress.c:module_extend_max_pages
  - kernel/module/sysfs.c:module_add_modinfo_attrs
  - kernel/module/sysfs.c:module_sect_read
  - kernel/profile.c:profile_init
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/user_namespace.c:insert_extent
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/latencytop.c:account_global_scheduler_latency
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:adjust_subprog_starts_after_remove
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/mprog.c:bpf_mprog_entry_shrink
  - kernel/bpf/mprog.c:bpf_mprog_entry_grow
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_bitfield_show
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - certs/blacklist.c:get_raw_hash
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shmem.c:shmem_enabled_store
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/madvise.c:anon_vma_name_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/aio.c:ioctx_add_table
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:verify_data_block
  - fs/verity/signature.c:fsverity_verify_signature
  - fs/binfmt_elf.c:fill_files_note
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/proc/proc_sysctl.c:new_links
  - fs/proc/proc_sysctl.c:new_dir
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_expand_inode_array
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
  - fs/ecryptfs/crypto.c:ecryptfs_copy_filename
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/miscdev.c:ecryptfs_send_miscdev
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/debugfs/file.c:debugfs_write_file_str
  - fs/pstore/platform.c:decompress_record
  - fs/efivarfs/file.c:efivarfs_file_read
  - fs/efivarfs/super.c:efivarfs_callback
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - security/keys/encrypted-keys/encrypted.c:__ekey_init
  - security/security.c:lsm_fill_user_ctx
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/tomoyo/audit.c:tomoyo_print_bprm
  - security/tomoyo/audit.c:tomoyo_print_bprm
  - security/tomoyo/audit.c:tomoyo_print_bprm
  - security/tomoyo/audit.c:tomoyo_print_bprm
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/lsm.c:do_setattr
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
  - security/integrity/ima/ima_template_lib.c:ima_write_template_field_data
  - crypto/lskcipher.c:crypto_lskcipher_crypt_unaligned
  - crypto/akcipher.c:crypto_akcipher_sync_prep
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/sha3_generic.c:crypto_sha3_update
  - crypto/sha3_generic.c:crypto_sha3_update
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_generate_id
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_generate_id
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - block/blk-map.c:bio_alloc_map_data
  - io_uring/rw.c:io_req_map_rw
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_create
  - lib/crypto/blake2s.c:blake2s_update
  - lib/crypto/blake2s.c:blake2s_update
  - lib/crypto/mpi/mpicoder.c:mpi_read_buffer
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh64_update
  - lib/xxhash.c:xxh32_update
  - lib/xxhash.c:xxh32_update
  - lib/xz/xz_dec_stream.c:fill_temp
  - lib/xz/xz_dec_lzma2.c:lzma2_lzma
  - lib/group_cpus.c:group_cpus_evenly
  - drivers/pci/pci.c:pci_store_saved_state
  - drivers/pci/pci.c:pci_store_saved_state
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/xenbus/xenbus_xs.c:split
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/hvc/hvc_console.c:hvc_console_print
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/gpu/drm/drm_edid.c:drm_edid_to_eld
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/message.c:usb_cache_string
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/input/mousedev.c:mousedev_read
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_clear
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_resume
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_hw_request
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_command_with_size
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - net/socket.c:kernel_connect
  - net/socket.c:kernel_bind
  - net/socket.c:sock_sendmsg
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/sysctl_net_core.c:dump_cpumask
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/filter.c:bpf_convert_filter
  - net/core/gro.c:skb_gro_receive
  - net/core/netprio_cgroup.c:extend_netdev_table
  - net/sched/sch_api.c:qdisc_get_stab
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv4/tcp_ao.c:tcp_ao_get_repair
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_hdr
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/unix/af_unix.c:unix_create_addr
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_del
  - net/ipv6/calipso.c:calipso_opt_insert
  - net/ipv6/calipso.c:calipso_opt_insert
  - net/packet/af_packet.c:packet_mc_add
  - net/devlink/health.c:devlink_fmsg_put_name
  - net/wireless/wext-core.c:wireless_send_event
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_query.c:dns_query
  - net/dns_resolver/dns_query.c:dns_query
  - net/xdp/xsk_buff_pool.c:xp_fill_cb
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mctp/device.c:mctp_rtm_newaddr
  - lib/maple_tree.c:mas_mab_cp
  - lib/maple_tree.c:mas_mab_cp
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/maple_tree.c:mab_shift_right
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
