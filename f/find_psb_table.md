# Function: <code>find_psb_table</code>

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
In drivers/cpufreq/powernow-k8.c (ffffffff816b81e9)
Location: drivers/cpufreq/powernow-k8.c:629
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81719bb0)
Location: drivers/cpufreq/powernow-k8.c:629
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81719bb0-ffffffff8171a243: find_psb_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff8174b970)
Location: drivers/cpufreq/powernow-k8.c:629
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8174b970-ffffffff8174c009: find_psb_table (STB_LOCAL)
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
In drivers/cpufreq/powernow-k8.c (ffffffff8176a0d5)
Location: drivers/cpufreq/powernow-k8.c:629
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
In drivers/cpufreq/powernow-k8.c (ffffffff817dffb5)
Location: drivers/cpufreq/powernow-k8.c:629
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:625
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff818287b0-ffffffff81828d38: find_psb_table (STB_LOCAL)
ffffffff818296a5-ffffffff818297cb: find_psb_table.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:625
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81854840-ffffffff81854dc8: find_psb_table (STB_LOCAL)
ffffffff818555b1-ffffffff818556d7: find_psb_table.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff818972f0-ffffffff81897832: find_psb_table (STB_LOCAL)
ffffffff81898a51-ffffffff81898ba2: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff818c9300-ffffffff818c9842: find_psb_table (STB_LOCAL)
ffffffff818caa41-ffffffff818cab92: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8199c710-ffffffff8199ca1d: find_psb_table (STB_LOCAL)
ffffffff8199d05c-ffffffff8199d0c0: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8199f7a0-ffffffff8199faad: find_psb_table (STB_LOCAL)
ffffffff81c29ea1-ffffffff81c29f05: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff819841e0-ffffffff819844ed: find_psb_table (STB_LOCAL)
ffffffff81c1c21d-ffffffff81c1c281: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81a2d850-ffffffff81a2db57: find_psb_table (STB_LOCAL)
ffffffff81d2c77f-ffffffff81d2c7e3: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81b991a0-ffffffff81b994cf: find_psb_table (STB_LOCAL)
ffffffff81ef8a9c-ffffffff81ef8ae8: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3a0a0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81d3a0a0-ffffffff81d3a420: find_psb_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81da4b30)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81da4b30-ffffffff81da4eb0: find_psb_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5cac0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81e5cac0-ffffffff81e5ce40: find_psb_table (STB_LOCAL)
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
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8186da20-ffffffff8186df62: find_psb_table (STB_LOCAL)
ffffffff8186f161-ffffffff8186f2b2: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81837070-ffffffff81837583: find_psb_table (STB_LOCAL)
ffffffff81838019-ffffffff81838170: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff818be7b0-ffffffff818becf2: find_psb_table (STB_LOCAL)
ffffffff818bfef1-ffffffff818c0042: find_psb_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int find_psb_table(struct powernow_k8_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:622
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff818daac0-ffffffff818db002: find_psb_table (STB_LOCAL)
ffffffff818dc201-ffffffff818dc352: find_psb_table.cold (STB_LOCAL)
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
