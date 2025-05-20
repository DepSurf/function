# Function: <code>list_del_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810326c1)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81072f0c)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
```
```
In kernel/exit.c (ffffffff81082660)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810995d8)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810b0582)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810bbfe6)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unregister_fair_sched_group
```
```
In kernel/printk/printk.c (ffffffff810d6bdf)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/core.c (ffffffff810e8843)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_disable_func
  - kernel/livepatch/core.c:klp_disable_func
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff8110778a)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/module.c:free_module
  - kernel/module.c:load_module
```
```
In kernel/cgroup.c (ffffffff81112b0b)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:create_css
```
```
In kernel/auditfilter.c (ffffffff81124698)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_del_rule
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81129ddf)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_tree.c (ffffffff8112ac18)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8112e078)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81166408)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff81167cfe)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811702fe)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In kernel/events/core.c (ffffffff811794d8)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
```
```
In mm/backing-dev.c (ffffffff811aefdb)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff811cc934)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff811d8267)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81254b1c)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/timerfd.c (ffffffff81258060)
Location: include/linux/rculist.h:129
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff812d0bde)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
```
```
In ipc/sem.c (ffffffff81327531)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:exit_sem
```
```
In security/selinux/hooks.c (ffffffff81349e5f)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_disable
```
```
In security/selinux/netif.c (ffffffff8134cda6)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff8134d2f4)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_flush
```
```
In security/selinux/netport.c (ffffffff8134d56c)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_flush
```
```
In security/apparmor/policy.c (ffffffff8137f157)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/apparmor/policy.c:__list_remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81394bea)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff81394f61)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8139582a)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In lib/bug.c (ffffffff813e8d70)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/textsearch.c (ffffffff81411762)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81479be6)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b5bac)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff814bd03b)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:__dma_request_channel
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81525849)
Location: include/linux/rculist.h:129
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff815344b1)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81539684)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8153b8d3)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff8155b9be)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81667092)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff8166b70b)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff8166cf0e)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff8168da17)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff816ae101)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff816f7386)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/gen_estimator.c (ffffffff8170f6c3)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/net_namespace.c (ffffffff81710cbf)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81713fe5)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:dev_remove_offload
```
```
In net/core/dev_addr_lists.c (ffffffff817227b2)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/fib_rules.c (ffffffff8173a5c2)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/sched/sch_api.c (ffffffff817430f3)
Location: include/linux/rculist.h:129
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8174a0aa)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/netfilter/core.c (ffffffff81751289)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_net_hook
```
```
In net/ipv4/tcp_cong.c (ffffffff817802d9)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/af_inet.c (ffffffff81793eaf)
Location: include/linux/rculist.h:129
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff817a8a0c)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817adea1)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7659)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff817c351f)
Location: include/linux/rculist.h:129
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8180cafa)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8180d175)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e36b)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031817)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81074782)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff81085471)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff8109cb5b)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810b317e)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810c227e)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/printk/printk.c (ffffffff810dbdff)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/core.c (ffffffff810efd80)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff81110b59)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup.c (ffffffff8111a22d)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8112dac9)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff811322e0)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81132e11)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8113630c)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811713a1)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff81171eb3)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff8117532e)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117da18)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In kernel/events/core.c (ffffffff81189d48)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffff811c8c12)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/vmalloc.c (ffffffff811eb488)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/zswap.c (ffffffff811f652f)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff8127ee34)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff81280960)
Location: include/linux/rculist.h:129
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81303c90)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff8135e804)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/hooks.c (ffffffff8137fbb6)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_disable
```
```
In security/selinux/netif.c (ffffffff81382d56)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff81383325)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813835a5)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy.c (ffffffff813b88cd)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/apparmor/policy.c:__list_remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813d05dc)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff813d0add)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff813d1576)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In lib/bug.c (ffffffff8142efe0)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/textsearch.c (ffffffff814594d2)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81895015)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8150554c)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff8150d041)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff81588d51)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158e154)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81590403)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff815adc3e)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff816c7342)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff816cb9cb)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff816cd24e)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff816ef087)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff8170e5ba)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8175c026)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/gen_estimator.c (ffffffff81776f21)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/net_namespace.c (ffffffff817785ee)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8177dfab)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8178c20e)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/fib_rules.c (ffffffff817a6da1)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/sched/sch_api.c (ffffffff817aff84)
Location: include/linux/rculist.h:129
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b6fca)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/netfilter/core.c (ffffffff817bd2b9)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_net_hook
```
```
In net/ipv4/tcp_cong.c (ffffffff817ed7b9)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/af_inet.c (ffffffff8180182f)
Location: include/linux/rculist.h:129
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818161ad)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181af96)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff818246a9)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff818305cf)
Location: include/linux/rculist.h:129
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff8186f676)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8187ec74)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8187f643)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818809eb)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff8188f00e)
Location: include/linux/rculist.h:129
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031467)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81078302)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff8108a3e1)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810a5113)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810b976e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810c82d0)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/printk/printk.c (ffffffff810e2e1f)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/core.c (ffffffff810f6960)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff811183b8)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup.c (ffffffff811220dd)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff811377f9)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff8113c040)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8113cb4d)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8114008c)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117cb11)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff8117d623)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff81180d1e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81189628)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In kernel/events/core.c (ffffffff81199128)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffff811d8d32)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/vmalloc.c (ffffffff811fc6f8)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/zswap.c (ffffffff81206ecc)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff812929c4)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff812944d0)
Location: include/linux/rculist.h:127
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81319c50)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff81374fdb)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/hooks.c (ffffffff81396646)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_disable
```
```
In security/selinux/netif.c (ffffffff813997d6)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff81399da5)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8139a025)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy.c (ffffffff813cfc71)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/apparmor/policy.c:__list_remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813e7cdc)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff813e81dd)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff813e8ca6)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In lib/bug.c (ffffffff8144b150)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/textsearch.c (ffffffff81477e92)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff818c976e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8152973c)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff81539151)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff815b6411)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bbc54)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff815bdc94)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff815c7318)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff815dca0e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff816f5332)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff816f997b)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff816fb1ee)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff817211e3)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff8174075a)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81788596)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff817a560e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff817abbc8)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff817b9ade)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/fib_rules.c (ffffffff817d58c3)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/netlink/af_netlink.c (ffffffff817e6a4a)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e0e9)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/af_inet.c (ffffffff8183279f)
Location: include/linux/rculist.h:127
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8184795d)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184c856)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81855db9)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff8186204f)
Location: include/linux/rculist.h:127
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818a25e6)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff818b3524)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff818b3ef3)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b529b)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff818c340e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8102f684)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81076d1a)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff81087435)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810a2283)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810b434e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810c1fc6)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/printk/printk.c (ffffffff810e1f0f)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff810f8b36)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
```
```
In kernel/module.c (ffffffff811197eb)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81121c2d)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81138d59)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff8113d708)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8113e124)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff81141436)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117f761)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811801b8)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff81183b2e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118c163)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In kernel/bpf/core.c (ffffffff8118f2ed)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
```
```
In kernel/events/core.c (ffffffff811a1e86)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffff811e1222)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff812073d7)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/zswap.c (ffffffff812130bc)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In fs/eventpoll.c (ffffffff8129fb60)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff812a17b0)
Location: include/linux/rculist.h:127
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81310f61)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff81388abe)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff813afbe6)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff813b0245)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813b0505)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff813b0758)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff813e3a55)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813ec5f5)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff813f46db)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff813f505c)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff81433406)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
```
In block/blk-stat.c (ffffffff814343ff)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/textsearch.c (ffffffff814811d2)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81900d55)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c23f)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff8154c9d1)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff815cc291)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d1884)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff815d3d79)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff815dbff8)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff815f157e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff8170ae02)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff8170f4db)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff81710bce)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff81738293)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff8175a434)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff8175c0f2)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8175d9ed)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff8175f92d)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff817a7696)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff817c386e)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff817ca158)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff817d861f)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/fib_rules.c (ffffffff817f4d0f)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/netlink/af_netlink.c (ffffffff8180684a)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff8183e849)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81841ec9)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81853abf)
Location: include/linux/rculist.h:127
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8186b2f3)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81870296)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81879a29)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff818863bf)
Location: include/linux/rculist.h:127
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818c8bf0)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff818d9ece)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff818da893)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbbeb)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff818e9da0)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In lib/bug.c (ffffffff818eb3c0)
Location: include/linux/rculist.h:127
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031684)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cf25)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff8108e1c5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810a8b13)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810bb5fe)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810c96f6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/printk/printk.c (ffffffff810e9fef)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff81102d6a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
```
```
In kernel/module.c (ffffffff81124d9c)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8112d45b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81145a49)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff8114a4d8)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8114af24)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8114e2d6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff811672fa)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8118d061)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff8118da58)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff8119187e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199c29)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In kernel/bpf/core.c (ffffffff8119d75d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
```
```
In kernel/bpf/devmap.c (ffffffff811af2f1)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811b5b06)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffffffff811f7232)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff812204c7)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/zswap.c (ffffffff8122dc18)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hmm.c (ffffffff8126d2ee)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_range_done
```
```
In fs/eventpoll.c (ffffffff812c2f64)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff812c4ad0)
Location: include/linux/rculist.h:128
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81332ce6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff813ad787)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff813d5c96)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff813d62e5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813d65a5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff813d67f8)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff8140a857)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81413f85)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff8141c78b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8141d21c)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff8145efe6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
```
In block/blk-stat.c (ffffffff8146008f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/textsearch.c (ffffffff814bd012)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff8198ad55)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159eda5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff815aff61)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff81633061)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81638654)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8163aaa9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff81643028)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff81658b6e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff8177bfe2)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff8178074b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (ffffffff81781e4e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (ffffffff817aaac3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff817cc674)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff817ce332)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff817cfa5d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff817d19bd)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181e8f6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff8183d32e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81843a78)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81852d1f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff8185a3b9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff8186a726)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff81870512)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/netlink/af_netlink.c (ffffffff8188551a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff818be099)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff818c1799)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff818d394f)
Location: include/linux/rculist.h:128
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818ebaa6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f0c8d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa479)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff819075cf)
Location: include/linux/rculist.h:128
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81913510)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/calipso.c (ffffffff8194c286)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8195fabe)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81960473)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819617cb)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff8196f4e0)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In lib/bug.c (ffffffff81971300)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032904)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fffb)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff81091fee)
Location: include/linux/rculist.h:128
Inline: True
```
```
In kernel/workqueue.c (ffffffff810af183)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810c2aae)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810d1852)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/printk/printk.c (ffffffff810f22ba)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff8110b3a0)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
```
```
In kernel/module.c (ffffffff8113337f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8113c0f5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81154393)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81158f20)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81159a53)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8115cbc2)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff81176016)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119bbac)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff8119cb03)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6c09)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811af471)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In kernel/bpf/core.c (ffffffff811b1e99)
Location: include/linux/rculist.h:128
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811c9e31)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811d51fb)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffffffff81218464)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff812422a3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/zswap.c (ffffffff81250046)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hmm.c (ffffffff81292cd1)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_range_done
```
```
In fs/eventpoll.c (ffffffff812ebc68)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff812edb5d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffff81363f62)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff813dd23f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff814062a5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff81406927)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81406bd7)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81406e3c)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff8143c063)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814462f5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff8144eb4d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8144f4e6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff8149290e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
```
In block/blk-stat.c (ffffffff81493a9f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/textsearch.c (ffffffff814ef9f2)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff819e7656)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6ac5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff815e8341)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff8166e281)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8167395a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81676099)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff8167e1f4)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff8169469e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff817bd0b7)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff817c2746)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff817c3947)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff817f2ab3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81815007)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff81817081)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818187cb)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff8181a77b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81868b46)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff81887b9d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff818915e0)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8189e43e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff818a5c69)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff818ba4c5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff818c1c94)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/netlink/af_netlink.c (ffffffff818d8ee5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81913df9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81917399)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81929e23)
Location: include/linux/rculist.h:128
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8194225b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819475ad)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81950f89)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff8195e193)
Location: include/linux/rculist.h:128
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8196acd6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff8199feda)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/calipso.c (ffffffff819a6936)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819b9204)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819b9c52)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bbaba)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff819c8bf8)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff819ccd6d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffff819cd6c0)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81033bc4)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81086b3b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff8109a2eb)
Location: include/linux/rculist.h:128
Inline: True
```
```
In kernel/workqueue.c (ffffffff810b82f3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810cbdae)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810db192)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/printk/printk.c (ffffffff810fda0a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff81116b90)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
```
```
In kernel/module.c (ffffffff8113ed2f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81148c75)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff811611b3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81165ee0)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81167078)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff811698c0)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff81183c56)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a9d0c)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811aaee3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b46d9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bd9f6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In kernel/bpf/core.c (ffffffff811c0749)
Location: include/linux/rculist.h:128
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811dd731)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811e40e4)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffffffff8122b3b4)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff812569d3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/zswap.c (ffffffff81264516)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hmm.c (ffffffff812a8221)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_range_done
```
```
In fs/eventpoll.c (ffffffff812ffeb2)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff813025ed)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffff8137c204)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff813f789f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff81421df5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff81422487)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81422747)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff814229ac)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff81458ed3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81463215)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff8146bb1d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8146c4c6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff814ac7f0)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
```
In block/blk-stat.c (ffffffff814adc7f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/textsearch.c (ffffffff81503912)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81a22ac6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f03ec)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff81602361)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff8168c6b1)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81691f2a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81695917)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff8169dc04)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff816b4d1e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff817e4517)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff817ea256)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff817eafb7)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff8181e9b3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81841017)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff81842921)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8184406b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff81845f6b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81888bc6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff818a86ad)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff818b1000)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff818c0c5e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff818c9219)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff818e1345)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff818eab04)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/netlink/af_netlink.c (ffffffff819056d5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81942769)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81945ba9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81959413)
Location: include/linux/rculist.h:128
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81972058)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197917d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff819844d9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81992cf3)
Location: include/linux/rculist.h:128
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8199fca6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff819d6a5d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/calipso.c (ffffffff819dd496)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819f04d4)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f0f22)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f2d2a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a00b28)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff81a05e7e)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffff81a06a20)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035a34)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a73c)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff8109e90b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810bdde9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810d3e5f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810e25f6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff81105d4f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff81120e21)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/module.c (ffffffff8114a08c)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81154bf3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8116d89f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81172a61)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81173c81)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8117677a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff81190807)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b7c88)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b8f56)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811cbade)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811d1289)
Location: include/linux/rculist.h:128
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f2ddd)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811fb2c4)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffffffff8123b002)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff8126ac1b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffff8127f469)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff81320e6f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff81323b62)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffff813a2c56)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff81423dd6)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff8144f9e5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff814500bc)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814503cc)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81450661)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff81486659)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814904d5)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff81498afb)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff81499bae)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff814daaa0)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffffffff814dbeff)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (ffffffff81511c54)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (ffffffff81531a6f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81a92b7d)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81622142)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff81634c3f)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff816c4136)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c9ebb)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816cdbe3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff816d4f98)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff816eec20)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81824f57)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff8182a849)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff8182bb27)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81861c33)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81884219)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff81885726)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81886e42)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff81888d52)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818d3479)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff818f3c8c)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff818fe011)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8190d370)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff819161e9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff8192fb25)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff8193a57a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/devlink.c (ffffffff81947bab)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (ffffffff819668f3)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6d59)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819aa1b9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff819bded3)
Location: include/linux/rculist.h:128
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819dba98)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2c5a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee1f9)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff819fe783)
Location: include/linux/rculist.h:128
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a0bf79)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a442af)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81a4b622)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5f772)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a601e2)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6209a)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a6fd5b)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff81a755fb)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffff81a76380)
Location: include/linux/rculist.h:128
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036234)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b3ac)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810a4ea5)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c43c4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810de37f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810ecca6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff811120cf)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff8112d4ae)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/module.c (ffffffff81155cf6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81160823)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8117973f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff8117e911)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8117faf1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff811826af)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff8119c7f7)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c32f8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c4536)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811d7b44)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811dd819)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811ff7f1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff81208394)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffff81249522)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff81279b2d)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffff8128eec9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff81333c0f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff813368c2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffff813bbab6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff8143db15)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff81469855)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff81469edc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8146a18c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8146a441)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff814a0509)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814aa395)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff814b2a2b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff814b3dae)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff814f3e60)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffffffff814f532f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (ffffffff81532694)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (ffffffff815528ff)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81aca34b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81643c22)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff8165695f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff816e7086)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ece8b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816f1a23)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff816f8dd8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff81712c7c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff818562a7)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff8185c1d9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff8185d49b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81893863)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff818b6139)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff818b76c6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818b8e02)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff818bad02)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff819057f9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff81925c3c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81930341)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8193fa70)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff81948819)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81961d95)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff8196d43a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffffffff81974b8c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff8197ccbb)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (ffffffff8199d373)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff819dda29)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819e0e79)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff819f4af3)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a129c8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19c4a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25069)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81a35373)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a42c29)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ae9f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81a821f2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a963a2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a96e12)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a98c7a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81aa65be)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff81aac455)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffff81aad780)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81038132)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8109273c)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810ac01b)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
```
```
In kernel/workqueue.c (ffffffff810cc038)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810dd49f)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/core.c:cpu_cgroup_css_released
```
```
In kernel/sched/fair.c (ffffffff810f6b46)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff8111d98f)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff8113bbf3)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/module.c (ffffffff81166f19)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8117029d)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
```
```
In kernel/auditfilter.c (ffffffff8118bc00)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81191d39)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81192e04)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff81196840)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811b29d5)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dcefa)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e0f96)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811f44e4)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811fa0f0)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
```
```
In kernel/bpf/devmap.c (ffffffff8122703b)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff81230f04)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffffffff81277879)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff812a8f40)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks
```
```
In mm/zswap.c (ffffffff812c1b8d)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff8136e11e)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff81371045)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
```
In fs/io-wq.c (ffffffff8138adc1)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_exit
```
```
In fs/ext4/mballoc.c (ffffffff81406f09)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff8148e68a)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff814bdac2)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff814be0ec)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814be3dc)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In security/selinux/ibpkey.c (ffffffff814d1a81)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
```
```
In security/apparmor/policy.c (ffffffff814fc37c)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
```
In security/apparmor/policy_ns.c (ffffffff81508045)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff81511d1b)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8151333e)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff81554490)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffffffff81555d47)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/textsearch.c (ffffffff815dbce2)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In lib/bug.c (ffffffff815e77d0)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/logic_pio.c (ffffffff815ed1c4)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In drivers/acpi/osl.c (ffffffff81bc269b)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1552)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff8170729f)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179d7f6)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a517b)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff817aa608)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
```
```
In drivers/base/core.c (ffffffff817b1b88)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff817ce57c)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81928637)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff8192eaf9)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff81931667)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff819634d1)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff819856ff)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_delete
```
```
In drivers/edac/edac_mc.c (ffffffff81988dd6)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
```
In drivers/edac/edac_device.c (ffffffff81989cc2)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff8198b952)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9ff6)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_del
```
```
In net/core/net_namespace.c (ffffffff819f8529)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81a037a0)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81a1026b)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_ref_unsync_dev
```
```
In net/core/rtnetlink.c (ffffffff81a18609)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81a35395)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff81a4139e)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_cleanup_ops
```
```
In net/core/drop_monitor.c (ffffffff81a49a9c)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff81a538fa)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/sched/cls_api.c (ffffffff81a6de9b)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81a765b3)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81acab09)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ace3c9)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81ae31f3)
Location: include/linux/rculist.h:156
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b03e59)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b2cb)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16c99)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81b2ab83)
Location: include/linux/rculist.h:156
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b394fa)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b7552f)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81b7dd7a)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81b91a12)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b925e2)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b9499d)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_condremove_iface
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba245e)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff81ba8712)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb375c)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bb5da9)
Location: include/linux/rculist.h:156
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81038c72)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff810657b7)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065923)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
```
In arch/x86/mm/kmmio.c (ffffffff81091dcc)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810a76bb)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
```
```
In kernel/workqueue.c (ffffffff810c7178)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810d9d7f)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/core.c:cpu_cgroup_css_released
```
```
In kernel/sched/fair.c (ffffffff810f4d0f)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff811183ef)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff81be331d)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/module.c (ffffffff811635c9)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8116cdd4)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
```
```
In kernel/auditfilter.c (ffffffff81188e10)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff8118eee9)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8118ff74)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff811938a0)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811b0443)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811da02a)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811de956)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811f2e94)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811f9120)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
```
```
In kernel/bpf/devmap.c (ffffffff8122db8b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8123ab14)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffffffff81281f29)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff812b4385)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks
```
```
In mm/zswap.c (ffffffff812cd76d)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/timerfd.c (ffffffff8137edc3)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
```
In fs/io-wq.c (ffffffff8139bbce)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_exit
```
```
In fs/ext4/mballoc.c (ffffffff8141a159)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff814abdc6)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff814db527)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff814dbb3c)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814dbe1c)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In security/selinux/ibpkey.c (ffffffff814eefb1)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
```
```
In security/apparmor/policy.c (ffffffff815195ec)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
```
In security/apparmor/policy_ns.c (ffffffff81525045)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff8152ebab)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8153048e)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-stat.c (ffffffff81572597)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/textsearch.c (ffffffff815f9932)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In lib/bug.c (ffffffff8160c990)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/logic_pio.c (ffffffff81611984)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In drivers/acpi/osl.c (ffffffff81c3b6e6)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e8f2)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff8172472f)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab516)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b25cb)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff817b6a8b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
```
```
In drivers/base/core.c (ffffffff817c7ee3)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff817e2bbc)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff8192fb67)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff81935e99)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff81938914)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81969d81)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff8198977f)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_delete
```
```
In drivers/edac/edac_mc.c (ffffffff8198c336)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
```
In drivers/edac/edac_device.c (ffffffff8198da32)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff8198f542)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca73e)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_del
```
```
In net/core/net_namespace.c (ffffffff819f7fab)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81a03d40)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81a10636)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_ref_unsync_dev
```
```
In net/core/rtnetlink.c (ffffffff81a186b9)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81a37715)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff81a43bc3)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_cleanup_ops
```
```
In net/core/drop_monitor.c (ffffffff81a4f26c)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff81a5a37a)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/sched/cls_api.c (ffffffff81a7686b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81a7f328)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad6a99)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ada3d9)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81af00d3)
Location: include/linux/rculist.h:164
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b11fce)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b19606)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81b24ee9)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81b39513)
Location: include/linux/rculist.h:164
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b481fa)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b842a4)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81b8c396)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba1712)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81ba2252)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba45dd)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_condremove_iface
```
```
In net/ncsi/ncsi-manage.c (ffffffff81bb1ceb)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb98e2)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_del_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc8bed)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bcaf59)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103a782)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065e87)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065ff3)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
```
In arch/x86/mm/kmmio.c (ffffffff810928dc)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810a874b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
```
```
In kernel/workqueue.c (ffffffff810c8916)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810db8ff)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/core.c:cpu_cgroup_css_released
```
```
In kernel/sched/fair.c (ffffffff810f6dff)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff81118a2f)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff81bd51ed)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/module.c (ffffffff81164191)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8116da34)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff8118a82f)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff8118fd19)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81190ea4)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81194873)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811b0d53)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db588)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811dfdf6)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811f3d14)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811f9f00)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
```
```
In kernel/bpf/devmap.c (ffffffff81232c4b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8123f2e4)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffffffff81286f03)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff812b9a65)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks
```
```
In mm/zswap.c (ffffffff812d4275)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/timerfd.c (ffffffff81385a43)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
```
In fs/io-wq.c (ffffffff813a3299)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/ext4/mballoc.c (ffffffff81420765)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff814b1c58)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff814e1ea7)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff814e24dc)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid_slow
```
```
In security/selinux/netport.c (ffffffff814e277c)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff814f5cd1)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff8151fef4)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
```
In security/apparmor/policy_ns.c (ffffffff8152b1f5)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff81534ebb)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8153668b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-stat.c (ffffffff8157a5b7)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/textsearch.c (ffffffff815dc682)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In lib/bug.c (ffffffff815efc30)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/logic_pio.c (ffffffff815f5064)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In drivers/acpi/osl.c (ffffffff81c2deb4)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff816eff12)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff817059ef)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e3a6)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179537b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81799d4b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
```
```
In drivers/base/core.c (ffffffff817ab3f3)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff817c6f7c)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81912ee7)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff81919e59)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff8191c183)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff8194e071)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff8196f374)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff819708d6)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
```
In drivers/edac/edac_device.c (ffffffff819720c2)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81973b52)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af746)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_del
```
```
In net/core/net_namespace.c (ffffffff819de44c)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff819eb190)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff819f74a6)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_ref_unsync_dev
```
```
In net/core/rtnetlink.c (ffffffff819ff589)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81a1e875)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff81a289e0)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffffffff81a342ac)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff81a3d3da)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/sched/cls_api.c (ffffffff81a5e76b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81a68308)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac1bd9)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ac54d9)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81adb813)
Location: include/linux/rculist.h:164
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81aff710)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07086)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81b12b09)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81b271e3)
Location: include/linux/rculist.h:164
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b35dfa)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b72f36)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81b7bad6)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81b9086e)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b91332)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b931ed)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba0d0b)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba88c2)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_del_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8f37)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bbe899)
Location: include/linux/rculist.h:164
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8104014b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8106ffa7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070113)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
```
In arch/x86/mm/kmmio.c (ffffffff810a2613)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810ba22b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
```
```
In kernel/workqueue.c (ffffffff810db533)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810ef88a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/core.c:cpu_cgroup_css_released
```
```
In kernel/sched/fair.c (ffffffff811110d3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff81139280)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff811599b5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff8118989f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81193311)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff811b33ae)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff811b8bf9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811b9d84)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff811bd76c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811dabd7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81208b98)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_eprobe.c (ffffffff812090d0)
Location: include/linux/rculist.h:155
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff8120f346)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff81225064)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff8122b5d0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
```
```
In kernel/bpf/devmap.c (ffffffff8126c12b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff81279e54)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffffffff812c64bf)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff812fc012)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks
```
```
In mm/zswap.c (ffffffff81319f80)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/timerfd.c (ffffffff813d213f)
Location: include/linux/rculist.h:155
Inline: True
```
```
In fs/io-wq.c (ffffffff813f27a9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/ext4/mballoc.c (ffffffff81473b1f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff8150a216)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff8153aea5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff8153b547)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8153b897)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff815506ea)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff8157e094)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
```
In security/apparmor/policy_ns.c (ffffffff81589595)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff8159390c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff81594dbb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-stat.c (ffffffff815df969)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/textsearch.c (ffffffff81647f52)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In lib/bug.c (ffffffff8165cd40)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/logic_pio.c (ffffffff81662484)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In drivers/acpi/osl.c (ffffffff81d4c7a3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176a002)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff817812bf)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/iommu/intel/dmar.c (ffffffff81815c36)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181d1eb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff818222bb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
```
```
In drivers/base/core.c (ffffffff81834750)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff8185135c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff819b4ee7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff819bc259)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff819be876)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff819f3471)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81a17c94)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff81a191f6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
```
In drivers/edac/edac_device.c (ffffffff81a1ad72)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c852)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5dc26)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_del
```
```
In net/core/net_namespace.c (ffffffff81a8e18c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81a9c15f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81aa9122)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
```
```
In net/core/rtnetlink.c (ffffffff81ab1859)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81ad2915)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff81add702)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffffffff81ae9dbc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff81af3a4a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/sched/cls_api.c (ffffffff81b17964)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81b21828)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81b7f8f9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81b83ce9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81b9aa53)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bc14a6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9f06)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd69b9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81becbd3)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bfc55a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d47f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81c467d6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5d00e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81c5dad2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f98d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6e60b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76612)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_del_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88607)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81c8e7f9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81047adb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8107d8dd)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107da54)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
```
In arch/x86/mm/kmmio.c (ffffffff810b6c08)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810d0ce3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
```
```
In kernel/workqueue.c (ffffffff810f4c86)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff8110cafa)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/core.c:cpu_cgroup_css_released
```
```
In kernel/sched/fair.c (ffffffff8112d2e8)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff8115bbaf)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff81e60b33)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/module/main.c (ffffffff8118f7db)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff811c45d5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff811e580a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff811ebb45)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811ecf8d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff811f0832)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81210b07)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812441d2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_eprobe.c (ffffffff81244eff)
Location: include/linux/rculist.h:155
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124c0f7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff81264f53)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff8126d030)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
```
```
In kernel/bpf/devmap.c (ffffffff812ba3db)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff812cd239)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:unaccount_event
```
```
In mm/backing-dev.c (ffffffff8132314f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff81361091)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffff81384fbc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/timerfd.c (ffffffff8145b408)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
```
In fs/proc/vmcore.c (ffffffff814afc99)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/proc/vmcore.c:unregister_vmcore_cb
```
```
In fs/ext4/mballoc.c (ffffffff814f530a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff8159bf7d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff815d260e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff815d2d27)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff815d30c7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff815e9b9b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff8161c806)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
```
In security/apparmor/policy_ns.c (ffffffff81629df5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff816350f1)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff81636f4b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-stat.c (ffffffff8168e0d7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In io_uring/io-wq.c (ffffffff816db303)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
```
```
In lib/textsearch.c (ffffffff8175df6a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In lib/bug.c (ffffffff817760e0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/logic_pio.c (ffffffff8177c1d4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In drivers/acpi/osl.c (ffffffff818230c1)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189eb8a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff818b7c2d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/iommu/intel/dmar.c (ffffffff81956ab1)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195df6a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81961cc2)
Location: include/linux/rculist.h:155
Inline: True
```
```
In drivers/base/core.c (ffffffff81976220)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff81996ebc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81b14277)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff81b1bf00)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff81b1d6c4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81b5f440)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81b7fa23)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_delete
```
```
In drivers/edac/edac_mc.c (ffffffff81b82145)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
```
In drivers/edac/edac_device.c (ffffffff81b837fa)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81b8593a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81bba494)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcdd92)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_del
```
```
In net/core/net_namespace.c (ffffffff81c040bc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81c15d6f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81c212d2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
```
```
In net/core/rtnetlink.c (ffffffff81c2aa19)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81c503f5)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/core/gro.c (ffffffff81c53440)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/gro.c:dev_remove_offload
```
```
In net/core/fib_rules.c (ffffffff81c5f093)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/core/devlink.c (ffffffff81c77c8a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/sched/cls_api.c (ffffffff81c9f7d9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81ca9ea0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0f829)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81d14399)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81d2cde3)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d569dd)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f654)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d289)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81d85093)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d95e89)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81ddbe06)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81de5194)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81dfee7e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81dffb92)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01207)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e1215b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1ae02)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_del_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2ed2c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mctp/route.c (ffffffff81e3b1cd)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
```
```
In net/mctp/neigh.c (ffffffff81e3b611)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81e3d8a6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8105259b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8108ee4d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108efe4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
```
In arch/x86/mm/kmmio.c (ffffffff810d24a5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810ef6c3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
```
```
In kernel/workqueue.c (ffffffff811170fe)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff811330da)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/core.c:cpu_cgroup_css_released
```
```
In kernel/sched/fair.c (ffffffff81157066)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff8118e5bf)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff811be2eb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/module/main.c (ffffffff811cc778)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff812069e4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff8122b89a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81231f55)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8123351d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81237608)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81259f97)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291e42)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_eprobe.c (ffffffff81292d7f)
Location: include/linux/rculist.h:155
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129a407)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff812b6b23)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff812c2170)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
```
```
In kernel/bpf/devmap.c (ffffffff8131d78b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff813352d9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:unaccount_event
```
```
In mm/backing-dev.c (ffffffff8139795f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff813dca85)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffff81402c84)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/timerfd.c (ffffffff814eaa18)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
```
In fs/proc/vmcore.c (ffffffff81546489)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/proc/vmcore.c:unregister_vmcore_cb
```
```
In fs/ext4/mballoc.c (ffffffff8158f5ea)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff8164537d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff8168050e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff81680cd7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816810c7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8169951b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff816cfaa6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
```
In security/apparmor/policy_ns.c (ffffffff816de625)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff816ebd31)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff816ee16b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-stat.c (ffffffff8174ca07)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In io_uring/io-wq.c (ffffffff817a73df)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
```
```
In lib/textsearch.c (ffffffff8188b60a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff820c42e2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7ea6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff81a04ead)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abd911)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac5a6a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca9fd)
Location: include/linux/rculist.h:155
Inline: True
```
```
In drivers/base/core.c (ffffffff81ae22f0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff81b07cec)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81ca52d7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff81cadd40)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff81caf6a4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81cfebe0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/md.c:md_kick_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81d1dcc3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_delete
```
```
In drivers/edac/edac_mc.c (ffffffff81d2097a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81d223d0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81d248d0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81d5f9d4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d78062)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_del
```
```
In net/core/net_namespace.c (ffffffff81db37cc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81dc70bf)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81dd33a2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
```
```
In net/core/rtnetlink.c (ffffffff81ddd779)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81e057c5)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/core/gro.c (ffffffff81e08acc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/gro.c:dev_remove_offload
```
```
In net/core/fib_rules.c (ffffffff81e15923)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/core/devlink.c (ffffffff81e30656)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/devlink.c:devl_dpipe_table_unregister
```
```
In net/sched/cls_api.c (ffffffff81e5ba59)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81e66f0e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5339)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81eda429)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81ef3cc1)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f212ad)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29d34)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38719)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81f522e1)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f64739)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81faf016)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81fb7944)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd3b1e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81fd4952)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6037)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fe8b8b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2332)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_del_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff820073ac)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mctp/route.c (ffffffff820147dd)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
```
```
In net/mctp/neigh.c (ffffffff82014ce1)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82016d96)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In lib/bug.c (ffffffff8201ea00)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/logic_pio.c (ffffffff82025474)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8105316b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091d3d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091ef5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
```
In arch/x86/mm/kmmio.c (ffffffff810d5915)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810fb667)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
```
```
In kernel/workqueue.c (ffffffff811240a9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff8114170a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/core.c:cpu_cgroup_css_released
```
```
In kernel/sched/fair.c (ffffffff8116711f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff8119ff1f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff811d0a80)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module/main.c (ffffffff811dfc5d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8121c5a4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff81241e7a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81248be5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8124a1c6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8124e6c8)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8127129b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
```
In kernel/trace/trace_osnoise.c (ffffffff812959af)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_unregister_instance
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812af0a2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_eprobe.c (ffffffff812affef)
Location: include/linux/rculist.h:155
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff812b7b77)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5eb3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
```
```
In kernel/trace/trace_probe.c (ffffffff812da013)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff812e9030)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
```
```
In kernel/bpf/devmap.c (ffffffff8134d58b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff81366019)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:unaccount_event
```
```
In mm/backing-dev.c (ffffffff813ca8ef)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff81413b76)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
```
```
In mm/zswap.c (ffffffff81436213)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/timerfd.c (ffffffff815217bb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
```
In fs/proc/vmcore.c (ffffffff8157e049)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/proc/vmcore.c:unregister_vmcore_cb
```
```
In fs/ext4/mballoc.c (ffffffff815c626a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff8167d872)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff816b85ee)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff816b8d87)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816b9177)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff816d19cb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff817086c6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
```
In security/apparmor/policy_ns.c (ffffffff81717c25)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff81726161)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff817285fb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-stat.c (ffffffff81789147)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In io_uring/io-wq.c (ffffffff817e8532)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker
```
```
In lib/textsearch.c (ffffffff818cdae6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff8199a5a0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30635)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff81a4dd0d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a281)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b124fa)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81b16f4e)
Location: include/linux/rculist.h:155
Inline: True
```
```
In drivers/base/core.c (ffffffff81b30210)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff81b55d4c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81d0ca17)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff81d15330)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff81d16ca4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81d61c01)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/md.c:md_kick_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81d86ea3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_delete
```
```
In drivers/edac/edac_mc.c (ffffffff81d89b7a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81d8b5c0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81d8dae0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81dcaad4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de5fb2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_del
```
```
In net/core/net_namespace.c (ffffffff81e23e7c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81e363ef)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81e43f6f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
```
```
In net/core/rtnetlink.c (ffffffff81e4e4c9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81e78015)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/core/gro.c (ffffffff81e7b3cc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/gro.c:dev_remove_offload
```
```
In net/core/fib_rules.c (ffffffff81e89233)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/sched/cls_api.c (ffffffff81eb8188)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81ec2cce)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81f347be)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81f39509)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81f535b1)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f8054c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f898e4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98109)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81fb1cf1)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fc482d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff8200ede7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff820180e4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/devlink/leftover.c (ffffffff82033446)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_dpipe_table_unregister
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8204f77e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff820505a2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82051cf7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff82064e0b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e562)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_del_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff8208374c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8208a992)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/mctp/route.c (ffffffff820915fd)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
```
```
In net/mctp/neigh.c (ffffffff82091b01)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82097146)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In lib/bug.c (ffffffff8209ea20)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/logic_pio.c (ffffffff820a5584)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8105a38b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8109911d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099265)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
```
In arch/x86/mm/kmmio.c (ffffffff810de115)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff81104a71)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
  - kernel/exit.c:__exit_signal
```
```
In kernel/workqueue.c (ffffffff8112e735)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_release_workfn
```
```
In kernel/sched/core.c (ffffffff8114ca8a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/core.c:cpu_cgroup_css_released
```
```
In kernel/sched/fair.c (ffffffff81173e9f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff811aef7f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff811e56d0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/dma/swiotlb.c (ffffffff811ed8a9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
```
```
In kernel/module/main.c (ffffffff811f598d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81234134)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
```
```
In kernel/auditfilter.c (ffffffff8125bc8a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81262ac5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff812640d6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff812685f8)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_aggr_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8128b71b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b100f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_unregister_instance
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb5c2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cc55f)
Location: include/linux/rculist.h:155
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d41c7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_events_user.c (ffffffff812e2717)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
```
```
In kernel/trace/trace_probe.c (ffffffff812f7fa3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff813073a0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
```
```
In kernel/bpf/devmap.c (ffffffff81374aab)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8138f139)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:unaccount_event
```
```
In mm/shrinker.c (ffffffff813e3e16)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_free
```
```
In mm/backing-dev.c (ffffffff813f535f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (ffffffff814405e6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
```
```
In mm/zswap.c (ffffffff8146fc51)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/timerfd.c (ffffffff81555dfb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
```
In fs/proc/vmcore.c (ffffffff815b6a89)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/proc/vmcore.c:unregister_vmcore_cb
```
```
In fs/ext4/mballoc.c (ffffffff816010c0)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff816b9c40)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff816f5021)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff816f5807)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816f5c27)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8170e02b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff81746156)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
```
In security/apparmor/policy_ns.c (ffffffff817565f5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff81767351)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8176992b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-stat.c (ffffffff817cb8aa)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In io_uring/io-wq.c (ffffffff8182e2d2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker
```
```
In lib/textsearch.c (ffffffff8191f546)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In lib/stackdepot.c (ffffffff819285bd)
Location: include/linux/rculist.h:155
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff819e2a20)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7bb45)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff81a999ad)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e2d1)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b66ada)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6d063)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid
```
```
In drivers/base/core.c (ffffffff81b87a10)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff81bae30c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81dc26a7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff81dcaf7f)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff81dcc954)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81e18c71)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/md.c:md_kick_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81e3e5b3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_delete
```
```
In drivers/edac/edac_mc.c (ffffffff81e412ca)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81e42e40)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81e45390)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81e83644)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c192)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_del
```
```
In net/core/net_namespace.c (ffffffff81ee1ddc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81ef46af)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81f02bbf)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
```
```
In net/core/rtnetlink.c (ffffffff81f0d229)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81f37fd5)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/core/gro.c (ffffffff81f3b65c)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/gro.c:dev_remove_offload
```
```
In net/core/fib_rules.c (ffffffff81f4b243)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/sched/cls_api.c (ffffffff81f7b1e5)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81f8601e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa93e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81fff5f9)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff82019941)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82046bcc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82051044)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff82065479)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff8207f411)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82091ddd)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff820ddd77)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff820e70b4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/devlink/dpipe.c (ffffffff8210a836)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devl_dpipe_table_unregister
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff82121e2e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff82122c52)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff821244d7)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff82137fab)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xsk_buff_pool.c (ffffffff821425e2)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_del_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff82158edc)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff82160562)
Location: include/linux/rculist.h:155
Inline: True
```
```
In net/mptcp/sched.c (ffffffff82161d42)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mptcp/sched.c:mptcp_unregister_scheduler
```
```
In net/mctp/route.c (ffffffff82167b9d)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
```
```
In net/mctp/neigh.c (ffffffff821680a1)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8216e626)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In lib/bug.c (ffffffff82176a20)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
```
In lib/logic_pio.c (ffffffff8217d6e4)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
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
In arch/arm64/kernel/debug-monitors.c (ffff800010086028)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:unregister_debug_hook
```
```
In virt/kvm/eventfd.c (ffff8000100c1000)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:irqfd_resampler_shutdown
```
```
In kernel/exit.c (ffff8000100fabf8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffff8000101226cc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffff80001013debc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffff80001014d264)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffff8000101730d4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/module.c (ffff8000101c4efc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffff8000101d14e8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffff8000101eea3c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffff8000101f3790)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffff8000101f4984)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffff8000101f72bc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffff800010215608)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242ce4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffff8000102440bc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffff800010257ed0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffff80001025e4b0)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (ffff800010286c80)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffff800010291c3c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:list_del_event
```
```
In mm/backing-dev.c (ffff8000102dec3c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffff800010310ed8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffff80001032bbc8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In fs/eventpoll.c (ffff8000103f0274)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffff8000103f464c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffff800010492498)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffff800010525960)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffff800010557da8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffff800010558720)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffff800010558b30)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffff800010558f20)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffff8000105962c0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffff8000105a1000)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffff8000105aa9a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffff8000105abc40)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffff8000105f36f8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffff8000105f5450)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (ffff80001063ecdc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (ffff80001065e774)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffff800010d9dbd4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffff8000107aef8c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffff8000107fc6fc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/core.c (ffff8000108e2ca4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffff8000109047f0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffff800010a9532c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffff800010a9c6a8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffff800010a9e348)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffff800010aea514)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffff800010b0e104)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffff800010b0f868)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffff800010b10e68)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffff800010b132e0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In net/core/net_namespace.c (ffff800010bc0e70)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffff800010bcb994)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffff800010bdeb40)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffff800010bea4a8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffff800010c05b68)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffff800010c13b68)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffff800010c1a8a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffff800010c248c8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (ffff800010c4a9bc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffff800010c90e90)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffff800010c94d90)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffff800010cabb74)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccc04c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5ac4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffff800010ce4014)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffff800010cf6394)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010d052a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffff800010d44c68)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffff800010d4e028)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffff800010d65470)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffff800010d66368)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d684cc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffff800010d792b8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffff800010d80d1c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffff800010d83a28)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0358ae0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (c0376080)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (c038ddcc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (c039aec4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (c03c50b4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/module.c (c040bf10)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (c041379c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (c042ea40)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (c0433c64)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (c0434b44)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (c0437d24)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (c0454374)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (c047e57c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_probe.c (c048b000)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (c0491c14)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (c04b6d4c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (c04c2bd0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (c0503bcc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (c052cc04)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (c0541c8c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In fs/eventpoll.c (c05c73ac)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (c05c9434)
Location: include/linux/rculist.h:146
Inline: True
```
```
In fs/ext4/mballoc.c (c0653838)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (c06dfe18)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (c070cca0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (c070d34c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c070d604)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (c070d8c8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (c07473a4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (c0751a38)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (c0759f30)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (c075b74c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (c079f830)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (c07a0f54)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (c07e43a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (c0807e48)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/dma/dmaengine.c (c091e610)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/core.c (c09d18c0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (c09edc3c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (c0b77f54)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (c0b7cf08)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_detach_client
```
```
In drivers/input/evdev.c (c0b7e7a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (c0bc9248)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (c0bec4d8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (c0bedb38)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (c0bef2ec)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (c0bf1294)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In net/core/net_namespace.c (c0cdc014)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (c0ce524c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (c0cf975c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (c0d02e3c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (c0d1ebb8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (c0d2b5f8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (c0d32c60)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (c0d3be30)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (c0d5b484)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (c0d9f80c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (c0da35c4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (c0db735c)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd7f1c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/cipso_ipv4.c (c0ddf958)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (c0deb9e8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (c0dfc734)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (c0e0c33c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (c0e47144)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (c0e4e284)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (c0e63f64)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (c0e64be0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66114)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (c0e74e54)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (c0e7b26c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (c0e7ed20)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a06f0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_put
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000dbac8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_unlink_table_and_group
```
```
In kernel/exit.c (c000000000142150)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (c00000000016c1a8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (c00000000018cec4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (c0000000001a0080)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (c0000000001cbabc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (c0000000001f1e94)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/module.c (c00000000022c8bc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (c00000000023c0ac)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (c000000000261924)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (c00000000026830c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (c000000000269a1c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (c00000000026e6dc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (c000000000296e94)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d5524)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (c0000000002d7288)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (c0000000002f9f84)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (c000000000303208)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (c00000000033222c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (c0000000003400c0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (c00000000039e558)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/vmalloc.c (c0000000003e1b5c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (c000000000403a14)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In fs/eventpoll.c (c0000000004f9998)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (c0000000004fc738)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (c0000000005ba984)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (c00000000066fe98)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (c0000000006b5db0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (c0000000006b6770)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c0000000006b6b50)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (c0000000006b6f20)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (c00000000070bd10)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (c00000000071b750)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (c000000000727cb0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (c000000000729db0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (c00000000078b00c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (c00000000078d01c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (c0000000007e83b0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (c000000000810d40)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/dma/dmaengine.c (c0000000008c7844)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/core.c (c000000000977944)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (c0000000009a20a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (c000000000b74414)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (c000000000b7d57c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (c000000000b7dd88)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_detach_client
```
```
In drivers/md/md.c (c000000000bd146c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (c000000000c00de8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (c000000000c02f0c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (c000000000c04c78)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (c000000000c07cb8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In net/core/net_namespace.c (c000000000c9b930)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (c000000000ca5c08)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (c000000000cbf4a4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (c000000000cccce4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (c000000000cefe50)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (c000000000d01028)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (c000000000d0c48c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (c000000000d180a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (c000000000d48928)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (c000000000d9fc14)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (c000000000da55b4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (c000000000dc0c04)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deb530)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (c000000000df52f8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (c000000000e05468)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (c000000000e1c2c4)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (c000000000e2f16c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (c000000000e79760)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (c000000000e83aa8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (c000000000ea1364)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (c000000000ea2450)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea3f84)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (c000000000eb8ae0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (c000000000ec09c4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (c000000000ec27b0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
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
In kernel/exit.c (ffffffe0000c49e8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffe0000db0fa)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffe0000ecc50)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffe0000f658e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffe00010e800)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/module.c (ffffffe000145858)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffe00014b390)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffe000162a84)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffe000166bbc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffe000167c08)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/trace/ftrace.c (ffffffe000175314)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffe00019779c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/bpf/core.c (ffffffe00019c8c4)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffe0001bbb32)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffe0001c446e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffe0001f6ada)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffe000218a60)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffe00022a7a8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffe0002a428e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffe0002a61a2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffe0003171e6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffe00038a276)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffe0003af6b8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffe0003afcc6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffe0003aff22)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffe0003b015e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffe0003e2b7e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__list_remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffe0003ebd2c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffe0003f3900)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffe0003f4626)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffe000431d12)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffffffe00043317c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (ffffffe00046bb7a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (ffffffe00048c136)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/dma/dmaengine.c (ffffffe000516786)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/core.c (ffffffe000578210)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/input/input.c (ffffffe0006a70b8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffe0006ace48)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffe0006adff6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffe0006dc116)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffe0006fb19c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffe0006fc956)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffe0006fde0e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffe0006ffd4c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In net/core/net_namespace.c (ffffffe00074dc9c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffe000757eb4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffe0007659c0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffe00076dc78)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffe0007842f0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffe00078f290)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffffffe000795148)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffe00079cd4a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (ffffffe0007b7d54)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0a24)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffe0007f40b6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffe00080574c)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe0008209a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000826708)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffe000830f0c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffe00084177e)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe00084f448)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffe00087f620)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffe0008874bc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffe0008991a8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffe000899e30)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b7e0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffe0008a8330)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad2be)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffe0008ae05c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036394)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a36c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff8109e7c5)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810be734)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810d856f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810e6e06)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff8110a6af)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff81125a8e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/module.c (ffffffff8114e316)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81158e43)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81171d5f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81176f31)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81178111)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8117accf)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff81194e17)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bb918)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bcb56)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811d0164)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811d5e39)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f7e11)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff812009b4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffff81241b72)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff8127217d)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffff812874a9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff8132c1ef)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff8132eea2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffff813b4096)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff814360f5)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff81461e35)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff814624bc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8146276c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81462a21)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff81498ae9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814a2975)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff814ab00b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff814ac38e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff814ec440)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffffffff814ed90f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (ffffffff8152ac74)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (ffffffff8154aedf)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81a691bb)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8161c7ff)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff816acb66)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b25fb)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816b7213)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff816be5c8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff816d901c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/nvme/host/core.c (ffffffff81747313)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
```
```
In drivers/input/input.c (ffffffff8180b2b7)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff818111e9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff818124ab)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff818396e3)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff8185bfb9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff8185d546)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8185ec82)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff81860b82)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818a4bb9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff818c5c3c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff818d0341)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff818dfa40)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff818e87e9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81901d65)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff8190d40a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffffffff81914b5c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff8191cb2b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (ffffffff8193d1e3)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff8197d899)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81980ce9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81994893)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b2288)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b92da)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff819c46f9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff819d4a03)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819e22b9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a52f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81a21882)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a35732)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a361a2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a3800a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a4594e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff81a4b7e5)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffff81a4c5d0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81025ce4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8107905c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff8108d1e9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810acf5e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810c6f7f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810d5fa6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff810fb58f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff811184ee)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/module.c (ffffffff811415c6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8114c153)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81164eff)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff8116a0d1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8116b2b1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8116de6f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff81187f27)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ae6f8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811af936)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811c2f34)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811c8bf9)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811eab61)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811f3704)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffff81234b62)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff812640ed)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffff81279309)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff8131d55f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff8131fae2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffff813a4b26)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff81426b75)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff81452865)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff81452eec)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8145319c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81453451)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff81489509)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81493395)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff8149ba2b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff8149cdae)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff814dc990)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffffffff814dde5f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (ffffffff8151af54)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (ffffffff8153b1bf)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81a25c7b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81610eef)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff8168a4c6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816902bb)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81694e53)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff81699878)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff816b363c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/nvme/host/core.c (ffffffff81728f3b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
```
```
In drivers/net/vxlan.c (ffffffff8176f1a2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:__vxlan_fdb_delete
  - drivers/net/vxlan.c:vxlan_fdb_update_existing
```
```
In drivers/input/input.c (ffffffff817d2a27)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff817d8929)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff817d9beb)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81800d53)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff81823589)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff81824b16)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81826252)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff81828152)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852f18)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
  - drivers/hv/channel_mgmt.c:hv_process_channel_removal
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81860379)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff8187fb7c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8188a2e1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81899880)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff818a2629)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff818bbb95)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff818c71ca)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffffffff818ce91c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff818d68db)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (ffffffff818f6ce3)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81937359)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff8193a7a9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff8194e353)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196e8b8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819760ca)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff819814e9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff819917c3)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8199f079)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff819d72ef)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff819de642)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819f2352)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f2dc2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4c2a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a0253e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff81a083d5)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffff81a09700)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810361f4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a31c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff8109e775)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810bdc94)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810d4d1f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810e31d6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff8110859f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff8112397e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/module.c (ffffffff8114c1c6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81156c13)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8116fb2f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff81174d01)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81175ee1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81178a9f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff81192be7)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b96e8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811ba926)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811cdf34)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811d3c09)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f5be1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811fe784)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffff8123f912)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff8126ff1d)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffff812852b9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff81329cbf)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff8132c972)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffff813b18f6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff81432295)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff8145ded5)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff8145e55c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8145e80c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8145eac1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff81494b89)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8149ea15)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff814a70ab)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff814a842e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff814e84d0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffffffff814e999f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (ffffffff81526d04)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (ffffffff81546c1f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81ad55cb)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81637a62)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff8164a79f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff816dad46)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e0b4b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816e56e3)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff816eca98)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff8170693c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff8184a437)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff81850369)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff8185162b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff81888d13)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff818ab5e9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff818acb76)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818ae2b2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff818b01b2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818f6219)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff81916c3c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81921341)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81930a70)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff81939819)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81952d95)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff8195e43a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffffffff81965b8c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff8196dcbb)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (ffffffff8198e373)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a35d9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_nat_helper_unregister
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_expectfn_unregister
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819ab502)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_destroy
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_flush
```
```
In net/ipv4/tcp_cong.c (ffffffff819e8069)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819eb4b9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff819ff133)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1cb28)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23d5a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f179)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f483)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a4cd39)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a84faf)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81a8c302)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa15e2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aa2052)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3eba)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ab17fe)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7695)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffff81ab89c0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810371f4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c5bc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
```
```
In kernel/exit.c (ffffffff810a6680)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c601b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
```
In kernel/sched/core.c (ffffffff810e014f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_offline_group
```
```
In kernel/sched/fair.c (ffffffff810eedb6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
```
```
In kernel/printk/printk.c (ffffffff8111393f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
```
```
In kernel/livepatch/patch.c (ffffffff8112ff9e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/module.c (ffffffff81158eac)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81162b33)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8117d32f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
```
```
In kernel/audit_watch.c (ffffffff811825e1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811837c9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8118636f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/ftrace.c (ffffffff811a0777)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c7788)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c89c6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
```
In kernel/trace/trace_probe.c (ffffffff811dc194)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/bpf/core.c (ffffffff811e1ef9)
Location: include/linux/rculist.h:146
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff812040b1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8120d7e4)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:_free_event
```
```
In mm/backing-dev.c (ffffffff8124f092)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/vmalloc.c (ffffffff8127f919)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
```
In mm/zswap.c (ffffffff8129540e)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In fs/eventpoll.c (ffffffff8133c6bd)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_remove
```
```
In fs/timerfd.c (ffffffff8133f6d0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_release
```
```
In fs/ext4/mballoc.c (ffffffff813c642c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In ipc/sem.c (ffffffff8144935f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
```
```
In security/selinux/netif.c (ffffffff81475675)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_destroy
```
```
In security/selinux/netnode.c (ffffffff81475d1c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81475fec)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff814762d1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/apparmor/policy.c (ffffffff814acba9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814b7045)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/yama/yama_lsm.c (ffffffff814bf7d0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/device_cgroup.c (ffffffff814c0dde)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
```
```
In block/blk-mq.c (ffffffff81501470)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-stat.c (ffffffff8150296f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_remove_callback
```
```
In lib/logic_pio.c (ffffffff81540684)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_unregister_range
```
```
In lib/textsearch.c (ffffffff815608b1)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
```
```
In drivers/acpi/osl.c (ffffffff81ae1a8b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651d92)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
```
```
In drivers/dma/dmaengine.c (ffffffff81664d3f)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/iommu/dmar.c (ffffffff816f52f6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fb15b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81700393)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/base/core.c (ffffffff817072d8)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_del
  - drivers/base/core.c:__device_link_del
```
```
In drivers/base/power/wakeup.c (ffffffff8172134c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_remove
```
```
In drivers/input/input.c (ffffffff81865607)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_unregister_handle
```
```
In drivers/input/mousedev.c (ffffffff8186b087)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
```
In drivers/input/evdev.c (ffffffff8186c449)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
```
In drivers/md/md.c (ffffffff818a6443)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
```
```
In drivers/md/dm-stats.c (ffffffff818c7829)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/edac/edac_mc.c (ffffffff818c8dc6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818ca542)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_del_device
```
```
In drivers/edac/edac_pci.c (ffffffff818cc442)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_del_device
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81917309)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
```
In net/core/net_namespace.c (ffffffff81937e4c)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8193ef11)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81952140)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_flush
```
```
In net/core/rtnetlink.c (ffffffff8195aef9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_unregister
```
```
In net/core/fib_notifier.c (ffffffff81974875)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
```
```
In net/core/fib_rules.c (ffffffff8198068a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/drop_monitor.c (ffffffff81987dcc)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
```
In net/core/devlink.c (ffffffff8199014b)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_unregister
```
```
In net/netlink/af_netlink.c (ffffffff819b0c1d)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1a39)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819f5339)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81a09213)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a27a60)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2f18a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3aac9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
```
```
In net/ipv6/af_inet6.c (ffffffff81a4af83)
Location: include/linux/rculist.h:146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a58ca9)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a918a6)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/calipso.c (ffffffff81a985b5)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81aad8a0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aae3c2)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_remove
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf76a)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-manage.c (ffffffff81abdbae)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
```
In net/xdp/xdp_umem.c (ffffffff81ac3ab5)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
```
In lib/bug.c (ffffffff81ac4df0)
Location: include/linux/rculist.h:146
Inline: True
Inline callers:
  - lib/bug.c:module_bug_cleanup
```
</details>
</li>
</ul>

## Differences
