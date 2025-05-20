# Function: <code>bpf_dump_raw_ok</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b464b)
Location: include/linux/filter.h:757
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8188ac53)
Location: include/linux/filter.h:757
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811c28b7)
Location: include/linux/filter.h:786
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff818abc93)
Location: include/linux/filter.h:786
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811d345d)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff818f7543)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811df754)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff819292c3)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811fc03e)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
```
```
In net/core/sysctl_net_core.c (ffffffff819fd24a)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811fb13f)
Location: include/linux/filter.h:896
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
```
```
In net/core/sysctl_net_core.c (ffffffff819fce8a)
Location: include/linux/filter.h:896
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811fbf2f)
Location: include/linux/filter.h:939
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
```
```
In net/core/sysctl_net_core.c (ffffffff819e36fa)
Location: include/linux/filter.h:939
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff8122d51f)
Location: include/linux/filter.h:960
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
```
```
In net/core/sysctl_net_core.c (ffffffff81a93cda)
Location: include/linux/filter.h:960
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff8126fbae)
Location: include/linux/filter.h:955
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
```
```
In net/core/sysctl_net_core.c (ffffffff81c0a1a9)
Location: include/linux/filter.h:955
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff812c550e)
Location: include/linux/filter.h:925
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
```
```
In net/core/sysctl_net_core.c (ffffffff81db9fc0)
Location: include/linux/filter.h:925
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff812ec64e)
Location: include/linux/filter.h:925
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
```
```
In net/core/sysctl_net_core.c (ffffffff81e2a7c0)
Location: include/linux/filter.h:925
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff8130ad5e)
Location: include/linux/filter.h:961
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8840)
Location: include/linux/filter.h:961
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffff8000102619bc)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (ffff800010bc571c)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (c04945f8)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
```
In net/core/sysctl_net_core.c (c0ce0a88)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (c0000000003061c0)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (c000000000ca02a0)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffe00019e70c)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffe000751d9e)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811d7d74)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff818c92c3)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811cab34)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81883203)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811d5b44)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8191a2c3)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
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
In kernel/bpf/syscall.c (ffffffff811e3eb4)
Location: include/linux/filter.h:852
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8193b503)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
</details>
</li>
</ul>

## Differences
