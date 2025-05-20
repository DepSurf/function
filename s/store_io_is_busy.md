# Function: <code>store_io_is_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3ed0)
Location: drivers/cpufreq/cpufreq_ondemand.c:299
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy_gov_pol
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy_gov_sys
```
**Symbols:**

```
ffffffff816b3ed0-ffffffff816b3fa4: store_io_is_busy.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715860)
Location: drivers/cpufreq/cpufreq_ondemand.c:205
Inline: False
```
**Symbols:**

```
ffffffff81715860-ffffffff817158df: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817475c0)
Location: drivers/cpufreq/cpufreq_ondemand.c:205
Inline: False
```
**Symbols:**

```
ffffffff817475c0-ffffffff8174763f: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765c30)
Location: drivers/cpufreq/cpufreq_ondemand.c:206
Inline: False
```
**Symbols:**

```
ffffffff81765c30-ffffffff81765caf: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbc40)
Location: drivers/cpufreq/cpufreq_ondemand.c:206
Inline: False
```
**Symbols:**

```
ffffffff817dbc40-ffffffff817dbcbf: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818248f0)
Location: drivers/cpufreq/cpufreq_ondemand.c:206
Inline: False
```
**Symbols:**

```
ffffffff818248f0-ffffffff81824970: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850880)
Location: drivers/cpufreq/cpufreq_ondemand.c:206
Inline: False
```
**Symbols:**

```
ffffffff81850880-ffffffff81850900: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81893dc0)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff81893dc0-ffffffff81893e40: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c5de0)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff818c5de0-ffffffff818c5e60: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81997e60)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff81997e60-ffffffff81997ee0: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199af80)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff8199af80-ffffffff8199b000: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197fc60)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff8197fc60-ffffffff8197fce0: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a28e00)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff81a28e00-ffffffff81a28e80: store_io_is_busy (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b23d68)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffff800010b23d68-ffff800010b23e04: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfde94)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
c0bfde94-c0bfdf2c: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c184e0)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
c000000000c184e0-c000000000c185a0: store_io_is_busy (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a500)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff8186a500-ffffffff8186a580: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818331b0)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff818331b0-ffffffff81833230: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb290)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff818bb290-ffffffff818bb310: store_io_is_busy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t store_io_is_busy(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7580)
Location: drivers/cpufreq/cpufreq_ondemand.c:203
Inline: False
```
**Symbols:**

```
ffffffff818d7580-ffffffff818d7600: store_io_is_busy (STB_LOCAL)
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
