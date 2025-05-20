# Function: <code>intel_pstate_resume</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174e6c0)
Location: drivers/cpufreq/intel_pstate.c:969
Inline: True
```
**Symbols:**

```
ffffffff8174e6c0-ffffffff8174e722: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176cc50)
Location: drivers/cpufreq/intel_pstate.c:891
Inline: True
```
**Symbols:**

```
ffffffff8176cc50-ffffffff8176cca6: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2940)
Location: drivers/cpufreq/intel_pstate.c:782
Inline: True
```
**Symbols:**

```
ffffffff817e2940-ffffffff817e2996: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b7e0)
Location: drivers/cpufreq/intel_pstate.c:810
Inline: True
```
**Symbols:**

```
ffffffff8182b7e0-ffffffff8182b84e: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81857760)
Location: drivers/cpufreq/intel_pstate.c:872
Inline: True
```
**Symbols:**

```
ffffffff81857760-ffffffff818577ce: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189aed0)
Location: drivers/cpufreq/intel_pstate.c:872
Inline: True
```
**Symbols:**

```
ffffffff8189aed0-ffffffff8189af3e: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cd080)
Location: drivers/cpufreq/intel_pstate.c:871
Inline: True
```
**Symbols:**

```
ffffffff818cd080-ffffffff818cd0ee: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199ed20)
Location: drivers/cpufreq/intel_pstate.c:877
Inline: True
```
**Symbols:**

```
ffffffff8199ed20-ffffffff8199ed91: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a22e0)
Location: drivers/cpufreq/intel_pstate.c:971
Inline: False
```
**Symbols:**

```
ffffffff819a22e0-ffffffff819a23ad: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81987580)
Location: drivers/cpufreq/intel_pstate.c:973
Inline: False
```
**Symbols:**

```
ffffffff81987580-ffffffff8198764d: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1073
Inline: False
```
**Symbols:**

```
ffffffff81a31280-ffffffff81a31359: intel_pstate_resume (STB_LOCAL)
ffffffff81d2ca3d-ffffffff81d2ca52: intel_pstate_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1103
Inline: False
```
**Symbols:**

```
ffffffff81b9d490-ffffffff81b9d57d: intel_pstate_resume (STB_LOCAL)
ffffffff81ef8d87-ffffffff81ef8d9c: intel_pstate_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1078
Inline: False
```
**Symbols:**

```
ffffffff81d3eed0-ffffffff81d3efbd: intel_pstate_resume (STB_LOCAL)
ffffffff820a9134-ffffffff820a9149: intel_pstate_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1098
Inline: False
```
**Symbols:**

```
ffffffff81da9a50-ffffffff81da9b3d: intel_pstate_resume (STB_LOCAL)
ffffffff8212a53d-ffffffff8212a552: intel_pstate_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:1122
Inline: False
```
**Symbols:**

```
ffffffff81e61fe0-ffffffff81e620cd: intel_pstate_resume (STB_LOCAL)
ffffffff8220c332-ffffffff8220c347: intel_pstate_resume.cold (STB_LOCAL)
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
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81870c80)
Location: drivers/cpufreq/intel_pstate.c:871
Inline: True
```
**Symbols:**

```
ffffffff81870c80-ffffffff81870cee: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8183a200)
Location: drivers/cpufreq/intel_pstate.c:871
Inline: True
```
**Symbols:**

```
ffffffff8183a200-ffffffff8183a26e: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c2530)
Location: drivers/cpufreq/intel_pstate.c:871
Inline: True
```
**Symbols:**

```
ffffffff818c2530-ffffffff818c259e: intel_pstate_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_resume(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818de840)
Location: drivers/cpufreq/intel_pstate.c:871
Inline: True
```
**Symbols:**

```
ffffffff818de840-ffffffff818de8ae: intel_pstate_resume (STB_LOCAL)
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
