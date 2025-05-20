# Function: <code>get_cpu_idle_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816ae8e0)
Location: drivers/cpufreq/cpufreq.c:197
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_check_cpu
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
```
**Symbols:**

```
ffffffff816ae8e0-ffffffff816ae98d: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710190)
Location: drivers/cpufreq/cpufreq.c:151
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff81710190-ffffffff8171023d: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81742170)
Location: drivers/cpufreq/cpufreq.c:151
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff81742170-ffffffff8174221d: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817607e0)
Location: drivers/cpufreq/cpufreq.c:151
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff817607e0-ffffffff817608b5: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d67b0)
Location: drivers/cpufreq/cpufreq.c:151
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff817d67b0-ffffffff817d6885: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8181f4a0)
Location: drivers/cpufreq/cpufreq.c:142
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff8181f4a0-ffffffff8181f584: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184b340)
Location: drivers/cpufreq/cpufreq.c:142
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff8184b340-ffffffff8184b424: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188e3c0)
Location: drivers/cpufreq/cpufreq.c:136
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff8188e3c0-ffffffff8188e4a8: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0550)
Location: drivers/cpufreq/cpufreq.c:139
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff818c0550-ffffffff818c0638: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819924e0)
Location: drivers/cpufreq/cpufreq.c:144
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff819924e0-ffffffff819925c2: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819956f0)
Location: drivers/cpufreq/cpufreq.c:150
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff819956f0-ffffffff819957d2: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197a560)
Location: drivers/cpufreq/cpufreq.c:147
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff8197a560-ffffffff8197a642: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a23550)
Location: drivers/cpufreq/cpufreq.c:147
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff81a23550-ffffffff81a23667: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8c7d0)
Location: drivers/cpufreq/cpufreq.c:148
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff81b8c7d0-ffffffff81b8c8f2: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c210)
Location: drivers/cpufreq/cpufreq.c:148
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff81d2c210-ffffffff81d2c332: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d954a0)
Location: drivers/cpufreq/cpufreq.c:153
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff81d954a0-ffffffff81d955c2: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4cfb0)
Location: drivers/cpufreq/cpufreq.c:154
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff81e4cfb0-ffffffff81e4d0ba: get_cpu_idle_time (STB_GLOBAL)
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
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1cf80)
Location: drivers/cpufreq/cpufreq.c:139
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffff800010b1cf80-ffff800010b1d0a4: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfab68)
Location: drivers/cpufreq/cpufreq.c:139
Inline: True
Direct callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
c0bfab68-c0bface0: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c0fa00)
Location: drivers/cpufreq/cpufreq.c:139
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
c000000000c0fa00-c000000000c0fb9c: get_cpu_idle_time (STB_GLOBAL)
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
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81864c70)
Location: drivers/cpufreq/cpufreq.c:139
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff81864c70-ffffffff81864d58: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182d920)
Location: drivers/cpufreq/cpufreq.c:139
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff8182d920-ffffffff8182da08: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b5a00)
Location: drivers/cpufreq/cpufreq.c:139
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff818b5a00-ffffffff818b5ae8: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 get_cpu_idle_time(unsigned int cpu, u64 *wall, int io_busy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d1cb0)
Location: drivers/cpufreq/cpufreq.c:139
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff818d1cb0-ffffffff818d1d98: get_cpu_idle_time (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
