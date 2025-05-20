# Function: <code>intel_pstate_hwp_save_state</code>

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
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174dfa0)
Location: drivers/cpufreq/intel_pstate.c:957
Inline: False
```
**Symbols:**

```
ffffffff8174dfa0-ffffffff8174dfdb: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c8e0)
Location: drivers/cpufreq/intel_pstate.c:879
Inline: False
```
**Symbols:**

```
ffffffff8176c8e0-ffffffff8176c91b: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e25d0)
Location: drivers/cpufreq/intel_pstate.c:770
Inline: False
```
**Symbols:**

```
ffffffff817e25d0-ffffffff817e260b: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b400)
Location: drivers/cpufreq/intel_pstate.c:796
Inline: False
```
**Symbols:**

```
ffffffff8182b400-ffffffff8182b43b: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81857390)
Location: drivers/cpufreq/intel_pstate.c:858
Inline: False
```
**Symbols:**

```
ffffffff81857390-ffffffff818573cb: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189ac00)
Location: drivers/cpufreq/intel_pstate.c:858
Inline: False
```
**Symbols:**

```
ffffffff8189ac00-ffffffff8189ac3b: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818ccdb0)
Location: drivers/cpufreq/intel_pstate.c:857
Inline: False
```
**Symbols:**

```
ffffffff818ccdb0-ffffffff818ccdeb: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199f585)
Location: drivers/cpufreq/intel_pstate.c:863
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
```
**Symbols:**

```
ffffffff8199fda0-ffffffff8199fe59: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818709b0)
Location: drivers/cpufreq/intel_pstate.c:857
Inline: False
```
**Symbols:**

```
ffffffff818709b0-ffffffff818709eb: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839f30)
Location: drivers/cpufreq/intel_pstate.c:857
Inline: False
```
**Symbols:**

```
ffffffff81839f30-ffffffff81839f6b: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c2260)
Location: drivers/cpufreq/intel_pstate.c:857
Inline: False
```
**Symbols:**

```
ffffffff818c2260-ffffffff818c229b: intel_pstate_hwp_save_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_pstate_hwp_save_state(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818de570)
Location: drivers/cpufreq/intel_pstate.c:857
Inline: False
```
**Symbols:**

```
ffffffff818de570-ffffffff818de5ab: intel_pstate_hwp_save_state (STB_LOCAL)
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
