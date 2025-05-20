# Function: <code>__intel_pmu_lbr_restore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810117ca)
Location: arch/x86/events/intel/lbr.c:229
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81011170)
Location: arch/x86/events/intel/lbr.c:331
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810112c0)
Location: arch/x86/events/intel/lbr.c:331
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8100f954)
Location: arch/x86/events/intel/lbr.c:331
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101001e)
Location: arch/x86/events/intel/lbr.c:335
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101099e)
Location: arch/x86/events/intel/lbr.c:335
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81010f81)
Location: arch/x86/events/intel/lbr.c:340
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012361)
Location: arch/x86/events/intel/lbr.c:340
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012b11)
Location: arch/x86/events/intel/lbr.c:340
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __intel_pmu_lbr_restore(struct x86_perf_task_context *task_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810142b0)
Location: arch/x86/events/intel/lbr.c:340
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff810142b0-ffffffff810144f9: __intel_pmu_lbr_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __intel_pmu_lbr_restore(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014180)
Location: arch/x86/events/intel/lbr.c:505
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81014180-ffffffff810142b4: __intel_pmu_lbr_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __intel_pmu_lbr_restore(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810152e0)
Location: arch/x86/events/intel/lbr.c:505
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff810152e0-ffffffff8101541b: __intel_pmu_lbr_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __intel_pmu_lbr_restore(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81016900)
Location: arch/x86/events/intel/lbr.c:505
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81016900-ffffffff81016a35: __intel_pmu_lbr_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __intel_pmu_lbr_restore(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81018d50)
Location: arch/x86/events/intel/lbr.c:484
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81018d50-ffffffff81018e7f: __intel_pmu_lbr_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __intel_pmu_lbr_restore(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101cc40)
Location: arch/x86/events/intel/lbr.c:424
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff8101cc40-ffffffff8101cd6c: __intel_pmu_lbr_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __intel_pmu_lbr_restore(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c900)
Location: arch/x86/events/intel/lbr.c:424
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff8101c900-ffffffff8101ca2c: __intel_pmu_lbr_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __intel_pmu_lbr_restore(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81022890)
Location: arch/x86/events/intel/lbr.c:424
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81022890-ffffffff810229bc: __intel_pmu_lbr_restore (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012b11)
Location: arch/x86/events/intel/lbr.c:340
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81011a81)
Location: arch/x86/events/intel/lbr.c:340
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012ad1)
Location: arch/x86/events/intel/lbr.c:340
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012cf1)
Location: arch/x86/events/intel/lbr.c:340
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct x86_perf_task_context *task_ctx</code>
</li>
</ul>
</details>
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
