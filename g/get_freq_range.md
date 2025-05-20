# Function: <code>get_freq_range</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_freq_range(struct devfreq *devfreq, long unsigned int *min_freq, long unsigned int *max_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cde80)
Location: drivers/devfreq/devfreq.c:114
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:max_freq_show
  - drivers/devfreq/devfreq.c:min_freq_show
  - drivers/devfreq/devfreq.c:update_devfreq
```
**Symbols:**

```
ffffffff819cde80-ffffffff819cdf6e: get_freq_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_freq_range(struct devfreq *devfreq, long unsigned int *min_freq, long unsigned int *max_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cd850)
Location: drivers/devfreq/devfreq.c:121
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:max_freq_show
  - drivers/devfreq/devfreq.c:min_freq_show
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff819cd850-ffffffff819cd93e: get_freq_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_freq_range(struct devfreq *devfreq, long unsigned int *min_freq, long unsigned int *max_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819b2ab0)
Location: drivers/devfreq/devfreq.c:122
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:max_freq_show
  - drivers/devfreq/devfreq.c:min_freq_show
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff819b2ab0-ffffffff819b2ba2: get_freq_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_freq_range(struct devfreq *devfreq, long unsigned int *min_freq, long unsigned int *max_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81a61560)
Location: drivers/devfreq/devfreq.c:122
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_summary_show
  - drivers/devfreq/devfreq.c:max_freq_show
  - drivers/devfreq/devfreq.c:min_freq_show
  - drivers/devfreq/devfreq.c:devfreq_update_target
```
**Symbols:**

```
ffffffff81a61560-ffffffff81a61652: get_freq_range (STB_LOCAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
