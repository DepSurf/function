# Function: <code>core_voltage_post_transition</code>

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
In drivers/cpufreq/powernow-k8.c (ffffffff816b7c15)
Location: drivers/cpufreq/powernow-k8.c:411
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
In drivers/cpufreq/powernow-k8.c (ffffffff817196f4)
Location: drivers/cpufreq/powernow-k8.c:411
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
In drivers/cpufreq/powernow-k8.c (ffffffff8174b321)
Location: drivers/cpufreq/powernow-k8.c:411
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
In drivers/cpufreq/powernow-k8.c (ffffffff81769d20)
Location: drivers/cpufreq/powernow-k8.c:411
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
In drivers/cpufreq/powernow-k8.c (ffffffff817dfab4)
Location: drivers/cpufreq/powernow-k8.c:411
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
In drivers/cpufreq/powernow-k8.c (ffffffff818283a9)
Location: drivers/cpufreq/powernow-k8.c:409
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
In drivers/cpufreq/powernow-k8.c (ffffffff81854432)
Location: drivers/cpufreq/powernow-k8.c:409
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
In drivers/cpufreq/powernow-k8.c (ffffffff8189842f)
Location: drivers/cpufreq/powernow-k8.c:406
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
In drivers/cpufreq/powernow-k8.c (ffffffff818ca41f)
Location: drivers/cpufreq/powernow-k8.c:406
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
int core_voltage_post_transition(struct powernow_k8_data *data, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_fid_vid
```
**Symbols:**

```
ffffffff8199bb20-ffffffff8199bc3d: core_voltage_post_transition (STB_LOCAL)
ffffffff8199ce98-ffffffff8199ceca: core_voltage_post_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int core_voltage_post_transition(struct powernow_k8_data *data, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_fid_vid
```
**Symbols:**

```
ffffffff8199ebc0-ffffffff8199ecdd: core_voltage_post_transition (STB_LOCAL)
ffffffff81c29cdd-ffffffff81c29d0f: core_voltage_post_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int core_voltage_post_transition(struct powernow_k8_data *data, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff819837e0-ffffffff819838fd: core_voltage_post_transition (STB_LOCAL)
ffffffff81c1c012-ffffffff81c1c044: core_voltage_post_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int core_voltage_post_transition(struct powernow_k8_data *data, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81a2ce50-ffffffff81a2cf61: core_voltage_post_transition (STB_LOCAL)
ffffffff81d2c550-ffffffff81d2c582: core_voltage_post_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int core_voltage_post_transition(struct powernow_k8_data *data, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81b98590-ffffffff81b9868e: core_voltage_post_transition (STB_LOCAL)
ffffffff81ef889a-ffffffff81ef88c2: core_voltage_post_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int core_voltage_post_transition(struct powernow_k8_data *data, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81d395f0)
Location: drivers/cpufreq/powernow-k8.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81d395f0-ffffffff81d39719: core_voltage_post_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int core_voltage_post_transition(struct powernow_k8_data *data, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81da4090)
Location: drivers/cpufreq/powernow-k8.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81da4090-ffffffff81da41b9: core_voltage_post_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int core_voltage_post_transition(struct powernow_k8_data *data, u32 reqvid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5c120)
Location: drivers/cpufreq/powernow-k8.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81e5c120-ffffffff81e5c249: core_voltage_post_transition (STB_LOCAL)
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
In drivers/cpufreq/powernow-k8.c (ffffffff8186eb3f)
Location: drivers/cpufreq/powernow-k8.c:406
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
In drivers/cpufreq/powernow-k8.c (ffffffff81836e71)
Location: drivers/cpufreq/powernow-k8.c:406
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
In drivers/cpufreq/powernow-k8.c (ffffffff818bf8cf)
Location: drivers/cpufreq/powernow-k8.c:406
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
In drivers/cpufreq/powernow-k8.c (ffffffff818dbbdf)
Location: drivers/cpufreq/powernow-k8.c:406
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
