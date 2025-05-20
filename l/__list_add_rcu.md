# Function: <code>__list_add_rcu</code>

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
In arch/x86/kernel/nmi.c (ffffffff810324fb)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8107352c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff8107f3c0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff81099bb6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
  - kernel/workqueue.c:__alloc_workqueue_key
```
```
In kernel/sched/core.c (ffffffff810b0440)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810b7b86)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810d65d9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/core.c (ffffffff8118bf94)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff81109234)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup.c (ffffffff811149b2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/cgroup.c:create_css
```
```
In kernel/auditfilter.c (ffffffff81125132)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81129e5b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8112b330)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8112ca11)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811663a0)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811689ae)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f5f1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/core.c (ffffffff81179b65)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
```
```
In mm/backing-dev.c (ffffffff811ae3f8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff811ccc3b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff811d841f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81256280)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/timerfd.c (ffffffff81258a46)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff812cea4c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In ipc/sem.c (ffffffff81327551)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/commoncap.c (ffffffff81f982ab)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81f986bf)
Location: include/linux/rculist.h:49
Inline: True
```
```
In security/selinux/netif.c (ffffffff8134cfc7)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8134d28d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8134d534)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/smack/smack_lsm.c (ffffffff813617f4)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8136291c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff81364b75)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_set_access
  - security/smack/smackfs.c:smk_set_access
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
```
```
In security/tomoyo/common.c (ffffffff8136aa5c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8136d55f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/gc.c (ffffffff8137037b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff81f98f5e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/tomoyo.c (ffffffff81f99133)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/policy.c (ffffffff8137f329)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/lsm.c (ffffffff81f99776)
Location: include/linux/rculist.h:49
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81394b13)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
```
```
In security/yama/yama_lsm.c (ffffffff81395039)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_add_hooks
```
```
In security/device_cgroup.c (ffffffff813957c6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff813971c2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In lib/bug.c (ffffffff813e8d19)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/genalloc.c (ffffffff8140762a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/textsearch.c (ffffffff8141188d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff8181adca)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b6277)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff814bdf2a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8152597f)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff81534152)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8153960b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8153c12c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff8155b92e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81666e41)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8166c951)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8166d733)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81690129)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff816ae53a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff816f6f1e)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8170f8d1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81fbae08)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81713589)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8172267c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/fib_rules.c (ffffffff81739825)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81743181)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8174a022)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff81751162)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hook
```
```
In net/ipv4/tcp_cong.c (ffffffff8178058d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/af_inet.c (ffffffff81792f05)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff817a9ffd)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817add2e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff817b70f0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff817c30ad)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/ip6mr.c (ffffffff817f8ff5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8180c5f5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8180d03f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180f125)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
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
In arch/x86/kernel/nmi.c (ffffffff81031634)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81074b0e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff81081576)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a0e17)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810b3040)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810bb5b4)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810db590)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/core.c (ffffffff810efc7d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff8110ff1a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup.c (ffffffff8111d31f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8112d1cf)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81132044)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81133537)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81134c15)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811712c7)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811727c3)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff8117603e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117ccce)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/core.c (ffffffff8119090a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:add_event_to_ctx
```
```
In mm/backing-dev.c (ffffffff811c7758)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff811eb673)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff811f6573)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8127eb96)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/timerfd.c (ffffffff812813d2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff81304159)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff8135dabe)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/commoncap.c (ffffffff81fc2f4b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81fc335a)
Location: include/linux/rculist.h:49
Inline: True
```
```
In security/selinux/netif.c (ffffffff81382f88)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81383269)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813834ff)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/smack/smack_lsm.c (ffffffff81397587)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81398aee)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8139bd32)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff813a0a21)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff813a40f6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff813a6757)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff813a76a8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/tomoyo/tomoyo.c (ffffffff81fc3e02)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/policy.c (ffffffff813b8e5c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/lsm.c (ffffffff81fc44eb)
Location: include/linux/rculist.h:49
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff813d018c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff813d0bb9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_add_hooks
```
```
In security/device_cgroup.c (ffffffff813d1506)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff813d321c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In lib/bug.c (ffffffff8142ef89)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/genalloc.c (ffffffff8144f48b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/textsearch.c (ffffffff814595fd)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81894f32)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505c4d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff8150dbf0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff815889e1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158e0e3)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81590c7e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff815adbae)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff816c70f1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff816cc821)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff816cd9c3)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff816f0e16)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff8170ea29)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8175bbb3)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff817771bd)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81fe89cc)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff8177b229)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8178c0cc)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/fib_rules.c (ffffffff817a69de)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/sched/sch_api.c (ffffffff817b0011)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b6f42)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff817bd191)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hook
```
```
In net/ipv4/tcp_cong.c (ffffffff817eda68)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/af_inet.c (ffffffff818006c6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81817533)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181ad1e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81824120)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81830128)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/ip6mr.c (ffffffff818687e3)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/ipv6/calipso.c (ffffffff8186f817)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8187e6ea)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8187f4fa)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818817c8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff8188df2d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff8188fcb6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
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
In arch/x86/kernel/nmi.c (ffffffff81031284)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8107868e)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff81085fbf)
Location: include/linux/rculist.h:48
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a5ee1)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810b9630)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810c1c74)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810e2060)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/core.c (ffffffff810f685d)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff811177d1)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup.c (ffffffff8112564f)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81136eea)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8113bda4)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8113d26c)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8113e995)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117ca37)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff8117dfc3)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff81181ace)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff811888de)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/core.c (ffffffff8119f7d8)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:add_event_to_ctx
```
```
In mm/backing-dev.c (ffffffff811d7878)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff811fc8e3)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81206f10)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81292726)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/timerfd.c (ffffffff81294efc)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff8131a118)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81374136)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/commoncap.c (ffffffff81fff997)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81fffda6)
Location: include/linux/rculist.h:48
Inline: True
```
```
In security/selinux/netif.c (ffffffff81399a08)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81399ce9)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81399f7f)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/smack/smack_lsm.c (ffffffff813ae189)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff813af6ce)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff813b2d62)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff813b75b1)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff813bac76)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff813bd2d7)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff813be22b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/tomoyo/tomoyo.c (ffffffff820007f6)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/policy.c (ffffffff813d021c)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/lsm.c (ffffffff82000f16)
Location: include/linux/rculist.h:48
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff813e7890)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff813e82b9)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_add_hooks
```
```
In security/device_cgroup.c (ffffffff813e8c36)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff813ea864)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff813ee670)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bug.c (ffffffff8144b0f9)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/genalloc.c (ffffffff8146de4b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/textsearch.c (ffffffff81477fbd)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff818c968b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529e4d)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81539d95)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff815b60a1)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bbbe3)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff815be50e)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff815c7fd4)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff815dc97e)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff816f50e1)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff816fa7c1)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff816fb963)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8172269b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff8173fb0c)
Location: include/linux/rculist.h:48
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81788123)
Location: include/linux/rculist.h:48
Inline: True
```
```
In net/core/net_namespace.c (ffffffff820271f2)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff817a8889)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff817b999c)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/fib_rules.c (ffffffff817d54e3)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/netlink/af_netlink.c (ffffffff817e69c2)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e3cf)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/af_inet.c (ffffffff81831616)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81848da3)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184c5de)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81855a70)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81861ba8)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/ip6mr.c (ffffffff8189b633)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/ipv6/calipso.c (ffffffff818a2787)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff818b2f9a)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff818b3daa)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b6078)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff818c2141)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff818c4296)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
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
In arch/x86/kernel/nmi.c (ffffffff8102f579)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81076fae)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff81082a04)
Location: include/linux/rculist.h:48
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a2f38)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810b424c)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810bc58b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810e1210)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff810f8a36)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81118d96)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81127d17)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff811381cf)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8113d3cf)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8113e89b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81141c34)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117f6a6)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff81180b5e)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff8118487e)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b530)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/core.c (ffffffff8118f13d)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/events/core.c (ffffffff811a435c)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:add_event_to_ctx
```
```
In mm/backing-dev.c (ffffffff811e1bbd)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8120755b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81213132)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8129f797)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/timerfd.c (ffffffff812a214b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff813114af)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81387a9c)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/security.c (ffffffff820e2f9d)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/netif.c (ffffffff813afe0c)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff813b0177)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813b044e)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff813b06bc)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff813c30b5)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff813c627e)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff813c9719)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff813cdec1)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff813d1532)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff813d3c3f)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff813d4aae)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff813e39b9)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813ec126)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff813f47d8)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff813f5009)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff813f6bb6)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff813faaed)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-mq.c (ffffffff81432f1c)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814343b2)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/genalloc.c (ffffffff8147351b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/textsearch.c (ffffffff814812fd)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81900bea)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153d279)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff8154d5e1)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff815cbece)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d1812)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff815d40d0)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff815dcc69)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff815f14fb)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8170abbd)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81710251)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff817113d9)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8173eddd)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff817598fc)
Location: include/linux/rculist.h:48
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8175be28)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8175dfe6)
Location: include/linux/rculist.h:48
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff8175fb07)
Location: include/linux/rculist.h:48
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff817a722e)
Location: include/linux/rculist.h:48
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8210a789)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff817c6ed9)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff817d84ea)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/fib_rules.c (ffffffff817f47ea)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/netlink/af_netlink.c (ffffffff818067c2)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff8183eb1f)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81841e6b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81852bc4)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff8186c32f)
Location: include/linux/rculist.h:48
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8186ffec)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81879600)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff818862c6)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/ip6mr.c (ffffffff818c13e9)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/ipv6/calipso.c (ffffffff818c8d17)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff818d994c)
Location: include/linux/rculist.h:48
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff818da742)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dca07)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff818e8ac8)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff818eabdc)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In lib/bug.c (ffffffff818eb38b)
Location: include/linux/rculist.h:48
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff81031579)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8107d2f6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff81089834)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a9868)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810bb4fc)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810c43fb)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810e94c0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff81102c69)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81124342)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81134255)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81144ed9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8114a19d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8114b6a8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8114e9e4)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811678ba)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8118cfa9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff8118e491)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/trace/trace_kprobe.c (ffffffff8119254e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198ff1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/core.c (ffffffff8119d5ad)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811af577)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/events/core.c (ffffffff811b8fc5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff811f7c56)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8122064b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8122dc8e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In mm/hmm.c (ffffffff8126d42e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_fault
```
```
In fs/eventpoll.c (ffffffff812c2c0c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/timerfd.c (ffffffff812c5471)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff8133304e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff813ac307)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/security.c (ffffffff826ebc56)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/selinux/netif.c (ffffffff813d5ebc)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff813d6217)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813d64ee)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff813d675c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff813e9375)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff813ec56e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff813efba9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff813f4361)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff813f79f2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff813fa154)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff813fafbe)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff8140a7af)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81413abc)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8141c888)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff8141d1c9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8141ecd6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81422f8d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-mq.c (ffffffff8145ead6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff8146003e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff8149b5d0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff814a08ab)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/textsearch.c (ffffffff814bd14d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff8198abea)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159fe45)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff815b0bcf)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff81632c9e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816385e2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8163ae36)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff81643c69)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff81658ae7)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8177bd7d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff817814d1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81782659)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff817b0dad)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff817cbb3d)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff817ce078)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff817d0056)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff817d1b95)
Location: include/linux/rculist.h:49
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181e48e)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8271412b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81840aa9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81852bea)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff8185a110)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff8186a6ee)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8186ff7b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/netlink/af_netlink.c (ffffffff81885492)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff818be36f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff818c173b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff818d29d4)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff818ecbf8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f099c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa050)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff819074d6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81911882)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81944615)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/ipv6/calipso.c (ffffffff8194c3b7)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8195f53c)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81960322)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819625f7)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff8196dfca)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff8196ee38)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In lib/bug.c (ffffffff819712cb)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff810324c9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81080226)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff8108d1ec)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/workqueue.c (ffffffff810aff97)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810c29ac)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810cbdf2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810f1790)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff8110b241)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81132866)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8114287c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff811532b2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81158c3a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8115a7ce)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8115d2b5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811765ba)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119bae9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811a2159)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6af3)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae6b0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/core.c (ffffffff811b1ce9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811c9db5)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/events/core.c (ffffffff811d92ee)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff81218f7d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8124243b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff812500af)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In mm/hmm.c (ffffffff812939a1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_fault
  - mm/hmm.c:hmm_vma_get_pfns
```
```
In fs/eventpoll.c (ffffffff812ebad1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffff812ee86d)
Location: include/linux/rculist.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81364424)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff813dc532)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/selinux/netif.c (ffffffff814064d3)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8140682a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81406b09)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81406d85)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff8141a2a6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8141d39e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff81420413)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff814252f0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff814289c1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff8142b049)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff8142bf30)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff8143bfc9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81445ecf)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8144ec29)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff8144f489)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff81450f76)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff8145556f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81457b5b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff8149241f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff8149390e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff814d0880)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff814d5a32)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/textsearch.c (ffffffff814ef958)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff819e7516)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d7a64)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff815e9028)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff8166df06)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816738eb)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8167641b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff8167f094)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff8169464e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff817bce2d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff817c26ed)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff817c38a4)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff817f5047)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff81814913)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81816e68)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81818d16)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff8181a925)
Location: include/linux/rculist.h:49
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8186879e)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81887796)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81890e69)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8189e2fa)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff818a5990)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff818ba481)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff818c1542)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/netlink/af_netlink.c (ffffffff818d8e51)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81913f8d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81917350)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81928fa2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff819429d3)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819472f2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81950c90)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff8195e0ba)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81968ca8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff8199f255)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff819a65e7)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819b8ca1)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819b9af2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bbe85)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff819c7b47)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff819c8513)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff819ccd09)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff819cd694)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff81033789)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81086d66)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff81094f20)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/workqueue.c (ffffffff810b9107)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810cbcac)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810d429e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810fce40)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff81116a31)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff8113e19c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8114e31d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8115ff66)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81165bfe)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811674a2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8116a0c5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811841fc)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a9c49)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b0f93)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b4f53)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcd20)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/core.c (ffffffff811c0599)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811dd6b5)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/events/core.c (ffffffff811e9630)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff8122beac)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81256b68)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8126457f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In mm/hmm.c (ffffffff812a8671)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_fault
  - mm/hmm.c:hmm_vma_get_pfns
```
```
In fs/eventpoll.c (ffffffff812ffd11)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffff813031fd)
Location: include/linux/rculist.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8137c6c7)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff813f6b6a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/selinux/netif.c (ffffffff81422026)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81422391)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81422670)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff814228f5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81436a23)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8143998e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8143cee3)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff81441960)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81445287)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff81447a00)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff81448862)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff81458e39)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81462def)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8146bbf9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff8146c469)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8146df56)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff8147294f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8147504d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814abf5c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814adc1e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff814e51b0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff814ea0bd)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/textsearch.c (ffffffff81503878)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81a22986)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f12d5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81602e23)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff8168c336)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81691ebb)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81695152)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff8169f4d4)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b4cce)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff817e426d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff817ea1fd)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff817eaf14)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81821257)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff81840929)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81842739)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818445b6)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff81846115)
Location: include/linux/rculist.h:49
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8188882e)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818a8036)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818b1449)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff818c0b1a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff818c8f20)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff818e1301)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff818ea353)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/netlink/af_netlink.c (ffffffff81905641)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff819426ed)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81945b60)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81958292)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81972a9f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81978ec2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819841c0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81992c1a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8199e5c8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff819d5d7c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff819dd147)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819eff71)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f0dc2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f30e9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff819ff697)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a00443)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff81a05e29)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81a069f4)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff8103594c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a944)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff81099587)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810bec54)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810d3d50)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810ddf0b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81105530)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff81120c39)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81149c8e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81157aa5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8116cbd8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff811726da)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81174208)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81176c45)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff81190f9c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b7bc8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bf4a5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811cba41)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811d109c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811f2d6f)
Location: include/linux/rculist.h:49
Inline: True
```
```
In kernel/events/core.c (ffffffff81202a58)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff8123bb4e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8126adba)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8127f4f1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81320d36)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffff81324441)
Location: include/linux/rculist.h:49
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a2f51)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81422205)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff8144fc1e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8144ffa2)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81450293)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81450598)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff814646db)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8146758f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8146aa3a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff8146f530)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81472f04)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff814756ae)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff814764b0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff814865b9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8149000e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff81498bd9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff81499b49)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149b626)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814a0648)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a2d1e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814da1cc)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814dbea9)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff81511bbc)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff81516d78)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff815319ca)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81a92a33)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff816230e8)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81635561)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816c3f05)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c9e4b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816cdf10)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff816d7b67)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816eeb9d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81824c9d)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8182a7f0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8182ba6e)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8186363f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff8188375a)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8188558b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81887075)
Location: include/linux/rculist.h:49
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff81888ee4)
Location: include/linux/rculist.h:49
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818d314e)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818f3031)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818fe1f5)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8190d22a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff81915ef0)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff8192fafa)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81939dbd)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81947503)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (ffffffff819667ef)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6cdd)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819aa15b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff819bcdb6)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff819dc530)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e29e1)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819edd30)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff819fe67a)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a0a671)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a44dce)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a4bd5b)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5f158)
Location: include/linux/rculist.h:49
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a60088)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62459)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a6e98c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a6f695)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff81a7559c)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81a7634f)
Location: include/linux/rculist.h:49
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff8103605c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b5b4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff8109fb81)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810c5254)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810de26c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810e85e8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff811118b0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff8112d309)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81155900)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81163715)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81178a8c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8117e58a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81180078)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81182b75)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff8119cf9c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c323c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cacf5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811d7a92)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811dd62c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811ffb31)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (ffffffff8120f955)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff8124a00c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81279cd3)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8128ef51)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81333ad6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffff813371a1)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813bbdb1)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff8143bfc5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff81469a94)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81469dea)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8146a0d5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8146a378)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff8147e4ab)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8148136f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8148481a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff81489330)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8148cca4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff8148f44e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff81490250)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff814a0469)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814a9ece)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff814b2b09)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff814b3d49)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff814b5866)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814bacc4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814bd9ee)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814f357d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814f52d9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff815325fc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff815377b8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff8155285a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81aca1f3)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644bb8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff8165727d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816e6e55)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ece1b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816f1d60)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff816fbc4c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff81712c29)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8185611d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8185c180)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8185d3e2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8189538f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff818b5677)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b752b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818b9035)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff818bae94)
Location: include/linux/rculist.h:67
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff819054ce)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81924f97)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81930525)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8193f92a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff81948500)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81961d6d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8196cc7d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff81974c14)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff8197c64f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (ffffffff8199d2cf)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff819dd9ad)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819e0e1b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff819f39c6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81a13520)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a199d1)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a24be0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81a3526a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a41324)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b9be)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a8292b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a95d88)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a96cb8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a99039)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81aa535c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81aa5ef5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff81aac3e7)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81aad74f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff8103806b)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81092a72)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
```
```
In kernel/fork.c (ffffffff810a6c18)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810ccbda)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff810e683c)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810f2541)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff8111cf50)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff8113b959)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff81162894)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/module.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff811749a4)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff8118aaae)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff811919db)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81193086)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff811963d7)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811b2fac)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:register_ftrace_direct
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dce2e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e6aea)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f4432)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811f9f67)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff81226c02)
Location: include/linux/rculist.h:77
Inline: True
```
```
In kernel/events/core.c (ffffffff8123a053)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff812781c1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff812aa3b4)
Location: include/linux/rculist.h:77
Inline: True
```
```
In mm/zswap.c (ffffffff812c1c06)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8136dfe6)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffff813710c0)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/io-wq.c (ffffffff8138a884)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
```
```
In fs/ext4/mballoc.c (ffffffff8140729a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff8148c6f5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff814bdc2d)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814be013)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814be2a0)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In security/selinux/ibpkey.c (ffffffff814d1925)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
```
```
In security/smack/smack_lsm.c (ffffffff814d3748)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff814d72df)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff814d7c41)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff814e09e0)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff814e3f33)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff814e6741)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff814e75ad)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff814fa30e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81507950)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff81511df8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff815132d9)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff81514f06)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff8151aae1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:restore_template_fmt
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8151e2df)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff81553ad0)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff81555cde)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/genalloc.c (ffffffff8159b8b8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff815dbc3a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/bug.c (ffffffff815e779f)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/logic_pio.c (ffffffff815ed11e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81bc2843)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1dbc)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81708467)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179d6fa)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a5117)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff817aa3ab)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/core.c (ffffffff817b543d)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff817ce529)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff819284ad)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8192eaa0)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff819315b1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8196967f)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff819863a4)
Location: include/linux/rculist.h:77
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81987f3f)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:add_mc_to_global_list
```
```
In drivers/edac/edac_device.c (ffffffff819895b1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:add_edac_dev_to_global_list
```
```
In drivers/edac/edac_pci.c (ffffffff8198b571)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:add_edac_pci_to_global_list
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb718)
Location: include/linux/rculist.h:77
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f9582)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff819ffa37)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81a0f32a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff81a18340)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81a3536e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81a40fca)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff81a49b24)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff81a544d8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81a6c49e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/netlink/af_netlink.c (ffffffff81a7650f)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81acaa85)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ace45b)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81ae1c86)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81b03992)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b01e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16810)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a21a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b36d4a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b7679e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81b7dc0b)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81b91508)
Location: include/linux/rculist.h:77
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b92488)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b94ce0)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81ba0e2c)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba1cf3)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff81ba86b4)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3b23)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bb59de)
Location: include/linux/rculist.h:77
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff81038bab)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065a24)
Location: include/linux/rculist.h:85
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81092102)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
```
```
In kernel/fork.c (ffffffff810a2735)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810c7d5a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff810e473c)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810f06e9)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81117a20)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff811360f9)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff8115e909)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/module.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8117168f)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff81187d0e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff8118eb8b)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811901f6)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff81193167)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811b0b0c)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9f5e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e44aa)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f2de2)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811f8f97)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8122d6f3)
Location: include/linux/rculist.h:85
Inline: True
```
```
In kernel/events/core.c (ffffffff812436eb)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff81282952)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff812b5a5e)
Location: include/linux/rculist.h:85
Inline: True
```
```
In mm/zswap.c (ffffffff812cd7e6)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8137ee44)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/io-wq.c (ffffffff8139b5c9)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
```
```
In fs/ext4/mballoc.c (ffffffff8141a4ea)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff814a9d21)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff814db68d)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814dba34)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814dbcc0)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In security/selinux/ibpkey.c (ffffffff814eee37)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
```
```
In security/smack/smack_lsm.c (ffffffff814f0908)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff814f478f)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff814f51b1)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff814fde10)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81501363)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff81503b41)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff8150497d)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff8151708e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff815249f0)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8152ec88)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff81530429)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff81531f76)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81537a41)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:restore_template_fmt
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8153b0af)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8157252e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/genalloc.c (ffffffff815b7154)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff815f988a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/bug.c (ffffffff8160c95f)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/logic_pio.c (ffffffff816118de)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81c3b89b)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f17c)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81725687)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab41a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b2567)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff817b6836)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/core.c (ffffffff817c9bcf)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff817e2b69)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8192f9dd)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81935e40)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81938872)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff819701a3)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff8198a3de)
Location: include/linux/rculist.h:85
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198be6f)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:add_mc_to_global_list
```
```
In drivers/edac/edac_device.c (ffffffff8198d321)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:add_edac_dev_to_global_list
```
```
In drivers/edac/edac_pci.c (ffffffff8198f161)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:add_edac_pci_to_global_list
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2eba9)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/net_namespace.c (ffffffff819f93a2)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff819ff797)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81a0f6ba)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff81a18410)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81a376f6)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81a4383e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff81a4f2f4)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff81a5b438)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81a74e3e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/netlink/af_netlink.c (ffffffff81a7f284)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad6a1a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ada46b)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81aeeb06)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81b11b07)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b193fe)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b249c0)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81b38b7a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b45a7a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b85563)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81b8cd34)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba121d)
Location: include/linux/rculist.h:85
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81ba20f8)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4944)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81bb0740)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81bb1583)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb987e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc8497)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bcab8e)
Location: include/linux/rculist.h:85
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff8103a6bb)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8106639d)
Location: include/linux/rculist.h:85
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81092ae8)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff810a341e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810c97ea)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff810e66dc)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810ecf7b)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81118100)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff81136ef9)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff8115f959)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/module.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff811722bd)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff81188d6e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff8118f9b7)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81191522)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff8119419c)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811b14c0)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db4be)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e5a8a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f3c62)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811f9d77)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8123280a)
Location: include/linux/rculist.h:85
Inline: True
```
```
In kernel/events/core.c (ffffffff812486af)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff81287a77)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff812bb14e)
Location: include/linux/rculist.h:85
Inline: True
```
```
In mm/zswap.c (ffffffff812d42f2)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff81385ac4)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/io-wq.c (ffffffff813a2842)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
```
```
In fs/ext4/mballoc.c (ffffffff8141e468)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff814b0001)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff814e200d)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814e239d)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid_slow
```
```
In security/selinux/netport.c (ffffffff814e26bc)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff814f5bf7)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff814f7888)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff814fb6fe)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff814fe6cf)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff815049d0)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81507e44)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff8150a6b7)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff8150b4fd)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff8151d93a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8152ab2c)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff81535429)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff81536629)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8153a346)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff815407c7)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81543784)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8157a54e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/genalloc.c (ffffffff815c1fc4)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff815dc47a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/bug.c (ffffffff815efbf1)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/logic_pio.c (ffffffff815f4fbe)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81c2e05b)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0a5c)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81706927)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e1b9)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179551b)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81799ae7)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/core.c (ffffffff817ad3c8)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff817c6f29)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81912d5d)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81919e00)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8191c0e1)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81954124)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff8196e990)
Location: include/linux/rculist.h:85
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8197068e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81971c15)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff819737d4)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c20df7)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/net_namespace.c (ffffffff819dea15)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff819e5f77)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff819f652a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff819ff2e0)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81a1e856)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81a285b0)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff81a34334)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff81a3db18)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81a5d98e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/netlink/af_netlink.c (ffffffff81a68264)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac1a9e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ac547b)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81ada236)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81b003b6)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06e7e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b125e0)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81b2686a)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b3386f)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b740d9)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81b7bbe4)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81b9038b)
Location: include/linux/rculist.h:85
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b911d8)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b935cf)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81b9f840)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba05b3)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba885e)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8659)
Location: include/linux/rculist.h:85
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bbe4ce)
Location: include/linux/rculist.h:85
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff81040072)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810704bd)
Location: include/linux/rculist.h:76
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff810a2854)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff810b4bac)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810dc57e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff810fdc3c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff81105c2b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81138bea)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff81159be3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff81184d19)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/module.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81198dad)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff811b1315)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff811b8897)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811ba3e2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff811bd033)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811db350)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81208ace)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_eprobe.c (ffffffff8120a21f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff8121688c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff81224fb2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff8122b447)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8126bb5c)
Location: include/linux/rculist.h:76
Inline: True
```
```
In kernel/events/core.c (ffffffff81282d26)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff812c7219)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff812fd758)
Location: include/linux/rculist.h:76
Inline: True
```
```
In mm/zswap.c (ffffffff81319ffd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff813d2c07)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/io-wq.c (ffffffff813f1252)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/io-wq.c:io_init_new_worker
```
```
In fs/ext4/mballoc.c (ffffffff81471a95)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81508b00)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff8153b00d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff8153b424)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8153b7ad)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff815505e9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81552428)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8155636e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff815594dd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff81561829)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81565051)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff81567d56)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff81568d59)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff8157ba2a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81588ecc)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff815939f8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff81594d59)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff81598cc6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff8159fff8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff815a3ee2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff815df8f4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/genalloc.c (ffffffff81629e3d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff81647d4a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/bug.c (ffffffff8165cd01)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/logic_pio.c (ffffffff816623de)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81d4c97a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176ab6c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff817821e7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff81815a49)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181d38b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff818217ff)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/core.c (ffffffff818366b8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff81851309)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff819b4d7d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff819bc200)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff819be7ca)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff819f96f4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff81a1722f)
Location: include/linux/rculist.h:76
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81a18fae)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81a1a8c5)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c4d4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d3280c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/net_namespace.c (ffffffff81a8e817)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81a96496)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81aa8141)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81ab14d0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81ad28f6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81add350)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff81ae9e44)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff81af3f78)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81b16b1e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/netlink/af_netlink.c (ffffffff81b21784)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81b7f7ce)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81b83c8b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81b99400)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81bc24a6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9cee)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd64b0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81bec2ec)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81bf9edf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e988)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81c468e4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5cb2b)
Location: include/linux/rculist.h:76
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81c5d978)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5fd6f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81c6d0a0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6df56)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c765ae)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88409)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81c8e40e)
Location: include/linux/rculist.h:76
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff81047793)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e6ae)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/mm/kmmio.c (ffffffff810b6e8b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff810cb081)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810f5cb4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff8111a67a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff811206e8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff8115b605)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff81183207)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module/main.c (ffffffff8118dbea)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/module/main.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff811c8f38)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff811e35df)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff811eb7bd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811ed76f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff811f0d38)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff812113b1)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8124410c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_eprobe.c (ffffffff8124616a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff81254ea7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
```
In kernel/trace/trace_probe.c (ffffffff81264e82)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff8126ce97)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff812ba95e)
Location: include/linux/rculist.h:76
Inline: True
```
```
In kernel/events/core.c (ffffffff812ce93b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff8132449b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff813646a1)
Location: include/linux/rculist.h:76
Inline: True
```
```
In mm/zswap.c (ffffffff81385018)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8145b488)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff814f2ed0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81599705)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff815d278d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff815d2bda)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff815d2fb6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff815e9a90)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff815ebe88)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff815f071e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff815f3a36)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff815fc84d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8160083b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff81603743)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff81604a99)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff8161a006)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81629758)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff816351ed)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff81636ed7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8163d6e8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81645c16)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_buf
  - security/integrity/ima/ima_template.c:ima_template_desc_current
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8164a8fe)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8168e047)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In io_uring/io-wq.c (ffffffff816d9645)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
```
```
In lib/genalloc.c (ffffffff816fb10d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff8175e029)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/bug.c (ffffffff8177608f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/logic_pio.c (ffffffff8177c11e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81f1c4bf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189f734)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff818b8bba)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff819568ac)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195e108)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81961a96)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff819786c1)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff81996e3d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81b140fc)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81b1be9d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81b1d60a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81b60c4c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff81b7ff26)
Location: include/linux/rculist.h:76
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81d79)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81b83665)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81b85594)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81bba559)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81efecf1)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/net_namespace.c (ffffffff81c0472b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81c0d337)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81c200e0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81c2a670)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81c5036c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/gro.c (ffffffff81c53315)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/gro.c:dev_add_offload
```
```
In net/core/fib_rules.c (ffffffff81c5ec44)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81c78221)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81c9e250)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/netlink/af_netlink.c (ffffffff81ca9dea)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0f9ed)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81d1443b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81d2b240)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81d57252)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f3a7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6cc60)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81d8484c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81d932d4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd0f3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81de5372)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81dfe930)
Location: include/linux/rculist.h:76
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81dffa08)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e02122)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81e10aaf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e14134)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1ad7e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f539)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff81e3536c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/route.c (ffffffff81e39af2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff81e3b978)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81e3d525)
Location: include/linux/rculist.h:76
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff810521c3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fbde)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/mm/kmmio.c (ffffffff810d2210)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff810e862d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff811181ff)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff81141f2a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff81153230)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff8118db85)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff811be287)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module/main.c (ffffffff811ca727)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/module/main.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8120bfcd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff812299ff)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff81231bbd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81233d3f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff812370a6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff8125a921)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291d6c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_eprobe.c (ffffffff812930d1)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a433d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
```
In kernel/trace/trace_probe.c (ffffffff812b6a32)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff812c1fc7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8131daeb)
Location: include/linux/rculist.h:76
Inline: True
```
```
In kernel/events/core.c (ffffffff81336a44)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff81398dcb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff813e01f2)
Location: include/linux/rculist.h:76
Inline: True
```
```
In mm/zswap.c (ffffffff81402ce0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff814eaa98)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff8158b20d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81642985)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff816806ce)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff81680b7a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81680fa4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81699400)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff8169bae8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff816a0b1e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff816a43b6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff816ad5cd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff816b177b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff816b4903)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff816b5d99)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/audit.c (ffffffff816c1e43)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
```
```
In security/apparmor/policy.c (ffffffff816cd2e6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff816dde48)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff816ebe3d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff816ee0e7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff816f5218)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff816fe0f8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81703a4e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8174c965)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In io_uring/io-wq.c (ffffffff817a54f5)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
```
```
In lib/genalloc.c (ffffffff817edc8d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff8188b6d9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff820c44ef)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8aea)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81a06115)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abd6ec)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac5c28)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca56c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff81ae4f7b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff81b07c5d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81ca512c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81cadcdd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81caf5ea)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81cfaef3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff81d1d63e)
Location: include/linux/rculist.h:76
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81d204cd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81d22165)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81d245f4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81d5fa99)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d7876a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/net_namespace.c (ffffffff81db41fb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81dbcf57)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81dd2050)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81ddd3e0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81e0571c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/gro.c (ffffffff81e08945)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/gro.c:dev_add_offload
```
```
In net/core/fib_rules.c (ffffffff81e154c4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81e30ca4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/devlink.c:devl_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81e5a980)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/netlink/af_netlink.c (ffffffff81e66e1a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed562a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81eda4db)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81ef2e30)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81f208ef)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29a47)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38030)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81f52180)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81f61a64)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81fae578)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81fb7b42)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd35a0)
Location: include/linux/rculist.h:76
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81fd4788)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6fe2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81fe726f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81feae74)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff229e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff82007c53)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8200e000)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/route.c (ffffffff82012bc2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff82014f4d)
Location: include/linux/rculist.h:76
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82016945)
Location: include/linux/rculist.h:76
Inline: True
```
```
In lib/bug.c (ffffffff8201e99f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/logic_pio.c (ffffffff8202539e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
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
In arch/x86/kernel/nmi.c (ffffffff81052f23)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092aee)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/mm/kmmio.c (ffffffff810d5680)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff810f428c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff81125434)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff8114dbfa)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff81162ae0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff8119f335)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff811d0cb7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module/main.c (ffffffff811df630)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff812215dd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff8123ffbf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff8124884d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8124aa2f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff8124e166)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff81271dc1)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296c35)
Location: include/linux/rculist.h:76
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aefcc)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b026c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff812c2200)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
```
In kernel/trace/trace_events_user.c (ffffffff812c6e71)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_event_mm_dup
  - kernel/trace/trace_events_user.c:current_user_event_mm
```
```
In kernel/trace/trace_probe.c (ffffffff812d9f22)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff812e8e87)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8134d8b9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_alloc
```
```
In kernel/events/core.c (ffffffff81367804)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff813cbd2b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff81414f9f)
Location: include/linux/rculist.h:76
Inline: True
```
```
In mm/zswap.c (ffffffff81436271)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8152183b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff815c6b21)
Location: include/linux/rculist.h:76
Inline: True
```
```
In ipc/sem.c (ffffffff8167af19)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff816b8797)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816b8beb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816b9061)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff816d18b6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff816d45c8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff816d945e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff816dd36c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff816e5fed)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff816ea185)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff816ed3f9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff816ee7a9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/audit.c (ffffffff816faa2d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
```
```
In security/apparmor/policy.c (ffffffff817059f7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81717448)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8172626d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff81728577)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8172f318)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81738118)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8173da7e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8178909b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In io_uring/io-wq.c (ffffffff817e64d3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
```
```
In lib/genalloc.c (ffffffff8182e09d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff818cdbb9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff821482cf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a313eb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81a4efd5)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a043)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b126c3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81b1717a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff81b3331d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff81b55cbd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81d0c85c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81d152cd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81d16bea)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81d61896)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff81d86833)
Location: include/linux/rculist.h:76
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81d896ad)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81d8b363)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81d8d804)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81dcaba0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de66aa)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/net_namespace.c (ffffffff81e248ab)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81e2d787)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81e42c20)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81e4e130)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81e77f6c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/gro.c (ffffffff81e7b245)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/gro.c:dev_add_offload
```
```
In net/core/fib_rules.c (ffffffff81e88dd4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/sched/cls_api.c (ffffffff81eb67c0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/netlink/af_netlink.c (ffffffff81ec2bda)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81f347a2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81f395bb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81f528e0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81f8110f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89606)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f97a20)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81fb1b90)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81fc1889)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff8200f9f8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff820182e2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/devlink/leftover.c (ffffffff82033714)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_dpipe_table_register
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8204f203)
Location: include/linux/rculist.h:76
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff820503d8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052cd2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff820634bf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff82067124)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e4ce)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff82083fd3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8208a8e4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/route.c (ffffffff8208f9bf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff82091d6d)
Location: include/linux/rculist.h:76
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82096cf5)
Location: include/linux/rculist.h:76
Inline: True
```
```
In lib/bug.c (ffffffff8209e9bf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/logic_pio.c (ffffffff820a54ae)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
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
In arch/x86/kernel/nmi.c (ffffffff8105a143)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099f2d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/mm/kmmio.c (ffffffff810dde50)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff810fd654)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff8112fbcf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff81159a0a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff8116f59d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff811ae515)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff811e5936)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/dma/swiotlb.c (ffffffff811ec778)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/module/main.c (ffffffff811f5360)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff812392d3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff81259e3f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff8126272c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8126493c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff81268096)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff8128c284)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2284)
Location: include/linux/rculist.h:76
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb4ec)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cc7dd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff812de937)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
```
In kernel/trace/trace_events_user.c (ffffffff812e2c9c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_create
  - kernel/trace/trace_events_user.c:user_event_mm_dup
  - kernel/trace/trace_events_user.c:current_user_event_mm
```
```
In kernel/trace/trace_probe.c (ffffffff812f7eb2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff813071f7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff81374dd9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_alloc
```
```
In kernel/events/core.c (ffffffff81394bb3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/shrinker.c (ffffffff813e3a7a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_register
```
```
In mm/backing-dev.c (ffffffff813f669b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff81441a6e)
Location: include/linux/rculist.h:76
Inline: True
```
```
In mm/zswap.c (ffffffff8146fcb3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff81555e7b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff81601288)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In ipc/sem.c (ffffffff816b72ce)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff816f51f4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816f566a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816f5b10)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8170df15)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81710a6e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81715ebe)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8171a5b4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff81722c9d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81726e95)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff8172a1c9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff8172b579)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/audit.c (ffffffff8173763d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
```
```
In security/apparmor/policy.c (ffffffff817432f7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81755fd8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8176748c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff817698a7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8176fca6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81778c37)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8177e8dd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff817cb801)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In io_uring/io-wq.c (ffffffff8182c293)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
```
```
In lib/genalloc.c (ffffffff8187fc5d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff8191f619)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/stackdepot.c (ffffffff81928bc9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In drivers/acpi/osl.c (ffffffff8222ac5e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7c85b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81a9ac75)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e093)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b66ca3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c6a5)
Location: include/linux/rculist.h:76
Inline: True
```
```
In drivers/base/core.c (ffffffff81b8ac5c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff81bae27d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81dc24ec)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81dcaf1c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81dcc89a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81e18a9a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff81e3df51)
Location: include/linux/rculist.h:76
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81e40ded)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81e42be3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81e450b4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81e83710)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c88a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/net_namespace.c (ffffffff81ee24fb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81eebabf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/dev_addr_lists.c (ffffffff81f01870)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81f0ce90)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81f37f2c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/gro.c (ffffffff81f3b4d5)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/gro.c:dev_add_offload
```
```
In net/core/fib_rules.c (ffffffff81f4ade4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/sched/cls_api.c (ffffffff81f7960d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/netlink/af_netlink.c (ffffffff81f85f2a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa922)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81fff6ab)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff82018bc0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff8204778f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050d66)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff82064d90)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff8207f2b0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8208ed9e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff820de988)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff820e72b2)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/devlink/dpipe.c (ffffffff8210aa07)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devl_dpipe_table_register
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff82121883)
Location: include/linux/rculist.h:76
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff82122a88)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82125513)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff821365ff)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff8213a396)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8214254e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff82159624)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff821604a9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mptcp/sched.c (ffffffff82161c98)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mptcp/sched.c:mptcp_register_scheduler
```
```
In net/mctp/route.c (ffffffff82165ece)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff8216833c)
Location: include/linux/rculist.h:76
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8216e165)
Location: include/linux/rculist.h:76
Inline: True
```
```
In lib/bug.c (ffffffff821769bf)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/logic_pio.c (ffffffff8217d60e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
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
In arch/arm64/kernel/debug-monitors.c (ffff800010086ae0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:register_kernel_break_hook
  - arch/arm64/kernel/debug-monitors.c:register_user_break_hook
  - arch/arm64/kernel/debug-monitors.c:register_kernel_step_hook
  - arch/arm64/kernel/debug-monitors.c:register_user_step_hook
```
```
In virt/kvm/eventfd.c (ffff8000100c1224)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In kernel/fork.c (ffff8000100f40e4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffff800010123734)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffff80001013dd44)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffff800010147608)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffff8000101731d8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/module.c (ffff8000101c4d04)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffff8000101d4eb0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffff8000101edbdc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffff8000101f341c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffff8000101f5320)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffff8000101f887c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffff800010215e54)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242c08)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffff80001024a140)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffff800010257e10)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffff80001025e234)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffff800010286bc8)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (ffff80001029776c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffff8000102de0a0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffff800010310e98)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffff80001032bc4c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffff8000103f187c)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/timerfd.c (ffff8000103f4f70)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (ffff800010492918)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffff800010523e40)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffff80001055813c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffff8000105585bc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffff8000105589dc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffff800010558df4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffff80001056f31c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffff800010572c90)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffff800010576e08)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffff80001057c508)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffff80001058018c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffff8000105830a4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffff80001058441c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffff800010596224)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffff8000105a08fc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffff8000105aaad8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffff8000105abbe0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffff8000105adcdc)
Location: include/linux/rculist.h:67
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffff8000105b313c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffff8000105b68cc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffff8000105f2d7c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffff8000105f53a4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffff80001063ec08)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffff800010644900)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffff80001065e68c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffff800010d9da18)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b0624)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffff8000107fd50c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/core.c (ffff8000108e6578)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffff800010904a70)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffff800010a9516c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffff800010a9c618)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffff800010a9e2e8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffff800010aea240)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffff800010b0d418)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (ffff800010b0f648)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffff800010b11158)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (ffff800010b134cc)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffff800010bc0a88)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffff800010bccaf0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffff800010bde998)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffff800010bea0bc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffff800010c05b28)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffff800010c13464)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffff800010c1a92c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffff800010c24230)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (ffff800010c4a910)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffff800010c90da0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffff800010c94cf0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffff800010cabcb4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffff800010ccdc38)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5784)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3f50)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffff800010cf64d0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffff800010d02e6c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffff800010d456dc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffff800010d4e1a8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffff800010d64c98)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffff800010d6617c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68924)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffff800010d77ad4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffff800010d7890c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffff800010d80c4c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffff800010d839f4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In kernel/fork.c (c0352b88)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (c037701c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (c038dcc8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (c0395b54)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (c03c4760)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/module.c (c040c00c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (c0417a1c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (c042dcd8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (c0433924)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (c04354b4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (c0438484)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (c0454bd0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
```
```
In kernel/trace/trace_events_trigger.c (c047e4a8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_probe.c (c048af3c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (c04918cc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (c04b71a8)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (c04c6fb8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (c0502c0c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (c052cd64)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (c0541d0c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (c05c7230)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (c05c9e84)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (c0653c1c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (c06debe4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (c070cf5c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (c070d288)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c070d554)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (c070d808)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (c0722d4c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (c0725ea0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (c0729c0c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (c072ecfc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (c073267c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (c0734e84)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (c0735ea4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (c0747300)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (c07514f0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (c075a038)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (c075b6f8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (c075d3cc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (c0762750)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (c0765890)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (c079eecc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (c07a0eec)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (c07e42e0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (c07ea51c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (c0807f74)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/dma/dmaengine.c (c091ebf4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/core.c (c09d4ba0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (c09edbd4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (c0b77de0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (c0b7e4e4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (c0b7f2b0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (c0bcc270)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (c0beb5d4)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (c0bed91c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (c0bef5c4)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (c0bf1460)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (c0cdcd70)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (c0ce13c0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (c0cf95fc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (c0d02a2c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (c0d1eb84)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (c0d2ae34)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (c0d32cec)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (c0d3b720)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (c0d5b3e4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (c0d9fb10)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (c0da3558)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (c0db6438)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (c0dd8bd4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (c0ddf670)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (c0deb168)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (c0dfc604)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (c0e09ab4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (c0e48114)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (c0e4e3f4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (c0e63750)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (c0e64a24)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (c0e6701c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (c0e73b40)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (c0e747cc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (c0e7b224)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (c0e7ecec)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a08f0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000dbc34)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_link_table_and_group
```
```
In kernel/fork.c (c00000000013a4c8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (c00000000016d724)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (c00000000018cd5c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (c000000000199c98)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (c0000000001ca698)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (c0000000001f1e18)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (c00000000022c0f0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (c000000000244230)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (c0000000002605cc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (c000000000267f48)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (c00000000026a954)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (c00000000026f19c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (c000000000297a3c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d53c0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (c0000000002e4fb8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (c0000000002f9e84)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (c000000000302efc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (c000000000332014)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (c000000000346408)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (c00000000039f2cc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (c0000000003e1d50)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (c000000000403ad4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (c0000000004f90b8)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/timerfd.c (c0000000004fd1bc)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (c0000000005bafb8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (c00000000066f220)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (c0000000006b60ec)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (c0000000006b6564)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c0000000006b6a38)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (c0000000006b6dfc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (c0000000006d50c4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (c0000000006dab60)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (c0000000006e01d0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (c0000000006e78b4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (c0000000006eda14)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (c0000000006f1c24)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (c0000000006f365c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (c00000000070bc2c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (c00000000071adfc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (c000000000727e44)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (c000000000729ce4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (c00000000072c86c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (c0000000007357bc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (c00000000073ac60)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (c00000000078a2d4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (c00000000078cf54)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (c0000000007e82f4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (c0000000007efe24)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (c000000000810bf4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/dma/dmaengine.c (c0000000008c88c8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/core.c (c00000000097c2d4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (c0000000009a200c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (c000000000b741ac)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (c000000000b7d4c0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (c000000000b7e9a8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (c000000000bd6010)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (c000000000bffdbc)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (c000000000c02c34)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (c000000000c050a0)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (c000000000c07f70)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (c000000000c9ad8c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (c000000000cab598)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (c000000000cbf28c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (c000000000ccc4c8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (c000000000cefdf8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (c000000000d0068c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (c000000000d0c56c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (c000000000d1b188)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (c000000000d4883c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (c000000000da03c8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (c000000000da5890)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (c000000000dbf2b4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (c000000000dea518)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (c000000000df4e38)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (c000000000e04bb8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (c000000000e1c0bc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (c000000000e2a7f4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (c000000000e7b118)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (c000000000e83cc8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (c000000000ea0ae4)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (c000000000ea222c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea53a0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (c000000000eb7208)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (c000000000eb8274)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (c000000000ec093c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (c000000000ec2774)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In kernel/fork.c (ffffffe0000c0898)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffe0000dbe02)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffe0000ecb42)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffe0000f2e18)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffe00010e062)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/module.c (ffffffe00014554a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffe00014e27a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffe00016208c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffe0001668fe)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffe000168380)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/trace/ftrace.c (ffffffe000175a4c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffe0001976e6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/bpf/core.c (ffffffe00019c6ce)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffe0001bbfc8)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (ffffffe0001c736e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffe0001f7464)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffe000218bde)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffe00022a828)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffe0002a411c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffe0002a60ca)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffe000317584)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffe000388c96)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffe0003af91e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffe0003afb9e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffe0003afe94)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffe0003b00c8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffe0003c525e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffe0003c6242)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffe0003c93a0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffe0003cdcb2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffe0003d0e52)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffe0003d32ca)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffe0003d4458)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffe0003e2f5c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffe0003eb81e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffe0003f3158)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffe0003f45de)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffe0003f6058)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffe0003fa77c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffe0003fd4e2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffe000431582)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffe0004330e6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffe00046bad2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffe000470862)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffe00048c03e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/dma/dmaengine.c (ffffffe00051716c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/core.c (ffffffe00057afd2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffe0006a6f40)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffe0006acdba)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffe0006adf84)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffe0006ddb26)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffe0006faa82)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffe0006fc75a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffe0006fe0be)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffe0006fff0e)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffe00074e986)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffe0007584d4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffe0007658aa)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffe00076d966)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffe0007842b0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffe00078ed46)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffe0007951d6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffe00079c80a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (ffffffe0007b7c8e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0c6e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffe0007f4022)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffe000804790)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffe00081ffb0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008263a8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffe000830a00)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffe000841622)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffe00084c128)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffe0008808ee)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffe000887356)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffe000898c5e)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffe000899cb4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089bbf0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffe0008a71c6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffe0008a7cf6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad266)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffe0008ae02e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff810361bc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a574)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff810994a1)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810bf5c4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810d845c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810e2798)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81109e90)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff811258e9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff8114df20)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8115bd35)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff811710ac)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81176baa)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81178698)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8117b195)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811955bc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bb85c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c3315)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811d00b2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811d5c4c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811f8151)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (ffffffff81207f75)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff8124265c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81272323)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81287531)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8132c0b6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffff8132f781)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b4391)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff814345a5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff81462074)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff814623ca)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814626b5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81462958)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81476a8b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8147994f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8147cdfa)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff81481910)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81485284)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff81487a2e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff81488830)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff81498a49)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814a24ae)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff814ab0e9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff814ac329)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff814ade46)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814b32a4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b5fce)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814ebb5d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814ed8b9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff8152abdc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff8152fd98)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff8154ae3a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81a69063)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8161d11d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816ac935)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b258b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816b7550)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff816c143c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff816d8fc9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8180b12d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81811190)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff818123f2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8183b20f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff8185b4f7)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8185d3ab)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8185eeb5)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff81860d14)
Location: include/linux/rculist.h:67
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818a488e)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818c4f97)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818d0525)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff818df8fa)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff818e84d0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81901d3d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8190cc4d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff81914be4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff8191c4bf)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (ffffffff8193d13f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff8197d81d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81980c8b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81993766)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff819b2d20)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b9061)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4270)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff819d48fa)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff819e09b4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b04e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a21fbb)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a35118)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a36048)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a383c9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a446ec)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a45285)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff81a4b777)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81a4c59f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff81025b0c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81078e44)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff81087ef1)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810adde4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810c6e6c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810d17d5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810fad70)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff81118349)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff811411d0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f01f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8116424c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81169d4a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8116b838)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8116e335)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811886cc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ae63c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b60f5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811c2e82)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811c8a0c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811eaea1)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (ffffffff811fb0a2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff8123562c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81264293)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81279391)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8131d426)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffff813203a5)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a4e21)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81425025)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff81452aa4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81452dfa)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814530e5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81453388)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff814674ab)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8146a36f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8146d81a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff81472330)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81475ca4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff8147844e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff81479250)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff81489469)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81492ece)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8149bb09)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff8149cd49)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149e866)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814a3cc4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a69ee)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814dc0ad)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814dde09)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff8151aebc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff81520078)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff8153b11a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81a25b23)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8161180d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff8168a295)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8169024b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81695190)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff8169c6ec)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff816b35e9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/net/vxlan.c (ffffffff8176eff1)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
```
```
In drivers/input/input.c (ffffffff817d289d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff817d88d0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff817d9b32)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8180287f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff81822ac1)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8182497b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81826485)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff818282e4)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852d1c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8186004e)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8187eed7)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff8188a405)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8189973a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff818a2310)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff818bbb6d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff818c6a0d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff818ce9a4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff818d626f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (ffffffff818f6c3f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff819372dd)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff8193a74b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff8194d226)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff8196f350)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81975e51)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81981060)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff819916ba)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8199d774)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff819d7e0e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff819ded7b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819f1d38)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f2c68)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4fe9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a012dc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a01e75)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff81a08367)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81a096cf)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff8103601c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a524)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff81099451)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810beb24)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810d4c0c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810deb18)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81107d80)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff811237d9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff8114bdd0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81159b05)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8116ee7c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8117497a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81176468)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81178f65)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff8119338c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b962c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c10e5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811cde82)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811d3a1c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811f5f21)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (ffffffff81205d45)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff812403fc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff812700c3)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81285341)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81329b86)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/timerfd.c (ffffffff8132d251)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b1bf1)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81430745)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff8145e114)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8145e46a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8145e755)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8145e9f8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81472b2b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff814759ef)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff81478e9a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff8147d9b0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81481324)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff81483ace)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff814848d0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff81494ae9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8149e54e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff814a7189)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff814a83c9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff814a9ee6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814af334)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b205e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814e7bed)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814e9949)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff81526c6c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff8152bad8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff81546b7a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81ad5473)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff816389f8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff8164b0bd)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816dab15)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e0adb)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5a20)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff816ef90c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff817068e9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8184a2ad)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81850310)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81851572)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8188a83f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff818aab27)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818ac9db)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818ae4e5)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff818b0344)
Location: include/linux/rculist.h:67
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818f5eee)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81915f97)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81921525)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8193092a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff81939500)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81952d6d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8195dc7d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff81965c14)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff8196d64f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (ffffffff8198e2cf)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a3590)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_nat_helper_register
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_expectfn_register
```
```
In net/ipv4/tcp_cong.c (ffffffff819e7fed)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819eb45b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff819fe006)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81a1d5c0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23ae1)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2ecf0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f37a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a4b434)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a85ace)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a8ca3b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa0fc8)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aa1ef8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4279)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81ab059c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ab1135)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7627)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81ab898f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff81036ffc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c7c4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/fork.c (ffffffff810a108a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810c6e94)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810e003c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810ea628)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81113120)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/livepatch/patch.c (ffffffff8112fdf9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81158abb)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81166b6c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8117c66c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8118225a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81183d28)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81186835)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811a0f5c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c76cc)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cf185)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811dc0e2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811e1d0c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff81204481)
Location: include/linux/rculist.h:67
Inline: True
```
```
In kernel/events/core.c (ffffffff81214bc6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/backing-dev.c (ffffffff8124faf7)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8127fae8)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81295482)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8133bff4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/timerfd.c (ffffffff8133fd4b)
Location: include/linux/rculist.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c6737)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81446d68)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff814758d4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81475c1c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81475f18)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81476206)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff8148a41b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8148d43f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8149094a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/common.c (ffffffff814954d0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81498e94)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/gc.c (ffffffff8149b45c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff8149c410)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/apparmor/policy.c (ffffffff814acb09)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814b6b3e)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff814bf8ae)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/device_cgroup.c (ffffffff814c0d79)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff814c2936)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814c7db4)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814caade)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff81500b8d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff81502919)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff815405ec)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/genalloc.c (ffffffff81545378)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffff815609da)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81ae1928)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652d48)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/dma/dmaengine.c (ffffffff8166565d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816f50c5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fb0eb)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816ffced)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/core.c (ffffffff8170a14c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeup.c (ffffffff817212f9)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8186547d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8186b030)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8186c392)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff818a96d2)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/dm-stats.c (ffffffff818c6757)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c8c2b)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818ca775)
Location: include/linux/rculist.h:67
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff818cc5d4)
Location: include/linux/rculist.h:67
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81916fde)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81937197)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff8193ba35)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81951ffa)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff8195abe0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81974850)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8197fecd)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffffffff81987e54)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/devlink.c (ffffffff8198fa9f)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/netlink/af_netlink.c (ffffffff819b0b7a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1d5d)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819f52db)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/af_inet.c (ffffffff81a08396)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81a28782)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2eec6)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a1b0)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/af_inet6.c (ffffffff81a4ae7a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a574c5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a925f7)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a98691)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81aad290)
Location: include/linux/rculist.h:67
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aae268)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab060a)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81abc94c)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81abd4e5)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
```
In net/xdp/xdp_umem.c (ffffffff81ac3a47)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81ac4dbf)
Location: include/linux/rculist.h:67
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
</details>
</li>
</ul>

## Differences
