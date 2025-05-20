# Function: <code>cpufreq_remove_update_util_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810ce310)
Location: kernel/sched/cpufreq.c:59
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810ce310-ffffffff810ce334: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810d4330)
Location: kernel/sched/cpufreq.c:59
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810d4330-ffffffff810d4354: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810d34c0)
Location: kernel/sched/cpufreq.c:59
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810d34c0-ffffffff810d34e4: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810db090)
Location: kernel/sched/cpufreq.c:59
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810db090-ffffffff810db0b4: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810e3250)
Location: kernel/sched/cpufreq.c:58
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810e3250-ffffffff810e3274: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810ed980)
Location: kernel/sched/cpufreq.c:55
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810ed980-ffffffff810ed9a4: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810f46b0)
Location: kernel/sched/cpufreq.c:55
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810f46b0-ffffffff810f46d4: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81100340)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff81100340-ffffffff81100364: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff8110a9e0)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8110a9e0-ffffffff8110aa04: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff811078f0)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff811078f0-ffffffff81107914: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff811099c0)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff811099c0-ffffffff811099e4: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81127e60)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81127e60-ffffffff81127ea4: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113e072)
Location: kernel/sched/cpufreq.c:54
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_stop
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8113b6a0-ffffffff8113b6ec: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116cd2f)
Location: kernel/sched/cpufreq.c:54
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_stop
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81166070-ffffffff811660bc: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117d18f)
Location: kernel/sched/cpufreq.c:54
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_stop
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff811764e0-ffffffff8117652c: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118af8f)
Location: kernel/sched/cpufreq.c:54
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_stop
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81184760-ffffffff811847ac: cpufreq_remove_update_util_hook (STB_GLOBAL)
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
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffff8000101649d0)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
```
**Symbols:**

```
ffff8000101649d0-ffff800010164a0c: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (c03b1010)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
```
**Symbols:**

```
c03b1010-c03b1044: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (c0000000001bb910)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
```
**Symbols:**

```
c0000000001bb910-c0000000001bb944: cpufreq_remove_update_util_hook (STB_GLOBAL)
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
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810f9650)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810f9650-ffffffff810f9674: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810e9830)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810e9830-ffffffff810e9854: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810f6870)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff810f6870-ffffffff810f6894: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpufreq_remove_update_util_hook(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff811018d0)
Location: kernel/sched/cpufreq.c:57
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
```
**Symbols:**

```
ffffffff811018d0-ffffffff811018f4: cpufreq_remove_update_util_hook (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
