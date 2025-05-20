# Function: <code>ignore_nice_load_store</code>

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
ssize_t ignore_nice_load_store(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b92ea0)
Location: drivers/cpufreq/cpufreq_ondemand.c:268
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81b93ff0)
Location: drivers/cpufreq/cpufreq_conservative.c:198
Inline: False
```
**Symbols:**

```
ffffffff81b92ea0-ffffffff81b92f41: ignore_nice_load_store (STB_LOCAL)
ffffffff81b93ff0-ffffffff81b94091: ignore_nice_load_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t ignore_nice_load_store(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d33460)
Location: drivers/cpufreq/cpufreq_ondemand.c:268
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d347a0)
Location: drivers/cpufreq/cpufreq_conservative.c:198
Inline: False
```
**Symbols:**

```
ffffffff81d33460-ffffffff81d33501: ignore_nice_load_store (STB_LOCAL)
ffffffff81d347a0-ffffffff81d34841: ignore_nice_load_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t ignore_nice_load_store(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9c7f0)
Location: drivers/cpufreq/cpufreq_ondemand.c:268
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81d9db10)
Location: drivers/cpufreq/cpufreq_conservative.c:198
Inline: False
```
**Symbols:**

```
ffffffff81d9c7f0-ffffffff81d9c891: ignore_nice_load_store (STB_LOCAL)
ffffffff81d9db10-ffffffff81d9dbb1: ignore_nice_load_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t ignore_nice_load_store(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e544b0)
Location: drivers/cpufreq/cpufreq_ondemand.c:268
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81e55830)
Location: drivers/cpufreq/cpufreq_conservative.c:197
Inline: False
```
**Symbols:**

```
ffffffff81e544b0-ffffffff81e54551: ignore_nice_load_store (STB_LOCAL)
ffffffff81e55830-ffffffff81e558d1: ignore_nice_load_store (STB_LOCAL)
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
