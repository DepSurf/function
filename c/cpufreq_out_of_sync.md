# Function: <code>cpufreq_out_of_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpufreq_out_of_sync(struct cpufreq_policy *policy, unsigned int new_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816aef90)
Location: drivers/cpufreq/cpufreq.c:1433
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
```
**Symbols:**

```
ffffffff816aef90-ffffffff816af01f: cpufreq_out_of_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpufreq_out_of_sync(struct cpufreq_policy *policy, unsigned int new_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710880)
Location: drivers/cpufreq/cpufreq.c:1454
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_current_freq
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff81710880-ffffffff8171090b: cpufreq_out_of_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpufreq_out_of_sync(struct cpufreq_policy *policy, unsigned int new_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81742890)
Location: drivers/cpufreq/cpufreq.c:1423
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_current_freq
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff81742890-ffffffff81742915: cpufreq_out_of_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpufreq_out_of_sync(struct cpufreq_policy *policy, unsigned int new_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81760f10)
Location: drivers/cpufreq/cpufreq.c:1426
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_current_freq
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff81760f10-ffffffff81760f95: cpufreq_out_of_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpufreq_out_of_sync(struct cpufreq_policy *policy, unsigned int new_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d6ed0)
Location: drivers/cpufreq/cpufreq.c:1458
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_current_freq
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff817d6ed0-ffffffff817d6f55: cpufreq_out_of_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpufreq_out_of_sync(struct cpufreq_policy *policy, unsigned int new_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81820fd0)
Location: drivers/cpufreq/cpufreq.c:1456
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_current_freq
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff81820fd0-ffffffff81821055: cpufreq_out_of_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpufreq_out_of_sync(struct cpufreq_policy *policy, unsigned int new_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184cd40)
Location: drivers/cpufreq/cpufreq.c:1461
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_current_freq
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
**Symbols:**

```
ffffffff8184cd40-ffffffff8184cdc5: cpufreq_out_of_sync (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff8189005d)
Location: drivers/cpufreq/cpufreq.c:1625
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff818c225d)
Location: drivers/cpufreq/cpufreq.c:1639
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff8199496d)
Location: drivers/cpufreq/cpufreq.c:1656
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff819978bd)
Location: drivers/cpufreq/cpufreq.c:1661
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff8197c57d)
Location: drivers/cpufreq/cpufreq.c:1667
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff81a25820)
Location: drivers/cpufreq/cpufreq.c:1673
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff81b8ea98)
Location: drivers/cpufreq/cpufreq.c:1695
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff81d2ee08)
Location: drivers/cpufreq/cpufreq.c:1692
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff81d97f38)
Location: drivers/cpufreq/cpufreq.c:1699
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff81e4fbb8)
Location: drivers/cpufreq/cpufreq.c:1740
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffff800010b1eb5c)
Location: drivers/cpufreq/cpufreq.c:1639
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (c0bf90dc)
Location: drivers/cpufreq/cpufreq.c:1639
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (c000000000c11700)
Location: drivers/cpufreq/cpufreq.c:1639
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff8186697d)
Location: drivers/cpufreq/cpufreq.c:1639
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff8182f62d)
Location: drivers/cpufreq/cpufreq.c:1639
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff818b770d)
Location: drivers/cpufreq/cpufreq.c:1639
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
In drivers/cpufreq/cpufreq.c (ffffffff818d2d4d)
Location: drivers/cpufreq/cpufreq.c:1639
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
