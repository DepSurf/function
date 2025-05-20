# Function: <code>cpus_read_trylock</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81097cd0)
Location: kernel/cpu.c:292
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff81097cd0-ffffffff81097d07: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bd70)
Location: kernel/cpu.c:293
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff8109bd70-ffffffff8109bda6: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a22f0)
Location: kernel/cpu.c:296
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff810a22f0-ffffffff810a2326: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a9390)
Location: kernel/cpu.c:297
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff810a9390-ffffffff810a93c9: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4de0)
Location: kernel/cpu.c:297
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff810a4de0-ffffffff810a4e19: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5ae0)
Location: kernel/cpu.c:302
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff810a5ae0-ffffffff810a5b19: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b7470)
Location: kernel/cpu.c:313
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff810b7470-ffffffff810b74a9: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cdc60)
Location: kernel/cpu.c:314
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff810cdc60-ffffffff810cdcc1: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ebdf0)
Location: kernel/cpu.c:314
Inline: False
```
**Symbols:**

```
ffffffff810ebdf0-ffffffff810ebe51: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f7ad0)
Location: kernel/cpu.c:493
Inline: False
```
**Symbols:**

```
ffffffff810f7ad0-ffffffff810f7b31: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81100ec0)
Location: kernel/cpu.c:493
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
```
**Symbols:**

```
ffffffff81100ec0-ffffffff81100f21: cpus_read_trylock (STB_GLOBAL)
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
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f7a90)
Location: kernel/cpu.c:296
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffff8000100f7a90-ffff8000100f7ae8: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0355c40)
Location: kernel/cpu.c:296
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
c0355c40-c0355c94: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013e180)
Location: kernel/cpu.c:296
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
c00000000013e180-c00000000013e1fc: cpus_read_trylock (STB_GLOBAL)
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
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bc10)
Location: kernel/cpu.c:296
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff8109bc10-ffffffff8109bc46: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108a640)
Location: kernel/cpu.c:296
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff8108a640-ffffffff8108a676: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bbc0)
Location: kernel/cpu.c:296
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff8109bbc0-ffffffff8109bbf6: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpus_read_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3c10)
Location: kernel/cpu.c:296
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:store
```
**Symbols:**

```
ffffffff810a3c10-ffffffff810a3c5e: cpus_read_trylock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
