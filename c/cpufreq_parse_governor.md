# Function: <code>cpufreq_parse_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_parse_governor(char *str_governor, unsigned int *policy, struct cpufreq_governor **governor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816b0f70)
Location: drivers/cpufreq/cpufreq.c:518
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff816b0f70-ffffffff816b1071: cpufreq_parse_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_parse_governor(char *str_governor, unsigned int *policy, struct cpufreq_governor **governor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81712570)
Location: drivers/cpufreq/cpufreq.c:572
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81712570-ffffffff81712669: cpufreq_parse_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_parse_governor(char *str_governor, unsigned int *policy, struct cpufreq_governor **governor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817437f0)
Location: drivers/cpufreq/cpufreq.c:572
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff817437f0-ffffffff817438e9: cpufreq_parse_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_parse_governor(char *str_governor, unsigned int *policy, struct cpufreq_governor **governor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81761e10)
Location: drivers/cpufreq/cpufreq.c:572
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81761e10-ffffffff81761f19: cpufreq_parse_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_parse_governor(char *str_governor, unsigned int *policy, struct cpufreq_governor **governor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d7df0)
Location: drivers/cpufreq/cpufreq.c:604
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff817d7df0-ffffffff817d7ef9: cpufreq_parse_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81820740)
Location: drivers/cpufreq/cpufreq.c:589
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81820740-ffffffff81820848: cpufreq_parse_governor.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184c5f0)
Location: drivers/cpufreq/cpufreq.c:589
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff8184c5f0-ffffffff8184c6f8: cpufreq_parse_governor.isra.30 (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff818918d6)
Location: drivers/cpufreq/cpufreq.c:633
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff818c39f7)
Location: drivers/cpufreq/cpufreq.c:634
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995e95)
Location: drivers/cpufreq/cpufreq.c:657
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998d95)
Location: drivers/cpufreq/cpufreq.c:664
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff8197d815)
Location: drivers/cpufreq/cpufreq.c:661
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff81a268a5)
Location: drivers/cpufreq/cpufreq.c:662
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff81b9059b)
Location: drivers/cpufreq/cpufreq.c:663
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff81d3077b)
Location: drivers/cpufreq/cpufreq.c:663
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff81d999fb)
Location: drivers/cpufreq/cpufreq.c:670
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff81e5166b)
Location: drivers/cpufreq/cpufreq.c:705
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b21444)
Location: drivers/cpufreq/cpufreq.c:634
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfbb00)
Location: drivers/cpufreq/cpufreq.c:634
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c152d0)
Location: drivers/cpufreq/cpufreq.c:634
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81868117)
Location: drivers/cpufreq/cpufreq.c:634
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff81830dc7)
Location: drivers/cpufreq/cpufreq.c:634
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff818b8ea7)
Location: drivers/cpufreq/cpufreq.c:634
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
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
In drivers/cpufreq/cpufreq.c (ffffffff818d5187)
Location: drivers/cpufreq/cpufreq.c:634
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
</ul>
