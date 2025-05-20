# Function: <code>get_target_freq_by_required_opp</code>

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
long unsigned int get_target_freq_by_required_opp(struct device *p_dev, struct opp_table *p_opp_table, struct opp_table *opp_table, long unsigned int *freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81bd6260)
Location: drivers/devfreq/governor_passive.c:50
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81bd6260-ffffffff81bd631e: get_target_freq_by_required_opp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int get_target_freq_by_required_opp(struct device *p_dev, struct opp_table *p_opp_table, struct opp_table *opp_table, long unsigned int *freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81d82970)
Location: drivers/devfreq/governor_passive.c:50
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81d82970-ffffffff81d82a2e: get_target_freq_by_required_opp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int get_target_freq_by_required_opp(struct device *p_dev, struct opp_table *p_opp_table, struct opp_table *opp_table, long unsigned int *freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81df0d50)
Location: drivers/devfreq/governor_passive.c:50
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81df0d50-ffffffff81df0e0e: get_target_freq_by_required_opp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int get_target_freq_by_required_opp(struct device *p_dev, struct opp_table *p_opp_table, struct opp_table *opp_table, long unsigned int *freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81ea7370)
Location: drivers/devfreq/governor_passive.c:50
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81ea7370-ffffffff81ea7430: get_target_freq_by_required_opp (STB_LOCAL)
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
