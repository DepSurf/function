# Function: <code>store_sampling_down_factor</code>

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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b42a0)
Location: drivers/cpufreq/cpufreq_ondemand.c:339
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor_gov_pol
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor_gov_sys
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff816b4dd9)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor_gov_pol
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor_gov_sys
```
**Symbols:**

```
ffffffff816b42a0-ffffffff816b4363: store_sampling_down_factor.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715ad0)
Location: drivers/cpufreq/cpufreq_ondemand.c:240
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81716690)
Location: drivers/cpufreq/cpufreq_conservative.c:120
Inline: False
```
**Symbols:**

```
ffffffff81715ad0-ffffffff81715b99: store_sampling_down_factor (STB_LOCAL)
ffffffff81716690-ffffffff8171670a: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747830)
Location: drivers/cpufreq/cpufreq_ondemand.c:240
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81748430)
Location: drivers/cpufreq/cpufreq_conservative.c:148
Inline: False
```
**Symbols:**

```
ffffffff81747830-ffffffff817478f3: store_sampling_down_factor (STB_LOCAL)
ffffffff81748430-ffffffff817484aa: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765ea0)
Location: drivers/cpufreq/cpufreq_ondemand.c:241
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81766ae0)
Location: drivers/cpufreq/cpufreq_conservative.c:148
Inline: False
```
**Symbols:**

```
ffffffff81765ea0-ffffffff81765f62: store_sampling_down_factor (STB_LOCAL)
ffffffff81766ae0-ffffffff81766b59: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbe80)
Location: drivers/cpufreq/cpufreq_ondemand.c:241
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff817dca80)
Location: drivers/cpufreq/cpufreq_conservative.c:148
Inline: False
```
**Symbols:**

```
ffffffff817dbe80-ffffffff817dbf42: store_sampling_down_factor (STB_LOCAL)
ffffffff817dca80-ffffffff817dcaf9: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824b30)
Location: drivers/cpufreq/cpufreq_ondemand.c:241
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818256f0)
Location: drivers/cpufreq/cpufreq_conservative.c:148
Inline: False
```
**Symbols:**

```
ffffffff81824b30-ffffffff81824bf2: store_sampling_down_factor (STB_LOCAL)
ffffffff818256f0-ffffffff81825769: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850ac0)
Location: drivers/cpufreq/cpufreq_ondemand.c:241
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81851660)
Location: drivers/cpufreq/cpufreq_conservative.c:150
Inline: False
```
**Symbols:**

```
ffffffff81850ac0-ffffffff81850b82: store_sampling_down_factor (STB_LOCAL)
ffffffff81851660-ffffffff818516d9: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81894000)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81894b70)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff81894000-ffffffff818940c2: store_sampling_down_factor (STB_LOCAL)
ffffffff81894b70-ffffffff81894be7: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c6020)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818c6b90)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff818c6020-ffffffff818c60e2: store_sampling_down_factor (STB_LOCAL)
ffffffff818c6b90-ffffffff818c6c07: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff819980a0)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81998cc0)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff819980a0-ffffffff81998162: store_sampling_down_factor (STB_LOCAL)
ffffffff81998cc0-ffffffff81998d37: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b1c0)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff8199bda0)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff8199b1c0-ffffffff8199b282: store_sampling_down_factor (STB_LOCAL)
ffffffff8199bda0-ffffffff8199be17: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197fea0)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81980a60)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff8197fea0-ffffffff8197ff62: store_sampling_down_factor (STB_LOCAL)
ffffffff81980a60-ffffffff81980ad7: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a29040)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81a29c00)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff81a29040-ffffffff81a29102: store_sampling_down_factor (STB_LOCAL)
ffffffff81a29c00-ffffffff81a29c77: store_sampling_down_factor (STB_LOCAL)
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
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b24040)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffff800010b24de0)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffff800010b24040-ffff800010b24128: store_sampling_down_factor (STB_LOCAL)
ffff800010b24de0-ffff800010b24e78: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfe0e0)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (c0bfed60)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
c0bfe0e0-c0bfe1bc: store_sampling_down_factor (STB_LOCAL)
c0bfed60-c0bfedf4: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c18850)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (c000000000c199a0)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
c000000000c18850-c000000000c18970: store_sampling_down_factor (STB_LOCAL)
c000000000c199a0-c000000000c19a50: store_sampling_down_factor (STB_LOCAL)
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
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a740)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff8186b2b0)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff8186a740-ffffffff8186a802: store_sampling_down_factor (STB_LOCAL)
ffffffff8186b2b0-ffffffff8186b327: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818333f0)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81833f60)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff818333f0-ffffffff818334b2: store_sampling_down_factor (STB_LOCAL)
ffffffff81833f60-ffffffff81833fd7: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb4d0)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818bc040)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff818bb4d0-ffffffff818bb592: store_sampling_down_factor (STB_LOCAL)
ffffffff818bc040-ffffffff818bc0b7: store_sampling_down_factor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t store_sampling_down_factor(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d77c0)
Location: drivers/cpufreq/cpufreq_ondemand.c:238
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818d8330)
Location: drivers/cpufreq/cpufreq_conservative.c:147
Inline: False
```
**Symbols:**

```
ffffffff818d77c0-ffffffff818d7882: store_sampling_down_factor (STB_LOCAL)
ffffffff818d8330-ffffffff818d83a7: store_sampling_down_factor (STB_LOCAL)
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
