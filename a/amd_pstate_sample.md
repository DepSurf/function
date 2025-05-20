# Function: <code>amd_pstate_sample</code>

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
bool amd_pstate_sample(struct amd_cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81b97320)
Location: drivers/cpufreq/amd-pstate.c:233
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
**Symbols:**

```
ffffffff81b97320-ffffffff81b97457: amd_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool amd_pstate_sample(struct amd_cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81d38190)
Location: drivers/cpufreq/amd-pstate.c:181
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
**Symbols:**

```
ffffffff81d38190-ffffffff81d382ca: amd_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool amd_pstate_sample(struct amd_cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81da2590)
Location: drivers/cpufreq/amd-pstate.c:396
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
**Symbols:**

```
ffffffff81da2590-ffffffff81da26ca: amd_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool amd_pstate_sample(struct amd_cpudata *cpudata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a660)
Location: drivers/cpufreq/amd-pstate.c:397
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
**Symbols:**

```
ffffffff81e5a660-ffffffff81e5a79a: amd_pstate_sample (STB_LOCAL)
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
