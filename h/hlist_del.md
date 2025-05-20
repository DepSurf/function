# Function: <code>hlist_del</code>

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
In arch/x86/kernel/kprobes/core.c (ffffffff8105f3f7)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810638fa)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/sched/core.c (ffffffff810a4a85)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8112cc6e)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff81140460)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:free_ftrace_hash
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
```
In kernel/trace/trace_output.c (ffffffff81154164)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff81189725)
Location: include/linux/list.h:624
Inline: True
```
```
In mm/ksm.c (ffffffff811e4ed0)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In fs/namespace.c (ffffffff8122be8b)
Location: include/linux/list.h:624
Inline: True
```
```
In fs/ecryptfs/messaging.c (ffffffff8130b611)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff8139d9ed)
Location: include/linux/list.h:624
Inline: True
```
```
In block/bsg.c (ffffffff813d69b7)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81505238)
Location: include/linux/list.h:624
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816e45fc)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:__clk_put
```
```
In net/core/flow.c (ffffffff8173466e)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/core/flow.c:__flow_cache_shrink
  - net/core/flow.c:flow_cache_flush_tasklet
```
```
In net/sched/sch_api.c (ffffffff817426f5)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/act_api.c (ffffffff817474fb)
Location: include/linux/list.h:624
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81799ade)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c44c)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1c6f)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b0e2c)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff817b8cd8)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
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
In arch/x86/events/amd/uncore.c (ffffffff81008da4)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f1fc)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81063538)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/sched/core.c (ffffffff810a81d5)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8113529b)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8114c902)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:free_ftrace_hash
```
```
In kernel/trace/trace_output.c (ffffffff8115d374)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff8119be05)
Location: include/linux/list.h:624
Inline: True
```
```
In mm/ksm.c (ffffffff81203a30)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In fs/namespace.c (ffffffff812545fc)
Location: include/linux/list.h:624
Inline: True
```
```
In fs/ecryptfs/messaging.c (ffffffff8133f877)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff813da94d)
Location: include/linux/list.h:624
Inline: True
```
```
In block/bsg.c (ffffffff8141c674)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815569a8)
Location: include/linux/list.h:624
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8174d27a)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In net/core/flow.c (ffffffff817a0d2a)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_tasklet
  - net/core/flow.c:__flow_cache_shrink
```
```
In net/sched/sch_api.c (ffffffff817af5a5)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/act_api.c (ffffffff817b46c0)
Location: include/linux/list.h:624
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81807728)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a03f)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f931)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181dd7c)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81826bab)
Location: include/linux/list.h:624
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
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
In arch/x86/events/amd/uncore.c (ffffffff81008de4)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106229c)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810669f8)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff810893da)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810ae075)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8113f01b)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811567f2)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:free_ftrace_hash
```
```
In kernel/trace/trace_output.c (ffffffff81167de4)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811ab7e5)
Location: include/linux/list.h:640
Inline: True
```
```
In mm/ksm.c (ffffffff81215a50)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In fs/namespace.c (ffffffff81267b3c)
Location: include/linux/list.h:640
Inline: True
```
```
In fs/ecryptfs/messaging.c (ffffffff813555fb)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff813f228d)
Location: include/linux/list.h:640
Inline: True
```
```
In block/bsg.c (ffffffff81437bb4)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff81535aea)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815831a8)
Location: include/linux/list.h:640
Inline: True
```
```
In net/core/flow.c (ffffffff817cf95a)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_tasklet
  - net/core/flow.c:__flow_cache_shrink
```
```
In net/sched/sch_api.c (ffffffff817dec95)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/act_api.c (ffffffff817e3f70)
Location: include/linux/list.h:640
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff818387b5)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b14f)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81840e81)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f616)
Location: include/linux/list.h:640
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
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
In arch/x86/events/amd/uncore.c (ffffffff81008b34)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810611c2)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81065d08)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff81086102)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810aab25)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff81142d34)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff81159bde)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff8116aff4)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811b2c55)
Location: include/linux/list.h:653
Inline: True
```
```
In mm/ksm.c (ffffffff81222cdd)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff8127516c)
Location: include/linux/list.h:653
Inline: True
```
```
In fs/ecryptfs/messaging.c (ffffffff8136a1fb)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff813fe57e)
Location: include/linux/list.h:653
Inline: True
```
```
In block/bsg.c (ffffffff81445344)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff81548e7a)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815975f1)
Location: include/linux/list.h:653
Inline: True
```
```
In net/core/flow.c (ffffffff817eed62)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_tasklet
  - net/core/flow.c:__flow_cache_shrink
```
```
In net/sched/sch_api.c (ffffffff817fe2c5)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/act_api.c (ffffffff81803936)
Location: include/linux/list.h:653
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a0f5)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8185ca0f)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81862730)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818730f6)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f26a)
Location: include/linux/list.h:653
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff81008d54)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81065011)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a2dd)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff8108cd83)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810b1835)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8114f9e4)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811666de)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff811780d4)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811c68a5)
Location: include/linux/list.h:654
Inline: True
```
```
In mm/ksm.c (ffffffff8123e139)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff81297a2c)
Location: include/linux/list.h:654
Inline: True
```
```
In fs/ecryptfs/messaging.c (ffffffff8138edab)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff81426b3e)
Location: include/linux/list.h:654
Inline: True
```
```
In block/bsg.c (ffffffff81471e14)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff815ac3ea)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815fc231)
Location: include/linux/list.h:654
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187bed5)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff818da015)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff818dc8ff)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2855)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3b06)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff8192185a)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff81008fc6)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067bb1)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8106cf4d)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff81090775)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810b87e5)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8115e524)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811753ee)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff811872e4)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811e6de5)
Location: include/linux/list.h:654
Inline: True
```
```
In mm/ksm.c (ffffffff8126192f)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff812be082)
Location: include/linux/list.h:654
Inline: True
```
```
In fs/ecryptfs/messaging.c (ffffffff813bde4f)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff81459a2f)
Location: include/linux/list.h:654
Inline: True
```
```
In block/bsg.c (ffffffff814a5bb0)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff815e4345)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816355ac)
Location: include/linux/list.h:654
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818ce765)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81930b1e)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff819334e9)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a41e)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81979cc3)
Location: include/linux/list.h:654
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff81009606)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106da71)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8107311d)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff81098835)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810c1905)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8116b09c)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8118302e)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff81194c54)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff811f7a15)
Location: include/linux/list.h:707
Inline: True
```
```
In mm/ksm.c (ffffffff8127618a)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff812d3392)
Location: include/linux/list.h:707
Inline: True
```
```
In fs/ecryptfs/messaging.c (ffffffff813d748f)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff81476f7f)
Location: include/linux/list.h:707
Inline: True
```
```
In block/bsg.c (ffffffff814bf889)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff815fe735)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8165387c)
Location: include/linux/list.h:707
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818f99b5)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff8195ff9e)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff819629d9)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c3d3)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff819af8b3)
Location: include/linux/list.h:707
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff81009aea)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071ba9)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81076d81)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff8109cdf4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810c7a05)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff81177f28)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8118fdb2)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (ffffffff811a2944)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff8120f855)
Location: include/linux/list.h:767
Inline: True
```
```
In mm/ksm.c (ffffffff81291289)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff812f1544)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff81401ddf)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff814a4c8b)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (ffffffff814ee0c1)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff81630db8)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81688278)
Location: include/linux/list.h:767
Inline: True
```
```
In net/sched/sch_api.c (ffffffff819591a5)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff819c49a2)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8125)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff819d5278)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e56ff)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1da03)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff81009eda)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81072b56)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81077dd1)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff810a3344)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810d0ae5)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff81183e24)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8119bd82)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (ffffffff811ae344)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff8121ce85)
Location: include/linux/list.h:767
Inline: True
```
```
In mm/ksm.c (ffffffff812a1009)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff813030f4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff8141bccf)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff814bf91b)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (ffffffff81507521)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff81652b78)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816aa918)
Location: include/linux/list.h:767
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8198f645)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb542)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff819fecd5)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81a0bdd8)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c72f)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54633)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff8100b0b2)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81079bb2)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8107eeee)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_queue_task
```
```
In kernel/cpu.c (ffffffff810aa384)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810da905)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff81197bad)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811b0e62)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff811c6714)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff8121f154)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/user-return-notifier.c (ffffffff81249205)
Location: include/linux/list.h:823
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff812d1c3b)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff812d621f)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff8133cbb4)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff8146a96f)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff8151fc9d)
Location: include/linux/list.h:823
Inline: True
```
```
In block/bsg.c (ffffffff81568b2c)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - block/bsg.c:bsg_put_device
```
```
In block/keyslot-manager.c (ffffffff815816e7)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/clk/clk.c (ffffffff8170271a)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175d398)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/interconnect/core.c (ffffffff819dceff)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/sock_map.c (ffffffff81a4e619)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_api.c (ffffffff81a67515)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae9cc2)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81aee239)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81afca55)
Location: include/linux/list.h:823
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0daef)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4b9a3)
Location: include/linux/list.h:823
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff8100a042)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kvm.c (ffffffff8107eade)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_queue_task
```
```
In kernel/cpu.c (ffffffff810a5c14)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810d6bd5)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/trace/ftrace.c (ffffffff811ae8d2)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff811c3d44)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff81222a01)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/user-return-notifier.c (ffffffff81253785)
Location: include/linux/list.h:850
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff812dd63b)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff812e1d1c)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff81348a74)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff814853df)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff8153cb0d)
Location: include/linux/list.h:850
Inline: True
```
```
In block/bsg.c (ffffffff8158345c)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - block/bsg.c:bsg_put_device
```
```
In block/keyslot-manager.c (ffffffff8159e717)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/clk/clk.c (ffffffff8171f9fa)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81778268)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/interconnect/core.c (ffffffff819dc61f)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/sock_map.c (ffffffff81a545f9)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_api.c (ffffffff81a6fc35)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81af6b22)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81afb199)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81b0a8d5)
Location: include/linux/list.h:850
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bcff)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5a5e3)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff8100a7c2)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kvm.c (ffffffff8107fb9d)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/cpu.c (ffffffff810a6a54)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810d88b5)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/trace/ftrace.c (ffffffff811af281)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff811c4e54)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff812271a1)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/user-return-notifier.c (ffffffff81257da5)
Location: include/linux/list.h:850
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff812e4dbb)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff812e94bc)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff8134ee44)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff8148acff)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff815451ed)
Location: include/linux/list.h:850
Inline: True
```
```
In block/bsg.c (ffffffff8158a29c)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/keyslot-manager.c (ffffffff815a5560)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/clk/clk.c (ffffffff81700c4a)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175bec8)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/interconnect/core.c (ffffffff819c289f)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/sock_map.c (ffffffff81a50456)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_api.c (ffffffff81a58525)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae2272)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae6739)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81af7feb)
Location: include/linux/list.h:850
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b099f2)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81b487b3)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/kernel/kvm.c (ffffffff8108e97d)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/cpu.c (ffffffff810b836c)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810ec175)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/trace/ftrace.c (ffffffff811d90b1)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff811f0394)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff8125f2a1)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/user-return-notifier.c (ffffffff81293915)
Location: include/linux/list.h:850
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8132cbcb)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff813313ec)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff8139cee4)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff814e253f)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff815a594d)
Location: include/linux/list.h:850
Inline: True
```
```
In block/keyslot-manager.c (ffffffff8160e030)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/clk/clk.c (ffffffff8177b45a)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff817dfad8)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/interconnect/core.c (ffffffff81a7214f)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/sock_map.c (ffffffff81b09056)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_api.c (ffffffff81b11505)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1a42)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba62db)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81bb8d59)
Location: include/linux/list.h:850
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcc97b)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81c0fa83)
Location: include/linux/list.h:850
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/kernel/kvm.c (ffffffff8109ea51)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/cpu.c (ffffffff810cebcd)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff811071d5)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/trace/ftrace.c (ffffffff8120fd8f)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff81228a74)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff812a9913)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/user-return-notifier.c (ffffffff812e93e5)
Location: include/linux/list.h:896
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8139cf10)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff813a2267)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff8141fe09)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff815707cf)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff8164c6dd)
Location: include/linux/list.h:896
Inline: True
```
```
In block/blk-crypto-profile.c (ffffffff816c2b56)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/clk/clk.c (ffffffff818b1cb7)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8191d59c)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/interconnect/core.c (ffffffff81be3c3c)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/sock_map.c (ffffffff81c8f096)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_api.c (ffffffff81c98635)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34082)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81d38cad)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4cc81)
Location: include/linux/list.h:896
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6268b)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81daac73)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/mctp/af_mctp.c (ffffffff81e374f5)
Location: include/linux/list.h:896
Inline: True
```
```
In net/mctp/route.c (ffffffff81e39fe6)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In arch/x86/kernel/kvm.c (ffffffff810b61c1)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/cpu.c (ffffffff810ecfcf)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff8112d105)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/trace/ftrace.c (ffffffff8125914f)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff81274154)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff81308493)
Location: include/linux/list.h:896
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81327c83)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/user-return-notifier.c (ffffffff81353155)
Location: include/linux/list.h:896
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8141c340)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff81421ef1)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff814ac319)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff816157cb)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff8170599d)
Location: include/linux/list.h:896
Inline: True
```
```
In block/blk-crypto-profile.c (ffffffff81783ee6)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff8178b95f)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In io_uring/net.c (ffffffff817966f4)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
```
```
In io_uring/poll.c (ffffffff8179dad8)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
```
In drivers/clk/clk.c (ffffffff819fe2e7)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7976c)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/interconnect/core.c (ffffffff81d8f96c)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/sock_map.c (ffffffff81e4a2e6)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_api.c (ffffffff81e54605)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81efc532)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0152d)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81f16521)
Location: include/linux/list.h:896
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d18b)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7a543)
Location: include/linux/list.h:896
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/kernel/kvm.c (ffffffff810b92c1)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/cpu.c (ffffffff810f8aef)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff8113a5c5)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/module/main.c (ffffffff811e06f9)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/trace/ftrace.c (ffffffff8127051f)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
```
In kernel/trace/trace_output.c (ffffffff8128ba84)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff81337273)
Location: include/linux/list.h:911
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81357fd4)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/user-return-notifier.c (ffffffff81384355)
Location: include/linux/list.h:911
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8144f8f0)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff81456bf6)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff814e10e9)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff8164d85b)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff8173fc2d)
Location: include/linux/list.h:911
Inline: True
```
```
In block/blk-crypto-profile.c (ffffffff817c41c7)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/clk/clk.c (ffffffff81a46f67)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac4eac)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/interconnect/core.c (ffffffff81dfdf4c)
Location: include/linux/list.h:911
Inline: True
```
```
In net/core/sock_map.c (ffffffff81ea59f6)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_api.c (ffffffff81eafea5)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5bf52)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60f9d)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81f761d1)
Location: include/linux/list.h:911
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cc8b)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81fda753)
Location: include/linux/list.h:911
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/kernel/kvm.c (ffffffff810c0701)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/cpu.c (ffffffff81101eff)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff811454d5)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/module/main.c (ffffffff811f6429)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/trace/ftrace.c (ffffffff8128a9be)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:enter_record
```
```
In kernel/trace/trace_output.c (ffffffff812a6e54)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/bpf/trampoline.c (ffffffff8135d0f3)
Location: include/linux/list.h:1000
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81380b54)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/user-return-notifier.c (ffffffff813ad765)
Location: include/linux/list.h:1000
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff814895d0)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff814916fd)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff815151b9)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff81686dbb)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff81780aad)
Location: include/linux/list.h:1000
Inline: True
```
```
In block/blk-crypto-profile.c (ffffffff81808e57)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/uring_cmd.c (ffffffff81819a40)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
```
In io_uring/kbuf.c (ffffffff818259b4)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_kbuf_mmap_list_free
```
```
In drivers/clk/clk.c (ffffffff81a92a07)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b17eac)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/interconnect/core.c (ffffffff81eb49ac)
Location: include/linux/list.h:1000
Inline: True
```
```
In net/core/page_pool_user.c (ffffffff81f462d4)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_unlist
```
```
In net/core/sock_map.c (ffffffff81f684b6)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_api.c (ffffffff81f72915)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff820224b2)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8202756d)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff8203c9a1)
Location: include/linux/list.h:1000
Inline: True
```
```
In net/ipv4/tcp_ao.c (ffffffff82059037)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a61b)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff820a81a3)
Location: include/linux/list.h:1000
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/arm64/kernel/probes/kprobes.c (0)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler
```
```
In virt/kvm/irqchip.c (0)
Location: include/linux/list.h:767
Inline: True
```
```
In kernel/cpu.c (ffff8000100f8a84)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffff800010131478)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffff8000101f8478)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffff800010214c04)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (ffff80001022b768)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In mm/ksm.c (ffff800010340960)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffff8000103b5448)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffff8000104fd180)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffff8000105b8e04)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (ffff8000106097d4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffff8000107c343c)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffff800010884edc)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In net/sched/sch_api.c (ffff800010c3b594)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7200)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffff800010cc5158)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8984)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/arm/probes/kprobes/core.c (c0ea0a40)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/core.c:trampoline_handler
```
```
In kernel/cpu.c (c0356ce8)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/kprobes.c (c0436d08)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (c045395c)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (c0468d50)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In mm/ksm.c (c0546220)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (c05947e8)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (c06ba7d4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (c0767928)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (c07b4ca0)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (c08eee30)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (c0982ff0)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In net/sched/sch_api.c (c0d4d300)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (c0dbecc4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (c0dc2734)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (c0dd0bd0)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c0de2560)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (c0e1eaa8)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/powerpc/kernel/kprobes.c (c0000000000572bc)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes.c:trampoline_probe_handler
```
```
In kernel/cpu.c (c00000000013f53c)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (c00000000017ab38)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (c00000000026cd30)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (c000000000295ff8)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (c0000000002b3760)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In mm/ksm.c (c00000000041dfc0)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (c0000000004b2b24)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (c0000000006403dc)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (c00000000073e700)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (c0000000007a5f94)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/tty/serial/8250/8250_core.c (c00000000092bf90)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In net/sched/sch_api.c (c000000000d34738)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (c000000000dca788)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (c000000000dcf69c)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (c000000000de1574)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000df91b4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (c000000000e46998)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In kernel/cpu.c (ffffffe0000c3856)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/trace/ftrace.c (ffffffe0001749d4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (ffffffe0001857e4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In mm/ksm.c (ffffffe00023417e)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffe00027911c)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffe00036b87a)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffe0003ff4da)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (ffffffe00044321c)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffe000510e22)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffe00055081a)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In net/sched/sch_api.c (ffffffe0007ac1f8)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b618)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffe00080e5ac)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffe000819058)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828e92)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d880)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff81009eda)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071b56)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81076dd1)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff8109cc64)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810cae65)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8117c444)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811943a2)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (ffffffff811a6964)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff812154d5)
Location: include/linux/list.h:767
Inline: True
```
```
In mm/ksm.c (ffffffff812995e9)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff812fb6d4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff814142af)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff814b7efb)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (ffffffff814ffb01)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff81618bd8)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81670388)
Location: include/linux/list.h:767
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8192f4b5)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b2e2)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8199ea75)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff819abb78)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbdbf)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3cc3)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff8100849a)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061b66)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81066e1f)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff8108b694)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810b9665)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8116f5e4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff811874b2)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (ffffffff811998e4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff81208235)
Location: include/linux/list.h:767
Inline: True
```
```
In mm/ksm.c (ffffffff8128b1a9)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff812ec2f4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff81404d2f)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff814a891b)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (ffffffff814f0011)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff8160d108)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8164f4a2)
Location: include/linux/list.h:767
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818e8fb5)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81954da2)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81958535)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81965638)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978baf)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0a83)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff81009e9a)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071b06)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81076d81)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff8109cc14)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810ca385)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff8117a214)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff81192172)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (ffffffff811a4734)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff81213275)
Location: include/linux/list.h:767
Inline: True
```
```
In mm/ksm.c (ffffffff812973f9)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff812f94c4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff8141162f)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff814b3f8b)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (ffffffff814fbb91)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff816469b8)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8169e758)
Location: include/linux/list.h:767
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81980645)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05b82)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81a09315)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81a16418)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2683f)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e743)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
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
In arch/x86/events/amd/uncore.c (ffffffff81009ffa)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073b7a)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81078dde)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff810a49b3)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/sched/core.c (ffffffff810d2885)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/kprobes.c (ffffffff81187b44)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff8119fd02)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
```
In kernel/trace/trace_output.c (ffffffff811b24c4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/user-return-notifier.c (ffffffff81222215)
Location: include/linux/list.h:767
Inline: True
```
```
In mm/ksm.c (ffffffff812a71c9)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/namespace.c (ffffffff8130a7e4)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
```
```
In fs/ecryptfs/messaging.c (ffffffff8142729f)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In crypto/algapi.c (ffffffff814cca0b)
Location: include/linux/list.h:767
Inline: True
```
```
In block/bsg.c (ffffffff81514c41)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/clk/clk.c (ffffffff81660f48)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816b8bbd)
Location: include/linux/list.h:767
Inline: True
```
```
In net/sched/sch_api.c (ffffffff819a2bb5)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10152)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81a13ac5)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/nexthop.c (ffffffff81a20e58)
Location: include/linux/list.h:767
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31cef)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6abc3)
Location: include/linux/list.h:767
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
</details>
</li>
</ul>

## Differences
