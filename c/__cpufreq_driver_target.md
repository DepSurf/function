# Function: <code>__cpufreq_driver_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816af390)
Location: drivers/cpufreq/cpufreq.c:1843
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_governor_userspace
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_governor_userspace
  - drivers/cpufreq/cpufreq_ondemand.c:dbs_freq_increase
  - drivers/cpufreq/cpufreq_ondemand.c:od_check_cpu
  - drivers/cpufreq/cpufreq_ondemand.c:od_check_cpu
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
  - drivers/cpufreq/cpufreq_conservative.c:cs_check_cpu
  - drivers/cpufreq/cpufreq_conservative.c:cs_check_cpu
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
```
**Symbols:**

```
ffffffff816af390-ffffffff816af700: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817116f0)
Location: drivers/cpufreq/cpufreq.c:1941
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff817116f0-ffffffff81711d3a: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81743ef0)
Location: drivers/cpufreq/cpufreq.c:1913
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff81743ef0-ffffffff817444a7: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81762460)
Location: drivers/cpufreq/cpufreq.c:1916
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff81762460-ffffffff817629bd: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d8450)
Location: drivers/cpufreq/cpufreq.c:1949
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff817d8450-ffffffff817d89bf: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1948
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff818231a8-ffffffff818231dd: __cpufreq_driver_target.cold.42 (STB_LOCAL)
ffffffff81821190-ffffffff81821742: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1949
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff8184f068-ffffffff8184f09d: __cpufreq_driver_target.cold.44 (STB_LOCAL)
ffffffff8184cf00-ffffffff8184d4b2: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2099
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff8189249e-ffffffff81892508: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff81890160-ffffffff818906ed: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2113
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff818c454c-ffffffff818c45b6: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff818c2360-ffffffff818c28ed: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81994d40)
Location: drivers/cpufreq/cpufreq.c:2150
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff81994d40-ffffffff81994e1e: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81997c20)
Location: drivers/cpufreq/cpufreq.c:2226
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff81997c20-ffffffff81997f6d: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197c8a0)
Location: drivers/cpufreq/cpufreq.c:2232
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff8197c8a0-ffffffff8197cbdf: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a25bd0)
Location: drivers/cpufreq/cpufreq.c:2238
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff81a25bd0-ffffffff81a25cb2: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2270
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_limits
  - kernel/sched/build_utility.c:sugov_limits
  - kernel/sched/build_utility.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff81ef822a-ffffffff81ef8243: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff81b8f3b0-ffffffff81b8f52b: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2267
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_limits
  - kernel/sched/build_utility.c:sugov_limits
  - kernel/sched/build_utility.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff820a8d70-ffffffff820a8d89: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff81d2f1d0-ffffffff81d2f345: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2274
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_limits
  - kernel/sched/build_utility.c:sugov_limits
  - kernel/sched/build_utility.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff82129f89-ffffffff82129fa2: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff81d98470-ffffffff81d985e5: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2315
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_limits
  - kernel/sched/build_utility.c:sugov_limits
  - kernel/sched/build_utility.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff8220bd63-ffffffff8220bd7c: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff81e500f0-ffffffff81e50265: __cpufreq_driver_target (STB_GLOBAL)
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
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1ed48)
Location: drivers/cpufreq/cpufreq.c:2113
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffff800010b1ed48-ffff800010b1f3b4: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf9328)
Location: drivers/cpufreq/cpufreq.c:2113
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
c0bf9328-c0bf9944: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c119e0)
Location: drivers/cpufreq/cpufreq.c:2113
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
c000000000c119e0-c000000000c12190: __cpufreq_driver_target (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2113
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff81868c6c-ffffffff81868cd6: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff81866a80-ffffffff8186700d: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2113
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff8183191c-ffffffff81831986: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff8182f730-ffffffff8182fcbd: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2113
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff818b99fc-ffffffff818b9a66: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff818b7810-ffffffff818b7d9d: __cpufreq_driver_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2113
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits
  - drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_set
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
**Symbols:**

```
ffffffff818d5c8f-ffffffff818d5cf9: __cpufreq_driver_target.cold (STB_LOCAL)
ffffffff818d2e10-ffffffff818d339d: __cpufreq_driver_target (STB_GLOBAL)
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
