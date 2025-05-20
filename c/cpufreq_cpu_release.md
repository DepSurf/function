# Function: <code>cpufreq_cpu_release</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:248
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81892570-ffffffff81892583: cpufreq_cpu_release.cold (STB_LOCAL)
ffffffff81890ef0-ffffffff81890f21: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c2fd0)
Location: drivers/cpufreq/cpufreq.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818c2fd0-ffffffff818c3000: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995d47)
Location: drivers/cpufreq/cpufreq.c:256
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff819953c0-ffffffff819953f3: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998bf7)
Location: drivers/cpufreq/cpufreq.c:256
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff819982b0-ffffffff819982e3: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197d66b)
Location: drivers/cpufreq/cpufreq.c:253
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff8197cda0-ffffffff8197cdd3: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a266f8)
Location: drivers/cpufreq/cpufreq.c:253
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81a25de0-ffffffff81a25e13: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b903a6)
Location: drivers/cpufreq/cpufreq.c:254
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81b8f750-ffffffff81b8f78f: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d30517)
Location: drivers/cpufreq/cpufreq.c:254
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81d2f780-ffffffff81d2f7bf: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d997fe)
Location: drivers/cpufreq/cpufreq.c:259
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81d98a60-ffffffff81d98a9f: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e5146e)
Location: drivers/cpufreq/cpufreq.c:260
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81e506e0-ffffffff81e5071f: cpufreq_cpu_release (STB_GLOBAL)
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
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b20870)
Location: drivers/cpufreq/cpufreq.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
**Symbols:**

```
ffff800010b20870-ffff800010b208b8: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfaf5c)
Location: drivers/cpufreq/cpufreq.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
**Symbols:**

```
c0bfaf5c-c0bfafa8: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c142d0)
Location: drivers/cpufreq/cpufreq.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
**Symbols:**

```
c000000000c142d0-c000000000c14334: cpufreq_cpu_release (STB_GLOBAL)
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
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818676f0)
Location: drivers/cpufreq/cpufreq.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818676f0-ffffffff81867720: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818303a0)
Location: drivers/cpufreq/cpufreq.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818303a0-ffffffff818303d0: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b8480)
Location: drivers/cpufreq/cpufreq.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818b8480-ffffffff818b84b0: cpufreq_cpu_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d4740)
Location: drivers/cpufreq/cpufreq.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818d4740-ffffffff818d4770: cpufreq_cpu_release (STB_GLOBAL)
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
