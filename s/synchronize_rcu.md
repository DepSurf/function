# Function: <code>synchronize_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810326e9)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810746e2)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8108161f)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
```
In kernel/notifier.c (ffffffff810a1642)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
```
```
In kernel/printk/printk.c (ffffffff810d6c10)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/rcu/sync.c (ffffffff810e36e0)
Location: include/linux/rcupdate.h:310
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/rcupdate.h:310
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81177531)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
```
```
In kernel/bpf/arraymap.c (ffffffff811780ed)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
```
```
In kernel/events/core.c (ffffffff8117950f)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In kernel/padata.c (ffffffff81189f89)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In mm/memcontrol.c (ffffffff811fb84c)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/filesystems.c (ffffffff8122b146)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/namespace.c (ffffffff8122baad)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - fs/namespace.c:replace_mount_options
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8123c3a4)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_umount
```
```
In fs/eventpoll.c (ffffffff81254a56)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_destroy_wakeup_source
```
```
In security/keys/gc.c (ffffffff8132f120)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/smack/smackfs.c (ffffffff8136520e)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8137f4fd)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In block/blk-core.c (ffffffff813b8d96)
Location: include/linux/rcupdate.h:310
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b5be6)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/tty/sysrq.c (ffffffff814edce2)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8152587d)
Location: include/linux/rcupdate.h:310
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8153371b)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815396a3)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/base/power/wakeup.c (ffffffff8155b9ea)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81666ef2)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/input/input.c:__input_release_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff8166b735)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff8166cf38)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/md/md.c (ffffffff8168da87)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bbc42)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff816f73a2)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/socket.c (ffffffff816fdf1a)
Location: include/linux/rcupdate.h:310
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81710dad)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/sysctl_net_core.c (ffffffff8171306e)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81716467)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
```
```
In net/netfilter/core.c (ffffffff81750fd4)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_afinfo
```
```
In net/netfilter/nf_log.c (ffffffff81751eb8)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_unset
  - net/netfilter/nf_log.c:nf_log_unregister
```
```
In net/netfilter/nf_queue.c (ffffffff81752714)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_unregister_queue_handler
```
```
In net/ipv4/tcp_cong.c (ffffffff81780303)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/fib_trie.c (ffffffff8179ebab)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:tnode_free
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b12c1)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7681)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb754)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
```
```
In net/ipv6/raw.c (ffffffff817e5064)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8180cbfe)
Location: include/linux/rcupdate.h:310
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810e36e0-ffffffff810e36eb: synchronize_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103183f)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075f31)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In kernel/notifier.c (ffffffff810a4d62)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
```
```
In kernel/sched/core.c (ffffffff810b29c2)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/printk/printk.c (ffffffff810dbe30)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/rcu/sync.c (ffffffff810e9a00)
Location: include/linux/rcupdate.h:319
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/rcupdate.h:319
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81186a75)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
```
```
In kernel/bpf/arraymap.c (ffffffff8118772f)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
```
```
In kernel/bpf/stackmap.c (ffffffff8118816d)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_free
```
```
In kernel/events/core.c (ffffffff8119010c)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
```
```
In kernel/padata.c (ffffffff8119c689)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In mm/zswap.c (ffffffff811f5f07)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff8121f530)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/filesystems.c (ffffffff812538a6)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/namespace.c (ffffffff81254415)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:replace_mount_options
```
```
In fs/fs-writeback.c (ffffffff81264214)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_umount
```
```
In fs/eventpoll.c (ffffffff8127d276)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_destroy_wakeup_source
```
```
In security/keys/gc.c (ffffffff81363dc9)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/smack/smackfs.c (ffffffff8139b309)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813b8ced)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff813d6323)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In block/blk-core.c (ffffffff813fcb86)
Location: include/linux/rcupdate.h:319
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505588)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/tty/sysrq.c (ffffffff8153e962)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/iommu/dmar.c (ffffffff81588d6d)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158e173)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/base/power/wakeup.c (ffffffff815adc6a)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/scsi/scsi.c (ffffffff815ffaff)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
```
In drivers/input/input.c (ffffffff816c738c)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
```
```
In drivers/input/mousedev.c (ffffffff816cb9f5)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff816cefff)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff816f64bc)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d512)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8175c042)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/socket.c (ffffffff81764a2a)
Location: include/linux/rcupdate.h:319
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817786df)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/sysctl_net_core.c (ffffffff8177b081)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffff8177e347)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
```
```
In net/netfilter/core.c (ffffffff817bd004)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_afinfo
```
```
In net/netfilter/nf_log.c (ffffffff817bdfa4)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/netfilter/nf_log.c:nf_log_unset
```
```
In net/ipv4/tcp_cong.c (ffffffff817ed7e3)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/fib_trie.c (ffffffff8180cb0b)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:tnode_free
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181e212)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
```
```
In net/xfrm/xfrm_state.c (ffffffff81824746)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/xfrm/xfrm_input.c (ffffffff81828676)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
```
```
In net/ipv6/raw.c (ffffffff81853344)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8187ef76)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810e9a00-ffffffff810e9a0b: synchronize_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103148f)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81079b11)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In kernel/notifier.c (ffffffff810aa9c2)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
```
```
In kernel/sched/core.c (ffffffff810b8fb2)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/printk/printk.c (ffffffff810e2e50)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/rcu/sync.c (ffffffff810f08c0)
Location: include/linux/rcupdate.h:319
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/rcupdate.h:319
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811937f5)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
```
```
In kernel/bpf/arraymap.c (ffffffff811956ef)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
```
```
In kernel/bpf/stackmap.c (ffffffff8119703d)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_free
```
```
In kernel/events/core.c (ffffffff811a0115)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
```
```
In kernel/padata.c (ffffffff811ac4a5)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In mm/zswap.c (ffffffff81206833)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff81231ba0)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/filesystems.c (ffffffff81266af6)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/namespace.c (ffffffff81267825)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:replace_mount_options
```
```
In fs/fs-writeback.c (ffffffff81277654)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_umount
```
```
In fs/eventpoll.c (ffffffff81290e06)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_destroy_wakeup_source
```
```
In security/keys/gc.c (ffffffff8137a5e5)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/smack/smackfs.c (ffffffff813b1ff9)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813d00ad)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff813edbf3)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In block/blk-core.c (ffffffff81416526)
Location: include/linux/rcupdate.h:319
Inline: True
```
```
In block/blk-mq.c (ffffffff8142136c)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529778)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/tty/sysrq.c (ffffffff8156afb2)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/iommu/dmar.c (ffffffff815b642d)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bbc73)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/base/power/wakeup.c (ffffffff815dca3a)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/scsi/scsi.c (ffffffff8162f15f)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
```
In drivers/input/input.c (ffffffff816f537c)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
```
```
In drivers/input/mousedev.c (ffffffff816f99a5)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff816fcccf)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff81727d05)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817500f2)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff817885b2)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/socket.c (ffffffff81791aaa)
Location: include/linux/rcupdate.h:319
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817a5702)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/sysctl_net_core.c (ffffffff817a86d4)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffff817abb47)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
```
```
In net/netfilter/core.c (ffffffff817ec894)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_afinfo
```
```
In net/netfilter/nf_log.c (ffffffff817ed8e4)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/netfilter/nf_log.c:nf_log_unset
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e113)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/fib_trie.c (ffffffff8183dd8b)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:tnode_free
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184fa92)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81855e56)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a056)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
```
```
In net/ipv6/raw.c (ffffffff81885144)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff818b3826)
Location: include/linux/rcupdate.h:319
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810f08c0-ffffffff810f08cb: synchronize_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8102f6ac)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810783c4)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In kernel/notifier.c (ffffffff810a7542)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
```
```
In kernel/printk/printk.c (ffffffff810e1f40)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/rcu/sync.c (ffffffff810f08a0)
Location: include/linux/rcupdate.h:94
Inline: False
```
```
In kernel/rcu/tree.c (ffffffff810f5b45)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu
```
```
In kernel/kprobes.c (ffffffff81140a69)
Location: include/linux/rcupdate.h:94
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8119ac15)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
```
```
In kernel/bpf/arraymap.c (ffffffff8119cb5f)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
```
```
In kernel/bpf/stackmap.c (ffffffff8119ecad)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_free
```
```
In kernel/events/core.c (ffffffff811a7d13)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
```
```
In kernel/padata.c (ffffffff811b39f5)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In mm/swap_state.c (ffffffff8120c5db)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - mm/swap_state.c:exit_swap_address_space
```
```
In mm/zswap.c (ffffffff812127d3)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff8123db60)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/filesystems.c (ffffffff81274376)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/namespace.c (ffffffff81274ee5)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff812849f5)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_umount
```
```
In fs/eventpoll.c (ffffffff8129dc96)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_destroy_wakeup_source
```
```
In security/keys/gc.c (ffffffff8138e20a)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/smack/smackfs.c (ffffffff813c85f9)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813e3940)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff813fa053)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In block/blk-core.c (ffffffff81423c10)
Location: include/linux/rcupdate.h:94
Inline: True
```
```
In block/blk-mq.c (ffffffff81433454)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c27b)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/tty/sysrq.c (ffffffff8157f5de)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/iommu/dmar.c (ffffffff815cc2ad)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d18a3)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/scsi/scsi.c (ffffffff81643f3f)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
```
In drivers/input/input.c (ffffffff8170ae4c)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
```
```
In drivers/input/mousedev.c (ffffffff8170f505)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff817125ab)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff81740279)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/edac/edac_mc.c (ffffffff8175c129)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8175da10)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff8175f950)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176ebb2)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff817a76b2)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/socket.c (ffffffff817af38a)
Location: include/linux/rcupdate.h:94
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817c3965)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/sysctl_net_core.c (ffffffff817c6d5c)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffff817ca0d7)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
```
```
In net/netfilter/core.c (ffffffff8180ccc4)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_afinfo
```
```
In net/netfilter/nf_log.c (ffffffff8180d8f4)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_unregister
```
```
In net/ipv4/tcp_cong.c (ffffffff8183e873)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81841ef3)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/fib_trie.c (ffffffff8185f57b)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:tnode_free
```
```
In net/xfrm/xfrm_policy.c (ffffffff81873625)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81879ab0)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff8187de30)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
```
```
In net/ipv6/raw.c (ffffffff818ab534)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff818da1ea)
Location: include/linux/rcupdate.h:94
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810f08a0-ffffffff810f08ab: synchronize_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810316ac)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e714)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In kernel/notifier.c (ffffffff810adcc2)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
```
```
In kernel/printk/printk.c (ffffffff810ea020)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/rcu/sync.c (ffffffff810fa540)
Location: include/linux/rcupdate.h:92
Inline: False
```
```
In kernel/rcu/tree.c (ffffffff810ff945)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu
```
```
In kernel/kprobes.c (ffffffff8114d909)
Location: include/linux/rcupdate.h:92
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811aa425)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
```
```
In kernel/bpf/arraymap.c (ffffffff811ac5ff)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
```
```
In kernel/bpf/lpm_trie.c (ffffffff811ae728)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_free
```
```
In kernel/bpf/devmap.c (ffffffff811af332)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cpumap.c (ffffffff811b0202)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_free
```
```
In kernel/bpf/sockmap.c (ffffffff811b1855)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_map_free
```
```
In kernel/bpf/stackmap.c (ffffffff811b1c1d)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_free
```
```
In kernel/events/core.c (ffffffff811bb483)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
```
```
In kernel/padata.c (ffffffff811c7685)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/memremap.c (ffffffff811c8d9d)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/memremap.c:pgmap_radix_release
```
```
In mm/swap_state.c (ffffffff81225d4b)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - mm/swap_state.c:exit_swap_address_space
```
```
In mm/zswap.c (ffffffff8122d1e3)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff8125d6f0)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/filesystems.c (ffffffff81296c76)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/namespace.c (ffffffff812977a5)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff812a7535)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_umount
```
```
In fs/eventpoll.c (ffffffff812c0e86)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_destroy_wakeup_source
```
```
In security/keys/gc.c (ffffffff813b36ab)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/smack/smackfs.c (ffffffff813eea89)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8140a730)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814224f3)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In block/blk-core.c (ffffffff8144f0f0)
Location: include/linux/rcupdate.h:92
Inline: True
```
```
In block/blk-mq.c (ffffffff8145f034)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159ede9)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/tty/sysrq.c (ffffffff815e414e)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/iommu/dmar.c (ffffffff8163307d)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81638673)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b39fa)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
```
In drivers/input/input.c (ffffffff8177c02c)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
```
```
In drivers/input/mousedev.c (ffffffff81780775)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff817837db)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff817aab20)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/edac/edac_mc.c (ffffffff817ce369)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff817cfa80)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff817d19e0)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e44b2)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181e912)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/socket.c (ffffffff818274ca)
Location: include/linux/rcupdate.h:92
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183d425)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/sysctl_net_core.c (ffffffff81840934)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffff818439f7)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
```
```
In net/core/rtnetlink.c (ffffffff8185a3da)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/netfilter/core.c (ffffffff8188bca4)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_afinfo
```
```
In net/netfilter/nf_log.c (ffffffff8188cdd4)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_unregister
```
```
In net/ipv4/tcp_cong.c (ffffffff818be0c3)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff818c17c3)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/fib_trie.c (ffffffff818df5eb)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:tnode_free
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3f85)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa500)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff818fecc0)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
```
```
In net/ipv6/raw.c (ffffffff8192e0d4)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8195fdda)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810fa540-ffffffff810fa54b: synchronize_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103292c)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81081745)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In kernel/notifier.c (ffffffff810b4b32)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
```
```
In kernel/printk/printk.c (ffffffff810f22e0)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/rcu/sync.c (ffffffff81102ac0)
Location: include/linux/rcupdate.h:92
Inline: False
```
```
In kernel/rcu/tree.c (ffffffff811072f7)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu
```
```
In kernel/kprobes.c (ffffffff8115c306)
Location: include/linux/rcupdate.h:92
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811af491)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In kernel/bpf/hashtab.c (ffffffff811c1a65)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
```
```
In kernel/bpf/arraymap.c (ffffffff811c41c5)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
```
```
In kernel/bpf/lpm_trie.c (ffffffff811c5c65)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_free
```
```
In kernel/bpf/devmap.c (ffffffff811c9e65)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cpumap.c (ffffffff811ca445)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_free
```
```
In kernel/bpf/sockmap.c (ffffffff811cde75)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:sock_map_free
```
```
In kernel/bpf/stackmap.c (ffffffff811d09d5)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_free
```
```
In kernel/events/core.c (ffffffff811db39f)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
```
```
In kernel/padata.c (ffffffff811e78d5)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/memremap.c (ffffffff811e932e)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - kernel/memremap.c:pgmap_radix_release
```
```
In mm/swap_state.c (ffffffff8124835b)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - mm/swap_state.c:exit_swap_address_space
```
```
In mm/zswap.c (ffffffff8124fbbf)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff81281250)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/filesystems.c (ffffffff812bd216)
Location: include/linux/rcupdate.h:92
Inline: True
```
```
In fs/namespace.c (ffffffff812bd995)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff812ce0f0)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_umount
```
```
In fs/eventpoll.c (ffffffff812e9db6)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_destroy_wakeup_source
```
```
In security/keys/gc.c (ffffffff813e3df6)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/smack/smackfs.c (ffffffff8141fb2b)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8143bf40)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81454c54)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
```
In block/blk-core.c (ffffffff81481cb4)
Location: include/linux/rcupdate.h:92
Inline: True
```
```
In block/blk-mq.c (ffffffff81492957)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6b01)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/tty/sysrq.c (ffffffff8161d4b3)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/iommu/dmar.c (ffffffff8166e29d)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81673973)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/scsi/scsi_lib.c (ffffffff816efaca)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
```
In drivers/input/input.c (ffffffff817bd0ec)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
```
```
In drivers/input/mousedev.c (ffffffff817c276d)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff817c47eb)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff817f61aa)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/edac/edac_mc.c (ffffffff81817099)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818187e0)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff8181a790)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d6c3)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81868b62)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/socket.c (ffffffff81870aea)
Location: include/linux/rcupdate.h:92
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81887ca8)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/sysctl_net_core.c (ffffffff8188b031)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffff8188ddae)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
```
```
In net/core/rtnetlink.c (ffffffff818a5c8a)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/netfilter/nf_log.c (ffffffff818e0834)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_unregister
```
```
In net/ipv4/tcp_cong.c (ffffffff81913e23)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819173c3)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/fib_trie.c (ffffffff81935dc8)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:tnode_free
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a77d)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81951010)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81955790)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
```
```
In net/ipv6/raw.c (ffffffff81986d61)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819b959a)
Location: include/linux/rcupdate.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81102ac0-ffffffff81102acb: synchronize_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113120)
Location: kernel/rcu/tree_plugin.h:1119
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_reset
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_replace
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/swap_state.c:exit_swap_address_space
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:cleanup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81113120-ffffffff8111319c: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111ccc0)
Location: kernel/rcu/tree.c:2667
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_reset
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff8111ccc0-ffffffff8111cd3c: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127a70)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81127a70-ffffffff81127ade: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81137b80)
Location: kernel/rcu/tree.c:3422
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:iounmap_trace_core
  - kernel/notifier.c:unregister_die_notifier
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/update.c:rcu_tasks_postgp
  - kernel/rcu/update.c:rcu_tasks_pregp_step
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:unregister_kretprobe
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:__padata_free
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/page_reporting.c:page_reporting_unregister
  - fs/file.c:expand_fdtable
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_pause
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:__register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
**Symbols:**

```
ffffffff81137b80-ffffffff81137bee: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811331c0)
Location: kernel/rcu/tree.c:3732
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:iounmap_trace_core
  - kernel/notifier.c:unregister_die_notifier
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:padata_replace
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pageunmap_range
  - mm/page_reporting.c:page_reporting_unregister
  - fs/file.c:expand_fdtable
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - security/keys/gc.c:key_garbage_collector
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_bridge_channels
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_pause
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:__register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:free_netdev
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
**Symbols:**

```
ffffffff811331c0-ffffffff8113322e: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133230)
Location: kernel/rcu/tree.c:3777
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:unregister_die_notifier
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/page_reporting.c:page_reporting_unregister
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - security/keys/gc.c:key_garbage_collector
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_pause
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
**Symbols:**

```
ffffffff81133230-ffffffff8113329e: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811554d0)
Location: kernel/rcu/tree.c:3738
Inline: True
Direct callers:
  - arch/x86/kernel/irq.c:kvm_set_posted_intr_wakeup_handler
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:unregister_die_notifier
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/migrate.c:migrate_on_reclaim_callback
  - mm/migrate.c:__set_migration_target_nodes
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/page_reporting.c:page_reporting_unregister
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - security/keys/gc.c:key_garbage_collector
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_pause
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - net/socket.c:sock_unregister
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
**Symbols:**

```
ffffffff811554d0-ffffffff8115553e: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117efe0)
Location: kernel/rcu/tree.c:3834
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:unregister_die_notifier
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/rcu/update.c:rcu_tasks_postgp
  - kernel/rcu/update.c:rcu_tasks_pregp_step
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:free_module
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/migrate.c:migrate_on_reclaim_callback
  - mm/migrate.c:__set_migration_target_nodes
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/page_reporting.c:page_reporting_unregister
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/super.c:__ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - block/blk-mq.c:blk_mq_update_nr_requests
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_pause
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - net/socket.c:sock_unregister
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_pack
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
**Symbols:**

```
ffffffff8117efe0-ffffffff8117f0ac: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b7d95)
Location: kernel/rcu/tree.c:3532
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:kvfree_call_rcu
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:unregister_die_notifier
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:free_module
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/syscall.c:bpf_map_update_value
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/page_reporting.c:page_reporting_unregister
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/super.c:__ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_pause
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - net/socket.c:sock_unregister
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_pack
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/devlink.c:devl_traps_unregister
  - net/core/devlink.c:devl_traps_unregister
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - lib/logic_pio.c:logic_pio_unregister_range
```
**Symbols:**

```
ffffffff811b2e10-ffffffff811b2ecf: synchronize_rcu.part.0 (STB_LOCAL)
ffffffff811b6310-ffffffff811b639d: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c8bb0)
Location: kernel/rcu/tree.c:3524
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:unregister_die_notifier
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:free_module
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/syscall.c:bpf_map_update_value
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/page_reporting.c:page_reporting_unregister
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/namespace.c:kern_unmount
  - fs/namespace.c:kern_unmount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/super.c:__ext4_remount
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
  - security/keys/gc.c:key_garbage_collector
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - io_uring/io_uring.c:io_ring_exit_work
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_pause
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_populate_hdev
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - net/socket.c:sock_unregister
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_pack
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/devlink/leftover.c:devl_traps_unregister
  - net/devlink/leftover.c:devl_traps_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - lib/logic_pio.c:logic_pio_unregister_range
```
**Symbols:**

```
ffffffff811c8bb0-ffffffff811c8ceb: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811dac20)
Location: kernel/rcu/tree.c:3596
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/kernel/reboot.c:cpu_emergency_unregister_virt_callback
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update
  - kernel/notifier.c:unregister_die_notifier
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:free_module
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_uninstall
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/page_reporting.c:page_reporting_unregister
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/namespace.c:kern_unmount
  - fs/namespace.c:kern_unmount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/super.c:__ext4_remount
  - fs/debugfs/file.c:debugfs_write_file_str
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
  - security/keys/gc.c:key_garbage_collector
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - io_uring/io_uring.c:io_ring_exit_work
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/gpu/drm/drm_file.c:drm_file_update_pid
  - drivers/net/netkit.c:netkit_uninit
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/net/netkit.c:netkit_link_release
  - drivers/net/netkit.c:netkit_prog_detach
  - drivers/net/netkit.c:netkit_prog_attach
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_pause
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_populate_hdev
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - net/socket.c:sock_unregister
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/tcp_ao.c:tcp_ao_del_cmd
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/devlink/trap.c:devl_traps_unregister
  - net/devlink/trap.c:devl_traps_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - lib/logic_pio.c:logic_pio_unregister_range
```
**Symbols:**

```
ffffffff811dac20-ffffffff811dad5b: synchronize_rcu (STB_GLOBAL)
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
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018fff0)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - arch/arm64/kernel/debug-monitors.c:unregister_debug_hook
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffff80001018fff0-ffff800010190080: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc808)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_reset_cpu
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_detach_client
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
c03dc808-c03dc8a0: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e9d30)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:fd_array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/misc/cxl/base.c:unregister_cxl_calls
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - net/socket.c:sock_unregister
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
c0000000001e9d30-c0000000001e9ddc: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000122638)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffe000122638-ffffffe0001226a0: synchronize_rcu (STB_GLOBAL)
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
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81120050)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81120050-ffffffff811200be: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111a50)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81111a50-ffffffff81111abe: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111df40)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - fs/file.c:expand_files
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/netfilter/nfnetlink.c:nfnetlink_subsys_unregister
  - net/netfilter/nfnetlink_queue.c:nfnl_queue_net_exit_batch
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_unregister
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_unregister
  - net/netfilter/nf_conntrack_extend.c:nf_ct_extend_unregister
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exit
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_net_exit_batch
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff8111df40-ffffffff8111dfae: synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129960)
Location: kernel/rcu/tree.c:2727
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_stop
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/super.c:ext4_remount
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_quiesce_queue
  - lib/logic_pio.c:logic_pio_unregister_range
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/netpoll.c:__netpoll_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_free
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81129960-ffffffff811299ca: synchronize_rcu (STB_GLOBAL)
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
