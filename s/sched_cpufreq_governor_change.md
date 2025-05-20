# Function: <code>sched_cpufreq_governor_change</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:949
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:978
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_cpufreq_governor_change(struct cpufreq_policy *policy, struct cpufreq_governor *old_gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110bab0)
Location: kernel/sched/cpufreq_schedutil.c:936
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8110bab0-ffffffff8110bae7: sched_cpufreq_governor_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_cpufreq_governor_change(struct cpufreq_policy *policy, struct cpufreq_governor *old_gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81108a60)
Location: kernel/sched/cpufreq_schedutil.c:956
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81108a60-ffffffff81108a97: sched_cpufreq_governor_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_cpufreq_governor_change(struct cpufreq_policy *policy, struct cpufreq_governor *old_gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a940)
Location: kernel/sched/cpufreq_schedutil.c:843
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8110a940-ffffffff8110a977: sched_cpufreq_governor_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_cpufreq_governor_change(struct cpufreq_policy *policy, struct cpufreq_governor *old_gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811290d0)
Location: kernel/sched/cpufreq_schedutil.c:850
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff811290d0-ffffffff81129107: sched_cpufreq_governor_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_cpufreq_governor_change(struct cpufreq_policy *policy, struct cpufreq_governor *old_gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81145f20)
Location: kernel/sched/cpufreq_schedutil.c:850
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81145f20-ffffffff81145f6f: sched_cpufreq_governor_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_cpufreq_governor_change(struct cpufreq_policy *policy, struct cpufreq_governor *old_gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811730f0)
Location: kernel/sched/cpufreq_schedutil.c:849
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff811730f0-ffffffff8117313f: sched_cpufreq_governor_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_cpufreq_governor_change(struct cpufreq_policy *policy, struct cpufreq_governor *old_gov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81183fe0)
Location: kernel/sched/cpufreq_schedutil.c:853
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81183fe0-ffffffff8118402f: sched_cpufreq_governor_change (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:984
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/cpufreq.h:984
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
