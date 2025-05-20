# Function: <code>smp_call_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103e00)
Location: kernel/smp.c:488
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/xen/smp.c:xen_stop_other_cpus
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81103e00-ffffffff81103e26: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110b24c)
Location: kernel/smp.c:472
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp.c:xen_stop_other_cpus
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8110b210-ffffffff8110b236: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112c8c)
Location: kernel/smp.c:476
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp.c:xen_stop_other_cpus
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81112bf0-ffffffff81112c16: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111419c)
Location: kernel/smp.c:487
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81114100-ffffffff81114126: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f70f)
Location: kernel/smp.c:489
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/memory.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8111f670-ffffffff8111f696: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112ca3f)
Location: kernel/smp.c:489
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/memory.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8112c9a0-ffffffff8112c9c6: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113830f)
Location: kernel/smp.c:489
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81138270-ffffffff81138296: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114346f)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81143430-ffffffff81143454: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114efaf)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8114ef70-ffffffff8114ef94: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115fa6f)
Location: kernel/smp.c:596
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8115f910-ffffffff8115f937: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115ba0f)
Location: kernel/smp.c:734
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8115b8b0-ffffffff8115b8d7: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115c9cf)
Location: kernel/smp.c:1010
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8115c970-ffffffff8115c997: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81181b7f)
Location: kernel/smp.c:1012
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81181b20-ffffffff81181b47: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b825f)
Location: kernel/smp.c:1031
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff811b8190-ffffffff811b81ec: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f955f)
Location: kernel/smp.c:1030
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff811f9470-ffffffff811f94cc: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120e3df)
Location: kernel/smp.c:878
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8120e2f0-ffffffff8120e34c: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81225b6f)
Location: kernel/smp.c:898
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81225a80-ffffffff81225adc: smp_call_function (STB_GLOBAL)
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
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bd68c)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
  - drivers/tty/sysrq.c:sysrq_showregs_othercpus
```
**Symbols:**

```
ffff8000101bd5b0-ffff8000101bd600: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c04057fc)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
c040575c-c0405794: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000223ae0)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/powerpc/kernel/dawr.c:dawr_write_file_bool
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
c0000000002239c0-c000000000223a14: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe000140c00)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - drivers/tty/sysrq.c:sysrq_showregs_othercpus
```
**Symbols:**

```
ffffffe000140b52-ffffffe000140b96: smp_call_function (STB_GLOBAL)
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
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811475cf)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81147590-ffffffff811475b4: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a8ff)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8113a870-ffffffff8113a894: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114547f)
Location: kernel/smp.c:506
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81145440-ffffffff81145464: smp_call_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smp_call_function(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81152020)
Location: kernel/smp.c:506
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81152020-ffffffff8115205b: smp_call_function (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
