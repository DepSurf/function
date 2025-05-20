# Function: <code>intel_pmu_lbr_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810115b0)
Location: arch/x86/events/intel/lbr.c:202
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable
```
**Symbols:**

```
ffffffff810115b0-ffffffff81011670: intel_pmu_lbr_reset.part.1 (STB_LOCAL)
ffffffff81011670-ffffffff8101168b: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81011322)
Location: arch/x86/events/intel/lbr.c:213
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81010ef0-ffffffff81010fca: intel_pmu_lbr_reset.part.1 (STB_LOCAL)
ffffffff81010fd0-ffffffff81010feb: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810114a1)
Location: arch/x86/events/intel/lbr.c:213
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81011050-ffffffff8101112a: intel_pmu_lbr_reset.part.1 (STB_LOCAL)
ffffffff81011130-ffffffff8101114b: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8100faf1)
Location: arch/x86/events/intel/lbr.c:213
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff8100f700-ffffffff8100f7c1: intel_pmu_lbr_reset.part.1 (STB_LOCAL)
ffffffff8100f7d0-ffffffff8100f7ec: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81010291)
Location: arch/x86/events/intel/lbr.c:217
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff8100fea0-ffffffff8100ff61: intel_pmu_lbr_reset.part.1 (STB_LOCAL)
ffffffff8100ff70-ffffffff8100ff8c: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81010cf1)
Location: arch/x86/events/intel/lbr.c:217
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81010820-ffffffff810108e1: intel_pmu_lbr_reset.part.1 (STB_LOCAL)
ffffffff810108f0-ffffffff8101090b: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81010e00)
Location: arch/x86/events/intel/lbr.c:217
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81010e00-ffffffff81010eed: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810121e0)
Location: arch/x86/events/intel/lbr.c:217
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff810121e0-ffffffff810122c5: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012990)
Location: arch/x86/events/intel/lbr.c:217
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81012990-ffffffff81012a75: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810141c0)
Location: arch/x86/events/intel/lbr.c:217
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
```
**Symbols:**

```
ffffffff810141c0-ffffffff810142a2: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810149a8)
Location: arch/x86/events/intel/lbr.c:271
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff810143a0-ffffffff810143ea: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81015ade)
Location: arch/x86/events/intel/lbr.c:271
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff81015500-ffffffff8101554a: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810170ee)
Location: arch/x86/events/intel/lbr.c:271
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff81016b20-ffffffff81016b6a: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81018cc0)
Location: arch/x86/events/intel/lbr.c:249
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
```
**Symbols:**

```
ffffffff81018cc0-ffffffff81018d45: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101cb80)
Location: arch/x86/events/intel/lbr.c:189
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
```
**Symbols:**

```
ffffffff8101cb80-ffffffff8101cc23: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c840)
Location: arch/x86/events/intel/lbr.c:189
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
```
**Symbols:**

```
ffffffff8101c840-ffffffff8101c8e3: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810227d0)
Location: arch/x86/events/intel/lbr.c:189
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
```
**Symbols:**

```
ffffffff810227d0-ffffffff81022873: intel_pmu_lbr_reset (STB_GLOBAL)
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
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012990)
Location: arch/x86/events/intel/lbr.c:217
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81012990-ffffffff81012a75: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810118c0)
Location: arch/x86/events/intel/lbr.c:217
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff810118c0-ffffffff810119e9: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012950)
Location: arch/x86/events/intel/lbr.c:217
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81012950-ffffffff81012a35: intel_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012b70)
Location: arch/x86/events/intel/lbr.c:217
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81012b70-ffffffff81012c55: intel_pmu_lbr_reset (STB_GLOBAL)
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
