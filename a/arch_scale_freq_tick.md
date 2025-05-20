# Function: <code>arch_scale_freq_tick</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void arch_scale_freq_tick();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:2086
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff8106bbbb-ffffffff8106bbe4: arch_scale_freq_tick.cold (STB_LOCAL)
ffffffff8106b750-ffffffff8106b817: arch_scale_freq_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void arch_scale_freq_tick();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:2164
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81bd6b28-ffffffff81bd6b51: arch_scale_freq_tick.cold (STB_LOCAL)
ffffffff8106d400-ffffffff8106d4c8: arch_scale_freq_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void arch_scale_freq_tick();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:2160
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81bc8d02-ffffffff81bc8d2b: arch_scale_freq_tick.cold (STB_LOCAL)
ffffffff8106de70-ffffffff8106df35: arch_scale_freq_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void arch_scale_freq_tick();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:2167
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81c9d6bc-ffffffff81c9d6e5: arch_scale_freq_tick.cold (STB_LOCAL)
ffffffff81079690-ffffffff81079755: arch_scale_freq_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void arch_scale_freq_tick();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/kernel/cpu/aperfmperf.c:373
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81e4a226-ffffffff81e4a24f: arch_scale_freq_tick.cold (STB_LOCAL)
ffffffff81061080-ffffffff81061165: arch_scale_freq_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_scale_freq_tick();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106f9b0)
Location: arch/x86/kernel/cpu/aperfmperf.c:382
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff8106f9b0-ffffffff8106faca: arch_scale_freq_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_scale_freq_tick();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810715b0)
Location: arch/x86/kernel/cpu/aperfmperf.c:382
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810715b0-ffffffff810716ca: arch_scale_freq_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_scale_freq_tick();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078d70)
Location: arch/x86/kernel/cpu/aperfmperf.c:382
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81078d70-ffffffff81078e8a: arch_scale_freq_tick (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
