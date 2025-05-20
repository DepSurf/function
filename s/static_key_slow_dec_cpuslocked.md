# Function: <code>static_key_slow_dec_cpuslocked</code>

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
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c8840)
Location: kernel/jump_label.c:232
Inline: False
Direct callers:
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
```
**Symbols:**

```
ffffffff811c8840-ffffffff811c888c: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8da0)
Location: kernel/jump_label.c:233
Inline: False
Direct callers:
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
```
**Symbols:**

```
ffffffff811e8da0-ffffffff811e8ddf: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9aa0)
Location: kernel/jump_label.c:256
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff811f9aa0-ffffffff811f9adf: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812119c0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff812119c0-ffffffff81211a07: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121f1c0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8121f1c0-ffffffff8121f207: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124b480)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffff8124b480-ffffffff8124b4d0: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812558e0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffff812558e0-ffffffff81255930: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259dc0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffff81259dc0-ffffffff81259e10: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffff81cb9c2c-ffffffff81cb9c40: static_key_slow_dec_cpuslocked.cold (STB_LOCAL)
ffffffff81295b40-ffffffff81295b9c: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffff81e6b229-ffffffff81e6b23e: static_key_slow_dec_cpuslocked.cold (STB_LOCAL)
ffffffff812eb840-ffffffff812eb8ab: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:302
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffff82061f92-ffffffff82061fa7: static_key_slow_dec_cpuslocked.cold (STB_LOCAL)
ffffffff81355950-ffffffff813559bb: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:302
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffff820e17c0-ffffffff820e17d5: static_key_slow_dec_cpuslocked.cold (STB_LOCAL)
ffffffff81386fd0-ffffffff8138703b: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:302
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffff821be223-ffffffff821be238: static_key_slow_dec_cpuslocked.cold (STB_LOCAL)
ffffffff813b04e0-ffffffff813b054b: static_key_slow_dec_cpuslocked (STB_GLOBAL)
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
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab610)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffff8000102ab610-ffff8000102ab67c: static_key_slow_dec_cpuslocked (STB_GLOBAL)
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
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035f7a0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
c00000000035f7a0-c00000000035f820: static_key_slow_dec_cpuslocked (STB_GLOBAL)
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
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81217810)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81217810-ffffffff81217857: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a570)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8120a570-ffffffff8120a5b7: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812155b0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff812155b0-ffffffff812155f7: static_key_slow_dec_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812245a0)
Location: kernel/jump_label.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:cfs_bandwidth_usage_dec
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff812245a0-ffffffff812245e7: static_key_slow_dec_cpuslocked (STB_GLOBAL)
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
