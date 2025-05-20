# Function: <code>perf_sched_cb_dec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117f550)
Location: kernel/events/core.c:2608
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable
```
**Symbols:**

```
ffffffff8117f550-ffffffff8117f55d: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811912f0)
Location: kernel/events/core.c:2845
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable
```
**Symbols:**

```
ffffffff811912f0-ffffffff811912fd: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a09f0)
Location: kernel/events/core.c:2911
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff811a09f0-ffffffff811a0a53: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a83c0)
Location: kernel/events/core.c:2994
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff811a83c0-ffffffff811a8419: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bbb30)
Location: kernel/events/core.c:2898
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff811bbb30-ffffffff811bbb89: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dbcc0)
Location: kernel/events/core.c:3142
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff811dbcc0-ffffffff811dbd19: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ec080)
Location: kernel/events/core.c:3137
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff811ec080-ffffffff811ec0d9: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81203a90)
Location: kernel/events/core.c:3161
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff81203a90-ffffffff81203ae4: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210680)
Location: kernel/events/core.c:3246
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff81210680-ffffffff812106d4: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123c890)
Location: kernel/events/core.c:3427
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff8123c890-ffffffff8123c8e4: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81246b30)
Location: kernel/events/core.c:3485
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff81246b30-ffffffff81246b84: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124a8a0)
Location: kernel/events/core.c:3507
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff8124a8a0-ffffffff8124a8f4: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81284150)
Location: kernel/events/core.c:3570
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff81284150-ffffffff812841a4: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d8500)
Location: kernel/events/core.c:3481
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_del_event
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff812d8500-ffffffff812d856c: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81340a40)
Location: kernel/events/core.c:3548
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_brs_del
  - arch/x86/events/amd/core.c:amd_pmu_brs_del
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_del
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff81340a40-ffffffff81340aa6: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813719e0)
Location: kernel/events/core.c:3548
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_brs_del
  - arch/x86/events/amd/core.c:amd_pmu_brs_del
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_del
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff813719e0-ffffffff81371a46: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139ace0)
Location: kernel/events/core.c:3592
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_brs_del
  - arch/x86/events/amd/core.c:amd_pmu_brs_del
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_del
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff8139ace0-ffffffff8139ad46: perf_sched_cb_dec (STB_GLOBAL)
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
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029ab68)
Location: kernel/events/core.c:3246
Inline: False
```
**Symbols:**

```
ffff80001029ab68-ffff80001029abd4: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c9fc8)
Location: kernel/events/core.c:3246
Inline: False
```
**Symbols:**

```
c04c9fc8-c04ca040: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034a6e0)
Location: kernel/events/core.c:3246
Inline: False
Direct callers:
  - arch/powerpc/perf/core-book3s.c:power_pmu_del
```
**Symbols:**

```
c00000000034a6e0-c00000000034a798: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cd27c)
Location: kernel/events/core.c:3246
Inline: False
```
**Symbols:**

```
ffffffe0001cd27c-ffffffe0001cd2f0: perf_sched_cb_dec (STB_GLOBAL)
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
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208cd0)
Location: kernel/events/core.c:3246
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff81208cd0-ffffffff81208d24: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fba60)
Location: kernel/events/core.c:3246
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff811fba60-ffffffff811fbab4: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81206a70)
Location: kernel/events/core.c:3246
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff81206a70-ffffffff81206ac4: perf_sched_cb_dec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_sched_cb_dec(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812157e0)
Location: kernel/events/core.c:3246
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
```
**Symbols:**

```
ffffffff812157e0-ffffffff81215834: perf_sched_cb_dec (STB_GLOBAL)
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
