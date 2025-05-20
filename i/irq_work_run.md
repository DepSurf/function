# Function: <code>irq_work_run</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81170ec0)
Location: kernel/irq_work.c:169
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff81170ec0-ffffffff81170eee: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8117e5b0)
Location: kernel/irq_work.c:169
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff8117e5b0-ffffffff8117e5de: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8118a1c0)
Location: kernel/irq_work.c:169
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff8118a1c0-ffffffff8118a1ee: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8118ccd0)
Location: kernel/irq_work.c:169
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff8118ccd0-ffffffff8118ccfe: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8119a6e0)
Location: kernel/irq_work.c:168
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff8119a6e0-ffffffff8119a70e: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811b0120)
Location: kernel/irq_work.c:168
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811b0120-ffffffff811b014e: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811be730)
Location: kernel/irq_work.c:168
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811be730-ffffffff811be75e: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811ce2d0)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811ce2d0-ffffffff811ce2fe: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811da8f0)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811da8f0-ffffffff811da91e: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f7580)
Location: kernel/irq_work.c:177
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff811f7580-ffffffff811f75ae: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f60e0)
Location: kernel/irq_work.c:182
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff811f60e0-ffffffff811f610e: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f6fd0)
Location: kernel/irq_work.c:184
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff811f6fd0-ffffffff811f6ffe: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812285a0)
Location: kernel/irq_work.c:184
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff812285a0-ffffffff812285ce: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81269660)
Location: kernel/irq_work.c:249
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81269660-ffffffff81269694: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812be530)
Location: kernel/irq_work.c:249
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff812be530-ffffffff812be564: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812e5170)
Location: kernel/irq_work.c:259
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff812e5170-ffffffff812e51a4: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81303220)
Location: kernel/irq_work.c:259
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81303220-ffffffff81303254: irq_work_run (STB_GLOBAL)
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
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffff80001025b0c8)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/perf_event.c:armv8pmu_handle_irq
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffff80001025b0c8-ffff80001025b108: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c048e15c)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
c048e15c-c048e194: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c0000000002fecf0)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/powerpc/kernel/time.c:timer_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
c0000000002fecf0-c0000000002fed40: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffe00019a0c4)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffe00019a0c4-ffffffe00019a118: irq_work_run (STB_GLOBAL)
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
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d2f10)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811d2f10-ffffffff811d2f3e: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811c5cd0)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811c5cd0-ffffffff811c5cfe: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d0ce0)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811d0ce0-ffffffff811d0d0e: irq_work_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_work_run();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811defa0)
Location: kernel/irq_work.c:178
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811defa0-ffffffff811defce: irq_work_run (STB_GLOBAL)
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
