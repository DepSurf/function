# Function: <code>perfmon_capable</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100db47)
Location: include/linux/capability.h:254
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff810101fd)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In arch/x86/events/intel/p4.c (ffffffff8101543b)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d8881)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_event_perm
  - kernel/trace/trace_event_perf.c:perf_trace_event_perm
```
```
In kernel/trace/bpf_trace.c (ffffffff811ead13)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/syscall.c (ffffffff81200552)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff81213112)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff812150a6)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/arraymap.c (ffffffff8121a64b)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/events/core.c (ffffffff8123f2b1)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff8100cc91)
Location: include/linux/capability.h:254
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f75d)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In arch/x86/events/intel/p4.c (ffffffff810158db)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d59a1)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_event_perm
  - kernel/trace/trace_event_perf.c:perf_trace_event_perm
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8eb3)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/syscall.c (ffffffff811ff993)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff812148f2)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81216bd7)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/arraymap.c (ffffffff8121d35a)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/events/core.c (ffffffff812496ae)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:find_get_context
```
```
In net/core/filter.c (ffffffff81a33988)
Location: include/linux/capability.h:254
Inline: True
Inline callers:
  - net/core/filter.c:flow_dissector_func_proto
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
In arch/x86/events/intel/core.c (ffffffff8100d748)
Location: include/linux/capability.h:257
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff810107ad)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In arch/x86/events/intel/p4.c (ffffffff81016bfa)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6f10)
Location: include/linux/capability.h:257
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff811e9da3)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/syscall.c (ffffffff8120033e)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff81217154)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff8121a1f9)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/arraymap.c (ffffffff81220e6a)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/events/core.c (ffffffff8124de24)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:find_get_context
```
```
In net/core/filter.c (ffffffff81a1a848)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - net/core/filter.c:flow_dissector_func_proto
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
In arch/x86/events/intel/core.c (ffffffff8100dd08)
Location: include/linux/capability.h:257
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff810111dd)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In arch/x86/events/intel/p4.c (ffffffff81018790)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203e0e)
Location: include/linux/capability.h:257
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff8121abd3)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/syscall.c (ffffffff8123208a)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8124d976)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81250e11)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/arraymap.c (ffffffff8125882a)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/events/core.c (ffffffff8128884a)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:find_get_context
```
```
In net/core/filter.c (ffffffff81aceb79)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - net/core/filter.c:flow_dissector_func_proto
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
In arch/x86/events/intel/core.c (ffffffff8100f128)
Location: include/linux/capability.h:257
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff81012937)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a94e)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123f1f4)
Location: include/linux/capability.h:257
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812598aa)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/syscall.c (ffffffff81274ec5)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff81294918)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81298864)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/arraymap.c (ffffffff812a163a)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/events/core.c (ffffffff812dd9ec)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:find_get_context
```
```
In net/core/filter.c (ffffffff81c3e3f7)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_base_func_proto
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
In arch/x86/events/intel/core.c (ffffffff81012ad7)
Location: include/linux/capability.h:257
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff81016927)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In arch/x86/events/intel/p4.c (ffffffff8101eabe)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128ce75)
Location: include/linux/capability.h:257
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812a9afa)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/syscall.c (ffffffff812ca2e6)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff812ef4e5)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff812f398e)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/arraymap.c (ffffffff812fe89a)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/events/core.c (ffffffff81345cd0)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:find_get_context
```
```
In net/core/filter.c (ffffffff81df26c7)
Location: include/linux/capability.h:257
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_base_func_proto
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
In arch/x86/events/intel/core.c (ffffffff8101204f)
Location: include/linux/capability.h:195
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff810162c7)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e7ae)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9df5)
Location: include/linux/capability.h:195
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812cc36a)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/syscall.c (ffffffff812f1a19)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8131be3a)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff813207aa)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/arraymap.c (ffffffff8132d48a)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/events/core.c (ffffffff81376d87)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:find_get_context
```
```
In net/core/filter.c (ffffffff81e6463b)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_base_func_proto
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
In arch/x86/events/intel/core.c (ffffffff810178ec)
Location: include/linux/capability.h:195
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff8101be07)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In arch/x86/events/intel/p4.c (ffffffff810245ee)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c5b05)
Location: include/linux/capability.h:195
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3ba5)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_free
```
```
In kernel/trace/bpf_trace.c (ffffffff812e97ea)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/syscall.c (ffffffff8131088c)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8133e1d7)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81342caa)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/arraymap.c (ffffffff8135195c)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/events/core.c (ffffffff813a0016)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:find_get_context
```
```
In net/core/filter.c (ffffffff81f237eb)
Location: include/linux/capability.h:195
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_base_func_proto
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
