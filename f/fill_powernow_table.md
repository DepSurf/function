# Function: <code>fill_powernow_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff816b844c)
Location: drivers/cpufreq/powernow-k8.c:564
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81719d5b)
Location: drivers/cpufreq/powernow-k8.c:564
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff8174bb1b)
Location: drivers/cpufreq/powernow-k8.c:564
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a2a4)
Location: drivers/cpufreq/powernow-k8.c:564
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff817e0156)
Location: drivers/cpufreq/powernow-k8.c:564
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff818288f3)
Location: drivers/cpufreq/powernow-k8.c:562
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81854983)
Location: drivers/cpufreq/powernow-k8.c:562
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81897442)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9452)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table(struct powernow_k8_data *data, struct pst_s *pst, u8 maxvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
**Symbols:**

```
ffffffff8199c500-ffffffff8199c70e: fill_powernow_table (STB_LOCAL)
ffffffff8199d015-ffffffff8199d05c: fill_powernow_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table(struct powernow_k8_data *data, struct pst_s *pst, u8 maxvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
**Symbols:**

```
ffffffff8199f590-ffffffff8199f79e: fill_powernow_table (STB_LOCAL)
ffffffff81c29e5a-ffffffff81c29ea1: fill_powernow_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table(struct powernow_k8_data *data, struct pst_s *pst, u8 maxvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
**Symbols:**

```
ffffffff81983f80-ffffffff819841de: fill_powernow_table (STB_LOCAL)
ffffffff81c1c12d-ffffffff81c1c21d: fill_powernow_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table(struct powernow_k8_data *data, struct pst_s *pst, u8 maxvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
**Symbols:**

```
ffffffff81a2d5e0-ffffffff81a2d846: fill_powernow_table (STB_LOCAL)
ffffffff81d2c68f-ffffffff81d2c77f: fill_powernow_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table(struct powernow_k8_data *data, struct pst_s *pst, u8 maxvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
**Symbols:**

```
ffffffff81b98f20-ffffffff81b9919c: fill_powernow_table (STB_LOCAL)
ffffffff81ef89d9-ffffffff81ef8a9c: fill_powernow_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fill_powernow_table(struct powernow_k8_data *data, struct pst_s *pst, u8 maxvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81d39d50)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
**Symbols:**

```
ffffffff81d39d50-ffffffff81d3a088: fill_powernow_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fill_powernow_table(struct powernow_k8_data *data, struct pst_s *pst, u8 maxvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81da47e0)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
**Symbols:**

```
ffffffff81da47e0-ffffffff81da4b17: fill_powernow_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fill_powernow_table(struct powernow_k8_data *data, struct pst_s *pst, u8 maxvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5c770)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
**Symbols:**

```
ffffffff81e5c770-ffffffff81e5caa7: fill_powernow_table (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff8186db72)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff818371c0)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff818be902)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff818dac12)
Location: drivers/cpufreq/powernow-k8.c:559
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
