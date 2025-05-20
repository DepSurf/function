# Function: <code>intel_pstate_prepare_request</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_pstate_prepare_request(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174ebd0)
Location: drivers/cpufreq/intel_pstate.c:1756
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
```
**Symbols:**

```
ffffffff8174ebd0-ffffffff8174ec88: intel_pstate_prepare_request (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff8176d35a)
Location: drivers/cpufreq/intel_pstate.c:1701
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e311a)
Location: drivers/cpufreq/intel_pstate.c:1478
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8182c536)
Location: drivers/cpufreq/intel_pstate.c:1657
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818589b6)
Location: drivers/cpufreq/intel_pstate.c:1720
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8189c127)
Location: drivers/cpufreq/intel_pstate.c:1746
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818ce417)
Location: drivers/cpufreq/intel_pstate.c:1792
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff819a0b87)
Location: drivers/cpufreq/intel_pstate.c:1800
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff819a3a53)
Location: drivers/cpufreq/intel_pstate.c:1948
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81988682)
Location: drivers/cpufreq/intel_pstate.c:1945
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81a32718)
Location: drivers/cpufreq/intel_pstate.c:2103
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81b9ec7d)
Location: drivers/cpufreq/intel_pstate.c:2272
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81d4024d)
Location: drivers/cpufreq/intel_pstate.c:2234
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81daadbd)
Location: drivers/cpufreq/intel_pstate.c:2264
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81e62edd)
Location: drivers/cpufreq/intel_pstate.c:2288
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81872017)
Location: drivers/cpufreq/intel_pstate.c:1792
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8183b9a4)
Location: drivers/cpufreq/intel_pstate.c:1792
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818c38c7)
Location: drivers/cpufreq/intel_pstate.c:1792
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818dfc37)
Location: drivers/cpufreq/intel_pstate.c:1792
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
