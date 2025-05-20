# Function: <code>bpf_reset_run_ctx</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121a69a)
Location: include/linux/bpf.h:1176
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff81276444)
Location: include/linux/bpf.h:1176
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/bpf/test_run.c (ffffffff81b2a793)
Location: include/linux/bpf.h:1176
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/trace/bpf_trace.c (ffffffff8125750c)
Location: include/linux/bpf.h:1387
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/bpf/trampoline.c (ffffffff812a9b2e)
Location: include/linux/bpf.h:1387
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit
```
```
In kernel/bpf/cgroup.c (ffffffff812c5ea8)
Location: include/linux/bpf.h:1387
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/bpf/test_run.c (ffffffff81cb43e8)
Location: include/linux/bpf.h:1387
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/trace/bpf_trace.c (ffffffff812a6eec)
Location: include/linux/bpf.h:1701
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7ff8)
Location: include/linux/bpf.h:1701
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5fa0)
Location: include/linux/bpf.h:1701
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff81308365)
Location: include/linux/bpf.h:1701
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_lsm_cgroup
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/cgroup.c (ffffffff8132b428)
Location: include/linux/bpf.h:1701
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
```
```
In net/bpf/test_run.c (ffffffff81e72658)
Location: include/linux/bpf.h:1701
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/trace/bpf_trace.c (ffffffff812cbab9)
Location: include/linux/bpf.h:1828
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db626)
Location: include/linux/bpf.h:1828
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323d41)
Location: include/linux/bpf.h:1828
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff81337594)
Location: include/linux/bpf.h:1828
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_lsm_cgroup
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/cgroup.c (ffffffff8135b648)
Location: include/linux/bpf.h:1828
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
```
```
In net/bpf/test_run.c (ffffffff81ece7f8)
Location: include/linux/bpf.h:1828
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/trace/bpf_trace.c (ffffffff812e57b9)
Location: include/linux/bpf.h:1954
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:uprobe_prog_run
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9705)
Location: include/linux/bpf.h:1954
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347cd1)
Location: include/linux/bpf.h:1954
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8135d3d4)
Location: include/linux/bpf.h:1954
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_lsm_cgroup
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/cgroup.c (ffffffff813842d8)
Location: include/linux/bpf.h:1954
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
```
```
In net/bpf/test_run.c (ffffffff81f9202d)
Location: include/linux/bpf.h:1954
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
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
