# Function: <code>store_sampling_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3dc9)
Location: drivers/cpufreq/cpufreq_ondemand.c:286
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_rate_gov_sys
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_rate_gov_pol
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff816b4829)
Location: drivers/cpufreq/cpufreq_conservative.c:177
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_rate_gov_pol
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_rate_gov_sys
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817169b0)
Location: drivers/cpufreq/cpufreq_governor.c:46
Inline: False
```
**Symbols:**

```
ffffffff817169b0-ffffffff81716a74: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748750)
Location: drivers/cpufreq/cpufreq_governor.c:46
Inline: False
```
**Symbols:**

```
ffffffff81748750-ffffffff8174880e: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81766e00)
Location: drivers/cpufreq/cpufreq_governor.c:45
Inline: False
```
**Symbols:**

```
ffffffff81766e00-ffffffff81766ebd: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dcd50)
Location: drivers/cpufreq/cpufreq_governor.c:47
Inline: False
```
**Symbols:**

```
ffffffff817dcd50-ffffffff817dce0c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818259c0)
Location: drivers/cpufreq/cpufreq_governor.c:47
Inline: False
```
**Symbols:**

```
ffffffff818259c0-ffffffff81825a7c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818518a0)
Location: drivers/cpufreq/cpufreq_governor.c:47
Inline: False
```
**Symbols:**

```
ffffffff818518a0-ffffffff8185195c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81894db0)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff81894db0-ffffffff81894e6c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c6dd0)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff818c6dd0-ffffffff818c6e8c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81998fa0)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff81998fa0-ffffffff8199905c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c080)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff8199c080-ffffffff8199c13c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81980d40)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff81980d40-ffffffff81980dfc: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a29ee0)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff81a29ee0-ffffffff81a29f9c: store_sampling_rate (STB_GLOBAL)
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
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b250b8)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffff800010b250b8-ffff800010b25198: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (c0bfefb0)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
c0bfefb0-c0bff084: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (c000000000c19df0)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
c000000000c19df0-c000000000c19f00: store_sampling_rate (STB_GLOBAL)
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
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186b4f0)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff8186b4f0-ffffffff8186b5ac: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818341a0)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff818341a0-ffffffff8183425c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc280)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff818bc280-ffffffff818bc33c: store_sampling_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8570)
Location: drivers/cpufreq/cpufreq_governor.c:44
Inline: False
```
**Symbols:**

```
ffffffff818d8570-ffffffff818d862c: store_sampling_rate (STB_GLOBAL)
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
