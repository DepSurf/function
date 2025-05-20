# Function: <code>cpufreq_add_policy_cpu</code>

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
In drivers/cpufreq/cpufreq.c (ffffffff816b188f)
Location: drivers/cpufreq/cpufreq.c:991
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
In drivers/cpufreq/cpufreq.c (ffffffff817139f4)
Location: drivers/cpufreq/cpufreq.c:1042
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
In drivers/cpufreq/cpufreq.c (ffffffff817458a8)
Location: drivers/cpufreq/cpufreq.c:1004
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
In drivers/cpufreq/cpufreq.c (ffffffff81763fa0)
Location: drivers/cpufreq/cpufreq.c:1022
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
In drivers/cpufreq/cpufreq.c (ffffffff817d9f96)
Location: drivers/cpufreq/cpufreq.c:1054
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
In drivers/cpufreq/cpufreq.c (ffffffff81822af3)
Location: drivers/cpufreq/cpufreq.c:1047
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
In drivers/cpufreq/cpufreq.c (ffffffff8184e9d3)
Location: drivers/cpufreq/cpufreq.c:1052
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
In drivers/cpufreq/cpufreq.c (ffffffff81891ba2)
Location: drivers/cpufreq/cpufreq.c:1083
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
In drivers/cpufreq/cpufreq.c (ffffffff818c3bc1)
Location: drivers/cpufreq/cpufreq.c:1090
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpufreq_add_policy_cpu(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81994fa0)
Location: drivers/cpufreq/cpufreq.c:1107
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81994fa0-ffffffff8199506d: cpufreq_add_policy_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpufreq_add_policy_cpu(struct cpufreq_policy *policy, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81999070)
Location: drivers/cpufreq/cpufreq.c:1111
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81999070-ffffffff8199913d: cpufreq_add_policy_cpu (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff8197db37)
Location: drivers/cpufreq/cpufreq.c:1108
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81a26be2)
Location: drivers/cpufreq/cpufreq.c:1108
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81b90bde)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81d310f7)
Location: drivers/cpufreq/cpufreq.c:1104
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81d9a3ac)
Location: drivers/cpufreq/cpufreq.c:1111
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffffffff81e520db)
Location: drivers/cpufreq/cpufreq.c:1152
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In drivers/cpufreq/cpufreq.c (ffff800010b215a0)
Location: drivers/cpufreq/cpufreq.c:1090
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
In drivers/cpufreq/cpufreq.c (c0bfbe70)
Location: drivers/cpufreq/cpufreq.c:1090
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
In drivers/cpufreq/cpufreq.c (c000000000c154bc)
Location: drivers/cpufreq/cpufreq.c:1090
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
In drivers/cpufreq/cpufreq.c (ffffffff818682e1)
Location: drivers/cpufreq/cpufreq.c:1090
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
In drivers/cpufreq/cpufreq.c (ffffffff81830f91)
Location: drivers/cpufreq/cpufreq.c:1090
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
In drivers/cpufreq/cpufreq.c (ffffffff818b9071)
Location: drivers/cpufreq/cpufreq.c:1090
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
In drivers/cpufreq/cpufreq.c (ffffffff818d5351)
Location: drivers/cpufreq/cpufreq.c:1090
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
</ul>
