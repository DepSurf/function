# Function: <code>list_add_rcu</code>

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
In arch/x86/kernel/nmi.c (ffffffff810324f4)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8107351e)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff81099bb2)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810b0432)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810b7b86)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/core.c (ffffffff8118bf94)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff81109229)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/auditfilter.c (ffffffff8112512f)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81129e57)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8112b322)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8112ca11)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8116638e)
Location: include/linux/rculist.h:78
Inline: True
```
```
In kernel/events/core.c (ffffffff81179b57)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
```
```
In mm/vmalloc.c (ffffffff811ccc2b)
Location: include/linux/rculist.h:78
Inline: True
```
```
In mm/zswap.c (ffffffff811d8485)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff81258a38)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff812cea3a)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff8132754d)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/selinux/netif.c (ffffffff8134cfb9)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8134d285)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8134d524)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/smack/smack_lsm.c (ffffffff813617f0)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81362915)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff81364b72)
Location: include/linux/rculist.h:78
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
In security/tomoyo/gc.c (ffffffff81370378)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff8137f321)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81394b0f)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
```
```
In security/yama/yama_lsm.c (ffffffff8139502d)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/bug.c (ffffffff813e8d0b)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/genalloc.c (ffffffff8140761e)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b6277)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff815341ae)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81539604)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8153c128)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff8155b923)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81666e2b)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff81690125)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/gen_estimator.c (ffffffff8170f8d1)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81713586)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff8173aa25)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff8174a017)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff8175115f)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hook
```
```
In net/ipv4/af_inet.c (ffffffff81792f05)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff817a9fef)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv6/af_inet6.c (ffffffff817c30aa)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
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
In arch/x86/kernel/nmi.c (ffffffff8103161c)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81074af6)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff8109d145)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810b3032)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810bb597)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/core.c (ffffffff810efc71)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff8110ff0f)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/auditfilter.c (ffffffff8112d1cc)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81131f65)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81133529)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81134c0d)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811712bf)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff811727b1)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/events/core.c (ffffffff811908fb)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:add_event_to_ctx
```
```
In mm/vmalloc.c (ffffffff811e9ceb)
Location: include/linux/rculist.h:78
Inline: True
```
```
In mm/zswap.c (ffffffff811f663f)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff812813c3)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff812fe3eb)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff8135dab2)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/selinux/netif.c (ffffffff81382f84)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81383248)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813834f8)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/smack/smack_lsm.c (ffffffff81397583)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81398ae7)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8139bc8a)
Location: include/linux/rculist.h:78
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
In security/tomoyo/gc.c (ffffffff813a6754)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff813b8e58)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813d0183)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff813d0bad)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/bug.c (ffffffff8142ef7b)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/genalloc.c (ffffffff8144f47d)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505c41)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff815889fb)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158e0dc)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81590c7a)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff815adba3)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff816c70db)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff816f0e12)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/gen_estimator.c (ffffffff817771b8)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff8177b226)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff817a69db)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff817b6f37)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff817bd18e)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hook
```
```
In net/ipv4/af_inet.c (ffffffff818006c6)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff8181752c)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/af_inet6.c (ffffffff81830125)
Location: include/linux/rculist.h:78
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
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
In arch/x86/kernel/nmi.c (ffffffff8103126c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81078676)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810a02f5)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810b9622)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810c1c57)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/core.c (ffffffff810f6851)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
  - kernel/livepatch/core.c:klp_enable_object
```
```
In kernel/module.c (ffffffff811177c6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/auditfilter.c (ffffffff81136ee7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8113bcc5)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8113d25e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8113e98d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117ca2f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff8117dfb1)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/events/core.c (ffffffff8119f7c9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:add_event_to_ctx
```
```
In mm/vmalloc.c (ffffffff811fb09b)
Location: include/linux/rculist.h:76
Inline: True
```
```
In mm/zswap.c (ffffffff81206fdc)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff81294eed)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff8131446b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81374122)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/selinux/netif.c (ffffffff81399a04)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81399cc8)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81399f78)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/smack/smack_lsm.c (ffffffff813ae185)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff813af6c7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff813b2cba)
Location: include/linux/rculist.h:76
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
In security/tomoyo/gc.c (ffffffff813bd2d4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff813d0218)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813e7887)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff813e82ad)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/bug.c (ffffffff8144b0eb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In lib/genalloc.c (ffffffff8146de3d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529e41)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff815b60bb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bbbdc)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff815be50a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff815dc973)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff816f50cb)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff81722697)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff817a8886)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff817d54e0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff817e69b7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81831616)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/ipmr.c (ffffffff81848d9c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/af_inet6.c (ffffffff81861ba5)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
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
In arch/x86/kernel/nmi.c (ffffffff8102f531)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81076fa0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff8109e075)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810b423e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810bc56f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff810f8a2c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81118d8a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/auditfilter.c (ffffffff811381cc)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8113d314)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8113e88d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81141c2c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117f69e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff81180b4c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/events/core.c (ffffffff811a435c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:add_event_to_ctx
```
```
In mm/vmalloc.c (ffffffff81205dbf)
Location: include/linux/rculist.h:76
Inline: True
```
```
In mm/zswap.c (ffffffff81213127)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff812a213d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff8130b99a)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81387a90)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/selinux/netif.c (ffffffff813afe08)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff813b0166)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813b0447)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff813b06b6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff813c30b1)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff813c6277)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff813c96aa)
Location: include/linux/rculist.h:76
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
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/gc.c (ffffffff813d3c3c)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff813e39b9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813ec11d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff813f47cd)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff8147350d)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153d26e)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff815cbf0f)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d180b)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff815d40cc)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff815f14f0)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8170abb6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff8173edd9)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff817c6ed6)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff817f47ea)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff818067b7)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81852bc4)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff818862c3)
Location: include/linux/rculist.h:76
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In lib/bug.c (ffffffff818eb37d)
Location: include/linux/rculist.h:76
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
In arch/x86/kernel/nmi.c (ffffffff81031531)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8107d2e8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810a47f5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810bb4ee)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810c43df)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff81102c5f)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81124336)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/auditfilter.c (ffffffff81144ed6)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8114a0f0)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8114b69a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8114e9dc)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811678b3)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8118cfa1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_hist.c (ffffffff8118e47f)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In kernel/events/core.c (ffffffff811b8fc5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/vmalloc.c (ffffffff8121eadf)
Location: include/linux/rculist.h:77
Inline: True
```
```
In mm/zswap.c (ffffffff8122dc83)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/hmm.c (ffffffff8126d416)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_fault
```
```
In fs/timerfd.c (ffffffff812c5463)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff813304ea)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff813ac2fb)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/selinux/netif.c (ffffffff813d5eb8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff813d6206)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813d64e7)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff813d6756)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff813e9371)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff813ec567)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff813efb3a)
Location: include/linux/rculist.h:77
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
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/gc.c (ffffffff813fa151)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff8140a7af)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81413aaa)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8141c87d)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff814a089d)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159fe3a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff81632cdf)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816385db)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8163ae32)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff81658adc)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8177bd76)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff817b0da9)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff81840aa6)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff8186ff7b)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff81885487)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff818d29d4)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff819074d3)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff8197080c)
Location: include/linux/rculist.h:77
Inline: True
```
```
In lib/bug.c (ffffffff819712bd)
Location: include/linux/rculist.h:77
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
In arch/x86/kernel/nmi.c (ffffffff810324c1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81080226)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810aadb5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810c29ac)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810cbdf2)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff8110b241)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81132866)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8113d325)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff811532af)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81158c37)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8115a7ce)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8115d2b5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811765b3)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119bae9)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff811d92ee)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/vmalloc.c (ffffffff812407af)
Location: include/linux/rculist.h:77
Inline: True
```
```
In mm/zswap.c (ffffffff812500a8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/hmm.c (ffffffff812939a1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_fault
  - mm/hmm.c:hmm_vma_get_pfns
```
```
In fs/timerfd.c (ffffffff812ee86d)
Location: include/linux/rculist.h:77
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8135eaa9)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff813dc52e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/selinux/netif.c (ffffffff814064c0)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81406818)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81406af9)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81406d75)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff8141a2a2)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8141d397)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff81420413)
Location: include/linux/rculist.h:77
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
In security/tomoyo/gc.c (ffffffff8142b046)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff8143bfc1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81445ecf)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8144ec29)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff814d5a2d)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d7a64)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff8166e002)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816738db)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff81676417)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff8169464e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff817bce26)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff817f5043)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff81890e66)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff818c1542)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff818d8e51)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81928fa2)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff8195e0b7)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff819c9f95)
Location: include/linux/rculist.h:77
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff819ccd09)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff819cd694)
Location: include/linux/rculist.h:77
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
In arch/x86/kernel/nmi.c (ffffffff81033781)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81086d66)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810b3e35)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810cbcac)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810d4297)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff81116a31)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff8113e19c)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81148bf5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff8115ff63)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81165bfb)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811674a2)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8116a0c5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811841fc)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a9c49)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff811e9630)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/vmalloc.c (ffffffff8125509f)
Location: include/linux/rculist.h:77
Inline: True
```
```
In mm/zswap.c (ffffffff81264578)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/hmm.c (ffffffff812a8671)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_fault
  - mm/hmm.c:hmm_vma_get_pfns
```
```
In fs/timerfd.c (ffffffff813031fd)
Location: include/linux/rculist.h:77
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8137658b)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff813f6b66)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/selinux/netif.c (ffffffff81422013)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8142237f)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81422660)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff814228e5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81436a1f)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81439987)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8143cee3)
Location: include/linux/rculist.h:77
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
In security/tomoyo/gc.c (ffffffff814479fd)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff81458e31)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81462def)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8146bbf9)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff814ea0b8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f12d5)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff8168c432)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81691eab)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8169514e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff816b4cce)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff817e4266)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff81821253)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff818b1446)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff818ea353)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff81905641)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81958292)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81992c17)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a02725)
Location: include/linux/rculist.h:77
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a05e29)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81a069f4)
Location: include/linux/rculist.h:77
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
In arch/x86/kernel/nmi.c (ffffffff81035944)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a944)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810b9d35)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810d3d49)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810ddf08)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff81120c39)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81149c8e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81154245)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff8116cdcc)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff811726d3)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81174208)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81176c45)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff81190f9c)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b7bc8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff81202a58)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff8127f4ea)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff81324441)
Location: include/linux/rculist.h:77
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a047a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81422201)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff8144fc0b)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8144ff8c)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8145027b)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81450585)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff814646d7)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81467588)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8146a9d9)
Location: include/linux/rculist.h:77
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
In security/tomoyo/gc.c (ffffffff814756ab)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff814865b1)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8149000e)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff81498bd9)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff81516d73)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/acpi/apei/ghes.c (ffffffff816230e8)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff816c3f21)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c9e3b)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816cdf0c)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff816eeb96)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81824c96)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff8186363a)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff818fe1f2)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff81939dba)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff819667ef)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff819bcdb6)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff819fe677)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a716de)
Location: include/linux/rculist.h:77
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a75595)
Location: include/linux/rculist.h:77
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81a7634f)
Location: include/linux/rculist.h:77
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
In arch/x86/kernel/nmi.c (ffffffff81036054)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b5b4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810c01b5)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810de265)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810e85e5)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff8112d309)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81155900)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8115fe7a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff81178a89)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff8117e583)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81180078)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81182b75)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff8119cf9c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c323c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff8120f955)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff8128ef4a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff813371a1)
Location: include/linux/rculist.h:95
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b9075)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff8143bfc1)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff81469a82)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81469dd4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8146a0c2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8146a365)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff8147e4a7)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81481368)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff814847b9)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (ffffffff8148f44b)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff814a0461)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814a9ece)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff814b2b09)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff815377b3)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644bb8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff816e6e71)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ece0b)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816f1d5c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff81712c22)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81856116)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff8189538a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff81930522)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff8196cc7a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff81974c14)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff8199d2cf)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff819f39c6)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81a35267)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81aa7ece)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81aac3df)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81aad74f)
Location: include/linux/rculist.h:95
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
In arch/x86/kernel/nmi.c (ffffffff81038063)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81092a72)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
```
```
In kernel/workqueue.c (ffffffff810cb653)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff810e6835)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810f253e)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff8113b959)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff81162894)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/module.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff811701c4)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff8118ab61)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff811919d4)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81193086)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff811963d7)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811b2fac)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:register_ftrace_direct
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dce2e)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff8123a053)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff812c1c06)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff813710c0)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff814045de)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff8148c6f1)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff814bdc1e)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814bdffd)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814be289)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In security/selinux/ibpkey.c (ffffffff814d190e)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
```
```
In security/smack/smack_lsm.c (ffffffff814d3744)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff814d72d8)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff814d7c03)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/gc.c (ffffffff814e673e)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff814fa30a)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81507950)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff81511df8)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff8159b8b3)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/bug.c (ffffffff815e779f)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1dbc)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179d72e)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a5107)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff817aa3ab)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/power/wakeup.c (ffffffff817ce522)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff819284a6)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff8196967a)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb711)
Location: include/linux/rculist.h:105
Inline: True
```
```
In net/core/dev.c (ffffffff819ffb14)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff81a40fc7)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff81a49b24)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff81a7650f)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81ae1c86)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a217)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba4172)
Location: include/linux/rculist.h:105
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ba86ac)
Location: include/linux/rculist.h:105
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
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
In arch/x86/kernel/nmi.c (ffffffff81038ba3)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065a24)
Location: include/linux/rculist.h:113
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81092102)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
```
```
In kernel/workqueue.c (ffffffff810c6783)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff810e4735)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810f06e6)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff811360f9)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff8115e909)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/module.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8116cd04)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff81187dc1)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff8118eb84)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811901f6)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff81193167)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811b0b0c)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9f5e)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff812436eb)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff812cd7e6)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8137ee44)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff81417783)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff814a9d1d)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff814db67e)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814dba30)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814dbca9)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In security/selinux/ibpkey.c (ffffffff814eee20)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
```
```
In security/smack/smack_lsm.c (ffffffff814f0904)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff814f4788)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff814f5173)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net6addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_net4addr_insert
  - security/smack/smackfs.c:smk_set_access
```
```
In security/tomoyo/gc.c (ffffffff81503b3e)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff8151708a)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff815249f0)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8152ec88)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff815b714f)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/bug.c (ffffffff8160c95f)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f17c)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab44e)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b2557)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff817b6836)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/power/wakeup.c (ffffffff817e2b62)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8192f9d6)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff8197019f)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2eba2)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/dev.c (ffffffff819ff874)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff81a4383b)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff81a4f2f4)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff81a7f284)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81aeeb06)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81b38b77)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81bb39e2)
Location: include/linux/rculist.h:113
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9879)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
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
In arch/x86/kernel/nmi.c (ffffffff8103a6b3)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8106639d)
Location: include/linux/rculist.h:113
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81092ae8)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810c80c3)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff810e66d5)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810ecf78)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff81136ef9)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff8115f959)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/module.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8116d943)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff81188e21)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff8118f9b0)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81191522)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff8119419c)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811b14c0)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db4be)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff812486af)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff812d42f2)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff81385ac4)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff8141e461)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff814afffd)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff814e1ffe)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814e2399)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid_slow
```
```
In security/selinux/netport.c (ffffffff814e26a9)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff814f5be4)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff814f7884)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff814fb6f7)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff814fe66f)
Location: include/linux/rculist.h:113
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
In security/tomoyo/gc.c (ffffffff8150a6b4)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff8151d936)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8152ab2c)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff81535429)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff815c1fbf)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/bug.c (ffffffff815efbf1)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0a5c)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e1ed)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81795514)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81799ae7)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/power/wakeup.c (ffffffff817c6f22)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81912d56)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff81954120)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c20df0)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/dev.c (ffffffff819e6054)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff81a285ad)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff81a34334)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff81a68264)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81ada236)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81b26867)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba29e2)
Location: include/linux/rculist.h:113
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8859)
Location: include/linux/rculist.h:113
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
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
In arch/x86/kernel/nmi.c (ffffffff8104006a)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810704bd)
Location: include/linux/rculist.h:104
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff810a2854)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810dc576)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff810fdc35)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff81105c28)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff81159be3)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module.c (ffffffff81184d19)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/module.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff811931d6)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff811b13d4)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff811b8890)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811ba3e2)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff811bd033)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811db350)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81208ace)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff81282d26)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff81319ffd)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff813d2c07)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff81471a89)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81508afc)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff8153affe)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff8153b419)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8153b7ad)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff815505dd)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81552424)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81556367)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff81559489)
Location: include/linux/rculist.h:104
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
In security/tomoyo/gc.c (ffffffff81567d53)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff8157ba26)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81588ecc)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff815939f8)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff81629e38)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/bug.c (ffffffff8165cd01)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176ab6c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/intel/dmar.c (ffffffff81815a7d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181d384)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff818217fb)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/power/wakeup.c (ffffffff81851302)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff819b4d76)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff819f96f0)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d32805)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/dev.c (ffffffff81a9657c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff81add34d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff81ae9e44)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff81b21784)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81b99400)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81bec2e9)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c70532)
Location: include/linux/rculist.h:104
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c765a9)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
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
In arch/x86/kernel/nmi.c (ffffffff8104778b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e6ae)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/mm/kmmio.c (ffffffff810b6e8b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810f5cac)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff8111a673)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff811206e5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff81183207)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module/main.c (ffffffff8118dbea)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/module/main.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff811c3736)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff811e36a5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff811eb7b6)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811ed76f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff811f0d38)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff812113b1)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8124410c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff812ce93b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff81385152)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8145b488)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff814f2ec4)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81599701)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff815d277e)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff815d2bcf)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff815d2faa)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff815e9a84)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff815ebe84)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff815f0717)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff815f39d7)
Location: include/linux/rculist.h:104
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
In security/tomoyo/gc.c (ffffffff81603740)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff81619ffe)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81629758)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff816351ed)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff816fb108)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/bug.c (ffffffff8177608f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189f734)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/intel/dmar.c (ffffffff819568e8)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195e101)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81961a92)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff81996e36)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81b140f5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff81b60c48)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81efecea)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/dev.c (ffffffff81c0d3a5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_add_pack
```
```
In net/core/gro.c (ffffffff81c53312)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/gro.c:dev_add_offload
```
```
In net/core/fib_rules.c (ffffffff81c5ec41)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff81ca9dea)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81d2b240)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81d84849)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e1412d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1ad79)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mctp/route.c (ffffffff81e39af2)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff81e3b971)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In arch/x86/kernel/nmi.c (ffffffff810521bb)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fbde)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/mm/kmmio.c (ffffffff810d2210)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff811181f7)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff81141f23)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff8115322d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff811be287)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module/main.c (ffffffff811ca727)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/module/main.c:add_unformed_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81205845)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff81229ac5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff81231bb6)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81233d3f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff812370a6)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff8125a921)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_alloc_direct_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291d6c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff81336a44)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff81402e3b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff814eaa98)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffff8158b201)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81642981)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff816806bf)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff81680b6f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81680f98)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff816993f4)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff8169bae4)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff816a0b17)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff816a4357)
Location: include/linux/rculist.h:104
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
In security/tomoyo/gc.c (ffffffff816b4900)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/audit.c (ffffffff816c1e43)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
```
```
In security/apparmor/policy.c (ffffffff816cd2de)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff816dde48)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff816ebe3d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff817edc88)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8aea)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abd728)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac5c21)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca567)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff81b07c56)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81ca5125)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff81cfaeee)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d78763)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/dev.c (ffffffff81dbcfc5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_add_pack
```
```
In net/core/gro.c (ffffffff81e08942)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/gro.c:dev_add_offload
```
```
In net/core/fib_rules.c (ffffffff81e154c1)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff81e66e1a)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81ef2e30)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81f5217d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81feae6d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2299)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff82007c4f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mctp/route.c (ffffffff82012bc2)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff82014f46)
Location: include/linux/rculist.h:104
Inline: True
```
```
In lib/bug.c (ffffffff8201e99f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff81052f1b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092aee)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/mm/kmmio.c (ffffffff810d5680)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff8112542c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff8114dbf3)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff81162add)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff811d0cb7)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/module/main.c (ffffffff811df630)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8121b2b5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff81240085)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff81248846)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8124aa2f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff8124e166)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff81271dc1)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aefcc)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_user.c (ffffffff812c6e6d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_event_mm_dup
  - kernel/trace/trace_events_user.c:current_user_event_mm
```
```
In kernel/events/core.c (ffffffff81367804)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff814363c5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8152183b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/sem.c (ffffffff8167af15)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff816b8788)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816b8be0)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816b9055)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff816d18aa)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff816d45c4)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff816d9457)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff816dd30d)
Location: include/linux/rculist.h:104
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
In security/tomoyo/gc.c (ffffffff816ed3f6)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/audit.c (ffffffff816faa2d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
```
```
In security/apparmor/policy.c (ffffffff817059ef)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81717448)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8172626d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff8182e098)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a313eb)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a07f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b126bc)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81b17175)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff81b55cb6)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81d0c85c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff81d61891)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de66a3)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/dev.c (ffffffff81e2d7f5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_add_pack
```
```
In net/core/gro.c (ffffffff81e7b242)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/gro.c:dev_add_offload
```
```
In net/core/fib_rules.c (ffffffff81e88dd1)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff81ec2bda)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81f528e0)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81fb1b8d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff8206711d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e4c9)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff82083fcf)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mctp/route.c (ffffffff8208f9bf)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff82091d66)
Location: include/linux/rculist.h:104
Inline: True
```
```
In lib/bug.c (ffffffff8209e9bf)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/x86/kernel/nmi.c (ffffffff8105a13b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099f2d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/mm/kmmio.c (ffffffff810dde50)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff8112d775)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_commit
```
```
In kernel/sched/core.c (ffffffff81159a03)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff8116f59a)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff811e5936)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/dma/swiotlb.c (ffffffff811ec771)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/module/main.c (ffffffff811f5360)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff812330e5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/auditfilter.c (ffffffff81259f05)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/audit_watch.c (ffffffff81262725)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8126493c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In kernel/kprobes.c (ffffffff81268096)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff8128c284)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb4ec)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/trace/trace_events_user.c (ffffffff812e2c98)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_create
  - kernel/trace/trace_events_user.c:user_event_mm_dup
  - kernel/trace/trace_events_user.c:current_user_event_mm
```
```
In kernel/events/core.c (ffffffff81394bb3)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff8146fe1e)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff81555e7b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/sem.c (ffffffff816b72ca)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (ffffffff816f51e5)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816f565f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816f5b04)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8170df09)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81710a6a)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81715eb7)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8171a555)
Location: include/linux/rculist.h:104
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
In security/tomoyo/gc.c (ffffffff8172a1c6)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/audit.c (ffffffff8173763d)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
```
```
In security/apparmor/policy.c (ffffffff817432ef)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81755fd8)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8176748c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff8187fc58)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/stackdepot.c (ffffffff81928bc2)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7c85b)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e0cf)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b66c9c)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c6a1)
Location: include/linux/rculist.h:104
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81bae276)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81dc24ec)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff81e18a95)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c883)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
```
In net/core/dev.c (ffffffff81eebb36)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_add_pack
```
```
In net/core/gro.c (ffffffff81f3b4d2)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/gro.c:dev_add_offload
```
```
In net/core/fib_rules.c (ffffffff81f4ade1)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/netlink/af_netlink.c (ffffffff81f85f2a)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff82018bc0)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff8207f2ad)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff8213a38f)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142549)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_add_xsk
```
```
In net/mptcp/pm_netlink.c (ffffffff82159620)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mctp/route.c (ffffffff82165ece)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff82168335)
Location: include/linux/rculist.h:104
Inline: True
```
```
In lib/bug.c (ffffffff821769bf)
Location: include/linux/rculist.h:104
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
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
In arch/arm64/kernel/debug-monitors.c (ffff800010086ad0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:register_kernel_break_hook
  - arch/arm64/kernel/debug-monitors.c:register_user_break_hook
  - arch/arm64/kernel/debug-monitors.c:register_kernel_step_hook
  - arch/arm64/kernel/debug-monitors.c:register_user_step_hook
```
```
In virt/kvm/eventfd.c (ffff8000100c1220)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In kernel/workqueue.c (ffff80001011deac)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffff80001013dd40)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffff800010147604)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/module.c (ffff8000101c4cfc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffff8000101d0c7c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffff8000101edbd8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffff8000101f3418)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffff8000101f531c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffff8000101f887c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffff800010215e54)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242c08)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffff80001029776c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffff80001032bc4c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffff8000103f4f6c)
Location: include/linux/rculist.h:95
Inline: True
```
```
In fs/ext4/mballoc.c (ffff80001048f4ac)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffff800010523e40)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffff800010558134)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffff8000105585b8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffff8000105589d8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffff800010558de0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffff80001056f318)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffff800010572c74)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffff800010576e08)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (ffff8000105830a0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffff800010596220)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffff8000105a08f0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffff8000105aaad4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffff800010644900)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b0620)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/base/power/wakeup.c (ffff800010904a6c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffff800010a95168)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffff800010aea238)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffff800010bccae8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffff800010c13460)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffff800010c1a928)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffff800010c4a910)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffff800010cabcb4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffff800010cf64cc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffff800010d7b720)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (ffff800010d80c4c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffff800010d839ec)
Location: include/linux/rculist.h:95
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
In kernel/workqueue.c (c03719c4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (c038dcc8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (c0395b50)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/module.c (c040c004)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (c0414878)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (c042dcd4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (c0433920)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (c04354b0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (c0438484)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (c0454bd0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
```
```
In kernel/trace/trace_events_trigger.c (c047e4a8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (c04c6fb8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (c0541d0c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (c05c9e7c)
Location: include/linux/rculist.h:95
Inline: True
```
```
In fs/ext4/mballoc.c (c0650bd4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (c06debdc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (c070cf50)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (c070d280)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c070d54c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (c070d7fc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (c0722d48)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (c0725e98)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (c0729ba8)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (c0734e80)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (c07472fc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (c07514f0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (c075a038)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (c07ea514)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/base/power/wakeup.c (c09edbd4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (c0b77ddc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (c0bcc26c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (c0ce13b8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (c0d2ae30)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (c0d32cec)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (c0d5b3e4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (c0db6438)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (c0dfc600)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (c0e76a54)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (c0e7b224)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (c0e7ece4)
Location: include/linux/rculist.h:95
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
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a08ec)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000dbc34)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_link_table_and_group
```
```
In kernel/workqueue.c (c0000000001661b4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (c00000000018cd5c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (c000000000199c94)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (c0000000001f1e14)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (c00000000022c0f0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (c00000000023b53c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (c0000000002605c8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (c000000000267f44)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (c00000000026a954)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (c00000000026f198)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (c000000000297a3c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d53c0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (c000000000346408)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (c000000000403ad4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (c0000000004fd1bc)
Location: include/linux/rculist.h:95
Inline: True
```
```
In fs/ext4/mballoc.c (c0000000005b6c0c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (c00000000066f218)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:lookup_undo
```
```
In security/selinux/netif.c (c0000000006b60dc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (c0000000006b6564)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c0000000006b6a30)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (c0000000006b6df4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (c0000000006d50c0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (c0000000006dab54)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (c0000000006e01d0)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (c0000000006f1c20)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (c00000000070bc28)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (c00000000071adfc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (c000000000727e44)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (c0000000007efe1c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/base/power/wakeup.c (c0000000009a200c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (c000000000b741a8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (c000000000bd600c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (c000000000cab590)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (c000000000d00688)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (c000000000d0c56c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (c000000000d4883c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (c000000000dbf2b4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (c000000000e1c0b8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (c000000000ebaecc)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (c000000000ec093c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (c000000000ec2774)
Location: include/linux/rculist.h:95
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
In kernel/workqueue.c (ffffffe0000d6de6)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffe0000ecb38)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffe0000f2e16)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/module.c (ffffffe000145540)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffe00014abc2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffe00016208a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffe00016688e)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffe00016837e)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/trace/ftrace.c (ffffffe000175a42)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffe0001976e6)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffe0001c736e)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffe00022a822)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffe0002a60bc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
```
```
In fs/ext4/mballoc.c (ffffffe00031489c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffe000388c94)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffe0003af916)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffe0003afb8c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffe0003afe74)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffe0003b00a8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffe0003c525c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffe0003c6236)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffe0003c93a0)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (ffffffe0003d32c8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffe0003e2f58)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffe0003eb812)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffe0003f3152)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffe00047085e)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/input/input.c (ffffffe0006a6f3c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffe0006ddb22)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffe0007584ce)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffe00078ed44)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffe0007951ce)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffe0007b7c86)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffe000804790)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffe000841620)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffe0008a9b3e)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad258)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffe0008ae020)
Location: include/linux/rculist.h:95
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
In arch/x86/kernel/nmi.c (ffffffff810361b4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a574)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810ba525)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810d8455)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810e2795)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff811258e9)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff8114df20)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8115849a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff811710a9)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81176ba3)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81178698)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8117b195)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811955bc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bb85c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff81207f75)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff8128752a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8132f781)
Location: include/linux/rculist.h:95
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b1655)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff814345a1)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff81462062)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff814623b4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814626a2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81462945)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81476a87)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff81479948)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8147cd99)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (ffffffff81487a2b)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff81498a41)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814a24ae)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff814ab0e9)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff8152fd93)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/iommu/dmar.c (ffffffff816ac951)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b257b)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816b754c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff816d8fc2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8180b126)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff8183b20a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff818d0522)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff8190cc4a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff81914be4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff8193d13f)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81993766)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff819d48f7)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a4725e)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a4b76f)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81a4c59f)
Location: include/linux/rculist.h:95
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
In arch/x86/kernel/nmi.c (ffffffff81025b04)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff81078e44)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810a8e65)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810c6e65)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810d17d2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff81118349)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff811411d0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8114b8ea)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff81164249)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81169d43)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8116b838)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff8116e335)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811886cc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ae63c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff811fb0a2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff8127938a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff813203a5)
Location: include/linux/rculist.h:95
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a20e5)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81425021)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff81452a92)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81452de4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814530d2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff81453375)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff814674a7)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8146a368)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff8146d7b9)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (ffffffff8147844b)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff81489461)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81492ece)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff8149bb09)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff81520073)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/iommu/dmar.c (ffffffff8168a2b1)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8169023b)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff8169518c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff816b35e2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff817d2896)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff8180287a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff8188a402)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff818c6a0a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff818ce9a4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff818f6c3f)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff8194d226)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff819916b7)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a03e4e)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a0835f)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81a096cf)
Location: include/linux/rculist.h:95
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
In arch/x86/kernel/nmi.c (ffffffff81036014)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a524)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810b9a85)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810d4c05)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810deb15)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff811237d9)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff8114bdd0)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8115626a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff8116ee79)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81174973)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81176468)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81178f65)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff8119338c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b962c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff81205d45)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff8128533a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8132d251)
Location: include/linux/rculist.h:95
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813aeeb5)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81430741)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff8145e102)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8145e454)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8145e742)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff8145e9e5)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff81472b27)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff814759e8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff81478e39)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (ffffffff81483acb)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff81494ae1)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8149e54e)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff814a7189)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff8152bad3)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/acpi/apei/ghes.c (ffffffff816389f8)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff816dab31)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e0acb)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5a1c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff817068e2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff8184a2a6)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff8188a83a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff81921522)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff8195dc7a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff81965c14)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff8198e2cf)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a3589)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_nat_helper_register
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_expectfn_register
```
```
In net/ipv4/af_inet.c (ffffffff819fe006)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f377)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ab310e)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ab761f)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81ab898f)
Location: include/linux/rculist.h:95
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
In arch/x86/kernel/nmi.c (ffffffff81036ff4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c7c4)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810c2bc5)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:link_pwq
```
```
In kernel/sched/core.c (ffffffff810e0035)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_online_group
```
```
In kernel/sched/fair.c (ffffffff810ea625)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/livepatch/patch.c (ffffffff8112fdf9)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_patch_object
```
```
In kernel/module.c (ffffffff81158abb)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81163b4a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
```
```
In kernel/auditfilter.c (ffffffff8117c669)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/audit_watch.c (ffffffff81182253)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81183d28)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In kernel/kprobes.c (ffffffff81186835)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:__get_insn_slot
```
```
In kernel/trace/ftrace.c (ffffffff811a0f5c)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c76cc)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/events/core.c (ffffffff81214bc6)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:list_add_event
```
```
In mm/zswap.c (ffffffff8129547b)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/timerfd.c (ffffffff8133fd4b)
Location: include/linux/rculist.h:95
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c3b13)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In ipc/sem.c (ffffffff81446d64)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
```
```
In security/selinux/netif.c (ffffffff814758c2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81475c06)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81475efe)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffffffff814761ec)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/smack/smack_lsm.c (ffffffff8148a417)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8148d438)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_insert_entry
```
```
In security/smack/smackfs.c (ffffffff814908e9)
Location: include/linux/rculist.h:95
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
In security/tomoyo/gc.c (ffffffff8149b459)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/policy.c (ffffffff814acb01)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814b6b3e)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/yama/yama_lsm.c (ffffffff814bf8ae)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In lib/genalloc.c (ffffffff81545373)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652d48)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/iommu/dmar.c (ffffffff816f50e1)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fb0db)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
```
In drivers/iommu/intel-svm.c (ffffffff816ffce9)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/base/power/wakeup.c (ffffffff817212f2)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_add
```
```
In drivers/input/input.c (ffffffff81865476)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
```
```
In drivers/md/md.c (ffffffff818a96cd)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
```
```
In net/core/dev.c (ffffffff8193ba32)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:dev_add_pack
```
```
In net/core/fib_rules.c (ffffffff8197feca)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (ffffffff81987e54)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/netlink/af_netlink.c (ffffffff819b0b7a)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/af_inet.c (ffffffff81a08396)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv6/af_inet6.c (ffffffff81a4ae77)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ncsi/ncsi-manage.c (ffffffff81abf4ae)
Location: include/linux/rculist.h:95
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ac3a3f)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/bug.c (ffffffff81ac4dbf)
Location: include/linux/rculist.h:95
Inline: True
Inline callers:
  - lib/bug.c:module_bug_finalize
```
</details>
</li>
</ul>

## Differences
