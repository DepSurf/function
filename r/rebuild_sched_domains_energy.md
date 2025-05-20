# Function: <code>rebuild_sched_domains_energy</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_energy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8110054c)
Location: kernel/sched/topology.c:214
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_energy_aware_handler
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:rebuild_sd_workfn
```
**Symbols:**

```
ffffffff811004a0-ffffffff811004d6: rebuild_sched_domains_energy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_energy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811026ec)
Location: kernel/sched/topology.c:214
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_energy_aware_handler
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:rebuild_sd_workfn
```
**Symbols:**

```
ffffffff81102640-ffffffff81102676: rebuild_sched_domains_energy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_energy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111f249)
Location: kernel/sched/topology.c:214
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_energy_aware_handler
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:rebuild_sd_workfn
```
**Symbols:**

```
ffffffff8111f1a0-ffffffff8111f1d6: rebuild_sched_domains_energy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_energy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114222b)
Location: kernel/sched/topology.c:213
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/sched/build_utility.c:rebuild_sd_workfn
```
**Symbols:**

```
ffffffff81149280-ffffffff811492bc: rebuild_sched_domains_energy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_energy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116d65b)
Location: kernel/sched/topology.c:213
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/sched/build_utility.c:rebuild_sd_workfn
```
**Symbols:**

```
ffffffff81177b80-ffffffff81177bbc: rebuild_sched_domains_energy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_energy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117e4fb)
Location: kernel/sched/topology.c:215
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/sched/build_utility.c:rebuild_sd_workfn
```
**Symbols:**

```
ffffffff811887c0-ffffffff811887fc: rebuild_sched_domains_energy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rebuild_sched_domains_energy();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a4e5)
Location: kernel/sched/topology.c:278
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:rebuild_sd_workfn
```
**Symbols:**

```
ffffffff811970a0-ffffffff811970dc: rebuild_sched_domains_energy (STB_GLOBAL)
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
