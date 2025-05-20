# Function: <code>intel_pstate_cpu_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8171b8b0)
Location: drivers/cpufreq/intel_pstate.c:1578
Inline: False
```
**Symbols:**

```
ffffffff8171b8b0-ffffffff8171b8df: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174db00)
Location: drivers/cpufreq/intel_pstate.c:2111
Inline: False
```
**Symbols:**

```
ffffffff8174db00-ffffffff8174db38: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c120)
Location: drivers/cpufreq/intel_pstate.c:2101
Inline: False
```
**Symbols:**

```
ffffffff8176c120-ffffffff8176c158: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e1f90)
Location: drivers/cpufreq/intel_pstate.c:1864
Inline: False
```
**Symbols:**

```
ffffffff817e1f90-ffffffff817e1fc8: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182acf0)
Location: drivers/cpufreq/intel_pstate.c:2055
Inline: False
```
**Symbols:**

```
ffffffff8182acf0-ffffffff8182ad28: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81856c60)
Location: drivers/cpufreq/intel_pstate.c:2121
Inline: False
```
**Symbols:**

```
ffffffff81856c60-ffffffff81856c98: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a3b0)
Location: drivers/cpufreq/intel_pstate.c:2147
Inline: False
```
**Symbols:**

```
ffffffff8189a3b0-ffffffff8189a3e8: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc810)
Location: drivers/cpufreq/intel_pstate.c:2189
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff818cc3b0-ffffffff818cc3e8: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199f160)
Location: drivers/cpufreq/intel_pstate.c:2201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff8199eda0-ffffffff8199eddb: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a1880)
Location: drivers/cpufreq/intel_pstate.c:2395
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff819a09b0-ffffffff819a09f6: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81986860)
Location: drivers/cpufreq/intel_pstate.c:2384
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff81985620-ffffffff81985666: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a30870)
Location: drivers/cpufreq/intel_pstate.c:2556
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff81a2f080-ffffffff81a2f0c3: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9c200)
Location: drivers/cpufreq/intel_pstate.c:2722
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff81b9ab20-ffffffff81b9ab77: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3dd70)
Location: drivers/cpufreq/intel_pstate.c:2686
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff81d3c3f0-ffffffff81d3c447: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da86c0)
Location: drivers/cpufreq/intel_pstate.c:2712
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff81da6f50-ffffffff81da6fa7: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e604a0)
Location: drivers/cpufreq/intel_pstate.c:2736
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff81e5ebc0-ffffffff81e5ec17: intel_pstate_cpu_exit (STB_LOCAL)
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
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81870410)
Location: drivers/cpufreq/intel_pstate.c:2189
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff8186ffb0-ffffffff8186ffe8: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839990)
Location: drivers/cpufreq/intel_pstate.c:2189
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff81839530-ffffffff81839568: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1cc0)
Location: drivers/cpufreq/intel_pstate.c:2189
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff818c1860-ffffffff818c1898: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_cpu_exit(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818ddfd0)
Location: drivers/cpufreq/intel_pstate.c:2189
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
```
**Symbols:**

```
ffffffff818ddb70-ffffffff818ddba8: intel_pstate_cpu_exit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
