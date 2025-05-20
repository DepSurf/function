# Function: <code>static_key_slow_inc_cpuslocked</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c8770)
Location: kernel/jump_label.c:82
Inline: True
Direct callers:
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/jump_label.c:static_key_slow_inc
```
**Symbols:**

```
ffffffff811c8770-ffffffff811c8806: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8cd0)
Location: kernel/jump_label.c:83
Inline: True
Direct callers:
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/jump_label.c:static_key_slow_inc
```
**Symbols:**

```
ffffffff811e8cd0-ffffffff811e8d66: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f99d0)
Location: kernel/jump_label.c:101
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff811f99d0-ffffffff811f9a6b: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211900)
Location: kernel/jump_label.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81211900-ffffffff81211988: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121f100)
Location: kernel/jump_label.c:116
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8121f100-ffffffff8121f188: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124b3c0)
Location: kernel/jump_label.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8124b3c0-ffffffff8124b44b: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81255820)
Location: kernel/jump_label.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81255820-ffffffff812558ab: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259d00)
Location: kernel/jump_label.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81259d00-ffffffff81259d8b: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81cb9c17-ffffffff81cb9c2c: static_key_slow_inc_cpuslocked.cold (STB_LOCAL)
ffffffff81295a70-ffffffff81295b0b: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81e6b214-ffffffff81e6b229: static_key_slow_inc_cpuslocked.cold (STB_LOCAL)
ffffffff812eb760-ffffffff812eb809: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81355870)
Location: kernel/jump_label.c:148
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81355870-ffffffff813558fa: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81386ef0)
Location: kernel/jump_label.c:148
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81386ef0-ffffffff81386f7a: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813b0400)
Location: kernel/jump_label.c:148
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff813b0400-ffffffff813b048a: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab4e0)
Location: kernel/jump_label.c:116
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffff8000102ab4e0-ffff8000102ab5d8: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035f610)
Location: kernel/jump_label.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
c00000000035f610-c00000000035f750: static_key_slow_inc_cpuslocked (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81217750)
Location: kernel/jump_label.c:116
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81217750-ffffffff812177d8: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a4b0)
Location: kernel/jump_label.c:116
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8120a4b0-ffffffff8120a538: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812154f0)
Location: kernel/jump_label.c:116
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff812154f0-ffffffff81215578: static_key_slow_inc_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void static_key_slow_inc_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812244e0)
Location: kernel/jump_label.c:116
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/fair.c:cfs_bandwidth_usage_inc
  - kernel/sched/topology.c:build_sched_domains
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/jump_label.c:static_key_slow_inc
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff812244e0-ffffffff81224568: static_key_slow_inc_cpuslocked (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
