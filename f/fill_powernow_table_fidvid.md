# Function: <code>fill_powernow_table_fidvid</code>

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
In drivers/cpufreq/powernow-k8.c (ffffffff816b8777)
Location: drivers/cpufreq/powernow-k8.c:807
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
In drivers/cpufreq/powernow-k8.c (ffffffff8171a4d7)
Location: drivers/cpufreq/powernow-k8.c:807
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In drivers/cpufreq/powernow-k8.c (ffffffff8174c29c)
Location: drivers/cpufreq/powernow-k8.c:807
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In drivers/cpufreq/powernow-k8.c (ffffffff8176a895)
Location: drivers/cpufreq/powernow-k8.c:807
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
In drivers/cpufreq/powernow-k8.c (ffffffff817e077a)
Location: drivers/cpufreq/powernow-k8.c:807
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
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:801
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:801
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table_fidvid(struct powernow_k8_data *data, struct cpufreq_frequency_table *powernow_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
**Symbols:**

```
ffffffff8199b130-ffffffff8199b2d9: fill_powernow_table_fidvid (STB_LOCAL)
ffffffff8199cc95-ffffffff8199cccf: fill_powernow_table_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table_fidvid(struct powernow_k8_data *data, struct cpufreq_frequency_table *powernow_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
**Symbols:**

```
ffffffff8199e1f0-ffffffff8199e399: fill_powernow_table_fidvid (STB_LOCAL)
ffffffff81c29ada-ffffffff81c29b14: fill_powernow_table_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table_fidvid(struct powernow_k8_data *data, struct cpufreq_frequency_table *powernow_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
**Symbols:**

```
ffffffff81982ed0-ffffffff81983089: fill_powernow_table_fidvid (STB_LOCAL)
ffffffff81c1bea7-ffffffff81c1bee1: fill_powernow_table_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table_fidvid(struct powernow_k8_data *data, struct cpufreq_frequency_table *powernow_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
**Symbols:**

```
ffffffff81a2c4c0-ffffffff81a2c673: fill_powernow_table_fidvid (STB_LOCAL)
ffffffff81d2c3e5-ffffffff81d2c41f: fill_powernow_table_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fill_powernow_table_fidvid(struct powernow_k8_data *data, struct cpufreq_frequency_table *powernow_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
**Symbols:**

```
ffffffff81b97ce0-ffffffff81b97eb4: fill_powernow_table_fidvid (STB_LOCAL)
ffffffff81ef87a1-ffffffff81ef87d0: fill_powernow_table_fidvid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fill_powernow_table_fidvid(struct powernow_k8_data *data, struct cpufreq_frequency_table *powernow_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81d38c30)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
**Symbols:**

```
ffffffff81d38c30-ffffffff81d38dde: fill_powernow_table_fidvid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fill_powernow_table_fidvid(struct powernow_k8_data *data, struct cpufreq_frequency_table *powernow_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81da36b0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
**Symbols:**

```
ffffffff81da36b0-ffffffff81da387f: fill_powernow_table_fidvid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fill_powernow_table_fidvid(struct powernow_k8_data *data, struct cpufreq_frequency_table *powernow_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5b740)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: False
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
**Symbols:**

```
ffffffff81e5b740-ffffffff81e5b90f: fill_powernow_table_fidvid (STB_LOCAL)
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
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In drivers/cpufreq/powernow-k8.c (0)
Location: drivers/cpufreq/powernow-k8.c:798
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
