# Function: <code>stop_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811206d0)
Location: kernel/stop_machine.c:569
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init
  - kernel/cpu.c:_cpu_down
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - mm/page_alloc.c:build_all_zonelists
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811206d0-ffffffff811207d8: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81128620)
Location: kernel/stop_machine.c:573
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - mm/page_alloc.c:build_all_zonelists
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81128620-ffffffff8112872c: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811322d0)
Location: kernel/stop_machine.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - mm/page_alloc.c:build_all_zonelists
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811322d0-ffffffff811323dd: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133a40)
Location: kernel/stop_machine.c:591
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81133a40-ffffffff81133a7a: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811407f0)
Location: kernel/stop_machine.c:591
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811407f0-ffffffff8114082a: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114f130)
Location: kernel/stop_machine.c:619
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff8114f130-ffffffff8114f16a: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115be10)
Location: kernel/stop_machine.c:619
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff8115be10-ffffffff8115be4a: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811684d0)
Location: kernel/stop_machine.c:627
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811684d0-ffffffff8116850e: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81174380)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81174380-ffffffff811743be: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81186250)
Location: kernel/stop_machine.c:602
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81186250-ffffffff8118628e: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811833e0)
Location: kernel/stop_machine.c:623
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811833e0-ffffffff8118341e: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81184510)
Location: kernel/stop_machine.c:624
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81184510-ffffffff8118454e: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811ac840)
Location: kernel/stop_machine.c:624
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811ac840-ffffffff811ac87e: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811de340)
Location: kernel/stop_machine.c:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811de340-ffffffff811de384: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81223e80)
Location: kernel/stop_machine.c:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81223e80-ffffffff81223ec4: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8123a4a0)
Location: kernel/stop_machine.c:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff8123a4a0-ffffffff8123a4e4: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81254170)
Location: kernel/stop_machine.c:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81254170-ffffffff812541b4: stop_machine (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e8c28)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - arch/arm64/kernel/cpufeature.c:enable_cpu_capabilities
  - arch/arm64/kernel/alternative.c:apply_alternatives_all
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
```
**Symbols:**

```
ffff8000101e8c28-ffff8000101e8c7c: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0428cac)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - arch/arm/kernel/ftrace.c:arch_ftrace_update_code
  - arch/arm/mm/init.c:free_initmem
  - arch/arm/mm/init.c:mark_rodata_ro
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
```
**Symbols:**

```
c0428cac-c0428cf0: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000259810)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:split_kernel_mapping
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
```
**Symbols:**

```
c000000000259810-c000000000259870: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015db8e)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
```
**Symbols:**

```
ffffffe00015db8e-ffffffe00015dbc8: stop_machine (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c9a0)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff8116c9a0-ffffffff8116c9de: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115fb40)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
```
**Symbols:**

```
ffffffff8115fb40-ffffffff8115fb7e: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116a770)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff8116a770-ffffffff8116a7ae: stop_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177ee0)
Location: kernel/stop_machine.c:631
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore
  - kernel/time/timekeeping.c:timekeeping_notify
  - kernel/trace/ftrace.c:arch_ftrace_update_code
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81177ee0-ffffffff81177f1e: stop_machine (STB_GLOBAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
