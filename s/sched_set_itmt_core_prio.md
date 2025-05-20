# Function: <code>sched_set_itmt_core_prio</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81069960)
Location: arch/x86/kernel/itmt.c:199
Inline: False
```
**Symbols:**

```
ffffffff81069960-ffffffff810699f4: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81068bd0)
Location: arch/x86/kernel/itmt.c:197
Inline: False
```
**Symbols:**

```
ffffffff81068bd0-ffffffff81068c63: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff8106ce20)
Location: arch/x86/kernel/itmt.c:197
Inline: False
```
**Symbols:**

```
ffffffff8106ce20-ffffffff8106ce9c: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff8106fcc0)
Location: arch/x86/kernel/itmt.c:196
Inline: False
```
**Symbols:**

```
ffffffff8106fcc0-ffffffff8106fd3c: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81075d20)
Location: arch/x86/kernel/itmt.c:196
Inline: False
```
**Symbols:**

```
ffffffff81075d20-ffffffff81075d9c: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81079920)
Location: arch/x86/kernel/itmt.c:190
Inline: False
```
**Symbols:**

```
ffffffff81079920-ffffffff8107999a: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff8107a970)
Location: arch/x86/kernel/itmt.c:190
Inline: False
```
**Symbols:**

```
ffffffff8107a970-ffffffff8107a9ea: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81081d80)
Location: arch/x86/kernel/itmt.c:189
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_acpi_perf_limits
```
**Symbols:**

```
ffffffff81081d80-ffffffff81081dfa: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81081850)
Location: arch/x86/kernel/itmt.c:189
Inline: False
```
**Symbols:**

```
ffffffff81081850-ffffffff810818ca: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81082670)
Location: arch/x86/kernel/itmt.c:189
Inline: False
```
**Symbols:**

```
ffffffff81082670-ffffffff810826ea: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810916e0)
Location: arch/x86/kernel/itmt.c:189
Inline: False
```
**Symbols:**

```
ffffffff810916e0-ffffffff810917af: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810a2860)
Location: arch/x86/kernel/itmt.c:189
Inline: False
```
**Symbols:**

```
ffffffff810a2860-ffffffff810a293d: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810baaa0)
Location: arch/x86/kernel/itmt.c:189
Inline: False
```
**Symbols:**

```
ffffffff810baaa0-ffffffff810bab8e: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810bdc80)
Location: arch/x86/kernel/itmt.c:180
Inline: False
```
**Symbols:**

```
ffffffff810bdc80-ffffffff810bdcdb: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810c4e00)
Location: arch/x86/kernel/itmt.c:179
Inline: False
```
**Symbols:**

```
ffffffff810c4e00-ffffffff810c4e5b: sched_set_itmt_core_prio (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81079970)
Location: arch/x86/kernel/itmt.c:190
Inline: False
```
**Symbols:**

```
ffffffff81079970-ffffffff810799ea: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810690e0)
Location: arch/x86/kernel/itmt.c:190
Inline: False
```
**Symbols:**

```
ffffffff810690e0-ffffffff8106915a: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81079920)
Location: arch/x86/kernel/itmt.c:190
Inline: False
```
**Symbols:**

```
ffffffff81079920-ffffffff8107999a: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_set_itmt_core_prio(int prio, int core_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff8107ba20)
Location: arch/x86/kernel/itmt.c:190
Inline: False
```
**Symbols:**

```
ffffffff8107ba20-ffffffff8107ba9a: sched_set_itmt_core_prio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>int core_cpu</code>
</li>
</ul>
</details>
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
