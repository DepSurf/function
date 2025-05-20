# Function: <code>cpufreq_cpu_acquire</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81890f30)
Location: drivers/cpufreq/cpufreq.c:272
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81890f30-ffffffff81890f81: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c3000)
Location: drivers/cpufreq/cpufreq.c:275
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818c3000-ffffffff818c3051: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995400)
Location: drivers/cpufreq/cpufreq.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81995400-ffffffff81995465: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998bd5)
Location: drivers/cpufreq/cpufreq.c:280
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff819982f0-ffffffff81998355: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197cde0)
Location: drivers/cpufreq/cpufreq.c:277
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff8197cde0-ffffffff8197ce45: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a25e20)
Location: drivers/cpufreq/cpufreq.c:277
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81a25e20-ffffffff81a25e85: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8f790)
Location: drivers/cpufreq/cpufreq.c:278
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81b8f790-ffffffff81b8f7fb: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d304f5)
Location: drivers/cpufreq/cpufreq.c:278
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81d2f7d0-ffffffff81d2f83b: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d99795)
Location: drivers/cpufreq/cpufreq.c:283
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81d98ab0-ffffffff81d98b1b: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e51405)
Location: drivers/cpufreq/cpufreq.c:284
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81e50730-ffffffff81e5079b: cpufreq_cpu_acquire (STB_GLOBAL)
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
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b208b8)
Location: drivers/cpufreq/cpufreq.c:275
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
ffff800010b208b8-ffff800010b20920: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfafa8)
Location: drivers/cpufreq/cpufreq.c:275
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
c0bfafa8-c0bfaff4: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c14340)
Location: drivers/cpufreq/cpufreq.c:275
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
c000000000c14340-c000000000c143c0: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
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
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81867720)
Location: drivers/cpufreq/cpufreq.c:275
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81867720-ffffffff81867771: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818303d0)
Location: drivers/cpufreq/cpufreq.c:275
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818303d0-ffffffff81830421: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b84b0)
Location: drivers/cpufreq/cpufreq.c:275
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818b84b0-ffffffff818b8501: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_acquire(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d4770)
Location: drivers/cpufreq/cpufreq.c:275
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818d4770-ffffffff818d47c1: cpufreq_cpu_acquire (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
