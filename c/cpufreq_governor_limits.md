# Function: <code>cpufreq_governor_limits</code>

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
In drivers/cpufreq/cpufreq_governor.c (ffffffff816b58d5)
Location: drivers/cpufreq/cpufreq_governor.c:506
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8171152d)
Location: drivers/cpufreq/cpufreq.c:2097
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
```
**Symbols:**

```
ffffffff81711470-ffffffff817114b9: cpufreq_governor_limits.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8174461f)
Location: drivers/cpufreq/cpufreq.c:2069
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
```
**Symbols:**

```
ffffffff817432b0-ffffffff817432f6: cpufreq_governor_limits.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81762daf)
Location: drivers/cpufreq/cpufreq.c:2072
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81761970-ffffffff817619b6: cpufreq_governor_limits.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d8c4f)
Location: drivers/cpufreq/cpufreq.c:2105
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff817d7950-ffffffff817d7999: cpufreq_governor_limits.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_governor_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81820380)
Location: drivers/cpufreq/cpufreq.c:2104
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81820380-ffffffff818203dc: cpufreq_governor_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_governor_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184c230)
Location: drivers/cpufreq/cpufreq.c:2105
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8184c230-ffffffff8184c28c: cpufreq_governor_limits (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff81891569)
Location: drivers/cpufreq/cpufreq.c:2255
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff818c3751)
Location: drivers/cpufreq/cpufreq.c:2269
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81995b50)
Location: drivers/cpufreq/cpufreq.c:2306
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81998a0d)
Location: drivers/cpufreq/cpufreq.c:2382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff8197d4f3)
Location: drivers/cpufreq/cpufreq.c:2388
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81a2655e)
Location: drivers/cpufreq/cpufreq.c:2390
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81b9019b)
Location: drivers/cpufreq/cpufreq.c:2430
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81d30323)
Location: drivers/cpufreq/cpufreq.c:2427
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81d99603)
Location: drivers/cpufreq/cpufreq.c:2434
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81e5128d)
Location: drivers/cpufreq/cpufreq.c:2475
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffff800010b21120)
Location: drivers/cpufreq/cpufreq.c:2269
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (c0bfb6d8)
Location: drivers/cpufreq/cpufreq.c:2269
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (c000000000c14e44)
Location: drivers/cpufreq/cpufreq.c:2269
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81867e71)
Location: drivers/cpufreq/cpufreq.c:2269
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff81830b21)
Location: drivers/cpufreq/cpufreq.c:2269
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff818b8c01)
Location: drivers/cpufreq/cpufreq.c:2269
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
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
In drivers/cpufreq/cpufreq.c (ffffffff818d4edd)
Location: drivers/cpufreq/cpufreq.c:2269
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
