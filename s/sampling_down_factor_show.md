# Function: <code>sampling_down_factor_show</code>

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
ssize_t sampling_down_factor_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b92ff0)
Location: drivers/cpufreq/cpufreq_ondemand.c:319
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81b93f90)
Location: drivers/cpufreq/cpufreq_conservative.c:247
Inline: False
```
**Symbols:**

```
ffffffff81b92ff0-ffffffff81b9301f: sampling_down_factor_show (STB_LOCAL)
ffffffff81b93f90-ffffffff81b93fbf: sampling_down_factor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t sampling_down_factor_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d335f0)
Location: drivers/cpufreq/cpufreq_ondemand.c:319
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d34720)
Location: drivers/cpufreq/cpufreq_conservative.c:247
Inline: False
```
**Symbols:**

```
ffffffff81d335f0-ffffffff81d3361f: sampling_down_factor_show (STB_LOCAL)
ffffffff81d34720-ffffffff81d3474f: sampling_down_factor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t sampling_down_factor_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9c980)
Location: drivers/cpufreq/cpufreq_ondemand.c:319
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d9da90)
Location: drivers/cpufreq/cpufreq_conservative.c:247
Inline: False
```
**Symbols:**

```
ffffffff81d9c980-ffffffff81d9c9af: sampling_down_factor_show (STB_LOCAL)
ffffffff81d9da90-ffffffff81d9dabf: sampling_down_factor_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t sampling_down_factor_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e54640)
Location: drivers/cpufreq/cpufreq_ondemand.c:319
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81e557b0)
Location: drivers/cpufreq/cpufreq_conservative.c:246
Inline: False
```
**Symbols:**

```
ffffffff81e54640-ffffffff81e5466f: sampling_down_factor_show (STB_LOCAL)
ffffffff81e557b0-ffffffff81e557df: sampling_down_factor_show (STB_LOCAL)
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
