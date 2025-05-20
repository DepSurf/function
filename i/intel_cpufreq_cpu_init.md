# Function: <code>intel_cpufreq_cpu_init</code>

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
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174f300)
Location: drivers/cpufreq/intel_pstate.c:2275
Inline: False
```
**Symbols:**

```
ffffffff8174f300-ffffffff8174f335: intel_cpufreq_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d740)
Location: drivers/cpufreq/intel_pstate.c:2236
Inline: True
```
**Symbols:**

```
ffffffff8176d740-ffffffff8176d782: intel_cpufreq_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e34e0)
Location: drivers/cpufreq/intel_pstate.c:1997
Inline: True
```
**Symbols:**

```
ffffffff817e34e0-ffffffff817e3522: intel_cpufreq_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182c9f0)
Location: drivers/cpufreq/intel_pstate.c:2230
Inline: True
```
**Symbols:**

```
ffffffff8182c9f0-ffffffff8182ca32: intel_cpufreq_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818585c0)
Location: drivers/cpufreq/intel_pstate.c:2305
Inline: True
```
**Symbols:**

```
ffffffff818585c0-ffffffff81858602: intel_cpufreq_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189be80)
Location: drivers/cpufreq/intel_pstate.c:2333
Inline: True
```
**Symbols:**

```
ffffffff8189be80-ffffffff8189bec2: intel_cpufreq_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2375
Inline: False
```
**Symbols:**

```
ffffffff818cdff0-ffffffff818ce1b6: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff818ce915-ffffffff818ce95f: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2383
Inline: False
```
**Symbols:**

```
ffffffff8199ff50-ffffffff819a0116: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff819a0dde-ffffffff819a0e28: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2683
Inline: False
```
**Symbols:**

```
ffffffff819a2d80-ffffffff819a2f99: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff81c29fb6-ffffffff81c2a000: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2662
Inline: False
```
**Symbols:**

```
ffffffff81987880-ffffffff81987a9f: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff81c1c39a-ffffffff81c1c3d6: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2833
Inline: False
```
**Symbols:**

```
ffffffff81a314f0-ffffffff81a316ea: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff81d2ca67-ffffffff81d2cab8: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2999
Inline: False
```
**Symbols:**

```
ffffffff81b9d760-ffffffff81b9d947: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff81ef8db1-ffffffff81ef8ded: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2963
Inline: False
```
**Symbols:**

```
ffffffff81d3f1e0-ffffffff81d3f41c: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff820a915e-ffffffff820a9179: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2989
Inline: False
```
**Symbols:**

```
ffffffff81da9d60-ffffffff81da9f95: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff8212a567-ffffffff8212a582: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:3005
Inline: False
```
**Symbols:**

```
ffffffff81e61c30-ffffffff81e61e94: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff8220c317-ffffffff8220c332: intel_cpufreq_cpu_init.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2375
Inline: False
```
**Symbols:**

```
ffffffff81871bf0-ffffffff81871db6: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff81872515-ffffffff8187255f: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2375
Inline: False
```
**Symbols:**

```
ffffffff8183b3e0-ffffffff8183b5a6: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff8183c1bb-ffffffff8183c205: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2375
Inline: False
```
**Symbols:**

```
ffffffff818c34a0-ffffffff818c3666: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff818c3dc5-ffffffff818c3e0f: intel_cpufreq_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_init(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2375
Inline: False
```
**Symbols:**

```
ffffffff818df800-ffffffff818df9c6: intel_cpufreq_cpu_init (STB_LOCAL)
ffffffff818e0135-ffffffff818e017f: intel_cpufreq_cpu_init.cold (STB_LOCAL)
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
