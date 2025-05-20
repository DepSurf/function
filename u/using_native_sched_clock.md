# Function: <code>using_native_sched_clock</code>

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
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034e80)
Location: arch/x86/kernel/tsc.c:230
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81034e80-ffffffff81034e94: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810371e0)
Location: arch/x86/kernel/tsc.c:230
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff810371e0-ffffffff810371f4: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037c88)
Location: arch/x86/kernel/tsc.c:231
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff810381e0-ffffffff810381ef: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81038fa8)
Location: arch/x86/kernel/tsc.c:248
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81039920-ffffffff8103992f: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103b535)
Location: arch/x86/kernel/tsc.c:248
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103beb0-ffffffff8103bebf: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103bce5)
Location: arch/x86/kernel/tsc.c:248
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103c670-ffffffff8103c67f: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f347)
Location: arch/x86/kernel/tsc.c:255
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103f460-ffffffff8103f46f: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f407)
Location: arch/x86/kernel/tsc.c:255
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103f520-ffffffff8103f52f: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81040a22)
Location: arch/x86/kernel/tsc.c:256
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81040e90-ffffffff81040ea1: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81046b12)
Location: arch/x86/kernel/tsc.c:256
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81046ff0-ffffffff81047001: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8104fbfd)
Location: arch/x86/kernel/tsc.c:256
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8104fdb0-ffffffff8104fdc5: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff83e79543)
Location: arch/x86/kernel/tsc.c:256
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8105d150-ffffffff8105d165: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8369bcaa)
Location: arch/x86/kernel/tsc.c:269
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8105e6a0-ffffffff8105e6b5: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff838cb9ca)
Location: arch/x86/kernel/tsc.c:269
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff81065760-ffffffff81065775: using_native_sched_clock (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103be45)
Location: arch/x86/kernel/tsc.c:248
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103c7d0-ffffffff8103c7df: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102bc85)
Location: arch/x86/kernel/tsc.c:248
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8102bec0-ffffffff8102becf: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103bca5)
Location: arch/x86/kernel/tsc.c:248
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103c630-ffffffff8103c63f: using_native_sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool using_native_sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103ccf5)
Location: arch/x86/kernel/tsc.c:248
Inline: True
Direct callers:
  - arch/x86/events/core.c:arch_perf_update_userpage
```
**Symbols:**

```
ffffffff8103d6c0-ffffffff8103d6cf: using_native_sched_clock (STB_GLOBAL)
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
