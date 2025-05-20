# Function: <code>pstate_update_perf</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pstate_update_perf(struct amd_cpudata *cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81b96e30)
Location: drivers/cpufreq/amd-pstate.c:200
Inline: True
```
**Symbols:**

```
ffffffff81b96e30-ffffffff81b96e97: pstate_update_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pstate_update_perf(struct amd_cpudata *cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81d37b70)
Location: drivers/cpufreq/amd-pstate.c:148
Inline: True
```
**Symbols:**

```
ffffffff81d37b70-ffffffff81d37bd7: pstate_update_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pstate_update_perf(struct amd_cpudata *cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81da1a20)
Location: drivers/cpufreq/amd-pstate.c:363
Inline: True
```
**Symbols:**

```
ffffffff81da1a20-ffffffff81da1a87: pstate_update_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pstate_update_perf(struct amd_cpudata *cpudata, u32 min_perf, u32 des_perf, u32 max_perf, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81e597c0)
Location: drivers/cpufreq/amd-pstate.c:364
Inline: True
```
**Symbols:**

```
ffffffff81e597c0-ffffffff81e59827: pstate_update_perf (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
