# Function: <code>arch_set_freq_scale</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d66d0)
Location: drivers/cpufreq/cpufreq.c:164
Inline: False
```
**Symbols:**

```
ffffffff817d66d0-ffffffff817d66db: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8181f3c0)
Location: drivers/cpufreq/cpufreq.c:155
Inline: False
```
**Symbols:**

```
ffffffff8181f3c0-ffffffff8181f3cb: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184b260)
Location: drivers/cpufreq/cpufreq.c:155
Inline: False
```
**Symbols:**

```
ffffffff8184b260-ffffffff8184b26b: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188e320)
Location: drivers/cpufreq/cpufreq.c:149
Inline: False
```
**Symbols:**

```
ffffffff8188e320-ffffffff8188e32b: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c04b0)
Location: drivers/cpufreq/cpufreq.c:152
Inline: False
```
**Symbols:**

```
ffffffff818c04b0-ffffffff818c04bb: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81992440)
Location: drivers/cpufreq/cpufreq.c:157
Inline: False
```
**Symbols:**

```
ffffffff81992440-ffffffff8199244b: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:1048
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:1042
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:1094
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:1206
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:1210
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:1213
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:1200
Inline: True
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
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (ffff8000109200c0)
Location: drivers/base/arch_topology.c:26
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:set_target
```
**Symbols:**

```
ffff8000109200c0-ffff800010920144: arch_set_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (c0a050ac)
Location: drivers/base/arch_topology.c:26
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:set_target
```
**Symbols:**

```
c0a050ac-c0a05114: arch_set_freq_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c0f8a0)
Location: drivers/cpufreq/cpufreq.c:152
Inline: False
```
**Symbols:**

```
c000000000c0f8a0-c000000000c0f8ac: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (ffffffe00059edae)
Location: drivers/base/arch_topology.c:26
Inline: False
```
**Symbols:**

```
ffffffe00059edae-ffffffe00059ee28: arch_set_freq_scale (STB_GLOBAL)
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
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81864bd0)
Location: drivers/cpufreq/cpufreq.c:152
Inline: False
```
**Symbols:**

```
ffffffff81864bd0-ffffffff81864bdb: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182d880)
Location: drivers/cpufreq/cpufreq.c:152
Inline: False
```
**Symbols:**

```
ffffffff8182d880-ffffffff8182d88b: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b5960)
Location: drivers/cpufreq/cpufreq.c:152
Inline: False
```
**Symbols:**

```
ffffffff818b5960-ffffffff818b596b: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_set_freq_scale(struct cpumask *cpus, long unsigned int cur_freq, long unsigned int max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d1c10)
Location: drivers/cpufreq/cpufreq.c:152
Inline: False
```
**Symbols:**

```
ffffffff818d1c10-ffffffff818d1c1b: arch_set_freq_scale (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
