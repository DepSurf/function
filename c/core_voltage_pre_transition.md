# Function: <code>core_voltage_pre_transition</code>

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
Location: drivers/cpufreq/powernow-k8.c:285
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
Location: drivers/cpufreq/powernow-k8.c:285
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
Location: drivers/cpufreq/powernow-k8.c:285
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
Location: drivers/cpufreq/powernow-k8.c:285
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
Location: drivers/cpufreq/powernow-k8.c:285
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
Location: drivers/cpufreq/powernow-k8.c:283
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
Location: drivers/cpufreq/powernow-k8.c:283
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
Location: drivers/cpufreq/powernow-k8.c:280
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
Location: drivers/cpufreq/powernow-k8.c:280
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
int core_voltage_pre_transition(struct powernow_k8_data *data, u32 reqvid, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_fid_vid
```
**Symbols:**

```
ffffffff8199bc40-ffffffff8199be3f: core_voltage_pre_transition (STB_LOCAL)
ffffffff8199ceca-ffffffff8199cee2: core_voltage_pre_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int core_voltage_pre_transition(struct powernow_k8_data *data, u32 reqvid, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_fid_vid
```
**Symbols:**

```
ffffffff8199ece0-ffffffff8199eedf: core_voltage_pre_transition (STB_LOCAL)
ffffffff81c29d0f-ffffffff81c29d27: core_voltage_pre_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int core_voltage_pre_transition(struct powernow_k8_data *data, u32 reqvid, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81983900-ffffffff81983af7: core_voltage_pre_transition (STB_LOCAL)
ffffffff81c1c044-ffffffff81c1c05c: core_voltage_pre_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int core_voltage_pre_transition(struct powernow_k8_data *data, u32 reqvid, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81a2cf70-ffffffff81a2d167: core_voltage_pre_transition (STB_LOCAL)
ffffffff81d2c582-ffffffff81d2c59a: core_voltage_pre_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int core_voltage_pre_transition(struct powernow_k8_data *data, u32 reqvid, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81b98690-ffffffff81b988ce: core_voltage_pre_transition (STB_LOCAL)
ffffffff81ef88c2-ffffffff81ef88d5: core_voltage_pre_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int core_voltage_pre_transition(struct powernow_k8_data *data, u32 reqvid, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3a770)
Location: drivers/cpufreq/powernow-k8.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81d3a770-ffffffff81d3a97d: core_voltage_pre_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int core_voltage_pre_transition(struct powernow_k8_data *data, u32 reqvid, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81da5270)
Location: drivers/cpufreq/powernow-k8.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81da5270-ffffffff81da547d: core_voltage_pre_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int core_voltage_pre_transition(struct powernow_k8_data *data, u32 reqvid, u32 reqfid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5d330)
Location: drivers/cpufreq/powernow-k8.c:280
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81e5d330-ffffffff81e5d53d: core_voltage_pre_transition (STB_LOCAL)
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
Location: drivers/cpufreq/powernow-k8.c:280
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
Location: drivers/cpufreq/powernow-k8.c:280
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
Location: drivers/cpufreq/powernow-k8.c:280
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
Location: drivers/cpufreq/powernow-k8.c:280
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
