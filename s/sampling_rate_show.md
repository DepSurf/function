# Function: <code>sampling_rate_show</code>

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
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t sampling_rate_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b93050)
Location: drivers/cpufreq/cpufreq_ondemand.c:317
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81b93fc0)
Location: drivers/cpufreq/cpufreq_conservative.c:246
Inline: False
```
**Symbols:**

```
ffffffff81b93050-ffffffff81b9307f: sampling_rate_show (STB_LOCAL)
ffffffff81b93fc0-ffffffff81b93fef: sampling_rate_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t sampling_rate_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d33670)
Location: drivers/cpufreq/cpufreq_ondemand.c:317
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d34760)
Location: drivers/cpufreq/cpufreq_conservative.c:246
Inline: False
```
**Symbols:**

```
ffffffff81d33670-ffffffff81d3369f: sampling_rate_show (STB_LOCAL)
ffffffff81d34760-ffffffff81d3478f: sampling_rate_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t sampling_rate_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9ca00)
Location: drivers/cpufreq/cpufreq_ondemand.c:317
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d9dad0)
Location: drivers/cpufreq/cpufreq_conservative.c:246
Inline: False
```
**Symbols:**

```
ffffffff81d9ca00-ffffffff81d9ca2f: sampling_rate_show (STB_LOCAL)
ffffffff81d9dad0-ffffffff81d9daff: sampling_rate_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t sampling_rate_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e546c0)
Location: drivers/cpufreq/cpufreq_ondemand.c:317
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81e557f0)
Location: drivers/cpufreq/cpufreq_conservative.c:245
Inline: False
```
**Symbols:**

```
ffffffff81e546c0-ffffffff81e546ef: sampling_rate_show (STB_LOCAL)
ffffffff81e557f0-ffffffff81e5581f: sampling_rate_show (STB_LOCAL)
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
