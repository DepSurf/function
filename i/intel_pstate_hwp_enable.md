# Function: <code>intel_pstate_hwp_enable</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff816baaf0)
Location: drivers/cpufreq/intel_pstate.c:526
Inline: True
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
In drivers/cpufreq/intel_pstate.c (ffffffff8171c930)
Location: drivers/cpufreq/intel_pstate.c:806
Inline: True
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
In drivers/cpufreq/intel_pstate.c (ffffffff8174e8db)
Location: drivers/cpufreq/intel_pstate.c:1226
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff8176d07a)
Location: drivers/cpufreq/intel_pstate.c:1256
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e2f8b)
Location: drivers/cpufreq/intel_pstate.c:1071
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b440)
Location: drivers/cpufreq/intel_pstate.c:1132
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff8182b440-ffffffff8182b49b: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818573d0)
Location: drivers/cpufreq/intel_pstate.c:1195
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff818573d0-ffffffff8185742b: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189ae60)
Location: drivers/cpufreq/intel_pstate.c:1232
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff8189ae60-ffffffff8189aec4: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cd010)
Location: drivers/cpufreq/intel_pstate.c:1278
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff818cd010-ffffffff818cd074: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199e720)
Location: drivers/cpufreq/intel_pstate.c:1285
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff8199e720-ffffffff8199e78a: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a1210)
Location: drivers/cpufreq/intel_pstate.c:1452
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
```
**Symbols:**

```
ffffffff819a1210-ffffffff819a1271: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81985d40)
Location: drivers/cpufreq/intel_pstate.c:1452
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
```
**Symbols:**

```
ffffffff81985d40-ffffffff81985da1: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a2f9b0)
Location: drivers/cpufreq/intel_pstate.c:1563
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
```
**Symbols:**

```
ffffffff81a2f9b0-ffffffff81a2fa11: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9c810)
Location: drivers/cpufreq/intel_pstate.c:1727
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
```
**Symbols:**

```
ffffffff81b9c810-ffffffff81b9c9b4: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1702
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
```
**Symbols:**

```
ffffffff81d3e2f0-ffffffff81d3e4bc: intel_pstate_hwp_enable (STB_LOCAL)
ffffffff820a90f5-ffffffff820a910a: intel_pstate_hwp_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1725
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
```
**Symbols:**

```
ffffffff81da8e80-ffffffff81da904c: intel_pstate_hwp_enable (STB_LOCAL)
ffffffff8212a4fe-ffffffff8212a513: intel_pstate_hwp_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1749
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
```
**Symbols:**

```
ffffffff81e60e00-ffffffff81e60fca: intel_pstate_hwp_enable (STB_LOCAL)
ffffffff8220c2c3-ffffffff8220c2d8: intel_pstate_hwp_enable.cold (STB_LOCAL)
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
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81870c10)
Location: drivers/cpufreq/intel_pstate.c:1278
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff81870c10-ffffffff81870c74: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8183a190)
Location: drivers/cpufreq/intel_pstate.c:1278
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff8183a190-ffffffff8183a1f4: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c24c0)
Location: drivers/cpufreq/intel_pstate.c:1278
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff818c24c0-ffffffff818c2524: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void intel_pstate_hwp_enable(struct cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818de7d0)
Location: drivers/cpufreq/intel_pstate.c:1278
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff818de7d0-ffffffff818de834: intel_pstate_hwp_enable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
