# Function: <code>cpu_pm_notify</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cpu_pm_notify(enum cpu_pm_event event, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu_pm.c (ffff80001025b428)
Location: kernel/cpu_pm.c:18
Inline: False
Direct callers:
  - kernel/cpu_pm.c:cpu_pm_resume
  - kernel/cpu_pm.c:cpu_pm_resume
  - kernel/cpu_pm.c:cpu_cluster_pm_enter
  - kernel/cpu_pm.c:cpu_cluster_pm_enter
  - kernel/cpu_pm.c:cpu_pm_enter
  - kernel/cpu_pm.c:cpu_pm_enter
```
**Symbols:**

```
ffff80001025b428-ffff80001025b498: cpu_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_pm_notify(enum cpu_pm_event event, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu_pm.c (c048e588)
Location: kernel/cpu_pm.c:18
Inline: False
Direct callers:
  - kernel/cpu_pm.c:cpu_pm_resume
  - kernel/cpu_pm.c:cpu_pm_resume
  - kernel/cpu_pm.c:cpu_cluster_pm_enter
  - kernel/cpu_pm.c:cpu_cluster_pm_enter
  - kernel/cpu_pm.c:cpu_pm_enter
  - kernel/cpu_pm.c:cpu_pm_enter
```
**Symbols:**

```
c048e588-c048e5ec: cpu_pm_notify (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
