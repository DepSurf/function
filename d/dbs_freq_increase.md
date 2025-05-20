# Function: <code>dbs_freq_increase</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dbs_freq_increase(struct cpufreq_policy *policy, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b34a0)
Location: drivers/cpufreq/cpufreq_ondemand.c:135
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_check_cpu
```
**Symbols:**

```
ffffffff816b34a0-ffffffff816b34fa: dbs_freq_increase (STB_LOCAL)
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817155e1)
Location: drivers/cpufreq/cpufreq_ondemand.c:115
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747365)
Location: drivers/cpufreq/cpufreq_ondemand.c:115
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765a4e)
Location: drivers/cpufreq/cpufreq_ondemand.c:116
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dba64)
Location: drivers/cpufreq/cpufreq_ondemand.c:116
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824716)
Location: drivers/cpufreq/cpufreq_ondemand.c:116
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818506a6)
Location: drivers/cpufreq/cpufreq_ondemand.c:116
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81893bda)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c5bfa)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81997be7)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199ad07)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197fa7b)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a28c1b)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b92be5)
Location: drivers/cpufreq/cpufreq_ondemand.c:115
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d33165)
Location: drivers/cpufreq/cpufreq_ondemand.c:115
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9c4f5)
Location: drivers/cpufreq/cpufreq_ondemand.c:115
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e541b5)
Location: drivers/cpufreq/cpufreq_ondemand.c:115
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b23b58)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (c0bfdccc)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c1825c)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a31a)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81832fca)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb0aa)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d739a)
Location: drivers/cpufreq/cpufreq_ondemand.c:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
