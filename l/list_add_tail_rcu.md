# Function: <code>list_add_tail_rcu</code>

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
In arch/x86/kernel/nmi.c (ffffffff81032562)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff8107f3b9)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff8109d7bf)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
```
In kernel/sched/fair.c (ffffffff810b851c)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810d65ce)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup.c (ffffffff811149a2)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/cgroup.c:create_css
```
```
In kernel/auditfilter.c (ffffffff81125240)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/kprobes.c (ffffffff8112f019)
Location: include/linux/rculist.h:99
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81168998)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f5db)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In mm/backing-dev.c (ffffffff811ae3f1)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff811cea0c)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff811d8414)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81256268)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/ext4/mballoc.c (ffffffff812d14f5)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/commoncap.c (ffffffff81f982a7)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81f986bb)
Location: include/linux/rculist.h:99
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81f98b9e)
Location: include/linux/rculist.h:99
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8136aa4b)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8136d55a)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/memory.c (ffffffff81f98f57)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/tomoyo.c (ffffffff81f9912f)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/lsm.c (ffffffff81f99772)
Location: include/linux/rculist.h:99
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff81f99908)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_add_hooks
```
```
In security/device_cgroup.c (ffffffff813957bb)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff813971b3)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In lib/textsearch.c (ffffffff81411882)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff8181adb3)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff814bdf1f)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81525971)
Location: include/linux/rculist.h:99
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8153414b)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/input/input.c (ffffffff81666e58)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8166c93f)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8166d720)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff816ae533)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff816f6f1a)
Location: include/linux/rculist.h:99
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81fbae01)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81716aaf)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81722677)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/fib_rules.c (ffffffff81739819)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/sched/sch_api.c (ffffffff8174316f)
Location: include/linux/rculist.h:99
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff81780586)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817add23)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff817b70e9)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/ip6mr.c (ffffffff817f8fee)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8180c5f1)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8180d037)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180f121)
Location: include/linux/rculist.h:99
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
In arch/x86/kernel/nmi.c (ffffffff810316a1)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff8108156f)
Location: include/linux/rculist.h:99
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a0e10)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
```
In kernel/sched/fair.c (ffffffff810bbca0)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810db585)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup.c (ffffffff8111d305)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8112d2d9)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/kprobes.c (ffffffff811371a8)
Location: include/linux/rculist.h:99
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81176028)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117ccb5)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In mm/backing-dev.c (ffffffff811c7751)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff811eb667)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff811f6568)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8127eb7e)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/ext4/mballoc.c (ffffffff81304155)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In security/commoncap.c (ffffffff81fc2f47)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81fc3356)
Location: include/linux/rculist.h:99
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81fc384f)
Location: include/linux/rculist.h:99
Inline: True
```
```
In security/tomoyo/common.c (ffffffff813a0a21)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff813a40ef)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff813a76a1)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/tomoyo/tomoyo.c (ffffffff81fc3dfe)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/lsm.c (ffffffff81fc44e7)
Location: include/linux/rculist.h:99
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff81fc4682)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_add_hooks
```
```
In security/device_cgroup.c (ffffffff813d14fb)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff813d3209)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In lib/textsearch.c (ffffffff814595f2)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81894f18)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8150dbe5)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff815889da)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/input/input.c (ffffffff816c7108)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff816cc80f)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff816cd9b0)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff8170ea25)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8175bbaf)
Location: include/linux/rculist.h:99
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81fe89c5)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff8177c58f)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8178c0ab)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/fib_rules.c (ffffffff817a5ac9)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/sched/sch_api.c (ffffffff817affff)
Location: include/linux/rculist.h:99
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff817eda61)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181ad13)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81824119)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/ip6mr.c (ffffffff818687c5)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/ipv6/calipso.c (ffffffff8186f80c)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8187e6e6)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8187f4f1)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818817c4)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff8188df0f)
Location: include/linux/rculist.h:99
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff8188fcaf)
Location: include/linux/rculist.h:99
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
In arch/x86/kernel/nmi.c (ffffffff810312f1)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff81085fb8)
Location: include/linux/rculist.h:97
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a5eda)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
```
In kernel/sched/fair.c (ffffffff810c214d)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810e2055)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup.c (ffffffff81125635)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81136ff4)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/kprobes.c (ffffffff81140f28)
Location: include/linux/rculist.h:97
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81181ab8)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff811888c5)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In mm/backing-dev.c (ffffffff811d7871)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff811fc8d7)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81206f05)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8129270e)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/ext4/mballoc.c (ffffffff8131a114)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In security/commoncap.c (ffffffff81fff993)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81fffda2)
Location: include/linux/rculist.h:97
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff82000260)
Location: include/linux/rculist.h:97
Inline: True
```
```
In security/tomoyo/common.c (ffffffff813b75b1)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff813bac6f)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff813be224)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/tomoyo/tomoyo.c (ffffffff820007f2)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/lsm.c (ffffffff82000f12)
Location: include/linux/rculist.h:97
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff820010b9)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_add_hooks
```
```
In security/device_cgroup.c (ffffffff813e8c2b)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff813ea851)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff813ee669)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/textsearch.c (ffffffff81477fb2)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff818c9671)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81539d8a)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff815b609a)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff815c7fcc)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff816f50f8)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff816fa7af)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff816fb950)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff8173fb08)
Location: include/linux/rculist.h:97
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8178811f)
Location: include/linux/rculist.h:97
Inline: True
```
```
In net/core/net_namespace.c (ffffffff820271eb)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff817a9cff)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff817b997b)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/fib_rules.c (ffffffff817d4539)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e3c8)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184c5d3)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81855a69)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/ip6mr.c (ffffffff8189b615)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/ipv6/calipso.c (ffffffff818a277c)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff818b2f96)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff818b3da1)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b6074)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff818c2123)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff818c428f)
Location: include/linux/rculist.h:97
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
In arch/x86/kernel/nmi.c (ffffffff8102f53f)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810829fd)
Location: include/linux/rculist.h:97
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a2f31)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
```
In kernel/sched/fair.c (ffffffff810bce37)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810e1205)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81127d0b)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff811382c0)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/kprobes.c (ffffffff811427a5)
Location: include/linux/rculist.h:97
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81184868)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b516)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/core.c (ffffffff8118f136)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In mm/backing-dev.c (ffffffff811e1b9d)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8120754f)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff812131d3)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8129f77e)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/ext4/mballoc.c (ffffffff813114ab)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In security/security.c (ffffffff820e2f99)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/tomoyo/common.c (ffffffff813cdec1)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff813d152b)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff813d4aa7)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff813f4ffe)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff813f6ba3)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff813faae6)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-mq.c (ffffffff81432f10)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814343ae)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/textsearch.c (ffffffff814812f2)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81900bd0)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8154d5d6)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff815cbec7)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff815dcc62)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff8170abd8)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8171023f)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff817113c4)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff817598f8)
Location: include/linux/rculist.h:97
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8175be1d)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8175dfe2)
Location: include/linux/rculist.h:97
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff8175fb03)
Location: include/linux/rculist.h:97
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff817a722a)
Location: include/linux/rculist.h:97
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8210a782)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff817c823f)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff817d84e1)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/fib_rules.c (ffffffff817f3849)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/ipv4/tcp_cong.c (ffffffff8183eb18)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81841e64)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff8186c317)
Location: include/linux/rculist.h:97
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8186ffe1)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff818795f9)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/ip6mr.c (ffffffff818c13cb)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/ipv6/calipso.c (ffffffff818c8d0c)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff818d9948)
Location: include/linux/rculist.h:97
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff818da75f)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dca03)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff818e8aaa)
Location: include/linux/rculist.h:97
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff818eabd5)
Location: include/linux/rculist.h:97
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103153f)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff8108982d)
Location: include/linux/rculist.h:98
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a9861)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
```
In kernel/sched/fair.c (ffffffff810c49ca)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810e94b5)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81134249)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81144fbc)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/kprobes.c (ffffffff8114f565)
Location: include/linux/rculist.h:98
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81192538)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198fd8)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/core.c (ffffffff8119d5a6)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811af569)
Location: include/linux/rculist.h:98
Inline: True
```
```
In mm/backing-dev.c (ffffffff811f7c36)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8122063f)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8122dd6c)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff812c2bf2)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/ext4/mballoc.c (ffffffff8133304a)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/security.c (ffffffff826ebc52)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In security/tomoyo/common.c (ffffffff813f4361)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff813f79eb)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff813fafb7)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff8141d1be)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8141ecc3)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81422f86)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-mq.c (ffffffff8145eaca)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff8146003a)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff8149b5c9)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff814bd142)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff8198abd0)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff815b0bc4)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff81632c97)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff81643c62)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff8177bd98)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff817814bf)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81782644)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff817cbb39)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff817ce06d)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff817d0052)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff817d1b91)
Location: include/linux/rculist.h:98
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181e48a)
Location: include/linux/rculist.h:98
Inline: True
```
```
In net/core/net_namespace.c (ffffffff82714124)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81841ddf)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81852be1)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff8185a109)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff8186a6e3)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8186edf9)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/ipv4/tcp_cong.c (ffffffff818be368)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff818c1734)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff818ecbe0)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f0991)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa049)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81911877)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81944603)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/ipv6/calipso.c (ffffffff8194c3ac)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8195f538)
Location: include/linux/rculist.h:98
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8196033f)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819625f3)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff8196dfae)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff8196ee1a)
Location: include/linux/rculist.h:98
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
In arch/x86/kernel/nmi.c (ffffffff8103248f)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff8108d1e5)
Location: include/linux/rculist.h:98
Inline: True
```
```
In kernel/workqueue.c (ffffffff810aff90)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
```
In kernel/sched/fair.c (ffffffff810cc285)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810f1790)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81142878)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff811538cf)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/kprobes.c (ffffffff8115df75)
Location: include/linux/rculist.h:98
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811a2151)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6af3)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae6b0)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/core.c (ffffffff811b1cd9)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811c9db5)
Location: include/linux/rculist.h:98
Inline: True
```
```
In mm/backing-dev.c (ffffffff81218f76)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81242433)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81250149)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff812ebaca)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (ffffffff81364420)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In security/tomoyo/common.c (ffffffff814252f0)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff814289ba)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff8142bf29)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff8144f489)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff81450f76)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81455568)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81457b54)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff8149241f)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff8149390a)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff814d0879)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff814ef958)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff819e7516)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff815e9028)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff8166deff)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff8167f08d)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/input/input.c (ffffffff817bce56)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff817c26ed)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff817c38a4)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff8181490f)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81816e68)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81818d12)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff8181a921)
Location: include/linux/rculist.h:98
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8186879a)
Location: include/linux/rculist.h:98
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81887796)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff8188f89b)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8189e2fa)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff818a5989)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff818ba481)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff818c0bf5)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/ipv4/tcp_cong.c (ffffffff81913f86)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81917349)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff819429d3)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819472f2)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81950c89)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81968ca8)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff8199f255)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff819a65e7)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819b8c9d)
Location: include/linux/rculist.h:98
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819b9b17)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bbe79)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff819c7b47)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff819c8513)
Location: include/linux/rculist.h:98
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
In arch/x86/kernel/nmi.c (ffffffff8103374f)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff81094f19)
Location: include/linux/rculist.h:98
Inline: True
```
```
In kernel/workqueue.c (ffffffff810b9100)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
```
In kernel/sched/fair.c (ffffffff810d42d6)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810fce40)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff8114e319)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81160685)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b0f8b)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b4f53)
Location: include/linux/rculist.h:98
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcd20)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/core.c (ffffffff811c0589)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811dd6b5)
Location: include/linux/rculist.h:98
Inline: True
```
```
In mm/backing-dev.c (ffffffff8122bea5)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81256b64)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81264619)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff812ffd0a)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (ffffffff8137c6c3)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In security/tomoyo/common.c (ffffffff81441960)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81445280)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff8144885b)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff8146c469)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8146df56)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81472948)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81475046)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814abf5c)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814adc1a)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff814e51a9)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff81503878)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81a22986)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81602e23)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff8168c32f)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff8169f4cd)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/input/input.c (ffffffff817e4296)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff817ea1fd)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff817eaf14)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff81840925)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81842739)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818445b2)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff81846111)
Location: include/linux/rculist.h:98
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8188882a)
Location: include/linux/rculist.h:98
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818a8036)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818b051b)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff818c0b1a)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff818c8f19)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff818e1301)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff818e8e55)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/ipv4/tcp_cong.c (ffffffff819426e6)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81945b59)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81972a9f)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81978ec2)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819841b9)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff8199e5c8)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff819d5d7c)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff819dd147)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819eff6d)
Location: include/linux/rculist.h:98
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f0de7)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f30dd)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff819ff697)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a00443)
Location: include/linux/rculist.h:98
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
In arch/x86/kernel/nmi.c (ffffffff81035915)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff81099580)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810bec4d)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810ddf6a)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81105530)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81157aa1)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8116cbd4)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bf4a1)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811cba41)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811d1095)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811f2d6f)
Location: include/linux/rculist.h:98
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123bb47)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8126adb6)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8127f5fd)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81320d2e)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (ffffffff813a2f4d)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffffffff8146f530)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81472efd)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff814764a9)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff81499b49)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149b626)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814a0641)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a2d17)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814da1cc)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814dbea5)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff81511bb5)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff815319ca)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81a92a33)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81635561)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816c3efe)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff816d7b60)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/input/input.c (ffffffff81824cc7)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8182a7f0)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8182ba6e)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff81883756)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8188558b)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81887071)
Location: include/linux/rculist.h:98
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff81888ee0)
Location: include/linux/rculist.h:98
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818d314a)
Location: include/linux/rculist.h:98
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818f3031)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818fd27b)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8190d22a)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff81915ee9)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff8192fafa)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8193889e)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81947503)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6cd6)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819aa154)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff819dc530)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e29e1)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819edd29)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81a0a671)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a44dce)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a4bd5b)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5f154)
Location: include/linux/rculist.h:98
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a600ad)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6244e)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a6e98c)
Location: include/linux/rculist.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a6f695)
Location: include/linux/rculist.h:98
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
In arch/x86/kernel/nmi.c (ffffffff81036025)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff8109fb7a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810c524d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810e8647)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff811118b0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81163711)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81178c93)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cacf1)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811d7a8b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811dd625)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811ffb31)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124a00c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81279ccf)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8128f05d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81333ace)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (ffffffff813bbdad)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffffffff81489330)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8148cc9d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff81490249)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff814b3d49)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff814b5866)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814bacbd)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814bd9e7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814f357d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814f52d5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff815325f5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff8155285a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81aca1f3)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8165727d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816e6e4e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff816fbc45)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff81856147)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8185c180)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8185d3e2)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff818b5673)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b752b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818b9031)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff818bae90)
Location: include/linux/rculist.h:116
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff819054ca)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81924f97)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff8192f88b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8193f92a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff819484f9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81961d6d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8196b75e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff8197c64f)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (ffffffff819dd9a6)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819e0e14)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81a13520)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a199d1)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a24bd9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81a41324)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b9be)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a8292b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a95d84)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a96cdd)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9902e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81aa535c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81aa5ef5)
Location: include/linux/rculist.h:116
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
In arch/x86/kernel/nmi.c (ffffffff81038034)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810a6c11)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810ccbd3)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810f265a)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff8111cf50)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff811749a0)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/auditfilter.c (ffffffff8118aaaa)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e6ae6)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f442b)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811f9f60)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff81226c02)
Location: include/linux/rculist.h:126
Inline: True
```
```
In kernel/events/core.c (ffffffff81235493)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/backing-dev.c (ffffffff812781c1)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff812aa3b0)
Location: include/linux/rculist.h:126
Inline: True
```
```
In mm/zswap.c (ffffffff812c1cc7)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8136dfdf)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io-wq.c (ffffffff8138a884)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
```
```
In fs/ext4/mballoc.c (ffffffff81407296)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
```
```
In security/tomoyo/common.c (ffffffff814e09e0)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff814e3f2c)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff814e75a6)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff815132d9)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff81514f06)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff8151aada)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:restore_template_fmt
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8151e2d8)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff81553ad0)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff81555cda)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/textsearch.c (ffffffff815dbc3a)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/logic_pio.c (ffffffff815ed117)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81bc2843)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81708467)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179d6f3)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff817b5436)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff819284d7)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8192eaa0)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff819315b1)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff819863a0)
Location: include/linux/rculist.h:126
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81987f3f)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:add_mc_to_global_list
```
```
In drivers/edac/edac_device.c (ffffffff819895ad)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:add_edac_dev_to_global_list
```
```
In drivers/edac/edac_pci.c (ffffffff8198b56d)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:add_edac_pci_to_global_list
```
```
In net/core/net_namespace.c (ffffffff819f9582)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff819ffa37)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81a0f32a)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff81a18339)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81a3536e)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81a3f31e)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81a544d4)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81a6c49e)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/ipv4/tcp_cong.c (ffffffff81acaa7e)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ace454)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81b03992)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b01e)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16809)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81b36d4a)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b7679e)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81b7dc0b)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81b91504)
Location: include/linux/rculist.h:126
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b924ad)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b94cd5)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81ba0e2c)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba1cf3)
Location: include/linux/rculist.h:126
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
In net/mptcp/pm_netlink.c (ffffffff81bb3b23)
Location: include/linux/rculist.h:126
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bb59da)
Location: include/linux/rculist.h:126
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
In arch/x86/kernel/nmi.c (ffffffff81038b74)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810a272e)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810c7d53)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810f0802)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81117a20)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff8117168b)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/auditfilter.c (ffffffff81187d0a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e44a6)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f2ddb)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811f8f90)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8122d6f3)
Location: include/linux/rculist.h:134
Inline: True
```
```
In kernel/events/core.c (ffffffff8123df43)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/backing-dev.c (ffffffff81282952)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff812b5a5a)
Location: include/linux/rculist.h:134
Inline: True
```
```
In mm/zswap.c (ffffffff812cd8a7)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/io-wq.c (ffffffff8139b5c9)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
```
```
In fs/ext4/mballoc.c (ffffffff8141a4e6)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
```
```
In security/tomoyo/common.c (ffffffff814fde10)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8150135c)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff81504976)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff81530429)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff81531f76)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81537a3a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:restore_template_fmt
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8153b0a8)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8157252a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/textsearch.c (ffffffff815f988a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/logic_pio.c (ffffffff816118d7)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81c3b89b)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81725687)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab413)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff817c9bc8)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff8192fa07)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81935e40)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81938872)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff8198a3da)
Location: include/linux/rculist.h:134
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198be6f)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:add_mc_to_global_list
```
```
In drivers/edac/edac_device.c (ffffffff8198d31d)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:add_edac_dev_to_global_list
```
```
In drivers/edac/edac_pci.c (ffffffff8198f15d)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:add_edac_pci_to_global_list
```
```
In net/core/net_namespace.c (ffffffff819f93a2)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff819ff797)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81a0f6ba)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff81a18409)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81a376f6)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81a41dce)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81a5b434)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81a74e3e)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad6a13)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ada464)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81b11b07)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b193fe)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b249b9)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81b45a7a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b85563)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81b8cd34)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba1219)
Location: include/linux/rculist.h:134
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81ba211d)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4940)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81bb0740)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81bb1583)
Location: include/linux/rculist.h:134
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
In net/mptcp/pm_netlink.c (ffffffff81bc8497)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bcab8a)
Location: include/linux/rculist.h:134
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
In arch/x86/kernel/nmi.c (ffffffff8103a684)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810a3417)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810c97e3)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810ed1e3)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
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
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81118100)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff811722b9)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/auditfilter.c (ffffffff81188d6a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e5a86)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f3c5b)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811f9d70)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8123280a)
Location: include/linux/rculist.h:134
Inline: True
```
```
In kernel/events/core.c (ffffffff81241183)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/backing-dev.c (ffffffff81287a77)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff812bb14a)
Location: include/linux/rculist.h:134
Inline: True
```
```
In mm/zswap.c (ffffffff812d4324)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/io-wq.c (ffffffff813a2842)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
```
```
In fs/ext4/mballoc.c (ffffffff81424bd3)
Location: include/linux/rculist.h:134
Inline: True
```
```
In security/tomoyo/common.c (ffffffff815049d0)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81507e3d)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff8150b4f6)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff81536629)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8153a346)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff815407c0)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8154377d)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8157a54a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/textsearch.c (ffffffff815dc47a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/logic_pio.c (ffffffff815f4fbe)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81c2e05b)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81706927)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e1b2)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff817ad3c1)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff81912d87)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81919e00)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8191c0e1)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff8196e98c)
Location: include/linux/rculist.h:134
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8197068e)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81971c11)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff819737d0)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In net/core/net_namespace.c (ffffffff819dea15)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff819e5f77)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff819f652a)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff819ff2d9)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81a1e856)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81a26a9e)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81a3db14)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81a5d98e)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac1a9e)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81ac5474)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81b003b6)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06e7e)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b125d9)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81b3386f)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81b740d9)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81b7bbe4)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81b90387)
Location: include/linux/rculist.h:134
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b911fd)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b935cb)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81b9f840)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba05b3)
Location: include/linux/rculist.h:134
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
In net/mptcp/pm_netlink.c (ffffffff81bb8659)
Location: include/linux/rculist.h:134
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bbe4ca)
Location: include/linux/rculist.h:134
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
In arch/x86/kernel/nmi.c (ffffffff8104003b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810b4ba5)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810dc717)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff81105e93)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
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
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81138bea)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81198da9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/auditfilter.c (ffffffff811b1311)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/trace/trace_eprobe.c (ffffffff8120a21b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff81216888)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff81224fab)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff8122b440)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8126bb5c)
Location: include/linux/rculist.h:125
Inline: True
```
```
In kernel/events/core.c (ffffffff8127bba7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/backing-dev.c (ffffffff812c7219)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff812fd754)
Location: include/linux/rculist.h:125
Inline: True
```
```
In mm/zswap.c (ffffffff8131a02f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/io-wq.c (ffffffff813f1252)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - fs/io-wq.c:io_init_new_worker
```
```
In fs/ext4/mballoc.c (ffffffff81478865)
Location: include/linux/rculist.h:125
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81561829)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8156504a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff81568d52)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff81594d59)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff81598cc6)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff8159fff1)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff815a3edb)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff815df8f0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/textsearch.c (ffffffff81647d4a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/logic_pio.c (ffffffff816623de)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81d4c97a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff817821e7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff81815a42)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff818366b0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff819b4da7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff819bc200)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff819be7ca)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff81a1722b)
Location: include/linux/rculist.h:125
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81a18fae)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81a1a8c1)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c4d0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In net/core/net_namespace.c (ffffffff81a8e817)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81a96496)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81aa813d)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81ab14c9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81ad28f6)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81adb84e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81af3f74)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81b16b1e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/ipv4/tcp_cong.c (ffffffff81b7f7ce)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81b83c84)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81bc24a6)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9cee)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd64a9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81bf9edf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e988)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81c468e4)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5cb27)
Location: include/linux/rculist.h:125
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81c5d99d)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5fd6b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81c6d0a0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6df56)
Location: include/linux/rculist.h:125
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
In net/mptcp/pm_netlink.c (ffffffff81c88409)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81c8e40a)
Location: include/linux/rculist.h:125
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
In arch/x86/kernel/nmi.c (ffffffff8104774f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810cb07a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810f5deb)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff811209a6)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
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
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff8115b605)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff811c8f34)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/auditfilter.c (ffffffff811e35db)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/trace/trace_eprobe.c (ffffffff81246166)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff81254ea7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
```
In kernel/trace/trace_probe.c (ffffffff81264e7b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff8126ce90)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff812ba95e)
Location: include/linux/rculist.h:125
Inline: True
```
```
In kernel/events/core.c (ffffffff812cf90b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/backing-dev.c (ffffffff8132449b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff8136469d)
Location: include/linux/rculist.h:125
Inline: True
```
```
In mm/zswap.c (ffffffff81385018)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/ext4/mballoc.c (ffffffff814fb050)
Location: include/linux/rculist.h:125
Inline: True
```
```
In security/tomoyo/common.c (ffffffff815fc84d)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81600834)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff81604a92)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff81636ed7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8163d6e8)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81645c0f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_buf
  - security/integrity/ima/ima_template.c:ima_template_desc_current
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8164a8f7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8168e043)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In io_uring/io-wq.c (ffffffff816d9645)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
```
```
In lib/textsearch.c (ffffffff8175e029)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In lib/logic_pio.c (ffffffff8177c11e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In drivers/acpi/osl.c (ffffffff81f1c4bf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff818b8bba)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff819568a5)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff819786b9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff81b14123)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81b1be9d)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81b1d60a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff81b7ff22)
Location: include/linux/rculist.h:125
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81d79)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81b83661)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81b85590)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81bba559)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In net/core/net_namespace.c (ffffffff81c0472b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81c0d337)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81c200d8)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81c2a669)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81c5036c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81c5cd1a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81c78221)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81c9e250)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0f9ed)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81d14434)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81d57252)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f3a7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6cc59)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81d932d4)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd0f3)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81de5372)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81dfe92c)
Location: include/linux/rculist.h:125
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81dffa39)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0211e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81e10aaf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e11a1d)
Location: include/linux/rculist.h:125
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
In net/mptcp/pm_netlink.c (ffffffff81e2f539)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35365)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81e3d521)
Location: include/linux/rculist.h:125
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
In arch/x86/kernel/nmi.c (ffffffff8105217f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810e8626)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff81118336)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff8115340e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff8118db85)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff8120bfc9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/auditfilter.c (ffffffff812299fb)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/trace/trace_eprobe.c (ffffffff812930cc)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a433d)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
```
In kernel/trace/trace_probe.c (ffffffff812b6a2b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff812c1fc0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8131daeb)
Location: include/linux/rculist.h:125
Inline: True
```
```
In kernel/events/core.c (ffffffff81339616)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/backing-dev.c (ffffffff81398dcb)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff813e01ee)
Location: include/linux/rculist.h:125
Inline: True
```
```
In mm/zswap.c (ffffffff81402ce0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/ext4/mballoc.c (ffffffff815957dd)
Location: include/linux/rculist.h:125
Inline: True
```
```
In security/tomoyo/common.c (ffffffff816ad5cd)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff816b1774)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff816b5d92)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff816ee0e7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff816f5218)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff816fe0f1)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81703a47)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff8174c961)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In io_uring/io-wq.c (ffffffff817a54f5)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
```
```
In lib/textsearch.c (ffffffff8188b6d9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff820c44ef)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81a06115)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abd6e5)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff81ae4f73)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff81ca5153)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81cadcdd)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81caf5ea)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff81d1d63a)
Location: include/linux/rculist.h:125
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81d204cd)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81d22161)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81d245f0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81d5fa99)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In net/core/net_namespace.c (ffffffff81db41fb)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81dbcf57)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81dd204c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81ddd3d9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81e0571c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81e1344a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff81e30ca4)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/devlink.c:devl_dpipe_table_register
```
```
In net/sched/cls_api.c (ffffffff81e5a980)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed562a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81eda4d4)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81f208ef)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29a47)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38029)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81f61a64)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81fae578)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81fb7b42)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd359c)
Location: include/linux/rculist.h:125
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81fd47b9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6fde)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81fe726f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fe83dd)
Location: include/linux/rculist.h:125
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
In net/mptcp/pm_netlink.c (ffffffff82007cc4)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8200dff9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82016941)
Location: include/linux/rculist.h:125
Inline: True
```
```
In lib/logic_pio.c (ffffffff8202539e)
Location: include/linux/rculist.h:125
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
In arch/x86/kernel/nmi.c (ffffffff81052edf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810f4285)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff8112553c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff81162cd3)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff8119f335)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff812215d9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/auditfilter.c (ffffffff8123ffbb)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296c35)
Location: include/linux/rculist.h:125
Inline: True
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b026c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff812c2200)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
```
In kernel/trace/trace_probe.c (ffffffff812d9f1b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff812e8e80)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff8134d8b9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_alloc
```
```
In mm/backing-dev.c (ffffffff813cbd2b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff81414f9a)
Location: include/linux/rculist.h:125
Inline: True
```
```
In mm/zswap.c (ffffffff81436271)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/ext4/mballoc.c (ffffffff815c6b1d)
Location: include/linux/rculist.h:125
Inline: True
```
```
In security/tomoyo/common.c (ffffffff816e5fed)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff816ea17e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff816ee7a2)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff81728577)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8172f318)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81738111)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8173da77)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff81789097)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In io_uring/io-wq.c (ffffffff817e64d3)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
```
```
In lib/textsearch.c (ffffffff818cdbb9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff821482cf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81a4efd5)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a03c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff81b33315)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff81d0c883)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81d152cd)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81d16bea)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff81d8682f)
Location: include/linux/rculist.h:125
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81d896ad)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81d8b35f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81d8d800)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81dcaba0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In net/core/net_namespace.c (ffffffff81e248ab)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81e2d787)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81e42c1c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81e4e129)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81e77f6c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81e86d8a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/sched/cls_api.c (ffffffff81eb67c0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/ipv4/tcp_cong.c (ffffffff81f347a2)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81f395b4)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81f8110f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89606)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f97a19)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81fc1889)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff8200f9f8)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff820182e2)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/devlink/leftover.c (ffffffff82033714)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_dpipe_table_register
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8204f1ff)
Location: include/linux/rculist.h:125
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff82050409)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052cce)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff820634bf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff8206465d)
Location: include/linux/rculist.h:125
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
In net/mptcp/pm_netlink.c (ffffffff82084044)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8208a8dd)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82096cf1)
Location: include/linux/rculist.h:125
Inline: True
```
```
In lib/logic_pio.c (ffffffff820a54ae)
Location: include/linux/rculist.h:125
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
In arch/x86/kernel/nmi.c (ffffffff8105a0ff)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810fd64d)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff8112fbc8)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff8116f78e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff811ae515)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff812392cf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/auditfilter.c (ffffffff81259e3b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_add_rule
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2284)
Location: include/linux/rculist.h:125
Inline: True
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cc7dd)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_hist.c (ffffffff812de937)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
```
In kernel/trace/trace_probe.c (ffffffff812f7eab)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff813071f0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/devmap.c (ffffffff81374dd9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_alloc
```
```
In mm/shrinker.c (ffffffff813e3a7a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_register
```
```
In mm/backing-dev.c (ffffffff813f669b)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:cgwb_create
```
```
In mm/vmalloc.c (ffffffff81441a69)
Location: include/linux/rculist.h:125
Inline: True
```
```
In mm/zswap.c (ffffffff8146fcb3)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/ext4/mballoc.c (ffffffff81601284)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffffffff81722c9d)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81726e8e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff8172b572)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff817698a7)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8176fca6)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff81778c30)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8177e8d6)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-stat.c (ffffffff817cb7fd)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In io_uring/io-wq.c (ffffffff8182c293)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
```
```
In lib/textsearch.c (ffffffff8191f619)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff8222ac5e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff81a9ac75)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e08c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff81b8ac54)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff81dc2513)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81dcaf1c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81dcc89a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff81e3df4d)
Location: include/linux/rculist.h:125
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81e40ded)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81e42bdf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
```
In drivers/edac/edac_pci.c (ffffffff81e450b0)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/leds/led-triggers.c (ffffffff81e83710)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In net/core/net_namespace.c (ffffffff81ee24fb)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81eebabf)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/dev_addr_lists.c (ffffffff81f0186c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/core/rtnetlink.c (ffffffff81f0ce89)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81f37f2c)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff81f48d9a)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/sched/cls_api.c (ffffffff81f7960d)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa922)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81fff6a4)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff8204778f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050d66)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff82064d89)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff8208ed9e)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff820de988)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff820e72b2)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/devlink/dpipe.c (ffffffff8210aa03)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devl_dpipe_table_register
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8212187f)
Location: include/linux/rculist.h:125
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff82122ab9)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8212550f)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff821365ff)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff8213779d)
Location: include/linux/rculist.h:125
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
In net/mptcp/pm_netlink.c (ffffffff821596a3)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff821604a2)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mptcp/sched.c (ffffffff82161c98)
Location: include/linux/rculist.h:125
Inline: True
Inline callers:
  - net/mptcp/sched.c:mptcp_register_scheduler
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8216e161)
Location: include/linux/rculist.h:125
Inline: True
```
```
In lib/logic_pio.c (ffffffff8217d60e)
Location: include/linux/rculist.h:125
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
In kernel/fork.c (ffff8000100f40dc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffff800010123730)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffff8000101476c4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffff8000101731d0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffff8000101d4ea8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffff8000101edd98)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (ffff80001024a13c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffff800010257e0c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffff80001025e220)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffff800010286bc4)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (ffff8000102de0a0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffff800010310e94)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffff80001032bce8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffff8000103f1878)
Location: include/linux/rculist.h:116
Inline: True
```
```
In fs/ext4/mballoc.c (ffff800010492914)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffff80001057c508)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffff800010580188)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffff800010584418)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffff8000105abbe0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffff8000105adcdc)
Location: include/linux/rculist.h:116
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffff8000105b3134)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffff8000105b68c8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffff8000105f2d7c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffff8000105f53a0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffff80001063ec04)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffff80001065e68c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffff800010d9da18)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffff8000107fd50c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/core.c (ffff8000108e6574)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffff800010a9518c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffff800010a9c618)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffff800010a9e2e8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffff800010b0d414)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (ffff800010b0f644)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffff800010b11154)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (ffff800010b134c8)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (ffff800010bc0a88)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffff800010bcb7e0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffff800010bde998)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffff800010bea0b8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffff800010c05b28)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffff800010c12acc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffff800010c24230)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (ffff800010c90d9c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffff800010c94cec)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffff800010ccdc38)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5784)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3f44)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffff800010d02e6c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffff800010d456dc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffff800010d4e1a8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffff800010d64c94)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffff800010d661ac)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68920)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffff800010d77ad4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffff800010d7890c)
Location: include/linux/rculist.h:116
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
In kernel/fork.c (c0352b84)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (c0377008)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (c0395bc0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (c03c4760)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (c0417a14)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (c042dee4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_probe.c (c048af38)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (c04918b8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (c04b719c)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (c0502c0c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (c052cd58)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (c0541d9c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (c05c722c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (c0653c08)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (c072ecfc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (c073267c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (c0735ea0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (c075b6f8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (c075d3cc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (c0762744)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (c076588c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (c079eecc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (c07a0ee4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (c07e42dc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (c0807f74)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/dma/dmaengine.c (c091ebf4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/core.c (c09d4b9c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (c0b77e08)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (c0b7e4e4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (c0b7f2b0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (c0beb5d0)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (c0bed91c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (c0bef5c0)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (c0bf145c)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (c0cdcd70)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (c0ce8798)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (c0cf95fc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (c0d02a28)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (c0d1eb84)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (c0d298d4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (c0d3b720)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (c0d9fb0c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (c0da3554)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (c0dd8bd4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (c0ddf670)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (c0deb15c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (c0e09ab4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (c0e48114)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (c0e4e3f4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (c0e6374c)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (c0e64a4c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (c0e67018)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (c0e73b40)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (c0e747c8)
Location: include/linux/rculist.h:116
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
In kernel/fork.c (c00000000013a4c0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (c00000000016d718)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (c000000000199d40)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (c0000000001ca698)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (c000000000244224)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (c000000000260820)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (c0000000002e4fb4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (c0000000002f9e7c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (c000000000302ef0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (c000000000332014)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (c00000000039f2cc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (c0000000003e1d4c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (c000000000403bd0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (c0000000004f90b4)
Location: include/linux/rculist.h:116
Inline: True
```
```
In fs/ext4/mballoc.c (c0000000005bafb4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (c0000000006e78b4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (c0000000006eda14)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (c0000000006f3658)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (c000000000729ce4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (c00000000072c86c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (c0000000007357b8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (c00000000073ac5c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (c00000000078a2d4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (c00000000078cf50)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (c0000000007e82ec)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (c000000000810bf4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/dma/dmaengine.c (c0000000008c88c8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/core.c (c00000000097c2d0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (c000000000b741d8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (c000000000b7d4c0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (c000000000b7e9a8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (c000000000bffdb8)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (c000000000c02c34)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (c000000000c0509c)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (c000000000c07f6c)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (c000000000c9ad8c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (c000000000caaad4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (c000000000cbf28c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (c000000000ccc4c0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (c000000000cefdf8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (c000000000cfe808)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (c000000000d1b188)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (c000000000da03c0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (c000000000da5888)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (c000000000dea518)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (c000000000df4e38)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (c000000000e04bac)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (c000000000e2a7f4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (c000000000e7b118)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (c000000000e83cc8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (c000000000ea0ae0)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (c000000000ea2288)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea539c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (c000000000eb7208)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (c000000000eb8274)
Location: include/linux/rculist.h:116
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
In kernel/fork.c (ffffffe0000c0852)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffe0000dbdf6)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffe0000f2e8e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffe00010e052)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffe00014e278)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffe000162246)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/bpf/core.c (ffffffe00019c6c2)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffe0001bbfba)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (ffffffe0001f7458)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffe000218bda)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffe00022a8bc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffe0002a4118)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (ffffffe000317580)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffffffe0003cdc88)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffe0003d0e40)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffe0003d4450)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffe0003f45d6)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffe0003f6046)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffe0003fa772)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffe0003fd4de)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffe00043157a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffe0004330e4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffe00046bace)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffe00048c036)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/dma/dmaengine.c (ffffffe00051715e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/core.c (ffffffe00057afce)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffe0006a6f58)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffe0006acdae)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffe0006adf78)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffe0006faa80)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffe0006fc754)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffe0006fe0bc)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffe0006fff0c)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (ffffffe00074e982)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffe0007574c8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffe000765892)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffe00076d95a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffe0007842aa)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffe00078de0c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffe00079c802)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0c6c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffe0007f401e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffe00081ffa0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008263a2)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffe0008309f6)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffe00084c120)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffe0008808de)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffe000887350)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffe000898c5c)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffe000899cac)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089bbe8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffe0008a71a8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffe0008a7c40)
Location: include/linux/rculist.h:116
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
In arch/x86/kernel/nmi.c (ffffffff81036185)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff8109949a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810bf5bd)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810e27f7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81109e90)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff8115bd31)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff811712b3)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c3311)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811d00ab)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811d5c45)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811f8151)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124265c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8127231f)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8128763d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8132c0ae)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (ffffffff813b438d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffffffff81481910)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8148527d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff81488829)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff814ac329)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff814ade46)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814b329d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b5fc7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814ebb5d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814ed8b5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff8152abd5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff8154ae3a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81a69063)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8161d11d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816ac92e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff816c1435)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff8180b157)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81811190)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff818123f2)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff8185b4f3)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8185d3ab)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8185eeb1)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff81860d10)
Location: include/linux/rculist.h:116
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818a488a)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818c4f97)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818cf88b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff818df8fa)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff818e84c9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81901d3d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8190b72e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff8191c4bf)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (ffffffff8197d816)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff81980c84)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff819b2d20)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b9061)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4269)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff819e09b4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b04e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a21fbb)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81a35114)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a3606d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a383be)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a446ec)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a45285)
Location: include/linux/rculist.h:116
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
In arch/x86/kernel/nmi.c (ffffffff81025ad5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff81087eea)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810adddd)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810d1834)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff810fad70)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f01b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff81164453)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b60f1)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811c2e7b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811c8a05)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811eaea1)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123562c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8126428f)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8127949d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8131d41e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (ffffffff813a4e1d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffffffff81472330)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81475c9d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff81479249)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff8149cd49)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149e866)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814a3cbd)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a69e7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814dc0ad)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814dde05)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff8151aeb5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff8153b11a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81a25b23)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8161180d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff8168a28e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff8169c6e5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/net/vxlan.c (ffffffff8176eff1)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
```
```
In drivers/input/input.c (ffffffff817d28c7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff817d88d0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff817d9b32)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff81822abd)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8182497b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81826481)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff818282e0)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852d1c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8186004a)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8187eed7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818899ab)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8189973a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff818a2309)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff818bbb6d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff818c54ee)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff818d626f)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (ffffffff819372d6)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff8193a744)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff8196f350)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81975e51)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81981059)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff8199d774)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff819d7e0e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff819ded7b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff819f1d34)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f2c8d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4fde)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a012dc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a01e75)
Location: include/linux/rculist.h:116
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
In arch/x86/kernel/nmi.c (ffffffff81035fe5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff8109944a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810beb1d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810deb77)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81107d80)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81159b01)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8116f083)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c10e1)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811cde7b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811d3a15)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff811f5f21)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (ffffffff812403fc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff812700bf)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff8128544d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff81329b7e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/ext4/mballoc.c (ffffffff813b1bed)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffffffff8147d9b0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff8148131d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff814848c9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff814a83c9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff814a9ee6)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814af32d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b2057)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff814e7bed)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff814e9945)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff81526c65)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff81546b7a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81ad5473)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8164b0bd)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816dab0e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff816ef905)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff8184a2d7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff81850310)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81851572)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff818aab23)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818ac9db)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818ae4e1)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff818b0340)
Location: include/linux/rculist.h:116
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818f5eea)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81915f97)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff8192088b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff8193092a)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff819394f9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81952d6d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8195c75e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff8196d64f)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (ffffffff819e7fe6)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819eb454)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81a1d5c0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23ae1)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2ece9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81a4b434)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a85ace)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a8ca3b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa0fc4)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aa1f1d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa426e)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81ab059c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ab1135)
Location: include/linux/rculist.h:116
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
In arch/x86/kernel/nmi.c (ffffffff81036fc5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In kernel/fork.c (ffffffff810a1083)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffff810c6e8d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
```
```
In kernel/sched/fair.c (ffffffff810ea687)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/printk/printk.c (ffffffff81113120)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81166b68)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
```
In kernel/auditfilter.c (ffffffff8117c873)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cf181)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_probe.c (ffffffff811dc0db)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/bpf/core.c (ffffffff811e1d05)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/devmap.c (ffffffff81204481)
Location: include/linux/rculist.h:116
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124faf7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff8127fadc)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/zswap.c (ffffffff81295592)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In fs/eventpoll.c (ffffffff8133bfe8)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/ext4/mballoc.c (ffffffff813c6733)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
```
In security/tomoyo/common.c (ffffffff814954d0)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_init_policy_namespace
```
```
In security/tomoyo/domain.c (ffffffff81498e8d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
```
```
In security/tomoyo/memory.c (ffffffff8149c409)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
```
```
In security/device_cgroup.c (ffffffff814c0d79)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/device_cgroup.c:dev_exception_add
```
```
In security/integrity/ima/ima_queue.c (ffffffff814c2936)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_template.c (ffffffff814c7dad)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814caad7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/blk-mq.c (ffffffff81500b8d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-stat.c (ffffffff81502915)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
```
```
In lib/logic_pio.c (ffffffff815405e5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_register_range
```
```
In lib/textsearch.c (ffffffff815609da)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_register
```
```
In drivers/acpi/osl.c (ffffffff81ae1928)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/dma/dmaengine.c (ffffffff8166565d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/dmar.c (ffffffff816f50be)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/base/core.c (ffffffff8170a145)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/input/input.c (ffffffff818654a7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_handle
```
```
In drivers/input/mousedev.c (ffffffff8186b030)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff8186c392)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff818c6753)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c8c2b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818ca771)
Location: include/linux/rculist.h:116
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffff818cc5d0)
Location: include/linux/rculist.h:116
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81916fda)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81937197)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff8194261b)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffffffff81951ffa)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create_ex
```
```
In net/core/rtnetlink.c (ffffffff8195abd9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
```
```
In net/core/fib_notifier.c (ffffffff81974850)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_ops_register
```
```
In net/core/fib_rules.c (ffffffff8197e977)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/devlink.c (ffffffff8198fa9f)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_register
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1d56)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_ulp.c (ffffffff819f52d4)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/ipmr.c (ffffffff81a28782)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_new_table_set
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2eec6)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a1a9)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_register_km
```
```
In net/ipv6/addrconf.c (ffffffff81a574c5)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6mr.c (ffffffff81a925f7)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_new_table_set
```
```
In net/ipv6/calipso.c (ffffffff81a98691)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81aad28c)
Location: include/linux/rculist.h:116
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aae28d)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab05ff)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/ncsi/ncsi-aen.c (ffffffff81abc94c)
Location: include/linux/rculist.h:116
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffffffff81abd4e5)
Location: include/linux/rculist.h:116
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
</details>
</li>
</ul>

## Differences
