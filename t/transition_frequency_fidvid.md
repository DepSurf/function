# Function: <code>transition_frequency_fidvid</code>

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
In drivers/cpufreq/powernow-k8.c (ffffffff816b791f)
Location: drivers/cpufreq/powernow-k8.c:889
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
In drivers/cpufreq/powernow-k8.c (ffffffff817193fc)
Location: drivers/cpufreq/powernow-k8.c:889
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
In drivers/cpufreq/powernow-k8.c (ffffffff8174b02c)
Location: drivers/cpufreq/powernow-k8.c:889
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
In drivers/cpufreq/powernow-k8.c (ffffffff81769833)
Location: drivers/cpufreq/powernow-k8.c:889
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
In drivers/cpufreq/powernow-k8.c (ffffffff817df5cb)
Location: drivers/cpufreq/powernow-k8.c:889
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
In drivers/cpufreq/powernow-k8.c (ffffffff81827ee2)
Location: drivers/cpufreq/powernow-k8.c:883
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
In drivers/cpufreq/powernow-k8.c (ffffffff81853f72)
Location: drivers/cpufreq/powernow-k8.c:883
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81897fc0-ffffffff81898627: transition_frequency_fidvid (STB_LOCAL)
ffffffff81898c9c-ffffffff81898d6a: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff818c9fb0-ffffffff818ca617: transition_frequency_fidvid (STB_LOCAL)
ffffffff818cac8c-ffffffff818cad5a: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff8199c150)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff8199c150-ffffffff8199c2f9: transition_frequency_fidvid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff8199f1f0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff8199f1f0-ffffffff8199f384: transition_frequency_fidvid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81983d60-ffffffff81983f77: transition_frequency_fidvid (STB_LOCAL)
ffffffff81c1c103-ffffffff81c1c12d: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81a2d3c0-ffffffff81a2d5d1: transition_frequency_fidvid (STB_LOCAL)
ffffffff81d2c665-ffffffff81d2c68f: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81b98b60-ffffffff81b98d97: transition_frequency_fidvid (STB_LOCAL)
ffffffff81ef897c-ffffffff81ef89a6: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3a990)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81d3a990-ffffffff81d3abe0: transition_frequency_fidvid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81da5490)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81da5490-ffffffff81da56e0: transition_frequency_fidvid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index, struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5d550)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81e5d550-ffffffff81e5d7a0: transition_frequency_fidvid (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff8186e6d0-ffffffff8186ed37: transition_frequency_fidvid (STB_LOCAL)
ffffffff8186f3ac-ffffffff8186f47a: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff818369f0-ffffffff8183706a: transition_frequency_fidvid (STB_LOCAL)
ffffffff81837f4d-ffffffff81838019: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff818bf460-ffffffff818bfac7: transition_frequency_fidvid (STB_LOCAL)
ffffffff818c013c-ffffffff818c020a: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int transition_frequency_fidvid(struct powernow_k8_data *data, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:880
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff818db770-ffffffff818dbdd7: transition_frequency_fidvid (STB_LOCAL)
ffffffff818dc44c-ffffffff818dc51a: transition_frequency_fidvid.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpufreq_policy *policy</code>
</li>
</ul>
</details>
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
