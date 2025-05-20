# Function: <code>core_frequency_transition</code>

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
In drivers/cpufreq/powernow-k8.c (ffffffff816b7b6e)
Location: drivers/cpufreq/powernow-k8.c:340
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
In drivers/cpufreq/powernow-k8.c (ffffffff8171965e)
Location: drivers/cpufreq/powernow-k8.c:340
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
In drivers/cpufreq/powernow-k8.c (ffffffff8174b28b)
Location: drivers/cpufreq/powernow-k8.c:340
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
In drivers/cpufreq/powernow-k8.c (ffffffff81769afe)
Location: drivers/cpufreq/powernow-k8.c:340
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
In drivers/cpufreq/powernow-k8.c (ffffffff817df891)
Location: drivers/cpufreq/powernow-k8.c:340
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
In drivers/cpufreq/powernow-k8.c (ffffffff81828138)
Location: drivers/cpufreq/powernow-k8.c:338
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
In drivers/cpufreq/powernow-k8.c (ffffffff818541c8)
Location: drivers/cpufreq/powernow-k8.c:338
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
In drivers/cpufreq/powernow-k8.c (ffffffff81898268)
Location: drivers/cpufreq/powernow-k8.c:335
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
In drivers/cpufreq/powernow-k8.c (ffffffff818ca258)
Location: drivers/cpufreq/powernow-k8.c:335
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
int core_frequency_transition(struct powernow_k8_data *data, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:335
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_fid_vid
```
**Symbols:**

```
ffffffff8199bf30-ffffffff8199c096: core_frequency_transition (STB_LOCAL)
ffffffff8199cf40-ffffffff8199cf89: core_frequency_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int core_frequency_transition(struct powernow_k8_data *data, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:335
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_fid_vid
```
**Symbols:**

```
ffffffff8199efd0-ffffffff8199f136: core_frequency_transition (STB_LOCAL)
ffffffff81c29d85-ffffffff81c29dce: core_frequency_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int core_frequency_transition(struct powernow_k8_data *data, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:335
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81983bf0-ffffffff81983d51: core_frequency_transition (STB_LOCAL)
ffffffff81c1c0ba-ffffffff81c1c103: core_frequency_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int core_frequency_transition(struct powernow_k8_data *data, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:335
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81a2d260-ffffffff81a2d3be: core_frequency_transition (STB_LOCAL)
ffffffff81d2c61c-ffffffff81d2c665: core_frequency_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int core_frequency_transition(struct powernow_k8_data *data, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:335
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81b989d0-ffffffff81b98b60: core_frequency_transition (STB_LOCAL)
ffffffff81ef893f-ffffffff81ef897c: core_frequency_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int core_frequency_transition(struct powernow_k8_data *data, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81d398a0)
Location: drivers/cpufreq/powernow-k8.c:335
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81d398a0-ffffffff81d39a90: core_frequency_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int core_frequency_transition(struct powernow_k8_data *data, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81da4340)
Location: drivers/cpufreq/powernow-k8.c:335
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81da4340-ffffffff81da4530: core_frequency_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int core_frequency_transition(struct powernow_k8_data *data, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5c3d0)
Location: drivers/cpufreq/powernow-k8.c:335
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81e5c3d0-ffffffff81e5c5c0: core_frequency_transition (STB_LOCAL)
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
In drivers/cpufreq/powernow-k8.c (ffffffff8186e978)
Location: drivers/cpufreq/powernow-k8.c:335
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
In drivers/cpufreq/powernow-k8.c (ffffffff81836ca1)
Location: drivers/cpufreq/powernow-k8.c:335
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
In drivers/cpufreq/powernow-k8.c (ffffffff818bf708)
Location: drivers/cpufreq/powernow-k8.c:335
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
In drivers/cpufreq/powernow-k8.c (ffffffff818dba18)
Location: drivers/cpufreq/powernow-k8.c:335
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
