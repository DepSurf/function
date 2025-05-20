# Function: <code>transition_fid_vid</code>

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
In drivers/cpufreq/powernow-k8.c (ffffffff816b79c5)
Location: drivers/cpufreq/powernow-k8.c:256
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
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
In drivers/cpufreq/powernow-k8.c (ffffffff8171948c)
Location: drivers/cpufreq/powernow-k8.c:256
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
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
In drivers/cpufreq/powernow-k8.c (ffffffff8174b0bc)
Location: drivers/cpufreq/powernow-k8.c:256
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
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
In drivers/cpufreq/powernow-k8.c (ffffffff817698c3)
Location: drivers/cpufreq/powernow-k8.c:256
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
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
In drivers/cpufreq/powernow-k8.c (ffffffff817df659)
Location: drivers/cpufreq/powernow-k8.c:256
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
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
In drivers/cpufreq/powernow-k8.c (ffffffff81827f73)
Location: drivers/cpufreq/powernow-k8.c:254
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
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
In drivers/cpufreq/powernow-k8.c (ffffffff81854003)
Location: drivers/cpufreq/powernow-k8.c:254
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
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
In drivers/cpufreq/powernow-k8.c (ffffffff81898087)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
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
In drivers/cpufreq/powernow-k8.c (ffffffff818ca077)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int transition_fid_vid(struct powernow_k8_data *data, u32 reqfid, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff8199c0a0-ffffffff8199c14c: transition_fid_vid (STB_LOCAL)
ffffffff8199cf89-ffffffff8199cfac: transition_fid_vid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int transition_fid_vid(struct powernow_k8_data *data, u32 reqfid, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff8199f140-ffffffff8199f1ec: transition_fid_vid (STB_LOCAL)
ffffffff81c29dce-ffffffff81c29df1: transition_fid_vid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81983e00)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2d460)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81b98c18)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3aa45)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81da5545)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5d605)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
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
In drivers/cpufreq/powernow-k8.c (ffffffff8186e797)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
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
In drivers/cpufreq/powernow-k8.c (ffffffff81836aba)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
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
In drivers/cpufreq/powernow-k8.c (ffffffff818bf527)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
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
In drivers/cpufreq/powernow-k8.c (ffffffff818db837)
Location: drivers/cpufreq/powernow-k8.c:251
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
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
</ul>
