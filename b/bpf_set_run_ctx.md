# Function: <code>bpf_set_run_ctx</code>

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
In kernel/trace/bpf_trace.c (ffffffff8121a63b)
Location: include/linux/bpf.h:1165
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff812763e9)
Location: include/linux/bpf.h:1165
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
In net/bpf/test_run.c (ffffffff81b2a629)
Location: include/linux/bpf.h:1165
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
In kernel/trace/bpf_trace.c (ffffffff812574db)
Location: include/linux/bpf.h:1376
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/bpf/trampoline.c (ffffffff812a9aa1)
Location: include/linux/bpf.h:1376
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter
```
```
In kernel/bpf/cgroup.c (ffffffff812c5e4a)
Location: include/linux/bpf.h:1376
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
In net/bpf/test_run.c (ffffffff81cb4271)
Location: include/linux/bpf.h:1376
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
In kernel/trace/bpf_trace.c (ffffffff812a6ebb)
Location: include/linux/bpf.h:1690
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7f5f)
Location: include/linux/bpf.h:1690
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5f76)
Location: include/linux/bpf.h:1690
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff81307fc2)
Location: include/linux/bpf.h:1690
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_enter_lsm_cgroup
  - kernel/bpf/trampoline.c:__bpf_prog_enter_recur
```
```
In kernel/bpf/cgroup.c (ffffffff8132b3ca)
Location: include/linux/bpf.h:1690
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
In net/bpf/test_run.c (ffffffff81e724e1)
Location: include/linux/bpf.h:1690
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
In kernel/trace/bpf_trace.c (ffffffff812cba59)
Location: include/linux/bpf.h:1817
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db58e)
Location: include/linux/bpf.h:1817
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323d16)
Location: include/linux/bpf.h:1817
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff81336e92)
Location: include/linux/bpf.h:1817
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_enter_lsm_cgroup
  - kernel/bpf/trampoline.c:__bpf_prog_enter_recur
```
```
In kernel/bpf/cgroup.c (ffffffff8135b5ea)
Location: include/linux/bpf.h:1817
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
In net/bpf/test_run.c (ffffffff81ece655)
Location: include/linux/bpf.h:1817
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
In kernel/trace/bpf_trace.c (ffffffff812e5786)
Location: include/linux/bpf.h:1943
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:uprobe_prog_run
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f966d)
Location: include/linux/bpf.h:1943
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347ca6)
Location: include/linux/bpf.h:1943
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8135cd12)
Location: include/linux/bpf.h:1943
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_enter_lsm_cgroup
  - kernel/bpf/trampoline.c:__bpf_prog_enter_recur
```
```
In kernel/bpf/cgroup.c (ffffffff8138427a)
Location: include/linux/bpf.h:1943
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
In net/bpf/test_run.c (ffffffff81f91e82)
Location: include/linux/bpf.h:1943
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
