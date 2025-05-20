# Function: <code>store_up_threshold</code>

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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3e49)
Location: drivers/cpufreq/cpufreq_ondemand.c:322
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold_gov_pol
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold_gov_sys
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff816b4d5d)
Location: drivers/cpufreq/cpufreq_conservative.c:192
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold_gov_pol
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold_gov_sys
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817157e0)
Location: drivers/cpufreq/cpufreq_ondemand.c:223
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81716600)
Location: drivers/cpufreq/cpufreq_conservative.c:135
Inline: False
```
**Symbols:**

```
ffffffff817157e0-ffffffff8171585a: store_up_threshold (STB_LOCAL)
ffffffff81716600-ffffffff81716686: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747540)
Location: drivers/cpufreq/cpufreq_ondemand.c:223
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff817483a0)
Location: drivers/cpufreq/cpufreq_conservative.c:163
Inline: False
```
**Symbols:**

```
ffffffff81747540-ffffffff817475ba: store_up_threshold (STB_LOCAL)
ffffffff817483a0-ffffffff81748423: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765af0)
Location: drivers/cpufreq/cpufreq_ondemand.c:224
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81766a50)
Location: drivers/cpufreq/cpufreq_conservative.c:163
Inline: False
```
**Symbols:**

```
ffffffff81765af0-ffffffff81765b69: store_up_threshold (STB_LOCAL)
ffffffff81766a50-ffffffff81766ad5: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbb00)
Location: drivers/cpufreq/cpufreq_ondemand.c:224
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff817dc9f0)
Location: drivers/cpufreq/cpufreq_conservative.c:163
Inline: False
```
**Symbols:**

```
ffffffff817dbb00-ffffffff817dbb79: store_up_threshold (STB_LOCAL)
ffffffff817dc9f0-ffffffff817dca75: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818247b0)
Location: drivers/cpufreq/cpufreq_ondemand.c:224
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81825660)
Location: drivers/cpufreq/cpufreq_conservative.c:163
Inline: False
```
**Symbols:**

```
ffffffff818247b0-ffffffff81824829: store_up_threshold (STB_LOCAL)
ffffffff81825660-ffffffff818256e5: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850800)
Location: drivers/cpufreq/cpufreq_ondemand.c:224
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818515d0)
Location: drivers/cpufreq/cpufreq_conservative.c:165
Inline: False
```
**Symbols:**

```
ffffffff81850800-ffffffff81850879: store_up_threshold (STB_LOCAL)
ffffffff818515d0-ffffffff81851655: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81893d40)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81894ae0)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff81893d40-ffffffff81893db7: store_up_threshold (STB_LOCAL)
ffffffff81894ae0-ffffffff81894b62: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c5d60)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818c6b00)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff818c5d60-ffffffff818c5dd7: store_up_threshold (STB_LOCAL)
ffffffff818c6b00-ffffffff818c6b82: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81997de0)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81998c30)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff81997de0-ffffffff81997e57: store_up_threshold (STB_LOCAL)
ffffffff81998c30-ffffffff81998cb2: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199af00)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff8199bd10)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff8199af00-ffffffff8199af77: store_up_threshold (STB_LOCAL)
ffffffff8199bd10-ffffffff8199bd92: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197fbe0)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff819809d0)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff8197fbe0-ffffffff8197fc57: store_up_threshold (STB_LOCAL)
ffffffff819809d0-ffffffff81980a52: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a28d80)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81a29b70)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff81a28d80-ffffffff81a28df7: store_up_threshold (STB_LOCAL)
ffffffff81a29b70-ffffffff81a29bf2: store_up_threshold (STB_LOCAL)
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
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b23cd0)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffff800010b24d38)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffff800010b23cd0-ffff800010b23d68: store_up_threshold (STB_LOCAL)
ffff800010b24d38-ffff800010b24ddc: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfde00)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (c0bfecc0)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
c0bfde00-c0bfde94: store_up_threshold (STB_LOCAL)
c0bfecc0-c0bfed60: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c18430)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (c000000000c198e0)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
c000000000c18430-c000000000c184e0: store_up_threshold (STB_LOCAL)
c000000000c198e0-c000000000c199a0: store_up_threshold (STB_LOCAL)
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
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a480)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff8186b220)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff8186a480-ffffffff8186a4f7: store_up_threshold (STB_LOCAL)
ffffffff8186b220-ffffffff8186b2a2: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81833130)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81833ed0)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff81833130-ffffffff818331a7: store_up_threshold (STB_LOCAL)
ffffffff81833ed0-ffffffff81833f52: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb210)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818bbfb0)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff818bb210-ffffffff818bb287: store_up_threshold (STB_LOCAL)
ffffffff818bbfb0-ffffffff818bc032: store_up_threshold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t store_up_threshold(struct gov_attr_set *attr_set, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7500)
Location: drivers/cpufreq/cpufreq_ondemand.c:221
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818d82a0)
Location: drivers/cpufreq/cpufreq_conservative.c:162
Inline: False
```
**Symbols:**

```
ffffffff818d7500-ffffffff818d7577: store_up_threshold (STB_LOCAL)
ffffffff818d82a0-ffffffff818d8322: store_up_threshold (STB_LOCAL)
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
