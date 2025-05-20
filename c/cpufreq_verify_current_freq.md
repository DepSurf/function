# Function: <code>cpufreq_verify_current_freq</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188ffe0)
Location: drivers/cpufreq/cpufreq.c:1640
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff8188ffe0-ffffffff818900c8: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c21e0)
Location: drivers/cpufreq/cpufreq.c:1654
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff818c21e0-ffffffff818c22c8: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819948f0)
Location: drivers/cpufreq/cpufreq.c:1671
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff819948f0-ffffffff819949d8: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81997840)
Location: drivers/cpufreq/cpufreq.c:1676
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81997840-ffffffff81997928: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197c500)
Location: drivers/cpufreq/cpufreq.c:1682
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff8197c500-ffffffff8197c5e8: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1688
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81a25790-ffffffff81a25888: cpufreq_verify_current_freq (STB_LOCAL)
ffffffff81d2bf7e-ffffffff81d2bf93: cpufreq_verify_current_freq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1710
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_start_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81b8e9e0-ffffffff81b8eb23: cpufreq_verify_current_freq (STB_LOCAL)
ffffffff81ef81aa-ffffffff81ef81bf: cpufreq_verify_current_freq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1707
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_start_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81d2ed50-ffffffff81d2ee93: cpufreq_verify_current_freq (STB_LOCAL)
ffffffff820a8d5b-ffffffff820a8d70: cpufreq_verify_current_freq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1714
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_start_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81d97e80-ffffffff81d97fc3: cpufreq_verify_current_freq (STB_LOCAL)
ffffffff82129f74-ffffffff82129f89: cpufreq_verify_current_freq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1755
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_start_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81e4fb00-ffffffff81e4fc43: cpufreq_verify_current_freq (STB_LOCAL)
ffffffff8220bd4e-ffffffff8220bd63: cpufreq_verify_current_freq.cold (STB_LOCAL)
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
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1eac0)
Location: drivers/cpufreq/cpufreq.c:1654
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffff800010b1eac0-ffff800010b1ebd0: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf903c)
Location: drivers/cpufreq/cpufreq.c:1654
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:show_cpuinfo_cur_freq
```
**Symbols:**

```
c0bf903c-c0bf9168: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c11620)
Location: drivers/cpufreq/cpufreq.c:1654
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
c000000000c11620-c000000000c1178c: cpufreq_verify_current_freq (STB_LOCAL)
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
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81866900)
Location: drivers/cpufreq/cpufreq.c:1654
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff81866900-ffffffff818669e8: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182f5b0)
Location: drivers/cpufreq/cpufreq.c:1654
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff8182f5b0-ffffffff8182f698: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b7690)
Location: drivers/cpufreq/cpufreq.c:1654
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff818b7690-ffffffff818b7778: cpufreq_verify_current_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int cpufreq_verify_current_freq(struct cpufreq_policy *policy, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d2cd0)
Location: drivers/cpufreq/cpufreq.c:1654
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff818d2cd0-ffffffff818d2db8: cpufreq_verify_current_freq (STB_LOCAL)
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
