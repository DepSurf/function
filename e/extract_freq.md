# Function: <code>extract_freq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int extract_freq(u32 val, struct acpi_cpufreq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b6020)
Location: drivers/cpufreq/acpi-cpufreq.c:238
Inline: True
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff816b6020-ffffffff816b610b: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81717bb0)
Location: drivers/cpufreq/acpi-cpufreq.c:236
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81717bb0-ffffffff81717ca9: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81749960)
Location: drivers/cpufreq/acpi-cpufreq.c:239
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81749960-ffffffff81749a59: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81767fa0)
Location: drivers/cpufreq/acpi-cpufreq.c:239
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81767fa0-ffffffff81768093: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817dde90)
Location: drivers/cpufreq/acpi-cpufreq.c:239
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff817dde90-ffffffff817ddf8a: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81826b50)
Location: drivers/cpufreq/acpi-cpufreq.c:239
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81826b50-ffffffff81826c49: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81852a40)
Location: drivers/cpufreq/acpi-cpufreq.c:244
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81852a40-ffffffff81852b43: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81896000)
Location: drivers/cpufreq/acpi-cpufreq.c:227
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81896000-ffffffff818960f6: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c8010)
Location: drivers/cpufreq/acpi-cpufreq.c:227
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff818c8010-ffffffff818c8106: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199a210)
Location: drivers/cpufreq/acpi-cpufreq.c:230
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff8199a210-ffffffff8199a306: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d370)
Location: drivers/cpufreq/acpi-cpufreq.c:231
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff8199d370-ffffffff8199d466: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81981eb0)
Location: drivers/cpufreq/acpi-cpufreq.c:231
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81981eb0-ffffffff81981fa6: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2b1e0)
Location: drivers/cpufreq/acpi-cpufreq.c:231
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81a2b1e0-ffffffff81a2b339: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b957b0)
Location: drivers/cpufreq/acpi-cpufreq.c:231
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81b957b0-ffffffff81b95928: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36080)
Location: drivers/cpufreq/acpi-cpufreq.c:236
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81d36080-ffffffff81d361f8: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9f3f0)
Location: drivers/cpufreq/acpi-cpufreq.c:237
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81d9f3f0-ffffffff81d9f569: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57200)
Location: drivers/cpufreq/acpi-cpufreq.c:237
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81e57200-ffffffff81e57379: extract_freq (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186c730)
Location: drivers/cpufreq/acpi-cpufreq.c:227
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff8186c730-ffffffff8186c826: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835250)
Location: drivers/cpufreq/acpi-cpufreq.c:227
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff81835250-ffffffff81835346: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd4c0)
Location: drivers/cpufreq/acpi-cpufreq.c:227
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff818bd4c0-ffffffff818bd5b6: extract_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy *policy, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d97b0)
Location: drivers/cpufreq/acpi-cpufreq.c:227
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu
```
**Symbols:**

```
ffffffff818d97b0-ffffffff818d98a6: extract_freq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpufreq_policy *policy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_cpufreq_data *data</code>
</li>
<li>
<b>Param reordered. </b>
<code>val, data</code> ➡️ <code>policy, val</code>
</li>
</ul>
</details>
</li>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
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
