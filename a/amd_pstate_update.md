# Function: <code>amd_pstate_update</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void amd_pstate_update(struct amd_cpudata *cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81b97460)
Location: drivers/cpufreq/amd-pstate.c:266
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/amd-pstate.c:amd_pstate_target
```
**Symbols:**

```
ffffffff81b97460-ffffffff81b975b6: amd_pstate_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_pstate_update(struct amd_cpudata *cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81d382e0)
Location: drivers/cpufreq/amd-pstate.c:214
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/amd-pstate.c:amd_pstate_target
```
**Symbols:**

```
ffffffff81d382e0-ffffffff81d3847a: amd_pstate_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_pstate_update(struct amd_cpudata *cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch, int gov_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81da26e0)
Location: drivers/cpufreq/amd-pstate.c:429
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq
```
**Symbols:**

```
ffffffff81da26e0-ffffffff81da287d: amd_pstate_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_pstate_update(struct amd_cpudata *cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch, int gov_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a7b0)
Location: drivers/cpufreq/amd-pstate.c:430
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq
```
**Symbols:**

```
ffffffff81e5a7b0-ffffffff81e5a98c: amd_pstate_update (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int gov_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
