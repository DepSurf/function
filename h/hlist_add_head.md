# Function: <code>hlist_add_head</code>

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
In arch/x86/kernel/kvm.c (ffffffff810639a8)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/user.c (ffffffff81f7bddb)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff81099f24)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810a5833)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff810eb928)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/cgroup.c (ffffffff81115a27)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8112ccac)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff811403ab)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:add_hash_entry
  - kernel/trace/ftrace.c:ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff81153f7b)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811897ba)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/mmu_notifier.c (ffffffff811e3be8)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff811e4626)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/huge_memory.c (ffffffff811f789f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/huge_memory.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff8120f918)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/dcache.c (ffffffff812243a2)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:__d_obtain_alias
```
```
In fs/inode.c (ffffffff81226678)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:insert_inode_locked
```
```
In fs/namespace.c (ffffffff8122db9c)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:__detach_mounts
```
```
In fs/pnode.c (ffffffff8123cd5b)
Location: include/linux/list.h:639
Inline: True
```
```
In fs/fs_pin.c (ffffffff81241fe8)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/locks.c (ffffffff8125f9cc)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/quota/dquot.c (ffffffff81271d93)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff812fb40f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8130b597)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In crypto/algapi.c (ffffffff8139e1f4)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff813b3bf3)
Location: include/linux/list.h:639
Inline: True
```
```
In block/blk-ioc.c (ffffffff813bf2c5)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff813d67cb)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff81435de8)
Location: include/linux/list.h:639
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81446f98)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81505484)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/clk/clk.c (ffffffff816e4658)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:__clk_create_clk
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
```
In net/core/flow.c (ffffffff81734911)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_api.c (ffffffff817426c7)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/act_api.c (ffffffff81746d88)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
```
```
In net/netlink/af_netlink.c (ffffffff81749f44)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762a39)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81763385)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff8178434a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff8179ca52)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff817a0446)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1a42)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b217b)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7437)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff817bdba0)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81008666)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/kvm.c (ffffffff81063a75)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/user.c (ffffffff81fa4ba6)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff8109f07f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/sched/core.c (ffffffff810aa283)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff8189e140)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/cgroup.c (ffffffff81fab216)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81135344)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811486af)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff8115d201)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff8119be9a)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/mmu_notifier.c (ffffffff81202664)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81205a37)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8121c9ee)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff812363c0)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/dcache.c (ffffffff8124cf8c)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff81250a35)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff8125638c)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mnt_set_mountpoint
```
```
In fs/pnode.c (ffffffff81264da2)
Location: include/linux/list.h:639
Inline: True
```
```
In fs/fs_pin.c (ffffffff8126a338)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/locks.c (ffffffff8128bb6c)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/quota/dquot.c (ffffffff8129e535)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff8132f0ff)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8133f7f6)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In crypto/algapi.c (ffffffff813db143)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff813f7807)
Location: include/linux/list.h:639
Inline: True
```
```
In block/blk-ioc.c (ffffffff8140321f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff8141c1fe)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff8148191b)
Location: include/linux/list.h:639
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81493148)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81556c87)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/clk/clk.c (ffffffff8174ccac)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In net/core/flow.c (ffffffff817a0b49)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_api.c (ffffffff817af577)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/act_api.c (ffffffff817b4056)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
```
```
In net/netlink/af_netlink.c (ffffffff817b6e57)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf5b0)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf845)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff817f1909)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a5df)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff8180e01f)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/inet_fragment.c (ffffffff8180fdd3)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818214be)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818263b1)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/unix/af_unix.c (ffffffff8182ab10)
Location: include/linux/list.h:639
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff8100869c)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/kvm.c (ffffffff81066f25)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff81089160)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/user.c (ffffffff81fe056b)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810a3f7c)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810ad99a)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810b01d3)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff818d2ff6)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/cgroup.c (ffffffff81fe748c)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8113f0c4)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8115255f)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff81167c71)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811ab876)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/mmu_notifier.c (ffffffff812144a4)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81217a47)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8122efee)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff81249056)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/dcache.c (ffffffff8126004c)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff81263ad5)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff812699ae)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812781e2)
Location: include/linux/list.h:655
Inline: True
```
```
In fs/fs_pin.c (ffffffff8127d2e8)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/locks.c (ffffffff8129f8d0)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/quota/dquot.c (ffffffff812b3e95)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff81344e5f)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff81355576)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In crypto/algapi.c (ffffffff813f2a83)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff81411318)
Location: include/linux/list.h:655
Inline: True
```
```
In block/blk-ioc.c (ffffffff8141cf4f)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff81437340)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff814a2deb)
Location: include/linux/list.h:655
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814b4ad8)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff8153550c)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81583487)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In net/core/flow.c (ffffffff817cf7a9)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_api.c (ffffffff817dec67)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/act_api.c (ffffffff817e38d6)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
```
```
In net/netlink/af_netlink.c (ffffffff817e68d7)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ff3a0)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff635)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81822689)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b6ef)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff8183f464)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/inet_fragment.c (ffffffff81841323)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff81852cce)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818560a2)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/unix/af_unix.c (ffffffff8185c590)
Location: include/linux/list.h:655
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff8100834b)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/kvm.c (ffffffff810661f5)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff81086f71)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff820c13a1)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810a10ae)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810aa582)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810ac429)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff810fe2e8)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff820c7a21)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81142cc1)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8115a1ab)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff8116aeda)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811b2cd6)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/mmu_notifier.c (ffffffff8121f926)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81223637)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff8123a82e)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff8125491a)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/dcache.c (ffffffff8126d95b)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff81271517)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff8127714e)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812854fb)
Location: include/linux/list.h:668
Inline: True
```
```
In fs/fs_pin.c (ffffffff8128ae78)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/locks.c (ffffffff812ae740)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/quota/dquot.c (ffffffff812c102c)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff813598d9)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8136a176)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In crypto/algapi.c (ffffffff813fed43)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff8141e9e8)
Location: include/linux/list.h:668
Inline: True
```
```
In block/blk-ioc.c (ffffffff8142afaf)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff814446d7)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff814acbfd)
Location: include/linux/list.h:668
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814bf0b4)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff81548884)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815978a8)
Location: include/linux/list.h:668
Inline: True
```
```
In drivers/dax/super.c (ffffffff8163ccc1)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/flow.c (ffffffff817eeb27)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_api.c (ffffffff817fe297)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/act_api.c (ffffffff818032c6)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
```
```
In net/netlink/af_netlink.c (ffffffff81806665)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f5f2)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f865)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff818432d9)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff8185cff3)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff818609ed)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/inet_fragment.c (ffffffff81862b97)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff81876962)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81879d02)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/unix/af_unix.c (ffffffff81880ac7)
Location: include/linux/list.h:668
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff810086a3)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105b140)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a045)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff8108dc88)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff826c9592)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810a7929)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b0de2)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810b3209)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff81108b78)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff826d0087)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8114f971)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff81166cbb)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff81177fba)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811c6926)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/mmu_notifier.c (ffffffff8123ab36)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8123ec77)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff8125a0be)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff81276a96)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/dcache.c (ffffffff812903fb)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff81293e39)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff81299b8e)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812a7f7b)
Location: include/linux/list.h:669
Inline: True
```
```
In fs/fs_pin.c (ffffffff812ad9b8)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/locks.c (ffffffff812d20b2)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff812e4d81)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff8137e5e9)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8138ed36)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In crypto/algapi.c (ffffffff81427303)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff814494b4)
Location: include/linux/list.h:669
Inline: True
```
```
In block/blk-ioc.c (ffffffff8145619f)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff81471607)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff814ebfcd)
Location: include/linux/list.h:669
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814ff434)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff815abcc4)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815fc4e2)
Location: include/linux/list.h:669
Inline: True
```
```
In drivers/dax/super.c (ffffffff816a5991)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff8187bea7)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff818853a5)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e555)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e7d5)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff818c2c9f)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd013)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff818e0a6d)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2cce)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f6740)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa762)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/unix/af_unix.c (ffffffff81901c5d)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81008e5e)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105ece8)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8106ce90)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff810915ec)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff826f3772)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810ae4dc)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b7bec)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810ba319)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff811145c7)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff826fa7cd)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8115e4c9)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811759b4)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff811871d7)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811e6e6d)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/mmu_notifier.c (ffffffff8125e1ca)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81262427)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff8127ddef)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff8129d495)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/dcache.c (ffffffff812b5065)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff812ba429)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff812bfa5d)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812cebac)
Location: include/linux/list.h:669
Inline: True
```
```
In fs/fs_pin.c (ffffffff812d5770)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/locks.c (ffffffff812fe567)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff81312483)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff813ae600)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff813bdddd)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In crypto/algapi.c (ffffffff81459f8d)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff8147c0e6)
Location: include/linux/list.h:669
Inline: True
```
```
In block/blk-ioc.c (ffffffff814895df)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff814a55a1)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff8151c1c5)
Location: include/linux/list.h:669
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8152fdae)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff815e3da2)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81635845)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff816e1d7b)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff818ce737)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff818d8d95)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f3084)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f33e8)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81918797)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff81933bb5)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff8193721e)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194d9a3)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8195126d)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/unix/af_unix.c (ffffffff81958704)
Location: include/linux/list.h:669
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81008d7e)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81064da8)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81073060)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff8109425f)
Location: include/linux/list.h:722
Inline: True
```
```
In kernel/cpu.c (ffffffff810998cc)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff828aa55a)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810b763b)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c0ce8)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810c3419)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff8111fe47)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828b16c9)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8116b041)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811835f4)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff81194b47)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811f7a9d)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/mmu_notifier.c (ffffffff81272a45)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81276ca7)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812924cf)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff812b2469)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/dcache.c (ffffffff812c9e65)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff812cf78d)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff812d4c5d)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812e3f1c)
Location: include/linux/list.h:722
Inline: True
```
```
In fs/fs_pin.c (ffffffff812eab40)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/crypto/keyinfo.c (ffffffff813111c1)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:find_or_insert_master_key
```
```
In fs/locks.c (ffffffff8131401b)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff81329003)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff813c77f0)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff813d741d)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In crypto/algapi.c (ffffffff814778fd)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff8149a156)
Location: include/linux/list.h:722
Inline: True
```
```
In block/blk-ioc.c (ffffffff814a3434)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff814bffb1)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff81531795)
Location: include/linux/list.h:722
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff815470ce)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff815fe185)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81653b13)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff8170519b)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff818f9987)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81905585)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81920ab5)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920f08)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81946f67)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff819630cc)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff81966c0e)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980e32)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81984c22)
Location: include/linux/list.h:722
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198d304)
Location: include/linux/list.h:722
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81009209)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810684b8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81076bc8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff810982ac)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109dc3b)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff828c2d47)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810bc9d6)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c6de3)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810c9519)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff8112822a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca36e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81177e3c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff81190373)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff811a2855)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff8120f8dd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/ksm.c (ffffffff81292514)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812acebc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff812cef77)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff812e838c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff812ec6e0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff812f3856)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81302742)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (ffffffff813095b7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keyinfo.c (ffffffff81338546)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:find_or_insert_master_key
```
```
In fs/locks.c (ffffffff8133ad9d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff81350b74)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff813f23af)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff81401d6d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (ffffffff814996c1)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (ffffffff814a559f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff814c822a)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (ffffffff814d150a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff814ee6e5)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff81561132)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8157607e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff8162fbbc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8168851f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff8173eff7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (ffffffff81953198)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/sched/sch_api.c (ffffffff81959177)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81966715)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff8198335d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819838d7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff819ab5e7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9165)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff819ccc91)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff819d5ba7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eabe5)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819eed31)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819f8c80)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81009609)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068df8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81077c18)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff8109e87c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a418b)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff828cb344)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c3726)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810cfeb3)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810d25e9)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff811341ca)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828d28cc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81183d4c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8119c34d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff811ae241)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff8121cf0d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/ksm.c (ffffffff812a2294)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812bdabc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff812e09a7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff812f9f1c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff812fe230)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff81305416)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff813157c2)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (ffffffff8131c627)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e355)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff813532bd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff81368ef4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff8140c2af)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8141bc5d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (ffffffff814b35e1)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (ffffffff814c024f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff814e131a)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (ffffffff814ea8b4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff81507b45)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff815822f2)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8159773e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff81651f7a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816aabb4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff817631d7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (ffffffff81989ccd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_api.c (ffffffff8198f617)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff8199d1a5)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9bd0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba0ca)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff819e22b7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffd2b)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a03806)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81a0c717)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21be5)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25c05)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a2f8d4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff8100a7b9)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106ebb8)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f101)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_queue_task
```
```
In kernel/fork.c (ffffffff810a5f74)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810ab3fb)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff82ced69a)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810cafcc)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d9c2d)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/ucount.c:get_ucounts
```
```
In kernel/sched/core.c (ffffffff810dc4e9)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff81145d23)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf3298)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81197b0c)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811b2468)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff811c6a3c)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff8121f4a8)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/user-return-notifier.c (ffffffff8124928d)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/watch_queue.c (ffffffff8124c8a9)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff812d1b7b)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff812d69a4)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812f32bc)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff81317c37)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff81331850)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/namespace.c (ffffffff8133ed16)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8134f000)
Location: include/linux/list.h:852
Inline: True
```
```
In fs/fs_pin.c (ffffffff81356367)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/io_uring.c (ffffffff8137f2ce)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
```
```
In fs/crypto/keysetup_v1.c (ffffffff81394451)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff81399fcd)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff813b1192)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff8145a35d)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8146a90c)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/selinux/ss/sidtab.c (ffffffff814c0462)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/safesetid/securityfs.c (ffffffff81512a8a)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:verify_ruleset
```
```
In crypto/algapi.c (ffffffff81520e7b)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff8153fd6a)
Location: include/linux/list.h:852
Inline: True
```
```
In block/blk-ioc.c (ffffffff81549854)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff81568c8e)
Location: include/linux/list.h:852
Inline: True
```
```
In block/keyslot-manager.c (ffffffff81581458)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/pci/pci.c (ffffffff81626ca0)
Location: include/linux/list.h:852
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81645b2e)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff817010d1)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175d5ab)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain
```
```
In drivers/dax/super.c (ffffffff8182303c)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/interconnect/core.c (ffffffff819dc715)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6205b)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/sched/sch_api.c (ffffffff81a674e7)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81a763e5)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa4751)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4b5a)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81ad02cf)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef6e3)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In net/ipv4/fib_trie.c (ffffffff81af2e3e)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_node
```
```
In net/ipv4/nexthop.c (ffffffff81afc5a3)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b13520)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17667)
Location: include/linux/list.h:852
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b25e91)
Location: include/linux/list.h:852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
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
In arch/x86/events/amd/uncore.c (ffffffff81009619)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810701d0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ed31)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_queue_task
```
```
In kernel/fork.c (ffffffff810a194d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a6c7b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff82fd9cf4)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c60fc)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d4ddd)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/ucount.c:get_ucounts
```
```
In kernel/sched/core.c (ffffffff810d8d09)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff81140a0e)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdfd72)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffff811afed8)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff811c406c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff81222e77)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/user-return-notifier.c (ffffffff8125380d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/watch_queue.c (ffffffff81256ce9)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff812dd57b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff812e24e4)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812fea1c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff81322efc)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff8133d1f0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/namespace.c (ffffffff8134ad76)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8135beb0)
Location: include/linux/list.h:879
Inline: True
```
```
In fs/fs_pin.c (ffffffff81362ca7)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/io_uring.c (ffffffff8138d3a9)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a594d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff813abad1)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff813c2788)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff814766ad)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8148537c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/selinux/ss/sidtab.c (ffffffff814ddec2)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/safesetid/securityfs.c (ffffffff8152f9f6)
Location: include/linux/list.h:879
Inline: True
```
```
In crypto/algapi.c (ffffffff8153dd0b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff8155c528)
Location: include/linux/list.h:879
Inline: True
```
```
In block/blk-ioc.c (ffffffff81565684)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff815835d4)
Location: include/linux/list.h:879
Inline: True
```
```
In block/keyslot-manager.c (ffffffff8159e48f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/pci/pci.c (ffffffff8164c913)
Location: include/linux/list.h:879
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8166bf01)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff8171e5f1)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8177847b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain
```
```
In drivers/dax/super.c (ffffffff81831d7c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/interconnect/core.c (ffffffff819dbd75)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/sched/sch_api.c (ffffffff81a6fc07)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81a7f155)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaeda1)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf1ba)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81adc2df)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc5e4)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In net/ipv4/fib_trie.c (ffffffff81affd4e)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_node
```
```
In net/ipv4/nexthop.c (ffffffff81b0a023)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b218f0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25727)
Location: include/linux/list.h:879
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b329c0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81009fef)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81071eb0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f9c1)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810a26d9)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a7d3b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff831e46ab)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c7a25)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff831e555b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/core.c (ffffffff810da689)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff81141ade)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff831ea984)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffff811b07e8)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff811c4fbc)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff81227046)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/user-return-notifier.c (ffffffff81257e2d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/watch_queue.c (ffffffff8125b185)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff812e4cfb)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff812e9c74)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff8130568c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff81328fbc)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff81343670)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/namespace.c (ffffffff81351626)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff81362ac3)
Location: include/linux/list.h:879
Inline: True
```
```
In fs/fs_pin.c (ffffffff81369747)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137de0d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/io_uring.c (ffffffff81397b33)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac9a9)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff813b5861)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/quota/dquot.c (ffffffff813c9361)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff8147c11d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8148ac9c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/selinux/ss/sidtab.c (ffffffff814e4831)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/safesetid/securityfs.c (ffffffff81535b06)
Location: include/linux/list.h:879
Inline: True
```
```
In crypto/algapi.c (ffffffff815463eb)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff81564dc8)
Location: include/linux/list.h:879
Inline: True
```
```
In block/blk-ioc.c (ffffffff8156dcf4)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff8158a3e4)
Location: include/linux/list.h:879
Inline: True
```
```
In block/keyslot-manager.c (ffffffff815a5271)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/pci/pci.c (ffffffff8162f493)
Location: include/linux/list.h:879
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8164e191)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff816ff641)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175c15e)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff81814fac)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/interconnect/core.c (ffffffff819c2028)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/sched/sch_api.c (ffffffff81a584f7)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81a67ff5)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9a045)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a4cd)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81ac724f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7def)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In net/ipv4/fib_trie.c (ffffffff81aeb4af)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81af4d33)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f510)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13247)
Location: include/linux/list.h:879
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b20500)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/kernel/apic/vector.c (ffffffff8107dcb0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e7a1)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810b3dd6)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810b97b5)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff832c8367)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810da79d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff832c9433)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/core.c (ffffffff810ee066)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff811650ce)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff832cf173)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffff811da672)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff811f04fc)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff8125f146)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/user-return-notifier.c (ffffffff8129399d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/watch_queue.c (ffffffff81296f85)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff8132cb0b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff81331b9e)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff8134f4e6)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff813765ec)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff81390fa0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/namespace.c (ffffffff8139f996)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff813b12c3)
Location: include/linux/list.h:879
Inline: True
```
```
In fs/fs_pin.c (ffffffff813b8447)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cad4a)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/io_uring.c (ffffffff813e4763)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc2ff)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff81405589)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/quota/dquot.c (ffffffff81419bd3)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff814d381d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff814e24c9)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/selinux/ss/sidtab.c (ffffffff8153ddf8)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/safesetid/securityfs.c (ffffffff81594106)
Location: include/linux/list.h:879
Inline: True
```
```
In crypto/algapi.c (ffffffff815a6bc9)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff815c9148)
Location: include/linux/list.h:879
Inline: True
```
```
In block/blk-ioc.c (ffffffff815d22e4)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/keyslot-manager.c (ffffffff8160dd1a)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/pci/pci.c (ffffffff8169efa3)
Location: include/linux/list.h:879
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff816bff61)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff81779e33)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff817dfcbb)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain
```
```
In drivers/dax/super.c (ffffffff8189f71c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/interconnect/core.c (ffffffff81a718a8)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/sched/sch_api.c (ffffffff81b114d7)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81b21515)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b554b5)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b5593d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81b85a6f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7c90)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In net/ipv4/fib_trie.c (ffffffff81bab7ec)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81bb55c6)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2940)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd7147)
Location: include/linux/list.h:879
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81be93ad)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
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
In arch/x86/kernel/apic/vector.c (ffffffff8108bda0)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f2c4)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810ca0c9)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810d01e0)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff8347b437)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810f3e83)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff8347c622)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/core.c (ffffffff8110a8b6)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff81198d0e)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff83482eb8)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffff81210575)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff81228be8)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff812a97b0)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/user-return-notifier.c (ffffffff812e947a)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/watch_queue.c (ffffffff812ed5b3)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff8139cdf3)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff813a2d2a)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff813c7744)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff813f5cea)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff814132c0)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/namespace.c (ffffffff81422f35)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff814361cd)
Location: include/linux/list.h:925
Inline: True
```
```
In fs/fs_pin.c (ffffffff8143dcf7)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81452afe)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f7a8)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff81479c43)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/quota/dquot.c (ffffffff81490641)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff8155ec49)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff81570759)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/selinux/ss/sidtab.c (ffffffff815d57b1)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/safesetid/securityfs.c (ffffffff81636146)
Location: include/linux/list.h:925
Inline: True
```
```
In crypto/algapi.c (ffffffff8164cb88)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff8167433b)
Location: include/linux/list.h:925
Inline: True
```
```
In block/blk-ioc.c (ffffffff8167d9f7)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-crypto-profile.c (ffffffff816c27cc)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff816ce8fc)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_arm_poll_handler
```
```
In drivers/pci/pci.c (ffffffff817c1af3)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff817e56ce)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff818b024e)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8191e8fc)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/interconnect/core.c (ffffffff81be3310)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/sched/sch_api.c (ffffffff81c985f7)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81caf945)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2ff1)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce333d)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a813)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In net/ipv4/fib_trie.c (ffffffff81d3e677)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81d49131)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d69680)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6db45)
Location: include/linux/list.h:925
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81d80118)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
```
```
In net/mctp/route.c (ffffffff81e3a504)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
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
In arch/x86/kernel/apic/vector.c (ffffffff810a0290)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810b67f7)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810e7733)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810ee9ca)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff83ea6219)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff811160d0)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff83ea79d7)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/core.c (ffffffff8112d816)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff811d724e)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb06e7)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffff812599b5)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff8127428e)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff81309558)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/cgroup.c (ffffffff81329083)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/user-return-notifier.c (ffffffff813531fa)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/watch_queue.c (ffffffff81357983)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff8141c223)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff8142298a)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff8144b734)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff8147ef8a)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff8149e5ed)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/namespace.c (ffffffff814af655)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff814c41cf)
Location: include/linux/list.h:925
Inline: True
```
```
In fs/fs_pin.c (ffffffff814cc6a7)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e17be)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500e8a)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8150c5e3)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/quota/dquot.c (ffffffff815241c1)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff81600e59)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff81615699)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/selinux/ss/sidtab.c (ffffffff816839d1)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/safesetid/securityfs.c (ffffffff816ed136)
Location: include/linux/list.h:925
Inline: True
```
```
In crypto/algapi.c (ffffffff81706e10)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff8173001b)
Location: include/linux/list.h:925
Inline: True
```
```
In block/blk-ioc.c (ffffffff8173a607)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-crypto-profile.c (ffffffff81783b2c)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff8178ed84)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_free_batch_list
```
```
In io_uring/net.c (ffffffff817953e6)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - io_uring/net.c:io_netmsg_recycle
```
```
In io_uring/poll.c (ffffffff8179c87b)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:io_poll_add_hash
```
```
In drivers/pci/pci.c (ffffffff818de0c3)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff8190a56e)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff819fc6fe)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7a8a4)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/interconnect/core.c (ffffffff81d8ef70)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/sched/sch_api.c (ffffffff81e545b7)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81e668e9)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea538a)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5c2f)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/fib_semantics.c (ffffffff81f03173)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In net/ipv4/fib_trie.c (ffffffff81f07257)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81f12751)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34980)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f39155)
Location: include/linux/list.h:925
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81f4cbd3)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/mctp/route.c (ffffffff820133ca)
Location: include/linux/list.h:925
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_add
  - net/mctp/route.c:mctp_key_add
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
In arch/x86/kernel/apic/vector.c (ffffffff810a3210)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9930)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810f32b1)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810fa9aa)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff836ca919)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff81122e70)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff836cc347)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/core.c (ffffffff8113ac56)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/irq/resend.c (ffffffff811ac10b)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/module/main.c (ffffffff811e05e0)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/time/timer.c (ffffffff811ebbae)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff836d56d7)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffff81270d73)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff8128afbe)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812c6826)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
```
```
In kernel/bpf/trampoline.c (ffffffff813383be)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/cgroup.c (ffffffff81359421)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/user-return-notifier.c (ffffffff813843fa)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/watch_queue.c (ffffffff813891e5)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff8144f7d3)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff8145786a)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff81480fb4)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff814b3c0c)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff814d390d)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/namespace.c (ffffffff814e46d7)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff814f95be)
Location: include/linux/list.h:940
Inline: True
```
```
In fs/fs_pin.c (ffffffff815028e7)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8151807e)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/crypto/keysetup_v1.c (ffffffff8153851a)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff81543d58)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/quota/dquot.c (ffffffff8155c5c9)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff81638d49)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8164d729)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/selinux/ss/sidtab.c (ffffffff816bbce8)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/safesetid/securityfs.c (ffffffff81727556)
Location: include/linux/list.h:940
Inline: True
```
```
In crypto/algapi.c (ffffffff81740ec0)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff8176c24e)
Location: include/linux/list.h:940
Inline: True
```
```
In block/blk-ioc.c (ffffffff81776d12)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-crypto-profile.c (ffffffff817c3e1c)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/poll.c (ffffffff817dd83b)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:io_poll_add_hash
```
```
In drivers/pci/pci.c (ffffffff81921523)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff8194dbee)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff81a4516e)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac6114)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/list.h:940
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eafe57)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81ec26a9)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03b14)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f043b0)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62b69)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In net/ipv4/fib_trie.c (ffffffff81f66cfb)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81f72400)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f945a0)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98c95)
Location: include/linux/list.h:940
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81fac53f)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/mctp/route.c (ffffffff820901ea)
Location: include/linux/list.h:940
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_add
  - net/mctp/route.c:mctp_key_add
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
In arch/x86/kernel/apic/vector.c (ffffffff810aa143)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__vector_schedule_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0d8a)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810fc661)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff81103dca)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff838fb62e)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff8112cef3)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff838fd749)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/core.c (ffffffff81145ae6)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/irq/resend.c (ffffffff811bbd0b)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/module/main.c (ffffffff811f6310)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/time/timer.c (ffffffff812016fe)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff83907a47)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffff8128b1f3)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff812a636e)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812e32dc)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
```
```
In kernel/bpf/trampoline.c (ffffffff8135e4be)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/cgroup.c (ffffffff81381fd0)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/user-return-notifier.c (ffffffff813ad80a)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In kernel/watch_queue.c (ffffffff813b2c37)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/mmu_notifier.c (ffffffff814894b3)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff8149233a)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff814affa4)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff814e632c)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff815063c9)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_alloc
```
```
In fs/namespace.c (ffffffff81518417)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8152de1e)
Location: include/linux/list.h:1029
Inline: True
```
```
In fs/fs_pin.c (ffffffff81537537)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154c45e)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d66a)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff81579240)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/quota/dquot.c (ffffffff81592d89)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff81672239)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff81686c88)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/selinux/ss/sidtab.c (ffffffff816f8818)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/safesetid/securityfs.c (ffffffff817687f6)
Location: include/linux/list.h:1029
Inline: True
```
```
In crypto/algapi.c (ffffffff81781d60)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff817ae43e)
Location: include/linux/list.h:1029
Inline: True
```
```
In block/blk-ioc.c (ffffffff817b8f3f)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-crypto-profile.c (ffffffff81808aac)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/uring_cmd.c (ffffffff818198cb)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_mark_cancelable
```
```
In io_uring/poll.c (ffffffff81821b8b)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:io_poll_add_hash
```
```
In io_uring/kbuf.c (ffffffff81825597)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
```
```
In io_uring/waitid.c (ffffffff8182aca2)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
```
```
In io_uring/futex.c (ffffffff8182f9e9)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wait
  - io_uring/futex.c:io_futexv_wait
```
```
In drivers/pci/pci.c (ffffffff81969a63)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff81996edd)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff81a90c76)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b19143)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/interconnect/core.c (ffffffff81eb38b1)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/core/page_pool_user.c (ffffffff81f4614c)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_list
```
```
In net/sched/sch_api.c (ffffffff81f728c7)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff81f859f9)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7dc4)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_create
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8717)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/fib_semantics.c (ffffffff82029139)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In net/ipv4/fib_trie.c (ffffffff8202d2ce)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff8203954f)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061990)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff82065ff5)
Location: include/linux/list.h:1029
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8207995f)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/mctp/route.c (ffffffff8216672a)
Location: include/linux/list.h:1029
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_add
  - net/mctp/route.c:mctp_key_add
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
In virt/kvm/irqchip.c (ffff8000100ec07c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - virt/kvm/irqchip.c:kvm_set_irq_routing
```
```
In kernel/fork.c (ffff8000100f36ac)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffff8000100f9fe0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffff8000114429d4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffff800010121404)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffff80001012fff8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:get_ucounts
```
```
In kernel/sched/core.c (ffff800010132b20)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffff80001019e2b8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffff80001144ae38)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffff8000101f8548)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffff8000102151f0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffff80001022b60c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In mm/ksm.c (ffff800010341aec)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffff80001035efe8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffff800010387644)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffff8000103a8ac0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffff8000103aea90)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffff8000103b73b0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffff8000103cc1a0)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (ffff8000103d4074)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f898)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffff800010414dbc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffff8000104303cc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffff8000104ed0ec)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffff8000104fd0fc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (ffff8000105ab2c0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (ffff8000105b98c8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffff8000105de2d8)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (ffff8000105e901c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffff800010609a84)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffff8000106e536c)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (ffff8000106fec78)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffff8000107c2aec)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffff80001088542c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffff8000109639e4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (ffff800010c3234c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_api.c (ffff800010c3b548)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffff800010c4a700)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b470)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bac0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffff800010c96e98)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffff800010cb8350)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffff800010cbc290)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffff800010cc5ce8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffff800010cddf38)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5ea8)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (ffff800010ceeab0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In kernel/fork.c (c0351cc4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c0358218)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (c151ca18)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (c03751ec)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (c037fc9c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/time/timer.c (c03e763c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (c15251c0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (c0436dc4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (c0453f2c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
```
In kernel/trace/trace_output.c (c0468c88)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In mm/ksm.c (c05479c8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In fs/super.c (c0570770)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (c058a108)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (c058e930)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (c0595a18)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (c05a7e00)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (c05ae200)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (c05dc130)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (c05e19b4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (c05f904c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (c06a9324)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (c06ba770)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (c075ae70)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (c0768274)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (c078b3b4)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (c07956c0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (c07b53fc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (c0880f98)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (c08976e4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (c08ed760)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (c09840c0)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/dax/super.c (c0a39c0c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (c0d48dc0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
```
In net/sched/sch_api.c (c0d4d2c8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (c0d5b204)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (c0d7a514)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a7e4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (c0da4a54)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (c0dc3700)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (c0dc7b00)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (c0dcf664)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
```
```
In net/xfrm/xfrm_policy.c (c0de8174)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0dec8b8)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (c0df7010)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In kernel/fork.c (c0000000001392d4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c00000000014112c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (c0000000013667c8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (c00000000016aa68)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (c000000000179a6c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (c00000000017d328)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (c0000000001fc2a0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (c00000000137060c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (c00000000026ce28)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (c000000000296934)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (c0000000002b3598)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In mm/ksm.c (c00000000041f1f8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (c000000000449aa8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (c00000000047e98c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (c0000000004a35dc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (c0000000004a9e0c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (c0000000004b3ea4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (c0000000004cd7a0)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (c0000000004d6be0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (c00000000051cf6c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (c0000000005241d4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (c000000000542104)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (c00000000062bc14)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (c000000000640338)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (c000000000729020)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (c00000000073fca0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (c00000000076f8f4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_add
```
```
In block/blk-ioc.c (c00000000077dc78)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (c0000000007a6b1c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (c00000000085fe14)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (c00000000087e198)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/tty/serial/8250/8250_core.c (c00000000092c39c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (c000000000a18e24)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1d2e8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:init_powernv_pstates
```
```
In net/core/bpf_sk_storage.c (c000000000d2b6a4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_api.c (c000000000d34704)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (c000000000d4834c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (c000000000d708a4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70db4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (c000000000da7824)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (c000000000dd0cb0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (c000000000dd5e68)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (c000000000de2540)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (c000000000dff368)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e0663c)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (c000000000e13c04)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In kernel/fork.c (ffffffe0000bfce2)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffe0000c4196)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffe000004e8e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffe0000da318)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffe0000e3954)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/time/timer.c (ffffffe00012be98)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffe00000c212)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffe000174f10)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffe000185716)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In mm/ksm.c (ffffffe000235f32)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In fs/super.c (ffffffe00025a62e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffe00026ee0c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffe000273856)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffe000279f4e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffe0002897d8)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (ffffffe00028e6a0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b830e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffe0002bc9e2)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffe0002cd456)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffe00035d224)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffe00036b80e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (ffffffe0003f3eb0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (ffffffe0003ffd66)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffe000420f00)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (ffffffe0004298e0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffe0004437a6)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffe0004bc56a)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (ffffffe0004ce976)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffe000510534)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffe000550b18)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/dax/super.c (ffffffe0005d055a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7cc6)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_api.c (ffffffe0007ac1b8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffe0007b7958)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d106a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d14ca)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffe0007f5352)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffe00080f2f2)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffe000812766)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffe00081a894)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082da10)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe000831986)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (ffffffe00083bb5c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81009609)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810688e8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81076c18)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff8109819c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109daab)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff828b4137)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810bda96)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810ca233)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810cc969)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff8112c97a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb77d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8117c36c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8119496d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff811a6861)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff8121555d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/ksm.c (ffffffff8129a874)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812b609c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff812d8f87)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff812f24fc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff812f6810)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff812fd9f6)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8130dda2)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (ffffffff81314c07)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346935)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8134b89d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff813614d4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff8140488f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8141423d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (ffffffff814abbc1)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (ffffffff814b882f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff814d98fa)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (ffffffff814e2e94)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff81500125)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff81576812)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8158b5ce)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff81617fda)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81670624)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff817178c7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (ffffffff81929b3d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_api.c (ffffffff8192f487)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff8193d015)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959a40)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959f3a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81982127)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff8199facb)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff819a35a6)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff819ac4b7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c1275)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5295)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819cef64)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81007df9)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058c58)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81066b98)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff81086bfc)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8108c4cb)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff828ac2b8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810ac2c6)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b8a47)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810bb169)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff8111f1ea)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828b3e10)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8116f50c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff81187a7d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff811997e1)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff812082bd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/ksm.c (ffffffff8128c434)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812a728c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff812c9c07)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff812e312c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff812e7430)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff812ee616)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff812fe9b2)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (ffffffff81305817)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (ffffffff81337615)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8133c57d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff81352174)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff813f530f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff81404cbd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (ffffffff8149c5e1)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (ffffffff814a924f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff814ca2aa)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (ffffffff814d3824)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff814f0635)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff81564f72)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8157a10e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff8160c50a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8164f72e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff816efdf7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (ffffffff818e38ed)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_api.c (ffffffff818e8f87)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff818f6b15)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff81913530)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913a2a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff8193bbe7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff8195958b)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff8195d066)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81965f77)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e065)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81982085)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198bd24)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff810095c9)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068d98)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81076bc8)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff8109814c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109da5b)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff828c7036)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810bcff6)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c9763)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810cbe89)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff8112a69a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce500)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8117a13c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8119273d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff811a4631)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff812132fd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/ksm.c (ffffffff81298684)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812b3eac)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff812d6d97)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff812f030c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff812f4620)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff812fb7e6)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8130bb92)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (ffffffff813129f7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (ffffffff81344405)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8134936d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff8135efa4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff81401c0f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff814115bd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (ffffffff814a7c61)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (ffffffff814b48bf)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff814d598a)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (ffffffff814def24)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff814fc1b5)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff81576042)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8158b48e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff81645dba)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8169e9f4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff81756697)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (ffffffff8197accd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_api.c (ffffffff81980617)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff8198e1a5)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c4210)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c470a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff819ec8f7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a36b)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a0de46)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81a16d57)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2bcf5)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2fd15)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a399e4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
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
In arch/x86/events/amd/uncore.c (ffffffff81009729)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_find_online_sibling
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81069348)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81078638)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff8109fd4c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a58eb)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
```
In kernel/user.c (ffffffff828cc386)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c5376)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d1c9a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810d43e9)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_register
```
```
In kernel/time/timer.c (ffffffff81137c7a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828d38fa)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81187a6c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811a02cd)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:__add_hash_entry
```
```
In kernel/trace/trace_output.c (ffffffff811b23c1)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:register_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff8122229d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:user_return_notifier_register
```
```
In mm/ksm.c (ffffffff812a8404)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_append
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:alloc_stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812c433e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/super.c (ffffffff812e8009)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
```
In fs/dcache.c (ffffffff8130140c)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff81305562)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/namespace.c (ffffffff8130cb23)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:get_mountpoint
```
```
In fs/pnode.c (ffffffff8131d3c0)
Location: include/linux/list.h:782
Inline: True
```
```
In fs/fs_pin.c (ffffffff81324227)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_insert
```
```
In fs/crypto/keysetup_v1.c (ffffffff813576e3)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8135c84d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/locks.c:__locks_insert_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/quota/dquot.c (ffffffff813719ca)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/fat/inode.c (ffffffff8141645d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/ecryptfs/messaging.c (ffffffff8142722d)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
```
```
In security/safesetid/securityfs.c (ffffffff814c05f1)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In crypto/algapi.c (ffffffff814cd33f)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In block/elevator.c (ffffffff814ee5aa)
Location: include/linux/list.h:782
Inline: True
```
```
In block/blk-ioc.c (ffffffff814f7d78)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/bsg.c (ffffffff81515265)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/pci/pci.c (ffffffff81590522)
Location: include/linux/list.h:782
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff815a593e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/clk/clk.c (ffffffff8166034a)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816b8e4e)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/dax/super.c (ffffffff817718f0)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/bpf_sk_storage.c (ffffffff8199d229)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_api.c (ffffffff819a2b87)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffffffff819b0a45)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cdc82)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819cdfca)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff819f67e7)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14b4b)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a18656)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/nexthop.c (ffffffff81a21787)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a373c5)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b6b5)
Location: include/linux/list.h:782
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a457f4)
Location: include/linux/list.h:782
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_insert_socket
```
</details>
</li>
</ul>

## Differences
