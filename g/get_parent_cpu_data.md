# Function: <code>get_parent_cpu_data</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devfreq_cpu_data *get_parent_cpu_data(struct devfreq_passive_data *p_data, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81bd6320)
Location: drivers/devfreq/governor_passive.c:21
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81bd6320-ffffffff81bd6396: get_parent_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devfreq_cpu_data *get_parent_cpu_data(struct devfreq_passive_data *p_data, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81d82a40)
Location: drivers/devfreq/governor_passive.c:21
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81d82a40-ffffffff81d82ab6: get_parent_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devfreq_cpu_data *get_parent_cpu_data(struct devfreq_passive_data *p_data, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81df0e20)
Location: drivers/devfreq/governor_passive.c:21
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81df0e20-ffffffff81df0e96: get_parent_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devfreq_cpu_data *get_parent_cpu_data(struct devfreq_passive_data *p_data, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81ea7440)
Location: drivers/devfreq/governor_passive.c:21
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81ea7440-ffffffff81ea74b6: get_parent_cpu_data (STB_LOCAL)
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
