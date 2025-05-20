# Function: <code>od_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715586)
Location: drivers/cpufreq/cpufreq_ondemand.c:136
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747320)
Location: drivers/cpufreq/cpufreq_ondemand.c:136
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765998)
Location: drivers/cpufreq/cpufreq_ondemand.c:137
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817db9a8)
Location: drivers/cpufreq/cpufreq_ondemand.c:137
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824658)
Location: drivers/cpufreq/cpufreq_ondemand.c:137
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818505e8)
Location: drivers/cpufreq/cpufreq_ondemand.c:137
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81893b12)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c5b32)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void od_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81997b90)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
```
**Symbols:**

```
ffffffff81997b90-ffffffff81997c90: od_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void od_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199acb0)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
```
**Symbols:**

```
ffffffff8199acb0-ffffffff8199adb0: od_update (STB_LOCAL)
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197f9b2)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a28b52)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b92b0b)
Location: drivers/cpufreq/cpufreq_ondemand.c:136
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d3308b)
Location: drivers/cpufreq/cpufreq_ondemand.c:136
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9c41b)
Location: drivers/cpufreq/cpufreq_ondemand.c:136
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e540db)
Location: drivers/cpufreq/cpufreq_ondemand.c:136
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
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b23a9c)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (c0bfdc08)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c18158)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a252)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81832f02)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bafe2)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d72d2)
Location: drivers/cpufreq/cpufreq_ondemand.c:134
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
