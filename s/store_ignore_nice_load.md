# Function: <code>store_ignore_nice_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b4140)
Location: drivers/cpufreq/cpufreq_ondemand.c:360
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load_gov_pol
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load_gov_sys
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff816b4e60)
Location: drivers/cpufreq/cpufreq_conservative.c:224
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load_gov_pol
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load_gov_sys
```
**Symbols:**

```
ffffffff816b4140-ffffffff816b4248: store_ignore_nice_load.isra.4 (STB_LOCAL)
ffffffff816b4e60-ffffffff816b4f67: store_ignore_nice_load.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817158e0)
Location: drivers/cpufreq/cpufreq_ondemand.c:268
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81716860)
Location: drivers/cpufreq/cpufreq_conservative.c:169
Inline: False
```
**Symbols:**

```
ffffffff817158e0-ffffffff81715971: store_ignore_nice_load (STB_LOCAL)
ffffffff81716860-ffffffff817168f1: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747640)
Location: drivers/cpufreq/cpufreq_ondemand.c:268
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81748600)
Location: drivers/cpufreq/cpufreq_conservative.c:197
Inline: False
```
**Symbols:**

```
ffffffff81747640-ffffffff817476d1: store_ignore_nice_load (STB_LOCAL)
ffffffff81748600-ffffffff81748691: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765cb0)
Location: drivers/cpufreq/cpufreq_ondemand.c:269
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81766cb0)
Location: drivers/cpufreq/cpufreq_conservative.c:197
Inline: False
```
**Symbols:**

```
ffffffff81765cb0-ffffffff81765d44: store_ignore_nice_load (STB_LOCAL)
ffffffff81766cb0-ffffffff81766d44: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbcc0)
Location: drivers/cpufreq/cpufreq_ondemand.c:269
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff817dcc20)
Location: drivers/cpufreq/cpufreq_conservative.c:197
Inline: False
```
**Symbols:**

```
ffffffff817dbcc0-ffffffff817dbd54: store_ignore_nice_load (STB_LOCAL)
ffffffff817dcc20-ffffffff817dccb4: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824970)
Location: drivers/cpufreq/cpufreq_ondemand.c:269
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81825890)
Location: drivers/cpufreq/cpufreq_conservative.c:197
Inline: False
```
**Symbols:**

```
ffffffff81824970-ffffffff81824a04: store_ignore_nice_load (STB_LOCAL)
ffffffff81825890-ffffffff81825924: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850900)
Location: drivers/cpufreq/cpufreq_ondemand.c:269
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81851800)
Location: drivers/cpufreq/cpufreq_conservative.c:199
Inline: False
```
**Symbols:**

```
ffffffff81850900-ffffffff81850994: store_ignore_nice_load (STB_LOCAL)
ffffffff81851800-ffffffff81851894: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81893e40)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81894d10)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff81893e40-ffffffff81893ed4: store_ignore_nice_load (STB_LOCAL)
ffffffff81894d10-ffffffff81894da4: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c5e60)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818c6d30)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff818c5e60-ffffffff818c5ef4: store_ignore_nice_load (STB_LOCAL)
ffffffff818c6d30-ffffffff818c6dc4: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81997ee0)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81998e60)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff81997ee0-ffffffff81997f74: store_ignore_nice_load (STB_LOCAL)
ffffffff81998e60-ffffffff81998ef4: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b000)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff8199bf40)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff8199b000-ffffffff8199b094: store_ignore_nice_load (STB_LOCAL)
ffffffff8199bf40-ffffffff8199bfd4: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197fce0)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81980c00)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff8197fce0-ffffffff8197fd76: store_ignore_nice_load (STB_LOCAL)
ffffffff81980c00-ffffffff81980c96: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a28e80)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81a29da0)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff81a28e80-ffffffff81a28f16: store_ignore_nice_load (STB_LOCAL)
ffffffff81a29da0-ffffffff81a29e36: store_ignore_nice_load (STB_LOCAL)
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
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b23e08)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffff800010b25008)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffff800010b23e08-ffff800010b23eb8: store_ignore_nice_load (STB_LOCAL)
ffff800010b25008-ffff800010b250b8: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfdf2c)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (c0bfef04)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
c0bfdf2c-c0bfdfd4: store_ignore_nice_load (STB_LOCAL)
c0bfef04-c0bfefac: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c185a0)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (c000000000c19c30)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
c000000000c185a0-c000000000c18670: store_ignore_nice_load (STB_LOCAL)
c000000000c19c30-c000000000c19d00: store_ignore_nice_load (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a580)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff8186b450)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff8186a580-ffffffff8186a614: store_ignore_nice_load (STB_LOCAL)
ffffffff8186b450-ffffffff8186b4e4: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81833230)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81834100)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff81833230-ffffffff818332c4: store_ignore_nice_load (STB_LOCAL)
ffffffff81834100-ffffffff81834194: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb310)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818bc1e0)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff818bb310-ffffffff818bb3a4: store_ignore_nice_load (STB_LOCAL)
ffffffff818bc1e0-ffffffff818bc274: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t store_ignore_nice_load(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7600)
Location: drivers/cpufreq/cpufreq_ondemand.c:266
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818d84d0)
Location: drivers/cpufreq/cpufreq_conservative.c:196
Inline: False
```
**Symbols:**

```
ffffffff818d7600-ffffffff818d7694: store_ignore_nice_load (STB_LOCAL)
ffffffff818d84d0-ffffffff818d8564: store_ignore_nice_load (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
