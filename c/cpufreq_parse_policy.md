# Function: <code>cpufreq_parse_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188f520)
Location: drivers/cpufreq/cpufreq.c:616
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff8188f520-ffffffff8188f57c: cpufreq_parse_policy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0e00)
Location: drivers/cpufreq/cpufreq.c:619
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff818c0e00-ffffffff818c0e4c: cpufreq_parse_policy (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff81995f7e)
Location: drivers/cpufreq/cpufreq.c:642
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81998e67)
Location: drivers/cpufreq/cpufreq.c:649
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff8197e05f)
Location: drivers/cpufreq/cpufreq.c:646
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81a2713a)
Location: drivers/cpufreq/cpufreq.c:647
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81b911d6)
Location: drivers/cpufreq/cpufreq.c:648
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81d31449)
Location: drivers/cpufreq/cpufreq.c:648
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81d9a70d)
Location: drivers/cpufreq/cpufreq.c:655
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81e524bb)
Location: drivers/cpufreq/cpufreq.c:690
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1d848)
Location: drivers/cpufreq/cpufreq.c:619
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffff800010b1d848-ffff800010b1d8b0: cpufreq_parse_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf86bc)
Location: drivers/cpufreq/cpufreq.c:619
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
c0bf86bc-c0bf8714: cpufreq_parse_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c10880)
Location: drivers/cpufreq/cpufreq.c:619
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
c000000000c10880-c000000000c10918: cpufreq_parse_policy (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81865520)
Location: drivers/cpufreq/cpufreq.c:619
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff81865520-ffffffff8186556c: cpufreq_parse_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182e1d0)
Location: drivers/cpufreq/cpufreq.c:619
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff8182e1d0-ffffffff8182e21c: cpufreq_parse_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b62b0)
Location: drivers/cpufreq/cpufreq.c:619
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff818b62b0-ffffffff818b62fc: cpufreq_parse_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int cpufreq_parse_policy(char *str_governor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d2560)
Location: drivers/cpufreq/cpufreq.c:619
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
```
**Symbols:**

```
ffffffff818d2560-ffffffff818d25ac: cpufreq_parse_policy (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
