# Function: <code>ignore_nice_load_show</code>

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
ssize_t ignore_nice_load_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b92fc0)
Location: drivers/cpufreq/cpufreq_ondemand.c:320
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81b93ef0)
Location: drivers/cpufreq/cpufreq_conservative.c:249
Inline: False
```
**Symbols:**

```
ffffffff81b92fc0-ffffffff81b92fef: ignore_nice_load_show (STB_LOCAL)
ffffffff81b93ef0-ffffffff81b93f1f: ignore_nice_load_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t ignore_nice_load_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d335b0)
Location: drivers/cpufreq/cpufreq_ondemand.c:320
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d34650)
Location: drivers/cpufreq/cpufreq_conservative.c:249
Inline: False
```
**Symbols:**

```
ffffffff81d335b0-ffffffff81d335df: ignore_nice_load_show (STB_LOCAL)
ffffffff81d34650-ffffffff81d3467f: ignore_nice_load_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t ignore_nice_load_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9c940)
Location: drivers/cpufreq/cpufreq_ondemand.c:320
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d9d9c0)
Location: drivers/cpufreq/cpufreq_conservative.c:249
Inline: False
```
**Symbols:**

```
ffffffff81d9c940-ffffffff81d9c96f: ignore_nice_load_show (STB_LOCAL)
ffffffff81d9d9c0-ffffffff81d9d9ef: ignore_nice_load_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t ignore_nice_load_show(struct gov_attr_set *attr_set, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e54600)
Location: drivers/cpufreq/cpufreq_ondemand.c:320
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81e556e0)
Location: drivers/cpufreq/cpufreq_conservative.c:248
Inline: False
```
**Symbols:**

```
ffffffff81e54600-ffffffff81e5462f: ignore_nice_load_show (STB_LOCAL)
ffffffff81e556e0-ffffffff81e5570f: ignore_nice_load_show (STB_LOCAL)
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
