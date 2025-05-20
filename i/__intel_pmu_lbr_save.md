# Function: <code>__intel_pmu_lbr_save</code>

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
In arch/x86/events/intel/lbr.c (ffffffff810116ed)
Location: arch/x86/events/intel/lbr.c:254
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
In arch/x86/events/intel/lbr.c (ffffffff8101109f)
Location: arch/x86/events/intel/lbr.c:357
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
In arch/x86/events/intel/lbr.c (ffffffff810111ec)
Location: arch/x86/events/intel/lbr.c:357
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
In arch/x86/events/intel/lbr.c (ffffffff8100f87e)
Location: arch/x86/events/intel/lbr.c:357
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
In arch/x86/events/intel/lbr.c (ffffffff81010100)
Location: arch/x86/events/intel/lbr.c:361
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
In arch/x86/events/intel/lbr.c (ffffffff81010b5c)
Location: arch/x86/events/intel/lbr.c:370
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
In arch/x86/events/intel/lbr.c (ffffffff8101107a)
Location: arch/x86/events/intel/lbr.c:388
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
In arch/x86/events/intel/lbr.c (ffffffff81012465)
Location: arch/x86/events/intel/lbr.c:388
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
In arch/x86/events/intel/lbr.c (ffffffff81012c15)
Location: arch/x86/events/intel/lbr.c:388
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810145ca)
Location: arch/x86/events/intel/lbr.c:388
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __intel_pmu_lbr_save(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013440)
Location: arch/x86/events/intel/lbr.c:582
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81013440-ffffffff810134e1: __intel_pmu_lbr_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __intel_pmu_lbr_save(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014660)
Location: arch/x86/events/intel/lbr.c:582
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81014660-ffffffff8101470e: __intel_pmu_lbr_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __intel_pmu_lbr_save(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81015a10)
Location: arch/x86/events/intel/lbr.c:582
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81015a10-ffffffff81015abe: __intel_pmu_lbr_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __intel_pmu_lbr_save(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81017b00)
Location: arch/x86/events/intel/lbr.c:561
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81017b00-ffffffff81017bb1: __intel_pmu_lbr_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __intel_pmu_lbr_save(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101bd80)
Location: arch/x86/events/intel/lbr.c:501
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff8101bd80-ffffffff8101be31: __intel_pmu_lbr_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __intel_pmu_lbr_save(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101ba50)
Location: arch/x86/events/intel/lbr.c:501
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff8101ba50-ffffffff8101bb01: __intel_pmu_lbr_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __intel_pmu_lbr_save(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810215d0)
Location: arch/x86/events/intel/lbr.c:501
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff810215d0-ffffffff81021681: __intel_pmu_lbr_save (STB_LOCAL)
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
In arch/x86/events/intel/lbr.c (ffffffff81012c15)
Location: arch/x86/events/intel/lbr.c:388
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
In arch/x86/events/intel/lbr.c (ffffffff81011bc3)
Location: arch/x86/events/intel/lbr.c:388
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
In arch/x86/events/intel/lbr.c (ffffffff81012bd5)
Location: arch/x86/events/intel/lbr.c:388
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
In arch/x86/events/intel/lbr.c (ffffffff81012df5)
Location: arch/x86/events/intel/lbr.c:388
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
