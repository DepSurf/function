# Function: <code>cpufreq_register_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816af7b0)
Location: drivers/cpufreq/cpufreq.c:2004
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff816af7b0-ffffffff816af83b: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710dc0)
Location: drivers/cpufreq/cpufreq.c:2108
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff81710dc0-ffffffff81710e47: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81742ce0)
Location: drivers/cpufreq/cpufreq.c:2080
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff81742ce0-ffffffff81742d67: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81761350)
Location: drivers/cpufreq/cpufreq.c:2083
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff81761350-ffffffff817613d7: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d72f0)
Location: drivers/cpufreq/cpufreq.c:2116
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff817d72f0-ffffffff817d7377: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8181feb0)
Location: drivers/cpufreq/cpufreq.c:2115
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff8181feb0-ffffffff8181ff37: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184bd50)
Location: drivers/cpufreq/cpufreq.c:2116
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff8184bd50-ffffffff8184bdd7: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188ed80)
Location: drivers/cpufreq/cpufreq.c:2266
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff8188ed80-ffffffff8188ee07: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0d70)
Location: drivers/cpufreq/cpufreq.c:2280
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff818c0d70-ffffffff818c0df7: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81992a10)
Location: drivers/cpufreq/cpufreq.c:2317
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff81992a10-ffffffff81992ad5: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995c20)
Location: drivers/cpufreq/cpufreq.c:2393
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_gov_init
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:CPU_FREQ_GOV_ONDEMAND_init
  - drivers/cpufreq/cpufreq_conservative.c:CPU_FREQ_GOV_CONSERVATIVE_init
```
**Symbols:**

```
ffffffff81995c20-ffffffff81995ce5: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197aa90)
Location: drivers/cpufreq/cpufreq.c:2399
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_gov_init
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:CPU_FREQ_GOV_ONDEMAND_init
  - drivers/cpufreq/cpufreq_conservative.c:CPU_FREQ_GOV_CONSERVATIVE_init
```
**Symbols:**

```
ffffffff8197aa90-ffffffff8197ab55: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a23a20)
Location: drivers/cpufreq/cpufreq.c:2401
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_gov_init
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:CPU_FREQ_GOV_ONDEMAND_init
  - drivers/cpufreq/cpufreq_conservative.c:CPU_FREQ_GOV_CONSERVATIVE_init
```
**Symbols:**

```
ffffffff81a23a20-ffffffff81a23ae5: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8cf90)
Location: drivers/cpufreq/cpufreq.c:2441
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:schedutil_gov_init
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:CPU_FREQ_GOV_ONDEMAND_init
  - drivers/cpufreq/cpufreq_conservative.c:CPU_FREQ_GOV_CONSERVATIVE_init
```
**Symbols:**

```
ffffffff81b8cf90-ffffffff81b8d05f: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c980)
Location: drivers/cpufreq/cpufreq.c:2438
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:schedutil_gov_init
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:CPU_FREQ_GOV_ONDEMAND_init
  - drivers/cpufreq/cpufreq_conservative.c:CPU_FREQ_GOV_CONSERVATIVE_init
```
**Symbols:**

```
ffffffff81d2c980-ffffffff81d2ca4f: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d95c10)
Location: drivers/cpufreq/cpufreq.c:2445
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:schedutil_gov_init
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:CPU_FREQ_GOV_ONDEMAND_init
  - drivers/cpufreq/cpufreq_conservative.c:CPU_FREQ_GOV_CONSERVATIVE_init
```
**Symbols:**

```
ffffffff81d95c10-ffffffff81d95cdf: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4d700)
Location: drivers/cpufreq/cpufreq.c:2486
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:schedutil_gov_init
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:CPU_FREQ_GOV_ONDEMAND_init
  - drivers/cpufreq/cpufreq_conservative.c:CPU_FREQ_GOV_CONSERVATIVE_init
```
**Symbols:**

```
ffffffff81e4d700-ffffffff81e4d7cf: cpufreq_register_governor (STB_GLOBAL)
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
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1d7b0)
Location: drivers/cpufreq/cpufreq.c:2280
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffff800010b1d7b0-ffff800010b1d844: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf8630)
Location: drivers/cpufreq/cpufreq.c:2280
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
c0bf8630-c0bf86bc: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c10790)
Location: drivers/cpufreq/cpufreq.c:2280
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
c000000000c10790-c000000000c10880: cpufreq_register_governor (STB_GLOBAL)
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
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81865490)
Location: drivers/cpufreq/cpufreq.c:2280
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff81865490-ffffffff81865517: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182e140)
Location: drivers/cpufreq/cpufreq.c:2280
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff8182e140-ffffffff8182e1c7: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b6220)
Location: drivers/cpufreq/cpufreq.c:2280
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff818b6220-ffffffff818b62a7: cpufreq_register_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpufreq_register_governor(struct cpufreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d24d0)
Location: drivers/cpufreq/cpufreq.c:2280
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_register
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_init
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_init
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_gov_userspace_init
  - drivers/cpufreq/cpufreq_ondemand.c:cpufreq_gov_dbs_init
  - drivers/cpufreq/cpufreq_conservative.c:cpufreq_gov_dbs_init
```
**Symbols:**

```
ffffffff818d24d0-ffffffff818d2557: cpufreq_register_governor (STB_GLOBAL)
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
