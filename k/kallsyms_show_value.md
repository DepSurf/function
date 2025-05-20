# Function: <code>kallsyms_show_value</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81127800)
Location: kernel/kallsyms.c:668
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
```
**Symbols:**

```
ffffffff81127800-ffffffff81127843: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81135650)
Location: kernel/kallsyms.c:622
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff81135650-ffffffff81135692: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81140de0)
Location: kernel/kallsyms.c:645
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff81140de0-ffffffff81140e22: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114c1e0)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff8114c1e0-ffffffff8114c222: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81157eb0)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff81157eb0-ffffffff81157ef2: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool kallsyms_show_value(const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81168ad0)
Location: kernel/kallsyms.c:647
Inline: True
Direct callers:
  - kernel/module.c:module_sect_read
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff81168ad0-ffffffff81168b17: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool kallsyms_show_value(const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81165150)
Location: kernel/kallsyms.c:681
Inline: True
Direct callers:
  - kernel/module.c:module_sect_read
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff81165150-ffffffff81165197: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool kallsyms_show_value(const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81165f20)
Location: kernel/kallsyms.c:732
Inline: True
Direct callers:
  - kernel/module.c:module_sect_read
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff81165f20-ffffffff81165f67: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool kallsyms_show_value(const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118b6e0)
Location: kernel/kallsyms.c:796
Inline: True
Direct callers:
  - kernel/module.c:module_sect_read
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff8118b6e0-ffffffff8118b727: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool kallsyms_show_value(const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811baa40)
Location: kernel/kallsyms.c:820
Inline: False
Direct callers:
  - kernel/module/sysfs.c:module_sect_read
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff811baa40-ffffffff811baaab: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kallsyms_show_value(const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fc700)
Location: kernel/kallsyms.c:983
Inline: False
Direct callers:
  - kernel/module/sysfs.c:module_sect_read
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kallsyms.c:bpf_iter_ksym_init
  - kernel/kprobes.c:report_probe
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff811fc700-ffffffff811fc76b: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool kallsyms_show_value(const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ksyms_common.c (ffffffff811381f0)
Location: kernel/ksyms_common.c:28
Inline: False
Direct callers:
  - kernel/module/sysfs.c:module_sect_read
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kallsyms.c:bpf_iter_ksym_init
  - kernel/kprobes.c:report_probe
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff811381f0-ffffffff8113825b: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kallsyms_show_value(const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ksyms_common.c (ffffffff81143400)
Location: kernel/ksyms_common.c:28
Inline: False
Direct callers:
  - kernel/module/sysfs.c:module_sect_read
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kallsyms.c:bpf_iter_ksym_init
  - kernel/kprobes.c:report_probe
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_fill_link_info
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_perf_link_fill_link_info
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff81143400-ffffffff8114346b: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffff8000101c7418)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffff8000101c7418-ffff8000101c7474: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c040e340)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
c040e340-c040e3b0: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022f6d0)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
c00000000022f6d0-c00000000022f758: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffe0001476dc)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffe0001476dc-ffffffe000147728: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811504d0)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff811504d0-ffffffff81150512: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81143780)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff81143780-ffffffff811437c2: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114e380)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff8114e380-ffffffff8114e3c2: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kallsyms_show_value();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115b160)
Location: kernel/kallsyms.c:648
Inline: True
Direct callers:
  - kernel/kallsyms.c:kallsyms_open
  - kernel/kprobes.c:report_probe
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
```
**Symbols:**

```
ffffffff8115b160-ffffffff8115b1a2: kallsyms_show_value (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *cred</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
