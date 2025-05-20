# Function: <code>devfreq_get_freq_range</code>

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
void devfreq_get_freq_range(struct devfreq *devfreq, long unsigned int *min_freq, long unsigned int *max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81bd1e20)
Location: drivers/devfreq/devfreq.c:122
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:max_freq_show
  - drivers/devfreq/devfreq.c:min_freq_show
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_update_target
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81bd1e20-ffffffff81bd1f1b: devfreq_get_freq_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devfreq_get_freq_range(struct devfreq *devfreq, long unsigned int *min_freq, long unsigned int *max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d7da10)
Location: drivers/devfreq/devfreq.c:122
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:max_freq_show
  - drivers/devfreq/devfreq.c:min_freq_show
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_update_target
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81d7da10-ffffffff81d7db0b: devfreq_get_freq_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devfreq_get_freq_range(struct devfreq *devfreq, long unsigned int *min_freq, long unsigned int *max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81debd90)
Location: drivers/devfreq/devfreq.c:122
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:max_freq_show
  - drivers/devfreq/devfreq.c:min_freq_show
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_update_target
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81debd90-ffffffff81debe8b: devfreq_get_freq_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devfreq_get_freq_range(struct devfreq *devfreq, long unsigned int *min_freq, long unsigned int *max_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea2180)
Location: drivers/devfreq/devfreq.c:122
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:max_freq_show
  - drivers/devfreq/devfreq.c:min_freq_show
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_update_target
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81ea2180-ffffffff81ea227b: devfreq_get_freq_range (STB_GLOBAL)
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
