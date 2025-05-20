# Function: <code>kcpustat_cpu_fetch</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178a46)
Location: include/linux/kernel_stat.h:92
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
```
```
In fs/proc/stat.c (ffffffff813c548d)
Location: include/linux/kernel_stat.h:92
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81992544)
Location: include/linux/kernel_stat.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175696)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
```
```
In fs/proc/stat.c (ffffffff813d742f)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81995754)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81176144)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
```
```
In fs/proc/stat.c (ffffffff813de27a)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197a5c4)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119d709)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
```
```
In fs/proc/stat.c (ffffffff8142fa52)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff8143020e)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a235c0)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811cd962)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
```
```
In fs/proc/stat.c (ffffffff814a96dd)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff814a9eb6)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8c85c)
Location: include/linux/kernel_stat.h:91
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81211020)
Location: include/linux/kernel_stat.h:94
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
```
```
In fs/proc/stat.c (ffffffff8153f1cf)
Location: include/linux/kernel_stat.h:94
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff8153fa48)
Location: include/linux/kernel_stat.h:94
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c29c)
Location: include/linux/kernel_stat.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81226a18)
Location: include/linux/kernel_stat.h:106
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
```
```
In fs/proc/stat.c (ffffffff81577522)
Location: include/linux/kernel_stat.h:106
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
```
In fs/proc/uptime.c (ffffffff81577dc8)
Location: include/linux/kernel_stat.h:106
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9552c)
Location: include/linux/kernel_stat.h:106
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void kcpustat_cpu_fetch(struct kernel_cpustat *dst, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/cputime.c:1067
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff821b0b36-ffffffff821b0b4b: kcpustat_cpu_fetch.cold (STB_LOCAL)
ffffffff811752e0-ffffffff811755e3: kcpustat_cpu_fetch (STB_GLOBAL)
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
</ul>
