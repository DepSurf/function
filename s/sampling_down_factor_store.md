# Function: <code>sampling_down_factor_store</code>

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
ssize_t sampling_down_factor_store(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b93080)
Location: drivers/cpufreq/cpufreq_ondemand.c:240
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81b93e20)
Location: drivers/cpufreq/cpufreq_conservative.c:149
Inline: False
```
**Symbols:**

```
ffffffff81b93080-ffffffff81b9315d: sampling_down_factor_store (STB_LOCAL)
ffffffff81b93e20-ffffffff81b93ea8: sampling_down_factor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t sampling_down_factor_store(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d336b0)
Location: drivers/cpufreq/cpufreq_ondemand.c:240
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d34560)
Location: drivers/cpufreq/cpufreq_conservative.c:149
Inline: False
```
**Symbols:**

```
ffffffff81d336b0-ffffffff81d3378d: sampling_down_factor_store (STB_LOCAL)
ffffffff81d34560-ffffffff81d345e8: sampling_down_factor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t sampling_down_factor_store(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9ca40)
Location: drivers/cpufreq/cpufreq_ondemand.c:240
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d9d8d0)
Location: drivers/cpufreq/cpufreq_conservative.c:149
Inline: False
```
**Symbols:**

```
ffffffff81d9ca40-ffffffff81d9cb1d: sampling_down_factor_store (STB_LOCAL)
ffffffff81d9d8d0-ffffffff81d9d958: sampling_down_factor_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t sampling_down_factor_store(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e54700)
Location: drivers/cpufreq/cpufreq_ondemand.c:240
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81e555f0)
Location: drivers/cpufreq/cpufreq_conservative.c:149
Inline: False
```
**Symbols:**

```
ffffffff81e54700-ffffffff81e547dd: sampling_down_factor_store (STB_LOCAL)
ffffffff81e555f0-ffffffff81e55678: sampling_down_factor_store (STB_LOCAL)
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
