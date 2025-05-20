# Function: <code>stop_machine_cpuslocked</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133950)
Location: kernel/stop_machine.c:555
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
  - mm/page_alloc.c:build_all_zonelists
```
**Symbols:**

```
ffffffff81133950-ffffffff81133a37: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81140700)
Location: kernel/stop_machine.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff81140700-ffffffff811407e9: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114f040)
Location: kernel/stop_machine.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff8114f040-ffffffff8114f129: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115bd20)
Location: kernel/stop_machine.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff8115bd20-ffffffff8115be09: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811683e0)
Location: kernel/stop_machine.c:591
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff811683e0-ffffffff811684c6: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811742a0)
Location: kernel/stop_machine.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff811742a0-ffffffff8117437d: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811860e0)
Location: kernel/stop_machine.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff811860e0-ffffffff81186244: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81183270)
Location: kernel/stop_machine.c:587
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff81183270-ffffffff811833d4: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81184390)
Location: kernel/stop_machine.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff81184390-ffffffff81184503: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff81cb3447-ffffffff81cb345c: stop_machine_cpuslocked.cold (STB_LOCAL)
ffffffff811ac6b0-ffffffff811ac831: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:586
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff81e64278-ffffffff81e6428d: stop_machine_cpuslocked.cold (STB_LOCAL)
ffffffff811de190-ffffffff811de333: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:586
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff8205c592-ffffffff8205c5a7: stop_machine_cpuslocked.cold (STB_LOCAL)
ffffffff81223cc0-ffffffff81223e65: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:586
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff820daeef-ffffffff820daf04: stop_machine_cpuslocked.cold (STB_LOCAL)
ffffffff8123a320-ffffffff8123a48f: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:586
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff821b6bed-ffffffff821b6c02: stop_machine_cpuslocked.cold (STB_LOCAL)
ffffffff81253ff0-ffffffff8125415f: stop_machine_cpuslocked (STB_GLOBAL)
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e8b38)
Location: kernel/stop_machine.c:595
Inline: False
Direct callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffff8000101e8b38-ffff8000101e8c28: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0428b98)
Location: kernel/stop_machine.c:595
Inline: True
Direct callers:
  - arch/arm/kernel/patch.c:patch_text
  - arch/arm/probes/kprobes/core.c:arch_disarm_kprobe
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
c0428b98-c0428cac: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000259680)
Location: kernel/stop_machine.c:595
Inline: True
Direct callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/platforms/powernv/subcore.c:set_subcores_per_core
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
c000000000259680-c000000000259804: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015dae2)
Location: kernel/stop_machine.c:595
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffe00015dae2-ffffffe00015db8e: stop_machine_cpuslocked (STB_GLOBAL)
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c8c0)
Location: kernel/stop_machine.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff8116c8c0-ffffffff8116c99d: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115fa80)
Location: kernel/stop_machine.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff8115fa80-ffffffff8115fb40: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116a690)
Location: kernel/stop_machine.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff8116a690-ffffffff8116a76d: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void *data, const struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177e00)
Location: kernel/stop_machine.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - kernel/cpu.c:takedown_cpu
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff81177e00-ffffffff81177edd: stop_machine_cpuslocked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
