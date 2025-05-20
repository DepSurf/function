# Function: <code>cpufreq_policy_alloc</code>

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
In drivers/cpufreq/cpufreq.c (ffffffff816b1c9c)
Location: drivers/cpufreq/cpufreq.c:1025
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81713e35)
Location: drivers/cpufreq/cpufreq.c:1074
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81745bd9)
Location: drivers/cpufreq/cpufreq.c:1036
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff8176424c)
Location: drivers/cpufreq/cpufreq.c:1054
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff817da235)
Location: drivers/cpufreq/cpufreq.c:1086
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81822c8f)
Location: drivers/cpufreq/cpufreq.c:1079
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff8184ec67)
Location: drivers/cpufreq/cpufreq.c:1084
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81892011)
Location: drivers/cpufreq/cpufreq.c:1170
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff818c400c)
Location: drivers/cpufreq/cpufreq.c:1174
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_policy_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1191
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81993930-ffffffff81993b3c: cpufreq_policy_alloc (STB_LOCAL)
ffffffff819966d2-ffffffff81996753: cpufreq_policy_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_policy_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1195
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff819969d0-ffffffff81996bdc: cpufreq_policy_alloc (STB_LOCAL)
ffffffff81c2973c-ffffffff81c297bd: cpufreq_policy_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_policy_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1192
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8197b730-ffffffff8197b93c: cpufreq_policy_alloc (STB_LOCAL)
ffffffff81c1bae3-ffffffff81c1bb64: cpufreq_policy_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_policy_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1192
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81a24ac0-ffffffff81a24ccc: cpufreq_policy_alloc (STB_LOCAL)
ffffffff81d2be67-ffffffff81d2bee8: cpufreq_policy_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_policy_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1197
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81b8e260-ffffffff81b8e470: cpufreq_policy_alloc (STB_LOCAL)
ffffffff81ef80d8-ffffffff81ef8156: cpufreq_policy_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_policy_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2dd60)
Location: drivers/cpufreq/cpufreq.c:1188
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81d2dd60-ffffffff81d2dff8: cpufreq_policy_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_policy_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d96fd0)
Location: drivers/cpufreq/cpufreq.c:1195
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81d96fd0-ffffffff81d97268: cpufreq_policy_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_policy_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4ec30)
Location: drivers/cpufreq/cpufreq.c:1236
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81e4ec30-ffffffff81e4eeeb: cpufreq_policy_alloc (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffff800010b2168c)
Location: drivers/cpufreq/cpufreq.c:1174
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (c0bfbcc4)
Location: drivers/cpufreq/cpufreq.c:1174
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (c000000000c155fc)
Location: drivers/cpufreq/cpufreq.c:1174
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff8186872c)
Location: drivers/cpufreq/cpufreq.c:1174
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff818313dc)
Location: drivers/cpufreq/cpufreq.c:1174
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff818b94bc)
Location: drivers/cpufreq/cpufreq.c:1174
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff818d579c)
Location: drivers/cpufreq/cpufreq.c:1174
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
